### Brian Gabriel Monroy - @brianUtn98

<!--
**brianUtn98/brianUtn98** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
-->
Hola! Soy Brian, y estoy estudiando Ingeniería en Sistemas en la UTN FRBA. Afortunadamente me encanta estudiar, y toda oportunidad para incorporar nuevos conocimientos es bienvenida. <br>
:point_right: [Curriculum Vitae](https://drive.google.com/file/d/15XWSxkPonHIeYY5x8hg2Ml0v-Y1qm-0a/view?usp=sharing)
- 🔭 Actualmente soy ayudante de la materia Paradigmas de Programación de la carrera Ing en Sistemas de Información.
- 🌱 Estoy haciendo cursos de [JavaScript](https://www.udemy.com/course/javascript-moderno-guia-definitiva-construye-10-proyectos/) y [Java](https://www.udemy.com/course/universidad-java-especialista-en-java-desde-cero-a-master/) en la plataforma Udemy y estudiando Ingles en un Instituto.
- 👯 Estoy buscando trabajo como Software Developer.
- 😄 Mi fuerte es el backend pero deseo aprender más sobre frontend.

Acá dejo mi portafolio! Pueden encontrar tanto proyectos propios como trabajos prácticos de mi carrera.

* [Gestion de proyectos](https://github.com/brianUtn98/GeSoc) Aplicación realizada con **Java + Maven + JPA + Hibernate + Spark** para la materia Diseño de Sistemas. El deploy de la aplicación fue en Heroku.
* [Delibird](https://github.com/brianUtn98/Delibird-SO-2020-1c-Omnidata) Sistema distribuido desarrollado en C. Utiliza conceptos como **Sockets, Sincronización de hilos (semáforos), planificación de hilos**. Consta de 4 módulos que se pueden comunicar entre sí mediante sockets.
* [Framework de Contratos](https://github.com/brianUtn98/tadp-2020-2c-brianMonroy/tree/master/ruby) Framework desarrollado en **Ruby**, que extiende el lenguaje permitiendo realizar chequeos de tipo, pre y post condiciones, invariantes entre otras características. Para el módulo de Metaprogramación de la materia Técnicas Avanzadas de Programación.
* [Adaptador de framework de dibujo](https://github.com/brianUtn98/tadp-2020-2c-brianMonroy/tree/master/scala) Aplicación desarrollada en **Scala**, que aprovecha el concepto de **parsers combinators** para analizar texto y combertirlo en objetos entendibles para un framework de dibujo. Para el módulo de Objeto-Funcional de la materia Técnicas Avanzadas de Programación.
* [Migración de datos y Modelo BI](https://github.com/brianUtn98/gdd-factura2) Scripts desarrollados con **Transact SQL**. Se trata de la migración y modelo de Inteligencia de Negocios de una tabla maestra que registra la facturación de concesionarias.
* [Intérprete para lenguaje Micro](https://github.com/brianUtn98/Sintaxis-y-Sem-ntica-2019/tree/master/TP%202/Compilador%20-%20Monroy%20-%20Bruniard) Intérprete básico para el lenguaje micro. Desarrolado con **C + Lex + Yacc**. Recibe un input de texto y lo analisa para determinar si es un código válido (pasando por la etapa de análisis sintáctico, léxico y semántico). Para el desarrollo del mismo se utilizaron expresiones regulares.
* [ABM Básico](https://github.com/brianUtn98/app-abm) Aplicación Web desarrolada con **HTML + JavaScript + PHP**. Cuenta con una base de datos, en la que se guardan datos. La aplicación permite la Alta Baja y Modificación de datos, además de visualización y filtrado de los mismos.
* [Carrito de compras](https://github.com/brianUtn98/progreso-javascript-moderno/tree/main/15-PROYECTO-Carrito) Carrito de compras básico realizado en el curso JavaScript Moderno de Udemy.
* [Formulario de envio Mail](https://github.com/brianUtn98/progreso-javascript-moderno/tree/main/16-PROYECTO-EnviarEmail) Formulario de envio de mails con validaciones realizado en el curso JavaScript Moderno de Udemy.
* [Aportes como docente](https://github.com/brianUtn98/Material-de-cursada) Parciales resueltos, ejercicios en clase y tutoriales realizados para los cursos en los que ayudo en la cátedra de Paradigmas de Programación.

![brianUtn98's github stats](https://github-readme-stats.vercel.app/api?username=brianUtn98&show_icons=true&theme=tokyonight)  

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=brianUtn98&layout=compact&langs_count=8)](https://github.com/anuraghazra/github-readme-stats)
    
[![GitHub followers](https://img.shields.io/github/followers/brianUtn98?label=Follow&style=social)](https://github.com/brianUtn98)

<!doctype html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width">
<title>jQuery & CSS Skills Bar</title>
<link href="css/style.css" rel="stylesheet">

<script src="js/jquery-2.1.4.min.js"></script>
<script src="js/skill.bars.jquery.js"></script>

<script>

$(document).ready(function(){
	
	$('.skillbar').skillBars({
		from: 0,
		speed: 4000, 
		interval: 100,
		decimals: 0,
	});
	
});

</script>

<style>

/** github btn style**/
.view_github_btn
{
	width:100%;
	display:inline-block;
	text-align:center;
	margin:15px 0 30px 0;
}
.view_github_btn a
{
	border-color: #cbcbcb #b7b7b7 #b3b3b3;
    border-radius: 30px;
    border-style: solid;
    border-width: 1px;
    box-shadow: 0 1px 5px #e8e8e8;
    color: #303030;
    display: inline-block;
    font-size: 15px;
    font-weight: bold;
    line-height: 25px;
    padding: 12px 10px 12px 20px;
    width: 179px;
	text-decoration:none;
	background: url(http://umarwebdeveloper.github.io/images/octocat-icon.png) no-repeat 10% center;
}
/** github btn style**/
</style>

</head>

<body>

<div class="wrapper">
    <h1>jQuery & CSS Skills Bar</h1>
    
    <span class="view_github_btn"><a href="https://github.com/umarwebdeveloper/jquery-css-skills-bar">View On GitHub</a></span>
    
    <div class="skillbar" data-percent="98">
      <span class="skillbar-title" style="background: #d35400;">HTML5</span>
      <p class="skillbar-bar" style="background: #e67e22;"></p>
      <span class="skill-bar-percent"></span>
    </div>
    <!-- End Skill Bar -->
    
    <div class="skillbar" data-percent="99">
      <span class="skillbar-title" style="background: #2980b9;">CSS3</span>
      <p class="skillbar-bar" style="background: #3498db;"></p>
      <span class="skill-bar-percent"></span>
    </div>
    <!-- End Skill Bar -->
    
    <div class="skillbar" data-percent="95">
      <span class="skillbar-title" style="background: #2c3e50;">jQuery</span>
      <p class="skillbar-bar" style="background: #2c3e50;"></p>
      <span class="skill-bar-percent"></span>
    </div>
    <!-- End Skill Bar -->
    
    <div class="skillbar" data-percent="70">
      <span class="skillbar-title" style="background: #46465e;">PHP</span>
      <p class="skillbar-bar" style="background: #5a68a5;"></p>
      <span class="skill-bar-percent"></span>
    </div>
    <!-- End Skill Bar -->
</div>

</body>
</html>
