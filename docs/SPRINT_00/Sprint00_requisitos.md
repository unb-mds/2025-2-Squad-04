# Estudos sobre Requisitos

Requisitos são funções, objetivos, prioridades e restrições que o sistema deve possuir para satisfazer contratos, padrões ou especificações de acordo com o(s) usuário(s).  
Eles representam aquilo que o sistema deve fazer e também como deve se comportar, servindo como base para todo o desenvolvimento do software.

---

## Tipos de Requisitos

### Requisitos Funcionais
São aqueles que descrevem o que o sistema deve realizar: suas funções, operações e informações processadas.

**Exemplos de requisitos funcionais:**
- [RF001] O sistema deve cadastrar médicos profissionais (entrada).  
- [RF002] O sistema deve emitir um relatório de clientes (saída).  
- [RF003] O sistema deve passar um cliente da situação “em consulta” para “consultado” quando o atendimento terminar (mudança de estado).  
- [RF004] O cliente pode consultar seus dados no sistema.  

---

### Requisitos Não Funcionais
São critérios que qualificam os requisitos funcionais, geralmente relacionados a desempenho, qualidade ou restrições externas.  
Diferente dos funcionais, eles não dizem o que o sistema faz, mas sim como ele deve ser.

#### Propriedades e Métricas Comuns
| Propriedade       | Métrica                                                                 |
|-------------------|-------------------------------------------------------------------------|
| Velocidade        | Transações por segundo, tempo de resposta, tempo de atualização de tela |
| Tamanho           | KB de armazenamento, número de chips de RAM                             |
| Facilidade de uso | Tempo de treinamento, quantidade de telas de ajuda                      |
| Confiabilidade    | Tempo médio entre falhas, taxa de indisponibilidade, disponibilidade    |
| Robustez          | Tempo de reinício após falha, probabilidade de corromper dados          |
| Portabilidade     | Número de sistemas-alvo, percentual de código dependente de plataforma  |

#### Classificação dos Requisitos Não Funcionais
- **Requisitos do produto final**: descrevem como o produto deve se comportar.  
- **Requisitos organizacionais**: relacionados a políticas ou processos internos da empresa.  
- **Requisitos externos**: ligados a legislações ou normas que devem ser seguidas.  

**Exemplos de requisitos não funcionais:**
- [RNF001] O sistema deve imprimir o relatório em até 5 segundos.  
- [RNF002] Todos os relatórios devem seguir o padrão especificado pelo setor XYZ.  
- [RNF003] O sistema deve ser implementado em Java.  

---

## Considerações Finais
- Os requisitos devem ser considerados durante todo o projeto, não apenas no início.  
- Eles precisam ser claros, testáveis e validados junto aos usuários.  
- Requisitos mal definidos podem levar a atrasos, aumento de custos ou falhas no sistema.  
- A engenharia de requisitos envolve atividades de levantamento, análise, documentação e validação para garantir que o sistema final atenda às necessidades reais.  

---

# Levantamento de Requisitos

- **Compreensão do domínio**: Os analistas devem desenvolver sua compreensão do domínio da aplicação.  
- **Coleta de requisitos**: Interagir com os stakeholders do sistema para descobrir seus requisitos.  
- **Classificação**: Organizar os requisitos em grupos coerentes.  
- **Resolução de conflitos**: Resolver divergências entre múltiplos stakeholders.  
- **Definição das prioridades**: Identificar os requisitos mais importantes em conjunto com os stakeholders.  
- **Verificação de requisitos**: Conferir se os requisitos estão completos, consistentes e de acordo com o esperado.  

### Técnicas de Levantamento de Requisitos
- Levantamento orientado a pontos de vista  
- Etnografia  
- Workshops  
- Prototipagem  

---

# Exemplos de Requisitos de um Sistema Fictício

**Sistema escolhido: Biblioteca Online**

### Requisitos Funcionais (RF)
- [RF001] O sistema deve permitir o cadastro de novos usuários.  
- [RF002] O sistema deve permitir que o usuário pesquise livros por título, autor ou assunto.  
- [RF003] O sistema deve registrar o empréstimo de um livro para um usuário.  
- [RF004] O sistema deve notificar o usuário por e-mail quando o prazo de devolução estiver próximo.  

### Requisitos Não Funcionais (RNF)
- [RNF001] O sistema deve processar pesquisas em até 3 segundos.  
- [RNF002] O sistema deve estar disponível 24 horas por dia, 7 dias por semana.  
- [RNF003] O sistema deve armazenar os dados em conformidade com a Lei Geral de Proteção de Dados (LGPD).  
