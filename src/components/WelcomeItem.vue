<template>
  <div class="flex pb-4">
    <div class="flex items-center px-6">
      <slot name="icon"></slot>
    </div>
    <div>
      <h3 clas="">
        <slot name="heading"></slot>
      </h3>
      <slot></slot>
    </div>
  </div>
</template>
