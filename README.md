# extraindo-Insights-feedback-clientes
Atividade de Desafio Criativo do Curso da Dio.me : Usando a IA para Extrair Insights de Feedback de Clientes na internet


PROMPT : 

Atue como analista de dados e experiência do Mercado Bitcoin
Busque na internet em sites de reclamação como o Procon, Reclame Aqui e outros que tenha conhecimento.
Sua tarefa é analisar feedbacks de clientes sobre aplicativo bancário, Pix, cartão de crédito, investimentos e atendimento por chat; para identificar temas recorrentes, sentimento dos clientes e oportunidades de melhoria.
Contexto: A análise será usada por uma equipe de experiência do cliente para priorizar melhorias nos canais digitais e reduzir atritos no atendimento. O foco é transformar comentários soltos em insights claros e acionáveis.
Dados disponíveis: Serão fornecidos comentários com data, canal de atendimento, texto do feedback, produto citado e nota de satisfação.

Instruções de análise:
1. Classifique os feedbacks por tema, sentimento, urgência e produto citado.
2. Identifique os principais padrões, problemas, elogios e oportunidades.
3. Aponte evidências nos dados fornecidos, usando exemplos curtos de comentários.
4. Sugira ações práticas para a equipe de experiência do cliente e para o time responsável pelos canais digitais.

Formato da resposta: Entregue um resumo executivo com até 5 linhas, uma tabela com tema, sentimento, evidência e ação sugerida, além de uma lista final com as 3 prioridades mais importantes.

Restrições:
- Use apenas os dados fornecidos.
- Não invente números, causas ou conclusões.
- Não exponha dados pessoais ou sensíveis.
- Informe limitações quando os dados não forem suficientes.
- Use linguagem simples, direta e voltada para tomada de decisão.


 Resposta do CHATGPT :
 
Resumo executivo
A principal fonte pública encontrada foi o Reclame Aqui; não encontrei, na busca realizada, uma base pública do Procon/Consumidor.gov.br suficientemente específica para complementar a análise sem extrapolar os dados.
O padrão mais recorrente é dificuldade de atendimento, especialmente quando o cliente precisa sair do fluxo automatizado e falar com uma pessoa.
Pix, saques, depósitos e bloqueios de conta/limites aparecem como situações de maior urgência, pois impedem o cliente de movimentar recursos.
Há relatos de instabilidade e falhas no aplicativo, inclusive após atualizações, algumas associadas à impossibilidade de visualizar saldo ou operar.
Apesar dos problemas, existem casos em que a solução foi efetiva após escalonamento, com clientes atribuindo notas altas ao atendimento.
Análise dos feedbacks encontrados
Tema	Sentimento	Evidência	Ação sugerida
Atendimento/chat	🔴 Negativo	“chat robô que não resolve” e dificuldade para conseguir atendimento humano.	Criar escalonamento rápido para atendimento humano, principalmente para bloqueios, dinheiro retido e falhas críticas.
Pix / depósitos / saques	🔴 Muito negativo / Alta urgência	Há relatos de Pix em processamento, depósitos não compensados e impossibilidade de sacar.	Criar status detalhado da transação, prazo estimado e explicação clara do motivo do bloqueio, além de fila prioritária para dinheiro indisponível.
Bloqueios / compliance	🔴 Negativo / Alta urgência	Clientes relatam envio de documentos e permanência do bloqueio sem atualização; em alguns casos, posteriormente houve encerramento definitivo da conta.	Informar etapa da análise, documentação pendente e próximo passo, sem deixar o cliente sem informação durante a análise.
Aplicativo / estabilidade	🔴 Negativo	Reclamações de aplicativo que não abre, fecha sozinho, saldo aparentemente zerado e problemas após atualização.	Implantar monitoramento de estabilidade por versão/SO e comunicação automática durante incidentes.
Cartão / conta digital	🔴 Negativo / Alta urgência	Relatos de dificuldades para ativar conta digital, solicitar cartão, bloqueio e contestação de cobranças.	Revisar jornadas de ativação e cartão; disponibilizar autoatendimento claro para bloqueio, substituição e contestação.
Investimentos / renda fixa	🔴 Negativo / Alta urgência	Há reclamações sobre valores de investimentos que não foram creditados no vencimento ou ficaram sujeitos a eventos da empresa emissora/parceira.	Melhorar comunicação pré e pós-vencimento: status do ativo, responsável pelo pagamento, prazo e próximos passos em caso de evento adverso.
Atendimento após solução	🟢 Positivo quando há intervenção humana eficaz	Em um caso, após escalonamento, o cliente informou que recebeu esclarecimentos e deu nota 8; em outro, a solução rápida recebeu nota 10.	Reproduzir o modelo de atendimento dos casos resolvidos: responsável identificado + acompanhamento + explicação objetiva + solução.
Sinais importantes para a experiência do cliente

