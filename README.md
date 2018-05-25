# laravel-docker


#### Step 1 — Clone/Create Laravel Project

Copy the following files in the root of the project

#### Step 2 — Install dependencies

<code>docker run --rm --interactive --tty --volume $PWD:/app composer install</code>

#### Step 3— Start the services

<code>docker-compose up </code>

#### Laravel CLI 

<code> docker-compose exec app php "comand" </code>
