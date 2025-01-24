# Monorepo Collection

Welcome to the **Monorepo Collection** of the Computer Engineering MS!
This repository serves as an aggregate of all the repositories within the organization, but it is not meant for direct development.

## What is this repository?
This repository contains submodules that point to the latest commits of each individual course repository.
It functions like a "monorepo" but without merging all the code into a single repository.
This allows us to manage multiple repositories under a common structure while keeping the individual repositories independent.

### How to sync submodules
To make sure you're working with the most up-to-date version of the submodules in this repo, run the following commands:
```bash
git submodule update --init --recursive
```

## How to contribute?

### Adding material
If you're planning to contribute to any of the projects to add your notes or useful material:

1. **Find the corresponding repository**: Each project is stored as a submodule here, pointing to the latest commit. To contribute, you should navigate to the **original repository** (not this one).
   
2. **Open your pull request there**: All pull requests should be opened on the respective repository where the code resides.

> [!NOTE]
> If you notice that some of the material is (really) outdated, maybe because the course has been re-organized or a new professor teaches it, we would probably create a new repo for the course.

### Missing courses
If some course is missing open a new issue on this monorepo.
