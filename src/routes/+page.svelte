<script>
	// Your selected Skeleton theme:
	import '@skeletonlabs/skeleton/themes/theme-crimson.css';

	// This contains the bulk of Skeletons required styles:
	import '@skeletonlabs/skeleton/styles/skeleton.css';

	// Finally, your application's global stylesheet (sometimes labeled 'app.css')
	import '../app.postcss';
</script>

<div class="flex h-screen justify-center items-center bg-zinc-900">
    <div class="card flex flex-col w-96 p-6 rounded-2xl">
        <h1 class="text-center font-bold text-3xl">Login</h1>
        <p class="text-center text-sm text-secondary-300 my-2" >Login to access todo list dashboard</p>
        <form action="" class="flex flex-col mt-4 gap-2">
            <label class="label">
                <span>Username</span>
                <input class="input" title="Input (text)" type="text" placeholder="Enter username.." />
            </label>
            <label class="label">
                <span>Password</span>
                <input class="input" title="Input (password)" type="password" placeholder="Enter password.." />
            </label>
            <button type="button" class="mt-4 btn variant-filled-primary">
                <span><i class="fa-solid fa-right-to-bracket"></i></span>
                <span>Login</span>
            </button>
        </form>
    </div>
</div>