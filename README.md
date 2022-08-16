# colab_python
這一個放置運用 Colab 平台開發出來的一些小空間的放置空間。   by 瑞課

# 語音轉文字工具
[錄音檔轉文字.ipynb](https://github.com/reic/colab_python/blob/main/%E9%8C%84%E9%9F%B3%E6%AA%94%E8%BD%89%E6%96%87%E5%AD%97.ipynb)採用 Python 開發，可應用於訪談錄音檔轉文字、影片的字幕的生成，及其它相關應用。

因為透過Google Colab 平台、Google的語音轉文字工具，完成語音轉文字的工作。只需要有 Google 帳號，即可具備執行此程式的環境，輔以簡單的設定，不會程式的使用者也可以完成相關的工作。

== 更新記錄 ===

- 2021/5/3 增加多執行緖的方法，縮短翻譯的時間
- 2021/5/9 修正因檔名無法產生 OTR 檔的問題，謝謝「彩虹小馬」的回饋
- 2021/5/12 增加不同翻譯語言變數的設定，並於檔案中提供語系參考表。 謝謝 chin ho Lau 的回饋。

# 關鍵字擴展工具
[技術議題關鍵字擴展.ipynb](https://github.com/reic/colab_python/blob/main/%E6%8A%80%E8%A1%93%E8%AD%B0%E9%A1%8C%E9%97%9C%E9%8D%B5%E5%AD%97%E6%93%B4%E5%B1%95.ipynb)採用 Python 開發，使用政府開放資料：民國 105-109年的政府研究資訊網 (grb.gov.tw) 公開資料做為資料集。

對於不理解的議題，可以透過此工具了解**特定關鍵字**之相關技術，加速對於特定技術領域的理解。

# 文字檔轉 epub
[Text_to_Epub.ipynb](https://github.com/reic/colab_python/blob/main/Text_to_Epub.ipynb)採用 python 開發，進行資料處理將文字檔轉成多個 md 檔，再透過 colab 系統的 pandoc 套件，完成 md to epub 的轉換。
