# Sutoorii Society

Site de apresentação comercial da Society, área de marketing digital da Sutoorii Labs.

## Estado atual

Esta versão contém o **protótipo front-end v2 de 6 de novembro de 2026**, em HTML, CSS e JavaScript, sem etapa de build.

- Página responsiva com apresentação da Society, serviços avulsos e pacotes mensais.
- Planos exibidos: Essencial (R$ 1.190/mês), Pro (R$ 1.990/mês) e Premium (R$ 4.490/mês).
- Interface de seleção dos serviços e simulação visual de contratação.

**Atenção:** o site está funcional como apresentação e demonstração visual. Ainda **não** realiza cadastro de clientes, autenticação pelo Sutoorii Tickets, assinatura de contratos, cobranças pelo Billing nem contratação efetiva. Não tratar os botões demonstrativos como pedidos concluídos.

## Como executar localmente

Abra o arquivo `index.html` em um navegador. Para servir por HTTP, utilize um servidor estático local.

## Próxima etapa (não implementada)

1. Definir configuração de hospedagem e publicação em `society.sutoorii.com`.
2. Implementar painel de administração dos planos/serviços e propostas privadas.
3. Integrar autenticação com Sutoorii Tickets.
4. Implementar contratos digitais de 6 e 12 meses e a integração com Sutoorii Billing.
5. Testar o fluxo ponta a ponta antes de habilitar contratações reais.

Código-base preservado como protótipo, sem credenciais ou configuração de servidor incluídas.

## Publicação automática

O workflow `.github/workflows/deploy.yml` é acionado a cada novo commit na branch `main` ou manualmente pelo GitHub Actions. A conexão FTPS exige que `FTP_HOST` corresponda ao certificado TLS do servidor Hostoo.
