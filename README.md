# What's this?

This is a template project for c++ using cmake and conan as a package manager to include libraries.

# Setup

After cloning this repository delete the remote and set a new remote to your new project repository. Create a build directory and run cmake.

```sh
git remote remove origin
git remote add origin .../project.git
git push origin master -u
```

If you have tools, that use the `compile-commands.json` file, link it from the build directory to the project root.
