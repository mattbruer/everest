<script>
	import Hero from '../../components/Hero.svelte';
</script>

<Hero />
<div class="mt-12 mb-12 flex w-full flex-col items-center justify-center gap-4 md:flex-row">
	<div class="mx-12">
		<div class="flex flex-col items-center">
			<h1 class="mb-2 text-center text-2xl">SERVICES</h1>
			<hr class="mb-12 w-[20%]" />
		</div>

		<p class="mb-4">
			At Everest Primary Care, Ann provides care for a wide range of health needs, including:
		</p>

		<ul class="mb-4 ml-6 list-disc">
			<li>Preventive health and annual wellness visits</li>
			<li>Management of chronic conditions such as high blood pressure, diabetes, and asthma</li>
			<li>Women’s and men’s health</li>
			<li>Weight management and lifestyle support</li>
			<li>Same-day visits for common illnesses</li>
		</ul>

		<p>
			Everest Primary Care was created with the belief that patients deserve accessible, attentive
			care and a provider who truly partners with them in their health journey. Ann is proud to
			serve the Kansas City community and is committed to helping patients take practical steps
			toward healthier, longer lives.
		</p>
	</div>

	<img
		class="trans md:w-1/2"
		src="https://img1.wsimg.com/isteam/stock/YDZkdK7/:/cr=t:0%25,l:0%25,w:100%25,h:100%25/rs=w:750,h:500,cg:true"
		alt="Stock"
	/>
</div>

<style>
	hr {
		color: red;
	}
</style>
