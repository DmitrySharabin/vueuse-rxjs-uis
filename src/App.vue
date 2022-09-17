<template>
	<header>
		<h1>
			Operating Heavily Dynamic UIʼs
		</h1>
		<h2>Event Sourcing &amp; CQRS in the frontend</h2>
	</header>
	<main>
		<output>0</output>

		<section class="dashboard">
			<button>Start</button>

			<button>Pause</button>

			<button>Set To</button>
			<input type="number" min="0" />

			<button>Reset</button>

			<button>Count Up</button>

			<button>Count Down</button>

			<label>
				Tick Speed
				<input type="number" min="0" />
			</label>

			<label>
				Count Diff
				<input type="number" min="0" />
			</label>
		</section>
	</main>
</template>

<script setup lang="ts">

</script>

<style scoped>

</style>
