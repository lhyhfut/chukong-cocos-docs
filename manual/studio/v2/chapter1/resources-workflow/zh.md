# 1.2 资源工作流程


我们将在本页说明资源是如何在Cocos Studio中使用的。

#### 导入资源

Cocos Studio支持多种形式的导入资源，您可以

(1) 通过菜单导入

您可以通过Cocos Studio的菜单“文件—导入资源”或资源面板菜单项”导入资源“，导入资源至项目管理器中。

(2) 通过拖拽导入

您可以直接将磁盘上的资源，通过拖拽的形式，直接导入至Cocos Studio的资源面板、画布面板、属性面板（对应属性）、动画面板上。

(3) 通过属性导入

您可以在编辑控件属性时，可以对控件的资源进行预览，并可以通过双击修改所引用的资源。

Cocos Studio会将这些散落在磁盘各处的资源，拷贝到您的项目所在目录中。

#### 使用资源

您导入的资源最终会以控件属性的形式被使用。例如图片控件，资源将作为其属性“图片资源”被使用。控件属性请参考[如何使用控件](../../chapter3/how-to-use-controls/zh.md)。

#### 输出资源
(1) 发布资源

您可以使用发布功能发布您的项目，Cocos Studio会为您梳理好所有被使用的资源并统一发布到指定的目录中，供编程人员使用。关于发布功能，请参考[构建发布](../../chapter2/publish-game/publish/zh.md)。