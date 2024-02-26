<template>
  <div id="app">
    <div class="container">
      <h1>Bulma Message Component Demo</h1>
      <Message type="is-primary" title="Primary Message">
        This is a primary message using Bulma CSS framework.
      </Message>
      <Message type="is-link" title="Link Message">
        This is a link message using Bulma CSS framework.
      </Message>
      <Message type="is-info" title="Info Message">
        This is an info message using Bulma CSS framework.
      </Message>
      <Message type="is-success" title="Success Message">
        This is a success message using Bulma CSS framework.
      </Message>
      <Message type="is-warning" title="Warning Message">
        This is a warning message using Bulma CSS framework.
      </Message>
      <Message type="is-danger" title="Danger Message">
        This is a danger message using Bulma CSS framework.
      </Message>
    </div>
  </div>
</template>

<script>
import Message from './components/MessageBox.vue';

export default {
  name: 'App',
  components: {
    Message
  }
};
</script>

<style>
.container {
  margin-top: 20px;
}
</style>
