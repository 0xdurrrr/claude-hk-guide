# Crypto 虛擬卡與手機錢包設置指南

本文詳細說明如何申請 Avalanche Visa 虛擬卡，並透過 Kraken 以本地信用卡或 Apple Pay 購買 USDC 為虛擬卡充值，然後綁定手機錢包在 Claude 官網訂閱 Pro 或 Max 計劃。

> **適用對象：** 沒有海外信用卡，但希望在 [claude.ai](https://claude.ai) 官網直接付款訂閱的香港及澳門用戶。

---

## 整體流程

1. 下載 **Avalanche** App，完成 KYC，獲取一張 Visa 虛擬卡。
2. 下載 **Kraken** App，完成 KYC。
3. 在 Kraken 以本地信用卡或 Apple Pay 購買 USDC（美元穩定幣）。
4. 將 USDC 從 Kraken 轉帳至 Avalanche Card 地址。
5. 將虛擬卡加入 Apple Pay / Google Pay，在 claude.ai 付款。

---

## 一、申請 Avalanche Visa 虛擬卡

1. 在 App Store 或 Google Play 搜尋「**[Avalanche Card](https://www.avalanchecard.com/)**」並下載安裝。
2. 開啟 App，使用電郵註冊帳號。
3. 按指引完成 **KYC 身份驗證**：
   - 提供身份證明文件（香港身份證、澳門身份證或護照）。
   - 自拍照以進行人臉比對。
4. KYC 通過後，App 會自動為你生成一張 **Visa 虛擬卡**，卡號、到期日、CVV 均可在 App 內查看。
5. 在 App 內點擊「**Add Funds**」，即可查看你的 **Avalanche 收款地址**（AVAX C-Chain 地址，以 `0x` 開頭）。複製並記下此地址，稍後步驟會用到。

> **提示：** KYC 審核一般由幾分鐘至數小時不等，視乎平台當時審核量。

---

## 二、註冊 Kraken 並購買 USDC

Kraken 是規模較大的美國加密貨幣交易所，支援以本地信用卡或 Apple Pay 直接購買 USDC。USDC 是與美元 1:1 掛鉤的穩定幣（1 USDC ≈ 1 美元），價格穩定，適合用作支付。

1. 在 App Store 或 Google Play 搜尋「**[Kraken](https://www.kraken.com/zh-hant/features/cryptocurrency-apps)**」並下載安裝。
2. 註冊帳號並登入。
3. 按指引完成 **KYC 身份驗證**（與 Avalanche 類似，需要身份證明文件及自拍）。
4. 驗證完成後，於 App 內點擊「**Buy**」，選擇 **USDC**。
5. 付款方式選擇：
   - **本地信用卡**（Visa / Mastercard），或
   - **Apple Pay**（iOS 裝置可用）。
6. 輸入購買金額。建議購買金額略高於訂閱所需（例如訂閱 $20 美元可買 $22），以覆蓋後續轉帳手續費。
7. 確認購買，等待到帳（通常即時完成）。

> **提示：** 以信用卡或 Apple Pay 購買加密貨幣會收取約 3% 手續費，這是業界普遍水平。

---

## 三、將 USDC 轉帳至 Avalanche Card

1. 在 Kraken App 進入「**Funding**」或「資產」頁面，找到 USDC。
2. 點擊「**Withdraw**」或「提款」。
3. **網絡務必選擇「Avalanche C-Chain」。** 切勿選擇 Ethereum、Solana 或其他網絡，否則資金會遺失且無法追回。
4. **收款地址**填入步驟一中從 Avalanche Card App「Add Funds」頁面複製的地址。建議複製貼上，不要手動輸入。
5. 輸入提款金額，確認提交。系統可能要求電郵或 Google Authenticator 二次驗證。
6. 等待資金到帳（Avalanche C-Chain 網絡通常數秒至數分鐘內到帳）。

> **⚠️ 重要警告：** 加密貨幣轉帳不可逆轉。務必確認：
> - 網絡為 **Avalanche C-Chain**
> - 收款地址與 Avalanche Card App 中顯示的完全一致
>
> 建議首次轉帳時先以小額測試，確認到帳後再轉入餘下金額。

---

## 四、綁定手機錢包並付款

USDC 到帳後，在 Avalanche Card App 中會自動顯示為虛擬卡可用餘額（以美元計）。Avalanche App 內已提供一鍵綁定手機錢包的功能，無需手動輸入卡號。

1. 在 Avalanche App 中點擊「**Add to Apple Pay**」或「**Add to Google Pay**」（或類似按鈕），按指示完成將虛擬卡加入手機錢包。
2. 在手機瀏覽器（iPhone 用 Safari、Android 用 Chrome）打開 [claude.ai](https://claude.ai)，選擇訂閱計劃。
3. 在結帳頁填入一個**美國 Oregon 地址**（Oregon 為免稅州，可避免額外消費稅；可在 Google Maps 搜尋「Portland, Oregon」隨意取一個地址）。
4. 付款方式選擇 **Apple Pay**（iOS）或 **Google Pay**（Android）。
5. 勾選同意條款（Terms），確認付款即可完成訂閱。

> **提示：** 必須在對應系統的**手機瀏覽器**打開 claude.ai，電腦版網站不會顯示 Apple Pay / Google Pay 選項。

---

## 安全提示

- **只轉入所需金額：** 不建議長期在虛擬卡中存放大額資金。
- **小額測試：** 首次轉帳時先轉一小筆測試，成功後再轉餘下金額。

---

> **返回主指南：** [Claude 註冊使用指南](./README.md)
