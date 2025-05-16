# Basketball Agent 🏀🤖

![Basketball Agent Banner](A_2D_digital_vector_illustration_banner_features_".png)

Bem-vindo ao **Basketball Agent**, um projeto que combina a emoção do basquete com a inteligência do Google GenAI!

## 🚀 Visão Geral

O **Basketball Agent** é um agente de linha de comando e notebook Colab que permite consultar:

* Jogos do dia
* Próximos jogos na semana
* Favoritos da rodada
* Estatísticas de confrontos entre times
* Classificação atual da NBA
* Principais jogadores da temporada
* Notícias recentes
* Jogos por time específico
* Jogos por data específica
* Estatísticas de jogador
* Ranking completo de times
* Definir e lembrar time favorito

Tudo isso usando o poder da API Google GenAI (modelo *gemini-2.0-flash*).

## 🎯 Funcionalidades

* **Cache & Erros**: Respostas em cache e tratamento amigável de erros.
* **Filtros Avançados**: Busca por time, por data e estatísticas de jogadores.
* **Ambientes Suportados**:

  * **Google Colab** (com integração direta)
  * **Local** (Python 3.11+)
* **Menu Interativo**: Fácil de usar, com opções numeradas e saídas formatadas.
* **Personalização**: Defina seu time favorito para consultas rápidas.

## ⚙️ Instalação Local

1. Clone o repositório:

   ```bash
   git clone https://github.com/SEU_USUARIO/basketball-agent.git
   cd basketball-agent
   ```
2. Crie e ative um ambiente virtual (recomendado):

   ```bash
   python3.11 -m venv .venv
   source .venv/bin/activate
   ```
3. Instale dependências:

   ```bash
   pip install -r requirements.txt
   ```
4. Configure sua chave de API:

   ```bash
   cp .env.example .env
   # edite .env e coloque sua GOOGLE_API_KEY
   ```
5. Execute o agente:

   ```bash
   python basketball_agent.py
   ```

## ☁️ Uso no Google Colab

1. Acesse:
   [Abrir no Colab](https://colab.research.google.com/github/SEU_USUARIO/basketball-agent/blob/main/Agent.ipynb)
2. Instale dependências e defina sua chave:

   ```python
   !pip install google-genai python-dotenv
   import os
   os.environ["GOOGLE_API_KEY"] = "SUA_API_KEY_AQUI"
   ```
3. Execute as células e interaja com o agente no notebook.

## 🤝 Contribuindo

1. Faça um fork deste repositório.
2. Crie uma branch para sua feature:

   ```bash
   git checkout -b feature/nome-da-sua-feature
   ```
3. Adicione suas mudanças e faça commit:

   ```bash
   git add .
   git commit -m "Adiciona nova feature"
   ```
4. Envie para o repositório remoto:

   ```bash
   git push origin feature/nome-da-sua-feature
   ```
5. Abra um Pull Request.

## 📄 Licença

Este projeto está licenciado sob a **MIT License**. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
