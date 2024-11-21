# Video Analyzer Youtube
Este projeto é um analisador de vídeos do YouTube utilizando Inteligência Artificial para extrair e resumir conteúdo. A automação é realizada utilizando agentes com Langchain, PyTube, Whisper, e a API da OpenAI para salvar os resumos gerados em uma pasta específica.
## Funcionalidades
- Download de vídeos do YouTube
- Extração de áudios de vídeos
- Transcrição de áudios
- Integração com WhatsApp Web utilizando Selenium
- Criação de tags, resumos curtos, resumos detalhados e bullet points com GPT-4o-mini
## Tecnologias Utilizadas
### Pré-requisitos
- Python 3.12
- Um arquivo .env contendo a sua chave da OpenAI API (`OPENAI_API_KEY`)
- Google Chrome instalado (para o Selenium)
- Um grupo criado no WhatsApp com um nome especificado no código
- Poetry instalado

