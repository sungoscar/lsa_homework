113213024_宋政賢    
題目:This challenge has text files (with a .txt extension) that contain the phrase "challenges are difficult". Delete this phrase from all text files recursively.
Note that some files are in subdirectories so you will need to search for them.
原因:因為原本的寫法是單純 find ... | sed ...但是這樣子不會修改找到的檔案內容，因為 Pipe 傳的是 find 輸出的路徑文字
<img width="1103" height="770" alt="螢幕擷取畫面 2026-09-30 170630" src="https://github.com/user-attachments/assets/84809b19-713e-4995-8fab-9a3dc2e61728" />
