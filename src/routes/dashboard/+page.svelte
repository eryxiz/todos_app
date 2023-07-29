<div class="mt-5 p-5 flex card gap-4">
    <div class="w-1/4 flex flex-col justify-center px-2 py-4 bg-surface-900 rounded-3xl gap-4 h-fit">
        <button class="btn variant-filled-primary w-full">
            <span><i class="fa-solid fa-plus"></i></span>
            <span>Add New Task</span>
        </button>
        <div class="flex gap-2 mx-2 items-center">
            <p class="text-sm text-zinc-600 px-4">FILTER</p>
            <hr class="w-full">
        </div>
        <button class="btn variant-soft w-full">
            <span><i class="fa-solid fa-check"></i></span>
            <span>Complete Task</span>
        </button>
        <button class="btn variant-soft w-full">
            <span><i class="fa-solid fa-xmark"></i></span>
            <span>Uncomplete Task</span>
        </button>
        <div class="flex gap-2 mx-2 items-center">
            <p class="text-sm text-zinc-600 px-4">TAG</p>
            <hr class="w-full">
        </div>
        <div class="w-full bg-surface-800 flex flex-wrap p-2 gap-2 mx-auto rounded-xl">
            <span class="chip variant-soft hover:variant-filled px-2 rounded-full">
                <span><i class="fa-solid fa-tag"></i></span>
                <span>Education</span>
            </span>
            <span class="chip variant-soft hover:variant-filled px-2 rounded-full">
                <span><i class="fa-solid fa-tag"></i></span>
                <span>Education</span>
            </span>
        </div>
    </div>
    <div class="w-full flex flex-col">
        <div class="w-full flex justify-between py-2">
            <div class="flex items-center text-2xl">
                <span class="px-4"><i class="fa-solid fa-list"></i></span>
                <h1>Tasks</h1>
            </div>
            <div class="flex items-center">
                <button type="button" class="btn-icon variant-filled-surface"><i class="fa-solid fa-bars"></i></button>
            </div>
        </div>
        <div class="w-full grid grid-cols-3 mt-3 gap-2">
            <div class="flex flex-col bg-surface-900 hover:bg-surface-600 w-full px-5 py-4 rounded-2xl transition ease-in-out hover:scale-[1.01] max-h-fit">
                <p class="text-sm text-secondary-400">01/01/0001 - 01:01:01</p>
                <p class="line-clamp-4">Nulla dolor velit adipisicing duis excepteur esse in duis nostrud occaecat mollit incididunt deserunt sunt. Ut ut sunt laborum ex occaecat eu tempor labore enim adipisicing minim ad. Est in quis eu dolore occaecat excepteur fugiat dolore nisi aliqua fugiat enim ut cillum. Labore enim duis nostrud eu. Est ut eiusmod consequat irure quis deserunt ex. Enim laboris dolor magna pariatur. Dolor et ad sint voluptate sunt elit mollit officia ad enim sit consectetur enim.</p>
                <div class="flex items-center justify-between mt-4">
                    <div class="flex">
                        <span class="chip variant-soft-success hover:variant-filled px-2 rounded-full">
                            <span><i class="fa-solid fa-check"></i></span>
                            <span>Complete</span>
                        </span>
                    </div>
                    <div class="flex gap-2">
                        <span class="chip variant-soft hover:variant-filled px-2 rounded-full">
                            <span><i class="fa-solid fa-tag"></i></span>
                            <span>Education</span>
                        </span>
                        <span class="chip variant-soft hover:variant-filled px-2 rounded-full">
                            <span><i class="fa-solid fa-tag"></i></span>
                            <span>Education</span>
                        </span>
                    </div>
                </div>
            </div>
            <div class="flex flex-col bg-surface-900 hover:bg-surface-600 w-full px-5 py-4 rounded-2xl transition ease-in-out hover:scale-[1.01] max-h-fit">
                <p class="text-sm text-secondary-400">01/01/0001 - 01:01:01</p>
                <p class="line-clamp-4">Nulla dolor velit adipisicing duis excepteur esse in duis nostrud occaecat mollit incididunt deserunt sunt. Ut ut sunt laborum ex occaecat eu tempor labore enim adipisicing minim ad. Est in quis eu dolore occaecat excepteur fugiat dolore nisi aliqua fugiat enim ut cillum. Labore enim duis nostrud eu. Est ut eiusmod consequat irure quis deserunt ex. Enim laboris dolor magna pariatur. Dolor et ad sint voluptate sunt elit mollit officia ad enim sit consectetur enim.</p>
                <div class="flex items-center justify-between mt-4">
                    <div class="flex">
                        <span class="chip variant-soft-primary hover:variant-filled px-2 rounded-full">
                            <span><i class="fa-solid fa-xmark"></i></span>
                            <span>Uncomplete</span>
                        </span>
                    </div>
                    <div class="flex gap-2">
                        <span class="chip variant-soft hover:variant-filled px-2 rounded-full">
                            <span><i class="fa-solid fa-tag"></i></span>
                            <span>Education</span>
                        </span>
                        <span class="chip variant-soft hover:variant-filled px-2 rounded-full">
                            <span><i class="fa-solid fa-tag"></i></span>
                            <span>Education</span>
                        </span>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>