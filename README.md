# Legacy Frontend Themes for OpenMage

This repo contains the app/design/frontend/default legacy themes for OpenMage/M1.

Please remember that, since symlinks are not allowed in the themes folder structure, you'll have to add

```
"extra": {
    "magento-deploystrategy-overwrite": {
        "openmage/legacy-frontend-themes": "copy"
    },
}
```

to your composer.json file.
