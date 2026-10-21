框架事件，scheduler，基础类型，没什么改变，
依旧依赖，网络，libwebsocket / curl /openssl，
物理，box2d / Chipmunk2D
音频，openal mpg123 vorbis ogg修正调试恢复后的音频中断与退出报错
图片，stb_image stb_image_write
sax解析改为tinyxml2，地图等一律用此，
渲染层统一改为SDL_RenderGeometry
相机带有类似2d视锥体剔除
加入zip.h .c 支持对异或/加密zip文件的查询，
字体 ft2
转码改为，提取iconv库的单头，支持utf8 utf16le utf32le互转，
json统一改为单头库，
包含2d audio base math network physics  platform render utils ui测试中，
粒子，丝带，各类地图，节点绘制等均以支持，转场2d翻页特效，等
应该是这样，
