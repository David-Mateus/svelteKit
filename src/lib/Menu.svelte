<script>
  const items = [
    { name: "home", href: "/" },
    { name: "sobre", href: "/sobre" },
    { name: "portfolio", href: "/portfolio" },
    { name: "contato", href: "/contato" },
    { name: "faq", href: "/faq" },
  ]
</script>
{#each items as {href, name} }


<a
href={href}
class="border-b-2 border-transparent hover:text-gray-800 transition-colors duration-300 transform dark:hover:text-gray-200 hover:border-blue-500 mx-1.5 sm:mx-6"
>{name}</a
>
{/each}



