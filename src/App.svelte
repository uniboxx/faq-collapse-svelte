<script lang="ts">
  import Faq from './lib/Faq.svelte';
</script>

<h1>Frequently Asked Questions</h1>

<div class="faq-container">
  <Faq title="Why shouldn't we trust atoms?" text="They make up everything" />
  <Faq
    title="What do you call someone with no body and no nose?"
    text="Nobody knows." />
  <Faq
    title="What's the object-oriented way to become wealthy?"
    text="Inheritance." />
  <Faq
    title="How many tickles does it take to tickle an octopus?"
    text="Ten-tickles!" />
  <Faq title="What is: 1 + 1?" text="Depends on who are you asking." />
</div>

<style lang="scss">
  h1 {
    margin: 50px 0 30px;
    text-align: center;
  }

  .faq-container {
    max-width: 600px;
    margin: 0 auto;
  }
</style>
