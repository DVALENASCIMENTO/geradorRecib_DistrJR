# Gerador de Recibos - JR Distribuidora

![image](https://github.com/user-attachments/assets/aca818c3-ffe7-4a9b-ba79-58ceefa9479a)

https://dvalenascimento.github.io/geradorRecib_DistrJR/

Este é um sistema web simples e responsivo para geração de recibos personalizados em PDF, desenvolvido para a **JR Distribuidora**. Ele permite que o usuário insira os dados do cliente, produtos/serviços adquiridos, valores e forma de pagamento, e gere recibos de maneira prática.

---

## 🎯 **Funcionalidades**

- **Cadastro de Cliente:** Insira informações como nome, CPF e endereço do cliente.
- **Adição de Produtos/Serviços:** Permite adicionar múltiplos itens ao recibo.
- **Cálculo Automático:** Soma automaticamente os valores dos produtos/serviços adicionados.
- **Geração de Recibo em PDF:** Criação de recibos personalizados com os dados fornecidos.
- **Design Responsivo:** Compatível com dispositivos móveis, tablets e desktops.
- **Estilização Atraente:** Interface intuitiva e visual moderno.

---

## 🛠️ **Tecnologias Utilizadas**

- **HTML5:** Para estruturação da página.
- **CSS3:** Para estilização e design responsivo.
- **JavaScript:** Para funcionalidades interativas e geração de PDF.
- **jsPDF:** Biblioteca para gerar documentos PDF diretamente no navegador.

---

## 📂 **Estrutura do Projeto**

```
/gerador-recibos
├── index.html              // Página principal
├── css/
│   └── styles.css          // Estilo da página
├── js/
│   └── script.js           // Lógica do JavaScript
├── assets/
│   └── logo_jr_distribuidora.webp  // Logo da empresa
└── README.md               // Documentação do projeto
```

---

## 🚀 **Como Utilizar**

1. **Preencha os Dados do Cliente:**
   - Nome, CPF e endereço.

2. **Adicione Produtos ou Serviços:**
   - Insira o nome e o valor do produto/serviço e clique no botão "Adicionar Produto".

3. **Escolha a Forma de Pagamento:**
   - Preencha o campo com a forma de pagamento utilizada (ex: PIX, Dinheiro).

4. **Gere o Recibo:**
   - Clique no botão "Gerar Recibo PDF" para criar o documento.

5. **Baixe o Recibo:**
   - O recibo será automaticamente baixado no formato PDF.

---

## 📑 **Exemplo de Recibo**

O recibo gerado contém:

- Informações do emitente (JR Distribuidora).
- Dados do cliente (nome, CPF, endereço).
- Lista de produtos/serviços adquiridos com os respectivos valores.
- Valor total e forma de pagamento.
- Espaços para assinatura do cliente e do emitente.

---

## 📱 **Design Responsivo**

O layout do sistema foi projetado para oferecer uma experiência otimizada em diferentes dispositivos. A interface adapta-se automaticamente para smartphones, tablets e desktops.

---

## 📸 **Captura de Tela**

### Página Principal
- **Formulário de entrada de dados do cliente, produtos e valores.**

---

## 📝 **Observações**

- A funcionalidade de geração de PDF utiliza a biblioteca jsPDF, que pode apresentar limitações em relação a fontes e formatos avançados.
- Certifique-se de que o caminho da logo está correto no arquivo `script.js` para inclusão no PDF.

---

## 🏗️ **Melhorias Futuras**

- Adicionar validação avançada para os campos de entrada.
- Permitir edição e exclusão de produtos/serviços já adicionados.
- Implementar banco de dados para persistência dos recibos gerados.

---

**Autor:** Diego Nascimento  
**Contato:** [devalecode@gmail.com]
