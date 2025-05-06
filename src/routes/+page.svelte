<script lang="ts">
	import Counter from './Counter.svelte';
	import welcome from '$lib/images/facility.png';
	import welcomeFallback from '$lib/images/facility.png';
</script>

<svelte:head>
	<title>MIS207</title>
	<meta name="description" content="MIS207 project" />
</svelte:head>

<section>
	<h1>
		<span class="welcome">
			<picture>
				<source srcset={welcome} type="facility/png" />
				<img src={welcomeFallback} alt="Welcome" />
			</picture>
		</span>

		SABIC<br />
		
	</h1>
	<h2>
		<strong>From making cars and planes more fuel-efficient, to helping conserve the world's water supply and enabling colorful smartphone cases</strong>
	</h2>



	

	<!-- From Uiverse.io by Rodrypaladin --> 
	<div class="card">
		<div class="card__title">content</div>
		<div class="card__data">
		<div class="card__right">
			<div class="item"><a href="/organization-background">Organization Background and Problem</a></div>
			<div class="item"><a href="/system-users">Who Will Use the System & Technology Needed</a></div>
			<div class="item"><a href="/business-processes">Business Processes Affected & Proposed Solution</a></div>
			<div class="item"><a href="/organizational-impacts">Organizational Impacts, Data Management & Lessons Learned</a></div>
			<div class="item"><a href="/references">References</a></div>
		</div>
		<div class="card__left">
			<div class="item">1</div>
			<div class="item">2</div>
			<div class="item">3</div>
			<div class="item">4</div>
			<div class="item">5</div>
		</div>
		</div>
	</div>
	
</section>

<style>
	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 0.6;
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

	nav ul {
		list-style: none;
		padding: 0;
	}

	nav li {
		margin: 0.5em 0;
	}

	nav a {
		text-decoration: none;
		color: #007acc;
	}

	nav a:hover {
		text-decoration: underline;
	}

	/* From Uiverse.io by Rodrypaladin */ 
.card {
  width: 80%;
  background:  #bae5ff;
  font-family: "Courier New", Courier, monospace;
  border-top-left-radius: 12px;
  border-top-right-radius: 12px;
  border-bottom-left-radius: 4px;
  border-bottom-right-radius: 4px;
  overflow: hidden;
}

.card__title {
  color: white;
  font-weight: bold;
  padding: 5px 10px;
  border-bottom: 1px solid rgb(167, 159, 159);
  font-size: 0.95rem;
}

.card__data {
  font-size: 1.2rem;
  display: flex;
  justify-content: space-between;
  border-right: 1px solid  #007acc;
  border-left: 1px solid  #007acc;
  border-bottom: 1px solid  #007acc;
}

.card__right {
  width: 90%;
  border-right: 1px solid  #007acc;
}

.card__left {
  width: 10%;
  text-align: end;
}

.item {
  padding: 3px 0;
  background-color: white;
}

.card__right .item {
  padding-left: 0.8em;
}

.card__left .item {
  padding-right: 0.8em;
}

.item:nth-child(even) {
  background:  #bae5ff;
}

</style>
