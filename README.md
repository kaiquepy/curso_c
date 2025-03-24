## Instalação do compilador
```bash
sudo apt install gcc
```

## Compilando programa
```bash
gcc -o saida programa.c
```
> [!TIP]
> `!gcc` executa o último comando do histórico que começa com "gcc".

## Executando programa
```bash
/path/to/file

# or

./file
```

## Visualizar a saída do último programa executado
```bash
echo $?
```

## Visualizar os códigos hexadecimais de uma string
```bash
echo -n string | hd
```

## Contar a quantidade de caracteres de uma string
```bash
echo -n string | wc -c
```
