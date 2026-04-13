---

title: Test Slide

---

# title
## title
### title
#### title
Contents

---

Image

<script setup>
const base = import.meta.env.BASE_URL
</script>

<img :src="base + 'image.svg'" style="max-height: 400px" />

---

Animation

<script setup>
const base = import.meta.env.BASE_URL
</script>

<object :key="$slidev.nav.currentPage" type="image/svg+xml" :data="base + 'excalidraw-animate.svg'" width="372" height="492"></object>

---

Claymate

<script setup>
const base = import.meta.env.BASE_URL
</script>

<img :src="base + 'excalidraw-claymate.gif'" style="max-height: 400px" />
