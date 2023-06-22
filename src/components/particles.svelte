<script>
    import { onMount } from 'svelte';
    import particlesJS from 'particles.js';
  
    onMount(() => {
      if (typeof window !== 'undefined') {
        particlesJS('particles-js', {
            particlesJS.load('particles-js', 'assets/particles.json', function() {
    console.log('callback - particles.js config loaded');
});
        });
      }
    });
  </script>
  
  <div id="particles-js"></div>
  
  <style>
    #particles-js {
      background-color: brown;
      width: 100%;
      height: 100%;
      position: fixed;
      top: 0;
      left: 0;
      z-index: -1;
    }
  </style>