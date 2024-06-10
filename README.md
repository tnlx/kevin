# Kevin

A Hugo theme to create a minimalistic web curriculum-vitae.

By default, it reads from `cv.*` in Hugo `/data` directory.

## Installation

```toml
# config.toml
theme = 'github.com/tnlx/kevin'
```

## Configuration

Place a cv.{toml,yml,json} in data directory. This example cv.toml can be used to get started:

```sh
curl "https://raw.githubusercontent.com/tnlx/kevin/data/cv.toml" > data/cv.toml
```

Optionally, customize the theme's parameters:

```toml
[Params.Kevin]
CvSource = "" # The name of the cv file, default to 'cv'
Sections = ['Experience', 'Project', 'Certificate', 'Education', 'Skill'] # Section names and order
Footer = "" # Footer text
```