<html lang="en" translate="no">
<head>
    <meta charset="UTF-8">
    <meta name="google" content="notranslate">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no">
    <meta name="description" content="¡Registra aquí tus quinielas! - Quiniela Liga MX">
    <meta name="keywords" content="Quiniela, Liga MX, Apostar, Pronósticos, Eurocopa, Copa America">
    <title>Quiniela Jalisco</title>
   
</head>

<body>
    <p id='bolsa'><br><span id='bolsatxt'></span><span id='cantidad' style="color:yellow"></span></p>
    <div class="quiniela" id="quiniela">
        <div class="aux"><h3 style="padding: 5px 7px" onclick="clean()"><ion-icon name="close-outline"></ion-icon></h3></div>
        <div class="partido">
            <span id="L1" onclick="selection(this)"></span>
            <div id="_"></div>
            <span id="E1" onclick="selection(this)"></span>
            <div id="_"></div>
            <span id="V1" onclick="selection(this)"></span>
        </div>
        <div class="partido">
            <span id="L2" onclick="selection(this)"></span>
            <div id="_"></div>
            <span id="E2" onclick="selection(this)"></span>
            <div id="_"></div>
            <span id="V2" onclick="selection(this)"></span>
        </div>
        <div class="partido">
            <span id="L3" onclick="selection(this)"></span>
            <div id="_"></div>
            <span id="E3" onclick="selection(this)"></span>
            <div id="_"></div>
            <span id="V3" onclick="selection(this)"></span>
        </div>
        <div class="partido">
            <span id="L4" onclick="selection(this)"></span>
            <div id="_"></div>
            <span id="E4" onclick="selection(this)"></span>
            <div id="_"></div>
            <span id="V4" onclick="selection(this)"></span>
        </div>
        <div class="partido">
            <span id="L5" onclick="selection(this)"></span>
            <div id="_"></div>
            <span id="E5" onclick="selection(this)"></span>
            <div id="_"></div>
            <span id="V5" onclick="selection(this)"></span>
        </div>
        <div class="partido">
            <span id="L6" onclick="selection(this)"></span>
            <div id="_"></div>
            <span id="E6" onclick="selection(this)"></span>
            <div id="_"></div>
            <span id="V6" onclick="selection(this)"></span>
        </div>
        <div class="partido">
            <span id="L7" onclick="selection(this)"></span>
            <div id="_"></div>
            <span id="E7" onclick="selection(this)"></span>
            <div id="_"></div>
            <span id="V7" onclick="selection(this)"></span>
        </div>
        <div class="partido">
            <span id="L8" onclick="selection(this)"></span>
            <div id="_"></div>
            <span id="E8" onclick="selection(this)"></span>
            <div id="_"></div>
            <span id="V8" onclick="selection(this)"></span>
        </div>
        <div class="partido">
            <span id="L9" onclick="selection(this)"></span>
            <div id="_"></div>
            <span id="E9" onclick="selection(this)"></span>
            <div id="_"></div>
            <span id="V9" onclick="selection(this)"></span>
        </div>
    <div class="partido">
            <span id="L10" onclick="selection(this)"></span>
            <div id="_"></div>
            <span id="E10" onclick="selection(this)"></span>
            <div id="_"></div>
            <span id="V10" onclick="selection(this)"></span>
        </div>
        <h1 id="text"></h1>
    </div>
    <table class="botonera">
    <tr>
        <td width="37%">
            <h2 class="botonenviar" onclick="send()"> Enviar <span>0</span>&nbsp <img src="https://logodownload.org/wp-content/uploads/2015/04/whatsapp-logo-5.png" height="23px" style="position: absolute;"></ion-icon></h2>
        </td>
        <td width="14%">
            <h2 id="botonlisto" onclick="save()"><ion-icon name="add-outline"></ion-icon></h2>
        </td>
        <td width="14%"> 
            <h2 id="botonborrar" onclick="deleteall()"><ion-icon name="trash-outline" id="trash"></ion-icon></h2>
        </td>
        <td width="35%">
            <table id="nombrebox">
                <tr style="height: 9px"><td id="nombretext"> &nbsp Nombre</td><td></td></tr>
                <tr style="height: 20px"><td><input id="nombre" type="text" placeholder="" maxlength="20" spellcheck="false"></td><td><label id="borrarnombre" onclick="clearname()"><ion-icon name="backspace"></ion-icon></label></td></tr>
            </table>
        </td>
    </tr>
    </table>
        <!--<input type="checkbox" id="checkcombinaciones" onclick="allowcombination()"><h6> <ion-icon name="apps"></ion-icon></h6>-->
        <table style="margin-top: 3px; width:100%">
            <tr>
                <td style="width: 37%">
                    <label id="random" onclick="random()">Aleatorio</ion-icon></label>
                </td>
                <td style="width: 40%">
                    <label id="checkcombinaciones" onclick="allowcombination()">
                        Dobles y Triples
                    </label>
                </td>
                <td style="width: 23%"></td>
            </tr>
        </table>
        <!--<script src="https://unpkg.com/ionicons@5.1.2/dist/ionicons.js"></script>-->

        <br><br>

    <div>
    <h4 id="costo">Costo: $0</h4><h4 id="total">Total: $0</h4><br>
    </div>
    <div>
        <h4 id="numquinielas">0 Quiniela(s)</h4>
    </div>
    <br>
    <!--<p id="display"></p>-->
    <div id="divaux" translate="no">
        <table id="display">
        </table>
    </div>
    <!--<button id="undo" onclick="remove()"><ion-icon name="arrow-undo-outline"></ion-icon></button>-->
    <br>
</body>
</html>
