<template>
	<v-col cols="12" md="4" sm="6">
		<v-card
				class="mx-auto"
				max-width="344"
		>
			<v-card-text>
				<p class="display-1 text--primary">
					{{people.name}}
				</p>
				<p>{{people.id}}</p>
				<div class="text--primary">
					<p><b>Age&emsp;&emsp;&emsp;&emsp;: </b>{{people.age}}</p>
					<p><b>Eye Color&emsp;&ensp;: </b>{{people.eye_color}}</p>
					<p><b>Gender&emsp;&emsp;&ensp;: </b>{{people.gender}}</p>
					<p><b>Hair Color&emsp; : </b>{{people.hair_color}}</p>
				</div>
			</v-card-text>
		</v-card>
	</v-col>
</template>

<script>
	export default {
		props: ['people']
	}
</script>

<style scoped>

</style>
