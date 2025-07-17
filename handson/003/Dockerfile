# ベースとなるイメージを指定(From=カスタマイズ、元あるやつをカスタマイズ)
FROM pytorch/pytorch:2.3.0-cuda12.1-cudnn8-runtime

# コンテナ内での作業ディレクトリを設定
WORKDIR /app

# コンテナが起動したときに実行されるコマンド
CMD ["python3", "main.py"]