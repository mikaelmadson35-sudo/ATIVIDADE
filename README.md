<?php

for($i = 1; $i <= 5; $i++){
    print "Arquivo $i: <input type='text' name='arquivo$i'> <br>";
}

$equipamentosdeinformatica = [
    'computador',
    'tablet',
    'celular',
    'monitor',
    'sistema de rede',
    'impressora',
    'roteadores',
    'servidores'
];

foreach ($equipamentosdeinformatica as $i){
    print 'Equipamento: ' . $i . '<br>';
}

$pessoas = [
    'kevin' => 10,
    'toguro' => 2,
    'gelado' => 9,
    'manu momo' => 7,
    'dan peso pesado' => 8,
    'samara' => 6,
    'felipe' => 7,
    'cuca' => 10,
];

foreach ($pessoas as $nome => $nota){
    print 'Pessoa: ' . $nome . ' | Idade: ' . $nota . '<br>';
}

?>
