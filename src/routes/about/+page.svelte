<svelte:head>
	<title>About</title>
	<meta name="description" content="About this app" />
</svelte:head>

<div class="text-column">
	<h1>About this Project</h1>

	<p>
		This project was made by:
	</p>

		<ul>
			<li>
				Abdulraof Alkheder
			</li>
			<li>
				Muhannad Abdu Alnami
			</li>

			<li>
				Abdulaziz saad waggas
			</li>
			<li>
				Abdulatif Basahel
			</li>
		</ul>
</div>

<style>
.text-column {
	display: flex;
	flex-direction: column;
	align-items: center;
	justify-content: center;
	padding: 2rem;
	background: linear-gradient(135deg, #f3f4f6, #e5e7eb);
	border-radius: 12px;
	box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
	max-width: 600px;
	margin: 2rem auto;
	font-family: 'Arial', sans-serif;
	color: #333;
}

h1 {
	font-size: 2rem;
	color: #1f2937;
	margin-bottom: 1rem;
	text-align: center;
}

p {
	font-size: 1.2rem;
	margin-bottom: 1rem;
	text-align: center;
}

ul {
	list-style: none;
	padding: 0;
	margin: 0;
}

li {
	font-size: 1rem;
	padding: 0.5rem;
	background: #ffffff;
	border: 1px solid #e5e7eb;
	border-radius: 8px;
	margin-bottom: 0.5rem;
	text-align: center;
	transition: transform 0.2s ease, box-shadow 0.2s ease;
}

li:hover {
	transform: scale(1.05);
	box-shadow: 0 4px 8px rgba(0, 0, 0, 0.15);
}
</style>
