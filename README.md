<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>صفحة ويب بسيطة</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
        }
        h1 {
            color: #333;
            margin-top: 50px;
        }
        button {
            padding: 10px 20px;
            font-size: 16px;
            background-color: #e74c3c; /* لون أحمر */
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #c0392b; /* لون أحمر داكن عند التحويم */
        }
        #output {
            margin-top: 20px;
            font-size: 18px;
            color: #555;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <h1>مرحبًا! اضغطي الزر أدناه</h1>
    <button onclick="showMessage()">اضغط هنا</button>
    <div id="output"></div>

    <script>
        function showMessage() {
            document.getElementById('output').textContent = 'انتي احلى بنية عرفتها واكثر بنية طيبة واصدق انسانة يمكن اني كلش محظوظ لان انتي صديقتي';
        }
    </script>
</body>
</html>
