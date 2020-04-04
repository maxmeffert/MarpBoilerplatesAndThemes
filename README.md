# MarpBoilerplatesAndThemes
Repository for [Marp](https://marp.app) Boilderplates and Themes

##  Build

```
npm run build-all
```

---

## Minimal

A minimalistic black & white theme.

### Download

[minimal.css](./themes/minimal.css)

### Usage

#### CLI

```
npx marp --theme minimal.css presentation.md
```

#### Marp for VS Code

```
---
marp: true
theme: diabolo
---
```

```json
// Please put `.vscode/settings.json` on your workspace
{
  "markdown.marp.themes": [
    "./path/to/minimal.css"
  ]
}
```

### Preview

|**Title**|**Headings**|**Itemization**|
|:-:|:-:|:-:|
|<img src="./previews/minimal/png/slides.001.png" width="200"/>|<img src="./previews/minimal/png/slides.002.png" width="200"/>|<img src="./previews/minimal/png/slides.003.png" width="200"/>|
|**Grouped Itemization**|**Enumeration**|**Grouped Enumeration**|
|<img src="./previews/minimal/png/slides.004.png" width="200"/>|<img src="./previews/minimal/png/slides.005.png" width="200"/>|<img src="./previews/minimal/png/slides.006.png" width="200"/>|
|**Mixed List**|**Hyperlink**|**Image**|
|<img src="./previews/minimal/png/slides.007.png" width="200"/>|<img src="./previews/minimal/png/slides.008.png" width="200"/>|<img src="./previews/minimal/png/slides.009.png" width="200"/>|
|**Blockquote**|**Table**|**Inline Code**|
|<img src="./previews/minimal/png/slides.010.png" width="200"/>|<img src="./previews/minimal/png/slides.011.png" width="200"/>|<img src="./previews/minimal/png/slides.012.png" width="200"/>|
|**Code Block**|||
|<img src="./previews/minimal/png/slides.013.png" width="200"/>|||


## Diabolo

**!!!Work in progress!!!**
I just added this to test some template derivation...

### Download

[diabolo.css](./themes/diabolo.css)

### Usage

#### CLI

```
npx marp --theme diabolo.css presentation.md
```

#### Marp for VS Code

```
---
marp: true
theme: diabolo
---
```

```json
// Please put `.vscode/settings.json` on your workspace
{
  "markdown.marp.themes": [
    "./path/to/diabolo.css"
  ]
}
```

### Preview

|**Title**|**Headings**|**Itemization**|
|:-:|:-:|:-:|
|<img src="./previews/diabolo/png/slides.001.png" width="200"/>|<img src="./previews/diabolo/png/slides.002.png" width="200"/>|<img src="./previews/diabolo/png/slides.003.png" width="200"/>|
|**Enumeration**|**Hyperlink**|**Image**|
|<img src="./previews/diabolo/png/slides.004.png" width="200"/>|<img src="./previews/diabolo/png/slides.005.png" width="200"/>|<img src="./previews/diabolo/png/slides.006.png" width="200"/>|
|**Blockquote**|**Table**|**Inline Code**|
|<img src="./previews/diabolo/png/slides.007.png" width="200"/>|<img src="./previews/diabolo/png/slides.008.png" width="200"/>|<img src="./previews/diabolo/png/slides.009.png" width="200"/>|
|**Code Block**|||
|<img src="./previews/diabolo/png/slides.010.png" width="200"/>||