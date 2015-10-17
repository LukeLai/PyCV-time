## differential_screen_tracker

### 用法

利用Camera 拍攝程式產生閃爍畫面後，
程式將該閃爍區域獨立顯示，
例如將該閃爍區域放置於例如顯示器或投影機畫面中，
可用於自動尋找真實空間中的ROI(Region of Interest)。


我們將產生指定大小的黑白閃爍區域視窗，
Camera將會利用MotionDetector()尋找出該區域，
並將閃爍區域分離出來(此時將停止閃爍)，
獨立顯示於'topview'視窗。


