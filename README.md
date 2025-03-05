<!DOCTYPE html>
<html lang="es">
    <head>
        <meta charset="utf-8" />
        <meta name="viewport" content="width=device-width, initial-scale=1" />
        <title>Primer ejemplo</title>
        <!-- Usando CSS Grid Generator - https://cssgridgenerator.io/ -->
        <style>
        body{
            font-famliy: Helvetica,Arial, sans-serif;
            text-align: center;
        }
        .parent {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 8px;
        }
        .div1 {
            grid-row-start: 2;
        }
        
        .div2 {
            grid-column-start: 1;
            grid-row-start: 3;
        }
        
        .div3 {
            grid-column-start: 2;
            grid-row-start: 2;
        }
        
        .div4 {
            grid-row-start: 3;
        }
        footer{
            padding-top: 15vh;
        }
        </style>
    </head>
    <body>
        <header>
            <h1>
                Tabla nacimientos por edad y por sexo
            </h1>
        </header>
        <main class="parent">
            <div class="div1">
                <svg width="100%" height="100%" viewBox="0 0 42 42" class="donut">
                    <circle class="donut-hole" cx="21" cy="21" r="15.91549430918954" fill="#fff"></circle>
                    <circle class="donut-ring" cx="21" cy="21" r="15.91549430918954" fill="transparent" stroke="#d2d3d4" stroke-width="3"></circle>
                    <circle class="donut-segment" cx="21" cy="21" r="15.91549430918954" fill="transparent" stroke="#ce4b99" stroke-width="3" stroke-dasharray="51 48" stroke-dashoffset="0"></circle>
                </svg>
                <p>Los Nacimientos según sexo, es la mitad de ambos generos. Datos extraidos de la INEI diciembre 2024</p>
            </div>
            <div class="div2">
                <svg width="100%" height="100%" viewBox="0 0 42 42" class="donut">
                    <circle class="donut-hole" cx="21" cy="21" r="15.91549430918954" fill="#fff"></circle>
                    <circle class="donut-ring" cx="21" cy="21" r="15.91549430918954" fill="transparent" stroke="#d2d3d4" stroke-width="3"></circle>
                    <circle class="donut-segment" cx="21" cy="21" r="15.91549430918954" fill="transparent" stroke="#ce4b99" stroke-width="3" stroke-dasharray="74 26" stroke-dashoffset="0"></circle>
                </svg>
                <p>El mayor porcentaje de nacimientos son por madres de 30-34 años con un 
                    total de 30%. Datos extraidos de la INEI diciembre 2024</p>
            </div>
            <div class="div3">
                <svg width="100%" height="100%" viewBox="0 0 42 42" class="donut">
                    <circle class="donut-hole" cx="21" cy="21" r="15.91549430918954" fill="#fff"></circle>
                    <circle class="donut-ring" cx="21" cy="21" r="15.91549430918954" fill="transparent" stroke="#d2d3d4" stroke-width="3"></circle>
                    <circle class="donut-segment" cx="21" cy="21" r="15.91549430918954" fill="transparent" stroke="#ce4b99" stroke-width="3" stroke-dasharray="51 49" stroke-dashoffset="0"></circle>
                </svg>
                <p> Número de Defunciones totales y distribución porcentual según sexo. </p>
            </div>
            <div class="div4">
                <svg width="100%" height="100%" viewBox="0 0 42 42" class="donut">
                    <circle class="donut-hole" cx="21" cy="21" r="15.91549430918954" fill="#fff"></circle>
                    <circle class="donut-ring" cx="21" cy="21" r="15.91549430918954" fill="transparent" stroke="#d2d3d4" stroke-width="3"></circle>
                    <circle class="donut-segment" cx="21" cy="21" r="15.91549430918954" fill="transparent" stroke="#ce4b99" stroke-width="3" stroke-dasharray="80 20" stroke-dashoffset="0"></circle>
                </svg>
                <p> Nacen mas niños en la región metropolitana que en la región de O´higgins</p>
            </div>
        </main>
        <footer>
            <p><small>Paloma Rojas  2025</small></p>
        </footer>
    </body>
</html>
