# <span style='color:red'>vscode</span>

[vscode中关于launch.json和tasks.json的变量说明](https://www.cnblogs.com/wanghao-boke/p/12058880.html)

[VScode tasks.json和launch.json的设置](https://zhuanlan.zhihu.com/p/92175757)

[VSCode创建自定义代码段](https://www.cnblogs.com/dotnetcrazy/p/9950431.html)

```json
  "react jsx": {
    "prefix": "rfcjsx",
    "body": [
      "import React from \"react\";",
      "import PropTypes from \"prop-types\";",
      "//import styles from \"./index.module.less\";",
      "",
      "const ${1:MyComponent} = () => {",
      "return <></>;",
      "};",
      "",
      "$1.defaultProps = {};",
      "",
      "$1.propTypes = {};",
      "",
      "export default $1;",
      ""
    ],
    "description": "react functional component jsx"
  }
  ```
