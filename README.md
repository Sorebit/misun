# Misun: A theme for Pelican

Misun is a [Pelican][pel] theme designed for 
[sorebit.github.io][sgi]. It aims for high readability, accessibility and light design.

For this theme to work the plugins are *required*.

## Dependencies 

- `python -m pip install libsass cssmin` or use [requirements.txt][req] from [sorebit.github.io][sgi]

## Notes

- The theme is in by means *complete*. It supports only what I needed to style.
- For example, only `h1`, `h2`, and `h3` headers are expected to be used as *actual headers*.
`h4` and below might be used in the future for additional functionalities (like bi-links)
- In article preview (`.preview`), summary is expected to **not** be auto-generated. That is, the
theme is **not** going to handle any non-plain text.


[pel]: https://github.com/getpelican/pelican
[req]: https://github.com/Sorebit/sorebit.github.io/blob/main/requirements.txt
[sgi]: https://sorebit.github.io
