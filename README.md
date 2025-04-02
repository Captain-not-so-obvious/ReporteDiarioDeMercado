# Reporte Diario De Mercado

Código que faz envio das informações de mercado para e-mail selecionado.

## Descrição

Este projeto tem como objetivo coletar informações diárias do mercado e enviar um relatório por e-mail para destinatários selecionados. Ele foi desenvolvido com o intuito de automatizar o processo de monitoramento de mercado, permitindo que os usuários recebam atualizações diárias diretamente em suas caixas de entrada.

## Funcionalidades

- Coleta de informações diárias do mercado financeiro
- Geração de relatórios automáticos
- Envio de relatórios por e-mail para destinatários selecionados

## Tecnologias Utilizadas

- Python

## Instalação

Siga os passos abaixo para configurar o projeto em sua máquina local:

1. Clone o repositório:
   ```sh
   git clone https://github.com/Captain-not-so-obvious/ReporteDiarioDeMercado.git
   ```

2. Navegue até o diretório do projeto:
   ```sh
   cd ReporteDiarioDeMercado
   ```

3. Instale as dependências:
   ```sh
   pip install pandas
   pip matplotlib
   pip mplcyberpunk
   ```

## Configuração

Antes de executar o projeto, certifique-se de configurar os parâmetros necessários:

1. Configure as variáveis de ambiente:
   - `EMAIL_HOST`: Servidor SMTP para envio de e-mails
   - `EMAIL_PORT`: Porta do servidor SMTP
   - `EMAIL_HOST_USER`: Usuário para autenticação no servidor SMTP
   - `EMAIL_HOST_PASSWORD`: Senha para autenticação no servidor SMTP
   - `EMAIL_RECIPIENTS`: Lista de destinatários dos relatórios

2. Caso não queira configurar seu e-mail de forma automática, o código vai pegar o e-mail logado no seu Outlook para fazer o envio para o e-mail selecionado no código

## Contribuição

Se você deseja contribuir com o projeto, siga os passos abaixo:

1. Faça um fork do repositório
2. Crie uma nova branch com a sua feature:
   ```sh
   git checkout -b minha-feature
   ```
3. Faça o commit das suas alterações:
   ```sh
   git commit -m 'Adiciona minha feature'
   ```
4. Faça o push para a branch:
   ```sh
   git push origin minha-feature
   ```
5. Abra um Pull Request
