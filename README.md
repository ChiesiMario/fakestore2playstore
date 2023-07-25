# 💡 說明
安裝 MicroG 的方法有很多，但如果你並非使用 LineageOS for MicroG 的話，我不太推薦你使用該模塊，其他選擇：

- 設備擁有第三方 Recovery 則推薦直接刷入 [microG unofficial installer](https://forum.xda-developers.com/t/mod-flashable-microg-unofficial-installer.3432360/)
  - ✅ MicroG
  - ✅ 可選安裝 Play Store 或 FakeStore
  - ✅ 可還原 Play Store 內購
  
  一些我遇到的問題：
  - ⛔ OTA 之後 MicroG 丟失
  
- 擁有 Magisk 或 KernelSU 推薦刷入模塊：[microG_GSync](https://github.com/ozingi/microG_GSync)
  - ✅ MicroG
  - ✅ 包括 Play Store
  - ✅ 可還原 Play Store 內購
  
  一些我遇到的問題：
  - ⛔ Play Store 無法使用，可嘗試下載 [microG unofficial installer](https://forum.xda-developers.com/t/mod-flashable-microg-unofficial-installer.3432360/) 提取替換裏面的 Play Store 。
  - ⛔ 最嚴重的問題是安裝一些其他模塊後有衝突，MicroG 套件會變成非系統應用，導致無法使用。
 
# ⭐️ 刷入 fakestore2playstore
1. 使用 Root Explorer 確認 FakeStore 的安裝位置
2. 在 [Releases](https://github.com/ChiesiMario/fakestore2playstore/releases) 下載模塊 
  - FakeStore 安裝位置在 `/system/pirv-app` 則下載：`fakestore2playstore-xxxx.zip`
  - FakeStore 安裝位置在 `/system/product/pirv-app` 則下載：`fakestore2playstore-product-xxxx.zip`
3. ❗務必先確認好 FakeStore 的位置，否則可能不生效，不排除會有無法開機的情況，提前做好如果無法開機如何刪模塊的準備
4. 使用 Magisk 或者 KernelSU 刷入
5. Enjoy it.
