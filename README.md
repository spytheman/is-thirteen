# is thirteen

Check if a number is equal to 13. Inspired from this [Go Module](https://github.com/stanleynguyen/is-thirteen).

## Installation

- Manually:
  - `git clone https://github.com/Delta456/is-thirteen is_thirteen`

- Via VPM
   - `v install is_thirteen`

- Via Vpkg
   - `vpkg install is_thirteen`

## Usage

```v
import is_thirteen as is

fn main() {
	is.number(13).thirteen()               // true
	is.number(12.8).roughly.thirteen()     // true
	is.number(6).within(10).of.thirteen()  // true

	// Check your math skillz
	is.number(4).plus(5).thirteen()     // false
	is.number(12).plus(1).thirteen()    // true
	is.number(4).minus(12).thirteen()   // false
	is.number(14).minus(1).thirteen()   // true
	is.number(1).times(8).thirteen()    // false
	is.number(26).divides(2).thirteen() // true

	// Check your spelling and chemistry skillz
	is.str("tHirTeEn").thirteen()  // true
	is.str("neetriht").backwards.thirteen()  // true
	is.str("aLumInUm").atomic_number.thirteen() // true
}
```

## License

Released under [MIT](LICENSE).
