<script>
	import { InlineCalendar } from 'svelte-calendar';
	const theme = {
		calendar: {
			width: '900px',
            maxWidth: '100vw',
			shadow: 'none'
		}
	};
</script>

<InlineCalendar {theme} />