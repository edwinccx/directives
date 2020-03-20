在 components 组件文件中 新建 directives.js 文件

main.js中导入  比如  import './components/directive/directives';  

使用 el-dialog 的地方加入 v-dialogDrag 如: el-dialog  title="XXX" :visible.sync="dialogVisible" v-dialogDrag 
