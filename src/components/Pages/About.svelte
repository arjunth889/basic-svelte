<script>
  import Courses from "../../data/data";

  const { coursedata } = Courses;
</script>

<div id="about">
  <div class="card-wraper">
    {#each coursedata as { id, username, desc }, i}
      <div class="card">
        <div class="card-header">
          <h1>{username}</h1>
        </div>
        <div class="card-desc">
          <h3>
            {desc}
          </h3>
        </div>
      </div>
    {/each}
  </div>
</div>

<style>
  div {
    display: flex;
    height: 100vh;
    align-items: center;
    justify-content: center;
  }

  .card-wraper {
    display: flex;
    justify-content: space-evenly;
    align-items: center;
    width: 70vw;
  }
  .card {
    width: 400px;
    height: 300px;
    border: 1px solid black;
    border-radius: 30px;
  }
</style>
