本專案是利用上次已完成之OpenQCam樹莓派迷你開源相機( [https://github.com/OmniXRI/OpenQCam](https://github.com/OmniXRI/OpenQCam) )(如圖一右圖所示)所衍生的應用實例【ePTZ攝影機】，一樣也會使用到OpenCV，希望這個專案能提供大家多一點使用上的想法。完整專案說明請參閱[https://github.com/OmniXRI/OpenQCam_ePTZ/wiki/OpenQCam-ePTZ%E5%B0%88%E6%A1%88%E8%AA%AA%E6%98%8E](https://github.com/OmniXRI/OpenQCam_ePTZ/wiki/OpenQCam-ePTZ%E5%B0%88%E6%A1%88%E8%AA%AA%E6%98%8E)。

傳統監視攝影機解析度通常不高，大約30萬畫像素(VGA)至二百萬畫像素(FHD)左右，若要監看較大範圍區域或特定一個小區域時常須搭配致動機構來使攝影機可以左右移動(Pan)、上下移動(Tilt)及調整光學倍率縮放(Zoom)，一般稱為PTZ攝影機(如圖1左圖所示)。這類攝影機由於須要搭配致動機構(馬達、齒輪等)及控制迴路，所以通常價格也會高出一般固定式攝影機許多。隨著攝影機取像晶片的快速進步，通常解析度已高出顯示器許多。以常見FHD(2K)的顯示幕來說不過約二百萬畫像素(1920x1080)，而4K顯示器雖然已可顯示八百萬畫像素，但高端攝影機早已高達五千萬甚至一億畫像素，而高過顯示器的解析度明顯就變成有些浪費。因此有許多廠商提出只需一隻固定式定焦(倍率不變)的高解析度攝影機，不須任何額外致動機構及元作，只要在高解析度影像中截剪(Crop)出顯示器所需解析度內容來顯示，即可取代部份PTZ攝影機使用場合，這樣的技術就稱為電子式或數位式PTZ，簡稱ePTZ。

![](https://github.com/OmniXRI/OpenQCam_ePTZ/blob/master/images/Fig1_PTZ_Camera_s.jpg)

圖1 左圖為傳統PTZ攝影機，右圖為利用OpenQCam所完成的ePTZ攝影機。

本專案是延續前一專案OpenQCam及做為熟悉本平台軟硬體架構很好的範例，程式的相關註解詳見各程式原始碼。受限於個人能力有限，撰文上難免產生誤解或疏漏，如有任何問題歡迎留言或來信指教！

作者：歐尼克斯實境互動工作室 [https://omnixri.blogspot.tw/](https://omnixri.blogspot.tw/) (Dec. 2017)
