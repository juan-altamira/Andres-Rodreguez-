<script lang="ts">
	// Smooth scroll to section
	function scrollToSection(id: string) {
		const element = document.getElementById(id);
		if (element) {
			element.scrollIntoView({ behavior: 'smooth' });
		}
	}
</script>

<!-- Hero Section -->
<section class="min-h-screen flex items-center justify-center bg-gradient-to-b from-[#0B0B0F] via-[#1a1a1f] to-[#0B0B0F] relative overflow-hidden">
	<div class="absolute inset-0 bg-[radial-gradient(circle_at_30%_50%,rgba(249,115,22,0.1),transparent_70%)]"></div>
	<div class="section-container text-center relative z-10">
		<h1 class="font-['Poppins'] font-bold text-5xl md:text-6xl lg:text-7xl mb-6 bg-gradient-to-r from-white via-white to-orange-200 bg-clip-text text-transparent leading-tight animate-fade-in">
			Transforma tu cuerpo y tu mente con un programa guiado paso a paso
		</h1>
		<p class="font-['Inter'] text-xl md:text-2xl text-gray-300 mb-8 max-w-3xl mx-auto leading-relaxed">
			Para personas que están cansadas de probar rutinas sueltas, dietas extremas o motivación de una semana… y quieren un cambio real como los que ves aquí abajo.
		</p>
		
		<ul class="space-y-3 mb-12 text-lg md:text-xl text-gray-300 max-w-2xl mx-auto">
			<li class="flex items-center justify-center gap-3">
				<span class="text-[#F97316] text-2xl">✓</span>
				<span>Entrenamiento + trabajo mental</span>
			</li>
			<li class="flex items-center justify-center gap-3">
				<span class="text-[#F97316] text-2xl">✓</span>
				<span>Acompañamiento de un coach que ya vive este estilo de vida</span>
			</li>
			<li class="flex items-center justify-center gap-3">
				<span class="text-[#F97316] text-2xl">✓</span>
				<span>Enfoque realista, sin promesas mágicas</span>
			</li>
		</ul>
		
		<div class="flex flex-col sm:flex-row gap-6 justify-center items-center">
			<a href="https://www.instagram.com/andresgareth39/" target="_blank" rel="noopener noreferrer" class="btn-primary">
				Quiero ver si encajo en el programa
			</a>
			<button onclick={() => scrollToSection('historias')} class="btn-secondary">
				Ver historias de cambio real →
			</button>
		</div>
	</div>
</section>

<!-- "Esto es para vos si..." Section -->
<section id="para-vos" class="bg-[#111117] py-10 md:py-20">
	<div class="section-container">
		<h2 class="font-['Poppins'] font-bold text-4xl md:text-5xl mb-12 text-center">
			Este programa es para ti si…
		</h2>
		
		<div class="grid md:grid-cols-2 gap-6 max-w-4xl mx-auto">
			<div class="bg-[#1a1a1f] p-6 rounded-2xl border border-gray-800 hover:border-[#F97316] transition-all duration-300 hover:scale-105">
				<p class="text-lg text-gray-300">
					Sientes que probaste de todo y siempre vuelves al mismo punto.
				</p>
			</div>
			<div class="bg-[#1a1a1f] p-6 rounded-2xl border border-gray-800 hover:border-[#F97316] transition-all duration-300 hover:scale-105">
				<p class="text-lg text-gray-300">
					Empiezas motivado, pero a la segunda semana pierdes el foco.
				</p>
			</div>
			<div class="bg-[#1a1a1f] p-6 rounded-2xl border border-gray-800 hover:border-[#F97316] transition-all duration-300 hover:scale-105">
				<p class="text-lg text-gray-300">
					Te cansaste de rutinas genéricas de internet que no están hechas para ti.
				</p>
			</div>
			<div class="bg-[#1a1a1f] p-6 rounded-2xl border border-gray-800 hover:border-[#F97316] transition-all duration-300 hover:scale-105">
				<p class="text-lg text-gray-300">
					Quieres cambiar tu físico, pero también tu cabeza y tu forma de mirarte.
				</p>
			</div>
			<div class="bg-[#1a1a1f] p-6 rounded-2xl border border-gray-800 hover:border-[#F97316] transition-all duration-300 hover:scale-105 md:col-span-2">
				<p class="text-lg text-gray-300">
					Valoras tener a alguien que te diga qué hacer y te acompañe en el proceso.
				</p>
			</div>
		</div>
		
		<p class="text-center text-xl md:text-2xl font-semibold text-[#F97316] mt-12">
			Si leíste esto y pensaste "ese soy yo", sigue leyendo.
		</p>
	</div>
