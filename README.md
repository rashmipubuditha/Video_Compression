<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <div class="container">
        <h1>Video Compression with FFmpeg</h1>
        <p>This project demonstrates video compression techniques using the FFmpeg library. It covers the following features:</p>
        <ul>
            <li>Modifying the encoder to encode an <strong>IBBBPBBPI</strong> pattern.</li>
            <li>Extracting frame types (I, B, P) from the video.</li>
            <li>Adjusting the quality of the decoded output using CRF.</li>
            <li>Obtaining compressed bit streams for different bitrates (1000, 2500, 10000) and comparing the output quality after decoding.</li>
            <li>Calculating PSNR between the original and decoded videos at different bitrates.</li>
            <li>Viewing the decoded frames and the video.</li>
            <li>Dropping B frames at a rate of 20% and showing the decoding output.</li>
        </ul>
    </div>
</body>
</html>
