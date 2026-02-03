WhatsApp Negative Balance Alert Automation

Automação em Python para monitoramento de clientes com saldo negativo a partir de bases em Excel, com geração de alertas visuais por assessor e envio automatizado via WhatsApp Web, apoiando rotinas de backoffice e acompanhamento operacional.

English (short): Python automation for monitoring negative balances using Excel data, generating visual alerts per advisor and delivering notifications via WhatsApp Web.

Principais recursos

- Processamento de bases em Excel para identificação de clientes com saldo negativo
- Consolidação e agrupamento das informações por assessor
- Geração automática de imagens-resumo para comunicação visual
- Envio automatizado de alertas via WhatsApp Web utilizando Selenium
- Apoio à atuação preventiva e ao acompanhamento operacional

Contexto

Em rotinas de backoffice e operações, o acompanhamento de clientes com saldo negativo exige:

- monitoramento frequente de bases atualizadas
- comunicação rápida com os responsáveis
- clareza visual para priorização de ações
- redução de controles manuais repetitivos

Este projeto automatiza esse fluxo operacional, reduzindo esforço manual, melhorando a visibilidade das situações críticas e apoiando a tomada de ação em tempo hábil.

Aviso importante (uso autorizado)

Este repositório é apresentado como exemplo técnico/portfólio.

- Utilize apenas ambientes e contas autorizadas
- Não utilize dados reais ou informações sensíveis
- Respeite políticas internas, LGPD e regras de uso do WhatsApp Web
- Este projeto não deve ser utilizado em produção sem as devidas autorizações

Estrutura do projeto

.
├─ main.py
├─ requirements.txt
├─ LICENSE
└─ README.md

Requisitos

- Python 3.10+
- Ambiente Windows
- Navegador Google Chrome
- Conta ativa no WhatsApp Web

Este projeto utiliza automação via Selenium, sendo dependente de navegador e sessão ativa.

Instalação

python -m venv .venv

# Windows
.venv\Scripts\activate

pip install -r requirements.txt

Configuração

As bases de dados em Excel utilizadas para leitura de saldos devem permanecer fora do versionamento.

Caminhos de arquivos e parâmetros operacionais podem ser ajustados diretamente no código ou adaptados para arquivos de configuração locais, conforme a necessidade do ambiente.

Execução

python main.py

O processo:

- lê a base em Excel
- identifica clientes com saldo negativo
- consolida informações por assessor
- gera imagens-resumo
- envia alertas via WhatsApp Web

Saídas geradas

- Imagens-resumo por assessor
- Alertas enviados via WhatsApp Web
- Apoio visual para acompanhamento operacional

Sanitização de dados

Este repositório não contém dados reais.

- Bases Excel reais devem permanecer fora do Git
- Imagens geradas não devem ser versionadas
- Identificadores sensíveis são tratados apenas em tempo de execução

Licença

MIT
