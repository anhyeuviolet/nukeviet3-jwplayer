# nukeviet3-jwplayer
Fix error #2035 when embed JWplayer inside HTML content.

# Hướng dẫn cho NukeViet 3.4

Download từ đây:

https://github.com/anhyeuviolet/nukeviet3-jwplayer

Download các file đính kèm về giải nén ghi đè lên các file hệ thống, có thể dùng chức năng cài đặt và đóng gói tự động trong admin để cài đặt tự động (bỏ qua các cảnh báo) mở file /theme/theme-dang-dung/layout/header.tpl thêm phía trước

`</head>`

Ba dòng này:

		<script type="text/javascript" src="{NV_BASE_SITEURL}images/jwplayer7/jwplayer.js"></script>
		<script type="text/javascript" src="{NV_BASE_SITEURL}images/jwplayer7/jwplayer.trigger.js"></script>
		<script type="text/javascript">jwplayer.key="18ewa3s2LTybLMlqx3nfOJTvmRqu9cuQPTrQ==";</script>


Lưu ý: Chỗ jwplayer.key là key mà bạn lấy được từ trang jwplayer.com 
( Hướng dẫn: https://github.com/anhyeuviolet/module-videos/wiki/H%C6%B0%E1%BB%9Bng-d%E1%BA%ABn-%C4%91%C4%83ng-k%C3%BD-Free-License-JWPlayer-7)


Tắt tối ưu site, dọn dẹp hệ thống và kiểm thử. 
