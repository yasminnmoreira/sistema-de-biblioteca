# sistema-de-biblioteca 
# 📚 Sistema de Biblioteca Online 

Este é um projeto simples de sistema de gerenciamento de biblioteca online, podendo salvar livros, excluir e etc

---

## 🚀 Tecnologias Utilizadas

    * Gerenciamento de dados e autenticação (se implementada).
    * Exposição automática da API REST para o CRUD.
  
* **Linguagem SQL:** Para modelagem e criação de recursos.

---

## ✨ Recursos e Requisitos Atendidos

O sistema foi desenvolvido seguindo os requisitos obrigatórios de projeto, destacando:

1.  **Modelagem em 3FN:** O banco de dados é estruturado com tabelas normalizadas (`livros`, `autores`, `categorias`, `usuarios`, `emprestimos`) para evitar redundância e garantir a integridade dos dados.
2.  **Múltiplas Relações:** Uso de chaves estrangeiras (`Foreign Keys`) nas tabelas (`livros` se relaciona com `autores` e `categorias`; `emprestimos` se relaciona com `livros` e `usuarios`).
3.  **CRUD Completo:** Implementação de Cadastro, Listagem, Edição e Exclusão para a gestão de livros.
    * **View:** Criação da `vw_catalogo_completo` para listagem de livros.
    ```

# ou yarn dev
