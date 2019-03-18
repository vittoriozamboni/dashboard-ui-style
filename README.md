# dashboard-ui-style

This repository contains SCSS files used by private [dashboard](https://github.com/vittoriozamboni/dashboard) project.

## Folders and files

The project is divided into two sections: global files and ui elements files.
Global files are in the main `style` folder, while ui specific files are under `styles/ui` folder and collected by `style/ui.scss` file.

In your project, import the following:

```scss
@import '~@vzamboni/dashboard-ui-style/style/colors';
@import '~@vzamboni/dashboard-ui-style/style/fonts';
@import '~@vzamboni/dashboard-ui-style/style/shadows';
@import '~@vzamboni/dashboard-ui-style/style/helpers';
@import '~@vzamboni/dashboard-ui-style/style/ui';
```
