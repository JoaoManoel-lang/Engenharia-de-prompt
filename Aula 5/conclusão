# 📖 Introdução

Neste documento, vamos explorar a diferença entre prompts vagos e prompts refinados na geração de código Python. 

Primeiramente, apresentaremos um exemplo de um prompt vago e o código básico que ele pode gerar. Este código tende a ser menos robusto, pois geralmente não inclui verificações de segurança, comentários detalhados ou exemplos de testes, o que pode dificultar a manutenção e a compreensão do código.

Em seguida, vamos refinar o prompt, adicionando especificações claras sobre os requisitos do código, como tipos de dados esperados, validações de entrada, comentários explicativos e exemplos de testes. Com um prompt refinado, o código gerado será mais completo, seguro e fácil de entender, ilustrando a importância de fornecer instruções precisas ao utilizar inteligência artificial para gerar código.

Através desta comparação, você poderá observar como a precisão e a clareza nas instruções impactam a qualidade do código gerado. Além disso, aprenderá boas práticas para solicitar códigos eficientes, bem estruturados e de fácil manutenção.

Esta análise visa aprimorar suas habilidades na solicitação de ajuda de IA para desenvolvimento de software, garantindo resultados mais alinhados com suas necessidades e expectativas.

---

> 💬 Crie um código em Python para calcular a soma de números.

```python
# Função para calcular a soma de uma lista de números
def soma_numeros(numeros):
    # Utiliza a função sum para calcular a soma
    return sum(numeros)

# Exemplo de uma lista de números
numeros = [5, 10, 15, 20]

# Calcula a soma dos números na lista
total = soma_numeros(numeros)

# Imprime o resultado
print(total)
```

> 🎯 "Escreva um código Python que some uma lista não vazia de números inteiros positivos. O código deve incluir comentários explicativos para cada parte do código. Se a lista estiver vazia ou contiver elementos que não sejam inteiros, o código deve retornar uma mensagem de erro apropriada. O código deve ser testado com exemplos que demonstrem as condições de erro e o funcionamento normal."

```python
# Função para somar uma lista de números inteiros
# Retorna uma mensagem de erro se a lista estiver vazia ou contiver elementos não inteiros
def soma_lista_numeros(lista_numeros):
    """
    Soma uma lista de números inteiros positivos e retorna a soma.
    Se a lista estiver vazia ou contiver elementos não inteiros, retorna uma mensagem de erro.
    """
    # Verifica se a lista está vazia
    if not lista_numeros:
        return "A lista está vazia, não é possível calcular a soma."

    # Inicializa a variável soma com zero
    soma = 0

    # Itera sobre cada número na lista
    for numero in lista_numeros:
        # Verifica se o número é inteiro
        if not isinstance(numero, int):
            return "Todos os elementos da lista devem ser inteiros."
        
        # Adiciona o número atual à soma
        soma += numero

    # Retorna a soma calculada
    return soma

# Exemplo de uso da função com lista válida
lista_de_numeros_valida = [1, 2, 3, 4, 5]
print(soma_lista_numeros(lista_de_numeros_valida))  # Imprime a soma

# Testes adicionais
print(soma_lista_numeros([]))              # Lista vazia
print(soma_lista_numeros([1, 2, 'a', 4]))  # Elemento não inteiro
```

---

### ⚠️ **Observações sobre o Código Sem Refinamento:**

1. O código assume que a lista de números fornecida como argumento é válida e não vazia.
2. Não há tratamento de erros ou verificação de tipos para os elementos da lista.
3. O código é simples e direto, utilizando a função embutida `sum` para calcular a soma.
4. Não há comentários adicionais explicativos, pois o prompt não especificou a necessidade deles.

### ⚖️ **Comparativo com a Versão Refinada:**

A versão refinada, por outro lado, inclui verificações para assegurar que a lista não está vazia e que todos os elementos são inteiros, além de fornecer comentários explicativos e exemplos de testes para diferentes cenários. A precisão e robustez do código são significativamente maiores quando prompts refinados são utilizados.

---

### 💡 Discussão e Boas Práticas:

👥 **Discussão em Grupo:**

- 🚧 **Restrições** são importantes para guiar a IA a fornecer um código robusto.
- 🧠 **Contexto** adicional melhora a utilidade e a completude do código gerado.
- 📝 **Formato** com comentários e exemplos de testes aumenta a clareza do código.
- 🎭 **Papel** bem definido ajuda a IA a considerar todos os cenários possíveis.

🛠️ **Boas Práticas de Prompting para Desenvolvimento de Sistemas:**

1. 🎯 **Especifique Restrições Claras**.
2. 🖼️ **Forneça Contexto Adequado**.
3. 📐 **Defina o Formato do Código**.
4. 🧑‍💻 **Estabeleça o Papel do Código**.
5. 🧪 **Inclua Exemplos de Testes**.
6. 🔍 **Seja Específico, Mas Flexível**.
