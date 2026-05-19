# cookiecutter-3ds-homebrew

This is a 3DS Homebrew Project Template

A modern C++ CMake template for Nintendo 3DS homebrew using devkitpro. Output supports `.3dsx` and `.cci`.

All other templates are either outdated (3ds itself is outdated I know) or scattered (some are cmake but not cpp and so on...), so this template ensures

1. Only Hello World with romfs and banners
2. Uses C++
3. Uses CMake

## Usage

1. Install cookiecutter:

```bash
uv tool install cookiecutter
```

or using system pip if you prefer

```bash
pip install cookiecutter
```

or any other package manager you prefer.

2. Generate a new project:

```bash
cookiecutter /path/to/cookiecutter-3ds
```

3. Follow the terminal prompts to configure your project.

# Special Thanks

This template would have been impossible without the awesome templates made by the community over the years, not to mention my cmake skills...

- Most upto date cmake [template](https://github.com/Xtansia/3ds-cmake) by [Xtansia](https://github.com/Xtansia), but it lacked romfs support
- This RSF [Template](https://gist.github.com/jakcron/9f9f02ffd94d98a72632)
- All the awesome work done by the homebrew community, the devkitpro project and various build tools made by the people.
