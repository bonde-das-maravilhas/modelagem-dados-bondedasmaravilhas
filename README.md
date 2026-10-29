# Das telas ás entidades

A partir das telas desenvolvidas no Figma para o KeepiMov , identifiquei os dados que o sistema precisa salvar no banco de dados:

# tela de Autenticação (Login e Cadastro)

#exemplo de table não formalizada
  <img width="958" height="240" alt="tabela Não normalizda" src="./assets/image/table-not-formalize.png" />
  essa tabela não formalizada usada como exemplo com dados que usaremos no nosso site(talvez haja alterações)
  aplicando a normalização da tabela como requerido
  <img width="592" height="285" alt="tabela 1FN" src="./assets/image/1FN.png" />
  aplicando a 1FN a gente deixa todos os dados de maneira atomica com um unico dado dentro de cada seção
  <img width="692" height="563" alt="tabela Não normalizda" src="./assets/image/2FN.png" />
  Aqui aplicando a 2FN tirando e separando as tabelas unicas (que só se pode ter 1 como só 1 telefone e 1 email ) e normalizando as informações mantendo as primarias não juntando com as primarias
  e fazendo os dados da tabela se separar ja que email e telefone são dois jeitos de puxar a tabela pessoa porém só precisamos do email pra puxar a tabela pessoa então não precisamos da informação do telefone naquela tabela
  assim separando as tabelas para evitar esse acumulo de linhas em uma tabela que pode ser repartida e mantendo as informações essenciais dentro da tabela requerida
  <img width="560" height="592" alt="tabela Não normalizda" src="./assets/image/3FN.png" />
  ultima formalização da tabela fazendo os atributos comuns não dependerem de atributos comuns e se relacionarem diretamente da chave da tabela e somente com ela

  #tabela toda na ordem dos passos
  <img width="1032" height="1009" alt="tabela Não normalizda" src="./assets/image/all-table.png" />

  Integrante: @tthomaslamounier
Anthropic. Claude (modelo utilizado). Ferramenta de inteligência artificial generativa.
Data de uso: 24 out. 2026.
Finalidade: Esclarecimento do que se fazer no exercício dado.
Arquivos impactados: README.md (seção Normalização)
