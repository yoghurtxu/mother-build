# mother-build

零成本上手mother-build

## 用法
配置项跟father-build类似，差异点是配置文件名：father-build是.fatherrc.js，而mother-build是.motherrc.js

## 配置示例

```javascript
export default {
      cjs: 'babel',
      esm: { type: 'babel', importLibToEs: true },
      runtimeHelpers: true,
      extraBabelPlugins: [['babel-plugin-lodash']],
      pkgs: [
        'xxx'
      ]
    }
```

## 打包构建
运行mother-build指令即可
