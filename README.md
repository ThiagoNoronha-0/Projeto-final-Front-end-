📌 Funcionalidades do Projeto
🛒 🛍️ Catálogo de Produtos

Exibe produtos com imagem, nome e preço

Botão Adicionar envia o item ao carrinho

Layout responsivo em grid

🛍️ Carrinho de Compras

Adiciona itens em tempo real

Exibe lista dos produtos selecionados

Permite remover itens individualmente

📧 Formulário de Contato

Campos: nome, e-mail, assunto e mensagem

Validação completa em JavaScript

Impede envio com dados inválidos

Exibe alerta de sucesso

🏷️ Menu de Navegação

Links para Produtos, Sobre e Contato

Navegação interna suave via âncoras

📱 Responsividade

Layout adaptativo via grid e auto-fit

Funciona bem em computadores, tablets e celulares

📂 Estrutura do Projeto
├── index.html
├── style.css
└── script.js

🧠 Tecnologias Utilizadas

HTML5 – Estruturação das páginas

CSS3 – Estilização e responsividade

JavaScript (Vanilla) – Lógica do carrinho e validação

🚀 Como Executar o Projeto

Baixe ou clone este repositório:

git clone https://github.com/usuario/com-pc.git


Abra o arquivo:

index.html


O site já estará funcionando — não precisa de servidor.

📝 Destaques do Código
🔹 Adicionar item ao carrinho
function addItemCarrinho(produto) {
    itensCarrinho.push(produto);
    mostrarCarrinho();
}

🔹 Excluir item
btn.onclick = () => {
    itensCarrinho.splice(i, 1);
    mostrarCarrinho();
};

🔹 Validação do formulário
if (email === "" || !email.includes("@")) {
    alert("Email inválido.");
    return false;
}

📸 Layout do Projeto

Cabeçalho com navegação

Sessão de produtos em grid

Formulário de contato centralizado

Carrinho funcional

Rodapé com informações da loja

(Se quiser, posso criar um banner ou imagens para colocar aqui!)

📜 Licença

Este projeto é livre para estudo, uso e modificações.