</section>

<!-- Historias de cambio real -->
<section id="historias" class="py-10 md:py-20 bg-gradient-to-b from-[#0B0B0F] to-[#111117]">
	<div class="section-container">
		<h2 class="font-['Poppins'] font-bold text-4xl md:text-5xl mb-6 text-center">
			Cambios reales de personas reales
		</h2>
		<p class="text-center text-xl text-gray-300 mb-16 max-w-3xl mx-auto">
			Andrés no habla solo de teoría. En su equipo hay personas que decidieron dejar de posponer su cambio y hoy se ven y se sienten distinto.
		</p>
		
		<div class="space-y-12 max-w-4xl mx-auto">
			<!-- Cambio 1 -->
			<div class="bg-[#1a1a1f] rounded-3xl overflow-hidden border border-gray-800 hover:border-[#F97316] transition-all duration-300">
				<div class="md:flex">
					<div class="md:w-2/5 bg-gradient-to-br from-gray-800 to-gray-900 flex items-center justify-center p-12">
						<div class="text-center">
							<div class="text-6xl mb-4">💪</div>
							<p class="text-sm text-gray-400">Transformación física y mental</p>
						</div>
					</div>
					<div class="md:w-3/5 p-8">
						<h3 class="font-['Poppins'] font-bold text-2xl mb-4 text-[#F97316]">Cambio 1</h3>
						<p class="text-lg text-gray-300 mb-4">
							De sentirse pesado, cansado y sin energía… a recuperar movimiento, seguridad y ganas de entrenar.
						</p>
						<blockquote class="border-l-4 border-[#F97316] pl-4 italic text-gray-400">
							"Pensé que ya era tarde para mí. Hoy entreno, me miro al espejo y me reconozco de nuevo."
						</blockquote>
					</div>
				</div>
			</div>
			
			<!-- Cambio 2 - María José -->
			<div class="bg-[#1a1a1f] rounded-3xl overflow-hidden border border-gray-800 hover:border-[#F97316] transition-all duration-300">
				<div class="md:flex md:flex-row-reverse">
					<div class="md:w-2/5 bg-gradient-to-br from-gray-800 to-gray-900 flex items-center justify-center p-12">
						<div class="text-center">
							<div class="text-6xl mb-4">🔥</div>
							<p class="text-sm text-gray-400">Tonificación y fuerza</p>
						</div>
					</div>
					<div class="md:w-3/5 p-8">
						<h3 class="font-['Poppins'] font-bold text-2xl mb-4 text-[#F97316]">Cambio 2 - María José</h3>
						<p class="text-lg text-gray-300 mb-4">
							María José pasó de no sentirse a gusto con su figura, a tonificar y ganar músculo con un plan ajustado a su realidad.
						</p>
						<blockquote class="border-l-4 border-[#F97316] pl-4 italic text-gray-400">
							"Por primera vez siento que mi cuerpo va para donde yo quiero, no al revés."
						</blockquote>
					</div>
				</div>
			</div>
			
			<!-- Cambio 3 -->
			<div class="bg-[#1a1a1f] rounded-3xl overflow-hidden border border-gray-800 hover:border-[#F97316] transition-all duration-300">
				<div class="md:flex">
					<div class="md:w-2/5 bg-gradient-to-br from-gray-800 to-gray-900 flex items-center justify-center p-12">
						<div class="text-center">
							<div class="text-6xl mb-4">⚡</div>
							<p class="text-sm text-gray-400">Autoestima renovada</p>
						</div>
					</div>
					<div class="md:w-3/5 p-8">
						<h3 class="font-['Poppins'] font-bold text-2xl mb-4 text-[#F97316]">Cambio 3</h3>
						<p class="text-lg text-gray-300 mb-4">
							De entrenar sin rumbo a seguir un plan y ver cómo cambian el físico y la postura.
						</p>
						<blockquote class="border-l-4 border-[#F97316] pl-4 italic text-gray-400">
							"Lo que más cambió no fue solo mi cuerpo, fue mi autoestima."
						</blockquote>
					</div>
				</div>
			</div>
		</div>
	</div>
