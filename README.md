# Portal de Fornecedores e Suprimentos — LCM Construção

Aplicação web corporativa desenvolvida para credenciamento, oferta de serviços de engenharia, envio de documentação de homologação e conformidade com a **Lei Geral de Proteção de Dados (LGPD — Lei nº 13.709/2018)** da **LCM Construção**.

## Funcionalidades Principais

- **Catálogo de Escopos de Contratação:** Infraestrutura Rodoviária e Terraplenagem, Edificações Civis, Fornecimento de Materiais/Insumos e Locação de Linha Amarela/Equipamentos.
- **Credenciamento em 4 Etapas:**
  1. Dados Empresariais, Fiscais e Domicílio Bancário PJ.
  2. Oferta de Serviços, Capacidade Operacional e Estados de Atuação (UFs).
  3. Central de Anexos de Certidões e Documentos de Homologação (`PDF`, `JPG`, `PNG`, `ZIP`).
  4. Termo de Privacidade LGPD (Lei nº 13.709/2018), Compliance Anticorrupção (Lei nº 12.846/2013) e Geração de Protocolo com Hash de Auditoria.
- **Painel de Acompanhamento de Protocolo:** Consulta por CNPJ ou número de protocolo e envio complementar de certidões.

## Como Executar Localmente

```bash
npm install
npm run dev
```

## Como Gerar a Versão de Produção (Vercel / Netlify)

```bash
npm run build
```
