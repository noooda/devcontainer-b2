FROM alpine:3.22.0

RUN apk update && \
    apk add --no-cache \
    curl

RUN curl -LsSf https://astral.sh/uv/install.sh | sh

ENV PATH="/root/.local/bin:$PATH" 
