# Alfred - Seu Parceiro Estoico e Amigo na Jornada de Autodesenvolvimento

Imagine ter um assistente pessoal, inteligente como o Jarvis do Ironman, mas com a calma sabedoria dos filósofos estoicos e a empatia de um grande amigo. Esse é o Alfred.

Nosso objetivo com Alfred é criar uma parceria entre o ser humano e a inteligência artificial para ajudar as pessoas a encontrarem um rumo e a melhorarem em diversas áreas da vida, com apoio constante para não desistir.

Alfred é mais que um assistente: é um amigo estoico e inteligente construído para te apoiar com sabedoria, praticidade e carinho em sua jornada de autodescoberta e melhoria contínua. Ele está aqui para te mostrar que, com disciplina e a atitude certa, você pode colocar um rumo na sua vida.

## ✨ Conheça as Personalidades de Alfred

Alfred está dividido em cinco áreas de especialização, cada uma com um tom fundamentalmente estoico, amigável e que demonstra cuidado, prontas para conversar e te ajudar a traçar seu caminho:

* **Fortitude (Motivação) 💪✨:** Não apenas frases prontas, mas uma conversa que busca entender sua necessidade real para te oferecer motivação estoica personalizada e que toca a alma, te ajudando a encontrar força interior.
* **Ordem (Organização) 🗓️🗺️:** Vai além de dicas genéricas. Alfred conversa com você, entende seus desafios e te ajuda a construir rotinas e planos práticos e mastigados, tornando o caos do dia a dia algo gerenciável.
* **Corpo (Disciplina Física) 💪🏃‍♀️:** Ajuda você a dialogar sobre seus objetivos físicos e a montar rotinas de treino ou planos de atividade que se encaixem *na sua realidade*, com foco na disciplina e resiliência estoica necessárias para cuidar do templo que é seu corpo.
* **Nutrição (Alimentação Consciente) 🌱🍎:** Guia você em uma conversa para organizar seus horários de refeição e planejar suas escolhas alimentares com base em uma alimentação consciente e sábia, nutrindo não só o corpo, mas também a mente.
* **Finanças (Prosperidade Material) 💰📊:** Conversa abertamente com você sobre sua situação financeira para te ajudar a organizar despesas, criar metas realistas e construir um plano prático para sua prosperidade, sempre com a sabedoria estoica sobre o verdadeiro valor das coisas.

## 🧠 Como Alfred Funciona

Alfred interage de forma **profundamente conversacional e prática** dentro de cada personalidade (exceto em Fortitude, que pode ser mais direta, mas sempre pessoal), fazendo perguntas pertinentes para te ajudar a refletir e chegar a um plano concreto para seus objetivos. Ele sempre se comunica com a **empatia genuína de um amigo que se importa**, utilizando alguns símbolos para adicionar carisma à interação. 😊

Tecnicamente, Alfred é um programa escrito em **Python** que utiliza o poder e a inteligência da **API do Google Gemini** para dar vida a cada uma dessas personalidades, permitindo interações ricas, contextuais e verdadeiramente personalizadas.

---

## 🚀 Primeiros Passos (Rodando Localmente)

Para rodar o Alfred na sua máquina localmente, siga estes passos:

1.  **Pré-requisitos:** Certifique-se de ter **Python 3.x** instalado em seu sistema.
2.  **Obtenha sua Chave da API Gemini:** Você precisará de uma chave da API do Google Gemini. Você pode obtê-la [aqui](https://makersuite.google.com/acquire_access) (Pode ser necessário ajustar o link se a URL mudar).
3.  **Clone o Repositório:** Abra o terminal e clone este projeto:
    ```bash
    git clone [https://github.com/SeuUsuario/NomeDoRepositorio.git](https://github.com/SeuUsuario/NomeDoRepositorio.git) # Substitua pelo link real do seu repositório
    cd NomeDoRepositorio
    ```
4.  **Instale as Dependências:** Navegue até a pasta do projeto e instale as bibliotecas necessárias:
    ```bash
    pip install -r requirements.txt
    ```
5.  **Configure sua Chave da API:** Crie um arquivo chamado `.env` na raiz do projeto (na mesma pasta do arquivo `main.py` ou similar) e adicione a seguinte linha, substituindo `SUA_CHAVE_AQUI` pela sua chave real da API Gemini:
    ```dotenv
    GEMINI_API_KEY=SUA_CHAVE_AQUI
    ```
6.  **Execute Alfred:**
    ```bash
    python main.py # Ou o nome do arquivo Python que inicia o Alfred
    ```
    Siga as instruções na tela para interagir com as diferentes personalidades de Alfred.

---

## ☁️ Usando no Google Colab

Se você prefere usar o Alfred diretamente no navegador sem instalar localmente, pode utilizar o Google Colab:

1.  **Abra um novo Notebook Colab:** Vá para [Google Colab](https://colab.research.google.com/) e crie um novo notebook.
2.  **Clone o Repositório (ou Baixe):** Em uma célula de código, execute o comando para clonar o repositório:
    ```python
    !git clone [https://github.com/SeuUsuario/NomeDoRepositorio.git](https://github.com/SeuUsuario/NomeDoRepositorio.git) # Substitua pelo link real do seu repositório
    %cd NomeDoRepositorio # Navegue para o diretório clonado
    ```
    *(Alternativamente, você pode baixar os arquivos do GitHub e fazer upload para o ambiente Colab)*
3.  **Instale as Dependências:** Em outra célula de código, instale as bibliotecas necessárias:
    ```python
    !pip install -r requirements.txt
    ```
4.  **Configure sua Chave da API:** **Não crie um arquivo `.env` em notebooks públicos.** A maneira mais segura no Colab é usar os "Segredos".
    * Clique no ícone da "chave" (🔑) no menu da esquerda do Colab.
    * Clique em "+ Novo segredo".
    * No campo "Nome", digite `GEMINI_API_KEY`.
    * No campo "Valor", cole sua chave da API Gemini.
    * Certifique-se de que a opção "Acesso ao notebook" esteja ativada para este notebook.
    * No seu código Python (no notebook), você acessará a chave assim:
        ```python
        from google.colab import userdata
        import os

        api_key = userdata.get('GEMINI_API_KEY')
        os.environ['GEMINI_API_KEY'] = api_key # Defina a variável de ambiente, se seu código a espera assim
        ```
        *(Adapte a forma como você acessa a chave no seu código Python para usar `userdata.get('GEMINI_API_KEY')`)*
5.  **Execute Alfred:** Em uma célula de código, execute o script principal:
    ```python
    !python main.py # Ou o nome do arquivo Python que inicia o Alfred
    ```
    Você poderá interagir com Alfred diretamente na saída do notebook Colab.


**Alfred: Sabedoria Estoica e Inteligência Artificial de Mãos Dadas para o Seu Crescimento Pessoal.**
