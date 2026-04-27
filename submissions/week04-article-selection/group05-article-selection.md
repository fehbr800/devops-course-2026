# Estrutura de um Relatório de Revisão Sistemática

Um relatório de revisão sistemática fornece um resumo abrangente dos métodos e dos resultados de uma revisão. Ele segue um formato estruturado para garantir clareza, transparência e reprodutibilidade.

---

## 1. Página de Título

- **Título:** Revisão Sistemática sobre Plataformas de Computação em Nuvem Aplicadas ao DevOps: AWS, Microsoft Azure e Google Cloud Platform.

- **Autores:**  
  Daniel Castilho de Oliveira;  
  Rian Karlos Silva Weber;  
  Ricardo de Almeida Sarruf.

- **Afiliação:** Disciplina DevOps – Tópicos Especiais em Computação IV.

- **Data:** 2026.

- **Contato:** ricardo.sarruf@aluno.ufr.edu.br (será adicionado dos outros dois integrantes)

---

## 2. Resumo (Abstract)

- **Contexto:**  
  A computação em nuvem tem se tornado um elemento essencial para a aplicação da cultura DevOps, pois oferece recursos que favorecem a automação, a integração contínua, a entrega contínua, a escalabilidade e o gerenciamento de aplicações em ambientes modernos. Nesse contexto, plataformas como Amazon Web Services (AWS), Microsoft Azure e Google Cloud Platform (GCP) destacam-se por disponibilizarem ferramentas e serviços voltados ao desenvolvimento, implantação e operação de software.

- **Objetivos:**  
  Esta revisão sistemática tem como objetivo analisar artigos relacionados ao uso de plataformas de computação em nuvem aplicadas ao DevOps, com foco em AWS, Microsoft Azure e Google Cloud Platform, observando aspectos como automação, CI/CD, infraestrutura como código, segurança, escalabilidade, custos, Kubernetes, ambientes multi-cloud e migração para a nuvem.

- **Métodos:**  
  A revisão foi conduzida com base nas diretrizes de Barbara Kitchenham, utilizadas em revisões sistemáticas na área de Engenharia de Software. Todos os artigos foram pesquisados por meio do Google Acadêmico. A seleção dos estudos ocorreu a partir da aplicação de strings de busca específicas, leitura dos títulos, análise dos resumos e verificação da relação dos trabalhos com o tema proposto. Os dados extraídos foram organizados considerando título, autores, ano, fonte de publicação e relação com o tema da pesquisa.

- **Resultados:**  
  Foram selecionados 12 artigos relacionados ao tema. Os estudos abordam práticas DevOps em ambientes de nuvem, comparação entre provedores, uso de CI/CD, infraestrutura como código, automação, Kubernetes, segurança, governança, conformidade, migração de aplicações e desempenho de aplicações containerizadas.

- **Conclusões:**  
  A revisão permitiu observar que as plataformas de computação em nuvem possuem papel relevante na adoção da cultura DevOps, principalmente por oferecerem recursos que facilitam a automação, a escalabilidade, a segurança e a eficiência dos processos de desenvolvimento e operação de software. Além disso, os estudos indicam que a escolha entre AWS, Microsoft Azure e Google Cloud Platform deve considerar critérios técnicos, organizacionais e econômicos.

---

## 3. Introdução

- **Contexto:**  
  Com o avanço da transformação digital, as organizações passaram a buscar formas mais ágeis, seguras e eficientes de desenvolver, implantar e manter aplicações. Nesse cenário, a cultura DevOps surge como uma abordagem voltada à integração entre desenvolvimento e operações, promovendo colaboração, automação de processos, melhoria contínua e entregas mais rápidas.

  A computação em nuvem contribui diretamente para esse cenário, pois oferece infraestrutura flexível, serviços sob demanda e ferramentas que apoiam práticas como integração contínua, entrega contínua, infraestrutura como código, monitoramento, segurança e escalabilidade. Entre as principais plataformas utilizadas no mercado, destacam-se AWS, Microsoft Azure e Google Cloud Platform.

- **Objetivos:**  
  O objetivo desta revisão é analisar como as plataformas AWS, Microsoft Azure e Google Cloud Platform são abordadas na literatura científica no contexto DevOps, identificando suas contribuições para automação, CI/CD, infraestrutura como código, segurança, escalabilidade e adoção organizacional.

  As principais questões de pesquisa consideradas são:

  1. Como as plataformas AWS, Microsoft Azure e Google Cloud Platform contribuem para a aplicação da cultura DevOps nas organizações?
  2. Quais são as principais diferenças entre essas plataformas em relação aos recursos voltados à automação, integração contínua e entrega contínua?
  3. De que forma essas plataformas auxiliam na escalabilidade, segurança, governança e redução de custos em ambientes DevOps?
  4. Quais critérios podem ser considerados na escolha entre AWS, Microsoft Azure e Google Cloud Platform para diferentes contextos organizacionais?

