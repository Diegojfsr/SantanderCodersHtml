
Formulários

- Propriedades(name, type, value)
- text
- password
- email
- number
- checkbox
- date
- time
- file
- url
- radio
- submit
- color
- range
- reset
Select--
- select
- option
- Props: value, selectes, disabled
Textarea--
Submissao--
- action
- method


Tags para a construcao do formulario.

<form></form> - Tag inicial para construir os formularios e Todo o conteudo dentro dele.

<input> - nao tem fechamento apenas atributos e tipos dentro delas.

<input type="text" id="texto"> - recebe valores de texto. Sempre bm que tenha um id para referenciar o label.

<label for="texto"> - texto fazendo referencia ao campo input.

<placeholder> - acompanha a tag input text, insere um texto dentro do input.
<input type="text" id="texto" placeholder="Informe seu nome.">

<value> - insere um valor inicial dentro do input.
<input type="text" id="texto" value="Diego">

<name> - ajuda o javascript a identificar o campo, durante o envio do formulario.
<input type="text" id="texto" name="Nome">


<input type="password"> - recebe valores de senhas.

<input type="email"> - recebe valores de e-mail.

