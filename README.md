# zheye

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).


### Study Note



4.3 介绍在vue中俄安装bootstrap，就一个命令 npm install bootstrap@next --save @next 是安装尚未发布的正式版本alpha

记得要回到4.2区重新建立一个vue项目

4.4 分析了ColumnList组件，没有实际代码

OK，现在回到了4.2
- vue create zheye
    - Manually select features
    - 选择Babel TypeScript和Linter/Formatter（提到了Router和Vuex后期会有用，暂时不选择）
    - 版本选择3.x 
    - ? Please pick a preset: Manually select features
    ? Check the features needed for your project: Choose Vue version, Babel, TS, Linter
    ? Choose a version of Vue.js that you want to start the project with 3.x
    ? Use class-style component syntax? No
    ? Use Babel alongside TypeScript (required for modern mode, auto-detected polyfills, transpiling JSX)? No
    ? Pick a linter / formatter config: Standard
    ? Pick additional lint features: Lint on save
    ? Where do you prefer placing config for Babel, ESLint, etc.? In dedicated config files

文件结构规范
三种规则：
    'plugin:vue/vue3-essential',
    '@vue/standard',
    '@vue/typescript/recommended'
    

