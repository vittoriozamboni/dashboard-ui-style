# dashboard-ui-style

This repository contains SCSS files used by private [dashboard](https://github.com/vittoriozamboni/dashboard) project.

## Folders and files

The project is divided into two sections: global files and ui elements files.
Global files are in the main `style` folder, while ui specific files are under `styles/ui` folder and collected by `style/ui.scss` file.

In your project, import the following:

```scss
@import '@vzamboni/dashboard-ui-style/style/ui';
```

If you are using a local version of the repository and `yarn link` facility, use:

```scss
@import '~@vzamboni/dashboard-ui-style/style/ui';
```
