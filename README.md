<!-- tyhp-readme:start -->
# tyhpdef/guzzlehttp-uri-template

Tyhp type definitions for `guzzlehttp/uri-template` `2.0.1`.

```bash
composer require --dev tyhpdef/guzzlehttp-uri-template:2.0.1
```

This is a metapackage. Composer also installs `tyhpdef/guzzlehttp-uri-template-impl` (type files).
Require **this** name, not `tyhpdef/guzzlehttp-uri-template-impl`.

See https://tyhplang.com.

## Maintain `guzzlehttp/uri-template`? Ship the types yourself

If you are a Packagist maintainer of `guzzlehttp/uri-template`, you can take over these
types.

Copy `_tyhpdef/` from **`tyhpdef/guzzlehttp-uri-template-impl`** (Apache-2.0; keep the `NOTICE`).
Then either:

1. **Bundle** the files in `guzzlehttp/uri-template` and set `extra.tyhp.package` on
   that `composer.json`, plus
   `"replace": { "tyhpdef/guzzlehttp-uri-template": "self.version" }`, or
2. **Publish a sibling** types package under your vendor, versioned with
   `guzzlehttp/uri-template` (same `X.Y.Z`). Set `extra.tyhp.package` there,
   `require` `guzzlehttp/uri-template` with a real constraint,
   `"replace": { "tyhpdef/guzzlehttp-uri-template": "self.version" }`, and set
   `extra.tyhp.tyhpdef` on `guzzlehttp/uri-template` to your sibling’s Composer name.

Ship that to Packagist first, then open an issue:

https://github.com/tyhpproject/tyhp-runtime-src/issues/new?template=tyhpdef-ownership.yml

We verify Packagist ownership and that the types parse and cover the PHP
API, then stop publishing community tags for those versions. We do not
transfer the `tyhpdef/guzzlehttp-uri-template` Packagist name.

Full process: `TYHPDEF_OWNERSHIP.md` in
https://github.com/tyhpproject/tyhp-runtime-src
<!-- tyhp-readme:end -->
