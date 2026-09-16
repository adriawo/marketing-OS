# Regras de Operação dos Agentes

Este documento estabelece as regras gerais de funcionamento para todos os agentes de Inteligência Artificial do Marketing OS.

Seu objetivo é garantir que todos os agentes atuem de forma consistente, organizada e alinhada aos padrões da agência.

Os agentes especializados devem seguir estas diretrizes antes de executar qualquer atividade.

---

# Regras Gerais

Todos os agentes devem:

- Seguir o fluxo de trabalho definido em `workflow.md`.
- Respeitar os padrões de nomenclatura, formatação e qualidade definidos em `conventions.md`.
- Utilizar a pasta `knowledge/` como fonte principal de conhecimento reutilizável.
- Salvar todas as entregas na pasta `output/`.
- Nunca considerar uma entrega como definitiva sem revisão humana.
- Nunca inventar informações sobre clientes, mercado, orçamento, concorrentes ou resultados.
- Registrar claramente todas as premissas quando o briefing estiver incompleto.
- Produzir conteúdos específicos para cada cliente, mercado, público-alvo e objetivo do projeto.
- Evitar duplicação de informações já documentadas em outros arquivos do repositório.

---

# Princípios para Desenvolvimento dos Agentes

Cada agente deve possuir uma única especialidade bem definida.

Todo agente deve possuir:

- Objetivo claramente definido.
- Responsabilidades específicas.
- Entradas (Inputs).
- Saídas (Outputs).
- Ferramentas autorizadas.
- Limites de acesso às informações.
- Critérios para solicitar apoio de outro agente.
- Processo de revisão.
- Registro de atividades (Logs).

Os agentes devem atuar como especialistas, nunca como agentes genéricos.

---

# Especializações Recomendadas

Os agentes devem representar competências permanentes da agência, e não tarefas temporárias.

As especializações recomendadas são:

- Diretor de Campanhas
- Inteligência de Mercado
- Planejamento Estratégico
- Branding
- Marketing Digital
- Trade Marketing
- Desenvolvimento de Embalagens
- Copywriting
- Social Media
- Marketing Analytics
- Desenvolvimento de Apresentações
- Gestão de Projetos

---

# Comunicação entre Agentes

Sempre que um agente transferir uma tarefa para outro, deverá fornecer:

- Briefing original.
- Objetivo atual.
- Contexto necessário.
- Referências consultadas.
- Trabalhos já concluídos.
- Premissas adotadas.
- Riscos identificados.
- Dúvidas pendentes.
- Formato esperado da entrega.

Nenhum agente deve assumir informações que não estejam documentadas.

---

# Registro de Atividades

Sempre que uma atividade impactar uma entrega do projeto, ela deverá ser registrada em:

`output/logs/`

O registro deve conter, no mínimo:

- Data e hora.
- Cliente.
- Projeto.
- Agente responsável.
- Ação executada.
- Arquivos utilizados como entrada.
- Local onde a entrega foi salva.
- Pendências ou pontos que necessitam revisão.

---

# Restrições

Os agentes não devem:

- Armazenar conhecimento permanente apenas dentro das entregas finais.
- Criar novas pastas na raiz do projeto sem justificativa arquitetural.
- Considerar conteúdos gerados automaticamente como aprovados.
- Misturar informações de clientes ou projetos diferentes.
- Utilizar nomes de arquivos genéricos, como:
  - final.md
  - final-final.md
  - novo.md
  - notas.md
  - teste.md
- Utilizar prompts como substitutos de arquitetura, processos ou documentação.

---

# Filosofia do Marketing OS

O Marketing OS foi desenvolvido para funcionar como um sistema operacional de marketing composto por especialistas.

Cada agente possui uma responsabilidade específica e trabalha em colaboração com os demais, compartilhando conhecimento, seguindo processos padronizados e produzindo entregas consistentes.

O objetivo não é substituir o pensamento estratégico humano, mas ampliar a produtividade, a qualidade e a capacidade de execução da equipe de marketing.

Toda decisão estratégica, aprovação final e publicação de materiais permanece sob responsabilidade da equipe humana.