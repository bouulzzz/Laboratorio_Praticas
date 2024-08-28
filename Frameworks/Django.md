## O que é Django?
O Django é um framework de código aberto que segue o padrão de arquitetura MVT (Model-View-Template).
É conhecido por seu enfoque em promover a produtividade e a simplicidade no desenvolvimento de aplicações web. 
Ele vem com uma série de componentes prontos para uso, o que acelera o processo de desenvolvimento.

## Para que serve?
1. Desenvolvimento Rápido de Aplicações Web: Facilita a criação de aplicações web com uma estrutura pronta e ferramentas integradas.
2. Gestão de Conteúdo: Permite a construção de sistemas de gerenciamento de conteúdo com um painel administrativo intuitivo.
3. Desenvolvimento de APIs: Facilita a criação de APIs para integrar e interagir com outras aplicações.
4. Segurança: Oferece proteções integradas contra vulnerabilidades comuns em aplicações web.
5. Escalabilidade e Manutenção: Suporta o crescimento e a manutenção de projetos pequenos e grandes.
6. Desenvolvimento de Sites Dinâmicos: Ideal para criar sites interativos que lidam com dados dinâmicos e interatividade.

## Como funciona o MVT do Django?
O padrão MVT no Django ajuda a separar a lógica de apresentação (Views e Templates) da lógica de dados (Modelos). Isso permite um desenvolvimento mais organizado e modular, facilitando a manutenção e escalabilidade do seu aplicativo web.
#### Componentes:
> Model
- Função: Representa a estrutura dos dados e a lógica de negócios. Define a forma como os dados são armazenados e manipulados no banco de dados.
- Como funciona: Você define modelos como classes Python, que são mapeadas para tabelas no banco de dados. Cada modelo corresponde a uma tabela, e cada atributo da classe corresponde a uma coluna na tabela.

> View
- Função: Controla a lógica de apresentação. Recebe solicitações HTTP, interage com o modelo para obter dados e seleciona um template para gerar a resposta HTTP.
- Como funciona: As views são funções ou classes que recebem solicitações, processam dados (usando modelos se necessário) e retornam uma resposta. No Django, as views podem ser baseadas em funções ou em classes.

> Template
- Função: Define a apresentação dos dados. Os templates são arquivos HTML que podem incluir placeholders para dados dinâmicos.
- Como funciona: Templates são arquivos que definem a estrutura HTML da resposta. Eles são preenchidos com dados fornecidos pela view para gerar a página final que será enviada ao navegador.
