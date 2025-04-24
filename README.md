# 📋 Formulário de Cadastro HTML

Este projeto é um formulário de cadastro simples feito em HTML, utilizando estilização básica inline e centralizado com Flexbox. Os dados são enviados via **FormSubmit**, diretamente para um e-mail configurado.

---

## 🛠️ Criação do Formulário

O formulário foi desenvolvido com foco em simplicidade e funcionalidade. Veja abaixo os elementos implementados:

### 🧾 Título

- Um título principal `<h1>` com a palavra **"CADASTRO"**, estilizado com a tag `<i>` para exibir em itálico.

### 👤 Campo de Nome

- Campo do tipo `text`, com `id="name"` e `name="name"`.
- Máximo de 30 caracteres, com preenchimento automático e estilo arredondado.

### 📧 Campo de E-mail

- Campo do tipo `email`, com validação HTML5 e limite de 50 caracteres.
- Sugestão de preenchimento automático habilitada.

### 📱 Campo de Telefone

- Campo do tipo `tel`, com limite de 11 caracteres.
- Placeholder no formato brasileiro, com estilo visual arredondado.

### 📎 Upload de Currículo

- Campo `file` para upload de um currículo.

> ⚠️ **Atenção**: O FormSubmit não suporta envio direto de arquivos, portanto este campo pode não funcionar sem um back-end adicional.

### 📝 Campo de Mensagem

- Campo `textarea` com limite de 200 caracteres.
- Estilizado com `border-radius` e `padding` para consistência visual.

### 📤 Botão de Envio

- Botão do tipo `submit`, que envia os dados do formulário para o e-mail especificado.
- Inclui o parâmetro `_next` para redirecionamento automático para a página `telaadcional.html` após o envio bem-sucedido.

---

## 🔧 Como o Formulário Funciona

- No atributo `action` do `<form>`, foi usada a API do [FormSubmit](https://formsubmit.co) junto com o e-mail de destino: `cauevalente00@gmail.com`.
- Ao clicar no botão **Enviar**, os dados são enviados automaticamente para o e-mail configurado.
- Após o envio, o usuário é redirecionado para a página `telaadcional.html`.

---

## 🚀 Publicação no GitHub

Abaixo estão os passos utilizados para versionar e publicar este projeto no GitHub:

1. Criei o repositório remoto na interface do GitHub, **sem arquivo README.md**.
2. No terminal, executei os seguintes comandos:

```bash
git init
git config --global user.name "CaueValente"
git config --global user.email "cauevalente00@gmail.com"
git remote add origin https://github.com/CaueSoaresValente/formEmail.git
git add .
git commit -m "Formulário HTML e Consumo de API"
git branch -M main
git push -u origin main
