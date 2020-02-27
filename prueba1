<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Generador Quiniela MX</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
</head>
<body>
    <div class="container body-content">
<style>
    body {
        text-align: center;
        background-color: #F3F0F0;
    }
    .dataHeader {
        width: 50%;
        margin: 0 auto;
    }
    .dataHeader>div {
        display: inline-block;
        margin:0 ;
        padding: 0;
        font-size: 1.5em;
        font-weight: bold;
    }
    .tableContainer {
        width: 50%;
        margin: 0 auto;
        font-size: 1.5em;
    }
    @@media screen and (max-width: 800px) {
        .tableContainer {
            width: 70%;
        }
        .dataHeader {
            width: 70%;
        }
    }
    @@media screen and (max-width: 600px) {
        .tableContainer {
            width: 80%;
        }
        .dataHeader {
            width: 80%;
        }
    }
    @@media screen and (max-width: 400px) {
        .tableContainer {
            width: 100%;
        }
        .dataHeader {
            width: 100%;
        }
    }
    h3 > input {
        text-align: center;
        width: 55%;
    }

    .row {
        margin: auto;
        text-align: center;
    }

        .row.border {
            margin: 1% auto;
        }

            .row.border > div {
                margin: 0 auto;
            }

    .col-4 > input[type=text] {
        width: 100%;
    }
    .matchNon {
        background-color: #E5E5E5;
    }
    .matchPar {
        background-color: #F6D5D5;
    }

    .resultPossibilities {
        width: 100%;
    }

        .resultPossibilities > div {
            height: 1.5em;
            margin: 0 2%;
        }

    .teamCls {
        padding: 0;
        margin: 0;
    }

        .teamCls > input[type=text] {
            width: 100%;
            padding: 0;
            margin: 0;
            text-align: center;
            color: #990000;
            font-weight: bolder;
        }

    .resultOption {
        padding: 0;
        margin: 0;
        background-color: white;
    }

    input[type=radio] {
        display: none;
    }

    .playerDataRow {
    }

    .playerData {
        text-align: right;
        font-size: 1.5em;
        margin: 1%;
    }
</style>
<h2>GENERADOR DE QUINIELA</h2>
<div><h3><input type="text" value="JORNADA 8" /></h3></div>
<div class="dataHeader">
    <div class="col-5" style="text-align: left">
        Local
    </div>
    <div class="col-2" style="text-align: center">
        Empate
    </div>
    <div class="col-4" style="text-align: right">
        Visita
    </div>
