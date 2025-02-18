# warpsign-ci 🚀

> CI workflow configurations for [warpsign](https://github.com/teflocarbon/warpsign)

## Overview

This repository contains GitHub Actions workflows for running warpsign in CI environments. Instead of maintaining a separate copy of warpsign that needs regular updates, this repository's workflows clone the latest version of warpsign directly from the main repository during each CI run.

## ⚡️ How It Works

1. When the workflow runs, it fetches the latest version of warpsign from the main repository
2. This ensures you're always using the most up-to-date version without manual updates
3. Simplifies maintenance and reduces version synchronization issues

## 🔧 Usage

Either fork (if you're okay with it being public) or press "Use this template" if you wish to have it private.

## ⚠️ Important Notes

- This repository contains only CI workflows - the main code lives in [warpsign](https://github.com/teflocarbon/warpsign)
- Issues are disabled - please report any issues in the [main repository](https://github.com/teflocarbon/warpsign/issues)

## 📝 License

This project is licensed under the same terms as the main warpsign repository.

## 🔗 Links

- [Main Repository](https://github.com/teflocarbon/warpsign)
- [Issue Tracker](https://github.com/teflocarbon/warpsign/issues)
