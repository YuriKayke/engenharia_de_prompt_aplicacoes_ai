Tarefa 1

Certo. Vou te explicar no estilo “militar”: direto, organizado e sem enrolação.

---

## 🎯 MISSÃO: ENTENDER API

### 📌 O que é API

API (Application Programming Interface) é um **meio de comunicação entre sistemas**.

➡️ Tradução simples:
É como um **mensageiro** que leva pedidos e traz respostas entre dois sistemas.

**Exemplo:**

* Um app pede: “me mostra a previsão do tempo”
* A API vai até o servidor, pega os dados e traz de volta

---

## ⚙️ Como funciona (PASSO A PASSO)

### 🔹 1. Requisição (Request)

Você faz um pedido
Ex: “Quero dados do usuário”

### 🔹 2. Processamento

O servidor recebe e entende o pedido

### 🔹 3. Resposta (Response)

O servidor devolve os dados

---

### 📡 Tipos comuns de requisição:

* **GET** → Buscar informação
* **POST** → Enviar informação
* **PUT** → Atualizar
* **DELETE** → Apagar

---

## 🧠 Analogia militar

Imagine um quartel:

* 👨‍✈️ Soldado = Usuário / Sistema
* 📡 Rádio = API
* 🏢 Comando = Servidor

O soldado não entra direto no comando.
Ele usa o rádio (API) para pedir informação.

---

## 💼 Aplicação no mercado de trabalho

### 🔥 Onde APIs são usadas:

* Aplicativos (banco, delivery, redes sociais)
* Sistemas de empresas
* Integrações (ex: site + pagamento)

---

### 🚀 Exemplos reais:

* Login com Google → usa API
* Pagamentos com Pix → usa API
* Apps como Uber → usam várias APIs

---

## 🎖️ Importância no mercado

Saber API te coloca em vantagem porque:

* Empresas precisam integrar sistemas
* Tudo hoje se conecta (apps, sites, bancos)
* É base para:

  * Programação
  * Desenvolvimento web
  * Back-end

---

## 🧩 Tipos de API (nível básico)

* **API pública** → qualquer um pode usar
* **API privada** → uso interno da empresa
* **API de terceiros** → você usa serviços prontos

---

## 📊 Resumo tático

* API = ponte entre sistemas
* Funciona com pedido e resposta
* Base da tecnologia moderna
* Muito valorizada no mercado

---

Mais estruturada 

🪖 **ATENÇÃO, RECRUTA — FOCO EM ESTRUTURA**
Aqui não há improviso. Vamos decompor API como um manual de operação militar: claro, organizado e executável.

---

## 🎯 MISSÃO: ENTENDER A ESTRUTURA DE UMA API

---

## 📌 1. O que é API (VISÃO ESTRUTURAL)

API é uma **interface estruturada de comunicação entre sistemas**.

👉 Em termos diretos:
É um **conjunto de regras + caminhos + formatos** que permitem interação controlada.

---

## 🧱 2. Estrutura de uma API

Uma API bem organizada possui os seguintes elementos:

---

### 🔹 2.1 Endpoint (Ponto de acesso)

É o **endereço** onde você faz a requisição.

Exemplo:

```
/usuarios
/pedidos
```

👉 Cada endpoint representa um recurso.

---

### 🔹 2.2 Método (Ação)

Define o que será feito no endpoint:

* **GET** → Buscar dados
* **POST** → Criar dados
* **PUT** → Atualizar
* **DELETE** → Remover

👉 Mesmo endereço, ações diferentes.

---

### 🔹 2.3 Requisição (Request)

É o que o cliente envia:

Contém:

* Cabeçalhos (headers)
* Parâmetros
* Corpo (body)

👉 Aqui está a ordem que você dá ao sistema.

---

### 🔹 2.4 Resposta (Response)

É o retorno da API:

Contém:

* Status (200, 404, 500…)
* Dados (geralmente JSON)

👉 Aqui está o resultado da missão.

---

### 🔹 2.5 Formato de dados

O padrão mais comum é:

