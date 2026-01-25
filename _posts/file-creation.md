# Cool Bash Command

I recommend executing the following line of code when creating your Markdown files. Name them whatever you want but Jekyll requires a specific format with a date.

This will add a date to the start of every file in your current directory. Switch out the date for whenever Warpcon falls for convenience.

```for f in *; do mv "$f" "2026-01-30_$f"; done```
