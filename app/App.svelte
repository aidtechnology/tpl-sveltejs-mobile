<script>
  let message = 'Svelte Native App'
</script>

<style>
  .info .fas {
    color: #3a53ff;
  }

  .info {
    font-size: 20;
  }
</style>

<page>
  <actionBar title="Svelte Native App"></actionBar>
  <gridLayout>
    <label
      class="info"
      horizontalAlignment="center"
      verticalAlignment="center"
      textWrap="true"
    >
      <formattedString>
        <span class="fas" text="&#xf135;"></span>
        <span text=" {message}"></span>
      </formattedString>
    </label>
  </gridLayout>
</page>
