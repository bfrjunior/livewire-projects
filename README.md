# 5 laravel Livewire Projects

## 🚀 Começando

1.Clonar o projeto

2.Acesse o diretório raiz do projeto e execute composer install e npm install

3.Crie um arquivo .env e copie o conteúdo de .env.example

4.Execute php artisan key:generate --ansi no terminal

5.Crie o arquivo de banco de dados database/database.sqlite

6.Execute as migrações com o comando php artisan migrate

7.Inicie o projeto executando php artisan serve

8.Inicie o servidor Vite (para servir arquivos CSS e JS) executando npm run dev
##
## Project #1 - Contador Simples


Um único número de contador com botões + e - para aumentar ou diminuir o número. O exemplo mais simples de como você pode criar uma página dinâmica sem escrever JavaScript.
![Alt text](storage/app/public/img-project/menos.PNG)
![Alt text](storage/app/public/img-project/plus.PNG)
## Project #2 - Calculadora

Uma calculadora muito simples com operações de +, -, *, /, %. Ela possui duas entradas e um menu suspenso para a operação, além do botão = para calcular o resultado.
![Alt text](storage/app/public/img-project/mult.PNG)
![Alt text](storage/app/public/img-project/menucal.PNG)
## Project #3 - Simples ToDo List

Aplicação feita milhões de vezes. Neste caso, ela foi feita com o Livewire e um modelo Eloquent. Os dados são salvos, atualizados e excluídos do banco de dados.
![Alt text](storage/app/public/img-project/todo.PNG)
## Project #4 - Cascading dropdown
Dropdowns dependentes para continentes e países, você escolhe um continente e os países são filtrados com base nessa seleção. Um indicador de carregamento é exibido enquanto os países estão sendo carregados.
![Alt text](storage/app/public/img-project/cas.PNG)
![Alt text](storage/app/public/img-project/cdown.PNG)
## Project #5 - Pesquisa de produtos e paginação
Temos uma tabela de produtos com várias colunas, links de paginação e um campo de entrada para pesquisa. Os dados vêm do banco de dados e a palavra-chave de pesquisa é salva na URL. Portanto, quando você atualiza a página, o conteúdo é filtrado com base nessa palavra-chave.
![Alt text](storage/app/public/img-project/product.PNG)
![Alt text](storage/app/public/img-project/find.PNG)
## Upload de Imagens
Possibilidade de enviar várias imagens.
Pré-visualização das imagens antes de enviar.
As imagens são validadas ao enviar.
As imagens são salvas no sistema de arquivos local.
Todas as imagens enviadas são exibidas mesmo após a atualização da página.
![Alt text](storage/app/public/img-project/img.PNG)
## Validação de Formulário de Registro
Formulário de registro muito simples com os seguintes campos:

Função do cliente (lista de rádio com duas opções: cliente, fornecedor),
Primeiro nome
Sobrenome
E-mail
Senha
Nome da empresa
Número de IVA
Os campos "Nome da empresa" e "Número de IVA" só são exibidos e são obrigatórios se a função for "fornecedor". Quando você envia o formulário, mensagens de validação são exibidas. Assim que você digita nos campos, a validação em tempo real ocorre e as mensagens de erro são atualizadas ou ocultadas. Cada campo tem um atraso na validação para evitar o envio de muitas solicitações AJAX.

Quando a validação é bem-sucedida, uma mensagem de sessão é exibida.
![Alt text](<storage/app/public/img-project/register error.PNG>)
![Alt text](storage/app/public/img-project/success.PNG)
## 🛠️ Construído com
* Mysql
* [Laravel](https://laravel.com/)
* [PHP](https://www.php.net/)
