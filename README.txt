# Universal Climate Houses

A simple NewGRF to enable vanilla temperate/arctic/sub-tropic houses on other climates. It also allows Temperate houses and all flats to also accept Food. Does not include additional artwork.

## Features

- Allow mixing various climates together.
- Reasonable extended cargo support (generally, all flats accept both foods and goods, Temperate houses accept food, all Toyland shops and offices accept both fizzy drinks and candy) utilizing the 16 cargo I/O feature.
- Allow either a sensible subselection or all combinations of vanilla and NewCC color gradients on both company and structure remap to bypass TTD 4-color-variations limit where possible.
- External parameter over stadium and church count.
- Optionally protect multicell buildings inside inner town zones from town autoreplacement to prevent them being heavily underrepresented in an ongoing game.
- Options to control how Hotels should handle Tourists, inspired by old TTRS behaviour (requires an external cargo NewGRF with Tourists).

## License

GPL v2

## Contributions

EmperorJake: NewCC gradients

PikkaBird: inspiration from Suburban Renewal Houses

2TallTyler: misc. subroutine examples

## Author

Graion Dilach

## Changelog

### v4 changelog

- Feature: Incorporate both vanilla and NewCC color gradients among random colorations, regardless of NewCC. Also consider green a sensible structure color.
- Feature: Add an option to allow multicell buildings to be protected against town renewal.
- Bugfix/feature: Fix behaviour on Toyland - Toyland is also redefined to benefit from the additional gradients and to allow all office blocks to accept both Sweets and Fizzy Drink.
- Bugfix: Restore missing tall office block variants.
- Tweak: Tie unlimited church/stadium counts to town population.

### v3 changelog

- Bugfix: Revert a tall office block recolor because it looks corrupted on OpenGFX.
- Bugfix: revert overdelayed Subtropic building introduction dates.
- Bugfix: Fix selected Arctic buildings ending up with confused building sprites.
- Bugfix/feature: Properly introduced the unlimited Tourist Hotels.

### v2 changelog

- Feature: Parametrize church/stadium limits.
- Feature: Introduce a "Sensible" setting to random colors.
- Feature: Refine Hotel-Tourist interaction options via introducing city limits.
- Bugfix: Fix large office block #1 ground sprite and restore the lift.
- Bugfix: Readd a missed tall office block variant.
- Bugfix: Fix house #3 snowed roof on OpenGFX2 8bpp.
- Bugfix: Fix arctic hotel sprite miscount.
- Bugfix: Disable temperate hotel remap because it only works with selected base sets.

### v1 changelog

- Initial release
