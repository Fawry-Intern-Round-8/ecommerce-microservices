# ecommerce-microservices

To clone the repository **with all submodules**, use:
```bash
git clone --recurse-submodules https://github.com/Fawry-Intern-Round-8/ecommerce-microservices.git
```
> If you already cloned the repo without `--recurse-submodules`, you can initialize the submodules manually:
```bash
git submodule update --init --recursive
```

To make sure all submodules are up to date with their latest commits from their respective repositories:

```bash
git submodule update --recursive --merge --remote
```
This pulls the latest changes from each submodule’s remote branch (usually `main`).

