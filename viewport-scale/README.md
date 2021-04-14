# Viewport Scale
这个没啥好说的，就是手动实现了 Viewport Width 固定时缩放的过程。

另外这里取宽度改成了 window.outerWidth，因为 scale 变更时，视窗宽度也会变更。  
所以导致 resize 无限触发，其实也无所谓，可以把监听换成 `orientationchange`。