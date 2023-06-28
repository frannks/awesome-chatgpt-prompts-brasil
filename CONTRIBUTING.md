# Diretrizes de Contribuição

Antes de contribuir para este repositório, certifique-se de seguir as seguintes diretrizes gerais. Além disso, se você estiver enviando um novo prompt para o repositório, certifique-se de seguir também as diretrizes específicas do prompt. Essas verificações garantirão que suas contribuições possam ser facilmente integradas ao repositório principal, sem dor de cabeça para os proprietários.

## Diretrizes Gerais

As seguintes diretrizes devem ser seguidas ao fazer qualquer contribuição de código aberto:

- [ ] As contribuições devem ser feitas por meio de uma solicitação pull para o repositório principal de um fork pessoal.
- [ ] As contribuições devem ser FEITAS EM PORTUGUÊS BRASIL.
- [ ] As solicitações pull devem ser acompanhadas por um título descritivo e uma explicação detalhada.
- [ ] Envie todas as solicitações pull para a branch principal do repositório.
- [ ] Antes de enviar uma solicitação pull, certifique-se de que as adições/edições estejam alinhadas com a organização geral do repo.
- [ ] Certifique-se de que as alterações sejam compatíveis com a licença do repositório.
- [ ] Em caso de conflito, forneça explicações úteis sobre as alterações propostas para que possam ser aprovadas pelos proprietários de repositórios.

## Novas diretrizes de solicitação
Para adicionar um novo prompt a este repositório, um colaborador deve seguir os seguintes passos (em seu fork pessoal):
1. Crie e teste o novo prompt.
    - See the [README](https://github.com/frannks/awesome-chatgpt-prompts-brasil/blob/main/README.md) para obter orientação sobre como escrever prompts eficazes.
    - Certifique-se de que os prompts gerem os resultados pretendidos e possam ser usados ​​por outros usuários para replicate those results.
2. Adicione o prompt a `README.md` usando o seguinte modelo de remarcação:

    `## Título do Prompt`

    `Contribuído por: [@github_username](https://github.com/github_profile)`

    `> conteúdo do prompt`

    - <b>Observação:</b> Se seu prompt foi gerado pelo ChatGPT, anexe `<mark>Gerado pelo ChatGPT</mark>` à linha "Contribuído por".
3. Adicione o prompt a `prompts.csv`.
    - Coloque o título do prompt na coluna `act` e o próprio prompt na coluna `prompt`.
4. Envie uma solicitação pull na branch principal do repositório.
    - Se possível, forneça alguma documentação de como você testou seu prompt e os tipos de resultados que você recebeu.
    - Certifique-se de incluir um título e uma descrição detalhados.

### Nova lista de verificação de solicitação:
- [ ] Eu confirmei que o prompt funciona bem
- [ ] Eu adicionei `Contribuído por: [@yourusername](https://github.com/yourusername)`
- [ ] Eu adicionei ao README.md
- [ ] Eu adicionei ao `prompts.csv`
  - [ ] Aspas escapadas por aspas duplas
  - [ ] Sem espaços após vírgulas após aspas duplas. por exemplo. `"atua","prompt"` não `"atua", "prompt"`
  - [ ] Removido "Agir como" do título no CSV

Certifique-se de que esses requisitos sejam atendidos antes de enviar uma solicitação pull.
