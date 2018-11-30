# Infura.io API wrapper

An Infura.io API wrapper, for Python.

## Installation
```
pip3 install infura
```

## Usage
```python
import infura

ifr = infura.Client(
    project_id='your-project-id',
    project_secret='your-project-secret',
    network='mainnet',
)

gas_price = ifr.eth_get_gas_price()

balance = ifr.eth_get_balance('0x39eB410144784010b84B076087B073889411F878')

block_number = ifr.eth_get_block_number()

block = ifr.eth_get_block_by_number(block_number, show_transaction_details: bool = False)
```
