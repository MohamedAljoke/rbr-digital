# RBR dashboard

dashboard front e back

## Cloning

Add the `--recurse-submodules` flag when cloning this repo to get the submodules

```
git clone https://github.com/MohamedAljoke/rbr-dashboard.git --recurse-submodules
```

### Init Submodules

If you did not clone with the flag `--recurse-submodules`, init the submodules with:

```sh
git submodule update --init --recursive
```

now to run the project just

```
docker-compose up -d
```
