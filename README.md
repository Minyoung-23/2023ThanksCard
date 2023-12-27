# 2023ThanksCard
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>2023년 미녕이와 함께 해주어 고마워요</title>
    <link rel="shortcut icon" href="https://e7.pngegg.com/pngimages/651/42/png-clipart-computer-icons-heart-favicon-love-symbols-love-color-pencil.png">
    <meta property="og:image"
        content="https://www.kindpng.com/picc/m/5-50664_happy-new-year-clipart-colourful-happy-new-year.png">
    <meta property="og:title" content="똑똑 비밀편지 도착">
    <meta property="og:description" content="Good Bye 2020">
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Gugi&family=Poor+Story&display=swap" rel="stylesheet">
    <script src="https://s3.ap-northeast-2.amazonaws.com/materials.spartacodingclub.kr/xmas/snow.js"></script>
    <style>
        * {
            font-family: 'Gugi', cursive;
            font-family: 'Poor Story', cursive;
        }

        body {
            background-color: #9b070f;
        }

        .envelope {

            width: 200px;
            height: 200px;

            background-image: url('https://pngimg.com/uploads/envelope/envelope_PNG18366.png');
            background-size: cover;
            background-position: center;

            margin: 200px auto 0px auto;
            cursor: pointer;
        }

        .envelope-msg {
            color: white;
            text-align: center;

        }

        .letter-close {
            display: block;
        }

        .letter-open {
            display: none;
        }

        .rtan {
            background-color: white;

            width: 200px;
            height: 200px;

            background-image: url('https://s3.ap-northeast-2.amazonaws.com/materials.spartacodingclub.kr/xmas/rtan.gif');
            background-size: cover;
            background-position: center;
            border-radius: 100px;

            margin: 100px auto 0px auto;
            border: 5px solid white;
            box-shadow: 0px 0px 10px 0px white;
        }

        h1 {
            color: white;
            text-align: center;
            margin-top: 30px;
            margin-bottom: 30px;
        }

        .messagebox {
            background-color: wheat;

            width: 400px;
            margin: auto;

            color: brown;

            padding: 30px;

            font-size: 20px;
            line-height: 30px;
            box-shadow: 0px 0px 10px 0px white;
        }

        .from {
            text-align: right;
            margin-bottom: 0px;
        }

        @media screen and (max-width: 760px) {
            .messagebox {
                width: 300px;
                padding: 20px;
            }

            .rtan {
                width: 150px;
                height: 150px;
                margin: 70px auto 0px auto;
            }

            h1 {
                font-size: 28px;
            }

            .envelope {
                margin: 150px auto 0px auto;
            }
        }
        }
    </style>
    <script>
        function open_letter() {
            document.getElementsByClassName("letter-close")[0].style.display = 'none'
            document.getElementsByClassName("letter-open")[0].style.display = 'block'
        }
        function go_rtan() {
            alert('앗, 어떻게 찾았지!')
            window.location.href = 'https://t1.daumcdn.net/thumb/R720x0/?fname=http://t1.daumcdn.net/brunch/service/user/iDz/image/y3pFBIgnTW_lWufDwO3dPRR78W4.jpg';
        }
    </script>
</head>

<body>
    <div class="letter-close">
        <div class="envelope" onclick="open_letter()"></div>
        <h2 class="envelope-msg">봉투를 열어봐!</h2>
    </div>

    <div class="letter-open">
        <div class="rtan" onclick="go_rtan()"></div>
        <h1>2020년 수고 많았어!</h1>
        <div class="messagebox">
            2020년 연말이네. <br />
            올해 이런저런 일이 많았는데 <br />
            멀리지만 같은 하늘아래 있다는게 <br />
            힘든시기 큰 힘이 됐어 <br />
            연말에 다 같이 못 봐서 아쉽다 <br />
            <p class="from">2021년 건강하자</p>
        </div>
    </div>


</body>

</html>
