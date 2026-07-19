# SekApp Stories

Static editorial article pages for the SekApp/OpenClaw AI team series.

## Production URL

https://medium.patkingdom.xyz/

## Structure

```text
public/
  index.html        # article index
  1/index.html      # บทที่ 1
  2/index.html      # บทที่ 2
  3/index.html      # บทที่ 3
  4/index.html      # บทที่ 4
  5/index.html      # บทที่ 5
```

## Local preview

```bash
cd public
python3 -m http.server 8088
# open http://localhost:8088/
```

## Deploy note

The production host serves `public/` as a static nginx site. All links and
assets are rooted at `/`, so the project can also be previewed locally:

```bash
cd public
python3 -m http.server 8088
```
