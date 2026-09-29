# Como o projeto é validado

As evidências abaixo representam verificações realizadas até **29/09/2026**. Não são uma afirmação de cobertura total do sistema.

| Frente | Evidência resumida |
| --- | --- |
| Rotas administrativas | 18 rotas disponíveis à conta fictícia de QA carregaram sem erro visível; oito formulários foram abertos sem gravar dados. |
| Larguras de celular | As 18 rotas verificadas em Chromium de 390 px não alargaram a página. Seis rotas prioritárias também foram conferidas em 320 px. |
| Financeiro | Casos de recebimento parcial, conciliação e alternância do fluxo de caixa foram exercitados em ambientes de teste. |
| Homologação | Mudanças de interface e grades foram avaliadas em ambiente online antes da produção; houve aceite visual em Android/Chrome. |
| Produção | A publicação mais recente teve backup integral verificado, 20 checagens de preflight sem falhas, sintaxe PHP válida e conferência de fotos e uploads preservados. |

## Limites atuais

- iPhone/Safari real ainda não foi validado neste ciclo.
- O teste das rotas com sessão própria do aluno fictício segue pendente.
- A confirmação visual detalhada das duas grades no Android após a publicação em produção ainda não foi registrada.
- Testes de leitura não substituem testes de gravação nem auditoria completa de segurança.

Dados de alunos e evidências que revelem informações operacionais não são publicados neste portfólio.
