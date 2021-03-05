# Technical drawings

Osifont is provided under GPL by `hikikomori82@gmail.com`.

My `sty` files are licensed under GPL as well. Feel free to use them.

## Dimline
The `din-dimline` package is adapted from `tikz-dimline`, provided under WTFPL by Sébastien Gross.

`din-dimline` is explicitely **not** compatible with `pgfplots`.

## Screws

### Button head screw
Due to technical limitations, this is still drawn according to DIN 7045:
In DIN 7045, it was always rf = 2*dk, so the angle of the button was always 60°. 

With the new norm however, rf is a bit smaller, so the angle has to be calculated for every screw. For now, I can't find a way to do this with tikz.
