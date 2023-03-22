<script>
  import LogoText from "./LogoText.svelte";
  let image = {
    src: "https://media.giphy.com/media/3o7TKsQ8UQhtVrZ3Di/giphy.gif",
    alt: "kopek gif resmi",
    title: "kopek gif",
  };

  let name = "AladdinAlizaa";
</script>

<LogoText {name} />
<img {...image} alt={image.alt} />
