# Integrating Docusaurus with Material UI Template

This project is a Docusaurus website integrated with Material UI. Docusaurus is a modern static website generator that makes it easy to build personal, project, and organization sites. Material UI is a popular React UI framework that provides a set of reusable, well-tested, and accessible UI components.

##  Deploy Your Own

Deploy your own Docusaurus project with Azion.

[![Deploy Button](/static/button.png)](https://console.azion.com/create/docusaurus/docusaurus-material-ui "Deploy with Azion")

## Technology used

- Docusaurus V3
- Material UI
- Search engine: `@easyops-cn/docusaurus-search-local`

## Features

The project uses the [@easyops-cn/docusaurus-search-local](https://github.com/easyops-cn/docusaurus-search-local) plugin for local search functionality. This plugin provides full-text search over your Docusaurus site, without needing to rely on any external services. It supports indexing of pages and documents, and even supports language-specific searching.

The website also features a new blog UI was built using Material UI components and provides a modern, clean interface for displaying blog posts. The blog posts are managed by a custom blog plugin, defined in `src/plugins/blog-plugin.js` and homepage config in `components/Homepage/index.js`.

## Start your project

### Installation

Clone the [repository](https://github.com/namnguyenthanhwork/docusaurus-material-ui-template)

Open project and install packages

```
npm i
```

### Ready to use

Start the development server

```
npm start
```

Build the project

```
npm run build
```

## Contributing to the project

Create a new Pull Request to contribute to the project. If you find any issues or have suggestions for improvements, please create a new issue. Thanks for any feedback!
