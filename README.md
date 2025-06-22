# ![brand-assets](https://github.com/Synergy-Engine/brand-assets/blob/main/assets/repository-headers/asset%20repo%20header.png?raw=true)

[![License](https://img.shields.io/github/license/Synergy-Engine/brand-assets?style=flat)](https://github.com/Synergy-Engine/brand-assets/blob/main/LICENSE)

This repository is the central hub for all the brand assets used by the Synergy Engine.


## Why do we need this?

* **Consistency**: Maintain a unified and professional look across all platforms and channels.
* **Ease of use**: Everything is stored in one place, so you don't have to dig around.
* **Clarity**: Define clear guidelines for cohesion.
* **Collaboration**: Enable efficient collaboration for all community members.
* **Reusability**: Encourage reuse of assets across projects.


## What's inside?

This is everything you'll find in this repository:

* [**Logos**](#logos): All the variants of the Synergy Engine logo for different use cases.
* [**GitHub Social Cards**](#other-assets): Social media cards for GitHub repositories.
* [**Repository Headers**](#other-assets): Headers for GitHub repositories.
* [**Brand Elements**](#brand-elements): Defined color palettes and typography.
* [**Usage Guidelines**](#usage-guidelines): Recommended usage patterns and best practices.

### Logos

There are *a lot* of variants of the logo, so you can find the one that best suits your needs in the [`assets/logos`](https://github.com/Synergy-Engine/brand-assets/tree/main/assets/logos) folder. The file structure is a mess, but it's a pain to organize and rename everything, since I'm auto-exporting from Figma. Sorry, not sorry.

#### Variants

* `{color}`: The main color: `black`, `white`, or `primary`.
    * If it's `primary`, it'll be further divided into: `light` (orange), `dark` (teal), and `grey` (purple).
* `[{gradient}]`: present if filling is a gradient.
* `[{gradient_radial}]`: present if filling is a radial gradient.
* `[{inner_shadow}]`: present if there's an inner shadow.
* `[{circle}]`: present if there's a circle encasing the logo.
* `[{padding}]`: present if the logo has padding (meaning they have 8px of space around it).
* `{size}`: Only for `png` files (`48` or `512` pixels). SVGs scale perfectly, so size isn't in their name.
* `{format}`: `svg` (preferred) or `png`.

#### Naming Convention

Do yourself a favor and use GitHub's search bar instead of navigating through the folder structure. This is the naming convention:

`synergy_logo_{color}_[{gradient}]_[{gradient_radial}]_[{inner_shadow}]_[{circle}]_[{padding}]-{size}.{format}`

**Example Searches**:

* Need a scalable white logo with a circle and padding? Search for `synergy_logo_white_circle_padding.svg`.
* Looking for a teal gradient logo, no circle, 512px PNG? Try `synergy_logo_primary_dark_gradient-512.png`.

### Other Assets

* **GitHub Social Cards**: Social media cards for GitHub repositories. Can be found in [`assets/github-social-cards`](https://github.com/Synergy-Engine/brand-assets/tree/main/assets/github-social-cards).
* **Repository Headers**: Headers for GitHub repositories. Can be found in [`assets/repository-headers`](https://github.com/Synergy-Engine/brand-assets/tree/main/assets/repository-headers).

### Brand Elements

#### Colors

Synergy has three primary colors, one for every theme:

| Theme | Color | Hex | RGB | HSL |
| --- | --- | --- | --- | --- |
| Dark | Teal | `#117474` | `(17, 116, 116)` | `(180, 100%, 26%)` |
| Light | Orange | `#D46A2E` | `(212, 106, 46)` | `(22, 66%, 51%)` |
| Grey | Purple | `#4D22A7` | `(77, 34, 167)` | `(259, 66%, 39%)` |

#### Typography

* For headings, text and basically everything else, we use the [Inter](https://fonts.google.com/specimen/Inter) font.
* For code, we use the [IBM Plex Mono](https://fonts.google.com/specimen/IBM+Plex+Mono) font.

### Usage Guidelines

These are some recommendations and best practices to help you use the assets in a consistent and professional way. Of course, these are just recommendations, and you're free to use them in any way you see fit. You are only obligated to follow the license, but not the guidelines.

* Keep the aspect ratio of the logo at 1:1.
* Only alter colors or add effects to the logo if you need to.
* Ensure that there is sufficient clear space around the logo.
* Don't shrink the logo too much, so it stays legible.
* Attribution is appreciated (e.g., "Powered by Synergy Engine" or a link back to our main GitHub repo).


## Contributing

Whatever this is has a LOT of room for improvement, so here are some of the things you can do if you're interested in helping out:

* **Request or create a new asset**: If you need an asset that isn't here, please [open a new issue using the "New Asset Request" template](https://github.com/Synergy-Engine/brand-assets/issues/new?template=new-asset-request.md).
* **Suggest or implement an improvement/revision**: If you see an existing asset that could be improved, please [open an issue using the "Asset Improvement/Revision" template](https://github.com/Synergy-Engine/brand-assets/issues/new?template=asset-improvement-revision.md).
* **Ask a question about guidelines**: For any questions or suggestions related to the usage guidelines, please [open an issue using the "Usage Guidelines Clarification" template](https://github.com/Synergy-Engine/brand-assets/issues/new?template=usage-guidelines-clarification.md).


## License

This repository is released under the [Apache-2.0](https://github.com/Synergy-Engine/brand-assets/blob/main/LICENSE) license.
