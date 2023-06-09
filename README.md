This repository provides a shared [dprint](dprint.dev) configuration for Kontent.ai repositories.

# How to use?

1) [Install dprint](https://dprint.dev/install/)
2) Create `dprint.json` file (usually in the root of your repository)
3) [Extend the `dprint.json` file](https://dprint.dev/config/#extending-a-different-configuration-file) from this repository. Add this property to your json to do that. `"extends": "https://raw.githubusercontent.com/kontent-ai/dprint-config/main/dprint.json"`
4) [Add `includes` and/or `excludes` properties](https://dprint.dev/config/#includes-and-excludes) to your `dprint.json` as needed, because the shared config cannot provide that.
5) Install dprint extension into your favourite IDE. https://dprint.dev/install/#editor-extensions

# How to check the formatting on CI with dprint?

There is a CLI command to do just that `dprint check`, but your can leverage [prepared scripts](https://dprint.dev/ci/) for GitHub Action or GitLab to do that for you.
