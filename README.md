# man-to-html

Opinionated man page (roff) to html converter.

### Usage
Here's how [my man page](https://man.eddie.sh) is created:
```bash
./man-to-html edward-shen.man index.html
```

This script will automatically fetch in metadata information from the
man page. Specifically, it'll parse the first line:

```roff
.TH cmd-name page date version title
```

This might not work and will likely break if the man page's first line
isn't in that exact format.

### Prereqs

Install `pandoc`.



