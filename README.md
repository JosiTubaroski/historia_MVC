<div> 
<p><a href="https://github.com/JosiTubaroski/Web_API_CriarProjeto/blob/main/README.md">Home</a></p>
</div> 

# 📜 História do MVC (Model-View-Controller)

O <b>MVC (Model-View-Controller)</b> foi criado na década de <b>1970</b> por <b>Trygve Reenskaug</b>, um cientista da computação norueguês. Ele desenvoleu esse conceito enquanto trabalhava na <b>Xerox PARC</b>, um dos laboratórios mais inovadores da época.

O objetivo do MVC era criar um <b>padão arquitetural</b> para facilitar a organização do código e a interação entre diferentes partes de um software. O conceito começou a ser popularizado nos anos 1980 e 1990, sendo adotado em frameworks como Smalltalk, Java (Spring MVC) e, mais tarde, no .NET (ASP.NET MVC).

# 🔹 Problemas que o MVC Resolve

Antes do MVC, muitos sistemas eram criados de forma monolítica, com código desorganizado e difícil de manter. O MVC resolve esses problemas ao separar as responsabilidades em três camadas principais:

### 1️⃣ Problema: Código Bagunçado e Difícil de Manter

🔹 Solução: O MVC divide a aplicação em três camadas distintas <b>(Model, View e Controller),</b> tornando o código mais modular e reutilizável.

### 2️⃣ Problema: Difícil Separar Regra de Negócio e Interface

🔹 Solução: No MVC, a regra de negócio fica no Model, a interface no View e a lógica de controle no Controller, tornando o código mais limpo e organizado.

### 3️⃣ Problema: Dificuldade em Testar Código

🔹 Solução: Como o MVC separa as camadas, podemos testar o Model e o Controller de forma independente, sem precisar da interface gráfica (View).

### 4️⃣ Problema: Aplicações Difíceis de Expandir

🔹 Solução: Com o MVC, é mais fácil adicionar novas funcionalidades sem quebrar o código existente, pois cada parte tem sua responsabilidade bem definida.

# 🔹 Como o MVC Funciona?

## 📌 O padrão MVC divide uma aplicação em três componentes principais:

### 1️⃣ Model 🗄️ → Representa os dados e regras de negócio.
### 2️⃣ View 🖥️ → Responsável pela interface com o usuário.
### 3️⃣ Controller 🎮 → Faz a comunicação entre o Model e a View.

## Fluxo de uma Requisição no MVC

1. O usuário faz uma requisição (ex: clica em um botão ou acessa uma URL).
2. O Controller recebe a requisição, processa a lógica necessária e chama o Model.
3. O Model acessa os dados e retorna a resposta ao Controller.
4. O Controller envia os dados para a View, que renderiza a interface para o usuário.

#  MVC no .NET

O <b>ASP.NET MVC</b> foi lançado pela Microsoft em 2009 e trouxe uma alternativa mais flexível ao <b>ASP.NET Web Forms</b>. Hoje, o MVC está integrado ao ASP.NET Core, permitindo a criação de APIs e aplicações web modernas.

# 🔹 Conclusão

### ✅ Código mais organizado e fácil de manter.
### ✅ Facilidade na criação de testes automatizados.
### ✅ Separação clara entre lógica de negócio e interface.
### ✅ Facilidade na expansão e manutenção do sistema.

O MVC continua sendo um dos padrões mais utilizados no desenvolvimento web até hoje! 🚀🔥

# O MVC é um conceito?

Exatamente! ✅ O MVC (Model-View-Controller) é um padrão de arquitetura de software, ou seja, um conceito que define uma forma organizada de estruturar aplicações. Ele não é uma tecnologia específica, mas um modelo de design que pode ser implementado em diversas linguagens e frameworks, como:

- ASP.NET MVC (C#)
- Spring MVC (Java)
- Ruby on Rails (Ruby)
- Django (Python)
- Laravel (PHP)

  Cada tecnologia pode ter sua própria forma de implementar o MVC, mas o conceito principal — separação de responsabilidades entre Model (dados), View (interface) e Controller (lógica de controle) — permanece o mesmo.

  Portanto, ao dizer que uma aplicação segue o MVC, significa que ela adota esse padrão para organizar seu código, tornando-o mais modular, reutilizável e testável. 🚀

# Como o .net8 utiliza o MVC?

O .NET 8 adota o MVC (Model-View-Controller) através do ASP.NET Core MVC, que permite criar aplicações web organizadas com separação de responsabilidades.
O ASP.NET Core MVC é baseado em controllers, views e models, permitindo que desenvolvedores construam APIs e aplicações web de forma estruturada.

# 📌 Estrutura do MVC no .NET 8

Uma aplicação ASP.NET Core MVC segue esta estrutura de pastas:

<img src="https://github.com/JosiTubaroski/WEB-API-com-.NET-8-e-SQL-Server/blob/main/img/curiosidades/01_Estrutura_MVC.png"/>

# 🔹 Como o MVC funciona no .NET 8?

### 1️⃣ O usuário faz uma requisição (HTTP GET, POST, etc.)

📌 Exemplo: O usuário acessa /Home/Index.

### 2️⃣ O Controller processa a requisição

🔹 O ASP.NET Core MVC direciona a requisição para o método correspondente no Controller.

<img src="https://github.com/JosiTubaroski/WEB-API-com-.NET-8-e-SQL-Server/blob/main/img/curiosidades/02_Controler.png"/>

➡️ O método Index() retorna uma View.

### 3️⃣ O Model trata os dados

🔹 O Model contém a regra de negócio e os dados.

<img src="https://github.com/JosiTubaroski/WEB-API-com-.NET-8-e-SQL-Server/blob/main/img/curiosidades/03_Models.png"/>

### 4️⃣ A View exibe os dados

🔹 A View utiliza Razor Pages (.cshtml) para exibir os dados na interface.

<img src="https://github.com/JosiTubaroski/WEB-API-com-.NET-8-e-SQL-Server/blob/main/img/curiosidades/04_Views.png"/>

# 🔹 Como o .NET 8 Implementa o MVC?

No .NET 8, o MVC é configurado no arquivo Program.cs:

<img src="https://github.com/JosiTubaroski/WEB-API-com-.NET-8-e-SQL-Server/blob/main/img/curiosidades/04_Program-CS.png"/>


