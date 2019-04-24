# CartaoCidadaoWEB
Leitura do Cartão do Cidadão através de uma página Web


Requisitos: Instalação do SDK do cartão do cidadão. 
Consiste em duas partes. Uma aplicação consola em C# que tem que estar a correr na máquina do cliente. 
A aplicação Web deverá estar a correr num servidor ou numa outra máquina. 

A aplicação que corre no servidor/maquina remota recomendo a instalação da extension no visual studio Conveyor by keyoti que vai abrir um porto para a página web ser acedida remotamente através do computador cliente. 
Funcionamento: 
A aplicação consola que corre no cliente é que vai fazer as chamadas ao cartão de cidadão, a página web ao clicar start vai comunicar com a aplicação consola que depois devolve os dados do cartão em formato json. 