</section>

<!-- Qué vas a conseguir -->
<section class="py-10 md:py-20 bg-[#111117]">
	<div class="section-container">
		<h2 class="font-['Poppins'] font-bold text-4xl md:text-5xl mb-6 text-center">
			Qué puedes conseguir con este programa
		</h2>
		<p class="text-center text-xl text-gray-300 mb-12 max-w-3xl mx-auto">
			Cada proceso es distinto, pero hay patrones que se repiten cuando entrenas con un plan y un acompañamiento real.
		</p>
		
		<div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8 max-w-6xl mx-auto">
			<div class="bg-gradient-to-br from-[#1a1a1f] to-[#0B0B0F] p-8 rounded-2xl border border-gray-800 hover:border-[#F97316] transition-all duration-300 hover:scale-105">
				<div class="text-4xl mb-4">📉</div>
				<p class="text-lg text-gray-300">
					Bajar grasa corporal de forma progresiva y sostenible.
				</p>
			</div>
			<div class="bg-gradient-to-br from-[#1a1a1f] to-[#0B0B0F] p-8 rounded-2xl border border-gray-800 hover:border-[#F97316] transition-all duration-300 hover:scale-105">
				<div class="text-4xl mb-4">💪</div>
				<p class="text-lg text-gray-300">
					Ganar fuerza y músculo según tu punto de partida.
				</p>
			</div>
			<div class="bg-gradient-to-br from-[#1a1a1f] to-[#0B0B0F] p-8 rounded-2xl border border-gray-800 hover:border-[#F97316] transition-all duration-300 hover:scale-105">
				<div class="text-4xl mb-4">✨</div>
				<p class="text-lg text-gray-300">
					Volver a verte al espejo sin sentir vergüenza o frustración.
				</p>
			</div>
			<div class="bg-gradient-to-br from-[#1a1a1f] to-[#0B0B0F] p-8 rounded-2xl border border-gray-800 hover:border-[#F97316] transition-all duration-300 hover:scale-105">
				<div class="text-4xl mb-4">⚡</div>
				<p class="text-lg text-gray-300">
					Recuperar energía para tu día a día, no solo para el gimnasio.
				</p>
			</div>
			<div class="bg-gradient-to-br from-[#1a1a1f] to-[#0B0B0F] p-8 rounded-2xl border border-gray-800 hover:border-[#F97316] transition-all duration-300 hover:scale-105">
				<div class="text-4xl mb-4">🎯</div>
				<p class="text-lg text-gray-300">
					Construir disciplina y hábitos que duren más que una "racha de motivación".
				</p>
			</div>
			<div class="bg-gradient-to-br from-[#1a1a1f] to-[#0B0B0F] p-8 rounded-2xl border border-gray-800 hover:border-[#F97316] transition-all duration-300 hover:scale-105">
				<div class="text-4xl mb-4">🍎</div>
				<p class="text-lg text-gray-300">
					Mejorar tu relación con la comida y con tu propio cuerpo.
				</p>
			</div>
		</div>
	</div>
</section>

