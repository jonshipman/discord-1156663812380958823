<script>
	import { PUBLIC_GMAP } from '$env/static/public';
</script>

<iframe
	class="w-100 bn"
	height="550"
	frameborder="0"
	referrerpolicy="no-referrer-when-downgrade"
	src="https://www.google.com/maps/embed/v1/view?key={PUBLIC_GMAP}&center=46.414382,10.013988"
	allowfullscreen
	title="googlemaps"
/>

<div><slot /></div>
