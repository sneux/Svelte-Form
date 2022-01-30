<script>
	import FeedbackList from './components/FeedbackList.svelte'
	let feedback = [
		{
			id: 1, 
			rating: 10, 
			text: 'this is some text'
		},
		{
			id: 2, 
			rating: 9, 
			text: 'this is some text'
		},
		{
			id: 3, 
			rating: 8, 
			text: 'this is some text'
		}
	]


</script>

<main class="container">
	<FeedbackList feedback={feedback} />
</main>

