<template>
	<footer class="container flex justify-center w-full py-12 mx-auto opacity-75">
		<p class="flex text-center">
			Made with
			<icon icon="heart" class="w-6 mx-2 transition-colors duration-200 text-brand motion-safe:animate-pulse" />
			by
			<a href="https://twitter.com/enzoinnocenzi" class="font-bold">&nbsp;Enzo Innocenzi&nbsp;</a>
		</p>
	</footer>
</template>

<script>
import Icon from '@/components/Icon';

export default {
	components: { Icon },
};
</script>
