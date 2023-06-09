<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Capa</title>

    <style>
        @import url('https://fonts.googleapis.com/css2?family=Monoton&family=Poppins:wght@300;400;500;600;700;800;900&display=swap');

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            text-decoration: none;
            border: none;
            outline: none;
            scroll-behavior: smooth;
            font-family: 'Poppins', sans-serif;
        }

        body {
            background-color: var(--bg-color);
        }

        :root {
            --bg-color: #1f242d;
            --second-bg-color: #323946;
            --text-color: #fff;
            --main-color: #0ef;
        }

        header {
            display: flex;
            justify-content: center;
        }

        header h2 {
            color: var(--main-color);
            text-align: center;
            font-size: 40px;
            margin-top: 20px;
        }

        .mid h1 {
            text-align: center;
            margin-top: 50px;
            color: var(--text-color);
        }

        .mid img {
            width: 22vw;
            justify-content: center;
            margin: 5% 40% 0 40%;
            animation: floatImage 4s ease-in-out infinite;
        }

        @keyframes floatImage {
            0% {
                transform: translateY(0);
            }

            50% {
                transform: translateY(-2.4rem);
            }

            100% {
                transform: translateY(0);
            }
        }

        /*                            Section 2                                                     */
        .section2 {
            display: flex;
            margin-left: 2%;
        }

        .habilidade {
            width: 48%;
        }

        .habilidade h1 {
            color: var(--main-color);
            text-align: center;
            font-size: 2rem;
        }

        .icons1 {
            padding-left: 28%;
        }

        .habilidade a {
            display: inline-flex;
            justify-content: center;
            align-items: center;
            width: 4rem;
            height: 4rem;
            background: transparent;
            border: .2rem solid var(--main-color);
            border-radius: 50%;
            font-size: 2rem;
            color: var(--main-color);
            margin: 3rem 1.5rem 3rem 0;
            transition: .5s ease;
        }

        .habilidade a:hover {
            background: var(--main-color);
            color: var(--second-bg-color);
            box-shadow: 0 0 1rem var(--main-color);
        }

        .icons2 {
            padding-left: 39%;
        }
    </style>

    <!-- Box Icons -->
    <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>

</head>

<body>

    <header>

        <h2> Igor Aguiar <span class="multiple-text"> </span> </h2>

    </header>

    <main>
        <section>
            <div class="mid">
                <h1>Olá eu sou o Igor Aguiar, estudante de programação e tecnologia!</h1>

                <img src="https://github.com/IgorAgui/ONE-Challenge1/blob/main/assets/img/eagle%20red.png?raw=true"
                    alt="">
            </div>
        </section>

        <section class="section2">
            <div class="habilidade">
                <h1>Habilidades</h1>
                <div class="icons1">
                    <a href=""><i class='bx bxl-html5'></i></a>
                    <a href=""><i class='bx bxl-css3'></i></a>
                    <a href=""><i class='bx bxl-javascript'></i></a>
                    <a href=""><i class='bx bxl-java'></i></a>
                </div>
            </div>

            <div class="habilidade">
                <h1>Redes Sociais</h1>
                <div class="icons1 icons2">
                    <a href=""><i class='bx bxl-linkedin'></i></a>
                    <a href=""><i class='bx bxl-gmail'></i></a>
                </div>
            </div>

        </section>

    </main>
    <!-- Typed js -->

    <script src="https://unpkg.com/typed.js@2.0.16/dist/typed.umd.js"></script>

    <script>

        //  Typed Js 

        const typed = new Typed('.multiple-text', {
            strings: ['Frontend Developer', 'Backend Developer', 'Vascaíno!!!'],
            typeSpeed: 100,
            backSpeed: 100,
            backDelay: 1000,
            loop: true
        });
    </script>

</body>

</html>
