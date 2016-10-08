# AutoLayout
鸿洋大神的 AutoLayout

引入
Android Studio
将autolayout引入

dependencies {
    compile project(':autolayout')
}

也可以直接

dependencies {
    compile 'com.zhy:autolayout:1.4.5'
}


用法

第一步：

在你的项目的AndroidManifest中注明你的设计稿的尺寸。

<meta-data android:name="design_width" android:value="768">
</meta-data>
<meta-data android:name="design_height" android:value="1280">
</meta-data>
第二步：

让你的Activity继承自AutoLayoutActivity.