1. O maior atrito não parece ser apenas o problema técnico, mas a combinação “problema + falta de informação”.
Nos relatos de Pix, bloqueios e aplicativo, a insatisfação aumenta quando o cliente não sabe por que aconteceu, quanto tempo levará e o que precisa fazer.

2. O atendimento automatizado é um ponto crítico.
Diversos relatos descrevem o chat como incapaz de resolver situações fora do fluxo padrão. Há inclusive reclamações específicas sobre não conseguir chegar a um atendente humano.

3. Problemas de disponibilidade têm impacto desproporcional.
Quando o aplicativo não abre ou Pix/saque ficam indisponíveis, o cliente não está apenas enfrentando um “bug”: ele percebe que não consegue acessar ou movimentar seu dinheiro. Isso eleva naturalmente a urgência percebida.

4. A recuperação do atendimento funciona quando existe acompanhamento humano.
Há evidência nos próprios relatos de que uma intervenção posterior, com esclarecimento adequado, consegue recuperar a percepção do cliente.

Como contexto quantitativo, o Reclame Aqui informa que, no período de 01/01/2026 a 30/06/2026, o Mercado Bitcoin recebeu 506 reclamações, respondeu 95,1%, resolveu 87,9% e teve nota média dos consumidores de 6,85 entre as avaliações; portanto, a reputação geral é positiva, mas a nota média das experiências avaliadas mostra espaço relevante para melhoria.

3 prioridades para a equipe de CX

1. Atendimento humano para casos críticos
Criar uma regra de escalonamento automático para Pix/saque bloqueado, dinheiro não creditado, conta bloqueada, cartão bloqueado e falha persistente do aplicativo.

2. Transparência durante bloqueios e análises
O cliente deveria conseguir visualizar algo como: “Em análise → documentos recebidos → análise concluída → próxima ação”, com prazo ou atualização prevista sempre que possível.

3. Reduzir falhas e melhorar comunicação de incidentes no app
Monitorar cada atualização por versão e sistema operacional e, quando houver incidente, informar imediatamente no próprio aplicativo: “Identificamos o problema / sua conta e seus ativos estão seguros / previsão de normalização / acompanhe aqui”.

Limitações da análise

Esta é uma análise qualitativa dos relatos públicos que consegui localizar, não uma análise estatística de uma base completa de clientes. Portanto, não é possível afirmar que os temas mais encontrados na busca representam proporcionalmente toda a base do Mercado Bitcoin. Também não atribuo causas aos problemas além do que os próprios relatos ou respostas públicas permitem concluir.Esta é uma análise qualitativa dos relatos públicos que consegui localizar, não uma análise estatística de uma base completa de clientes. Portanto, não é possível afirmar que os temas mais encontrados na busca representam proporcionalmente toda a base do Mercado Bitcoin. Também não atribuo causas aos problemas além do que os próprios relatos ou respostas públicas permitem concluir.
