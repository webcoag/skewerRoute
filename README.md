<h1>skewerRoute, crie rotas com geolocation!</h1>

<ul>
<li>Copyright (C) 2013, <a href="https://github.com/ralves87">Rafael Alves</a></li>
<li>Versão atual: 1.0</li>
</ul>

<p>Necessita do jQuery 1.9+</p>

<h2>Como usar</h2>

<p>O <code>skewerRoute</code> tem a finalidade de criar rotas automáticas a partir da geolocalização. Tendo a possibilidade de alterar temas, adicionar novas rotas e customizar os markers, tudo isso de uma maneira bem simples.</p>

<pre>$(".skewerRoute").skewerRoute();</pre>

<h3>Configurações do mapa</h3>
<p>Veja como é fácil configurar o mapa com o <code>skewerRoute</code>.</p>

<pre>
$(".skewerRoute").skewerRoute({
	controls:{
		navigate: false, 	//Habilita o controle de navegação do mapa.
		zoom: false,		//Habilita o zoom.
		type: false,		//Habilita a opção de altarar o mapa para o modo satélite.
		scale: false,		//Habilita a escala do mapa.
		streetview: false,	//Habilita o streetview.
		overview: false,	//Habilita a visão global.
		scrollwheel: false	//Habilita zoom através do scroll do mouse.
	}
});
</pre>

<h3>Temas</h3>
<p>O nosso amigo <code>skewerRoute</code> possui alguns temas para você deixar o mapa mais atrente, veja o exemplo abaixo:</p>

<pre>
$(".skewerRoute").skewerRoute({
	theme: "BlackAndWhite"
});
</pre>

<p>Confira a lista atual de temas:</p>
<ul>
<li>BlackAndWhite</li>
<li>PaleDawn</li>
<li>Commander</li>
<li>BlueWater</li>
<li>BrightBubbly</li>
<li>NeutralBlue</li>
<li>Greyscale</li>
<li>VitaminC</li>
</ul>

<h3>Definindo a rota</h3>
<p>Para que definir a localização de distino, basta preencher com o endereço o parâmetro <code>route</code>.</p>

<pre>
$(".skewerRoute").skewerRoute({
	route: "Campinas, SP"
});
</pre>
