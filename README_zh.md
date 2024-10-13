# Dictate 鍵盤（Whisper AI 轉錄）

[Switch to English](./README.md)

<a href='https://play.google.com/store/apps/details?id=net.devemperor.dictate'><img alt='在 Google Play 上取得' width="258px" height="100px" src='https://github.com/DevEmperor/Dictate/blob/d99981575350cfde1fa91d4c449d97483eda14d0/img/google-play-badge.png?raw=true'/></a>

#### Dictate 是一個易於使用的轉錄和聽寫鍵盤。該應用程序在後台使用 [OpenAI Whisper](https://openai.com/index/whisper/)，支持[多種不同語言](https://platform.openai.com/docs/guides/speech-to-text/supported-languages)的極其準確的結果，包括標點符號和使用 GPT-4 Omni 的自定義 AI 重新措辭。一圖勝千言，這裡有一個展示視頻和一些截圖：

| <a href='https://youtube.com/watch?v=F6C1hRi1PSI'><img src='https://github.com/DevEmperor/Dictate/blob/624fde1cbc8e29fdb77f334f3edfa6231d27df82/img/dictate_player.png?raw=true'/></a> | ![dictate_keyboard_notes_recording.png](https://github.com/DevEmperor/Dictate/blob/624fde1cbc8e29fdb77f334f3edfa6231d27df82/img/dictate_keyboard_notes_recording.png?raw=true) | ![dictate_settings.png](https://github.com/DevEmperor/Dictate/blob/624fde1cbc8e29fdb77f334f3edfa6231d27df82/img/dictate_settings.png?raw=true) |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| ![dictate_settings_2.png](https://github.com/DevEmperor/Dictate/blob/58fd05bad9b33a91efb51a9506f6d9bf6310ad5b/img/dictate_settings_2.png?raw=true) | ![dictate_prompts_overview.png](https://github.com/DevEmperor/Dictate/blob/624fde1cbc8e29fdb77f334f3edfa6231d27df82/img/dictate_prompts_overview.png?raw=true) | ![dictate_prompts_edit.png](https://github.com/DevEmperor/Dictate/blob/624fde1cbc8e29fdb77f334f3edfa6231d27df82/img/dictate_prompts_edit.png?raw=true) |

## 最近更新

1. 改進網路連接處理：
   - 在 API 請求前增加網路可用性檢查
   - 為失敗的請求實現重試機制（最多 3 次嘗試）
2. 增強錯誤處理和用戶反饋：
   - 新增網路問題和達到最大重試次數的錯誤訊息
   - 改進錯誤日誌記錄，以便更好地進行調試
3. 升級依賴項：
   - 更新 GitHub Actions 工作流程
   - 新增 OkHttp 庫用於網路請求
4. 重構網路請求邏輯：
   - 用 OkHttp 替換 Retrofit，以更直接地控制請求
   - 改進請求和回應處理

## 安裝

**該應用程序可在 [Google Play](https://play.google.com/store/apps/details?id=net.devemperor.dictate) 上獲得**（需要支付少量費用以支持我和未來的開發），您可以輕鬆安裝並獲得免費的終身更新。只需點擊上面的徽章或[此鏈接](https://play.google.com/store/apps/details?id=net.devemperor.dictate)。

## 許可證

Dictate 遵循 [Apache 2.0 許可證](https://www.apache.org/licenses/LICENSE-2.0) 的條款，遵守[許可證文件](https://raw.githubusercontent.com/DevEmperor/Dictate/master/LICENSE)中所述的所有說明。

