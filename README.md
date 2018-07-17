# export-excel
js excel table 

/**
 * excel 导出
 * @param {string} name  导出文件名
 * @param {string} type
 * @param {string} id
 */
export const educeExcel = function (name: string = '导出文件名', id: string = 'export', type: string = 'xlsx') {
  exportExcel(id, type, `${name}.xlsx`);
}