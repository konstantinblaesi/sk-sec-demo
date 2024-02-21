<script lang="ts">
	import { page } from '$app/stores';
	import { user } from '$lib';

	const currentUser = $page.url.searchParams.get('user');
	if (currentUser) {
		$user = currentUser;
	}
</script>

Hello {currentUser ? currentUser : 'stranger'}<br />
Do you know {$user ? $user : 'nobody'}
