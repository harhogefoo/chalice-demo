# chalice-demo
https://chalice.readthedocs.io/en/latest/quickstart.html

## Setup
```
pip install virtualenv
virtualenv ~/.virtualenvs/cholice-demo
source ~/.virtualenvs/chalice-demo/bin/activate
pip install chalice
```

## Prepare
```
source ~/.virtualenvs/chalice-demo/bin/activate
```

## Run
```
chalice local
or
chalice local -port=8080
```

## Deploy
```
chalice deploy
```

## Delete App
```
chalice delete --stage dev
```
