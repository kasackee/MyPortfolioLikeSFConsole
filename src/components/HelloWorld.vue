<template>
  <div class="hello">
    <h1>{{ msg }}</h1>

    <h2>Essential Links</h2>
    <ul>
      <li>
        <a href="https://vuejs.org" target="_blank">Core Docs</a>
      </li>
      <li>
        <a href="https://forum.vuejs.org" target="_blank">Forum</a>
      </li>
      <li>
        <a href="https://chat.vuejs.org" target="_blank">Community Chat</a>
      </li>
      <li>
        <a href="https://twitter.com/vuejs" target="_blank">Twitter</a>
      </li>
      <li>
        <a href="http://vuejs-templates.github.io/webpack/" target="_blank">Docs for This Template</a>
      </li>
    </ul>

    <h2>Ecosystem</h2>
    <ul>
      <li>
        <a href="http://router.vuejs.org/" target="_blank">vue-router</a>
      </li>
      <li>
        <a href="http://vuex.vuejs.org/" target="_blank">vuex</a>
      </li>
      <li>
        <a href="http://vue-loader.vuejs.org/" target="_blank">vue-loader</a>
      </li>
      <li>
        <a href="https://github.com/vuejs/awesome-vue" target="_blank">awesome-vue</a>
      </li>
    </ul>

    <h2>Test</h2>
    <ul>
      <li v-for="exp in exp_list" :key="exp.id">
        {{ exp.text }}
      </li>
    </ul>

  </div>
</template>

<script>
  export default {
    name: 'HelloWorld',
    data () {
      return {
        msg: 'Welcome to Your Vue.js App',
        exp_list: [
          {
            id: 1,
            text: 'Laravel 5.x',
          }, {
            id: 2,
            text: 'Codeigniter 2.x',
          }, {
            id: 3,
            text: 'cordova',
          }, {
            id: 4,
            text: 'react.js',
          }, {
            id: 5,
            text: 'monaca',
          }, {
            id: 6,
            text: 'angular.js',
          }, {
            id: 7,
            text: '趣味：Ruby (DXRuby使用 シューティング）',
          }, {
            id: 8,
            text: '趣味：Unity（3Dブロック崩し、2Dシューティング）',
          },
        ],
      }
    }
  }
</script>

<style scoped>
  h1, h2 {
    font-weight: normal;
  }
  ul {
    list-style-type: none;
    padding: 0;
  }
  li {
    display: inline-block;
    margin: 0 10px;
  }
  a {
    color: #42b983;
  }
</style>
