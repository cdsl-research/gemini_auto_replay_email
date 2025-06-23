# gemini_auto_replay_email
### 概要
未読メールを検知し，その未読メールをGeminiが返信を行ってくれるPythonプログラムです．

### バージョン
- Ubuntu 24.04.2 LTS
- Python 3.12.3

Pythonモジュール
- annotated-types          0.7.0
- anyio                    4.9.0
- cachetools               5.5.2
- certifi                  2025.4.26
- charset-normalizer       3.4.2
- google-api-core          2.25.0
- google-api-python-client 2.171.0
- google-auth              2.40.2
- google-auth-httplib2     0.2.0
- google-auth-oauthlib     1.2.2
- google-genai             1.20.0
- googleapis-common-protos 1.70.0
- h11                      0.16.0
- httpcore                 1.0.9
- httplib2                 0.22.0
- httpx                    0.28.1
- idna                     3.10
- oauthlib                 3.2.2
- pip                      24.0
- proto-plus               1.26.1
- protobuf                 6.31.1
- pyasn1                   0.6.1
- pyasn1_modules           0.4.2
- pydantic                 2.11.7
- pydantic_core            2.33.2
- pyparsing                3.2.3
- requests                 2.32.3
- requests-oauthlib        2.0.0
- rsa                      4.9.1
- sniffio                  1.3.1
- typing_extensions        4.14.0
- typing-inspection        0.4.1
- uritemplate              4.2.0
- urllib3                  2.4.0
- websockets               15.0.1

### 実行方法
必要なモジュールのインストール
```
pip install --upgrade google-api-python-client google-auth-httplib2 google-auth-oauthlib
pip install -q -U google-genai
```

Gmail APIの有効化
![image](https://github.com/user-attachments/assets/44213da2-d887-41bc-8458-1f0d0d8d95d0)


OAuth 2.0 クライアント IDの登録
![zu1](https://github.com/user-attachments/assets/bd992477-4606-4305-bbce-bab79ee84801)

Gemini API Keyの作成
![zu3](https://github.com/user-attachments/assets/faf42284-8b77-4e0c-ae62-0823566325d8)



### 実行結果
