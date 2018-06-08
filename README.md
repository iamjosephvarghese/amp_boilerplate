# amp_boilerplate

* Start with `<!doctype html>`
* Should have `<html amp>` tag at the top
* Should have `<head>` and `<body>` tags
* Should have `<meta charset="utf-8">` tag as the first child of the `<head>` tag
* Shoul have `<script async src="https://cdn.ampproject.org/v0.js"></script>` tag as the second child of their `<head>` tag
* `<meta name="viewport" content="width=device-width,minimum-scale=1">`
* Should contain `<link rel="canonical" href="$SOME_URL">` tag inside `<head>`. This is used to  point to the regular HTML document.

## Running on localhost

Run `python -m SimpleHTTPServer` from the folder which you need to serve on localhost
