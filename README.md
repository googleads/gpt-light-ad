# Glade Ad Polymer Element
Web Component wrapper for Glade library code using Polymer.

# Usage

1. Load the Glade library at the header of your root page:

```html
<script src='https://securepubads.g.doubleclick.net/static/glade.js' async></script>
```

2. Import and use the gpt-ad element inside any Web Component:

```html
<link rel="import" href="glade-ad.html">
```
```html
<glade-ad ad-slot-id="ad_slot_example" data-ad-unit-path="ad_unit_path" width='XXX' height='YYY'></glade-ad>
```

# Known Limitations

In Single-page Apps (SPA), which reuse components between page visits (including glade-ad), the corresponding ad slots won't be refreshed.

## License

Copyright 2017 Google, Inc.

Licensed under the [Apache License, Version 2.0](LICENSE) (the "License");
you may not use this file except in compliance with the License. You may
obtain a copy of the License at

  http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.