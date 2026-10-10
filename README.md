# Boas-vindas da Pós

Ferramenta do time de CS para enviar a mensagem de onboarding aos alunos novos das pós-graduações.

**Acesse o site:** https://institutonta.github.io/boas-vindas-pos/

## Pendências e métricas

O acompanhamento de cada aluno (checklist de onboarding de cada curso) e as métricas do time ficam no painel do Claude:

**Painel:** https://claude.ai/artifact/RgutxohXmkHwQiF7Vo1hYS

- Envie a mensagem pelo menu **Enviar mensagens** do painel: o aluno entra sozinho em **Pendências**, com nome e telefone.
- Marque as etapas conforme o aluno conclui. O botão **Arquivar** só libera quando todas estiverem feitas.
- O menu **Painel** mostra formulários enviados, contratos e formulários pendentes, alunos nas comunidades de alunos e de inglês, workshops liberados e alunos parados há 3 dias ou mais, com gráficos e percentuais.
- Para acessar, peça ao Otacílio para compartilhar o painel com você como **Colaborador**.

Os envios feitos por este site do GitHub não entram em Pendências automaticamente.

### Checklist de onboarding por curso

| Etapa | Engenharia | Defesa Cibernética | Arquitetura | IA Negócios | MBA Direito |
|---|:-:|:-:|:-:|:-:|:-:|
| Aceitar contrato | ✓ | ✓ | ✓ | ✓ | ✓ |
| Preencher os formulários | ✓ | ✓ | ✓ | ✓ | ✓ |
| Entrar na comunidade de alunos | ✓ | ✓ | ✓ | ✓ | ✓ |
| Entrar na comunidade de inglês | ✓ | — | ✓ | — | — |
| Acessar a plataforma (AVA/Cosmos) | ✓ | ✓ | ✓ | ✓ | ✓ |
| Subir a documentação | ✓ | ✓ | ✓ | ✓ | ✓ |
| Liberar workshop | ✓ | — | — | ✓ | ✓ |

## Cursos disponíveis

| Curso | Libera workshops? |
|---|---|
| Engenharia de Dados e Inteligência Artificial | Sim |
| Defesa Cibernética com IA Generativa Aplicada | Não |
| Arquitetura Avançada de Cloud com Azure | Não |
| Inteligência Artificial Aplicada a Negócios | Sim |
| MBA em Inteligência Artificial Aplicada ao Direito | Sim |

## Como usar

1. Escolha o curso do aluno no topo da página.
2. Digite o nome do aluno.
3. Confira a saudação. Ela muda sozinha conforme o horário (Bom dia, Boa tarde, Boa noite), mas pode ser escolhida manualmente.
4. Clique em **Copiar mensagem** e cole no WhatsApp, ou preencha o telefone e clique em **Abrir no WhatsApp**.

Cada um dos 4 passos tem um botão **Copiar** para enviar só aquele link, quando o aluno pedir.

## Como atualizar um link ou mensagem

Todo o conteúdo fica no arquivo `index.html`, na lista `COURSES`. Para trocar um link de turma:

1. Abra `index.html` aqui no GitHub e clique no lápis (Editar).
2. Procure o link antigo (Ctrl + F) e troque pelo novo. Ele aparece duas vezes por curso: na lista `links` e no texto da mensagem.
3. Clique em **Commit changes** (ou **Confirmar alterações**, se o GitHub estiver em português). O site atualiza em 1 a 2 minutos.
