# pageCode
分页功能样式
```
/**
 * create time: 2016-xx-xx
 * author: dongsheng
 * fn: 分页
 * 操控dom 依赖jQuery
 * 样式: scss/pageCode.scss
 * 用法：var pages = new PageCode(params)
 * 参数详解(params):
 * 类型： Object {}
 * 		obj: 分页dom结构容器元素
 * 		classNames: {
 * 			prevPage: 上一页class类名,默认 "prevPage"
 * 			nextPage: 下一页class类名,默认 "nextPage"
 * 			tcdNumber: 页码clas类名,默认 "tcdNumber"
 * 			active: 当前选中class类名,默认 "current"
 * 		}
 * 		pageCount:  总页数
 * 		current: 当前页
 * 		backFn: 回调函数 参数（当前页码）function (p){
 *			pages.refresh(pageCount,p);
 *		}
 * 		
 * 禁止翻页class类名: disabled
 *
 * 方法： 
 * 	refresh： 更新分页 (总页数，当前页码)
 */
```