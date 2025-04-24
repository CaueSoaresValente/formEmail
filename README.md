Passo a Passo

Criação do formulário:
O formulário de cadastro HTML está com a estilização simples, criado para ser exibido centralizado na tela utilizando flexbox com as propriedades display: flex, justify-content: center e align-items: center.

Título
O título principal <h1> com a palavra "CADASTRO", estilizado com a tag <i> para deixar o texto em itálico.

Campo de Nome
O campo de entrada do tipo text com o id="name" e o name="name", com um maxlength de 30 caracteres e preenchimento automático habilitado. Estilizado com border-radius e padding para um visual arredondado e espaçado.

Campo de E-mail
O campo do tipo email, com validação embutida do HTML5, limitado a 50 caracteres e com sugestão de preenchimento automático.

Campo de Telefone
O campo tel com limite de 11 caracteres e placeholder no formato brasileiro. Também estilizado para visual arredondado.

Upload de Currículo
O campo file para envio de um arquivo (presumivelmente um currículo). Apesar disso, o FormSubmit não aceita arquivos diretamente, então esse campo pode não funcionar como esperado sem outro back-end de suporte.

Campo de Mensagem
O campo textarea para digitação de uma mensagem com limite de 200 caracteres. Estilizado de forma semelhante aos outros campos.

Botão de Envio
Botão do tipo submit.

Como o formulário ficou funcional:
Na criação do form, no atributo action, chamamos a api juntamente ao e-mail que desejamos enviar este formulário 
O botão do tipo submit, envia os dados para o e-mail definido no action. O mesmo possui também, o parâmetro _next para redirecionar o usuário para uma nova página (telaadcional.html) após o envio.

Criação do repositório
Criei o repositório remoto pela a interface do GitHub, entretanto, deixei este repositório sem README.md;
Fui para o git e fiz os seguintes comandos: git init, git config --global user.name "CaueValente", git config --global user.email "cauevalente00@gmail.com", git remote add origin https://github.com/CaueSoaresValente/formEmail.git,
git add ., git commit"Formulário HTML e Consumo de API", git branch -M main e git push -u origin main.

