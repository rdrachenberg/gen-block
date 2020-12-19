# gen-block
A python program to create a simple blocklchain
worked off of this [tutorial](https://hackernoon.com/learn-blockchains-by-building-one-117428612f46).
Deployed to [Heroku Here](https://gen-block.herokuapp.com/). 

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
<br>

1. Make sure [Python 3.9+](https://www.python.org/downloads/) is installed.

<br>


2. Install [pipenv](https://github.com/kennethreitz/pipenv). 

```
$ pip install pipenv 
```
<br>


3. Install requirements  
```
$ pipenv install 
```
<br>

4. Open file named blockchain.py

``` 
change line #233 
port = int(os.environ.get('PORT', args.port))


to this: 
port = args.port
```
<br>

5. Run the server:
    * `$ python3 blockchain.py` 
    * `$ python3 blockchain.py -p 5001`
    * `$ python3 blockchain.py --port 5002`

<br>

## Valid endpoints
```
/chain
/mine
/transactions/new
/nodes/register
/nodes/resolve
```
