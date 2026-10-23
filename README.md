# Das telas ás entidades

_(Victor Alves)_

A partir das telas desenvolvidas no Figma para o KeepiMov , identifiquei os dados que o sistema precisa salvar no banco de dados:

# tela de Autenticação (Login e Cadastro)

![Tela de Autenticação](docs/telas/login.png)

ao analisar a tela de entrada do KeepiMov, identificamos a necessidades de criar a tabela de usuarios para autenticação no aplicativo.

- Entidade gerada: `usuario`
  -campos identificados no figma: -`id` Codigo identificador do usuario -`nome-completo`: Nome digitado no cadastro -`email`:E-mail usado para login -`senha_hash`: Senha cadastrada pelo usuario -`data_criacao`: Data de registrono aplicativo

  ***

# Tela de perfil e configurações

![Tela de perfil](docs/telas/perfil.png)

Nesta tela, o usuario gerencia suas informações pessoais e preferencias de uso do aplicativo

- Entidade geradas `perfil` e `preferencia`
- Campos identificados do figma:
- Na tabela `perfil`: `foto_url`, `biografia`, `cidade_residencia`
- Na tabela `preferencia`: `notificacoes_linhas_ativas`, `tema_escuro`

---

# Tela principal (Home / Status das linhas)

![tela principal](docs/telas/home.png)

tela principal do KeepiMov, o usuario acompanha a situação das linhas de metro e pode registrar alertas de incidentes

-Entidades geradas: `linha` e `alerta`
-campo identificados no figma:

- Na tabela `linha`: `nome_linha`, `status_operacao` (ex: Normal, Velocidade Reduzida)
- Na Tabela `alerta`: `tipo_incidente`, `descricao`, `horario_registro`
