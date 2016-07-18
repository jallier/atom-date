# Atom Date-Plus Package

Based on the [package by dannyfritz](https://github.com/dannyfritz/atom-date). Insert the current date & time, with optional
additional padding.

## Installation

```sh
apm install date-plus
```
or find it in the Packages tab under settings

## Usage

Select a command from `Packages`, `date-plus:Date & Time`.

You can also bind your keys to `date-plus:date`, `date-plus:time` and `date-plus:datetime`.

# Options

You can specify the following options for the date and time format:

- YYYY - Four digit year
- MMMM - Full month name. ie January
- MMM  - Short month name. ie Jan
- MM   - Zero padded month ie 01
- M    - Month ie 1
- DDDD - Full day or week name ie Tuesday
- DDD  - Abbreviated day of the week ie Tue
- DD   - Zero padded day ie 08
- D    - Day ie 8
- HH24 - Hours in 24 notation ie 18
- HH   - Padded Hours ie 06
- H    - Hours ie 6
- MI   - Padded Minutes
- SS   - Padded Seconds
- PP   - AM or PM
- P    - am or pm

Checking the 'match line length' option for pre/post padding will match the
length of the date inserted with the first character of the padding string.
eg

18/07/16

becomes (using # for example)
<p>
#######<br>
18/07/16<br>
#######
</p>
