Algoritmos e Programação de Computadores
========================================

Material de apoio a disciplina [CIC-113476 Algoritmos e Programação de Computadores](http://aprender.ead.unb.br/course/view.php?id=2482). Os arquivos de código são feitos para funcionar em ambiente Unix, com o compilador [gcc](http://gcc.gnu.org/) e [interpretador Python 2.7](http://wiki.python.org.br/InicieSe). A seguir estão instruções para começar, mas não se esqueça de olhar as [dicas](Dicas.md).


Download
--------

A forma mais simples de se obter os arquivos é baixar a versão compacta ([.ZIP](https://pt.wikipedia.org/wiki/ZIP)) de todos eles: procure o há um botão "Download ZIP" nesta página ou simplesmente [clique aqui](https://github.com/gnramos/CIC-APC/archive/master.zip). Depois basta [descompactá-lo](https://www.google.com.br/search?q=descompactar+arquivo+zip). A forma "correta" (e mais interessante) é usar a própria ferramenta [Git](http://git-scm.com/book/pt-br/v1), com o comando:

```bash
git clone https://github.com/gnramos/CIC-APC.git
```


Uso
---

O diretório [pdf](pdf) contém textos auxiliares e anotações de aula para referência, e [src](src) o código fonte para estudo (e prática). Os programas são feitos para exemplificar certos conceitos, os detalhes são apresentados no cabeçalho e em comentários. Assume-se serão executados pela [linha de comando](http://www.ibm.com/developerworks/br/linux/library/l-lpic1-v3-103-1/).

### Pseudocódigo ###

Os exemplos em [pseudocódigo](https://pt.wikipedia.org/wiki/Pseudoc%C3%B3digo) (nos arquivos ```.txt```) seguem um padrão arbitrário. Não há interpretador/compilador para isso ainda, a ideia é obter familiaridade com algoritmos.

### Código ```C```###

Os exemplos [nos arquivos ```.c```] seguem o [padrão ANSI](https://pt.wikipedia.org/wiki/Biblioteca_padrão_do_C#Padr.C3.A3o_ANSI), e devem ser compilados/executados com os seguintes comandos:

```bash
gcc -Wall -ansi codigo_fonte.c -o nome_executavel
./nome_executavel
```

Por exemplo:

```bash
gcc -Wall -ansi 0-hello_world.c -o ola_mundo
```

Gera o arquivo ```ola_mundo``` (se não houver problemas), que pode ser executado da seguinte forma:

```bash
./ola_mundo
```

### Código Python ###

Os exemplos [nos arquivos ```.py```] tentam seguir o [PEP8](http://wiki.python.org.br/GuiaDeEstilo), e podem ser executados com o seguinte comando:

```bash
python codigo_fonte.py
```

Por exemplo:

```bash
python 0-hello_world.py
```

Espaço de Memória
-----------------

Git é uma ferramenta de controle de versão que utiliza diversos arquivos "desnecessários" para o aluno de APC. Uma alternativa é baixar diretamente os arquivos do GitHub (um a um), e outra é baixar todos os arquivos e depois apagar os indesejados. Neste último caso, para manter apenas os arquivos de código e PDFs, basta remover o diretório ```.git``` (atenção ao '.' antes de 'git'). Em Unix, é só executar o seguinte comando.

```bash
cd caminho/para/CIC-APC
rm -rf .git
```

Erros
-----

Em caso de erro, lembre-se que a [internet](http://www.google.com.br) é sua amiga, basta procurar um pouco. Se não houver jeito, entre em contato com o responsável pelo projeto.
