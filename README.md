# 📋 Gerenciador de Clientes - Python, SQLite e Tkinter

Bem-vindo ao **Gerenciador de Clientes**, um projeto simples e didático desenvolvido em **Python**, com banco de dados **SQLite3** e interface gráfica usando **Tkinter**.

> 🎓 Ideal para estudantes iniciantes que desejam aprender a construir aplicações completas com interface, banco de dados e lógica de programação.

---

## ⚙️ Funcionalidades

Com esta aplicação, você pode:

- ✅ Adicionar novos clientes
- ✅ Visualizar todos os registros salvos
- ✅ Buscar clientes por nome, sobrenome, email ou CPF
- ✅ Atualizar os dados de um cliente selecionado
- ✅ Deletar clientes do banco de dados

A interface é intuitiva, com campos de entrada e botões para cada ação, e a base de dados é armazenada localmente em `clientes.db`.

---

## 🧱 Estrutura do Projeto

O código está organizado em três arquivos principais:

### 📁 `Gui.py`
- Cria a interface gráfica com **Tkinter**
- Define os campos de entrada, botões e tabela (Treeview)
- Conecta a interface às funções do backend

### 📁 `Backend.py`
- Gerencia o banco de dados **SQLite**
- Possui métodos para criar tabela, inserir, buscar, atualizar e deletar clientes
- Utiliza **consultas SQL seguras** com parâmetros

### 📁 `application.py`
- Ponto de entrada da aplicação
- Inicializa o banco e exibe a janela principal com a interface gráfica

---

## 🚀 Como Executar

### 1. Pré-requisitos

- Python 3.8 ou superior
- Tkinter (já vem com Python)
- SQLite3 (módulo `sqlite3` incluso)
- PyInstaller (opcional, para gerar executável)

### 2. Passo a passo para rodar:

```bash
# Verifique se o Python está instalado
python --version

# Navegue até a pasta do projeto
cd caminho/para/gerenciador_clientes

# Execute a aplicação
python application.py
---
## 👤 Autor

**João Arthur**  
💻 Projeto desenvolvido para fins educacionais e prática com Python, SQLite e Tkinter.

📅 **Última atualização:** 04 de julho de 2025