<!-- Cómo funciona el programa -->
<section class="py-10 md:py-20 bg-gradient-to-b from-[#0B0B0F] to-[#111117]">
	<div class="section-container">
		<h2 class="font-['Poppins'] font-bold text-4xl md:text-5xl mb-16 text-center">
			Cómo funciona el programa, paso a paso
		</h2>
		
		<div class="max-w-4xl mx-auto space-y-8">
			<!-- Step 1 -->
			<div class="flex gap-6 group">
				<div class="flex-shrink-0">
					<div class="w-16 h-16 rounded-full bg-[#F97316] flex items-center justify-center text-2xl font-bold group-hover:scale-110 transition-transform duration-300">
						1
					</div>
				</div>
				<div class="flex-grow bg-[#1a1a1f] p-6 rounded-2xl border border-gray-800 group-hover:border-[#F97316] transition-all duration-300">
					<h3 class="font-['Poppins'] font-bold text-2xl mb-3 text-[#F97316]">Evaluación inicial</h3>
					<p class="text-lg text-gray-300 leading-relaxed">
						Revisan tu situación actual: objetivos, tiempo disponible, historial de entreno, lesiones, gustos, etc. A partir de ahí se define el enfoque.
					</p>
				</div>
			</div>
			
			<!-- Step 2 -->
			<div class="flex gap-6 group">
				<div class="flex-shrink-0">
					<div class="w-16 h-16 rounded-full bg-[#F97316] flex items-center justify-center text-2xl font-bold group-hover:scale-110 transition-transform duration-300">
						2
					</div>
				</div>
				<div class="flex-grow bg-[#1a1a1f] p-6 rounded-2xl border border-gray-800 group-hover:border-[#F97316] transition-all duration-300">
					<h3 class="font-['Poppins'] font-bold text-2xl mb-3 text-[#F97316]">Plan a medida de tu contexto</h3>
					<p class="text-lg text-gray-300 leading-relaxed">
						Se arma un plan de entrenamiento adaptado a tu nivel (gimnasio o casa) y se te dan lineamientos claros de alimentación que puedas aplicar en tu día a día.
					</p>
				</div>
			</div>
			
			<!-- Step 3 -->
			<div class="flex gap-6 group">
				<div class="flex-shrink-0">
					<div class="w-16 h-16 rounded-full bg-[#F97316] flex items-center justify-center text-2xl font-bold group-hover:scale-110 transition-transform duration-300">
						3
					</div>
				</div>
				<div class="flex-grow bg-[#1a1a1f] p-6 rounded-2xl border border-gray-800 group-hover:border-[#F97316] transition-all duration-300">
					<h3 class="font-['Poppins'] font-bold text-2xl mb-3 text-[#F97316]">Acompañamiento y ajustes</h3>
					<p class="text-lg text-gray-300 leading-relaxed">
						No te quedas solo con un PDF: hay seguimiento, revisión de progresos y ajustes según cómo vas respondiendo.
					</p>
				</div>
			</div>
			
			<!-- Step 4 -->
			<div class="flex gap-6 group">
				<div class="flex-shrink-0">
					<div class="w-16 h-16 rounded-full bg-[#F97316] flex items-center justify-center text-2xl font-bold group-hover:scale-110 transition-transform duration-300">
						4
					</div>
				</div>
				<div class="flex-grow bg-[#1a1a1f] p-6 rounded-2xl border border-gray-800 group-hover:border-[#F97316] transition-all duration-300">
					<h3 class="font-['Poppins'] font-bold text-2xl mb-3 text-[#F97316]">Trabajo mental y de hábitos</h3>
					<p class="text-lg text-gray-300 leading-relaxed">
						Se trabaja también la parte de mentalidad: compromisos, foco, autosabotaje, disciplina. Porque sin esto, el cuerpo vuelve al punto de inicio.
					</p>
				</div>
			</div>
			
			<!-- Step 5 -->
			<div class="flex gap-6 group">
				<div class="flex-shrink-0">
					<div class="w-16 h-16 rounded-full bg-[#F97316] flex items-center justify-center text-2xl font-bold group-hover:scale-110 transition-transform duration-300">
						5
					</div>
				</div>
				<div class="flex-grow bg-[#1a1a1f] p-6 rounded-2xl border border-gray-800 group-hover:border-[#F97316] transition-all duration-300">
					<h3 class="font-['Poppins'] font-bold text-2xl mb-3 text-[#F97316]">Cierre del ciclo y nuevo objetivo</h3>
					<p class="text-lg text-gray-300 leading-relaxed">
						Cuando llegas a tu primer gran cambio, se ajustan metas y se define el siguiente paso, en vez de volver atrás.
					</p>
				</div>
			</div>
		</div>
	</div>
</section>

