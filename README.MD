# Front-end do Sistema de Investimentos

Esta diretório contém os arquivos responsáveis pela interface visual do sistema, permitindo ao usuário interagir com a aplicação de forma dinâmica e intuitiva.

---

## ℹ️ Sobre o projeto

Este teste prático tem como objetivo desenvolver uma aplicação para controle simples de investimentos, permitindo **cadastrar**, **visualizar**, **editar** e **deletar** registros de ativos financeiros, como ações e fundos.

O front-end foi construído com **HTML**, **CSS** e **JavaScript puro**, utilizando **AJAX** para comunicação assíncrona com o back-end e troca de dados via **JSON**.

---

## 📌 Funcionalidades

- Exibição de tabela com os investimentos cadastrados
- Formulário para inclusão de novos ativos financeiros
- Envio e recebimento de dados via **AJAX**, sem recarregar a página
- Comunicação com o back-end utilizando **JSON**
- Validação básica de campos no navegador

---

## 📂 Estrutura dos arquivos

- `index.html`: Página principal da interface. Onde o cadastro de novos investimentos é efetuado.
- `lista.html`: Página onde são exibidos todos os investimentos cadastrados, permitindo gerenciá-los por meio das opções de edição e exclusão.
- `css/style.css`: Estilização da interface (layout, cores, responsividade)
- *(Obs: não há arquivos JS separados, todo o código está centralizado no HTML.)*

---

## ▶️ Como rodar

1. Crie uma pasta com o nome de `proj` em `htdocs`.
1. Clone o repositório em `htdocs/proj` no XAMPP.
3. Acesse o repositório do back-end e siga as instruções do arquivo `README.md`:
- Configuração da conexão com o banco
- Importação do banco via phpMyAdmin
- Posicionamento da pasta `investimentos-backend` corretamente em `htdocs/proj/`
