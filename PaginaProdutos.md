
------------------------------------------------------
| Header + Menu                                        |
------------------------------------------------------
| Título: Produtos                                    |
------------------------------------------------------
| Filtros à esquerda (categoria, faixa de preço)     |
|                                                     |
| Lista de produtos (cards: imagem, nome, preço, botão "Ver detalhes") |
| (grid responsivo com 3-4 cards por linha)           |
------------------------------------------------------
| Footer                                              |
------------------------------------------------------


# Guia do Sistema de Cadastro de Produtos - Ferragem na Mao

## Visão Geral

Esta página permite o cadastro e a visualização dinâmica de produtos para a loja Ferragem na Mao. Você pode inserir nome, categoria e preço dos produtos, além de editar os dados cadastrados diretamente na lista.

---

## Funcionalidades

- **Cadastro de produtos:** Insira nome, categoria e preço.
- **Visualização dinâmica:** Os produtos cadastrados aparecem instantaneamente em uma galeria.
- **Edição inline:** É possível editar os dados do produto clicando em "Editar" e salvar as alterações.
- **Navegação simples:** Links para navegar entre páginas de produtos e clientes.
- **Design responsivo:** Adaptado para diferentes dispositivos.

---

## Como Usar

1. Preencha o formulário com os dados do produto:
   - Nome do Produto (obrigatório)
   - Categoria (obrigatório)
   - Preço (obrigatório, aceita valores decimais)

2. Clique no botão **Cadastrar**.

3. O produto aparecerá na seção **Produtos Cadastrados** como um cartão com imagem, nome, categoria e preço.

4. Para editar um produto:
   - Clique no botão **Editar** no cartão correspondente.
   - Altere os dados diretamente nos campos exibidos.
   - Clique em **Salvar** para confirmar as mudanças.

---

## Detalhes Técnicos

- O formulário utiliza JavaScript para evitar recarregar a página ao cadastrar um produto.
- Cada produto é exibido em um cartão com uma imagem padrão (caminho fixo local).
- Os campos do produto são editáveis via atributos `contenteditable`, ativados/desativados pelos botões "Editar" e "Salvar".
- A edição altera apenas a exibição atual; não há persistência dos dados em banco ou arquivo.
- O layout e estilo são controlados por um arquivo CSS externo (`style.css`).

---

## Suporte

Se precisar de ajuda ou quiser reportar problemas, entre em contato:

- Email: suporte@ferragemnamao.com  
- Telefone: (51) 3451-7002  
- WhatsApp: (51) 9998981-8197  

---

## Direitos Autorais

© 2025 Ferragem na Mao - Todos os direitos reservados.

---

*Agradecemos por utilizar nosso sistema de cadastro de produtos!*
