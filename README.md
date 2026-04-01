# devops-supermodule

Supermodule repo to manage all DevOps repositories as Git submodules.

## Usage
```bash
# Clone with all submodules
git clone --recurse-submodules https://github.com/chirag-18bit/devops-supermodule.git

# Pull updates for all submodules
git pull --recurse-submodules

# Update all submodules to latest
git submodule foreach 'git pull origin main'
```
