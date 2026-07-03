# Instalação

## Requisitos

Antes de importar o dashboard, certifique-se de possuir:

- Grafana 10 ou superior
- Zabbix 7.x
- Plugin oficial do Zabbix para Grafana
- Template FortiGate instalado no Zabbix

---

## Importando o Dashboard

1. Faça o download do arquivo `dashboard.json`.

2. No Grafana, acesse:

```
Dashboards → New → Import
```

3. Selecione o arquivo `dashboard.json`.

4. Escolha o Data Source do Zabbix.

5. Clique em **Import**.

---

## Ajustes

Após a importação poderá ser necessário:

- Ajustar o nome do Data Source
- Selecionar os Hosts corretos
- Configurar as Variáveis
- Ajustar o Time Range

---

## Observações

Este dashboard foi desenvolvido utilizando dados anonimizados.

Dependendo da versão do Template FortiGate, alguns painéis poderão exigir pequenos ajustes.
