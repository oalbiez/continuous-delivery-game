# ...

docker build -t card-game .
docker run -i -t 1d750a549e30 /bin/bash
ruby deck.rb
docker cp 39c92f73f6ea://workspace/_output //Users/crochas/Documents/output
