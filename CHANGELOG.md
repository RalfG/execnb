# Release notes

<!-- do not remove -->

## 0.1.4


### Bugs Squashed

- `CaptureShell.shell` sets `cell.outputs` to ordinary dicts instead of `AttrDict`s ([#39](https://github.com/fastai/execnb/pull/39)), thanks to [@seeM](https://github.com/seeM)


## 0.1.3

### New Features

- Add `DummyHistory` ([#38](https://github.com/fastai/execnb/issues/38))

### Bugs Squashed

- `nbdev_test` fails due to unescaped backslash in windows path ([#37](https://github.com/fastai/execnb/issues/37))


## 0.1.2

### New Features

- Only write file if changed in `write_nb` ([#35](https://github.com/fastai/execnb/issues/35))
- faster startup with `MPLBACKEND` environment variable to lazily set matplotlib backend ([#33](https://github.com/fastai/execnb/pull/33)), thanks to [@seeM](https://github.com/seeM)


## 0.1.1

### New Features

- Support `ipywidgets` ([#24](https://github.com/fastai/execnb/issues/24))

### Bugs Squashed

- Seaborn is not compatible with execnb ([#27](https://github.com/fastai/execnb/issues/27))


## 0.1.0

### New Features

- Remove usage of fastcore.xtras and fastcore.foundation to reduce chance of macOS fork issue ([#26](https://github.com/fastai/execnb/issues/26))


## 0.0.10

### New Features

- add `mk_cell` ([#25](https://github.com/fastai/execnb/issues/25))
- Add new nb function ([#23](https://github.com/fastai/execnb/pull/23)), thanks to [@dleen](https://github.com/dleen)
- Parameterize Notebooks ([#19](https://github.com/fastai/execnb/issues/19))
  - (This was completed earlier but not marked done in gh issues)


## 0.0.9

### New Features

- use fork mode on mac ([#22](https://github.com/fastai/execnb/issues/22))


## 0.0.8

- Use nbdev2


## 0.0.6

### Bugs Squashed

- do not fail if matplotlib is not installed when running  `%matplotlib inline` ([#6](https://github.com/fastai/execnb/pull/6)), thanks to [@hamelsmu](https://github.com/hamelsmu)


## 0.0.3

- Add notebook dir to python path


## 0.0.2

- Compat with nbdev test runner


## 0.0.1

- Initial release

