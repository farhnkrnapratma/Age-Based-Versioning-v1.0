# Age-based Versioning v1.0 Documentation

> **IMPORTANT NOTE**: Documentation and Age-based Versioning is deprecated due to major improvements to itself and its documentation. Please check the changelog when the latest version is released.
> Correspondence contact: [`farhnkrnapratma@gmail.com`](farhnkrnapratma@gmail.com)

## Introduction

Age-based versioning is determined based on the age of _something_ which increases incrementally every 1 month.

## Example (new concept)

**Sample case**: if you were born on `January 1, 2000`, your current age on `February 12, 2025`, will be `25` years and `2` months. So the form in Age-based Versioning is:

```
> v25.2                          # in the most concise form, or
> Self v25.2+01022025_01012000   # in full form | date format [DDMMYYYY]
```

The latest version will support release stages, for example cases: A software company x will launch their software on `May 25, 2025` and will go through several stages of release before becoming a `stable` version on `February 25, 2027`, the first `LTS` version on `May 25, 2028` and `EOL` for the first `LTS` version on `May 25, 2033`, example table:

| Release Stages            | Example Format        |
|------------------------|---------------------|
| **Pre-Alpha**         | `Self v4+25092025-prealpha.1` or `v4-prealpha.1`  |
| **Alpha**             | `Self v8+25012026-alpha.1` or `v8-alpha.1`     |
| **Beta**              | `Self v1.3+25082026-beta.1` or `v1.3-beta.1`      |
| **RC (Release Candidate)** | `Self v1.7+25122026-rc.1` or `v1.7-rc.1`     |
| **Stable (Final Release)** | `Self v1.9+25022027` or `v1.9`         |
| **LTS (Long-Term Support)** | `Self v3.0+25052028-lts` or `v3.0-lts`   |
| **EOL (End of Life)** | `Self v8.0+25052033-eol` or `v8.0-eol` |

**Another examples**:

| Release Stages            | Example Format        |
|------------------------|---------------------|
| **Nightly Build**     | `Self v9+25022026-nightly.01032026` or `v9-nightly.01032026` |
| **Canary Build**      | `Self v10+25032026-canary.3` or `v10-canary.3`    |
| **Dev (Development Build)** | `Self v11+25042026-dev.4` or `v11-dev.4` |
| **Preview / Insider** | `Self v1.0+25052026-preview.5` or `v1.0-preview.5`   |
| **ESR (Extended Support Release)** | `Self v12.0+25052037-esr` or `v12.0-esr` |
| **GA (General Availability)** | `Self v1.9+25022027-ga` or `v1.9-ga` |

## Documentation [🗑️deprecated]

You can read the full documentation [`here`](./docs/selfvdocs_v1.0.pdf) or download the documentation [`here`](https://github.com/farhnkrnapratma/selfv/releases/tag/v1.0).

## License Notice

This document and the ideas contained within it are licensed under the **Creative Commons Attribution-NoDerivatives-NonCommercial 4.0 International License**. This means you are free to share (copy and redistribute the material in any medium or format) as long as you provide appropriate credit. However, you may not modify, adapt, or create derivative works based on this material, nor use it for commercial purposes. 

For full license details, visit: [https://creativecommons.org/licenses/by-nc-nd/4.0/](https://creativecommons.org/licenses/by-nc-nd/4.0/). 

The age-based versioning system itself is free to use and implement by anyone. However, this document and its explanation are protected under the aforementioned license.
