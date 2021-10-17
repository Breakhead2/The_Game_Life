<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <script src="main.js" defer></script>
    <title>lesson1</title>
</head>

<body>

    <div class="paint-box">
        <div class="tools">
            <div class="tools-item">
                <button class="btn-start">Start</button>
            </div>
            <div class="tools-item">
                <button class="btn-stop">Stop</button>
            </div>
            <div class="tools-item">
                <button class="btn-clear">Reload</button>
            </div>
            <div class="tools-item">
                <input type="color" name="color" id="myColor" value="#002bd8">
            </div>
            <form action="#" oninput="result.value = (range_R.value)">
                <div class="tools-item">
                    <input type="range" min="0" max="100" id="range_R" step="1">
                    <p>R:
                        <output name="result" for="range_R"></output>
                    </p>
                </div>
            </form>
            <form action="#" oninput="result.value = (range_r.value)">
                <div class="tools-item">
                    <input type="range" min="0" max="100" id="range_r" step="1">
                    <p>r:
                        <output name="result" for="range_r"></output>
                    </p>
                </div>
            </form>
            <form action="#" oninput="result.value = (range_D.value)">
                <div class="tools-item">
                    <input type="range" min="0" max="100" id="range_D" step="1">
                    <p>D:
                        <output name="result" for="range_D"></output>
                    </p>
                </div>
            </form>
        </div>
        <div class="table">
            <canvas id="cnvs"></canvas>
        </div>
    </div>

</body>

</html>
