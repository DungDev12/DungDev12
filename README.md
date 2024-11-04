<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SVG với HTML</title>
    <style>
        body {
            margin: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f0f0f0;
        }
    </style>
</head>
<body>
    <svg fill="none" viewBox="0 0 1200 750" width="1200" height="750" xmlns="http://www.w3.org/2000/svg">
        <foreignObject width="100%" height="100%">
            <div xmlns="http://www.w3.org/1999/xhtml">
                <style>
                    @keyframes typing {
                        from { width: 0 }
                        to { width: 100% }
                    }
                    .container {
                        font-family: system-ui, -apple-system, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
                        display: flex;
                        flex-direction: column;
                        align-items: left;
                        justify-content: center;
                        margin: 0;
                        width: 100%;
                        height: 750px;
                        background-color: rgba(255, 255, 255, 0.8);
                        padding: 20px;
                    }
                    .text {
                        font-size: 24px;
                        white-space: nowrap;
                        overflow: hidden;
                        border-right: 4px solid black;
                        animation: typing 4s steps(30, end) infinite;
                    }
                </style>
                <div class="container">
                    <div class="text">Xin chào, tôi là Dũng!</div>
                </div>
            </div>
        </foreignObject>
    </svg>
</body>
</html>
