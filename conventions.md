# Convenções do Marketing OS

Este documento define os padrões oficiais de organização, nomenclatura, documentação e qualidade utilizados em todo o Marketing OS.

Todos os agentes devem seguir estas convenções para garantir consistência, organização e facilidade de manutenção dos projetos.

---

# Padrões de Documentação

Todos os documentos devem:

- Ser escritos em Markdown compatível com GitHub.
- Iniciar com um título claro utilizando `#`.
- Apresentar um objetivo logo no início do documento.
- Utilizar títulos e subtítulos organizados por níveis (`#`, `##`, `###`).
- Escrever de forma clara, objetiva e profissional.
- Evitar repetições entre documentos.
- Referenciar outros documentos sempre que possível, em vez de duplicar conteúdo.
- Evitar textos genéricos ou placeholders.
- Documentar premissas, limitações e pendências quando existirem.
- Ser compreensíveis por qualquer membro da equipe.

---

# Idioma

Toda a documentação do Marketing OS deve ser escrita em **Português (Brasil)**.

Exceções:

- Nomes de pastas.
- Nomes de arquivos.
- Convenções técnicas.
- Comandos.
- Código.
- APIs.
- Ferramentas.

Esses elementos devem permanecer em inglês quando fizerem parte do padrão internacional de desenvolvimento.

---

# Convenções de Nomes de Arquivos

Utilizar nomes descritivos, em letras minúsculas, separados por hífen.

Exemplos:

```text
plano-de-marketing.md
analise-concorrentes.md
estrategia-posicionamento.md
campanha-lancamento.md
```

Quando necessário, incluir a data para facilitar o histórico:

```text
2026-07-10-plano-de-lancamento.md
2026-07-10-relatorio-campanha.md
```

Evitar nomes como:

```text
novo.md
teste.md
final.md
final-final.md
arquivo.md
documento.md
```

---

# Convenções de Pastas

As pastas devem representar áreas permanentes do sistema.

Utilizar nomes curtos, claros e em inglês, seguindo o padrão do projeto.

Exemplo:

```text
agents/
briefs/
knowledge/
output/
templates/
playbooks/
projects/
```

Evitar criar novas pastas na raiz sem necessidade arquitetural.

---

# Estrutura dos Documentos

Sempre que possível utilizar esta sequência:

1. Objetivo
2. Contexto
3. Desenvolvimento
4. Recomendações
5. Próximos Passos

Documentos longos devem possuir títulos claros para facilitar a navegação.

---

# Formatação Markdown

Utilizar:

- `#` para título principal.
- `##` para seções.
- `###` para subseções.
- Listas para organizar informações.
- Tabelas para comparações.
- Checklists para validação.
- Blocos de código apenas para exemplos técnicos.

Evitar:

- Blocos muito longos.
- Títulos genéricos.
- Texto sem divisão em seções.

---

# Padrão das Entregas

Todo material produzido deve conter, quando aplicável:

- Objetivo.
- Cliente.
- Projeto.
- Público-alvo.
- Contexto.
- Premissas.
- Desenvolvimento.
- Recomendações.
- Próximas ações.

---

# Nomenclatura das Entregas

Utilizar preferencialmente o seguinte padrão:

```text
AAAA-MM-DD-cliente-projeto-entrega-status.md
```

Exemplo:

```text
2026-07-10-qualicoco-plano-lancamento-draft.md

2026-07-10-guimaraes-campanha-pascoa-review.md

2026-07-10-rozcato-plano-marketing-final.md
```

---

# Status dos Arquivos

Sempre utilizar um dos seguintes status:

| Status | Significado |
|---------|-------------|
| draft | Documento em desenvolvimento |
| review | Em revisão |
| approved | Aprovado internamente |
| final | Pronto para entrega |
| archived | Arquivado |

---

# Padrão de Qualidade

Todo documento deve:

- Estar alinhado ao briefing.
- Possuir objetivo claro.
- Ser específico para o cliente.
- Considerar o mercado e o público.
- Ser baseado em informações verificáveis.
- Informar premissas quando necessário.
- Estar organizado na pasta correta.
- Estar pronto para revisão antes de ser considerado final.

---

# Organização do Conhecimento

Informações permanentes devem ser armazenadas em:

```text
knowledge/
```

Exemplos:

- clientes
- concorrentes
- mercados
- personas
- playbooks
- tendências
- regulamentações

Entregas específicas de projetos devem permanecer em:

```text
output/
```

Sempre que um projeto gerar conhecimento reutilizável, atualizar a base de conhecimento correspondente.

---

# Convenções para Briefings

Todo briefing deve conter:

- Cliente.
- Projeto.
- Objetivo.
- Público.
- Produtos.
- Mercado.
- Concorrentes.
- Prazo.
- Entregas esperadas.
- Restrições.
- Critérios de sucesso.

Nenhum agente deve assumir informações não documentadas.

---

# Convenções para Apresentações

Toda apresentação deve:

- Possuir narrativa clara.
- Informar objetivo.
- Possuir sequência lógica.
- Utilizar títulos orientados à conclusão.
- Informar fontes quando utilizar dados.
- Ser compatível com PowerPoint, Google Apresentações ou Apple Keynote quando solicitado.

---

# Convenções para Campanhas

Toda campanha deve documentar:

- Objetivo.
- Público.
- Posicionamento.
- Conceito.
- Mensagens principais.
- Canais.
- Cronograma.
- KPIs.
- Próximos passos.

---

# Convenções para Embalagens

Projetos de embalagem devem informar:

- Categoria.
- Linha.
- SKU.
- Arquitetura.
- Hierarquia das informações.
- Benefícios.
- Claims aprovados.
- Restrições regulatórias.
- Recomendações para design.

---

# Convenções para Trade Marketing

Todo plano de Trade deve documentar:

- Objetivo.
- Canal.
- Sell-in.
- Sell-out.
- Materiais de PDV.
- Cronograma.
- Responsáveis.
- Indicadores.
- Riscos.

---

# Convenções para Analytics

Toda análise deve informar:

- Fonte dos dados.
- Período analisado.
- KPIs.
- Premissas.
- Limitações.
- Recomendações.

Nunca apresentar dados sem contexto.

---

# Controle de Versões

Sempre que um documento sofrer alterações relevantes:

- Atualizar a data.
- Registrar a revisão quando necessário.
- Manter apenas uma versão oficial como `final`.

Evitar múltiplos arquivos com pequenas variações do mesmo documento.

---

# Filosofia do Marketing OS

O Marketing OS foi desenvolvido para funcionar como uma equipe especializada de marketing.

Todos os documentos devem ser produzidos de forma organizada, reutilizável e orientada à colaboração entre especialistas.

O objetivo é criar uma base de conhecimento que evolua continuamente, reduzindo retrabalho e aumentando a qualidade das entregas.

Cada documento produzido deve agregar valor ao projeto atual e, sempre que possível, enriquecer o conhecimento da agência para projetos futuros.