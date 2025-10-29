# 🌦️ Consulta de Clima com API — Projeto de Aprendizado

## 🧠 Objetivo de Aprendizado

Este projeto tem como objetivo **ensinar o consumo de APIs em Python**, utilizando a biblioteca `requests` para realizar **requisições HTTP** e tratar **respostas no formato JSON**.
Além disso, o exercício desenvolve habilidades em:

* Leitura e interpretação de **documentação de APIs**;
* Manipulação de **dados em dicionários Python**;
* Interação com o usuário via **entrada de dados (`input`)**;
* Boas práticas de **tratamento de erros e status da resposta**.

---

## 🧩 Descrição do Projeto

O código realiza a **consulta de informações climáticas** de uma cidade informada pelo usuário.
Ele se conecta à **API do WeatherAPI** e exibe:

* 🌡️ Temperatura atual (em °C);
* ☁️ Descrição do clima (ex.: “Céu limpo”, “Chuva leve”, etc.).

---

## ⚙️ Funcionamento do Código

1. **Define a chave da API e a URL de requisição**;
2. **Recebe o nome da cidade** digitado pelo usuário;
3. **Monta os parâmetros da requisição** (como chave e idioma);
4. **Envia a requisição HTTP** usando o `requests.get()`;
5. **Verifica se a resposta foi bem-sucedida** (`status_code == 200`);
6. **Extrai e exibe as informações de clima** no terminal.

---

## 🧾 Exemplo de Saída

```
Digite o nome da cidade: São Paulo
Temperatura na cidade São Paulo é 23.5°C.
Descrição: Céu limpo
```

---

## 🛠️ Tecnologias Utilizadas

* **Python 3.x**
* **Biblioteca requests**
* **API pública do [WeatherAPI](https://www.weatherapi.com/)**

---

## 📦 Instalação

Antes de rodar o código, instale a biblioteca necessária:

```bash
pip install requests
```

---

## ▶️ Como Executar

1. Baixe ou clone este repositório:

   ```bash
   git clone https://github.com/SEU_USUARIO/nome-do-repositorio.git
   ```
2. Acesse a pasta do projeto:

   ```bash
   cd nome-do-repositorio
   ```
3. Execute o código:

   ```bash
   python clima_api.py
   ```

---

## 🧰 Aprendizado Recomendado

Para compreender completamente este projeto, recomenda-se estudar:

* Introdução ao **HTTP (GET, POST, status code)**;
* Manipulação de **JSON** em Python (`.json()`);
* Uso da **biblioteca requests**;
* Leitura da **documentação de APIs REST**.

---

## 💡 Desafio Extra

Como exercício, tente:

* Exibir também a **sensação térmica** (`feelslike_c`);
* Mostrar **velocidade do vento** (`wind_kph`);
* Tratar **erros de cidade inexistente**;
* Armazenar os resultados em um **arquivo `.txt`**.

---

## 👩‍🏫 Autor / Projeto Didático

Este projeto faz parte das atividades de **aprendizado prático em Python** com foco em **consumo de APIs** e **análise de dados**, orientado pela professora [Alexsandra Campos].


Deseja que eu personalize o final com o nome do curso (por exemplo, *Curso de Programação Python para Data Science — SENAI Ary Torres*) e o seu nome completo como instrutora? Assim posso deixar o README pronto para os alunos apenas adaptarem o nome deles.
