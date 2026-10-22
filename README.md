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

Este site do GitHub não envia mensagens: o botão **Enviar pelo painel** leva direto para o painel.

### Checklist de onboarding por curso

| Etapa | Engenharia | Defesa Cibernética | Arquitetura | IA Negócios | MBA Direito |
|---|:-:|:-:|:-:|:-:|:-:|
| Aceitar contrato | ✓ | ✓ | ✓ | ✓ | ✓ |
| Preencher os formulários | ✓ | ✓ | ✓ | ✓ | ✓ |
| Entrar na comunidade de alunos | ✓ | ✓ | ✓ | ✓ | ✓ |
| Entrar na comunidade de inglês | ✓ | — | — | — | — |
| Acessar a plataforma (AVA/Cosmos) | ✓ | ✓ | ✓ | ✓ | ✓ |
| Subir a documentação | ✓ | ✓ | ✓ | ✓ | ✓ |
| Liberar workshop | — | — | — | — | ✓ |

### Sequência de mensagens (todos os cursos)

1. **Boas-vindas:** formulário de inscrição, comunidade de alunos (e de inglês em Engenharia), acesso à plataforma. No MBA, inclui também o tutorial de navegação.
2. **Pedido de retorno:** enviada logo depois da 1.
3. **Liberação de acesso:** enviada quando o aluno avisa que finalizou. Só no MBA ela libera os Workshops.
4. **Documentação:** enviada na sequência da 3.

## Cursos disponíveis

| Curso | Libera workshops? |
|---|---|
| Engenharia de Dados e Inteligência Artificial | Não |
| Defesa Cibernética com IA Generativa Aplicada | Não |
| Arquitetura Avançada de Cloud com Azure | Não |
| Inteligência Artificial Aplicada a Negócios | Não |
| MBA em Inteligência Artificial Aplicada ao Direito | Sim |

## Como usar este site

Este site é só para **consultar** as mensagens e os links de cada curso. Todo envio de boas-vindas é feito pelo **painel do Claude**, para o aluno entrar em Pendências.

Cada um dos 4 passos tem um botão **Copiar** para mandar só aquele link, quando um aluno já cadastrado pedir.

## Como atualizar um link ou mensagem

Todo o conteúdo fica no arquivo `index.html`, na lista `COURSES`. Para trocar um link de turma:

1. Abra `index.html` aqui no GitHub e clique no lápis (Editar).
2. Procure o link antigo (Ctrl + F) e troque pelo novo. Ele aparece duas vezes por curso: na lista `links` e no texto da mensagem.
3. Clique em **Commit changes** (ou **Confirmar alterações**, se o GitHub estiver em português). O site atualiza em 1 a 2 minutos.
