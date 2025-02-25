# test_datasets

Test data used in github actions for stjudecab's bioinformatics pipelines

## Introduction

This repository serves as a centralized testing datasets for our `stjudecab`'s Nextflow-based bioinformatics pipelines.
Each branch is dedicated to a specific pipeline, containing all necessary files for comprehensive testing
and infrastructure validation (e.g., `conda`, `docker` and `singularity`).

## Optimizing cloning

Due to the large size of test datasets, we recommend cloning only the specific branch(es) you need:

```bash
# Clone a single pipeline branch
git clone <url> --single-branch --branch <pipeline/branch_name>
```

To add another pipeline branch to your local repository later:

```bash
git remote set-branches --add origin <remote-branch>
git fetch
git checkout <remote-branch>
```

## Support

If you encounter any issues or have questions about testing specific pipelines,
please submit an issue through our [GitHub Issues page](https://github.com/stjudecab/test_datasets/issues).

## Contributing

To contribute new test datasets or improve existing tests,
please follow our standard pull request process targeting the appropriate pipeline branch.
