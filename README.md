# Enrutar-trafico-por-tor
Este repositorio de muestra como instalar y configurar nipe una herramienta para enrutar tu grafico en TOR

## Enrutar tu trafico por la red de TOR

### Paso 1 

Clonar la repo de nipe  

```bash
git clone https://github.com/htrgouvea/nipe.git
cd nipe
```
### Paso 2

instalar cpanm y se hace de la siguiente manera 

```bash
sudo apt install cpanminus                                                                                
```

### Paso 3 

instalar las dependencias

```bash
sudo cpanm --installdeps .                                                                             
```

### Paso 4

Estando en el directorio de nipe nos instalamos el nipe.p1 de la siguiente forma

```bash
sudo perl nipe.pl install                                                                       
```

### Paso 5 

Una vez ya instalado lo incoamos 

```bash
sudo perl nipe.pl start                                                                       
```
### Y listo
