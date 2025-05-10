# Streaming Sharing Page

  

**Sua central visual para organizar, divulgar e gerenciar vagas em grupos de assinaturas compartilhadas de streaming, música ou cursos online.**

  

---

  

## 🚩 O que é?

  

O **Streaming Sharing Page** é uma Landing Page pronta, projetada para facilitar a vida de grupos de compartilhamento de assinaturas online. Com visual moderno, intuitivo e responsivo, ela lista todos os serviços e vagas disponíveis do seu grupo, com busca instantânea, detalhes de cada assinatura e botões de acesso direto para contato via Telegram ou WhatsApp.

  

![enter image description here](https://i.ibb.co/8g65ZwSk/Screenshot-660.png)

  

---

  

## 🎯 Principais diferenciais

  

-  **Fácil customização:** Interface separada para editar e gerar sua lista de assinaturas, sem precisar editar código manualmente!

-  **Busca instantânea:** Encontre rapidamente vagas por serviço, status ou método.

-  **Design responsivo:** Funciona perfeitamente em celulares e computadores.

-  **Links rápidos:** Botões diretos para grupos do WhatsApp e Telegram.

-  **Visual atrativo:** Cards bonitos, com ícones e informações organizadas.

-  **Fácil atualização:** Atualize o arquivo `script.js` em segundos com a ferramenta online.

  

---

  

## ⚙️ Como funciona a atualização dos dados?

  

### Gerencie suas assinaturas sem editar código!

  

1.  **Acesse o editor online gratuito:**

👉 [Editor Versatile - Streaming Sharing Editor](https://huggingface.co/spaces/alexlivre/versatileeditor)

  

2.  **Faça upload do seu arquivo atual `script.js`.**

3.  **Adicione, edite, delete, duplique e organize** suas assinaturas usando a tabela intuitiva.

4.  **Gere e baixe o `script_updated.js` atualizado**.

5.  **Renomeei o arquivo `script_updated.js` para `script.js`**.
   
6.  **Substitua o arquivo `script.js` na pasta do seu site** pelo novo arquivo baixado.

7. Pronto! **Sua landing page mostrará a lista atualizada automaticamente.**

  

> Este editor resolve tudo: nenhuma necessidade de saber programar ou editar códigos manualmente!

> O editor "**Versatile Editor**" foi criado justamente para este projeto.

  

![enter image description here](https://i.ibb.co/9m0zKMqV/editorversatile-Screenshot-650.png)

---

  

## 🛠️ Como customizar o nome do seu grupo na página

  

Você pode deixar a sua Landing Page com a identidade do seu grupo em poucos passos!

  

1.  **Abra o arquivo `index.html` em qualquer editor de texto.**

2.  **Altere o nome do grupo em dois pontos importantes:**

  

-  **Título da janela do navegador:**

  

Procure a linha:

```html

<title>Assinaturas Compartilhadas</title>

```

  

Troque pelo nome do seu grupo. Por exemplo:

```html

<title>Grupo Amigos do Streaming</title>

```

  

-  **Título principal exibido na página ("header"):**

  

Procure a linha:

```html

<h1  class="text-4xl font-extrabold text-yellow-700 drop-shadow-lg tracking-tight">Nome do seu grupo de compartilhamento.</h1>

```

  

Troque pelo nome do seu grupo. Por exemplo:

```html

<h1  class="text-4xl font-extrabold text-yellow-700 drop-shadow-lg tracking-tight">Amigos do Streaming</h1>

```

![enter image description here](https://i.ibb.co/Kprnnqrf/edit-script-Screenshot-650.png)

  

3.  **Salve o arquivo e atualize a página no navegador.**

  

Pronto! Sua página agora aparece personalizada com o nome do seu grupo.

  

---

  

## 📁 Estrutura do projeto

  

```

/

├── index.html # Página principal (onde você personaliza o nome do grupo)

├── script.js # Dados e lógica das assinaturas (atualizados via o editor online)

├── README.md # Este arquivo, com instruções completas

```

  

---

  

## 💻 Tecnologias usadas

  

-  **HTML5** (estrutura da página)

-  **Tailwind CSS** (estilização moderna e responsiva)

-  **JavaScript puro** (renderização dinâmica e busca)

-  **Font Awesome** (ícones)

- [Versatile Editor (Gradio/Python)](https://huggingface.co/spaces/alexlivre/versatileeditor) *(para edição do script.js, externo a este repositório)*

  

---

  

## ⏩ Instalação e uso rápido

  

1.  **Baixe ou clone este repositório:**

```bash

git clone https://github.com/seu-usuario/streaming-sharing-page.git

```

  

2.  **Personalize o nome do seu grupo em `index.html`** conforme instruções acima.

  

3.  **Atualize a lista de assinaturas com o editor online,** conforme explicado [aqui](#-como-funciona-a-atualização-dos-dados).

  

4.  **Abra o arquivo `index.html` em qualquer navegador.**

Tudo pronto!

  

---

  

## 📋 Licença

  

Este projeto está licenciado sob a **Licença MIT**.

###  Aviso Importante sobre o Rodapé e a Licença MIT

Este projeto é de minha autoria, Alex Breno, e estou liberando-o publicamente no GitHub sob a **Licença MIT**.

### O que a Licença MIT permite?

- Uso livre do código, inclusive para fins comerciais.
- Possibilidade de modificar, copiar, distribuir e até vender o software.
- Total liberdade para criar projetos derivados.

### Minha única exigência:

Embora você tenha liberdade para modificar o código, **não é permitido alterar, remover ou ocultar o rodapé presente na interface do projeto**. 

O rodapé contém informações importantes sobre a autoria e os créditos do projeto, e manter essas informações visíveis é **a única condição para o uso e redistribuição deste software**.

### Por que essa exigência?

O rodapé funciona como o **aviso de copyright e reconhecimento do autor**, que deve ser mantido para respeitar a autoria do projeto. Essa condição está alinhada com o espírito da Licença MIT, que exige a manutenção desse aviso em cópias e distribuições do software.

### Resumo

- Pode usar, copiar e modificar o projeto livremente.
- Deve manter o rodapé original intacto.
- Essa é a única condição que peço para respeitar meu trabalho.

---

  

## 👨‍💻 Sobre o editor online (Diferencial deste projeto!)

  

O editor [Versatile Editor](https://huggingface.co/spaces/alexlivre/versatileeditor):

  

- Não exige cadastro;

- Funciona online em celulares e computadores;

- Permite editar sua lista de assinaturas facilmente via uma tabela;

- Gera o arquivo prontinho, sem erros de formatação.

  

---

  

## 📬 Suporte e contribuição

  

Fique à vontade para abrir **issues** com dúvidas, sugestões ou problemas.

Pull requests, melhorias e colaborações são encorajados!

  

Autor: **Alex Breno**

GitHub: [@alexlivre](https://github.com/alexlivre)

Site: [inteligenciaversatil.com.br](https://inteligenciaversatil.com.br)

  

Feito com 🍿, tecnologia e praticidade para todos os grupos de compartilhamento!
