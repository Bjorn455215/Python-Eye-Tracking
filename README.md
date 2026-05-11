# Python-Eye-Tracking
基於 Python 與 Mediapipe 開發的即時人體姿態偵測專案。透過電腦攝影機來追蹤使用者的頭部轉向、雙眼位置，並估算與相機的相對距離。

## 功能
- **即時眼部追蹤**：精準標定雙眼關鍵點。
- **動態回饋**：標註點大小會隨著使用者靠近/遠離相機而自動調整。
- **轉向判斷**：透過計算鼻子與耳朵的相對座標，判斷使用者是向左轉、向右轉還是直視前方。
- **鏡像處理**：內建水平翻轉，符合直覺的操作體驗。

## 需求
本專案使用 **Python 3.9.7 版**(因為 mediapipe 在 3.10+ 以上無法執行)，執行以下指令安裝必要套件：

```bash
pip install opencv-python cvzone mediapipe
```

## 成果

## 參考資料
https://github.com/Tech-Watt/YOUTUBE-TUTORIAL-CODES/blob/main/Eye%20detection.py
