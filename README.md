# WhatsApp Negative Balance Alert Automation

Automação em Python para monitoramento de clientes com saldo negativo a partir de bases em Excel, com geração de alertas visuais por assessor e envio automatizado via WhatsApp Web, apoiando rotinas de backoffice e acompanhamento operacional.

> English (short): Python automation for negative balance monitoring using Excel data, generating per-advisor visual alerts and automated delivery via WhatsApp Web.

---

## Principais recursos

* Processamento de bases em Excel para identificação de clientes com saldo negativo
* Consolidação e agrupamento das informações por assessor
* Geração automática de imagens-resumo para comunicação visual
* Envio automatizado de alertas via WhatsApp Web utilizando Selenium
* Apoio à atuação preventiva e ao acompanhamento operacional

---

## Contexto

Em rotinas de backoffice e operações, o acompanhamento de clientes com saldo negativo exige:

* monitoramento frequente de bases atualizadas
* comunicação rápida com os responsáveis
* clareza visual para priorização de ações
* redução de controles manuais repetitivos

A execução manual desse processo é suscetível a falhas, atrasos e inconsistências operacionais.

Este projeto automatiza esse fluxo de forma estruturada, reduzindo esforço manual, melhorando a visibilidade das situações críticas e apoiando a tomada de ação em tempo hábil.

---

## Aviso importante (uso autorizado)

Este repositório é apresentado como exemplo técnico/portfólio.

* Utilize apenas ambientes e contas autorizadas
* Não utilize dados reais ou informações sensíveis
* Respeite políticas internas, LGPD e regras de uso do WhatsApp Web
* Este projeto não deve ser utilizado em produção sem as devidas autorizações

---

## Estrutura do projeto

A estrutura do projeto foi mantida simples, refletindo a complexidade real da automação:

```
.
├─ main.py
├─ requirements.txt
├─ LICENSE
└─ README.md
```

---

## Requisitos

* Python 3.10+
* Ambiente Windows
* Navegador Google Chrome
* Conta ativa no WhatsApp Web

Este projeto utiliza automação via Selenium, sendo dependente de navegador e sessão ativa.

---

## Instalação

Crie um ambiente virtual e instale as dependências:

```bash
python -m venv .venv

# Windows
.venv\Scripts\activate

pip install -r requirements.txt
```

---

## Configuração

As bases de dados em Excel utilizadas para leitura de saldos devem permanecer fora do versionamento.

* Arquivos reais de entrada não devem ser incluídos no Git
* Caminhos e parâmetros operacionais podem ser ajustados diretamente no código
* Caso necessário, o projeto pode ser adaptado para uso de arquivos de configuração locais

---

## Execução

Execute o script principal:

```bash
python main.py --saldos "caminho/para/saldos.xlsx" --contatos "caminho/para/contatos.xlsx"
```

O processo executa as seguintes etapas:

* leitura da base em Excel
* identificação de clientes com saldo negativo
* consolidação das informações por assessor
* geração de imagens-resumo
* envio automatizado de alertas via WhatsApp Web

---

## Saídas geradas

* Imagens-resumo por assessor
* Alertas enviados via WhatsApp Web
* Apoio visual para acompanhamento operacional

---

## Sanitização de dados

Este repositório não contém dados reais.

* Bases Excel reais devem permanecer fora do Git
* Imagens geradas são tratadas apenas em tempo de execução
* Identificadores sensíveis não são persistidos

---

## Licença

MIT
