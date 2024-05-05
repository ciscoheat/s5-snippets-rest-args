<script lang="ts"></script>

<!-- Error when using rest argument (...) -->
{#snippet foo(...test: string[])}
	<button>{test.join(", ")}</button>
{/snippet}
{@render foo(["a", "b"])}

