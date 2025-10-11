# Cadmus Lexicography API

🐋 Quick Docker image build:

  docker buildx build . --platform linux/amd64,linux/arm64,windows/amd64 -t vedph2020/cadmus-lexicography-api:0.0.1 -t vedph2020/cadmus-lexicography-api:latest --push

(replace with the current version).

This is a Cadmus API layer customized for the Lexicography shell app. Most of its code is derived from [shared Cadmus libraries](https://github.com/vedph/cadmus-api).
