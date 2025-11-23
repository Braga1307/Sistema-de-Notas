## 📚 README: Sistema de Notas Escolares em Python

Este é um projeto simples em Python para a gestão básica de notas de um único aluno, permitindo a inserção de notas, o cálculo da média e a determinação da situação final (Aprovado ou Reprovado).

---

### 🌟 Funcionalidades

* **Registro de Aluno:** Coleta o nome do aluno.
* **Entrada de Notas:** Permite a inserção de um número definido de notas, garantindo que o valor esteja entre 0 e 10.
* **Cálculo Automático:** Calcula a **média aritmética** das notas inseridas.
* **Determinação da Situação:** Classifica o aluno como **APROVADO** (Média $\ge 6.0$) ou **REPROVADO** (Média $< 6.0$).
* **Relatório Final:** Exibe um resumo formatado com todas as informações.

---

### ⚙️ Detalhes Técnicos

O código é estruturado em uma única função (`sistema_notas`) e utiliza as seguintes características do Python:

* **Dicionário (`dict`):** Usado para armazenar os dados do aluno (`nome`, `notas`, `media`, `situacao`).
* **Listas (`list`):** Usada para armazenar as notas individuais (`notas`).
* **Estruturas de Controle:**
    * **`while True` / `try...except ValueError`:** Utilizadas para garantir que o usuário insira apenas valores numéricos válidos (tratamento de erros).
    * **`if/else`:** Usadas para a validação do intervalo das notas e para determinar a situação final.
* **Funções Integradas:**
    * `input()` para coleta de dados.
    * `sum()` e `len()` para facilitar o cálculo da média.
    * `round()` para formatar a média.

---

### 🤝 Contribuições

Sinta-se à vontade para fazer *fork* do projeto e enviar *pull requests* com melhorias. Algumas ideias de expansão incluem:

* Adicionar suporte para **múltiplos alunos**.
* Implementar a **persistência de dados** (salvar/carregar dados em um arquivo CSV ou JSON).
* Criar uma **interface gráfica** (GUI) usando bibliotecas como Tkinter ou PyQt.
