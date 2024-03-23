# Site BMW - Desenvolvido somente em HTML

Site desenvolvido na linguagem HTML e CSS, com o objetivo de cumprir a primeira atividade na disciplina de Desenvolvimento WEB I, no curso de Desenvolvimento de Software Multiplataforma, apresentando um barra de navegação, área de castro e uma galeria com fotos da BMW.

## 📄 Descrição

Para obter uma cópia basta baixar o arquivo INDEX.HTML com a pasta IMGAGENS, executar o arquivo em um navagador (Chrome, Edge, FireFox, etc.).


## 🚀 [Link do Site](https://meusitetestefatec.000webhostapp.com/atv_dwi/site_bmw/index.html)


## 📦 Aparência

<img src="/prints/print1.png">
<img src="/prints/print2.png">
<img src="/prints/print3.png">


## ⚙️ Código Fonte

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Primeira Página</title>
</head>
<body bgcolor="#0b1116" style="color: white; font-family: verdana;;">
    
    <table border="0" width="1300" heigth="500" align="center" cellspacing="4" cellpadding="7" bgcolor="#101820" background="imagens/car1.png">
        <tr heigth="50">
            <td widh="580"><img src="imagens/bmw.png" width="50" height="50" alt="NAME"></td>

            <!-- Menu do site-->
            <td align="center" width="'150" height="50"><a href="#" title="Go to Home"><button class="button" style="width: 100;height:30;background-color: #0b0b0b;border: 0;color: white;"><b><big>HOME</big></b></button></a></td>

            <td align="center" width="'150" height="50"><a href="#aboutus" title="Go to About"><button class="button" style="width: 100;height:30;background-color: #0b0b0b;border: 0;color: white;"><b><big>ABOUT</big></b></button></a></td>

            <td align="center" width="'150" height="50"><a href="#gallery" title="Go to Gallery"><button class="button" style="width: 100;height:30;background-color: #0b0b0b;border: 0;color: white;"><b><big>GALLERY</big></b></button></a></td>

            <td align="center" width="'150" height="50"><a href="#contact" title="Go to Contact"><button class="button" style="width: 100;height:30;background-color: #0b0b0b;border: 0;color: white;"><b><big>CONTACT</big></b></button></a></td>

            <!-- Redes Sociais-->
            <td align="center" width="30"><a href="https://twitter.com" title="Twitter"><img src="imagens/twitter.png" width="30" height="30"></a></td>

            <td align="center" width="30"><a href="https://web.facebook.com" title="Facebook"><img src="imagens/facebook.png" width="30" height="30"></a></td>

            <td align="center" width="30"><a href="https://instagram.com" title="Instagram"><img src="imagens/instagram.png" width="30" height="30"></a></td>

            <td align="center" width="30"><a href="https://youtube.com" title="YouTube"><img src="imagens/youtube.png" width="30" height="30"></a></td>

            <!-- Nome do Site-->
            <tr height="200" width="1300" rawspan="8">
                <td width="1300" colspan="9" align="center">
                    <h1 style="align:center"><big><big><big><b>BMW MOTORS FRANCA-SP</b></big></big></big></h1>
                    <P style="align:center"><big><big><big><b>A sua concessionária de confiança</b></big></big></big></P>
                </td>
            </tr>

            <tr>
                <td width="1300" height="400"></td>
            </tr>
            </tr

        </table>

            <!-- Galeria de Fotos -->
            <div id="gallery">
                <table border="0" width="1300" height="100" align="center" bgcolor="#0b1116">
                    <tr>
                        <td>
                            <center>
                                <p style="width: 250; height: 30; background-color: #0b1116;border: 0; color: white; font-family: verdana;">
                                    <big><big><b>GALLERY</b></big></big>
                                </p>
                            </center>
                        </td>
                    </tr>
                </table>
            </div>

                <table style="border: 1;border-collapse: collapse;" width="1300" heigth="300" align="center" bgcolor="#101820" align="center" border-collapdse="collapse">

                    <tr>
                        <td align="center" width="400" heigth="500">
                            <img src="imagens/car4.png" width="400" height="500" title="ALI">
                        </td>
                        <td align="center" rowspan="2" width="400" heigth="500">
                            <img src="imagens/car3.png" width="250" height="500" title="ALI">
                        </td>
                        <td align="center" rowspan="2" width="400" heigth="500">
                            <img src="imagens/car6.png" width="250" height="500" title="ALI">
                        </td>
                        <td align="center" width="400" heigth="500">
                            <img src="imagens/car5.png" width="400" height="500">
                        </td>
                    </tr>
                </table>
            </div>

            <!-- Sobre Nós -->
            <div id="aboutus">
                <table border="0" width="1300" height="100" align="center" bgcolor="#0b1116">
                    <tr>
                        <td>
                            <center>
                                <p style="width: 250; height: 30; background-color: #0b1116;border: 0; color: white; font-family: verdana;">
                                    <big><big><b>ABOUT IS</b></big></big>
                                </p>
                            </center>
                        </td>
                    </tr>
                </table>

                <table border="0" width="1300" height="500" align="center" bgcolor="#0b1116">
                    <tr>
                        <td rowspan="2" width="100" height="500"></td>
                        <td width="500" height="500">
                            <p style="font-family: verdana;color: lightgrey;">
                                <big><big>What is Lorem Ipusum?</big></big><br><br>
                                <big>
                                    Lorem Ipsum is simply dummy text of the printing and typesetting industry. 
                                    Lorem Ipsum has been the industry's standard dummy text ever since the 1500s,
                                    when an unknown printer took a galley of type and scrambled it to meke a type specimen book. 
                                    It has survived not only five centuries. 
                                    But also the leap into electronic typesetting, remaining essentially unchanged.
                                </big>
                            </p>
                        </td>
                        <td align="center" width="700" height="500"><img src="imagens/car2.png" width="700" height="500"></td>
                    </tr>
                </table>
               
            </div>

            <!-- Contato -->
            <div id="contact">
                <table border="0" width="1300" height="100" align="center" bgcolor="#0b1116">
                    <tr>
                        <td>
                            <center>
                                <p style="width: 250; height: 30; background-color: #0b1116;border: 0; color: white; font-family: verdana;">
                                    <big><big><b>CONTACT US</b></big></big>
                                </p>
                            </center>
                        </td>
                    </tr>
                </table>

                <table border="0" width="1300" height="300" align="center" bgcolor="#101820">
                    <tr>
                        <td width="300"></td>
                        <td>
                            <form>
                                <p align="left">Username</p>
                                <input type="text"><br>
                                <p align="left">Email</p>
                                <input type="text"><br><br><br>
                                <input type="submit">
                            </form>
                        </td>
                        <td align="center">
                            <textarea name="" id="" cols="50" rows="12" textsize="6">
                            </textarea>
                        </td>
                        <td width="300"></td>
                    </tr>
                </table>

                <table border="0" width="1300" height="30" align="center" bgcolor="#0b1116">
                    <tr>
                        <td>
                        </td>
                    </tr>
                </table>

                <table border="0" width="1300" height="30" align="center">
                    <tr>
                        <td>
                            <p align="center"><b>BMW</b></p>
                            <p align="center">acb@gmail.com</p>
                            <p align="center">Phone Number</p>
                            <p align="center">Name company name Street City area/Discrict City/<br>Town/Village County Postal code Country</p>

                            <p align="center" width="40">
                                <a href="https://twitter.com" title="Twitter"><img src="imagens/twitter.png" width="40" height="40"></a>
                                <a href="https://web.facebook.com" title="Facebook"><img src="imagens/facebook.png" width="40" height="40"></a>
                                <a href="https://instagram.com" title="Instagram"><img src="imagens/instagram.png" width="40" height="40"></a>
                                <a href="https://youtube.com" title="YouTube"><img src="imagens/youtube.png" width="40" height="40"></a>
                            </p>
                        </td>
                    </tr>
                </table>

            </div>

</body>
</html>
```

## 🛠️ Construído com

* Visual Studio Code - Editor de Código-Fonte;
* HTML5 - Linguagem de Marcação;


## ✒️ Autor

* **Luís Pedro Dutra Carrocini** - *Desenvolvimento do Código-Fonte;*


## 🎁 Expressões de gratidão

* Conte a outras pessoas sobre este projeto 📢;
* Agradecimento ao 🫂 [Prof. Márcio](https://github.com/marciofunes);
