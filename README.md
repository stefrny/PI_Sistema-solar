<!DOCTYPE html>
<div class="orbit" style="width:220px;height:220px;animation-duration:14s;">
<div class="planet venus" style="--distance:110px;"></div>
</div>
<div class="orbit" style="width:300px;height:300px;animation-duration:20s;">
<div class="planet earth" style="--distance:150px;"></div>
</div>
<div class="orbit" style="width:380px;height:380px;animation-duration:30s;">
<div class="planet mars" style="--distance:190px;"></div>
</div>
</div>


<section>
<h2 onclick="toggleLang(this)">Introduction / Introdução</h2>
<p class="en">My project aims to explore the Solar System through programming using the “p5.js library.” The idea came about to illustrate the Solar System, providing information about each planet in it and its characteristics, combining creative visualization with scientific learning about the topic. My interest in the project arose from the need to make complex concepts more accessible and visually appealing. I was able to not only visually represent the planets and their curved trajectories, but also provide an engaging educational experience.

I hope this project not only educates, but also inspires viewers to explore more about the universe!</p>

<p class="pt">O meu projeto tem o objetivo de explorar o Sistema Solar através da programação utilizando a "biblioteca p5.js". A ideia surgiu para ilustrar o Sistema Solar, informando cada planeta contido nele e suas caracteristicas, combinando uma visualização criativa com o aprendizado científico acerca do tema. O interesse pelo projeto surgiu da necessidade de tornar conceitos complexos mais acessíveis, e, visualmente atrativos. Consegui não só representar visualmente os planetas e sua trajetória de curva, mas também proporcionar uma experiência educativa envolvente.

Espero que este projeto não apenas eduque, mas também inspire os espectadores à explorar mais sobre o universo!</p>


<h2 onclick="toggleLang(this)">Methodology / Metodologia</h2>
<p class="en">The planets were created using a standard code, adjusting only their sizes, speeds, and locations to resemble the solar system. To visualize the planets, their speeds, and sizes, we used the <strong>Solar System Score</strong> and the table from the website.
  <a href="https://www.if.ufrgs.br/cref/maikida/sistemasolar.htm" target="_blank">
    https://www.if.ufrgs.br/cref/maikida/sistemasolar.htm
  </a>.
</p>

<p>
  The methods used to position planets in circular orbits around the Sun include defining two variables, such as the <code>X</code> and <code>Y</code>, through the use of trigonometric functions (sine and cosine), together with the command <code>translate(width / 2, height / 2);</code> to center according to the screen, ensuring that there are no changes if it changes size.
</p>

<p style="text-align:center;">
  \\( x = r \\times \\cos(\\theta), \\; y = r \\times \\sin(\\theta) \\)
</p>

<p>
  Arrays were initialized to store the speed and angle of each planet, for example:
  <code>ang[ângulo][]</code>. For the angles, I used the table below:
</p>

<figure>
  <img src="<img width="1366" height="249" alt="tabela" src="https://github.com/user-attachments/assets/95ea66b9-de97-4b0f-b8aa-e93bff819f32" />"style="width:75%;max-width:600px;">
  <figcaption>
    Fonte: <a href="https://www.if.ufrgs.br/cref/maikida/sistemasolar.htm" target="_blank">
      if.ufrgs.br/cref/maikida/sistemasolar.htm
    </a>
  </figcaption>
</figure>

<p>
  The orbital velocity (km/s) of each planet was divided by 10&nbsp;000, becoming more similar and not so fast.
Example for Neptune:
</p>

<pre><code>ang[7] -= 0.00054;</code></pre></p>
<p class="pt"><p>
  Os planetas foram feitos com um código padrão, ajustando apenas seus devidos tamanhos, velocidades e localizações
  para ficarem semelhantes ao sistema solar. Para a visualização dos planetas, e de suas velocidades e tamanhos,
  foi utilizado o simulador <strong>Solar System Score</strong> e a tabela do site
  <a href="https://www.if.ufrgs.br/cref/maikida/sistemasolar.htm" target="_blank">
    https://www.if.ufrgs.br/cref/maikida/sistemasolar.htm
  </a>.
</p>

<p>
  Os métodos utilizados para posicionar os planetas em órbitas circulares ao redor do Sol incluem a definição de duas
  variáveis, como <code>X</code> e <code>Y</code>, através do uso de funções trigonométricas (seno e cosseno),
  junto ao comando <code>translate(width / 2, height / 2);</code> para centralizar de acordo com a tela, garantindo
  que não haja alterações caso ela mude de tamanho.
</p>

<p style="text-align:center;">
  \\( x = r \\times \\cos(\\theta), \\; y = r \\times \\sin(\\theta) \\)
</p>

<p>
  Foram inicializados arrays para armazenar a velocidade e o ângulo de cada planeta, por exemplo:
  <code>ang[ângulo][]</code>. Para os ângulos utilizei a tabela abaixo:
</p>

<figure>
  <img src="<img width="1366" height="249" alt="tabela" src="https://github.com/user-attachments/assets/95ea66b9-de97-4b0f-b8aa-e93bff819f32" />"style="width:75%;max-width:600px;">
  <figcaption>
    Fonte: <a href="https://www.if.ufrgs.br/cref/maikida/sistemasolar.htm" target="_blank">
      if.ufrgs.br/cref/maikida/sistemasolar.htm
    </a>
  </figcaption>
</figure>

<p>
  A Velocidade Orbital (Km/s) de cada planeta foi dividida por 10&nbsp;000, ficando mais semelhante e não tão rápida.
  Exemplo para Netuno:
</p>

<pre><code>ang[7] -= 0.00054;</code></pre></p>


<h2 onclick="toggleLang(this)">Development / Desenvolvimento</h2>
<p class="en">An HTML/CSS simulation with animations represents the orbital movement of the planets around the Sun.</p>
<p class="pt">Foi criada uma simulação em HTML/CSS com animações que representam o movimento orbital dos planetas em torno do Sol.</p>


<h2 onclick="toggleLang(this)">Results / Resultado</h2>
<p class="en">An interactive and animated visualization demonstrating planetary orbits, making it easier to understand gravity and orbital motion.</p>
<p class="pt">Uma visualização interativa e animada que demonstra as órbitas planetárias, facilitando a compreensão dos conceitos de gravidade e movimento orbital.</p>


<h2 onclick="toggleLang(this)">Technology / Tecnologia</h2>
<ul class="en">
<li>HTML5 and CSS3 for structure and animations.</li>
<li>Optional JavaScript for additional interactivity.</li>
<li>GitHub Pages for project hosting.</li>
</ul>
<ul class="pt">
<li>HTML5 e CSS3 para estrutura e animações.</li>
<li>JavaScript opcional para interatividade adicional.</li>
<li>GitHub Pages para hospedagem do projeto.</li>
</ul>
</section>


<script>
function toggleLang(element){
const nextEls = [];
let el = element.nextElementSibling;
while (el && (el.tagName === 'P' || el.tagName === 'UL')) {
nextEls.push(el);
el = el.nextElementSibling;
}
nextEls.forEach(n => {
if(n.classList.contains('pt')){
n.style.display = n.style.display === 'block' ? 'none' : 'block';
} else if(n.classList.contains('en')){
n.style.display = n.style.display === 'none' ? 'block' : 'none';
}
});
}
// hide all Portuguese by default
document.querySelectorAll('.pt').forEach(el=>el.style.display='none');
</script>
</body>
</html>
