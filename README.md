Whales Watcher
========

Python web3 project to track whales trade on a specified set of token contracts.

The blockchain used is Ethereum.

Project parts
--------
 - Collector : Collect every Buy & Sell of selected tokens
 - Interpreter : Detect whales wallet which buy/sell at the best moments 

Requirements
--------
- Create `.env` file in the current folder and add the following global variable :
```
INFURA_PROJECT_ID=<Your-Infura-Project-ID>
```
- Install web3:
```
pip3 install web3
```

Usage
--------
execute:
```
chmod +x run-collector.sh
```
 - Collector : Execute `./run-collector.sh`
 - Interpreter : Execute `./run-interpreter.sh`


Credits - ESILV :
--------
- Jean Daniel Adrien
- Alexandre Bauchet
- Yani Ferhaoui
