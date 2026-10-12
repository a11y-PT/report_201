---
website: "C2E - Contratação Centralizada de energia"          # Entre as aspas escreve o nome do website
date: "31/12/1999"                    # Entre as aspas escreve a data de criação do 1º relatório. Os restantes estão no histórico
uri: "https://apps.espap.gov.pt/C2E/"   # Entre as aspas escreve o domínio do website
a11y_statement: "https://ppr-iam.espap.gov.pt/IAM/?client_id=c38612f1-c579-478e-ada8-75a28637dd37&state=b88d59ac-930c-4526-b182-14e9d46c8ed4&code_challenge=t9iBBNoLoRpWl4sXhgE-IsSmbivG3aqNfAf7ILS5Jm0&code_challenge_method=S256#" # Entre as aspas escreve o URL da Declaração de Acessibilidade do website
a11y_statement_date: "05/09/2025"  # Entre as aspas escreve a data da Declaração de Acessibilidade
owner: "nome_do_proprietário"         # Entre as aspas escrever o nome do owner do website
seal: "Prata"                          # Entre as aspas escreve Bronze, Prata ou Ouro
validity: "dd/mm/aaaa a dd/mm/aaaa" # Entre as aspas escreve data de início e data de fim no formato 31/12/1999 a 31/12/2000
status: "Auditoria a decorrer" # Entre as aspas escreve uma das seguintes opções: "Auditoria a decorrer", "A aguardar correções da entidade", "Concluído" 
---

# Relatório de auditoria

Sítio Web: {{ page.website }}

- Data de criação: {{ page.date }}
- URL: {{ page.uri }}
- Propriedade: {{ page.owner }}
- Candidatura: {{ page.seal }}
- Validade do selo: {{ page.validity }}
- Estado: {{ page.status }}

## Relatório {{ page.website }}

<p>O presente relatório resultou da auditoria da informação publicada na <a href="{{ page.a11y_statement }}">Declaração de Acessibilidade e Usabilidade</a>.</p>

Consulte aqui a última atualização: [Relatório {{ page.website }}](report.html)

<details>
  <summary>Histórico de atualizações</summary>
  <ul aria-label="lista de relatórios já efetuados">
    <li><a href="ddmmaaaa_report.html">(dd/mm/aaaa). Relatório {{ page.website }}</a></li>
  </ul>
</details>

<hr>

<p><small>2025 - 2026, GitTemplateReports Web (v.1.0.4)</small></p>
