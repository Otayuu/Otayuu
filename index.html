<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>発注システム</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            background-color: #f4f4f4;
        }
        .container {
            text-align: center;
        }
        #productSelection, #confirmation {
            display: none;
        }
        .product-grid {
            display: grid;
            grid-template-columns: repeat(3, 100px);
            grid-gap: 10px;
            margin: 20px 0;
        }
        .product-item {
            width: 100px;
            height: 100px;
            cursor: pointer;
            border: 2px solid white;
        }
        .product-item.selected {
            border-color: blue;
        }
        #selectedImage {
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- 発注先名入力画面 -->
        <div id="orderEntry">
            <h1>発注システム</h1>
            <label for="orderName">発注先名を入力してください:</label><br>
            <input type="text" id="orderName" placeholder="発注先名" required>
            <br><br>
            <button onclick="goToProductSelection()">OK</button>
        </div>

        <!-- 商品選択画面 -->
        <div id="productSelection">
            <h2>商品を選択してください</h2>
            <div class="product-grid">
                <!-- サンプル色の商品を表示 -->
                <div class="product-item" style="background-color: red;" onclick="selectProduct(this, '赤')"></div>
                <div class="product-item" style="background-color: green;" onclick="selectProduct(this, '緑')"></div>
                <div class="product-item" style="background-color: blue;" onclick="selectProduct(this, '青')"></div>
                <div class="product-item" style="background-color: yellow;" onclick="selectProduct(this, '黄')"></div>
                <div class="product-item" style="background-color: orange;" onclick="selectProduct(this, '橙')"></div>
                <div class="product-item" style="background-color: purple;" onclick="selectProduct(this, '紫')"></div>
                <div class="product-item" style="background-color: cyan;" onclick="selectProduct(this, '水色')"></div>
                <div class="product-item" style="background-color: pink;" onclick="selectProduct(this, 'ピンク')"></div>
                <div class="product-item" style="background-color: gray;" onclick="selectProduct(this, '灰色')"></div>
            </div>
            <label for="quantity">個数を入力してください:</label>
            <br>
            <input type="number" id="quantity" min="1" placeholder="個数" required>
            <br><br>
            <button onclick="confirmSelection()">OK</button>
        </div>

        <!-- 確認画面 -->
        <div id="confirmation">
            <h2>確認</h2>
            <p id="confirmationMessage"></p>
            <button onclick="sendOrder()">確認</button>
        </div>
    </div>

    <script>
        let selectedProduct = null;

        function goToProductSelection() {
            const orderName = document.getElementById('orderName').value;
            if (orderName === "") {
                alert("発注先名を入力してください");
                return;
            }
            document.getElementById('orderEntry').style.display = 'none';
            document.getElementById('productSelection').style.display = 'block';
        }

        function selectProduct(element, productName) {
            // 既に選択された商品がある場合、選択状態を解除
            if (selectedProduct) {
                selectedProduct.classList.remove('selected');
            }
            // 新しい商品を選択
            selectedProduct = element;
            selectedProduct.classList.add('selected');
            selectedProduct.productName = productName;
        }

        function confirmSelection() {
            const quantity = document.getElementById('quantity').value;
            if (!selectedProduct) {
                alert("商品を選択してください");
                return;
            }
            if (!quantity || quantity <= 0) {
                alert("正しい個数を入力してください");
                return;
            }

            // 確認メッセージ表示
            const orderName = document.getElementById('orderName').value;
            document.getElementById('confirmationMessage').innerText = 
                `${orderName} 様\n\n選択した商品: ${selectedProduct.productName}\n個数: ${quantity}\n\nご確認ください。`;

            // 商品選択画面を非表示、確認画面を表示
            document.getElementById('productSelection').style.display = 'none';
            document.getElementById('confirmation').style.display = 'block';
        }

        function sendOrder() {
            alert("ご注文が送信されました！");
            // 実際のメール送信はサーバーサイドで行います
            document.getElementById('confirmation').style.display = 'none';
            document.getElementById('orderEntry').style.display = 'block'; // 最初の画面に戻る
        }
    </script>
</body>
</html>
