# WWW Live

Web root of [www.antenna2.net](https://www.antenna2.net/)

Each sub folder in the site is its own repo, this repo's .gitignore ignores the sub repos.

Example, /cebik is a sub repo that is excluded from this repo in .gitignore.

rsync with `--exclude-from='scripts/rsync-exclude.txt'` is used to exclude .git/ .gitignore etc when syncing changes to the webhost (which supports using rsync). See [rsync-exclude.txt](https://github.com/lonney9/HTML-Scripts/blob/main/rsync-exclude.txt) in the scripts repo.

## Favicon and Apple Touch Icon

[https://favicon.io/emoji-favicons/satellite-antenna/](https://favicon.io/emoji-favicons/satellite-antenna/)

## Sitemap.xml

Current [www.antenna2.net/sitemap.xml](https://www.antenna2.net/sitemap.xml) has been manually uploaded Dec/18/2024.

## Sitemap.xml Generator

Sitemap.xml generator script: [50-sitemap.sh](https://github.com/lonney9/HTML-Scripts/blob/main/50-sitemap.sh).
