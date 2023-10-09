# NSCoder Night London Website

Files for generating the static site for NSCoder Night London.

- Generated using Hugo (Static site generator written in Go)
- Theme called Sam - imported as a submodule.

## Procedure

- Update content - This is from ox-hugo, so update the Content.org file
- Generate the markdown files with `C-c C-e H A`
- Generate the site `hugo --minify`.
- FTP the files to the web-server.