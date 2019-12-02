OctoMap - Um Framework Mapeamento 3D Probabilístico Eficiente Baseado em Octreess.
===========================================================================

http://octomap.github.io

Originalmente desenvolvido por Kai M. Wurm and Armin Hornung, University of Freiburg, Copyright (C) 2009-2014.
Atualmente mantido por [Armin Hornung](https://github.com/ahornung).
Ver a [lista de colaboradores](octomap/AUTHORS.txt) para demais autores.

Licença: 
  * octomap: [New BSD License](octomap/LICENSE.txt)
  * octovis and related libraries: [GPL](octovis/LICENSE.txt)


Faça o download dos últimos *releases*:
  https://github.com/octomap/octomap/releases

Documentação da API:
  http://octomap.github.com/octomap/doc/
  
Status: 
  [![Build Status](https://travis-ci.org/OctoMap/octomap.png?branch=devel)](https://travis-ci.org/OctoMap/octomap)
  
Uma lista de alterações está disponível no [octomap changelog](octomap/CHANGELOG.txt)


VISÃO GLOBAL

--------
O OctoMap consiste em duas bibliotecas separadas, cada uma em sua própria subpasta:
** octomap **, a biblioteca real e ** octovis **, nossas bibliotecas e ferramentas de visualização.
Este README fornece uma visão geral de ambos, para obter detalhes sobre a compilação de cada
Ver [octomap/README.md](octomap/README.md) and [octovis/README.md](octovis/README.md) respectively.
Ver http://www.ros.org/wiki/octomap and http://www.ros.org/wiki/octovis

Você pode criar cada biblioteca separadamente com o CMake executando-a nos subdiretórios,
ou crie octomap e octovis juntos nesse diretório de nível superior. Por exemplo, para
compile apenas a biblioteca, execute:

    cd octomap
    mkdir build
    cd build
    cmake ..
    make
  
Para compilar o pacote completo, execute:

    cd build
    cmake ..
    make
  
Binários e bibliotecas terminarão nos diretórios `bin` e` lib` do diretório
diretório de nível superior onde você iniciou a construção.
