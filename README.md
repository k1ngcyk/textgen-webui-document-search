# textgen-webui-document-search
document vector database search extension for text-generation-webui

## usage

1. Confirm you can run and chat with [text-generation-webui](https://github.com/oobabooga/text-generation-webui)
2. 

```
cd /path/to/text-generation-webui
git clone https://github.com/k1ngcyk/textgen-webui-document-search extensions/document_search
cd extensions/document_search
pip install -r requirements.txt
cd -
python server.py --extensions document_search
```

3. Load documents with uploading a folder
