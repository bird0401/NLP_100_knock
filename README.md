# NLP_100_knock
proceed by referring the solution below

## reference
https://qiita.com/nymwa

## progress and consideration
### 20211112:
- start from Chap6
- Download files
- create this github
### 20211113:
- finish 50-53
### 20211114:
- finish 54-57
- tech
  - micro and macro ave 
  - argsort
### 20211115:
- finish 58-59 (chap 6 finish)
- tech
  - optuna is useful
  - xgb has many params
### 20210111:
- restart from chap4 
### 20210112:
- finish chap4 形態素解析
- tech 
  - when opening files, using "with open() as ~"
  - mecab can devide POS from sentenses automatically
  - mecab can infer base form, POS, POS in detali, etc.
  - by using defaultdict, we can initialize automatically
  - plt.figure initialize the graph
  - plt.hist can make histgram
### 20210114:
- review chap6 50-58 機械学習
- tech
  - stratify is important to be balanced devision
  - string.punctuation is not only punctuation but also other symbols
  - translate is useful to replace text
  - it is easy to pursue tf-idf by using TfidfVectorizer
  - get_feature_names convert id to feature name
  - seaborn makes heatmap
### 20210115:
- review chap6 58-59 
- GPU setting is needed
- tqdm tell completed percent
- setting learning time limit is important for testing
### 20210123:
- start chap8 ニューラルネット
- use pytorch to create NN model
- use KeyedVectors to make words vectors
- use CrossEntropyLoss as Loss function
### 20210124:
- continue chap8
- torch can use GPU
- multi nn shows higher accuracy than single nn
- creating nn is so dificult, and cannot understand fully. I should study pytorch
- torch.nn.functions has relu()
- nn.Module should change its mode by model.train and model.eval
- should do optimizer.zero_grad to initiate it
### 20210125:
- finish chap8
- start chap9 
- sed -e "s/hoge/hoge/g" ./file.txt > ./new_file.txt can translate its character
- nn.Module can be a parent of RNN and CNN
