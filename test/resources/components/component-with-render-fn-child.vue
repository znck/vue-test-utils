<script>
    import ChildComponent from './component.vue'

    export default{
      name: 'component-with-render-fn-child',
      render: h => h(ChildComponent)
    }
</script>
