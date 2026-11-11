# Painel Comercial | Equipamentos

Dashboard público com dados agregados da carteira comercial.

## Privacidade
Este repositório contém somente indicadores agregados por região e UF. Não publicar nomes de clientes, códigos SAP ou linhas individualizadas.

## Hospedagem
GitHub Pages gratuito, branch main, diretório raiz.

## Fonte e atualização
Planilha Google Sheets privada: ID `1nCc5nzp44iAju_VutdPEW89X84q-RTfBkY_vLkokkGk`.
A versão inicial usa totais agregados conhecidos da base tratada. A atualização automática será ligada após validar um endpoint seguro do Google Apps Script. Nenhuma credencial deve ser inserida no navegador ou neste repositório.

## Limitações
- A base atual não contém datas de início/fim dos contratos.
- Cidades sem preenchimento não são geocodificadas.
- Registros duplicados foram mantidos por solicitação; registros não equivalem a clientes únicos.
- O mapa usa GeoJSON público e Leaflet via CDN.
