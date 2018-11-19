### Практикум AncConc 

__AntConc__ -- корпусный менеджер

* [Страница программы](http://www.laurenceanthony.net/software/antconc/), где её можно скачать и посмотреть инструкции
* [Мануал](http://www.laurenceanthony.net/software/antconc/resources/help_AntConc321_english.pdf) (на английском)
* [Видео-тьюториал от автора](https://www.youtube.com/playlist?list=PLiRIDpYmiC0Ta0-Hdvc1D7hG6dmiS_TZj)
* [Тьюториал для семинара](https://drive.google.com/file/d/0B6-5pzCmb8MOblpzRXI3elFFeFU/view?usp=sharing)

#### Материал для работы на семинаре
Анна Каренина: [text](https://drive.google.com/file/d/0B6-5pzCmb8MOVFBjajZJUHhNNmM/view?usp=sharing), [xml](https://drive.google.com/file/d/0B6-5pzCmb8MOTktNVlpjaDdOY2M/view?usp=sharing)

Война и Мир: [text](https://github.com/ElizavetaKuzmenko/Programming-and-computer-instruments/blob/master/Vojna%20i%20mir.%20Tom%201.txt)

Тихий Дон: [text](https://github.com/ElizavetaKuzmenko/Programming-and-computer-instruments/blob/master/tihiyd.txt)

#### Основное задание
* Загрузите файл, проверьте, что он отображается нормально (вкладка FileView).  
* Постройте частотный список слов романа (вкладка Word List, нажмите кнопку Start). Кликнув на слово, вы сможете попасть в конкорданс, построенный для этого слова.  
* В Word List отсортируйте частотный список по алфавиту (Sort by Word внизу страницы).     
* Постройте частотный список двух-, трех- и т.д. -словных словосочетаний (вкладка Cluster/N-Grams, поставьте галочку на N-Grams, укажите, сколько слов в ngram-е вы хотите видеть, например, Min:3, Max:3, установите порог вхождений в корпусе, например, 10). Кликнув на n-грам, вы также можете попасть в его конкорданс.    
* Постройте списки коллокатов выбранного вами слова (вкладка Collocates), указав границы окна справа  / слева.  

#### Работа с размеченными файлами 
* Построить частотный список, игнорируя теги xml (см. xml-файл) 

#### Лемматизация словоформ 
* Разметьте фрагмент файла "Анны Карениной" с помощью разметчика [UDPipe](http://lindat.mff.cuni.cz/services/udpipe/) (модель Russian-SynTagRus, версия UD 2.0, tokenize and tag) 

<img src="https://raw.githubusercontent.com/pykili/pykili.github.io/master/img/data_udpipe/udpipe_rus.png" width = "800"></img>

* Отредактируйте разметку, чтобы в файле остались только а) части речи б) леммы в) леммы и части речи вида `дом_NOUN`   

* Постройте частотный список а) частей речи б) лемм в) леммных коллокаций прилагательное+существительное

#### Списки char-граммов (дополнительное задание) 
* Постройте список двубуквенных сочетаний (используя [файл](https://drive.google.com/file/d/0B6-5pzCmb8MONVN6ektrNzJZbDg/view?usp=sharing), сначала изучив, как он устроен)
