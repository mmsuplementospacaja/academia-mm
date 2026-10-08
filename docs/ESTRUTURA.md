# Estrutura para expansão

A versão inicial mantém Atendimento Consultivo no `index.html`, como solicitado, sem introduzir um catálogo vazio.

Quando houver um segundo treinamento aprovado:

1. Mover o treinamento atual para `treinamentos/atendimento-consultivo/index.html`.
2. Criar cada novo treinamento em `treinamentos/<nome-curto>/index.html`.
3. Transformar a página principal em catálogo, com links para os treinamentos e um caminho de volta para a Academia.
4. Extrair apenas estilos e comportamentos reutilizáveis para `assets/css/` e `assets/js/`.
5. Manter os recursos e links relativos, compatíveis com o prefixo `/academia-mm/` do GitHub Pages.
6. Caso seja introduzido armazenamento de progresso, separar as chaves por treinamento e versão. Não há registro de progresso nesta versão.

## Manutenção

- Publicação automática a partir da branch `main`, pasta raiz.
- Não adicionar senhas ou dados individuais de colaboradores: esta versão é pública.
- Novos conteúdos comerciais exigem revisão da MM.
- O histórico do Git registra alterações e permite recuperar versões anteriores.
- Controle de acesso real, gestão de usuários e resultados de avaliações exigem uma solução de autenticação e armazenamento além deste site estático.
