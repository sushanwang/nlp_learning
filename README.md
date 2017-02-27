# nlp_learning

The tensorflow 1.0.0 support of "lstm-char-cnn-tensorflow" project

the original project can be found: https://github.com/carpedm20/lstm-char-cnn-tensorflow

Thanks to the author:Taehoon Kim / @carpedm20

MIT License


replace files in "lstm-char-cnn-tensorflow" project with same name.

replace "batch_loader.py" with "batch_loader_chinese.py", and rename "batch_loader_chinese.py" as "batch_loader.py" to process Chinese

The Chinese dataset should be preprocessed with fine word segmentation

e.g:"今天 天气 真 好啊"

this project using jieba, which can be found in https://github.com/fxsjy/jieba/
