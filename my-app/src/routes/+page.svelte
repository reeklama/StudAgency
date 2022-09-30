<script>

</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<main>
	<div>
		<p class="in1 shrift">
			Выполнение всех видов <br> студенческих и учебных работ
		</p>
	</div>

	<div class="in2">
		<p class="shrift2">Вас приветствует студенческое Агентство «СДАМВСЕ24»!<br>
			<b>Спасибо, что посетили наш сайт.</b> Наши специалисты выполняют работы любой сложности по
			многим дисциплинам со строгим соблюдением сроков. При необходимости внесения в работу
			правок и корректировок – наши авторы сделают это в рамках основного заказа. Уникальность
			работы гарантируем. Мы ждем Вас!</p>
	</div>

	<div class="hr1">
		<p class="unde">Порядок оказания услуг</p>
	</div>

	<div>
		<p class="shm"><img src="src/lib/shema.png" alt=""/></p>
		<p class="hrr"><a  href="/order">Заказать работу</a></p>
	</div>
	<div class="in3">
		<p class="shrift4">Контакты</p>


		<div class="flex shrift2">
			<div class="padd1">Телефон: +79131968552</div>
			<div class="padd2">WhatsApp, Viber: +79131968552</div>
		</div>
		<div class="flex shrift2">
			<div class="padd1">Telegram, Вконтакте: @sdamvse24</div>
			<div class="padd2">E-mail: sdamvse24@mail.ru</div>
		</div>
		<p ><img class="embl" src="src/lib/logo.png" alt="" /></p>
		<div class="padd3 shrift2">Адрес: г. Красноярск, ул. Красной Гвардии, д. 24, этаж 3, офис 319</div>
		<div>
			<p></p>
			<iframe id="map_134751498" frameborder="0" width="800px" height="300px" sandbox="allow-modals allow-forms allow-scripts allow-same-origin allow-popups allow-top-navigation-by-user-activation"></iframe><script type="text/javascript">(function(e,t){var r=document.getElementById(e);r.contentWindow.document.open(),r.contentWindow.document.write(atob(t)),r.contentWindow.document.close()})("map_134751498", "PGJvZHk+PHN0eWxlPgogICAgICAgIGh0bWwsIGJvZHkgewogICAgICAgICAgICBtYXJnaW46IDA7CiAgICAgICAgICAgIHBhZGRpbmc6IDA7CiAgICAgICAgfQogICAgICAgIGh0bWwsIGJvZHksICNtYXAgewogICAgICAgICAgICB3aWR0aDogMTAwJTsKICAgICAgICAgICAgaGVpZ2h0OiAxMDAlOwogICAgICAgIH0KICAgICAgICAuYnVsbGV0LW1hcmtlciB7CiAgICAgICAgICAgIHdpZHRoOiAyMHB4OwogICAgICAgICAgICBoZWlnaHQ6IDIwcHg7CiAgICAgICAgICAgIGJveC1zaXppbmc6IGJvcmRlci1ib3g7CiAgICAgICAgICAgIGJhY2tncm91bmQtY29sb3I6ICNmZmY7CiAgICAgICAgICAgIGJveC1zaGFkb3c6IDAgMXB4IDNweCAwIHJnYmEoMCwgMCwgMCwgMC4yKTsKICAgICAgICAgICAgYm9yZGVyOiA0cHggc29saWQgIzAyODFmMjsKICAgICAgICAgICAgYm9yZGVyLXJhZGl1czogNTAlOwogICAgICAgIH0KICAgICAgICAucGVybWFuZW50LXRvb2x0aXAgewogICAgICAgICAgICBiYWNrZ3JvdW5kOiBub25lOwogICAgICAgICAgICBib3gtc2hhZG93OiBub25lOwogICAgICAgICAgICBib3JkZXI6IG5vbmU7CiAgICAgICAgICAgIHBhZGRpbmc6IDZweCAxMnB4OwogICAgICAgICAgICBjb2xvcjogIzI2MjYyNjsKICAgICAgICB9CiAgICAgICAgLnBlcm1hbmVudC10b29sdGlwOmJlZm9yZSB7CiAgICAgICAgICAgIGRpc3BsYXk6IG5vbmU7CiAgICAgICAgfQogICAgICAgIC5kZy1wb3B1cF9oaWRkZW5fdHJ1ZSB7CiAgICAgICAgICAgIGRpc3BsYXk6IGJsb2NrOwogICAgICAgIH0KICAgICAgICAubGVhZmxldC1jb250YWluZXIgLmxlYWZsZXQtcG9wdXAgLmxlYWZsZXQtcG9wdXAtY2xvc2UtYnV0dG9uIHsKICAgICAgICAgICAgdG9wOiAwOwogICAgICAgICAgICByaWdodDogMDsKICAgICAgICAgICAgd2lkdGg6IDIwcHg7CiAgICAgICAgICAgIGhlaWdodDogMjBweDsKICAgICAgICAgICAgZm9udC1zaXplOiAyMHB4OwogICAgICAgICAgICBsaW5lLWhlaWdodDogMTsKICAgICAgICB9CiAgICA8L3N0eWxlPjxkaXYgaWQ9Im1hcCI+PC9kaXY+PHNjcmlwdCB0eXBlPSJ0ZXh0L2phdmFzY3JpcHQiIHNyYz0iaHR0cHM6Ly9tYXBzLmFwaS4yZ2lzLnJ1LzIuMC9sb2FkZXIuanM/cGtnPWZ1bGwmYW1wO3NraW49bGlnaHQiPjwvc2NyaXB0PjxzY3JpcHQ+KGZ1bmN0aW9uKGUpe3ZhciB0PUpTT04ucGFyc2UoZSkscj10Lm9yZGVyZWRHZW9tZXRyaWVzLG49dC5tYXBQb3NpdGlvbixhPXQuaXNXaGVlbFpvb21FbmFibGVkO2Z1bmN0aW9uIG8oZSl7cmV0dXJuIGRlY29kZVVSSUNvbXBvbmVudChhdG9iKGUpLnNwbGl0KCIiKS5tYXAoZnVuY3Rpb24oZSl7cmV0dXJuIiUiKygiMDAiK2UuY2hhckNvZGVBdCgwKS50b1N0cmluZygxNikpLnNsaWNlKC0yKX0pLmpvaW4oIiIpKX1ERy50aGVuKGZ1bmN0aW9uKCl7dmFyIGU9REcubWFwKCJtYXAiLHtjZW50ZXI6W24ubGF0LG4ubG9uXSx6b29tOm4uem9vbSxzY3JvbGxXaGVlbFpvb206YSx6b29tQ29udHJvbDohYX0pO0RHLmdlb0pTT04ocix7c3R5bGU6ZnVuY3Rpb24oZSl7dmFyIHQscixuLGEsbztyZXR1cm57ZmlsbENvbG9yOm51bGw9PT0odD1lKXx8dm9pZCAwPT09dD92b2lkIDA6dC5wcm9wZXJ0aWVzLmZpbGxDb2xvcixmaWxsT3BhY2l0eTpudWxsPT09KHI9ZSl8fHZvaWQgMD09PXI/dm9pZCAwOnIucHJvcGVydGllcy5maWxsT3BhY2l0eSxjb2xvcjpudWxsPT09KG49ZSl8fHZvaWQgMD09PW4/dm9pZCAwOm4ucHJvcGVydGllcy5zdHJva2VDb2xvcix3ZWlnaHQ6bnVsbD09PShhPWUpfHx2b2lkIDA9PT1hP3ZvaWQgMDphLnByb3BlcnRpZXMuc3Ryb2tlV2lkdGgsb3BhY2l0eTpudWxsPT09KG89ZSl8fHZvaWQgMD09PW8/dm9pZCAwOm8ucHJvcGVydGllcy5zdHJva2VPcGFjaXR5fX0scG9pbnRUb0xheWVyOmZ1bmN0aW9uKGUsdCl7cmV0dXJuInJhZGl1cyJpbiBlLnByb3BlcnRpZXM/REcuY2lyY2xlKHQsZS5wcm9wZXJ0aWVzLnJhZGl1cyk6REcubWFya2VyKHQse2ljb246ZnVuY3Rpb24oZSl7cmV0dXJuIERHLmRpdkljb24oe2h0bWw6IjxkaXYgY2xhc3M9J2J1bGxldC1tYXJrZXInIHN0eWxlPSdib3JkZXItY29sb3I6ICIrZSsiOyc+PC9kaXY+IixjbGFzc05hbWU6Im92ZXJyaWRlLWRlZmF1bHQiLGljb25TaXplOlsyMCwyMF0saWNvbkFuY2hvcjpbMTAsMTBdfSl9KGUucHJvcGVydGllcy5jb2xvcil9KX0sb25FYWNoRmVhdHVyZTpmdW5jdGlvbihlLHQpe2UucHJvcGVydGllcy5kZXNjcmlwdGlvbiYmdC5iaW5kUG9wdXAobyhlLnByb3BlcnRpZXMuZGVzY3JpcHRpb24pLHtjbG9zZUJ1dHRvbjohMCxjbG9zZU9uRXNjYXBlS2V5OiEwfSksZS5wcm9wZXJ0aWVzLnRpdGxlJiZ0LmJpbmRUb29sdGlwKG8oZS5wcm9wZXJ0aWVzLnRpdGxlKSx7cGVybWFuZW50OiEwLG9wYWNpdHk6MSxjbGFzc05hbWU6InBlcm1hbmVudC10b29sdGlwIn0pfX0pLmFkZFRvKGUpfSl9KSgneyJvcmRlcmVkR2VvbWV0cmllcyI6W3sidHlwZSI6IkZlYXR1cmUiLCJwcm9wZXJ0aWVzIjp7ImNvbG9yIjoiIzAyODFmMiIsInRpdGxlIjoiMEtIUWxOQ1EwSnpRa3RDaDBKVXlOQT09IiwiZGVzY3JpcHRpb24iOiIiLCJ6SW5kZXgiOjEwMDAwMDAwMDB9LCJnZW9tZXRyeSI6eyJ0eXBlIjoiUG9pbnQiLCJjb29yZGluYXRlcyI6WzkyLjgzNzkzOCw1Ni4wMjE5NjhdfSwiaWQiOjEzMTh9XSwibWFwUG9zaXRpb24iOnsibGF0Ijo1Ni4wMjE5NzY3MjczOTEzMDUsImxvbiI6OTIuODM3OTcwMjU2ODA1NDMsInpvb20iOjE4fSwiaXNXaGVlbFpvb21FbmFibGVkIjp0cnVlfScpPC9zY3JpcHQ+PHNjcmlwdCBhc3luYz0iIiB0eXBlPSJ0ZXh0L2phdmFzY3JpcHQiIHNyYz0iaHR0cHM6Ly93d3cuZ29vZ2xldGFnbWFuYWdlci5jb20vZ3RhZy9qcz9pZD1VQS0xNTg4NjYxNjgtMSI+PC9zY3JpcHQ+PHNjcmlwdCB0eXBlPSJ0ZXh0L2phdmFzY3JpcHQiPihmdW5jdGlvbihlKXtmdW5jdGlvbiB0KCl7ZGF0YUxheWVyLnB1c2goYXJndW1lbnRzKX13aW5kb3cuZGF0YUxheWVyPXdpbmRvdy5kYXRhTGF5ZXJ8fFtdLHQoImpzIixuZXcgRGF0ZSksdCgiY29uZmlnIixlKSx3aW5kb3cuZ3RhZz10fSkoJ1VBLTE1ODg2NjE2OC0xJyk8L3NjcmlwdD48L2JvZHk+")</script>
			<p></p>
		</div>

	</div>
