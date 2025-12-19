# Sistema de Gerenciamento de Estoque - FastAPI

API REST para gerenciamento de estoque de aparelhos eletrônicos com FastAPI e XML.

## 🚀 Instalação Rápida

### 1. Verificar Python 3.12
```bash
python3.12 --version
```

### 2. Criar ambiente virtual
```bash
python3.12 -m venv venv
```

### 3. Ativar ambiente virtual

**macOS/Linux:**
```bash
source venv/bin/activate
```

**Windows:**
```bash
venv\Scripts\activate
```

### 4. Instalar dependências
```bash
pip install -r requirements.txt
```

### 5. Inicializar configuração
```bash
python config.py
```

### 6. Executar servidor
```bash
uvicorn app:app --reload
```

## 📍 Acesso

- **API:** http://127.0.0.1:8000
- **Documentação:** http://127.0.0.1:8000/docs

## 📚 Endpoints

| Método | Endpoint | Descrição |
|--------|----------|-----------|
| POST | `/aparelhos` | Adicionar aparelho |
| GET | `/aparelhos` | Listar todos |
| GET | `/aparelhos/{id}` | Buscar por ID |
| PUT | `/aparelhos/{id}` | Atualizar |
| DELETE | `/aparelhos/{id}` | Remover |
| PUT | `/aparelhos/{id}/transferir/{novo_deposito}` | Transferir depósito |

## 🛠️ Comandos Úteis

**Parar servidor:** `Ctrl + C`

**Desativar ambiente:** `deactivate`

**Reativar ambiente:** `source venv/bin/activate` (macOS/Linux)