* JSON (leve e organizado)

Exemplo:

```json
{
  "nome": "João",
  "idade": 25
}
```

---

### 🔹 2.6 Autenticação (Segurança)

Define quem pode acessar:

* Token
* Chave de API
* Login

👉 Sem isso: vulnerabilidade total.

---

## ⚙️ 3. Como funciona (FLUXO ESTRUTURADO)

1. Cliente envia requisição → endpoint + método
2. Servidor valida (segurança + regras)
3. Processa a ação
4. Retorna resposta padronizada

👉 Fluxo linear, previsível, controlado.

---

## 🧠 4. Analogia militar (ESTRUTURA DE COMANDO)

* 🪖 Soldado → Cliente
* 📡 Canal oficial → API
* 🏢 Quartel → Servidor
* 📍 Endereço → Endpoint
* 📜 Ordem → Método
* 🎯 Resultado → Response

👉 Sem estrutura: falha de missão.

---

## 🌍 5. Aplicação no mundo real

APIs estruturam sistemas modernos.

---

### 🚀 Exemplos:

* Google → múltiplos serviços integrados
* Pix → comunicação bancária em tempo real
* Uber → integração de mapas, usuários e pagamentos

👉 Todos seguem estrutura de API.

---

## 💼 6. Aplicação no mercado de trabalho

### 🔥 Onde essa estrutura é usada:

* Desenvolvimento de sistemas
* Aplicativos móveis
* Sites e plataformas
* Integração entre empresas

---

### 🎖️ Habilidades valorizadas:

* Criar APIs (back-end)
* Consumir APIs (front-end)
* Integrar sistemas
* Garantir segurança e desempenho

---

## 📊 7. RESUMO ESTRUTURAL

* API = interface estruturada
* Possui:

  * Endpoint
  * Método
  * Request
  * Response
  * Segurança
* Funciona em fluxo controlado
* Base da tecnologia moderna

---

🪖 **ORDEM FINAL:**
Quem entende a estrutura não depende de tentativa e erro.
👉 **Opera com precisão, como um comandante que conhece cada peça do sistema.**

Tarefa 2

Como instrutor, vou te entregar algo sólido, claro e com disciplina de código.

🎯 Função: cálculo de média com tratamento rigoroso
✅ Requisitos atendidos:
   Lista não pode ser vazia
   Todos os elementos devem ser números
   Tratamento de erros explícito

   🧠 Código Python (amplamente comentado)
def calcular_media(lista):
    """
    Calcula a média de uma lista de números com validações rigorosas.

    Parâmetros:
    lista (list): Lista contendo números (int ou float)

    Retorno:
    float: Média dos valores da lista

    Exceções:
    TypeError: Se a entrada não for uma lista ou contiver elementos não numéricos
    ValueError: Se a lista estiver vazia
    """

    # Verifica se o argumento passado é realmente uma lista
    if not isinstance(lista, list):
        raise TypeError("O valor fornecido deve ser uma lista.")

    # Verifica se a lista está vazia
    if len(lista) == 0:
        raise ValueError("A lista não pode estar vazia.")

    # Inicializa a soma dos valores
    soma = 0

    # Itera sobre cada elemento da lista
    for i, elemento in enumerate(lista):
        # Verifica se cada elemento é numérico (int ou float)
        if not isinstance(elemento, (int, float)):
            raise TypeError(f"Elemento inválido na posição {i}: {elemento}")

        # Acumula o valor na soma
        soma += elemento

    # Calcula a média dividindo a soma pelo número de elementos
    media = soma / len(lista)

    # Retorna o resultado
    return media
    
---
  
  🧪 Casos de teste (exatamente 3)

# Caso 1: Lista válida
print(calcular_media([10, 20, 30]))  
# Esperado: 20.0

# Caso 2: Lista vazia (deve gerar erro)
print(calcular_media([]))  
# Esperado: ValueError

# Caso 3: Lista com valor inválido (deve gerar erro)
print(calcular_media([10, "a", 30]))  
# Esperado: TypeError
