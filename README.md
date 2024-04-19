# LaravelStart

Para criar um projeto Laravel com um banco de dados já configurado, você pode seguir estes passos:

Instale o Composer: Se ainda não tiver o Composer instalado, você pode baixá-lo e instalá-lo a partir do site oficial: https://getcomposer.org/.
Instale o Laravel: Abra um terminal ou prompt de comando e execute o seguinte comando para instalar o Laravel globalmente:

composer global require laravel/installer

Crie um novo projeto Laravel: Execute o seguinte comando para criar um novo projeto Laravel:
arduino
laravel new NomeDoProjeto
Isso criará um novo diretório chamado NomeDoProjeto com uma instalação padrão do Laravel.
Configure o Banco de Dados: Edite o arquivo .env no diretório raiz do seu projeto Laravel e configure as informações do banco de dados (como nome do banco, usuário, senha, etc.).
Criar as Tabelas do Banco de Dados: Você pode usar as migrações do Laravel para criar as tabelas do banco de dados. Execute o comando:

php artisan migrate

Isso executará todas as migrações pendentes e criará as tabelas no banco de dados conforme definido nos arquivos de migração localizados em database/migrations.
Opcional: Popular o Banco de Dados: Se desejar, você pode criar seeds para popular seu banco de dados com dados de amostra. Você pode executar os seeds usando o comando:

php artisan db:seed
