<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>gestão 2 teste</title>
    <style>
        html {
            margin: 0;
        }

        body {
            margin: 0;
        }

        .container {
            height: 100%;
            background-color: #212b36;
            display: flex;
            justify-content: space-around;
        }

        .sub-container {

            flex: 1;
            display: flex;
            justify-content: center;
            flex-direction: column;
            border: none;
            padding: 0 24px;
            left: 0;
            position: absolute;
            box-shadow: 40px 20px 40px rgb(0 0 0 / 80%);
            height: 100%;
            width: 50%;
            background-color: #212b36;
        }

        .foto {
            padding: 0 24px;
            width: 50%;
            height: 100vh;
            margin-left: auto;
            background-color: #293139;
        }

        .cel {
            width: 38%;
            position: absolute;
        }

        .sn {
            display: flex;
            justify-content: center;
            background-color: #212b36;
        }

        /*caixa de log*/
        .uno {
            font-size: 30px;
            margin-bottom: 34px;
            text-align: center;
            justify-content: center;
            color: white;
        }

        .caixa {
            display: flex;
            flex-direction: column;
            justify-content: center;
            margin-bottom: 24px;
            padding: 18px 16px 16px 16px;
            border-radius: 8px;
            box-shadow: 0 8px 20px rgb(0 5 10 / 20%);
            background-color: #213b39;
            border: none;
        }

        .campo {
            border-radius: 8px;
            padding: 18px 18px 18px 18px;
            width: 100%;
            background-color: #151c23;
            display: flex;
            align-items: center;
        }

        .login {
            display: flex;
            width: 100%;

            padding: 4px 4px 4px 4px;
        }

        .jss {
            margin-top: 16px;
        }

        .acessar {
            margin-left: 50%;
            padding: 8px 8px 8px 8px;
            width: 50%;

        }

        .copy {
            left: 0;
            right: 0;
            bottom: 0;
            margin-left: auto;
            margin-right: auto;
        }

        .powered {
            left: 0;
            right: 0;
            bottom: 0;
            margin-left: auto;
            margin-right: auto;
        }

        .aviso {
            font-size: 10px;
            left: 0;
            right: 0;
            bottom: 0;
            position: absolute;
            text-align: center;
        }
    </style>
</head>

<body>
    <div class="container">

        <div class="sub-container">
            <div class="uno">
                <div class="gn">Gestão do seu negocio</div>
            </div>

            <div class="caixa">
                <div class="login">
                    <div class="user">login</div>
                </div>

                <div class="login">
                    <input class="campo" id="input" type="" name="usuario" placeholder="usuario" />
                </div>

                <div class="login">
                    <input class="campo" id="input" type="senha" name="senha" placeholder="senha" />
                </div>
                <div class="botao">
                    <div class="jss">
                        <button class="acessar">Acessar</button>
                    </div>
                </div>
            </div>
            <div class="aviso">
                <p class="copy">Copyright © UNO 2023.</p>
                <p class="powered">powered by Unobject</p>
            </div>
        </div>

        <div class="foto">
            <div class="ng">
                Seu negocio
            </div>
            <div class="ps">
                na palma da sua mao
            </div>
            <div class="sn">
                <img src="cell.png" class="cel">
            </div>
        </div>

    </div>

</body>

</html>
