# sass_tel
 在这样的一个模板中，每个Sass目录下的文件夹都对应着各种分类的_xxx.scss文件：

base：放置一些基本样式的SCSS文件，比如重置样式_normalize.scss，基本样式_base.scss，文本排版样式_typography.scss等
components：放置一些公用组件，比如：按钮_buttons.scss、表单_form.scss、表格_tables.scss、选项卡_tabs.scss等
helps：放置一些辅助功能性文件，比如：_css3.scss、_variables.scss、_mixins.scss、_helpers.scss和_function.scss等
layout：放置一些跟页面布局相关的，比如：_layout.scss、_header.scss、_footer.scss、_sidbar.scss等
pages:放置跟具体项目页面相关的样式文件。
themes：对于一些有前后台页面，或者需换肤的项目，就可以将相关文件放置在这里。
vendors：引用的外部插件或者框架的SCSS文件，比如_bootstrap.scss、_foundation.scss。
style.scss这是主样式文件，最终编译，就编译这个问题。当然根据项目大小，可做一些其他处理。比如说针对不同的页面,创建不同的page_xxx.scss文件。