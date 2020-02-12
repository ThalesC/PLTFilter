
SETUP
=====

Extrair o conteúdo do arquivo .zip e executar o script de setup

```
$ unzip /path/to/PLTFilter-master.zip
$ cd /path/to/PLTFilter-master/pltfilter_setup/
$ chmod +x setup
$ ./setup
```

USO BÁSICO
==========

Executar script principal

```
$ pltfilter
```

Selecionar um único arquivo plt para extrair parâmetro referente ao eixo X.

![1](http://imgur.com/5rfBVHQl.png)

Selecionar parâmetro a ser extraído ao eixo X.

![2](http://imgur.com/PKPETPIl.png)

Selecionar um ou mais arquivos plt para extrair parâmetros referentes ao eixo Y.

![3](http://imgur.com/L5OTmPxl.png)

Selecionar parâmetros a serem extraídos ao eixo Y.

![4](http://imgur.com/N9wyo1ul.png)

Definir onde será salvo o _plot.csv_.

![5](http://imgur.com/8Eex6XJl.png)

FLAGS
=====
- -**d DELIMITER** - Define caractere como separador, utiliza vírgula se não for definido, ignora export PLTFILTER_DELIMITER
- -**h** - Apresenta diálogo de ajuda

EXPORTS
=======
- **PLTFILTER_DELIMITER** - Define caractere como separador, utiliza vírgula se não for definido
- **PLTFILTER_FOLDER** - Pasta padrão para selecionar arquivos, utiliza pasta de execução do _pltfilter_ se não for definido
- **PLTFILTER_OUTFOLDER** - Pasta padrão onde serão salvos novos plots, com nome padrão e timestamp