<!-- Qué incluye exactamente -->
<section class="py-10 md:py-20 bg-[#111117]">
	<div class="section-container">
		<h2 class="font-['Poppins'] font-bold text-4xl md:text-5xl mb-12 text-center">
			Qué incluye el programa
		</h2>
		
		<div class="grid md:grid-cols-2 gap-6 max-w-4xl mx-auto mb-12">
			<div class="flex gap-4 items-start">
				<span class="text-3xl mt-1">✓</span>
				<p class="text-lg text-gray-300">
					Plan de entrenamiento estructurado según tu nivel y objetivo
				</p>
			</div>
			<div class="flex gap-4 items-start">
				<span class="text-3xl mt-1">✓</span>
				<p class="text-lg text-gray-300">
					Lineamientos claros de alimentación para acompañar el cambio físico
				</p>
			</div>
			<div class="flex gap-4 items-start">
				<span class="text-3xl mt-1">✓</span>
				<p class="text-lg text-gray-300">
					Revisión periódica de progresos (fotos, medidas, rendimiento)
				</p>
			</div>
			<div class="flex gap-4 items-start">
				<span class="text-3xl mt-1">✓</span>
				<p class="text-lg text-gray-300">
					Ajustes del plan cuando hace falta, no solo al principio
				</p>
			</div>
			<div class="flex gap-4 items-start">
				<span class="text-3xl mt-1">✓</span>
				<p class="text-lg text-gray-300">
					Acompañamiento directo con Andrés para dudas clave
				</p>
			</div>
			<div class="flex gap-4 items-start">
				<span class="text-3xl mt-1">✓</span>
				<p class="text-lg text-gray-300">
					Enfoque en la parte mental: disciplina, constancia, cambio de narrativa interna
				</p>
			</div>
		</div>
		
		<p class="text-center text-xl md:text-2xl font-semibold text-[#F97316] max-w-3xl mx-auto">
			No es solo "qué hacer en el gimnasio", es un sistema completo para sostener el cambio.
		</p>
	</div>
</section>

<!-- Quién es Andrés -->
<section class="py-10 md:py-20 bg-gradient-to-b from-[#0B0B0F] to-[#111117]">
	<div class="section-container">
		<h2 class="font-['Poppins'] font-bold text-4xl md:text-5xl mb-12 text-center">
			Quién te acompaña en este proceso
		</h2>
		
		<div class="max-w-4xl mx-auto bg-[#1a1a1f] rounded-3xl overflow-hidden border border-gray-800">
			<div class="md:flex">
				<div class="md:w-2/5 bg-gradient-to-br from-[#F97316] to-[#EA580C] flex items-center justify-center p-16">
					<div class="text-center text-white">
						<div class="text-8xl mb-4">👨‍🏫</div>
						<p class="text-2xl font-bold">Andrés</p>
						<p class="text-lg opacity-90">Coach Personal</p>
					</div>
				</div>
				<div class="md:w-3/5 p-10">
					<p class="text-lg text-gray-300 mb-6 leading-relaxed">
						Andrés no es solo "un entrenador más de Instagram". Vive este estilo de vida y acompaña a personas que estaban cansadas de empezar y abandonar.
					</p>
					<p class="text-lg text-gray-300 mb-6 leading-relaxed">
						Lleva años entrenando, formándose y guiando a alumnos que llegaron sin energía, con poca autoestima o sin rumbo claro… y hoy tienen un físico y una mentalidad distinta.
					</p>
					<div class="bg-[#0B0B0F] p-6 rounded-xl border-l-4 border-[#F97316]">
						<p class="text-lg text-gray-300 font-semibold mb-2">Su enfoque es simple:</p>
						<p class="text-gray-400">
							Entrenamiento serio + acompañamiento real + trabajo mental.
						</p>
						<p class="text-gray-400 mt-2">
							Nada de promesas mágicas ni atajos imposibles de sostener.
						</p>
					</div>
				</div>
			</div>
		</div>
	</div>
</section>

