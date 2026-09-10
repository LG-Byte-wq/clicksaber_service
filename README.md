# ClickSaber - v1.4

Aplicação web para processamento, validação e conversão de arquivos de carga (CSV/XLSX) de escolas para inclusão de cadastros e personalizações da plataforma.

---

## Versão 1.4

- **Preservação de Zeros à Esquerda (CNPJ / Código Escola):** Implementada a formatação de texto explícita (`="000..."`) para garantir que CNPJs e Códigos de Escola mantenham os zeros iniciais sem distorções ao serem abertos no Excel ou Google Sheets.
- **Suporte Nativo a XLSX:** Leitura e processamento direto de arquivos do Excel (`.xlsx` e `.xls`), além do suporte padrão a CSV.
- **Melhorias de Interface (UI/UX):**
  - Toggle de **Modo Escuro (Dark Mode)** com suporte a variáveis CSS dinâmicas.
  - Título principal e versão reorganizados e centralizados.
  - Indicadores de versão mantidos no rodapé do sistema.
