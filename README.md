# Vulkan-Headers packaged for zig

This is a fork of [vulkan-headers](https://github.com/KhronosGroup/Vulkan-Headers), packaged for Zig. Unnecessary files have been deleted, and the build system has been replaced with build.zig.

## Updating

To update this repository, run `./update.sh` followed by `./verify.sh` to verify the repository contents.

## Verifying repository contents

For supply chain security reasons (e.g. to confirm we made no patches to the code) we provide a `git diff` command you can run to verify the contents of this repository:

```sh
./verify.sh
```

If nothing is printed, there is no diff. Deleted files, and changes to `README.md`, `build.zig`, `.github` CI files and `.gitignore` are ignored.
