# voe

Web component compiler.

# 还没写完，暂时放弃，未来重新开坑

### Feature

- **Idom insteadof vdom** — It no longer needs an intermediate tree, but a tree in memory, which is the core technology of [Angular ivy](https://github.com/angular/angular/blob/master/aio/content/guide/ivy.md)

- **Staic template optimization** — This is a coarse-grained staic template optimization idea from [vue3 block tree](https://zhuanlan.zhihu.com/p/150732926)

- **Compilation rather than runtime** — Research compilation principle, data structure, algorithm.


```svelte
<script>
  export default {
    data: 0,
    add() {
      this.data++
    }
  }
</script>

<button onclick={add} style={ padding: 10; margin: 10; }>{count}</button>
```
