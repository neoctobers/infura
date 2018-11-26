# Infura.io wrapper

## Installation
```
pip3 install infura
```

## Usage
```python
import infura

ifr = infura.Infura(
    project_id='your-project-id',
    project_secret='your-project-secret',
    network='mainnet',
)

gas_price = ifr.eth_gas_price()
balance = ifr.eth_get_balance(address, block)
```
