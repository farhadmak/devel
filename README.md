# datasource

expects elasticsearch to be running on `localhost:9200`

# globals

Install `lerna` and `mgit2` globally, so you can bootstrap the development
enviroment.

`npm i -g lerna && npm i -g mgit2`

`mgit bootstrap && lerna bootstrap`

# seed elasticsearch

You need to create the appropriate indices and mappings for `elasticsearch`.

[yeg-relief/utils](https://github.com/yeg-relief/utils/tree/master/seed)

# start the applications

`lerna run --parallel start`