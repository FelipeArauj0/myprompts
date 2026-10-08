# myprompts

Acervo profissional de prompts de **Felipe Araujo**, desenvolvido para guardar, adaptar e evoluir instruções usadas na criação de sites, SaaS, software, propostas comerciais e outras atividades ao longo da carreira.

Cada prompt é mantido em Markdown para facilitar a edição, a reutilização e o acompanhamento de mudanças pelo GitHub.

## Prompts disponíveis

| Área | Prompt | Uso |
| --- | --- | --- |
| Propostas comerciais | [Apresentação de site e proposta em PDF](specs/proposta-comercial-site-pdf.md) | Apresentar um site com capturas desktop e mobile, identidade visual, SEO, mensuração e condições comerciais |

O índice deve ser atualizado sempre que um novo prompt for adicionado.

## Estrutura atual

- `readme.md`: documentação, índice e orientações do repositório.
- `specs/proposta-comercial-site-pdf.md`: primeiro prompt reutilizável.

## Organização sugerida para expansão

As categorias abaixo são uma convenção para arquivos futuros; as pastas devem ser criadas conforme houver conteúdo.

| Caminho sugerido | Conteúdo |
| --- | --- |
| `specs/` | Prompts detalhados e especificações gerais |
| `specs/sites/` | Sites institucionais, landing pages, portfólios e lojas |
| `specs/saas/` | Produtos SaaS, funcionalidades e modelos de operação |
| `specs/software/` | Aplicações, arquitetura, integrações e implementação |
| `specs/propostas/` | Propostas comerciais, escopos e apresentações |
| `specs/documentacao/` | READMEs, guias e documentação de projetos |
| `specs/revisao/` | Revisão de código, conteúdo e qualidade |
| `specs/automacoes/` | Fluxos e tarefas automatizadas |

O primeiro prompt permanece em `specs/proposta-comercial-site-pdf.md`. Caso seja movido para uma subpasta no futuro, atualize os links deste índice.

## Como usar um prompt

1. Escolha o prompt no índice.
2. Abra o arquivo e leia seu objetivo e suas instruções.
3. Edite os campos de briefing para o projeto atual.
4. Anexe os materiais citados, quando necessários.
5. Copie o documento para a ferramenta de IA.
6. Revise o resultado antes de utilizá-lo ou enviar ao cliente.
7. Registre no prompt as melhorias que possam ser reutilizadas.

Valores, paletas, prazos e condições de um exemplo devem ser adaptados a cada projeto.

### Exemplo: proposta de um site

No [prompt de proposta comercial](specs/proposta-comercial-site-pdf.md), personalize:

- Nome, segmento, público e objetivo do cliente.
- Seções e funcionalidades reais do site.
- Capturas de computador e celular.
- Foto do profissional e referência de identidade visual.
- Valor, mensalidade, domínio e hospedagem.
- Serviços incluídos e opcionais.
- Prazo, pagamento, revisões e validade, quando definidos.

O modelo inicial utiliza R$ 700,00, pagamento único e nenhuma mensalidade pelo site. Essas condições são editáveis e não se aplicam automaticamente a todos os projetos.

## Como editar pelo GitHub

1. Abra o arquivo desejado.
2. Clique no ícone de edição.
3. Ajuste o briefing, o escopo ou as instruções.
4. Revise as alterações.
5. Faça um commit com uma mensagem que explique a mudança.

Para usar o prompt, abra a visualização **Raw** e copie seu conteúdo. As instruções de criação do PDF dependem de uma ferramenta com capacidade de gerar arquivos.

## Como trabalhar localmente

```bash
git clone https://github.com/FelipeArauj0/myprompts.git
cd myprompts
```

Edite os arquivos em seu editor preferido. Depois, registre e envie as mudanças:

```bash
git add specs/proposta-comercial-site-pdf.md readme.md
git commit -m "docs: aprimora prompt de proposta comercial"
git push origin main
```

Não há dependências ou etapa de build: o conteúdo do repositório é documental.

## Padrão para novos prompts

Cada novo prompt deve conter:

1. **Título e objetivo:** qual tarefa resolve.
2. **Metadados:** autor, versão e data de atualização.
3. **Briefing editável:** entradas, variáveis e materiais necessários.
4. **Contexto e papel da IA:** qual abordagem deve adotar.
5. **Instruções:** ações claras e ordenadas.
6. **Escopo e limites:** entregas incluídas e itens fora do pedido.
7. **Formato de saída:** PDF, Markdown, código ou outro formato.
8. **Critérios de qualidade:** como revisar e validar o resultado.
9. **Informações ausentes:** quando perguntar e o que não presumir.
10. **Entrega:** como disponibilizar o resultado final.

Use nomes de arquivos em minúsculas, com palavras separadas por hífen, como `landing-page-servicos.md`. Evite nomes genéricos como `prompt-final-2.md`.

Use `[PREENCHER]` para campos obrigatórios e `[OPCIONAL]` para campos que podem ser omitidos. Os marcadores servem para edição e devem ser resolvidos antes da entrega ao cliente.

## Evolução e histórico

- Prefira prompts independentes de um cliente específico.
- Preserve exemplos úteis, identificando-os como referências editáveis.
- Faça commits pequenos e descritivos.
- Atualize a versão e a data quando alterar as instruções.
- Revise o índice ao adicionar, mover ou renomear arquivos.
- Registre no próprio prompt limitações observadas e melhorias de uso.

Sugestão de versões: ajustes de redação em `1.0.1`, ampliação compatível em `1.1.0` e reformulação importante em `2.0.0`.

## Dados e materiais de clientes

Use marcadores no lugar de senhas, tokens, dados pessoais de terceiros e informações confidenciais. Anexe materiais do projeto diretamente no ambiente de trabalho autorizado, sem incluí-los neste acervo por padrão.

Este repositório armazena instruções reutilizáveis. As entregas geradas, como PDFs e projetos de clientes, devem ficar em seus respectivos locais de trabalho.

## Autor

**Felipe Araujo** · Desenvolvedor Web

[GitHub](https://github.com/FelipeArauj0) · [WhatsApp](https://wa.me/5571981062268)