</main>

<style>

	.unde{
		display: inline-block;
		border-bottom: 2px solid #000;
		padding: -10px;
	}

	.shrift4{
		font-size: 30px;
		font-family: Gill Sans, sans-serif;
		letter-spacing: -2px;
		font-style: italic;
		text-decoration: underline;
		text-align: center;
		color: black;
	}

	.embl{
		margin-top: -10px;
		width: 198px;
		height: 76px;
		outline-width: 2px;
		outline-color: white;
	}

	.hr1{
		font-size: 30px;
		font-family: Gill Sans, sans-serif;
		letter-spacing: -1px;
		font-style: italic;
		text-align: center;
		color: black;


		padding: -20px;
		background-color: white;
		border-radius: 50px;

		box-shadow: 1px 4.62px 18.1px #8b8b8b;
	}

	.hrr{
		margin-top: -368px;
		margin-left: 30px;
		font-size: 20px;
		font-weight: bold;
		text-decoration: none;
		transition: 0.5s; /* Время эффекта */
	}
	.hrr:hover {
		transform: scale(1.03); /* Увеличиваем масштаб */
	}
	.shm{
		margin-left: 20px;
		text-align: center;
		width: 700px;
		height: 400px;

	}

	a{
		font-size: 20px;
		font-family: Gill Sans, sans-serif;
		letter-spacing: -1px;
		font-style: italic;
		text-align: center;
		color: #000000;
		background-color: #a42828;
		padding: 38px 34px 38px 34px;
		border-radius: 16px;
		text-decoration: none;
		border-width: 4px;
		border-style: solid;
		border-color: black;
	}

	.padd1{
		padding-left: 100px;
	}
	.padd2{
		padding-right: 100px;
	}
	.padd3{
		padding-top: 0px;
	}
	.flex{
		display: flex;
		justify-content: space-between;
		padding-bottom: 5px;

	}
	.in1{
		margin-top: 10px;
		margin-left: auto;
		margin-right: auto;
		background-color: white;
		text-align: center;

		width: 700px;
		border-radius: 30px;
		box-shadow: 1px 4.62px 18.1px #8b8b8b;
	}


	.shrift{
		font-size: 30px;
		font-family: Gill Sans, sans-serif;
		letter-spacing: -1px;
		font-style: italic;
		text-align: center;
		padding-top: 20px;
		padding-bottom: 20px;
		color: black;
	}

	.in2{
		background-color: white;
		text-align: center;
		padding: 5px 10px 10px 20px;
		margin: 30px;
		border-radius: 30px;
		box-shadow: 1px 4.62px 18.1px #8b8b8b;
	}

	.in3{
		background-color: white;
		text-align: center;
		padding: 5px 10px 10px 20px;

		margin: 30px;
		margin-top: 310px;
		border-radius: 30px;
		box-shadow: 1px 4.62px 18.1px #8b8b8b;

	}



	.shrift1{
		font-size: 40px;
		font-family: Gill Sans, sans-serif;
		letter-spacing: -2px;
		font-style: italic;
		text-decoration: underline;
		text-align: center;
		color: black;
	}
	.shrift2{
		font-size: 24px;
		font-family: Gill Sans, sans-serif;
		letter-spacing: -0px;
		font-style: italic;
		text-align: center;
		color: black;
	}


	section {
		margin-top: 1px;
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 1;
		background-image: image('../lib/fon1.jpg');


	}

	h1 {
		width: 100%;
	}

	.welcome {
		display: block;
		position: relative;
		width: 100%;
		height: 0;
		padding: 0 0 calc(100% * 495 / 2048) 0;
	}

	.welcome img {
		position: absolute;
		width: 100%;
		height: 100%;
		top: 0;
		display: block;
	}
</style>
