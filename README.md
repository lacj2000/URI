# URI

### URI JS
##### Exemplo 1001 by URI
###### OBS.: Sempre usar as duas linhas iniciais e usar o 'lines.shift()' para leitura
###### OBS.: Nos Exemplos faço uso do prompt para testar no console do navegador.
    var input = require('fs').readFileSync('/dev/stdin', 'utf8');
    var lines = input.split('\n');

    var a = parseInt(lines.shift());
    var b = parseInt(lines.shift());

    console.log('X = ' + (a+b));
