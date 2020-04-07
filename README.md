# JZVD DEMO说明
## [MainActivity](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/MainActivity.java)
饺子快长大----包含JZVD最基本的使用例子
### [ApiActivity](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/ApiActivity.java)
展示饺子播放器自定义用法
  * [SmallChangeUiActivity](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/api/SmallChangeUiActivity.java)
    * [饺子想呼吸----添加分享按钮](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/CustomJzvd/JzvdStdShowShareButtonAfterFullscreen.java)
    * [饺子想摇头----全屏时显示标题](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/CustomJzvd/JzvdStdShowTitleAfterFullscreen.java)
    * [饺子想旅行----播放完显示textureview](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/CustomJzvd/JzvdStdShowTextureViewAfterAutoComplete.java)
    * [饺子没来----播放完成后保持全屏](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/CustomJzvd/JzvdStdAutoCompleteAfterFullscreen.java)
    * [饺子摇摆----进入全屏模式的时候打开声音](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/CustomJzvd/JzvdStdVolumeAfterFullscreen.java)
    * [饺子你听----播放MP3音乐](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/CustomJzvd/JzvdStdMp3.java)
    * [饺子快点----视频倍速播放](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/CustomJzvd/JzvdStdSpeed.java)
    * [饺子定身----添加锁定按钮，全屏后锁定无法操作界面](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/CustomJzvd/JzvdStdLockScreen.java)
    * [饺子有事吗----视频按1:1显示](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/api/SmallChangeUiActivity.java)
    * [饺子来不了----视频按16:9显示](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/api/SmallChangeUiActivity.java)
  * [BigChangeUiActivity----包含了模仿市面上成熟APP的UI范例](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/api/BigChangeUiActivity.java)
    * [UiBigChangeAGActivity-模仿爱奇艺,包含选集快进快退等](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/api/BigUIChangeAG/UiBigChangeAGActivity.java)
  * [OrientationActivity](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/api/OrientationActivity.java)
    * [饺子会旋转----展示饺子视频方向切换](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/api/SmallChangeUiActivity.java)
  * [ExtendsNormalActivity](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/api/ExtendsNormalActivity.java)
    * [饺子不信----适配了普通的Activity](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/api/ExtendsNormalActivity.java)
  * [RotationVideoSizeActivity-展示视频旋转，封面填充方式设置](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/api/RotationVideoSizeActivity.java)
    * [饺子坐火车----展示了视频画面旋转一定度数，视频封面填充方式](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/api/RotationVideoSizeActivity.java)
  * [CustomMediaActivity-自定义饺子播放内核](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/api/CustomMediaActivity.java)
    * [饺子很保守----展示使用系统默认播放器内核](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/api/CustomMediaActivity.java)
    * [饺子变心----展示使用Ijkplayer播放器内核](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/api/CustomMediaActivity.java)
    * [饺子回来了----展示饺子切换回使用系统默认播放器内核](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/api/CustomMediaActivity.java)
    * [饺子追星----展示使用ExoPlayer播放器内核](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/api/CustomMediaActivity.java)
  * [PreloadingActivity](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/api/PreloadingActivity.java)
    * [饺子存钱----展示饺子预加载视频，加载完成后播放](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/api/PreloadingActivity.java)
  * [ScreenRotateActivity](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/api/CustomMediaActivity.java)
    * [饺子挺好----根据重力感应切换横竖屏](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/api/ScreenRotateActivity.java)
  * [GetGifActivity](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/api/GetGifActivity.java)
    * [饺子会拼图----展示饺子生成GIF功能](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/CustomJzvd/JzvdStdGetGif.java)
	
###[ListViewActivity](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/ListViewActivity.java)
展示饺子播放器在列表中的使用
  * [NormalListViewActivity----展示饺子在ListView中的一般用法](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/ListView/NormalListViewActivity.java)
  * [ListViewFragmentViewPagerActivity----展示饺子在viewpager-fragment中使用](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/ListView/ListViewFragmentViewPagerActivity.java)
  * [ListViewMultiHolderActivity----展示饺子在多布局中使用](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/ListView/ListViewMultiHolderActivity.java)
  * [RecyclerViewActivity----展示饺子在Recyleview中的一般用法](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/ListView/RecyclerViewActivity.java)
  * [ListViewToDetailActivity----展示饺子从列表到详情页无缝切换](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/ListView/ListViewToDetailActivity.java)
  * [AutoPlayListViewActivity----展示饺子在列表中实现自动播放](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/ListView/AutoPlayListViewActivity.java)
  * [ActivityTikTok----模仿抖音列表](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/ListView/ActivityTikTok.java)
  
### [TinyWindowActivity](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/TinyWindow/TinyWindowActivity.java)
展示饺子小窗播放功能
### [DirectPlayActivity](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/DirectPlayActivity.java)
展示饺子直接全屏播放
###[WebViewActivity](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/WebViewActivity.java)
展示在WebView中使用饺子播放器
### [LocalVideoActivity](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/LocalVideoActivity.java)
展示播放本地视频文件
### [UiBigChangeAGActivity](https://github.com/Jzvd/JiaoZiVideoPlayer/blob/develop/demo/src/main/java/cn/jzvd/demo/api/BigUIChangeAG/UiBigChangeAGActivity.java)
高仿爱奇艺UI，包含锁定屏幕，视频切换，快进，快退等
