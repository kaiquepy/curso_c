# :placard: Curso de C - Mente Binária
Este repositório contém meus estudos e exercícios realizados a partir do curso de linguagem C do canal [Mente Binária](https://www.youtube.com/watch?v=8Qm5K0GTD3s&list=PLIfZMtpPYFP5qaS2RFQxcNVkmJLGQwyKE). O objetivo principal é construir uma base sólida na linguagem C para, futuramente, estudar engenharia reversa e segurança ofensiva.

## :gear: Instalação do compilador
```bash
sudo apt install gcc
```

## :package: Compilando programa
```bash
gcc -o programa programa.c
```
> [!TIP]
> `!gcc` executa o último comando do histórico que começa com "gcc".

## Executando programa
```bash
/path/to/file

# or

./file
```

## Comandos úteis
Exibe o código de saída do último programa executado:
```bash
echo $?
```

Exibe os códigos hexadecimais de uma string:
```bash
echo -n string | hd
```

Exibe a quantidade de caracteres de uma string:
```bash
echo -n string | wc -c
```

**Autor:** Kaique Vieira
