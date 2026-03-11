# 📦 Sistema Logístico - Gerador de Etiquetas A4

Uma aplicação web ágil e responsiva desenvolvida para otimizar o processo logístico de armazéns e estoques. O sistema permite a importação de planilhas (Excel/CSV), o mapeamento de colunas e a geração automática de etiquetas prontas para impressão em formato padrão A4.

## 🚀 Funcionalidades

- **Importação de Planilhas:** Leitura nativa de arquivos `.xlsx`, `.xls` e `.csv`.
- **Mapeamento Dinâmico:** Seleção intuitiva de quais colunas da planilha correspondem aos dados da etiqueta (Código, Descrição, Embalagem, Pallet, Lastro).
- **Busca em Tempo Real:** Filtro rápido por Código ou Descrição sem perder o estado das seleções.
- **Seleção em Massa:** Checkbox inteligente para marcar/desmarcar todos os itens visíveis na tela.
- **Geração de Códigos:** Criação automática de Código de Barras e QR Code de alta resolução para cada produto.
- **Impressão Industrial A4:** Layout rigorosamente calculado usando CSS Grid para preencher folhas A4 sem cortes, com quebra de página automática.
- **Tipografia Dinâmica (Smart Sizing):** O tamanho da fonte da descrição se ajusta automaticamente ao tamanho do texto, evitando quebra de layout em nomes de produtos muito longos.

## 🛠️ Tecnologias Utilizadas

Este projeto foi construído utilizando as seguintes tecnologias e bibliotecas:

- **HTML5 & CSS3** (com tipografia Inter)
- **JavaScript (Vanilla)**
- **[Tailwind CSS](https://tailwindcss.com/)**: Para estilização rápida, moderna e responsiva da interface.
- **[SheetJS (xlsx)](https://sheetjs.com/)**: Para leitura e extração de dados das planilhas em tempo real no navegador.
- **[JsBarcode](https://lindell.me/JsBarcode/)**: Para renderização precisa dos códigos de barras (padrão Code128).
- **[QRCode.js](https://davidshimjs.github.io/qrcodejs/)**: Para a geração dos QR Codes escaneáveis por leitores logísticos.

## ⚙️ Como Usar

Como a aplicação roda inteiramente no lado do cliente (navegador), não é necessário instalar dependências ou rodar servidores complexos.


<img width="615" height="860" alt="image" src="https://github.com/user-attachments/assets/f8a18b87-b58f-4fd2-a7ec-f6c68f8e2dd1" />
