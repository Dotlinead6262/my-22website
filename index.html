<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>स्वागत है</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-image: url('images/background.jpg');
            background-size: cover;
            background-position: center;
            background-repeat: no-repeat;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            margin: 0;
        }
        .welcome-box {
            background: rgba(255, 255, 255, 0.9);
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.2);
            text-align: center;
            max-height: 80vh;
            overflow-y: auto;
        }
        .welcome-box h1 {
            color: #2ecc71;
            margin: 0;
        }
        .welcome-box p {
            color: #333;
            margin: 10px 0;
        }
        .upload-section {
            margin: 20px 0;
        }
        .upload-section input[type="file"] {
            margin-bottom: 10px;
        }
        .upload-section button {
            padding: 10px 20px;
            background: #3498db;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .upload-section button:hover {
            background: #2980b9;
        }
        video {
            width: 100%;
            max-width: 500px;
            margin-top: 20px;
            display: block;
        }
    </style>
</head>
<body>
    <div class="welcome-box">
        <h1>You are welcome!</h1>
        <p>आपका स्वागत है!</p>

        <!-- अपलोड सेक्शन -->
        <div class="upload-section">
            <input type="file" id="videoInput" accept="video/*" multiple>
            <button onclick="uploadVideos()">Upload Videos</button>
        </div>

        <!-- वीडियो यहाँ डायनामिकली जोड़े जाएंगे -->
        <div id="videoContainer">
            <!-- डिफ़ॉल्ट वीडियो (अगर चाहें तो) -->
            <video controls>
                <source src="videos/myvideo.mp4" type="video/mp4">
                आपका ब्राउज़र वीडियो टैग को सपोर्ट नहीं करता।
            </video>
        </div>
    </div>

    <script>
        function uploadVideos() {
            const videoInput = document.getElementById('videoInput');
            const videoContainer = document.getElementById('videoContainer');
            const files = videoInput.files;

            // अगर कोई फाइल सिलेक्ट नहीं की गई
            if (files.length === 0) {
                alert("कृपया कम से कम एक वीडियो सिलेक्ट करें!");
                return;
            }

            // हर सिलेक्ट की गई फाइल के लिए
            for (let i = 0; i < files.length; i++) {
                const file = files[i];

                // सुनिश्चित करें कि फाइल एक वीडियो है
                if (!file.type.startsWith('video/')) {
                    alert(`${file.name} एक वीडियो फाइल नहीं है!`);
                    continue;
                }

                // नया वीडियो टैग बनाएँ
                const videoElement = document.createElement('video');
                videoElement.controls = true;
                videoElement.style.width = '100%';
                videoElement.style.maxWidth = '500px';
                videoElement.style.marginTop = '20px';
                videoElement.style.display = 'block';

                // वीडियो का URL बनाएँ और सेट करें
                const videoURL = URL.createObjectURL(file);
                videoElement.src = videoURL;

                // वीडियो को कंटेनर में जोड़ें
                videoContainer.appendChild(videoElement);
            }

            // इनपुट को रीसेट करें ताकि अगली बार नई फाइल्स सिलेक्ट की जा सकें
            videoInput.value = '';
        }
    </script>
</body>
</html>
