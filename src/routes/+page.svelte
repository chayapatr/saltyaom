<script lang="ts">
  const proofs: {
    link: string;
    img: string;
  }[] = [
    {
      link: 'https://twitter.com/saltyAom/status/1584456558536105984',
      img: 'https://media.discordapp.net/attachments/1034868245750108310/1034868371709247680/unknown.png?width=1138&height=1138'
    },
    {
      link: '',
      img: 'https://media.discordapp.net/attachments/1034868245750108310/1034868811561717810/unknown.png?width=1518&height=1139'
    },
    {
      link: '',
      img: 'https://media.discordapp.net/attachments/1034868245750108310/1034868986829086760/unknown.png?width=854&height=1139'
    },
    {
      link: '',
      img: 'https://media.discordapp.net/attachments/1034868245750108310/1034872772163284992/unknown.png?width=854&height=1139'
    },
    {
      link: '',
      img: 'https://media.discordapp.net/attachments/1034868245750108310/1034869965284712528/unknown.png?width=854&height=1139'
    },
    {
      link: 'https://www.facebook.com/AomKhunpanitchot/posts/pfbid05TRtzdeUFYDxzCyHkfkwbkm6CqFZz7iQy1SyyBQn724XfBr7HaKkJ9YGV6R3ywyLl',
      img: 'https://media.discordapp.net/attachments/1034868245750108310/1034873036035346542/unknown.png?width=854&height=1139'
    },
    {
      link: 'https://www.facebook.com/AomKhunpanitchot/posts/pfbid0GGQSEuwWBY7WnLnjhFey56UH2R9aqKD4hJmVG53Ca6GFQDTkzFGMocoHDH34P14nl',
      img: 'https://media.discordapp.net/attachments/1034868245750108310/1034873190767398972/unknown.png?width=854&height=1139'
    },
    {
      link: 'https://www.facebook.com/AomKhunpanitchot/posts/pfbid0GGQSEuwWBY7WnLnjhFey56UH2R9aqKD4hJmVG53Ca6GFQDTkzFGMocoHDH34P14nl',
      img: 'https://media.discordapp.net/attachments/1034868245750108310/1034873369969045534/unknown.png?width=896&height=1138'
    },
    {
      link: 'https://www.facebook.com/media/set/?set=a.1884314428409888&type=3',
      img: 'https://media.discordapp.net/attachments/1034868245750108310/1034873446984847450/unknown.png'
    },
    {
      link: 'https://www.facebook.com/AomKhunpanitchot/posts/pfbid0sHPJFvkF55C8HB4Fgbvpmg8oeQY2vCWKwgmhhrjVGTiTcqPDqVPyH4rgSA5jbKGel',
      img: 'https://media.discordapp.net/attachments/1034868245750108310/1034873803651690607/unknown.png?width=854&height=1139'
    },
    {
      link: 'https://www.facebook.com/AomKhunpanitchot/posts/pfbid0kWtETYEEWcRaJzeViS1tcCtHq2VC7iYLDfcMtHSwPKnNZT14swFdy93MrdtKKur9l',
      img: 'https://media.discordapp.net/attachments/1034868245750108310/1034873984170332211/unknown.png?width=854&height=1139'
    },
    {
      link: 'https://www.facebook.com/AomKhunpanitchot/posts/pfbid02YkKXtsskcLR9cJZ7mnH3uoyLv9F98fKsbTZUuDWjuKM8GJeYzQmYUnCHpYaBKnZel',
      img: 'https://media.discordapp.net/attachments/1034868245750108310/1034874280330154155/unknown.png?width=854&height=1139'
    },
    {
      link: '',
      img: 'https://media.discordapp.net/attachments/1034868245750108310/1034874871076888666/unknown.png'
    },
    {
      link: 'https://www.facebook.com/AomKhunpanitchot/posts/pfbid0kXYGBzPyvPhMZm3byMsgoVbXFLjgkGGbHPgEj8U9efowdmmpsvwnZq5kdqBtiKqUl',
      img: 'https://media.discordapp.net/attachments/1034868245750108310/1034875144885260349/unknown.png?width=854&height=1139'
    },
    {
      link: 'https://www.facebook.com/AomKhunpanitchot/posts/pfbid037eL5STDAK7gtpB6BQ4HsCZQ8gquFXPHdwg4XphwxYfKH4LVLABrotu2Txp4DQifal',
      img: 'https://media.discordapp.net/attachments/1034868245750108310/1034875810705838231/unknown.png?width=854&height=1139'
    },
    {
      link: 'https://www.facebook.com/photo.php?fbid=2035696579938338&set=pb.100004940473416.-2207520000.&type=3',
      img: 'https://media.discordapp.net/attachments/1034868245750108310/1034876039299596328/unknown.png?width=1518&height=1139'
    },
    {
      link: 'https://www.facebook.com/AomKhunpanitchot/posts/pfbid02U71QTs4RQpNFu44fwNTkakQA3W6pGa7WYhu8cpnzF84rrJuktbnBQyQG47ZeD46Zl',
      img: 'https://media.discordapp.net/attachments/1034868245750108310/1034876298335629383/unknown.png'
    }
  ];
</script>

<h1 class="text-2xl">
  Proofs that <a
    class="text-sky-500 underline"
    href="https://github.com/saltyaom">SaltyAom</a
  > is 😭
</h1>
<div class="grid grid-cols-2 md:grid-cols-3 xl:grid-cols-4 gap-3 w-full">
  {#each proofs as proof}
    <a
      href={proof.link || '#'}
      class="w-full h-full aspect-square bg-gray-400 hover:shadow-md hover:scale-[1.01] border-2 border-black transition-all"
    >
      <img src={proof.img} alt="" class="w-full h-full object-cover" />
    </a>
  {/each}
</div>
