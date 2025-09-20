# reimu-template

<img alt="theme version" src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fraw.githubusercontent.com%2FD-Sketon%2Freimu-template%2Frefs%2Fheads%2Fmain%2Fpackage.json&query=%24.dependencies.hexo-theme-reimu&label=theme version">


Template for [hexo-theme-reimu](https://github.com/D-Sketon/hexo-theme-reimu)

## Usage

```bash
git clone https://github.com/D-Sketon/reimu-template
cd reimu-template
npm install
npm run server
```

## Features

The following features are pre-supported:

- support LaTeX (@reimujs/hexo-renderer-markdown-it-plus)
- support mermaid (hexo-filter-mermaid-diagrams)
- support git (hexo-deployer-git)
- support rss (hexo-generator-feed)
- support Algolia search (@reimujs/hexo-algoliasearch)

## How to use

The configuration of Hexo is in `_config.yml`  
The configuration of Reimu is in `_config.reimu.yml`  
You can modify the configuration according to your needs
