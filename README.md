# Space Detector Bot 🌍🛰

The Telegram Bot for inference YoloV3 architecture Objecte Detection in The Optical Remote Sensing

## Requirements

```
pip install -U -r requirements.txt
```

## Getting started

Install YoloV3 weights:
```
mkdir weights
wget https://github.com/Vlad15lav/ors-detection/releases/download/weights/dior_weights.pth -O weights/dior_weights.pth
```

Create a database and run queries from the db\sql.py file.

Request an API key from BotFather in Telegram and paste it into main.py.

Start bot:
```
python main.py
```

## References
- [Detection in Optical Remote Sensing Dataset](https://arxiv.org/ftp/arxiv/papers/1909/1909.00133.pdf)
- [You Only Look Once V3](https://arxiv.org/pdf/1804.02767.pdf)
