# LAEGestor e LAEVendas - Sistema de Gestão e Vendas

Bem-vindo ao sistema **LAEGestor e LAEVendas**. Este projeto foi desenvolvido como uma solução de gestão de vendas e controle de estoque. Ele está completamente funcional e disponível para acesso online. Este sistema foi construído utilizando **HTML, PHP, MySQL, CSS, Bootstrap e JavaScript**.

---

## Acesso ao Sistema

O sistema possui duas interfaces principais para diferentes perfis de usuário:

### 1. **LAEGestor (Administração)**

O painel de administração permite que você gerencie todos os aspectos do sistema, incluindo usuários, produtos, vendas e configurações.

- **Link para Login (Admin):** [Acessar LAEGestor](http://laegestor.myartsonline.com/)
- **Credenciais de Login (Admin):**
  - **Usuário:** admin
  - **Senha:** 60ed3207

### 2. **LAEVendas (Vendedores)**

O painel de vendas é destinado aos vendedores, permitindo que registrem vendas e gerenciem transações de forma simples.

- **Link para Login (Vendedor):** [Acessar LAEVendas](http://laevendas.myartsonline.com/)
- **Credenciais de Login (Vendedor):**
  - **Usuário:** vendedor
  - **Senha:** vendedor

---

## Configuração do Sistema

Para que o sistema funcione corretamente em seu ambiente, é necessário realizar algumas configurações iniciais.

### 1. **Configuração do Banco de Dados**

O sistema utiliza o MySQL para armazenar as informações. Para configurar a conexão ao banco de dados, você precisa alterar as credenciais no arquivo `db.php` localizado nas pastas de ambos os sistemas **LAEGestor** e **LAEVendas**.

- **Arquivo de Configuração:**
  - Nos arquivos : `db.php`
  - Modifique as configurações de **host**, **usuário**, **senha** e **nome do banco de dados** para que correspondam ao seu ambiente.

### 2. **Requisitos Técnicos**

O sistema foi desenvolvido utilizando as seguintes tecnologias:

- **Frontend**: HTML, CSS (Bootstrap), JavaScript
- **Backend**: PHP (com suporte a MySQL)
- **Banco de Dados**: MySQL

Certifique-se de que o servidor web (Apache ou Nginx) tenha suporte a **PHP** e esteja configurado para executar o sistema adequadamente. O sistema também utiliza o **Bootstrap** para estilização responsiva, garantindo que o layout seja adaptável a diferentes dispositivos.

---

## Aviso de Segurança

Devido à hospedagem gratuita utilizada, o sistema pode ser sinalizado como "inseguro" ao ser acessado, já que o serviço não oferece suporte a **SSL** (Secure Socket Layer). Embora isso não comprometa a integridade do sistema, é importante que você tenha em mente que a comunicação entre o navegador e o servidor não é criptografada.

Se você planeja usar o sistema em um ambiente de produção ou com dados sensíveis, recomendo a implementação de **SSL** para garantir a segurança da comunicação.

---

## Contato

Caso tenha alguma dúvida ou precise de suporte, estou à disposição para ajudar:

- **Nome:** Alcedo Madruga
- **Telefone:** +244 921 703 737
- **E-mail:** alcedodev05@gmail.com

---

## Guia de Uso

1. **Acesse o Link de Acesso**:
   - Para o **LAEGestor (Admin)**: [http://laegestor.myartsonline.com/](http://laegestor.myartsonline.com/)
   - Para o **LAEVendas (Vendedor)**: [http://laevendas.myartsonline.com/](http://laevendas.myartsonline.com/)

2. **Login**:
   - Para **Admin**: Insira as credenciais de administrador.
   - Para **Vendedor**: Insira as credenciais de vendedor.

3. **Navegação**:
   - **LAEGestor**: Aqui, você pode gerenciar usuários, produtos, vendas e configurações do sistema.
   - **LAEVendas**: O painel de vendas permite que os vendedores registrem novas vendas e visualizem o estoque.

---

## Sobre o Projeto

Este sistema foi desenvolvido para ser uma solução simples e eficiente para a gestão de vendas e controle de estoque. A interface foi projetada com o objetivo de ser intuitiva e fácil de usar tanto para administradores quanto para vendedores.

---

## Licença

Este projeto é de **licença gratuita**. Se desejar obter o código-fonte ou quiser colaborar no desenvolvimento, entre em contato comigo pelo e-mail: [alcedodev05@gmail.com](mailto:alcedodev05@gmail.com).

---

## Como Contribuir

Se você quiser contribuir para o projeto, basta realizar um **fork** deste repositório e fazer as modificações que achar necessárias. As **contribuições** são sempre bem-vindas e apreciadas!

