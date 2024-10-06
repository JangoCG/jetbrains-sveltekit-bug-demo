<script>
	import Card from '$lib/components/Card.svelte';
</script>

<!--Import of Card works, because it beginners with an upper case letter-->
<Card></Card>

<!--Import of Button will never work, because the file name starts with an lower case -->
<Button></Button>