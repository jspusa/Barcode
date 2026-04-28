# Barcode Generator

簡易的 EAN-13 條碼產生器，使用瀏覽器即可運作。

## 使用方式
1. 以瀏覽器開啟 `index.html`。
2. 輸入前 12 位數字後按下 **產生條碼**。
3. 生成的條碼可直接下載為 SVG 檔案。
4. 可額外下載 **4x6 標籤紙（10.2cm x 15.2cm）PDF**，版面自動以 **11mm x 35mm** 條碼尺寸重複排列，方便自行裁切。
5. 也可上傳自訂圖片檔（例如 11mm x 35mm 或其他尺寸），輸入寬高（mm）後，自動排版成 4x6 PDF。

此專案以 [JsBarcode](https://github.com/lindell/JsBarcode) 為核心實作。
