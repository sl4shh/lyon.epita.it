<script>
	const GCAL_EMBEDURL =
		'https://calendar.google.com/calendar/embed?height=600&wkst=2&ctz=UTC&hl=fr&mode=AGENDA&title=%F0%9F%A6%81%20Calendrier%20des%20events%20Epita%20Lyon&src=YmRlcmVwcmlzZS5lcGl0YUBnbWFpbC5jb20&src=NzdiNTMyZGYyNzExMTIyNDlhMGI5MmVhMWZmOTZlYzRlNTc5YjRhYTM3NGNkZTI5MmQ2NzA3MWM3M2ZiMzg2NkBncm91cC5jYWxlbmRhci5nb29nbGUuY29t&src=MjhiOTZjMGZhMDRiYTIzNDQxNTQzNmUxZTM3MjU5NzNiODM3NTc5MjZlNmVmN2YzNzNkMjc4MjgyN2MyMDQyMUBncm91cC5jYWxlbmRhci5nb29nbGUuY29t&src=N2E1NmNiMWUwN2NkMDFiOTFhOTUzYTQ1Mzc0NTI1N2U4ZjBmMTQ4ODg2YTJjNWZjOWRiOTBjNmYyNDg1MTgxNEBncm91cC5jYWxlbmRhci5nb29nbGUuY29t&src=MzFhMDUxZTE5NGMxZWMwMDgwMjU5YTU2OWM3NmIzMjg5ZjBlNDkxMDY5NTUyNzZhMTFjMGFkNTdhYTY2ZWY2NUBncm91cC5jYWxlbmRhci5nb29nbGUuY29t&src=ODhjZWI1NThkNjk2MTE4M2QzNjkyNjI5N2UyNDEyZjYwNWZmZjM5MTY0Nzk5YWU1NGQ0YTkwYWEzYmQ1MTg5Y0Bncm91cC5jYWxlbmRhci5nb29nbGUuY29t&src=MDk2OWIwMzljMTE1MmFiOWM3NmY2NWFlYjQwOTUxODVhYjAyYTY5NzQ4ODI0MjhiMjNjMjc4ZmU3M2M5YzhkNEBncm91cC5jYWxlbmRhci5nb29nbGUuY29t&src=MDA5NDYxNWFiMmI5MDUyOTVkMGNlY2RkYTljZTExMjI0OGMxODM0ZmUyNTZjZjQ3NWM0MTUyMDdkN2MxZmQ5Y0Bncm91cC5jYWxlbmRhci5nb29nbGUuY29t&src=ODk4ZGFlY2RhZDUzYzFjYmNjYWRlZDNjODQzNTFiZWU1ZTA1ZjFlMDIzNjJjNWJmMjBjZDQ5NmM4YjNhZjk0ZUBncm91cC5jYWxlbmRhci5nb29nbGUuY29t&src=MGI0MTRhYTcwYzYwYWIzMmU0MDRiODM2MzA5MWFiYjM3NjhjZTBiYWU2MmYyODMwZjVlMTI4MjRkM2E3Yjk2ZkBncm91cC5jYWxlbmRhci5nb29nbGUuY29t&src=Y2NiZWE4NGU5YmIxNmE5YzRmYzAzMzhhNGQ5YmEwMDMxZGNkNWVmODQ3MWY0MDU3MWNjNWI3YjIyNWZhZmM4MkBncm91cC5jYWxlbmRhci5nb29nbGUuY29t&src=ZjM2Mjk3ZDA3OWMwYjMwNjViZmQ4YTIyYWQ3MTllMTZjZWY3MjRmMDFkODEyYzJhYzNkNWMwYTViOTdkMmVmN0Bncm91cC5jYWxlbmRhci5nb29nbGUuY29t&src=ZWUzYzIwOWFkMDgyMTNiYTdlOGYwNTE4NjYxMDQ2MDQ3Mjk3ZWFiNGEyODUwMzdjZTU5NzJhODYwOTc2MDA1NEBncm91cC5jYWxlbmRhci5nb29nbGUuY29t&src=M2I1YmE1NjU1NjQ5ZmZkNjMwMWU0YWY2MjdjNzhiODYzMWQ2Y2EzY2ViYzVjYjc4MTQxNzY2ZWE0MDU0NzczMUBncm91cC5jYWxlbmRhci5nb29nbGUuY29t&src=ZGIxNDg2NWUwZDRmNDJiNTExYjYyNTIyOTU2NzVhZmIzMGQyMWRiNWJlNTA5OTU2MjY2OTc5OWI5ZmI1MDAwZUBncm91cC5jYWxlbmRhci5nb29nbGUuY29t&src=YzY2NmM1MzhhMGEyMzI4ZjIzNjFjMTM3YjI0Y2IzZTU4Nzg4YTc4ZDdmZGZmNWQ3ODJlMjUxNGIwNzY0MzliOEBncm91cC5jYWxlbmRhci5nb29nbGUuY29t&color=%23039BE5&color=%23E4C441&color=%237986CB&color=%23F6BF26&color=%23F09300&color=%23C0CA33&color=%238E24AA&color=%23E67C73&color=%23616161&color=%233F51B5&color=%239E69AF&color=%23F6BF26&color=%23C0CA33&color=%23B39DDB&color=%239E69AF&color=%23D50000';

	const LIST_ASSOS = [
		{
			title: 'EpiGame',
			url: 'https://discord.gg/Fh7NYy4Ysp',
			desc: "L'asso de JDS d'EPITA Lyon !",
			img: 'epigame.png',
			bg: '#0FF00080'
		},
		{
			title: 'BattelBot',
			url: 'https://battelbot.fr',
			desc: "Codez vos bots et rentrez dans la compétition dans des jeux temporaires !",
			img: 'battelbot.svg',
			bg: '#FF500080'
		},
		{
			title:'BDE',
			url:"https://discord.gg/wda6dZJyN3",
			desc:"Le BDE d'EPITA Lyon",
			img: "bde.png",
			bg: '#12345680'
		}
	];
</script>

<h1 class="h1 text-center m-8">
	<span class="bg-gradient-to-br from-blue-500 to-cyan-300 bg-clip-text text-transparent box-decoration-clone">Planning</span>
</h1>
<section id="planning" class="flex items-center justify-center gap-3 flex-col">
	<iframe
		src={GCAL_EMBEDURL}
		style="border:solid 1px #777"
		frameborder="0"
		scrolling="no"
		title="Calendrier d'events"
	></iframe>
</section>
<h1 class="h1 text-center m-8">
	<span class="bg-gradient-to-br from-red-500 to-yellow-500 bg-clip-text text-transparent box-decoration-clone">Assos</span>
</h1><section id="grid" class="grid grid-cols-4 gap-6 p-6">
	{#each LIST_ASSOS as a}
		<a class="block card variant-filled card-hover" href={a.url} target="_blank">
			<header class="card-header rounded-md h-64" style={`background:${a.bg ?? "#ffffff"}`}>
				{#if a.img}
					<img src={`/img/${a.img}`} alt="" class="w-64 h-64">
				{/if}
			</header>
			<section class="p-4 text-xl font-semibold">{a.title ?? ""}</section>
			<footer class="card-footer">{a.desc ?? ""}</footer>
		</a>
	{/each}
</section>

<style>
	iframe {
		width: 80vw;
		height: 60vh;
		border-radius: 16px;
		box-shadow: 0px 0px 20px rgba(0, 255, 255, 0.3);
	}
</style>
