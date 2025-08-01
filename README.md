# Grafana Dashboards

Coleção de dashboards Grafana configurados como ficheiros JSON para provisionamento via Git.

## 📦 Estrutura do repositório

- `dashboards/` – contém todos os dashboards em formato JSON.
- `dashboards/zabbix/` – Ficam os dashboards com o datasource zabbix.
- `provisioning/` – configuração para provisionamento no Grafana.
- `datasources/` – configuração e coleção dos datasources e configurações necessárias para o funcionamento.
- `dashboards.yaml` – define onde os dashboards serão carregados.
- `README.md` – (este ficheiro) explicação geral e instruções.

## ❓ Objetivo

Este repositório permite gerir dashboards Grafana como código, garantindo:

- Versão controlada através do Git.
- Reutilização e partilha entre diferentes instâncias Grafana.
- Automação do deployment via provisionamento Git ou local :contentReference[oaicite:1]{index=1}.

## 🚀 Como utilizar

1. Certifica-te de que tens uma instância Grafana (versão >= v12).
2. Clona o repositório:
   ```bash
   git clone https://github.com/Nidaime-Pedro/grafana-dashboards.git
