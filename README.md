#speakit - un lecteur text to speech 

#CE SCRIPT NECESSITE UNE CONNECTIVITE A INTERNET

#installation

```
    git clone https://github.com/dev0ps221/speakit

    cd speakit

    pip3 install -r requirements.txt

    chmod +x speakit
```


#exemple

```
./speakit -t "hello world" --lang=en
```

#utilisation

```


    Usage: speakit [options]


    Options:

    -h, --help            show this help message and exit

    -f FILE, --file=FILE  choisir le fichier a lire

    -l TEXT, --lang=TEXT  langue de lecture

    -L, --live            lire le fichier en meme temps qu il est parcouru

    -P FILE, --pdf=FILE   choisir le fichier [pdf] a lire

    -o FILE, --outfile=FILE

                            enregistrer dans le fichier

    -t TEXT, --text=TEXT  specifier le texte a lire

```
