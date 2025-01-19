# 🛒 Controle de Estoque

Uma aplicação web simples desenvolvida em Flask para gerenciar o estoque de produtos. Permite o upload de planilhas em formato `.xlsx`, exibição e edição dos dados diretamente na interface, e exportação do estoque atualizado.

## 🎯 Funcionalidades

- Upload de arquivos Excel (`.xlsx`) com os dados do estoque.
- Exibição dos produtos, quantidades e contagens na interface web.
- Edição de quantidades e contagens diretamente pela interface.
- Exclusão de produtos do estoque.
- Exportação do estoque atualizado como um arquivo Excel.

---

## 🚀 Tecnologias Utilizadas

- **Backend**: Flask, Python
- **Frontend**: HTML, CSS, JavaScript
- **Bibliotecas**:
  - `openpyxl` para manipulação de planilhas Excel.
  - `werkzeug` para manuseio de uploads.
- **Banco de Dados**: Dados armazenados em memória.

---

## 🛠️ Como Executar o Projeto

### Pré-requisitos
- Python 3.8 ou superior instalado.
- Biblioteca `openpyxl` instalada.
- Ambiente virtual Python (opcional, mas recomendado).

### Passo a passo
1. Clone o repositório:
   ```bash
   git clone https://github.com/seuusuario/controle-estoque.git
   cd controle-estoque
2. Crie um ambiente virtual (opcional):
```bash
  python -m venv venv
  source venv/bin/activate   # No Windows: venv\Scripts\activate

```
3. Instale as dependências:
```bash
 pip install -r requirements.txt
```
4. Execute a aplicação:
```bash
  python app.py
```


## 📋 Como Usar

### Envio do arquivo Excel:
- Clique no botão de upload na página inicial.
- Escolha um arquivo `.xlsx` com os dados do estoque.
- Os dados serão exibidos na tabela.

### Edição dos produtos:
- Use os botões `+` e `-` para alterar a quantidade.
- O estoque será atualizado automaticamente.

### Exclusão de produtos:
- Clique em "Excluir" para remover um produto do estoque.

### Exportação:
- Clique no botão "Baixar Estoque Atualizado" para obter uma planilha Excel atualizada.

