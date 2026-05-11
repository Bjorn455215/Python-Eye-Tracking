# Python-Eye-Tracking
基於 Python 與 Mediapipe 開發的即時人體姿態偵測專案。透過電腦攝影機來追蹤使用者的頭部轉向、雙眼位置，並估算與相機的相對距離。

## 原始功能
- **即時眼部追蹤**：精準標定雙眼關鍵點。

## 新增功能
- **動態回饋**：標註點大小會隨著使用者靠近/遠離相機而自動調整。
- **轉向判斷**：透過計算鼻子與耳朵的相對座標，判斷使用者是向左轉、向右轉還是直視前方。
- **鏡像處理**：內建水平翻轉，符合直覺的操作體驗。

## 需求
本專案使用 **Python 3.9.7 版**(因為 mediapipe 在 3.10+ 以上無法執行)，執行以下指令安裝必要套件：
| 套件名稱 (Library) | 建議版本 (Version) | 說明 (Description) |
| :--- | :--- | :--- |
| **opencv-python** | `4.8.0.74` | 基礎影像處理庫 |
| **opencv-contrib-python** | `4.13.0.92` | 包含擴展功能的 OpenCV 版本 |
| **mediapipe** | `0.10.9` | Google 開發的機器學習視覺推論框架 |
| **cvzone** | `1.6.1` | 簡化 Mediapipe 操作的封裝工具庫 |

## 成果
https://github.com/user-attachments/assets/12cedf83-5f0e-4c22-a25c-66311a1d9cf8


## 參考資料
https://github.com/Tech-Watt/YOUTUBE-TUTORIAL-CODES/blob/main/Eye%20detection.py
