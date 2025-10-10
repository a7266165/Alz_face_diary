# Alz_face_diary
AI在很多人眼中，是難以使用，又容易失控的工具。

而我是這陣子才明白，它之所以難用，
是因為每次輸入，
都需要仔細斟酌字句、幫它準備很多先備知識並檢查它的輸出。
但反過來說，只要願意仔細去做這些，它就會是個很強大的加速器。

這陣子，我在試著把Alz的分析流程架成一個API接口，
也趁著這次機會，盡可能詳盡記錄了我與claude的對話過程。

關於這件事，需要多補充一些背景
最一開始，我是先請AI複刻學弟的實作流程，
沒有宏觀的思考程式碼架構，
API之前也是隨便地請AI刻完就上。

接著，移植分析流程時遇到阻礙，才進行第一次重構，
也就是現在放在legacy裡的相關程式碼。

從中還是可以感受到，細部架構仍有些混亂。

另一方面，從對話記錄可以發現，如果我敘述不清，通常得不到太好的回應。
又或者沒有仔細看過回應就往下走，也容易導致後面有更多問題。

至於這次重構，我試著做更充份的準備，相信接下來會有更好的結果。

repo相關連結

Alz_face_analyze
https://github.com/a7266165/Alz_face_analyze
Alz_face_api
https://github.com/a7266165/Alz_face_api

Alz_face_analyze_legacy
https://github.com/a7266165/Alz_face_analyze_legacy
Alz_face_api_legacy
https://github.com/a7266165/Alz_face_api_legacy