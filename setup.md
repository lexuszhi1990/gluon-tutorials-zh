
docker run --rm -p 8888:8888 -it -v /Users/david/repo/private_repos/gluon-tutorials-zh:/app-dev -v /Users/david/mnt/data/VOCdevkit:/mnt/data/VOCdevkit -v /Users/david/mnt/data/ckpt:/mnt/ckpt mxnet/python:1.2.0-dev bash



jupyter notebook --allow-root --ip 0.0.0.0
