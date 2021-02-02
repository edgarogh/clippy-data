# clippy-data

> Data for [edgarogh/clippy-api](https://github.com/edgarogh/clippy-api)

## File format

All quote/proverb files are in txt format.

The first line is a [SPDX license ID](https://spdx.org/licenses/), optionally followed by a space character the author's name if applicable. `CC0-1.0` or `WTFPL` can be used for (near) public domain.

The following lines contain quotes:
  * One per line
  * (Hash)Tags can be set at the end of the line with the `#` character followed by an alphanumeric(+hyphen+underscore) string of characters (diacritics and non-latin characters should be allowed), and separated with spaces
  * Double slashes `//` denote a line comment. They're treated as "nothing", as if they weren't here.
  * Double backslashes `\\` denote line breaks
  * A line can be attributed to somebody by suffix-ing it with any non-line-break whitespace, a `–` (en dash) character or `--` (double hyphen), another non-LB whitespace and the person/entity to attribute the quote to

Empty lines and lines containing only whitespaces are ignored.

In the end, all files will be merged and treated as one big list of quotes/proverbs.

### Example

```
CC-BY-4.0 Edgar Onghena

// First batch of quotes
It is better to have serious friends than non-serious friends. #friends #social
Instead of making fun of people, stop making fun of them. -- Gandhi #social
```

## License

  * This README.md is dual-licensed under CC0 and WTFPL.
  * The text files, as you might guess, are licensed under the license ID specified on their first line, for the author specified after, when applicable.
