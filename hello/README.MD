* 了解rustc, it's rust ccompiler, 用他來編譯程式  
  
* 了解cargo, 這是綜合工具包, 可以開啟新專案`cargo new projectName`, 可以測試`cargo test`, 可以執行`cargo run`, 雖然有很多制式化的組合, 但是可以練習所謂嚴謹的流程, 另外, rust的測試工具都內建的, 而且很完善, 不像powershell, 需要在內部使用`try_Catch`去抓錯誤, rust通常在程式編輯階段就會幫你抓很多錯誤了, 然後每個變數, 流程都需要嚴謹的規範, 這是powershell and apps script(JS)所沒有的  
  
* 指令工具複習. windows除了cmd外, 我是選擇繼續用 powershell, 而且也裝了powershell 7 來用, 兩個框架不同, 一個是dotNet, 一個是dotNet core, 後面的可以跨環境, 執行檔不太一樣, PS 7 是 pwsh.  

* 一般作業系統程式結束是回傳0, 1-255是錯誤訊息
  
* crate 是rust 遠端線上包管理平台, 類似powershell 的nuGet or PSGallery, 可以 in stall for global area, or just add to module for current program, or manual type the information in the toml file, rust 是看這個文件, 自動管理各種依賴的, 我覺得很像golang 的 mod.

* 使用rust的測試框架, #[test] 將function 變成測試單元, 不過`cargo test`他第一次跑單元測試, 第二次會跑全部的測試, 錯誤回報的訊息很現代化, 喜歡
  
* 可以獨立執行\src\bin中的binary file, 調用外部crate, 進行各種可能錯誤訊息的報告閱讀練習