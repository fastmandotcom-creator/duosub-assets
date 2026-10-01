# duosub-assets

Data-only mirror for the DuoSub extension. No JavaScript and no WebAssembly.

Clients must fetch `https://duosub.study/ext-assets/<path>` (Cloudflare in front of this repo). Do not point the extension at `raw.githubusercontent.com` — that host is blocked in mainland China.

Tag `v1` is the immutable set the extension zip expects.
