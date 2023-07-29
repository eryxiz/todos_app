<script>
    import '@skeletonlabs/skeleton/themes/theme-crimson.css';
	import '@skeletonlabs/skeleton/styles/skeleton.css';
	import '../../app.postcss';
    import { AppShell, AppBar } from '@skeletonlabs/skeleton';
    
</script>

<AppShell>
    <AppBar>
        <svelte:fragment slot="lead">(icon)</svelte:fragment>
        (title)
        <svelte:fragment slot="trail">(actions)</svelte:fragment>
    </AppBar>
    <div class="container mx-auto">
        <slot />
    </div>
</AppShell>