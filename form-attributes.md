# Atributos de Forms no HTML

## Atributos Comuns na Tag `<form>`
- **`action`**  
  Define a URL para onde os dados do formulário serão enviados.  
  **Exemplo:** `action="https://example.com/submit-form"`

- **`method`**  
  Especifica o método HTTP para envio dos dados:
  - `GET`: Dados enviados como parâmetros na URL.
  - `POST`: Dados enviados no corpo da requisição.  
  **Exemplo:** `method="POST"`

- **`target`**  
  Determina onde exibir a resposta ao envio do formulário:
  - `_self` (padrão): Abre na mesma janela.
  - `_blank`: Abre em uma nova aba.  
  **Exemplo:** `target="_blank"`

- **`enctype`**  
  Define o tipo de codificação para os dados do formulário. Usado principalmente com `POST`:
  - `application/x-www-form-urlencoded` (padrão): Para texto.
  - `multipart/form-data`: Para envio de arquivos.  
  **Exemplo:** `enctype="multipart/form-data"`

- **`novalidate`**  
  Impede a validação automática do navegador antes do envio.  
  **Exemplo:** `novalidate`

- **`autocomplete`**  
  Controla se o navegador pode sugerir preenchimento automático:
  - `on` (padrão): Permite.
  - `off`: Desativa.  
  **Exemplo:** `autocomplete="off"`

---

## Atributos Comuns em `<input>` e Outros Campos de Formulário
- **`type`**  
  Define o tipo de campo (e.g., `text`, `password`, `email`, `checkbox`, `radio`, `file` etc.).  
  **Exemplo:** `type="email"`

- **`name`**  
  Identifica o campo ao enviar os dados para o servidor.  
  **Exemplo:** `name="username"`

- **`id`**  
  Um identificador único para o campo, usado para associar um `<label>` ou manipulação no JavaScript.  
  **Exemplo:** `id="user-input"`

- **`value`**  
  Define o valor padrão ou o valor enviado ao servidor.  
  **Exemplo:** `value="option1"`

- **`placeholder`**  
  Mostra um texto temporário no campo até o usuário começar a digitar.  
  **Exemplo:** `placeholder="Digite seu nome"`

- **`required`**  
  Torna o campo obrigatório antes do envio do formulário.  
  **Exemplo:** `required`

- **`readonly`**  
  Torna o campo apenas leitura; o usuário não pode modificá-lo.  
  **Exemplo:** `readonly`

- **`disabled`**  
  Desabilita o campo; ele não pode ser interagido ou enviado.  
  **Exemplo:** `disabled`

- **`checked`**  
  Indica que um botão de rádio ou checkbox deve ser selecionado por padrão.  
  **Exemplo:** `checked`

- **`min` e `max`**  
  Define os valores mínimo e máximo permitidos para campos numéricos ou de data.  
  **Exemplo:** `min="1" max="10"`

- **`step`**  
  Define o incremento dos valores numéricos ou de data.  
  **Exemplo:** `step="0.1"`

- **`pattern`**  
  Especifica uma expressão regular para validar o campo.  
  **Exemplo:** `pattern="[A-Za-z]+"`

- **`multiple`**  
  Permite seleção de vários valores, como em uploads de arquivos.  
  **Exemplo:** `multiple`

- **`size`**  
  Define a largura (número de caracteres) de um campo de texto.  
  **Exemplo:** `size="20"`

- **`maxlength`**  
  Especifica o número máximo de caracteres que o campo pode ter.  
  **Exemplo:** `maxlength="10"`

- **`autocomplete`**  
  Especifica se o campo permite preenchimento automático, similar ao atributo do `<form>`.  
  **Exemplo:** `autocomplete="off"`

---

## Atributos Específicos de Botões
- **`type`**  
  Define o tipo de botão:
  - `submit`: Envia o formulário.
  - `reset`: Reseta os campos.
  - `button`: Apenas um botão sem ação.  
  **Exemplo:** `type="submit"`

- **`formaction`**  
  Substitui o `action` do formulário para este botão.  
  **Exemplo:** `formaction="https://example.com/submit"`

- **`formmethod`**  
  Substitui o `method` do formulário para este botão.  
  **Exemplo:** `formmethod="POST"`

- **`formtarget`**  
  Substitui o `target` do formulário para este botão.  
  **Exemplo:** `formtarget="_blank"`
