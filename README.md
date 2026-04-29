# GSTT-archive
Archive of websites for general and set-theoretic topology and related fields

- [Ken Kunen](./kunen/)

## Dev

Use this command to mirror the website

```
wget --mirror --convert-links --adjust-extension --page-requisites --no-parent https://example.com/path/to/foldername/
```

then rename/move as necessary:

```
mv example.com/path/to/foldername .
rm -rf example.com
```

Run this command to preview the site

```
python -m http.server -d foldername
```
