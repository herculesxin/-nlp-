# -nlp-
基于nlp_rasa的医疗问答系统
Train model by running:

```
python -m rasa_nlu.train -c sample_configs/config_jieba_mitie_sklearn.json
```
Run the rasa_nlu server:


```
python -m rasa_nlu.server -c sample_configs/config_jieba_mitie_sklearn.json
```


test
‘’‘
$ curl -XPOST localhost:5000/parse -d '{"q":"我发烧了该吃什么药？", "project": "rasa_nlu_test", "model": "model_20170921-170911"}' | python -mjson.tool
#vue

# Socket.IO 

A simple chat demo for  aidoctor

## How to use

```
$ cd medical
$ npm install
$ node index.js
```

And point your browser to `http://localhost:3000`. Optionally, specify
a port by supplying the `PORT` env variable.

# Socket.IO 

A simple chat demo for  aidoctor

## How to use

$ npm instll
$ node index.js
```

And point your browser to `http://localhost:3000`. Optionally, specify
a port by supplying the `PORT` env variable.

