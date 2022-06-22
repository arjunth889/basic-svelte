<script>
let name = '';
</script>

<section id="contact">
    <div>
        <label for="name"> enter your name</label>
        <input type="text" bind:value={name} placeholder="enter your name">
    </div>
    <h2>
        Hello {name || 'stranger'} !
    </h2>
</section>

<style>
    section{
        height: 60vh
    }

</style>