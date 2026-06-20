# Relatório Fotográfico

App web para inspeções técnicas e manutenções preventivas (MP/INSP). Funciona em qualquer navegador, celular ou computador.

## Acesse

**https://jjuniordev18.github.io/app-relatorio-fotografico/**

## Funcionalidades

- 📷 **Câmera integrada** — tira fotos direto no navegador
- ✅ **Status OK/NOK/N/A** — controle por item
- 📄 **PDF completo** — grade de fotos, observações, assinatura digital
- 📤 **Compartilhar** — E-mail, Teams, WhatsApp, copiar texto
- 📊 **Relatório Consolidado** — selecione múltiplas atividades
- 📊 **Exportar Excel** — dados completos em .xlsx
- 🔍 **Busca e filtros** — encontre itens rapidamente
- ↕ **Ordenar por status** — pendentes primeiro
- ✍ **Assinatura** — digitada ou desenhada no canvas
- 🌙 **Modo escuro** — tema claro/escuro com persistência
- 📱 **PWA** — funciona offline após primeiro acesso
- 💾 **Auto-save** — dados salvos automaticamente no navegador
- 🔐 **Modo Admin** — edite, reordene e adicione atividades (senha: ****)

## Como usar

1. Acesse o link acima no celular ou computador
2. Selecione a atividade no menu lateral ☰
3. Preencha técnico, local e setor
4. Para cada item: tire foto e marque OK/NOK/N/A
5. Adicione observações quando necessário
6. Gere o PDF ou compartilhe

## Atividades disponíveis

- MP Local de Radio Nokia MW
- Inspeção Sensitiva de Abrigo
- INSP Sensitiva Radio MW
- Insp sens. Ar Cond.
- MP Repetidora/Poste
- INSP Sensitiva de Gerador
- INSP Radio Nokia MW
- MP de Enode-B
- INSP Sens. Retificador
- MP Retificador

## Admin

Clique em ⚙ e digite a senha **----** para:
- Editar nomes de atividades e itens
- Reordenar itens (▲▼)
- Adicionar/excluir itens
- Criar novas atividades
- Importar/Exportar JSON e Excel

## Tecnologias

- HTML5 / CSS3 / JavaScript vanilla
- jsPDF (geração de PDF)
- SheetJS/XLSX (exportação Excel)
- Geolocalização (GPS por foto)
- Service Worker (PWA/offline)
