<template>
  <Page>
    <ActionBar>
      <Label text="Crowdly" class="font-bold text-lg" />
    </ActionBar>

    <GridLayout>
      <Label
        class="text-xl align-middle text-center text-gray-500"
        :text="message"
        @tap="logMessage"
      />
    </GridLayout>
  </Page>
</template>

<div v-html="
<p>bienvenue"</p></div>

<style>
/* .info {
    font-size: 20;
  } */
</style>
