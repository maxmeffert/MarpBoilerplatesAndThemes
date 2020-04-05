# MarpMe
Repository for [Marp](https://marp.app) Boilderplates and Themes

##  Build

```
yarn build
```

---

## Minimal Theme

A minimalistic black & white theme.

### Download

[minimal.css](./themes/minimal/minimal.css)

### Usage

#### CLI

```
npx marp --theme minimal.css presentation.md
```

#### Marp for VS Code

```
---
marp: true
theme: minimal
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

* [PDF](./themes/minimal/previews/pdf/slides.pdf)
* [HTML](./themes/minimal/previews/html/slides.html)

|**Title**|**Headings**|**Itemization**|
|:-:|:-:|:-:|
|<img src="./themes/minimal/previews/png/slides.001.png" width="200"/>|<img src="./themes/minimal/previews/png/slides.002.png" width="200"/>|<img src="./themes/minimal/previews/png/slides.003.png" width="200"/>|
|**Grouped Itemization**|**Enumeration**|**Grouped Enumeration**|
|<img src="./themes/minimal/previews/png/slides.004.png" width="200"/>|<img src="./themes/minimal/previews/png/slides.005.png" width="200"/>|<img src="./themes/minimal/previews/png/slides.006.png" width="200"/>|
|**Mixed List**|**Hyperlink**|**Image**|
|<img src="./themes/minimal/previews/png/slides.007.png" width="200"/>|<img src="./themes/minimal/previews/png/slides.008.png" width="200"/>|<img src="./themes/minimal/previews/png/slides.009.png" width="200"/>|
|**Blockquote**|**Table**|**Inline Code**|
|<img src="./themes/minimal/previews/png/slides.010.png" width="200"/>|<img src="./themes/minimal/previews/png/slides.011.png" width="200"/>|<img src="./themes/minimal/previews/png/slides.012.png" width="200"/>|
|**Code Block**|**Some Larger Code Block**|**Some Inline Math**|
|<img src="./themes/minimal/previews/png/slides.013.png" width="200"/>|<img src="./themes/minimal/previews/png/slides.014.png" width="200"/>|<img src="./themes/minimal/previews/png/slides.015.png" width="200"/>|
|Some Math Blocks|**Background Image**|**Split Background (Right)**|
|<img src="./themes/minimal/previews/png/slides.016.png" width="200"/>|<img src="./themes/minimal/previews/png/slides.017.png" width="200"/>|<img src="./themes/minimal/previews/png/slides.018.png" width="200"/>|
|**Split Background (Left)**|**Split Background (Right Scaled)**|**Multiple Background**|
|<img src="./themes/minimal/previews/png/slides.019.png" width="200"/>|<img src="./themes/minimal/previews/png/slides.020.png" width="200"/>|<img src="./themes/minimal/previews/png/slides.021.png" width="200"/>|