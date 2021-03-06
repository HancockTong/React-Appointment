# React-Redux-Appointment

## 文件结构

最终的文件目录如下:

```
react_redux_appointment/
  README.md
  node_modules/
  package.json
  public/
    index.html
    favicon.ico
  src/
    actions/
      index.js
    components/
      AddForm.js
      AptList.js
      Search.js
      Sort.js
    constants/
      index.js
    containers/
      AddForm.js
      App.js
    reducers/
      apts.js
      formExpanded.js
      index.js
      openDialog.js
      orderBy.js
      orderDir.js
      query.js
    index.css
    index.js
```
## 用到的模块

```json
{
  "name": "react_redux_appointment",
  "version": "0.1.0",
  "private": true,
  "devDependencies": {
    "react-scripts": "0.8.4"
  },
  "dependencies": {
    "axios": "^0.15.3",
    "gh-pages": "^0.12.0",
    "lodash": "^4.17.2",
    "material-ui": "^0.16.5",
    "moment": "^2.17.1",
    "react": "^15.4.1",
    "react-dom": "^15.4.1",
    "react-redux": "^5.0.1",
    "react-tap-event-plugin": "^2.0.1",
    "redux": "^3.6.0"
  },
  "scripts": {
    "start": "react-scripts start",
    "build": "react-scripts build",
    "deploy": "yarn build && gh-pages -d build",
    "test": "react-scripts test --env=jsdom",
    "eject": "react-scripts eject"
  }
}



