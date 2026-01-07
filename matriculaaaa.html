<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Matrícula – Validación</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background-color: #f6f5ef;
    color: #000;
}
.header {
    background-color: #6fae2f;
    padding: 14px;
    font-weight: bold;
}
.container { padding: 15px; }
.title { color: #c9a100; font-size: 16px; }
.subtitle { color: #3b7f1f; font-size: 20px; margin-bottom: 12px; }
.table { width: 100%; border-collapse: collapse; background-color: #fff; }
.table tr { border-bottom: 1px solid #e0e0e0; }
.table td { padding: 10px; font-size: 14px; }
.label { width: 45%; }
input {
    width: 85%;
    border: none;
    background: transparent;
    font-size: 14px;
}
input::placeholder {
    color: rgba(0,0,0,0.4);
    font-style: italic;
}
button {
    margin-top: 15px;
    width: 100%;
    padding: 12px;
    background-color: #6fae2f;
    border: none;
    font-size: 16px;
}
.footer {
    background-color: #e0e0e0;
    padding: 10px;
    font-size: 12px;
    text-align: center;
}
</style>
</head>

<body>

<div class="header">MATRÍCULA</div>

<div class="container">
<div class="title">Sistema Datamatrix</div>
<div class="subtitle">Validación de Documentos</div>

<form onsubmit="generarQR(event)">
<table class="table">
<tr><td class="label">Código</td><td><input id="codigo" placeholder="Ingrese código"></td></tr>
<tr><td class="label">Matrícula</td><td><input id="matricula" placeholder="Ingrese matrícula"></td></tr>
<tr><td class="label">Marca</td><td><input id="marca" placeholder="Ingrese marca"></td></tr>
<tr><td class="label">Modelo</td><td><input id="modelo" placeholder="Ingrese modelo"></td></tr>
<tr><td class="label">Color</td><td><input id="color" placeholder="Ingrese color"></td></tr>
<tr><td class="label">Año</td><td><input id="ano" placeholder="Ingrese año"></td></tr>
<tr><td class="label">Placa</td><td><input id="placa" placeholder="Ingrese placa"></td></tr>
<tr><td class="label">Chasis</td><td><input id="chasis" placeholder="Ingrese chasis"></td></tr>
</table>

<button type="submit">Generar enlace para QR</button>
</form>

<p id="linkQR"></p>

</div>

<div class="footer">Dirección General de Impuestos Internos</div>

<script>
function generarQR(e) {
    e.preventDefault();

    const params = new URLSearchParams({
        codigo: codigo.value,
        matricula: matricula.value,
        marca: marca.value,
        modelo: modelo.value,
        color: color.value,
        ano: ano.value,
        placa: placa.value,
        chasis: chasis.value
    });

    const url = location.pathname + "?" + params.toString();
    document.getElementById("linkQR").innerHTML =
        "Link para QR:<br><b>" + url + "</b>";
}

// RELLENAR AUTOMÁTICO DESDE QR
const datos = new URLSearchParams(window.location.search);
datos.forEach((valor, clave) => {
    const campo = document.getElementById(clave);
    if (campo) campo.value = valor;
});
</script>

</body>
</html>
