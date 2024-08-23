# Documentação do Software

## Índice 
1. [Introdução](#introdução)
2. [Visão Geral do Sistema](#visão-geral-do-sistema)
3. [Requisitos Funcionais](#requisitos-funcionais)
4. [Requisitos Não Funcionais](#requisitos-não-funcionais)
5. [Casos de Uso](#casos-de-uso)
6. [Diagrama de Arquitetura](#diagrama-de-arquitetura)
7. [Conclusão](#conclusão)

## Introdução
Esta documentação descreve o software MentorIa, suas funcionalidades, requisitos e arquitetura. O objetivo é fornecer uma visão clara e abrangente do sistema para desenvolvedores, gestores e partes interessadas.

## Visão Geral do Sistema
O MentorIA utilizara dos recursos de informações dos usuarios para criar um plano de carreira utilizando, as vontades que incluem locais de trabalho e cargos do mentoriado para que ele tenha uma boa colocação no mercado de trabalho

## Requisitos Funcionais
Os requisitos funcionais descrevem as funcionalidades que o sistema deve oferecer. Abaixo estão listados os requisitos funcionais identificados:

1. **RF001**: Entrega de um plano de ação
2. **RF002**: Demonstração de outras pessoas que tem o cargo desejado
3. **RF003**: Cursos proprios da plataforma, com profissionais da area requisitada
4. **RF004**: Sistema de recrutamento com empresas parceiras

## Requisitos Não Funcionais
Os requisitos não funcionais definem as qualidades e restrições do sistema. Abaixo estão listados os requisitos não funcionais identificados:

1. **RNF001**: O sistema não terá uma navegação simples
2. **RNF002**: Será compativel com todas as plataformas como IOS, Windows ou Smartphone
3. **RNF003**: os usuarios precisarão adicionar todos os documentos antes de se candidatar a uma vaga.


## Casos de Uso
O sistema vai ser principalmente utilizado para poder gerenciar carreiras de pessoas que não sabem com oque querem trabalhar ou sabem mas não sabem oque estudar para chegar a essa meta, vai ser necessario que o usuario tenha ciencia das suas habilidade e que informe seus desejos, como linguas e materias que tem o interesse em desenvolver
### Caso de Uso 1: Busca de cursos
- **Ator Principal**: Luan
- **Pré-condições**: ter cursos dentro da ferramenta
- **Fluxo Principal**:
  1. Arrumar profissionais que tenham o interesse de abastecer a ferramenta
  2. criar variedades de cursos para todas as areas
  3. ter incentivo para os usuarios tambem compartilhar cursos dentro da ferramenta
- **Fluxo Alternativo**:
  - Parceria com uma empresa que forneça os cursos

## Diagrama de Arquiteturagraph TD
A[Usuário] --> B(Cadastro)
B --> C{Perfil}
C --> D[Atualizar]
C --> E[Avaliar]

F[Gestor] --> G(Vagas)
G --> H[Cadastrar]
G --> I[Candidatar]

J[Ferramenta AI] --> K{Avaliação}
K --> L[Perfil x Vagas]
K --> M[Plano Desenvolvimento]

N[RH] --> O{Relatórios}
O --> P[Movimentação]
O --> Q[Desenvolvimento]

R[Treinamentos] --> S[Plano Desenvolvimento]

## Conclusão
Esta documentação fornece uma visão geral dos requisitos e funcionalidades do software MentorIA. Para mais informações ou esclarecimentos, entre em contato com a equipe de desenvolvimento.