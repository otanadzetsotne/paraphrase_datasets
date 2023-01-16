# Paraphrasing datasets


* **GLUE (General Language Understanding Evaluation benchmark)**

  [Домашняя страница ->](https://gluebenchmark.com/)

  [tensorflow ->](https://www.tensorflow.org/datasets/catalog/glue)

  [github ->](https://github.com/nyu-mll/GLUE-baselines)


* **MRPC (Microsoft Research Paraphrase Corpus)**

  Microsoft Research Paraphrase Corpus (Dolan & Brockett, 2005) представляет собой корпус пар предложений, автоматически извлекаемых из онлайн-источников новостей, с человеческими аннотациями, указывающими, являются ли предложения в паре семантически эквивалентными.
    
  [Домашняя страница ->](https://www.microsoft.com/en-us/download/details.aspx?id=52398)

  [Скачать ->](https://download.microsoft.com/download/D/4/6/D46FF87A-F6B9-4252-AA8B-3604ED519838/MSRParaphraseCorpus.msi)


* **CoLA (The Corpus of Linguistic Acceptability)**

  Корпус лингвистической приемлемости состоит из суждений о приемлемости английского языка, взятых из книг и журнальных статей по лингвистической теории. Каждый пример представляет собой последовательность слов, аннотированных с указанием, является ли это грамматически английским предложением.
  
  [Домашняя страница ->](https://nyu-mll.github.io/CoLA/)

  [Скачать ->](https://nyu-mll.github.io/CoLA/cola_public_1.1.zip)


* **QQP (Quora Question Pairs)**

  Набор данных Quora Question Pairs2 представляет собой набор пар вопросов с веб-сайта Quora, отвечающего на вопросы сообщества. Задача состоит в том, чтобы определить, являются ли пары вопросов семантически эквивалентными.

  [Kaggle ->](https://www.kaggle.com/competitions/quora-question-pairs)


* **STS (The Semantic Textual Similarity Benchmark)**

  Тест семантического текстового сходства (Cer et al., 2017) представляет собой набор пар предложений, взятых из заголовков новостей, подписей к видео и изображениям, а также данных логического вывода на естественном языке. Каждая пара аннотируется человеком с оценкой сходства от 0 до 5.

  [Домашняя страница ->](http://ixa2.si.ehu.eus/stswiki/index.php/STSbenchmark)

  [Скачать ->](http://ixa2.si.ehu.es/stswiki/images/4/48/Stsbenchmark.tar.gz)


* **PAWS (Paraphrase Adversaries from Word Scrambling)**

  Этот набор данных содержит 108 463 пары, помеченные человеком, и 656 тыс. пар, помеченных шумом, которые показывают важность моделирования структуры, контекста и информации о порядке слов для проблемы идентификации парафраз. Набор данных состоит из двух подмножеств, одно из которых основано на Википедии, а другое — на наборе данных Quora Question Pairs (QQP).

  [paper ->](https://arxiv.org/abs/1904.01130)

  [github ->](https://github.com/google-research-datasets/paws)

  [Скачать (Wiki) (размеченный) ->](https://storage.googleapis.com/paws/english/paws_wiki_labeled_final.tar.gz)

  [Скачать (Wiki) (размеченный, только с перестановками) ->](https://storage.googleapis.com/paws/english/paws_wiki_labeled_swap.tar.gz)


* **PAWS-x**

  Этот набор данных содержит 23 659 оценочных пар PAWS, переведенных человеком, и 296 406 обучающих пар, переведенных машинным способом, на шести типологически различных языках: французском, испанском, немецком, китайском, японском и корейском. Все переведенные пары взяты из примеров в PAWS-Wiki.

  [github ->](https://github.com/google-research-datasets/paws/tree/master/pawsx)
  
  [Скачать ->](https://storage.googleapis.com/paws/pawsx/x-final.tar.gz)


* **PIT (Paraphrase and Semantic Similarity in Twitter)**

  Парафраз и семантическое сходство в Твиттере (PIT) представляет сконструированный корпус перефразирования Твиттера, который содержит 18 762 пары предложений.

  [github ->](https://github.com/cocoxu/SemEval-PIT2015)


* **SciTail**

  Набор данных SciTail представляет собой набор данных, созданный на основе научных экзаменов с несколькими вариантами ответов и веб-предложений. Каждый вопрос и правильный вариант ответа преобразуются в утвердительное утверждение для формирования гипотезы.

  [Домашняя страница ->](https://allenai.org/data/scitail)

  [Paper ->](https://www.semanticscholar.org/paper/SciTaiL%3A-A-Textual-Entailment-Dataset-from-Science-Khot-Sabharwal/cf8c493079702ec420ab4fc9c0fabb56b2a16c84)

  [Скачать ->](https://ai2-public-datasets.s3.amazonaws.com/scitail/SciTailV1.1.zip)


* **TURL (Twitter News URL Corpus)**

  *Requires Access*

  Twitter News URL Corpus — это помеченный человеком корпус парафраз на сегодняшний день, состоящий из 51 524 пар предложений и первый междоменный бенчмаркинг для автоматической идентификации парафраз.

  [github ->](https://github.com/lanwuwei/Twitter-URL-Corpus)


* **CQADupStack**

  CQADupStack — это эталонный набор данных для исследования ответов на вопросы сообщества. Он содержит темы из двенадцати подфорумов StackExchange, аннотированные повторяющейся информацией о вопросах. Предусмотрены предварительно определенные обучающие и тестовые сплиты как для экспериментов по извлечению, так и по классификации, чтобы обеспечить максимальную сопоставимость между различными исследованиями с использованием набора. Кроме того, он поставляется со сценарием для различных способов манипулирования данными.

  [Домашняя страница ->](http://nlp.cis.unimelb.edu.au/resources/cqadupstack/)

  [github ->](https://github.com/D1Doris/CQADupStack)

  [Скачать ->](http://nlp.cis.unimelb.edu.au/resources/cqadupstack/cqadupstack.tar.gz)


* **Paralex**

  Paralex учится на собрании из 18 миллионов пар «вопрос-парафраз», взятых из WikiAnswers.

  [Домашняя страница ->](http://knowitall.cs.washington.edu/paralex/)

  [Cкачать ->](http://knowitall.cs.washington.edu/paralex/wikianswers-paraphrases-1.0.tar.gz)


* **Benchmark for Neural Paraphrase Detection**

  Это эталон для обнаружения нейронных парафраз, чтобы различать оригинальный и созданный компьютером контент.

  [Домашняя страница ->](https://zenodo.org/record/4621403#.Y8HKMuxByrN)

  [Скачать ->](https://zenodo.org/record/4621403/files/MPC.zip?download=1)

