# Digit Guesser

Machine learning from the browser; served from the Internet Computer Blockchain.

**Live Demo**: https://avtg3-4iaaa-aaaal-ajqhq-cai.icp0.io/

## Description

This website is powered by [pyodide](https://pyodide.org/en/stable/). The site uses a slightly modified version of the SVM classifier from the [sklearn docs](https://scikit-learn.org/stable/auto_examples/classification/plot_digits_classification) to predict a digit drawn by a site visitor.

For details on how to model was trained and exported, see [train_model.ipynb](train_model.ipynb).

## Project setup

```bash
pnpm install
```

### Compiles and hot-reloads for development

```bash
pnpm run serve
```

### Compiles and minifies for production

```bash
pnpm run build
```
