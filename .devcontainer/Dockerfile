# ベースイメージとしてPython 3.10を使用
FROM python:3.10-slim

# 作業ディレクトリを作成
WORKDIR /workspace

# 必要なパッケージをインストール
COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt

# ポートを公開
EXPOSE 8000