</div>
<div class="tableContainer">
    <div class="row border">
        <div class="col-1 border resultOption" name="match1" onclick="checkRadio('1L', this, 'matchNameId1L')" id="matchNameId1L"></div>
        <div class="col-4 teamCls"><input type="text" value="TOLUCA" class="matchNon" /></div>
        <div class="col-1 border resultOption" name="match1" onclick="checkRadio('1E', this, 'matchNameId1E')" id="matchNameId1E"></div>
        <div class="col-4 teamCls"><input type="text" value="MONTERREY" class="matchNon" /></div>
        <div class="col-1 border resultOption" name="match1" onclick="checkRadio('1V', this, 'matchNameId1V')" id="matchNameId1V"></div>
    </div>
    <div class="row border">
        <div class="col-1 border resultOption" name="match2" onclick="checkRadio('2L', this, 'matchNameId2L')" id="matchNameId2L"></div>
        <div class="col-4 teamCls"><input type="text" value="SAN LUIS" class="matchPar" /></div>
        <div class="col-1 border resultOption" name="match2" onclick="checkRadio('2E', this, 'matchNameId2E')" id="matchNameId2E"></div>
        <div class="col-4 teamCls"><input type="text" value="JUAREZ" class="matchPar" /></div>
        <div class="col-1 border resultOption" name="match2" onclick="checkRadio('2V', this, 'matchNameId2V')" id="matchNameId2V"></div>
    </div>
    <div class="row border">
        <div class="col-1 border resultOption" name="match3" onclick="checkRadio('3L', this, 'matchNameId3L')" id="matchNameId3L"></div>
        <div class="col-4 teamCls"><input type="text" value="MORELIA" class="matchNon" /></div>
        <div class="col-1 border resultOption" name="match3" onclick="checkRadio('3E', this, 'matchNameId3E')" id="matchNameId3E"></div>
        <div class="col-4 teamCls"><input type="text" value="CRUZ AZUL" class="matchNon" /></div>
        <div class="col-1 border resultOption" name="match3" onclick="checkRadio('3V', this, 'matchNameId3V')" id="matchNameId3V"></div>
    </div>
    <div class="row border">
        <div class="col-1 border resultOption" name="match4" onclick="checkRadio('4L', this, 'matchNameId4L')" id="matchNameId4L"></div>
        <div class="col-4 teamCls"><input type="text" value="TIJUANA" class="matchPar" /></div>
        <div class="col-1 border resultOption" name="match4" onclick="checkRadio('4E', this, 'matchNameId4E')" id="matchNameId4E"></div>
        <div class="col-4 teamCls"><input type="text" value="PUEBLA" class="matchPar" /></div>
        <div class="col-1 border resultOption" name="match4" onclick="checkRadio('4V', this, 'matchNameId4V')" id="matchNameId4V"></div>
    </div>
    <div class="row border">
        <div class="col-1 border resultOption" name="match5" onclick="checkRadio('5L', this, 'matchNameId5L')" id="matchNameId5L"></div>
        <div class="col-4 teamCls"><input type="text" value="PACHUCA" class="matchNon" /></div>
        <div class="col-1 border resultOption" name="match5" onclick="checkRadio('5E', this, 'matchNameId5E')" id="matchNameId5E"></div>
        <div class="col-4 teamCls"><input type="text" value="QUERETARO" class="matchNon" /></div>
        <div class="col-1 border resultOption" name="match5" onclick="checkRadio('5V', this, 'matchNameId5V')" id="matchNameId5V"></div>
    </div>
    <div class="row border">
        <div class="col-1 border resultOption" name="match6" onclick="checkRadio('6L', this, 'matchNameId6L')" id="matchNameId6L"></div>
        <div class="col-4 teamCls"><input type="text" value="AMERICA" class="matchPar" /></div>
        <div class="col-1 border resultOption" name="match6" onclick="checkRadio('6E', this, 'matchNameId6E')" id="matchNameId6E"></div>
        <div class="col-4 teamCls"><input type="text" value="NECAXA" class="matchPar" /></div>
        <div class="col-1 border resultOption" name="match6" onclick="checkRadio('6V', this, 'matchNameId6V')" id="matchNameId6V"></div>
    </div>
    <div class="row border">
        <div class="col-1 border resultOption" name="match7" onclick="checkRadio('7L', this, 'matchNameId7L')" id="matchNameId7L"></div>
        <div class="col-4 teamCls"><input type="text" value="TIGRES" class="matchNon" /></div>
        <div class="col-1 border resultOption" name="match7" onclick="checkRadio('7E', this, 'matchNameId7E')" id="matchNameId7E"></div>
        <div class="col-4 teamCls"><input type="text" value="PUMAS" class="matchNon" /></div>
        <div class="col-1 border resultOption" name="match7" onclick="checkRadio('7V', this, 'matchNameId7V')" id="matchNameId7V"></div>
    </div>
    <div class="row border">
        <div class="col-1 border resultOption" name="match8" onclick="checkRadio('8L', this, 'matchNameId8L')" id="matchNameId8L"></div>
        <div class="col-4 teamCls"><input type="text" value="GUADALAJARA" class="matchPar" /></div>
        <div class="col-1 border resultOption" name="match8" onclick="checkRadio('8E', this, 'matchNameId8E')" id="matchNameId8E"></div>
        <div class="col-4 teamCls"><input type="text" value="LEON" class="matchPar" /></div>
        <div class="col-1 border resultOption" name="match8" onclick="checkRadio('8V', this, 'matchNameId8V')" id="matchNameId8V"></div>
    </div>
    <div class="row border">
        <div class="col-1 border resultOption" name="match9" onclick="checkRadio('9L', this, 'matchNameId9L')" id="matchNameId9L"></div>
        <div class="col-4 teamCls"><input type="text" value="SANTOS" class="matchNon" /></div>
        <div class="col-1 border resultOption" name="match9" onclick="checkRadio('9E', this, 'matchNameId9E')" id="matchNameId9E"></div>
        <div class="col-4 teamCls"><input type="text" value="ATLAS" class="matchNon" /></div>
        <div class="col-1 border resultOption" name="match9" onclick="checkRadio('9V', this, 'matchNameId9V')" id="matchNameId9V"></div>
    </div>
</div>
<div class="row playerDataRow">
    <label for="playerNameId" class="col-4 playerData">NOMBRE: </label>
    <h2 class="col-7"><input type="text" id="playerNameId" /></h2>
</div>
<div class="row">
    <label for="playerNameId" class="col-4 playerData">TEL. CELULAR: </label>
    <h2 class="col-7"><input type="text" id="playerPhoneId" /></h2>
</div>
<div class="row">
    <label for="playerNameId" class="col-4 playerData">EMAIL: </label>
    <h2 class="col-7"><input type="text" id="playerEmailId" /></h2>
</div>
<input type="radio" name="match1_radio" value="L" id="1L">
<input type="radio" name="match1_radio" value="E" id="1E">
<input type="radio" name="match1_radio" value="V" id="1V">

<script>
    function checkRadio(radioId, e, matchNameId) {
        var eAux = e;
        var radios = document.getElementsByName(e.getAttribute("name"));
        var inputList = Array.prototype.slice.call(radios);
        inputList.forEach(function (element) {
            element.style.backgroundColor = "white";
        });
        try { document.getElementById(radioId).checked = true; } catch{ }
        document.getElementById(matchNameId).style.backgroundColor = "black"
    }
</script>


        <footer>
           
        </footer>
    </div>

    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
</body>
</html>
