# S.S.T.T : Sapper + SvelteJS + Tailwindcss + Typescript skeleton
This should help you to get started using latest versions of **sapper, sveltejs, tailwindcss and typescript** while keeping **CSS purging optimizations** enabled.

# Note about svelte layouts and tailwind
A special component named **GlobalStyle** has been created and is used into the default **_layout** in order to use tailwindcss with some optimizations.

If you plan to create different layouts (eg : for another route on top of the default) then you must **inject the <GlobalStyle> component** aswell into it.
