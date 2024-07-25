<template>
  <ul class="p-5">
    <li class="mb-2">
      <b-tooltip title="foo" variant="danger">
        <template #target>
          <b-button>with component tooltip</b-button>
        </template>
      </b-tooltip>
    </li>
    <li><b-button v-b-tooltip="'foo'">with directive tooltip</b-button></li>
  </ul>
</template>
