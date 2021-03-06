# Models

This folder contains models that are trained by the agent. The default model is pre-trained with the following parameters:

```json
{
      "env" : {
      "episodes": 50,
      "episode_length": 400,
      "trading_fee": 0.2,
      "time_fee": 0,
      "history_length": 2,
      "profit_taken": 0.01,
      "stop_loss": -5
      },
      "agent": {
        "memory_size": 3000,
        "gamma": 0.96,
        "epsilon_min": 0.01,
        "batch_size": 64,
        "train_interval": 10,
        "learning_rate": 0.001
      },
      "run": {
        "useExistingModel": false,
        "renderGraph": true,
        "tradingType": "S",
        "dataGenType": "W"
      }
}
```