# 15pp237.github.io
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>おみくじゲーム</title>
</head>
<body>
    <input id="omikuji_btn" type="button" value="おみくじを引く">
    <script>
        document.getElementById("omikuji_btn").onclick = function(){
            var rnd = Math.floor(Math.random()*6);
            var omikuji;
            if (rnd === 0) omikuji = "perfect"
            if (rnd === 1) omikuji = "great"
            if (rnd === 2) omikuji = "good"
            if (rnd === 3) omikuji = "nice"
            if (rnd === 4) omikuji = "nomal"
            if (rnd === 5) omikuji = "bad"
            alert(omikuji);
        }
    </script>
</body>
</html>
