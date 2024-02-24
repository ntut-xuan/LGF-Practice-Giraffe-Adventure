# LGF - Giraffe Adventure

長頸鹿大冒險是一款真正的 LGF 框架練習專案。

請嘗試通過所有的關卡來完成練習。



## Installation

將此專案 clone 下來（`git clone https://github.com/ntut-xuan/LGF-Giraffe-Adventure.git`）



## Stage

### Stage 1：修改主角

- 將灰色方格修改為長頸鹿。

- 嘗試理解 `CMovingBitmap` 如何讀取圖片。
- 你可能需要更改 `CGameStateRun::OnInit` 內的內容。



### Stage 2：移動主角

- 讓長頸鹿可以移動到指定的位置。

- 嘗試理解 `CMovingBitmap` 如何進行移動。
- 你可能需要更改 `CGameStateRun::OnKeyDown` 內的內容。



### Stage 3：與其他物件互動

- 讓長頸鹿碰到寶箱之後消失。

- 嘗試理解 `CMovingBitmap` 如何確認交疊。
- 你可能需要更改 `CGameStateRun::OnKeyDown` 內的內容。



### Stage 4：循環動畫

- 讓蜜蜂為循環動畫。

- 嘗試理解 `CMovingBitmap` 如何運行循環動畫。
- 你可能需要更改 `CGameStateRun::OnInit` 內的內容。



### Stage 5：與多個物件互動

- 讓長頸鹿碰到門之後可以打開門。

- 嘗試理解 `CMovingBitmap` 如何指定當前顯示的幀以及確認交疊。
- 你可能需要更改 `CGameStateRun::OnKeyDown` 內的內容。



### Stage 6：一次性動畫

- 讓球從 `3` 倒數到 `OK`。

- 嘗試理解 `CMovingBitmap` 如何運行一次性動畫，並且在適當的時機觸發一次性動畫。
- 你可能需要更改 `CGameStateRun::OnKeyDown` 與`CGameStateRun::OnInit` 內的內容。



## Useful Reference

- 快速入門：https://lgf-readthedocs.readthedocs.io/zh_TW/latest/index.html
- 函式庫：https://ntut-xuan.github.io/LeistungsstarkesGameFramework
