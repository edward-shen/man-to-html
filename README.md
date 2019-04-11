# man-to-html

Opinionated man page (roff) to html converter.

### Usage
Here's how [my man page](https://man.eddie.sh) is created:
```bash
./man-to-html edward-shen.man index.html edward-shen "Edward Shen Manual"
```

You can also specify version number, page number, and date:
```bash
./man-to-html edward-shen.man index.html edward-shen "Edward Shen Manual" 4.2.0 1 "January 1st, 1970"
```

### Prereqs

- `pandoc`



