# espanso-calc-macos
Basic calculation pacakge for epanso that works in MacOS.

## Example

https://user-images.githubusercontent.com/23709916/175306689-92b317f5-216d-4135-9278-dcbcb2d7f910.mov


## Usage
1. Type `:calc`
2. You'll see a form, type the calculation
  <img width="185" alt="image" src="https://user-images.githubusercontent.com/23709916/175305102-2453d39b-b7d8-45f2-8a42-9286a2ab2d25.png">
3. The text will be replaced with the result

## Commands

| Command                    | Match  | Example       | Result     |
|----------------------------|--------|---------------|------------|
| Calculate                  | :calc  | Input: 10 - 3 | 7          |
| Calculate and show account | :ecalc | Input: 10 - 3 | 10 - 3 = 7 |

## Implementation

This package uses `bc` to do the calculations
```
echo '10 * 4' | bc
```
