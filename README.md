# Armarinho Virtual

O Armarinho Virtual é um organizador pessoal para acompanhar meus projetos de crochê em um só lugar.

## Objetivo

O projeto foi criado para concentrar projetos atuais, futuros e concluídos, facilitando a organização da minha rotina de crochê e permitindo que eu acompanhe minha evolução ao longo do tempo.

Além de registrar o que já foi feito, o organizador ajuda principalmente no planejamento das próximas peças e na hora de comprar linhas nos armarinhos. Assim, consigo consultar quais projetos estão planejados, quais linhas já tenho em estoque e quais materiais ainda preciso adquirir.

## O que posso organizar

- Projetos planejados, em andamento e concluídos.
- Nome, status, anotações e foto de cada projeto.
- Linhas cadastradas por cor, espessura, estoque e observações.
- Relação entre as linhas disponíveis e os projetos que utilizam cada uma.
- Histórico visual da evolução dos trabalhos realizados.

## Armazenamento dos dados

Os dados são armazenados localmente no navegador, sem depender de uma conta ou de um servidor externo.

- O armazenamento principal utiliza IndexedDB, adequado para guardar projetos, anotações e fotos.
- O `localStorage` é mantido como cópia de segurança local e fallback.
- A opção de exportar permite salvar todos os dados em um arquivo `.json`.
- A opção de importar permite recuperar os dados em outro navegador ou dispositivo.

Recomenda-se exportar os dados periodicamente para manter uma cópia independente do navegador.

## Como usar

Abra o arquivo `index.html` no navegador. Depois, é possível:

1. Cadastrar as linhas disponíveis no estoque.
2. Criar projetos e associar as linhas necessárias.
3. Atualizar o status conforme cada peça evolui.
4. Adicionar fotos e anotações para registrar o processo.
5. Exportar os dados antes de trocar de dispositivo ou navegador.

## Tecnologias

- HTML
- CSS
- JavaScript
- IndexedDB
- localStorage
- Tabler Icons

## Propósito pessoal

Mais do que uma lista de tarefas, este projeto funciona como um pequeno diário de crochê: ajuda a transformar ideias em projetos, evita compras desnecessárias de linhas e registra cada etapa do meu aprendizado e da minha evolução.
