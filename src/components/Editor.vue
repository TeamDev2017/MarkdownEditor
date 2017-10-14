<template>
  <div class="editor">
    <textarea>Editor</textarea>
    <vue-markdown>

``` go
package main

import "fmt"

func main() {
	fmt.Println("Hello, world!")
}
```

### Solar System Exploration, 1950s – 1960s

- [ ] Mercury
- [x] Venus
- [x] Earth (Orbit/Moon)
- [x] Mars
- [ ] Jupiter
- [ ] Saturn
- [ ] Uranus
- [ ] Neptune
- [ ] Comet Haley
    </vue-markdown>
  </div>
</template>

<script>

import VueMarkdown from 'vue-markdown'

export default {
  name: 'editor',
  components: {
    VueMarkdown
  }
}
</script>
