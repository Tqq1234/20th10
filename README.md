<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chúc mừng 20/10</title>
    <link rel="stylesheet" href="20thanng10.css">
    <style>
        body {
            background-color: #ffe6e6;
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 0;
            padding: 0;
        }

        .container {
            padding: 20px;
            border-radius: 10px;
            background-color: #fff;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
            max-width: 600px;
            margin: 50px auto;
        }

        h1 {
            color: #ff6699;
        }

        .flower-image {
            width: 100%;
            max-width: 300px;
            height: auto;
            margin-top: 20px;
        }

        p {
            font-size: 18px;
            color: #333;
        }

        button {
            background-color: #ff6699;
            color: #fff;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
            margin-top: 20px;
        }

        button:hover {
            background-color: #ff3366;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Chúc mừng Ngày Phụ nữ Việt Nam 20/10!</h1>
        <img src="https://files.oaiusercontent.com/file-yKkxoWLhb06Ib22JthFAJFPl?se=2024-10-19T12%3A09%3A36Z&sp=r&sv=2024-08-04&sr=b&rscc=max-age%3D604800%2C%20immutable%2C%20private&rscd=attachment%3B%20filename%3Dbcc35305-75a8-4857-8f2c-1dd3180fd22f.webp&sig=DsFfvNZ5Fey32FqnGBZ99HJ%2B/Yt1d0ewjZoPjadZaD0%3D" alt="Hình ảnh hoa" class="flower-image">
        <p id="message">Nhân ngày 20 tháng 10 </p>
        <button onclick="showMoreMessage()">Bấm vào </button>
        <p id="extraMessage" style="display: none;">Con chúc mẹ luôn khỏe mạnh, xinh đẹp, ngày càng nhiều khách, vui vẻ và hạnh phúc mỗi ngày</p>
    </div>
    
    <script>
        function showMoreMessage() {
            var extraMessage = document.getElementById("extraMessage");
            if (extraMessage.style.display === "none") {
                extraMessage.style.display = "block";
            } else {
                extraMessage.style.display = "none";
            }
        }
    </script>
    
</body>
</html>
