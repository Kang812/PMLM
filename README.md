# PMLM
개인 비서 LLM 만들기

## 개발환경
```
OS  : Ubuntu 20.04
CPU : AMD Ryzen 5 PRO 4650G
RAM : 64GB
GPU : RTX 3060 12GB x 2
```

## library
```
pip install -r requirements.txt
pip install "unstructured[pdf]"
curl -fsSL https://ollama.com/install.sh | sh # 우분투
```

## model download
```
./model_download/EEVE-Korean_10B_GGUF.sh
```

## LangServer 실행 
- [app](app)