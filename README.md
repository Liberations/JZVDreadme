# JZVD DEMO说明
## [MainActivity-包含JZVD最基本的使用例子](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/MainActivity.java)
* [API-展示饺子播放器自定义用法](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/ApiActivity.java)
  * [Small change Ui-UI小改动](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/api/SmallChangeUiActivity.java)
    * [添加分享按钮](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/CustomJzvd/JzvdStdShowShareButtonAfterFullscreen.java)
    * [全屏时显示标题](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/CustomJzvd/JzvdStdShowTitleAfterFullscreen.java)
    * [播放完显示textureview](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/CustomJzvd/JzvdStdShowTextureViewAfterAutoComplete.java)
    * [播放完成后保持全屏](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/CustomJzvd/JzvdStdAutoCompleteAfterFullscreen.java)
    * [进入全屏模式的时候关闭静音模式](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/CustomJzvd/JzvdStdVolumeAfterFullscreen.java)
    * [播放MP3](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/CustomJzvd/JzvdStdMp3.java)
    * [视频调速](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/CustomJzvd/JzvdStdSpeed.java)
    * [添加锁定按钮](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/CustomJzvd/JzvdStdLockScreen.java)
    * [16:9显示/1:1显示](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/api/SmallChangeUiActivity.java)
  * [Big change Ui-包含了模仿市面上成熟APP的UI范例](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/api/BigChangeUiActivity.java)
    * [UI Big Change AG-模仿爱奇艺,包含选集快进快退等](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/api/BigUIChangeAG/UiBigChangeAGActivity.java)
  * [Orientation-横竖屏切换例子](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/api/OrientationActivity.java)
  * [Extends Normal Activity-适配普通Activity非AppCompatActivity](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/api/ExtendsNormalActivity.java)
  * [Video And VideoSize-视频旋转，封面填充方式设置](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/api/RotationVideoSizeActivity.java)
  * [Custom MediaPlayer-自定义饺子播放内核](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/api/CustomMediaActivity.java)
  * [Preloading-预加载播放](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/api/PreloadingActivity.java)
  * [Screen Rotate-根据重力感应自动进入全屏](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/api/CustomMediaActivity.java)
  * [GetGifActivity-GIF动图生成](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/api/GetGifActivity.java)
* [LISTVIEW-展示饺子在列表中的使用](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/ListViewActivity.java)
   * [Normal ListView-在ListView中的一般用法](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/ListView/NormalListViewActivity.java)
   * [ListView Fragment ViewPager-在viewpager-fragment中使用](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/ListView/ListViewFragmentViewPagerActivity.java)
   * [Multi Holder ListView-多布局中使用](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/ListView/ListViewMultiHolderActivity.java)
   * [Recyleview-在Recyleview中的一般用法](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/ListView/RecyclerViewActivity.java)
   * [List Smooth To Detail-列表详情页无缝切换](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/ListView/ListViewToDetailActivity.java)
   * [List Auto Play-在列表中实现自动播放](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/ListView/AutoPlayListViewActivity.java)
   * [TikTok-模仿抖音列表](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/ListView/ActivityTikTok.java)
* [Tiny Window-小窗播放](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/TinyWindow/TinyWindowActivity.java)
* [Direct Play-直接全屏播放](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/DirectPlayActivity.java)
* [WebView-在WebView中添加饺子播放器](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/WebViewActivity.java)
* [LOCAL VIDEO-播放本地视频](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/LocalVideoActivity.java)
* [Custom Ag Video !!-仿爱奇艺UI](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/TinyWindowActivity.java)