![image](https://github.com/user-attachments/assets/71f8d2d0-cc2d-4d15-b178-7b2beace5930)

## Configurations

For example if you want to swap USDC to SOL

![image](https://github.com/user-attachments/assets/96fc2fa4-2afb-49f7-b986-7f8fd9e7e2a5)

1. Get market id from URL
2. Change min / max for all settings as you need
3. type `Buy`

```
[
  {
    "action": "trade",
    "market_id": "4DoNfFBfF7UokCC2FQzriy7yHK6DY6NVdYpuekQ5pRgg",
    "order": "Market",
    "type": "Sell",
    "min_delay": 30,
    "max_delay": 100,
    "token0": "SOL",
    "token1": "USDC",
    "percentage_min": 30,
    "percentage_max": 50
  }
]
```


For example if you want to swap SOL to USDC

![image](https://github.com/user-attachments/assets/96fc2fa4-2afb-49f7-b986-7f8fd9e7e2a5)

1. Get market id from URL
2. Change min / max for all settings as you need
3. type `Sell`

```
[
  {
    "action": "trade",
    "market_id": "4DoNfFBfF7UokCC2FQzriy7yHK6DY6NVdYpuekQ5pRgg",
    "order": "Market",
    "type": "Sell",
    "min_delay": 30,
    "max_delay": 100,
    "token0": "SOL",
    "token1": "USDC",
    "percentage_min": 30,
    "percentage_max": 50
  }
]
```




## Examples schema.json
```schema_example.json

[
  {
    "action": "trade",
    "market_id": "4DoNfFBfF7UokCC2FQzriy7yHK6DY6NVdYpuekQ5pRgg",
    "order": "Market",
    "type": "Sell",
    "min_delay": 30,
    "max_delay": 100,
    "token0": "SOL",
    "token1": "USDC",
    "percentage_min": 30,
    "percentage_max": 50
  },
  {
    "action": "trade",
    "market_id": "4DoNfFBfF7UokCC2FQzriy7yHK6DY6NVdYpuekQ5pRgg",
    "order": "Market",
    "type": "Buy",
    "min_delay": 30,
    "max_delay": 100,
    "token0": "SOL",
    "token1": "USDC",
    "percentage_min": 100,
    "percentage_max": 100
  },
  {
    "action": "withdraw",
    "market_id": "4DoNfFBfF7UokCC2FQzriy7yHK6DY6NVdYpuekQ5pRgg"
  }
]
```