<!-- FAQ Section -->
<section class="py-10 md:py-20 bg-[#111117]">
	<div class="section-container">
		<h2 class="font-['Poppins'] font-bold text-4xl md:text-5xl mb-16 text-center">
			Preguntas frecuentes
		</h2>
		
		<div class="max-w-4xl mx-auto space-y-6">
			<details class="bg-[#1a1a1f] rounded-2xl border border-gray-800 hover:border-[#F97316] transition-all duration-300 group">
				<summary class="p-6 cursor-pointer font-['Poppins'] font-semibold text-xl text-gray-200 list-none flex justify-between items-center">
					<span>¿Nunca entrené o hace mucho que no lo hago, ¿puedo empezar igual?</span>
					<span class="text-[#F97316] text-2xl group-open:rotate-180 transition-transform">▼</span>
				</summary>
				<div class="px-6 pb-6">
					<p class="text-lg text-gray-400 leading-relaxed">
						Sí. El plan se adapta a tu nivel actual. La idea no es destruirte en la primera semana, sino construir una base que puedas sostener.
					</p>
				</div>
			</details>
			
			<details class="bg-[#1a1a1f] rounded-2xl border border-gray-800 hover:border-[#F97316] transition-all duration-300 group">
				<summary class="p-6 cursor-pointer font-['Poppins'] font-semibold text-xl text-gray-200 list-none flex justify-between items-center">
					<span>¿No tengo mucho tiempo, ¿cuántos días a la semana necesito?</span>
					<span class="text-[#F97316] text-2xl group-open:rotate-180 transition-transform">▼</span>
				</summary>
				<div class="px-6 pb-6">
					<p class="text-lg text-gray-400 leading-relaxed">
						Se define según tu contexto. Mejor 3 días constantes que 6 días que abandonas. El programa prioriza lo que realmente puedes sostener.
					</p>
				</div>
			</details>
			
			<details class="bg-[#1a1a1f] rounded-2xl border border-gray-800 hover:border-[#F97316] transition-all duration-300 group">
				<summary class="p-6 cursor-pointer font-['Poppins'] font-semibold text-xl text-gray-200 list-none flex justify-between items-center">
					<span>¿Hace falta gimnasio o puedo entrenar en casa?</span>
					<span class="text-[#F97316] text-2xl group-open:rotate-180 transition-transform">▼</span>
				</summary>
				<div class="px-6 pb-6">
					<p class="text-lg text-gray-400 leading-relaxed">
						Se puede trabajar con ambas opciones. Lo importante es el plan, no el lugar.
					</p>
				</div>
			</details>
			
			<details class="bg-[#1a1a1f] rounded-2xl border border-gray-800 hover:border-[#F97316] transition-all duration-300 group">
				<summary class="p-6 cursor-pointer font-['Poppins'] font-semibold text-xl text-gray-200 list-none flex justify-between items-center">
					<span>¿Y si me desmotivo a mitad de camino?</span>
					<span class="text-[#F97316] text-2xl group-open:rotate-180 transition-transform">▼</span>
				</summary>
				<div class="px-6 pb-6">
					<p class="text-lg text-gray-400 leading-relaxed">
						Justamente por eso el enfoque incluye seguimiento y trabajo mental. No depende solo de tu fuerza de voluntad de un día.
					</p>
				</div>
			</details>
		</div>
	</div>
</section>

<!-- Final CTA Section -->
<section class="py-16 md:py-32 bg-gradient-to-b from-[#0B0B0F] via-[#1a1a1f] to-[#0B0B0F] relative overflow-hidden">
	<div class="absolute inset-0 bg-[radial-gradient(circle_at_70%_50%,rgba(249,115,22,0.15),transparent_70%)]"></div>
	<div class="section-container text-center relative z-10">
		<h2 class="font-['Poppins'] font-bold text-4xl md:text-5xl lg:text-6xl mb-8 max-w-4xl mx-auto leading-tight">
			Si estás cansado de empezar cada lunes y abandonar, este puede ser tu punto de quiebre
		</h2>
		<p class="text-xl md:text-2xl text-gray-300 mb-12 max-w-3xl mx-auto leading-relaxed">
			Si quieres un cambio como los que viste arriba y sientes que solo te falta una guía clara y un acompañamiento serio, el siguiente paso es simple:
		</p>
		
		<a href="https://www.instagram.com/andresgareth39/" target="_blank" rel="noopener noreferrer" class="btn-primary mb-6 text-base md:text-xl max-w-[90%] mx-auto">
			Quiero hablar con Andrés sobre el programa
		</a>
		
	</div>
</section>

<style>
	@keyframes fade-in {
		from {
			opacity: 0;
			transform: translateY(20px);
		}
		to {
			opacity: 1;
			transform: translateY(0);
		}
	}
	
	.animate-fade-in {
		animation: fade-in 1s ease-out;
	}
	
	details summary::-webkit-details-marker {
		display: none;
	}
</style>
