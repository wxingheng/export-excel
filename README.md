# export-excel
js excel table 

```
import '/node_modules/x-export-excel'
```

 * excel 导出
 * @param {string?} name  导出文件名
 * @param {string?} type  导出的文件类型
 * @param {string} id    表格id
 
```
export const educeExcel = function (name: string = '导出文件名', id: string = 'export', type: string = 'xlsx') {
  exportExcel(id, type, `${name}.xlsx`)
}
```
 
