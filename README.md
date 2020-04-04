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
|**Code Block**|**Some Larger Code Block**|**Some Inline Math**|
|<img src="./previews/minimal/png/slides.013.png" width="200"/>|<img src="./previews/minimal/png/slides.014.png" width="200"/>|<img src="./previews/minimal/png/slides.015.png" width="200"/>|
|Some Math Blocks|**Background Image**|**Split Background (Right)**|
|<img src="./previews/minimal/png/slides.016.png" width="200"/>|<img src="./previews/minimal/png/slides.017.png" width="200"/>|<img src="./previews/minimal/png/slides.018.png" width="200"/>|
|**Split Background (Left)**|**Split Background (Right Scaled)**|**Multiple Background**|
|<img src="./previews/minimal/png/slides.019.png" width="200"/>|<img src="./previews/minimal/png/slides.020.png" width="200"/>|<img src="./previews/minimal/png/slides.021.png" width="200"/>|