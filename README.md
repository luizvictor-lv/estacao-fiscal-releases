# Estação Fiscal RTC — Instaladores

Este repositório guarda apenas os **instaladores oficiais** da Estação Fiscal RTC, o aplicativo
desktop que roda o motor oficial de cálculo de CBS, IBS e Imposto Seletivo da Receita Federal
(Reforma Tributária do Consumo — LC 214/2025) 100% offline, no computador do escritório contábil.

O código-fonte do aplicativo não fica aqui.

## Download

Baixe sempre pelo site oficial — **https://estacao-fiscal-rtc.pages.dev** — ou pela aba
[Releases](../../releases/latest) deste repositório.

| Sistema | Arquivo |
| :--- | :--- |
| Windows 10/11 (64 bits) | `EstacaoFiscalRTC_x64-setup.exe` |
| Linux (AppImage) | `EstacaoFiscalRTC_amd64.AppImage` |
| Ubuntu/Debian | `EstacaoFiscalRTC_amd64.deb` |
| macOS (Apple Silicon e Intel) | `EstacaoFiscalRTC_universal.dmg` |

Cada release informa a versão do motor oficial da Receita Federal embutido e o respectivo hash
SHA-256, também exibido no aplicativo em **Configurações**.

## Licença de uso

O aplicativo exige uma chave de licença (`RTC-XXX-XXXX-XXXX`), ativada uma vez com internet.
Depois disso funciona offline por até 7 dias seguidos, renovando sozinho quando há conexão.

## Privacidade

Planilhas, XMLs e cálculos dos clientes do escritório nunca saem do computador: o motor oficial
roda localmente em `127.0.0.1`. A internet é usada apenas para validar a licença.

---

A Estação Fiscal RTC é um produto independente e não é afiliada à Receita Federal do Brasil.
Utiliza o código aberto da calculadora RTC publicado pela Receita Federal (licença MIT).
Os resultados são simulações e não substituem a apuração oficial.
