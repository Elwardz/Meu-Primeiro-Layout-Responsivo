# 💻 Meu Primeiro Layout Responsivo – Flex e Grid

![image](https://github.com/user-attachments/assets/7534a169-0463-48b2-8de3-b1345304cbb5)


Este repositório contém dois projetos desenvolvidos como exercício prático utilizando **HTML semântico**, **CSS Flexbox** e **CSS Grid**. O objetivo foi criar um layout baseado em um modelo proposto, com foco em **responsividade** para diferentes tamanhos de tela.

---

## 📁 Estrutura do Repositório

![image](https://github.com/user-attachments/assets/0fa3d7f6-b102-471f-9f44-e085e14dafa8)


- `flexbox-layout/`: Projeto utilizando apenas **CSS Flexbox**.
- `grid-layout/`: Projeto utilizando **CSS Grid combinado com Flexbox**.
- `README.md`: Explicações sobre os projetos e principais aprendizados durante o desenvolvimento.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5**
- **CSS3**
  - Flexbox
  - Grid
  - Media Queries (para responsividade)

---

## 🧱 Estrutura dos Layouts

Ambos os projetos seguem a mesma estrutura visual e semântica:

- **Header** contendo uma `nav` alinhada à direita.
- **Main** dividido entre uma área principal (com sections e articles) e um `aside`.
- **Footer** posicionado ao final da página.
- Layout adaptável para diferentes tamanhos de tela (responsivo).

---

## 🔍 Relato Pessoal: Diferenças entre Flexbox e Grid + Flexbox

### 🧩 Usando somente Flexbox

> "O Flexbox foi tranquilo de usar pra montar um layout em colunas, principalmente porque ele é ótimo pra alinhar e distribuir elementos em linha ou em coluna. Mas pra fazer colunas com tamanhos diferentes, como uma maior pro conteúdo principal e uma menor pro aside, precisei usar `flex: 3` e `flex: 1`, o que exige mais atenção. Além disso, pra deixar responsivo, precisei mudar a direção dos elementos com `flex-direction: column`, o que funciona, mas não é tão direto quanto o Grid."

---

### 🧩 Usando CSS Grid combinado com Flexbox

> "Já com o Grid, foi bem mais fácil estruturar o layout geral. Só com `grid-template-columns: 3fr 1fr`, já consegui definir a divisão principal da página. Na responsividade, foi mais simples também: só troquei as colunas por uma única com `grid-template-columns: 1fr` dentro de um `@media`. O Flexbox ficou responsável apenas por alinhar os elementos internos, como os artigos e a `nav`. Senti que com Grid o código ficou mais organizado e escalável."

---

## ✅ Conclusão

> "No geral, achei que a combinação de Grid com Flexbox deixou o projeto mais limpo e fácil de manter. O Flexbox funciona bem sozinho, mas quando a estrutura do layout é mais complexa, o Grid ajuda bastante na clareza e controle das áreas. Pra projetos maiores, com várias seções, o Grid vale muito a pena."

---

## 👨‍🎓 Desenvolvido por **Gabriel Lopes de Albuquerque** 
 
Estudante de Engenharia de Software – Universidade de Pernambuco (UPE)  
Projeto prático de front-end com foco em HTML, CSS e Responsividade.

---

## 🌐 Acesso ao Projeto

Você pode acessar a versão publicada do layout com CSS Grid aqui:

🔗 [https://elwardz.github.io/Meu-Primeiro-Layout-Responsivo/](https://elwardz.github.io/Meu-Primeiro-Layout-Responsivo/)



