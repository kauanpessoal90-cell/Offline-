# Bolso — orçamento offline

Aplicativo estático em português para registrar gastos, acompanhar categorias e guardar backups no próprio navegador. Sem API de IA, rastreamento ou conexão bancária.

## Publicar no GitHub Pages

Em Settings → Pages, escolha **Deploy from a branch**, branch **main**, pasta **/ (root)** e salve. Aguarde a publicação indicada pelo GitHub. Abra o endereço, espere **Pronto para offline** e adicione à tela inicial no Chrome. Teste em modo avião.

## Dados pessoais

O código começa com saldos zerados. Em Backup, importe o JSON privado recebido separadamente. Não envie esse arquivo para este repositório público. Exporte backups com frequência. Dados são locais a cada navegador/dispositivo; não há sincronização automática.

## Escopo

Esta versão trabalha com novembro de 2026. Não há virada automática de mês. O décimo é protegido contra despesas. Reserva e resgate são transferências entre conta e CDB. Valores a receber não entram no patrimônio até o recebimento.

## Desenvolvimento

HTML/CSS/JavaScript sem dependências. Sirva esta pasta em localhost para testar o service worker. Ao atualizar a interface, incremente a versão de cache em sw.js e no indicador de index.html. O cache prioriza a versão salva. Todos os valores monetários são inteiros em centavos.


