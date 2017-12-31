<script lang="babel">
export default {
  name: 'Bye',
  data () {
    return {
      list: [1,2,3,4,5]
    }
  },
  render(h) {
    return (
      <div>
          <h1>Having some trouble here</h1>
          <ul>
            {this.list.map((value) => {
              return <li>{value}</li>;
            })}
          </ul>
      </div>
    )
  }
}
</script>

<style>
h1.bye {
  color: red;
}
</style>
