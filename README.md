﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿## FF14_3A画质补丁 ## FF14_3Areal_Reshade`Ver 6.15.0_Beta2019-6-29`>注：2019-6-29迁移到新托管网站，改善下载速度> *  [→目前在使用中的托管站点](https://github.com/UTwelve/3AReal/releases)> * -于 v6.15.0(2019-6-29) 更换了托管-> *  [→此阶段版本在此托管中下载](https://bitbucket.org/utwelve/ff14_3areal_reshade/downloads/?tab=tags)***## **FF14_3A画质补丁**基于Reshade通用后处理注入器开发`https://github.com/crosire/reshade`**以写实为目标的画质调整补丁*****## 安装说明>* ### 安装说明与注意事项答疑解惑等 详见：> http://bbs.nga.cn/read.php?tid=13624110>> 若有**旧版本补丁**或其他画质补丁，很大几率会冲突，请**务必**清理旧补丁>* ### 最新版本和往期版本的截图 详见：> http://tieba.baidu.com/p/5588728805>> 点击 **只看楼主** 可快速查看最新发布的图片***## 使用说明* Ver 6.15.0_Beta   至 最新版本图文示例详见NGA贴中说明| 按键      | 功能          | 说明 || -------- | -----:        | :----: || Shift+F12      | 整体开关 | 开关整个注入器，关闭后不会消耗游戏帧数 || Shift+F11      | 光线追踪(目前不含) | 屏幕空间的光追，不需要RTX显卡支持|| Shift+F10      | 反射追踪 | 屏幕空间反射SSR || Shift+F9       |  运动模糊 | 运动模糊，也可充当静物拍摄时的抗锯齿使用|| Shift+F8       | 手动景深 |可控性更高，使用鼠标对焦①|| Shift+F7       | 自动景深 | 模仿真实相机，根据镜头位置自动调整光圈|| Shift+F6       | 写实透视 | 模仿光学透镜固有的透视失真，可校正屏幕边缘的拉伸|| Shift+F5       | 16:9黑边 | 给黑条爱好者与正方形屏幕受害者的|| Shift+F4       | 自拍舞台背板 | 生成一个绿色抠图背板②|| Shift+F3       | 画笔效果 |独特的美术风格，个别情况也可做为抗锯齿使用|| Shift+F1       | LUT滤镜 | 可自定义的风格化滤镜，默认关闭|>  ① 注释 ：两种景深 **原则上** 不是用来同时开启的>  >  ② 注释 ：可在 **设置** 中自定义颜色与尺寸，见帖子中高级设置> >  ③ 注释 ：替换方式见NGA帖子***## 近期更新说明>* Alpha：试验收集反馈阶段，未经充分测试，需要自己的动手能力>* Beta：公测，有已知的问题待改进，但已经可以正常使用 * Ver 6.15.0_Beta>* [功能+]新增光追系列效果，目前可用F10的SSR屏幕空间反射（不含内测阶段的光反弹**qUINT_rt.fx**，有条件得到此fx的同学可以将其加入，排序在LUT和MXAO之间。已设置好参数。待作者公布此FX时，会加入补丁的F11）>* [功能+]常驻的近景景深，解决一些因剪裁平面引起的问题>* [功能+]新的艺术风格效果，模仿笔触的画面>* [功能+]全新重制的光线效果，调整Bloom绘制新的Lens。改善光污染带来的问题>* [功能+]全新重制的灰尘图，绘制新的Dirt，配和新版本光追与Bloom，现在更柔和>* [功能+]新的锐化>* [功能-]移除深度雾，提升画面清晰度>* [功能-]移除全屏CA，改善画面模糊问题>* [功能-]删除SMAA>* [功能修改>F11的功能临时移除，为光追做调整>* [功能修改]更改AO，为光追做调整>* [功能修改]调整曝光，现在亮度更均衡>* [功能修改]调整fx排序，配合新的光线效果>* [功能修改]CA效果减弱，优化小屏效果>* [功能修改]以及一些Alpha阶段时的微小小调整 * Ver 6.14.6>* [功能修改]现在画面更温和一些 * Ver 6.14.5>* [功能+]UI蒙版进一步完善，在画面处理前从原始画面中去除UI，避免UI对效果器的影响>* [功能+]泛光的灰尘图重置后回归>* [功能+]增加横向泛光效果>* [功能+]远景天地交接处处理>* [功能+]增加自带的后期校色（非LUT）>* [功能修改]改善AO阴影效果，提高质量，调整混合模式>* [功能修改]完善CA色差效果>* [功能修改]改善海都白天效果>* [功能-]SMAA改为默认关闭，效果与性能损耗的性价比太低 * Ver 6.13.0.1>* [功能修改]Shift+f1的Lut改为默认关闭 * Ver 6.13.0>* [功能+]SMAA抗锯齿>* [功能修改]修复景深模糊错乱的问题>* [功能修改]镜头四周的CA效果减轻 * Ver 6.12.1>* [功能+]增加几套LUT>* [功能修改]默认LUT更换为接近 3AREAL 的5.x版本经典滤镜 * Ver 6.12.0>* [功能+]可自定义LUT滤镜正式上线>* [功能+]亮度自适应回归，改善海都等高亮度地区的光污染>* [功能+]消灭游戏难看的“16bit”色阶>* [功能+]噪点的效果现在更好>* [功能修改]手动景深现在精度更高，改善画质>* [功能修改]色差屏幕四周的效果降低，改善小屏幕的体验>* [功能修改]更换了一个速度更快的锐化>* [功能修改]多个效果器同步到新版本 * Ver 6.0.1>* 测试完毕，正式发布>* [功能修改] 微调阴影 * Ver 6.0.0>* [功能修改]为配合累计增加的多个效果器（旧LUT很难配合过去增加的一些新效果器），6.0换上了全新的LUT滤镜，重点提升了肉质(？，去除默认屎黄色，改善曝光，白天夜晚画面更清晰>* [功能修改]F10效果默认为开启>* [功能修改]多个效果做大幅调整>* [功能-]去除包中未使用的效果器以缩小下载体积>* [功能预告]新LUT滤镜偏口味清淡，后续版本会有第二个LUT，为专门的电影效果LUT（制作中，目前未分配开启快捷键，可手动开启） * Ver 5.2.0>* [功能+]F10效果中新增镜头泛光Lens效果>* 色散等效果根据反馈，由默认开启转为放入F10中 * Ver 5.1.0>* 【重大】本补丁此版本开始不影响技能、地图、窗口等UI>* 某些之前会影响UI的效果已经改为常驻>* bloom泛光效果修改完成，重新加回补丁>* 修改了AO阴影的表现 * Ver 5.0.2>* 更换了一个F3补丁开关对比的实现方式>* Shift+F10的相机效果现在更清晰>* 默认为关闭编辑的性能模式以减少一些bug（SHIFT+F2可在右下角打开）>* 清理图片缩减下载体积 * Ver 5.0.1>* 修改快捷键 * Ver 5.0.0> * 多种美术调整（参考贴吧帖子中的版本配图）> * Reshade版本升至官方4.0.2> * 修正Reshade对于中文目录的支持，并进行针对性的汉化> * 修复DX9支持>  * 效果器更新> * 低配版改为单独存放，用于覆盖： F11开启后，会将阴影质量切换为最高，用于拍照（帧数会爆降） * Ver 4.3.0.2> * 修正锐化过度，F12失效问题 * Ver 4.3.0.1> * 临时解决F8黑屏问题 * Ver 4.3.0> * 【ps】中间几个版本我都没更新上来，因为要这次要增加个低配版~~出低配版是不可能的，这辈子都不可能，快换高配电脑~~，一改得改两个，工作量翻倍了，所以之后如果没有什么急需修复的BUG，一般会攒一波更新一次（比如这次），不会像之前那样更新的跟抽风一样> * 【重大】新增了低配版，`shift+f2`下拉菜单中选择`HK12_3Areal_Low.ini`；低配版画质相同，只是将一些高消耗的常驻特效移入F11中，可以只在截图时开启 > * 提高AO阴影深度，提升光反弹饱和度，降低了质量优化运行速度> * 调整LUT、增加曝光适应着色器，改善白天过亮的问题，微妙地增加了夜晚亮度。> * 重写了噪点着色器，增加自适应，白天噪点消失，只在很暗的情况下出现，模仿真正的相机iso设置> * 景深更新到外网大佬新版本，优化了近景散焦，修正了几个我都没发现存在的BUG> * 写实透视（改名了，不叫镜头畸变了，看到畸变二字不知道的还以为这是削减画质的呢）更新到外网新版本，增加了一个之前我以为他有功能，顺手把填补黑框关了，视觉上舒服些> * 【重大】增加动态模糊效果，替换了原强力抗锯齿；发现的一个野生着色器，和之前用的TAA原理类似，我拿来加进去了，除实现原有抗锯齿功能外还可以当做运动模糊使用，电脑越好，间隔越小，效果越好> * 删除了暂时不用的着色器与贴图，缩小体积；因为要上传到外网，可以尽量增加大家的下载速度> * 上个版本到现在的一些美术上的小调整，参数增增减减的积累更新，我不说你也注意不到 * Ver 4.0.3> * 全新的F9鼠标对焦景深！优质的远近景散焦> * 全新的Bloom，性能更快，效果升级> * 调整了F11的范围，边缘模糊减小，合照更清晰> * 曝光范围调整，增加夜景噪点，模仿相机拍摄质感 * Ver 4.0.0> * Reshade核心升级到3.4.1，为避免混淆版本，补丁版本跳过3.x> * 汉化Reshade WIP * Ver 2.4.1> * 更新了一些着色器版本，手动景深参照50mm f/1.8镜头做了调整 * Ver 2.4.0> * 更新了近景表现力强的手动对焦景深 * Ver 2.3.2> * 提升色彩范围，改善强光发灰问题> * 补充手动景深供选择使用> * 更改按键 * Ver 2.3.0> * 景深更新为新算法，模拟真实相机焦距，根据镜头距离与焦距自动对焦> * 新增舞台背板功能> * 更新SMAA着色器，优化抗锯齿> * 调整较色，修正个别场景红色过度的问题、平衡整体亮度至接近原版> * 更新着色器版本> * 调整按键设置更符合操作习惯> * 其他积累更新 * Ver 2.2.1> * 修正了AO阴影范围> * 拆分功能，更改按键设置> * 进一步降低锐化 * Ver 2.0.1> * 畸变校正fx版本更新，自带了抗锯齿> * 降低了AO浓度与范围，解决一些场景会出现的BUG> * 降低了夜晚噪点效果的强度> * 降低了锐化效果> * 提高了景深光圈效果 * Ver 2.0.0> * Reshade从3.2.2编译> * 新的AO/IL着色器> * 景深大修> * 着色器顺序调整> * 测试新的TAA抖动抗锯齿> * 更改按键 * Ver 1.5.1> * 修正了夜景表现力，夜景更拟真> * 增加了光照自适应，过亮会降低亮度> * 更改按键，F12开关 F11景深 F10镜头色差 F9广角畸变 F8电影化黑条> * 修正了红色饱和度过高的问题> * 优化了SMAA与TXAA抗锯齿逻辑> * 调整了锐化效果> * 降低了假光反弹的亮度> * 独立出镜头色差，针对小屏幕做了优化> * 关闭了景深的广角畸变，因为现在有独立的广角畸变着色器> * 优化体积删除备份着色器 * Ver 1.4.3> * 修复了画面偏粉的问题> * 优化了景深效率> * 针对对话框过亮的问题做了调整 * Ver1.3.0> * 修复泛光着色器特殊条件下会产生微小斜纹的BUG * Ver1.2.1> * 紧急修复一个着色器排序问题 * Ver1.2.0> * 环境光遮蔽曲线调整> * 修正景深鼠标对焦时有往左偏90像素误差的BUG> * 默认截图目录改为C:\Users\Public\Pictures * Ver1.1.1> * 稍微降低了亮度> * 去掉无用景深，未使用着色器放在BAK文件中提升载入速度 * 更多历史版本更新内容请通过标签查询