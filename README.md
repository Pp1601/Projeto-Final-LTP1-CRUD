# Projeto Final LTP1 — Sistema CRUD em C

---

## Sobre o Projeto

Sistema **CRUD 100% funcional** voltado para o gerenciamento de uma loja especializada na **venda de placas de vídeo**. O sistema permite o cadastro, consulta, atualização e exclusão de clientes, produtos e ordens de compra/venda.

---

## Estrutura do Sistema

### Clientes
Gerenciamento dos perfis de clientes com os seguintes campos:

| Campo | Descrição |
|-------|-----------|
| ID | Identificador único |
| CPF | Cadastro de Pessoa Física |
| Nome | Nome completo |
| Telefone | Número de contato |
| E-mail | Endereço de e-mail *(opcional)* |

### Produtos
Gerenciamento do catálogo de produtos com os seguintes campos:

| Campo | Descrição |
|-------|-----------|
| Código | Identificador do produto |
| Nome | Nome do produto |
| Valor | Preço de venda |
| Qtd. Estoque | Quantidade disponível em estoque |

### Compra / Venda
Registro das ordens de compra e venda com os seguintes campos:

| Campo | Descrição |
|-------|-----------|
| Nº do Pedido | Número identificador do pedido |
| Cód. Cliente | Referência ao cliente |
| Cód. Produto | Referência ao produto |
| Qtd. Desejada | Quantidade solicitada |
| Valor Total | Valor calculado da transação |

---

## Operações CRUD disponíveis

| Módulo | Cadastrar | Consultar | Atualizar | Excluir |
|--------|:---------:|:---------:|:---------:|:-------:|
| Cliente | ✅ | ✅ | ✅ | ✅ |
| Produto | ✅ | ✅ | ✅ | ✅ |
| Compra/Venda | ✅ | ✅ | ✅ | ✅ |

---

## Dados de Exemplo

### Clientes

| ID | Nome | CPF | E-mail |
|----|------|-----|--------|
| 01 | Arthur Nagasaki | 629.464.294-62 | japex@gmail.com |
| 02 | Bruno Vaidant | 659.759.632-32 | jingchines@gmail.com |
| 03 | Matheus Jardim | 235.684.759-36 | — |

### Produtos

| Cód. | Nome | Valor | Qtd. Estoque |
|------|------|-------|:------------:|
| 01 | Asus TUF Gaming NVIDIA GeForce RTX 3090 Ti | R$ 14.599,90 | 6 |
| 02 | Zotac Gaming NVIDIA GeForce RTX 2060 | R$ 2.099,90 | 62 |
| 03 | Asus TUF Gaming NVIDIA GeForce GTX 1660 Ti | R$ 3.148,82 | 43 |
| 04 | AMD Radeon RX 550 Pulse | R$ 749,90 | 36 |

---

## Tecnologias Utilizadas

- **Linguagem:** C
- **Paradigma:** Programação Estruturada
- **Persistência:** Arquivos binários (`.dat`)
- **Compilador:** GCC

---

## Arquivos do Projeto

| Arquivo | Descrição |
|---------|-----------|
| `Projeto Final` | Arquivo principal com o menu e integração dos módulos |
| `Cadastro de cliente` | Módulo de cadastro de clientes |
| `Cadastro de produto` | Módulo de cadastro de produtos |
| `Cadastro Compra_e_Venda` | Módulo de registro de compras e vendas |
| `Consulta Cliente` | Módulo de consulta de clientes |
| `Consulta produto` | Módulo de consulta de produtos |
| `Consulta Compra` | Módulo de consulta de compras |
| `Atualiza Cliente` | Módulo de atualização de clientes |
| `Atualiza Produto` | Módulo de atualização de produtos |
| `Atualiza Compra` | Módulo de atualização de compras |
| `Exclui Cliente` | Módulo de exclusão de clientes |
| `Exclui Produto` | Módulo de exclusão de produtos |
| `Exclui Compra` | Módulo de exclusão de compras |

---

## Autor

Desenvolvido por **[Pp1601](https://github.com/Pp1601)** — 2022
