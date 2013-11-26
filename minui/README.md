汉化说明
--------
使用了ruby脚本生成字库的汉化方式<br /><br />

###生成字库
1、定位到本目录<br />
2、命令行：./chinese_gen.rb 宽度 高度 字体大小<br />
例如：./chinese_gen.rb 15 24 24<br />

###注意
要在device的BoardConfig.mk文件加上：BOARD_USE_CUSTOM_RECOVERY_FONT := \"字库头文件\"<br />

