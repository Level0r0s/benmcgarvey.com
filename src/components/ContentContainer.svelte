<style>
  .container {
    display: flex;
    flex-flow: row;
    justify-content: center;
    margin-bottom: 50px;
    width: 100%;
    margin-left: 10%;
    margin-right: 10%;
  }

  .content {
    margin-top: 30px;
    max-width: 700px;
    word-break: break-word;
    width: 100%;
  }
</style>

<div class="container">
  <div class="content">
    <slot />
  </div>
</div>
