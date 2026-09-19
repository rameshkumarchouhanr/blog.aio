# blog.aio
# About Jekyll build errors for GitHub Pages sites  If Jekyll encounters an error building your GitHub Pages site locally or on GitHub, you'll receive an error message with more information.  > \[!NOTE] While the `github-pages` gem remains supported for some workflows, GitHub Actions is now the recommended approach for deploying and auto
<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>मेरा AI असिस्टेंट</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="chat-container">
        <header>
            <h2>मेरा AI असिस्टेंट</h2>
            <p>आप यहाँ बात कर सकते हैं!</p>
        </header>
        <div id="chat-box" class="chat-box">
            <div class="message ai-message">नमस्ते! मैं आपका AI असिस्टेंट हूँ। मैं आपकी क्या मदद कर सकता हूँ?</div>
        </div>
        <div class="input-area">
            <input type="text" id="user-input" placeholder="यहाँ टाइप करें...">
            <button id="send-btn">भेजें</button>
        </div>
    </div>
    <script src="script.js"></script>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    background-color: #f0f2f5;
    margin: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
}
.chat-container {
    width: 100%;
    max-width: 400px;
    background: white;
    border-radius: 10px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    display: flex;
    flex-direction: column;
    overflow: hidden;
}
header {
    background: #4a90e2;
    color: white;
    padding: 15px;
    text-align: center;
}
.chat-box {
    flex: 1;
    padding: 15px;
    overflow-y: auto;
    height: 300px;
    display: flex;
    flex-direction: column;
    gap: 10px;
}
.message {
    padding: 10px 15px;
    border-radius: 8px;
    max-width: 80%;
}
.ai-message {
    background: #e4e6eb;
    align-self: flex-start;
}
.user-message {
    background: #4a90e2;
    color: white;
    align-self: flex-end;
}
.input-area {
    display: flex;
    padding: 10px;
    border-top: 1px solid #ddd;
}
input {
    flex: 1;
    padding: 10px;
    border: 1px solid #ddd;
    border-radius: 5px;
    outline: none;
}
button {
    background: #4a90e2;
    color: white;
    border: none;
    padding: 10px 15px;
    margin-left: 5px;
    border-radius: 5px;
    cursor: pointer;
}
