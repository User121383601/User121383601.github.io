<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>欢迎访问我的自定义网页</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #4CAF50;
            color: white;
            text-align: center;
            padding: 20px;
        }
        main {
            padding: 20px;
            text-align: center;
        }
        footer {
            background-color: #4CAF50;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        .content-box {
            background-color: white;
            padding: 30px;
            margin: 20px auto;
            width: 80%;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            border-radius: 10px;
        }
        button {
            background-color: #4CAF50;
            color: white;
            border: none;
            padding: 10px 20px;
            margin-top: 20px;
            cursor: pointer;
            border-radius: 5px;
        }
        button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>

    <header>
        <h1>欢迎来到我的自定义网页</h1>
    </header>

    <main>
        <div class="content-box">
            <h2>我的网站内容</h2>
            <p>这是一个简单的网页示例，您可以在这里添加更多的内容、图片、链接等。</p>
            <button onclick="alert('按钮被点击了！')">点击我</button>
        </div>
    </main>

    <footer>
        <p>&copy; 2024 我的网页 | 保留所有权利</p>
    </footer>

</body>
</html>
