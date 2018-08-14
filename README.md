# datakapistelya

1. Mene päätteellä oikeaan kansioon (huodynnä cd, ls)
2. Avaa kansio, jossa tiedosto on
3. Kirjoita päätteelle python3 <tiedostonnimi>

## Ympäristön asentaminen
Asennetaan tarvittavat paketit (tarvitsee tehdä kerran)

    apt-get install python3 python3-virtualenv virtualenv
    source /etc/bash_completion.d/virtualenvwrapper

Luodaan Pythonin virtualenv -ympäristö, ja asennetaan siihen vaaditut Python-paketit (tarvitsee tehdä kerran)

    mkvirtualenv -p /usr/bin/python3 datakapistelya
    pip install numpy matplotlib pandas pandas-datareader quandl sklearn

Jatkossa aiemmin luodun Python virtualenv -ympäristön saa käyttöön komennolla

    workon datakapistelya


## Lähteet

 - https://pythonprogramming.net/data-analysis-python-pandas-tutorial-introduction/
