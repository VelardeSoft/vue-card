<template>
  <pv-Card style="width: 25rem; overflow: hidden;">
    <template #header>
      <img alt="user header" width="100%"
           src="https://github.com/user-attachments/assets/43c01537-b929-40da-981f-669662ecb0de"/>
    </template>
    <template #title>Advanced Card</template>
    <template #subtitle>Card subtitle</template>
    <template #content>
      <p class="m-0">
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Inventore sed consequuntur error
        repudiandae numquam deserunt quisquam repellat libero asperiores earum nam nobis, culpa
        ratione quam perferendis esse, cupiditate neque
        quas!
      </p>
    </template>
    <template #footer>
      <div class="flex gap-4 mt-1">
        <a href="https://github.com/VelardeSoft" target="_blank">
          <pv-Button label="GitHub" severity="secondary" outlined class="w-full"/>
        </a>
        <pv-Button label="Save" class="w-full"/>
      </div>
    </template>
  </pv-Card>
</template>

<script setup>
</script>
