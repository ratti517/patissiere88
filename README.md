<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>patissiere88 - 顧客管理サイト</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #ff6f61;
            color: white;
            padding: 20px;
            text-align: center;
        }
        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background-color: white;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1 {
            color: #333;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }
        table, th, td {
            border: 1px solid #ddd;
        }
        th, td {
            padding: 10px;
            text-align: left;
        }
        th {
            background-color: #f2f2f2;
        }
        .add-customer {
            margin-top: 20px;
            text-align: right;
        }
        .add-customer button {
            background-color: #ff6f61;
            color: white;
            border: none;
            padding: 10px 20px;
            cursor: pointer;
        }
        .add-customer button:hover {
            background-color: #ff4c3b;
        }
    </style>
</head>
<body>
    <header>
        <h1>patissiere88 - 顧客管理サイト</h1>
    </header>
    <div class="container">
        <h2>顧客リスト</h2>
        <table>
            <thead>
                <tr>
                    <th>名前</th>
                    <th>メールアドレス</th>
                    <th>電話番号</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>山田 太郎</td>
                    <td>taro.yamada@example.com</td>
                    <td>090-1234-5678</td>
                </tr>
                <tr>
                    <td>鈴木 花子</td>
                    <td>hanako.suzuki@example.com</td>
                    <td>080-9876-5432</td>
                </tr>
            </tbody>
        </table>
        <div class="add-customer">
            <button>顧客を追加</button>
        </div>
    </div>
</body>
