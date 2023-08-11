<script>
    import Header from '../lib/header.svelte';
    import Footer from '../lib/footer.svelte';
    import '../styles/global.css';
</script>


<div id="wrapper">
   <Header />
     
      <slot></slot>

   <Footer />
</div>