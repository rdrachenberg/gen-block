# gen-block
A python program to create a simple blocklchain
worked off of this [tutorial](https://hackernoon.com/learn-blockchains-by-building-one-117428612f46)

## Python 3.9.1 required

## Dependancies
* hashlib
* json
* time
* urllib.parse
* uuid
* request
* Flask

## Installation

1. Make sure [Python 3.9+](https://www.python.org/downloads/) is installed. 
2. Install [pipenv](https://github.com/kennethreitz/pipenv). 

```
$ pip install pipenv 
```
3. Install requirements  
```
$ pipenv install 
``` 

4. Run the server:
    * `$ python3 blockchain.py` 
    * `$ python3 blockchain.py -p 5001`
    * `$ python3 blockchain.py --port 5002`


## Valid endpoints

    /chain
    /mine
    /transactions/new
    /nodes/register
    /nodes/resolve
