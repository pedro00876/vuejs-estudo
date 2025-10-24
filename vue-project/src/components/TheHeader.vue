<template>
  <!-- O v-bind é para falar que algo é dinamico -->
  <img src="" alt="" />
  <div v-for="obj in todos" v-bind:key="obj.id">
    {{ obj.title }}
  </div>
</template>

<script>
export default {
  name: 'App',
  data() {
    return {
      todos: [
        {
          userId: 1,
          id: 1,
          title: 'delectus aut autem',
          completed: false,
        },
        {
          userId: 1,
          id: 2,
          title: 'quis ut nam facilis et officia qui',
          completed: false,
        },
        {
          userId: 1,
          id: 3,
          title: 'fugiat veniam minus',
          completed: false,
        },
        {
          userId: 1,
          id: 4,
          title: 'et porro tempora',
          completed: true,
        },
        {
          userId: 1,
          id: 5,
          title:
            'laboriosam mollitia et enim quasi adipisci quia provident illum',
          completed: false,
        },
      ],
    }
  },
}

alert
</script>
