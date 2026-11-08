# Proton AI Core Vision+ documentation

Source of the documentation site at [docs.protonverse.io](https://docs.protonverse.io), built with [Mintlify](https://mintlify.com).

The content is derived from, and verified against, the hardware and firmware repository: [Protonverse-Labs/proton-ai-core-vision-plus](https://github.com/Protonverse-Labs/proton-ai-core-vision-plus) (firmware V20). When the hardware or firmware changes, update the matching pages here. If a statement here cannot be backed by that repository, it should not be on the site.

## Structure

- `docs.json`: site configuration and navigation
- `introduction.mdx`, `getting-started/`, `hardware/`, `setup/`, `guides/`, `resources/`: the pages
- `images/`, `logo/`, `favicon.png`: assets

## Preview locally

```bash
npm i -g mint
mint dev
```

Validate before pushing:

```bash
mint validate
mint broken-links
```

Every push to `main` deploys the site.

## Licence

Documentation is licensed under CERN-OHL-P v2 (permissive), the same as the documentation in the hardware repository. See [LICENSE](LICENSE). "Protonverse", "Protonverse Labs" and "Proton AI Core" are trademarks and are not licensed under it.
