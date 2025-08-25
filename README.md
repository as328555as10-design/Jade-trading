<!DOCTYPE html>
<html lang="zh-Hant">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>玉石 OTC 中間人免責聲明</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="container">
    <h1>玉石 OTC 中間人免責聲明</h1>
    
    <p>本聲明適用於使用本人提供的玉石 OTC 中間人撮合服務的所有買賣雙方。</p>
    
    <h2>1. 中間人角色限定</h2>
    <p>本人僅為玉石交易的中間撮合者，不持有商品，不保證商品真偽或品質。</p>

    <h2>2. 交易風險</h2>
    <p>買賣雙方自行承擔商品真偽、交付及價格風險，任何爭議由買賣雙方協商或依法律途徑解決。</p>

    <h2>3. 資金管理聲明</h2>
    <p>本人可能協助將買方資金轉換為 USDT 或指定方式交給賣方，但不保證商品交付或品質。</p>

    <h2>4. 佣金說明</h2>
    <p>中間人佣金僅於交易完成後收取，比例由雙方事先協議。</p>

    <h2>5. 交易前確認</h2>
    <p>使用本人服務即表示買賣雙方同意本免責條款，中間人不承擔任何法律責任。</p>

    <h2>建議</h2>
    <ul>
      <li>盡量使用第三方托管或 Escrow 平台進行資金流轉。</li>
      <li>建議買方與賣方使用第三方鑑定或物流追蹤以降低交易風險。</li>
      <li>保留所有交易訊息、轉帳及物流憑證，以便後續追蹤和信用管理。</li>
    </ul>

    <div class="checkbox-container">
      <input type="checkbox" id="agreeCheckbox">
      <label for="agreeCheckbox">我已閱讀並同意上述免責聲明</label>
    </div>
    <button class="agree-btn" id="agreeBtn" disabled>同意並繼續交易</button>
  </div>

  <script>
    const agreeCheckbox = document.getElementById('agreeCheckbox');
    const agreeBtn = document.getElementById('agreeBtn');

    agreeCheckbox.addEventListener('change', function() {
      agreeBtn.disabled = !this.checked;
    });

    agreeBtn.addEventListener('click', function() {
      alert("感謝您的同意，您現在可以進行交易。");
      // 可導向交易頁面
      // window.location.href = "https://你的交易頁面網址.com";
    });
  </script>
</body>
</html>
