# minify
Minify .css, .js, .less with Line Macro and Gzip Minimized supported
## Usage
```sh
minify  FILENAME [-skip-macro] [-skip-less] [-skip-min] [-skip-gzip] [-skip-delete] [-outdir=output_dir]
```
* If minify .less file and output_dir not provided, script will try to use relative path ./../css/ as the output_dir
