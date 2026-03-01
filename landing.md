---
title: Proyectos
layout: landing
image: assets/images/Mapas.jpg
---

<div id="main">

<section id="one">
	<div class="inner">
		<p>En esta sección describo brevemente algunos proyectos que he realizado a lo largo de mi carrera. Todos están vinculados con sus respectivos repositorios en GitHub, por lo que les invito a conocer más sobre ellos si cualquiera les llama la atención.</p>
	</div>
</section>

<section id="two" class="spotlights">
	
    <section>
		<a href="https://github.com/carlarhdz/INEGIShapefiles" class="image">
			<img src="{% link assets/images/Shapefiles.png %}" alt="" data-position="center center" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>INEGI Shapefiles</h3>
				</header>
				<p>Este fue un proyecto que realicé con otros dos compañeros míos. Consistió en impartir una clase sobre Shapefiles, archivos que usan en el INEGI para representar datos geoespaciales vectoriales. Primero hablamos un poco sobre los tipos de geometría que se pueden representar así como de la estructura de un Shapefile, y luego pasamos a la parte práctica en donde mostramos las funciones geométricas básicas así como otras más avanzadas. </p>
				<ul class="actions">
					<li><a href="https://github.com/carlarhdz/INEGIShapefiles" class="button">Ver más</a></li>
				</ul>
			</div>
		</div>
	</section>

    <section>
		<a href="https://github.com/ULB-INFO-F-422/pose-estimation-from-emg-signal-team-17" class="image">
			<img src="{% link assets/images/EMG.png %}" alt="" data-position="center center" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Predicción de Movimientos con Señales EMG</h3>
				</header>
				<p>Usamos Machine Learning para predecir poses de mano a partir de señales electromiográficas (EMG), con posibles aplicaciones en el control de prótesis. Entrenamos modelos como Random Forests, Gradient Boosting y SVR utilizando características en el dominio del tiempo y matrices de covarianza riemannianas. Finalmente, utilizamos técnicas de ensemble para superar el rendimiento de los algoritmos individuales.</p>
				<ul class="actions">
					<li><a href="https://github.com/ULB-INFO-F-422/pose-estimation-from-emg-signal-team-17" class="button">Ver más</a></li>
				</ul>
			</div>
		</div>
	</section>

	<section>
        <a href="https://github.com/ULB-INFO-H-515/distributed-retrieval-augmented-generation-team-7">
            <img src="{% link assets/images/Vector.png %}" alt="" data-position="center center" />
        </a>
        <div class="content">
            <div class="inner">
                <header class="major">
                    <h3>Sistema RAG Distribuido con Apache Spark</h3>
                </header>
				<p>Creamos un sistema de Generación Aumentada por Recuperación (RAG) con Apache Spark, para procesar grandes volúmenes de texto y generar bancos de preguntas de examen. Para ello, implementamos un pipeline con chunking en paralelo y generación de embeddings. Evaluamos el impacto de diferentes métricas en la recuperación de contexto para alimentar un modelo de lenguaje, logrando generar preguntas complejas sobre sistemas distribuidos.</p>
				
                <ul class="actions">
                    <li><a href="https://github.com/ULB-INFO-H-515/distributed-retrieval-augmented-generation-team-7" class="button">Ver más</a></li>
                </ul>
            </div>
        </div>
    </section>

	<section>
        <a href="https://github.com/garcia-gayou/stadium_evac" class="image">
            <img src="{% link assets/images/Evacuacion.png %}" alt="" data-position="center center" />
        </a>
        <div class="content">
            <div class="inner">
                <header class="major">
                    <h3>Simulación de Evacuación: Estadio GNP</h3>
                </header>
                <p>Este proyecto simula la evacuación de emergencia del Estadio GNP utilizando modelado basado en agentes y la dinámica de multitudes del modelo de fuerza social (Social Force Model). Cada agente posee características únicas y navega hacia las salidas evitando colisiones con obstáculos y otras personas. El objetivo fue analizar el comportamiento de multitudes bajo estrés, identificar cuellos de botella y evaluar la efectividad de los protocolos de seguridad en eventos masivos.</p>
                <ul class="actions">
                    <li><a href="https://github.com/garcia-gayou/stadium_evac" class="button">Ver más</a></li>
                </ul>
            </div>
        </div>
    </section>

</section>
</div>