<script>
  import { onMount } from 'svelte';

  onMount(() => {
    if (typeof window !== 'undefined') {
      import('particles.js').then(({ default: particlesJS }) => {
        particlesJS.load('particles-js', './particles.json', function() {
          console.log('callback - particles.js config loaded');
        });
      });
    }
  });
</script>

<div id="particles-js"></div>

<style>
  #particles-js {
    position: absolute;
    width: 100%;
    height: 100%;
    background-color: #920000;
    background-image: url("");
    background-repeat: no-repeat;
    background-size: cover;
    background-position: 50% 50%;
  }
</style>