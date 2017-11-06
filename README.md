[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/googleads/gpt-light-ad)

# GPT Light Ad Polymer Element
Web Component wrapper for GPT Light library code using Polymer.

# Usage

1. Load the GPT Light library at the header of your root page:

```html
<script src='https://securepubads.g.doubleclick.net/static/glade.js' async></script>
```

2. Import and use the gpt-light-ad element inside any Web Component:

```html
<link rel="import" href="gpt-light-ad.html">
```
```html
<gpt-light-ad ad-slot-id="ad_slot_example" data-ad-unit-path="ad_unit_path" width='XXX' height='YYY'></gpt-light-ad>
```

# Known Limitations

In Single-page Apps (SPA), which reuse components between page visits (including gpt-light-ad), the corresponding ad slots won't be refreshed.

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
