# SecurePDF-Python

SecurePDF-Python 是一個簡單的 Python 腳本，
針對 PDF 檔案進行密碼保護。

提供了一個簡單的界面，
讓使用者能夠輸入 PDF 檔案的路徑和加密密碼，
從而快速地生成加密過的 PDF 檔案(不會取代舊有的)。

## 功能

- **加密PDF**: 針對 PDF 檔案進行保護。
- **自動檔案命名**: 自動在原檔案名後添加 `_encrypted` 作為新檔案的名稱。

## 如何使用

1. **安裝PyPDF2**：
   需要先安裝 PyPDF2 。可以通過以下指令安裝：

```bash
pip install pypdf2
```

2. **執行腳本**：
   將`encrypt_pdf.py`腳本下載到你的 Python 環境，並在指令行中執行：

```bash
python encrypt_pdf.py
```

3. **輸入資訊**：
   根據提示輸入PDF檔案的完整路徑和你希望設定的密碼。

4. **獲得加密的PDF**：
   加密過的PDF將會保存在原檔案所在的目錄下，檔案名會附加 `_encrypted`。

## 注意事項
- 確保 PDF 檔案未被其他程式使用。
- 使用這個腳本時應確保檔案路徑和檔案名的準確性。
- 對於含有敏感資訊的 PDF 檔案，建議在安全的環境下使用此腳本。

## 貢獻
任何形式的貢獻都是歡迎的！如果你有改進建議或功能請求，請隨時開啟 issue 或發送 pull 請求。
