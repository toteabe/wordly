# **WORDLY**

![IES Vega de Mijas](https://github.com/toteabe/wordly/blob/main/public/LogoVdM.jpg?raw=true "IES Vega de Mijas")
<img src="https://github.com/toteabe/wordly/blob/main/public/gandalf_tuxedo.png?raw=true" width="15%"/>

node wordly.js

docker run -d --name tika  -p 9998:9998 -v $(pwd)/tika-config.xml:/tika-config.xml:ro   apache/tika:latest-full --config /tika-config.xml

docker run -d -v ollama:/root/.ollama -p 11434:11434 --name ollama ollama/ollama
docker exec -it ollama bash
ollama run qwen3:8b

Browser: http://localhost:3000





