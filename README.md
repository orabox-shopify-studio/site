# OraBox Shopify Studio — site

Public marketing + privacy pages for [orabox-shopify-studio](https://github.com/orabox-shopify-studio).

```
public/
  index.html
  apps/<slug>/
  privacy/<slug>/
```

Deploy from studio:

```bash
cd ../studio
cp .env.example .env   # once
./scripts/deploy-site-tree.sh
```
