# Public Assets & Resources 🗂️

Welcome to my **Public Assets** repository! This is a multipurpose storage for various publicly available files. The goal is to decouple static resources (images, data, configurations) from specific project codebases, making them reusable across my portfolio, demos, and other applications.

## 🎯 Purpose

This repository is designed to be a scalable container for **anything** that needs to be publicly accessible, such as:

- **Images:** Logos, banners, screenshots, and icons.
- **Data:** JSON files, mock data for testing, or configuration presets.
- **Documents:** PDFs, guides, or downloadable resources.
- **Media:** Videos, gifs, or audio clips.

## 🚀 Usage

You can access **any file** in this repository via the [jsDelivr](https://www.jsdelivr.com/) CDN.

**Base URL Pattern:**

```
https://cdn.jsdelivr.net/gh/YaGRRusso/public-assets@main/[path-to-file]
```

### Examples

**Fetching a JSON file (Hypothetical):**

```javascript
fetch("https://cdn.jsdelivr.net/gh/YaGRRusso/public-assets@main/data/mock.json")
  .then((response) => response.json())
  .then((data) => console.log(data));
```

**Displaying an Image:**

```markdown
![My Certificate](https://cdn.jsdelivr.net/gh/YaGRRusso/public-assets@main/certificates/cesuca.jpg)
```

## ✨ Benefits

- **Universal Access:** Use the same resource in multiple projects without duplication.
- **Performance:** Served via global CDN for low latency.
- **Clean Repositories:** Keep your project source code light by offloading binary or large static files here.

## 📝 Maintenance

This is a living repository. New folders and file types are added as new requirements arise in my development workflow.
