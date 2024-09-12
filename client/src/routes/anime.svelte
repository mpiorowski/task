<script lang="ts">
	export let title: string;
	export let mal_id: number;
	export let image: string;
</script>

<h1>{title}</h1>

<a href="/{mal_id}">
	<img
		class="hover:cursor-pointer hover:opacity-50"
		src={image}
		alt={title}
		height="200px"
		width="200px"
	/>
</a>
