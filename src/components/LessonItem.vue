<script setup>
// import {ref } form "vue";
const lessonData = [
  {
    date: '0731',
    lesson: 'Vue環境、基礎概念、Vue指令'
  },
  {
    date: '0807',
    lesson: '方法、監聽與AJAX'
  },
  {
    date: '0814',
    lesson: 'Vue與元件概念，Props&Emits'
  },
  {
    date: '0821',
    lesson: 'Vue Router 與 ToDoList 全攻略'
  }
]
</script>
<template>
  <ul>
    <li v-for="(item, key) in lessonData" :key="key">{{ item.date }}:{{ item.lesson }}</li>
  </ul>
</template>