- **Justificativa:**  
  A realização desta revisão é importante porque permite reunir estudos relacionados à aplicação da computação em nuvem no contexto DevOps, contribuindo para uma melhor compreensão sobre o papel das plataformas AWS, Microsoft Azure e Google Cloud Platform. Além disso, a análise dos artigos selecionados pode auxiliar na identificação de critérios relevantes para adoção dessas ferramentas em diferentes ambientes organizacionais.

---

## 4. Métodos

- **Protocolo e Registro:**  
  A revisão foi conduzida com base no método de revisão sistemática proposto por Barbara Kitchenham, referência na área de Engenharia de Software. O protocolo da revisão foi definido internamente pelo grupo, contemplando o tema, as questões de pesquisa, as strings de busca, os critérios de elegibilidade, o processo de seleção dos estudos e a forma de extração dos dados.

  Esta revisão não foi registrada em plataformas externas, como PROSPERO, por se tratar de uma atividade acadêmica da disciplina DevOps – Tópicos Especiais em Computação IV.

- **Critérios de Elegibilidade:**  
  Para a definição dos critérios de elegibilidade, foi utilizada uma adaptação do modelo PICOS:

  - **População:**  
    Estudos relacionados a organizações, equipes de desenvolvimento de software, ambientes de computação em nuvem, práticas DevOps e aplicações em cloud.

  - **Intervenção:**  
    Uso de plataformas de computação em nuvem, especialmente AWS, Microsoft Azure e Google Cloud Platform, além de práticas como automação, CI/CD, infraestrutura como código, Kubernetes, containers e ambientes multi-cloud.

  - **Comparação:**  
    Comparação entre provedores de nuvem, ferramentas de automação, modelos de implantação, ambientes cloud-native, máquinas virtuais, aplicações containerizadas e estratégias de migração para a nuvem.

  - **Resultados (Outcomes):**  
    Foram considerados estudos que abordassem resultados relacionados à automação, integração contínua, entrega contínua, escalabilidade, segurança, governança, conformidade, redução de custos, desempenho e melhoria dos processos de desenvolvimento e operação de software.

  - **Tipo de estudo:**  
    Foram considerados artigos científicos, revisões, estudos comparativos, publicações acadêmicas, teses e trabalhos técnicos relacionados ao tema.

- **Fontes de Informação:**  
  Todos os artigos utilizados nesta revisão foram pesquisados por meio do Google Acadêmico. A escolha dessa fonte ocorreu em razão de sua ampla cobertura de publicações científicas, artigos acadêmicos, teses, dissertações e estudos técnicos relacionados à área de computação em nuvem e DevOps.

- **Estratégia de Busca:**  
  As buscas foram realizadas com strings em inglês, considerando que a maior parte dos estudos científicos sobre DevOps, cloud computing, AWS, Microsoft Azure e Google Cloud Platform é publicada nesse idioma.

  As strings utilizadas foram:

  | Nº | String de Busca |
  | -- | --------------- |
  | 1 | ("comparative study" AND "DevOps" AND "cloud computing") AND ("Amazon Web Services" AND "Microsoft Azure" AND "Google Cloud Platform") AND ("CI/CD pipeline") |
  | 2 | ("DevOps" AND "CI/CD pipeline" AND "cloud computing") AND ("AWS CodePipeline" AND "Azure DevOps" AND "Google Cloud Build") |
  | 3 | ("infrastructure as code" AND "DevOps" AND "cloud platforms") AND ("AWS CloudFormation" AND "Azure Resource Manager" AND "Google Cloud Deployment Manager") |
  | 4 | ("DevOps automation" AND "cloud computing platforms") AND ("Amazon Web Services" AND "Microsoft Azure" AND "Google Cloud Platform") AND ("security" AND "scalability" AND "cost") |

- **Seleção dos Estudos:**  
  A seleção dos estudos foi realizada em etapas. Inicialmente, foram aplicadas as strings de busca no Google Acadêmico. Em seguida, foi realizada a leitura dos títulos dos trabalhos encontrados, com o objetivo de identificar aqueles que possuíam relação com o tema da revisão.

  Após essa etapa, foram analisados os resumos dos artigos mais relevantes, verificando se tratavam de computação em nuvem, DevOps, automação, CI/CD, infraestrutura como código, segurança, escalabilidade, custos, Kubernetes, migração para a nuvem ou comparação entre plataformas.

  Por fim, foram aplicados critérios de inclusão e exclusão, priorizando estudos com maior aderência ao tema proposto. Ao final do processo, foram selecionados 12 artigos para compor a revisão sistemática.

- **Extração de Dados:**  
  Os dados foram coletados e organizados a partir das informações principais dos artigos selecionados. Foram extraídos os seguintes elementos:

  - Título do artigo;
  - Nome dos autores;
  - Ano de publicação;
  - Fonte de publicação;
  - Tema central do estudo;
  - Relação com DevOps;
  - Relação com computação em nuvem;
  - Tecnologias ou plataformas abordadas;
  - Contribuição do artigo para a revisão.

  Após a extração, os dados foram organizados em tabela, permitindo melhor visualização dos artigos selecionados e facilitando a comparação entre os estudos.
