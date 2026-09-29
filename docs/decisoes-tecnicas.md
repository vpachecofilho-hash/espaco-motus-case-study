# Decisões técnicas

## Pagamentos parciais

Um título pode receber mais de uma baixa. A regra de negócio precisa preservar cada valor e sua data, calcular o saldo restante e mostrar o histórico ao operador. Dados legados sem parcelas detalhadas são tratados como legado; parcelas anteriores não são inventadas. Em testes, casos de pagamento integral, parcial e valor inválido são separados.

## Previsão e realizado

O fluxo de caixa padrão representa a previsão baseada em vencimentos. O filtro **Somente Pagos** usa valores já recebidos ou pagos. Essa distinção evita interpretar um vencimento futuro como dinheiro em caixa.

## Interface adaptada à rotina

O painel prioriza atalhos pertinentes ao perfil e acesso rápido às rotinas financeiras. Em telas pequenas, grades extensas rolam dentro do próprio painel; o documento não deve ganhar rolagem horizontal. Os temas claro e escuro precisam manter contraste em formulários, tabelas e conteúdo do aluno.

## Respeito ao framework

O Adianti fornece a base da aplicação. Ajustes de negócio e aparência são feitos preferencialmente na camada específica do Motus, para reduzir o impacto de manutenção do framework.

## Publicação gradual

Uma mudança passa por verificação local, homologação e publicação seletiva. Antes da produção, há backup verificável de arquivos e banco. Após publicar, conferem-se a integridade dos arquivos modificados, a resposta do site e a preservação de conteúdo persistente. Problemas observados durante os testes são registrados com passos, resultado esperado e resultado obtido.
