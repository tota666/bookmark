分享一个小技术 美化浏览器书签做成网页

该样式支持谷歌浏览器75.0.3770.100、chrome内核的edge和IE浏览器11导出的书签。

第一步 导出书签

第二步 使用代码编辑器打开导出的收藏夹(能不用记事本就别用记事本) 在<TITLE>Bookmarks</TITLE>后面插入代码

第三步 全局替换 <H3 为 <H3 class="mdui-btn mdui-btn-block"

第四步 谷歌浏览器导出的全局替换 ICON=" 为 ><img src=" 

      IE浏览器导出的书签全局替换 ICON_URI=" 为 ><img src="
