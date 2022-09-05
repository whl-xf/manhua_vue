<template>
  <div class="demo-image_lazy">
    <el-image v-for="url in urls" :key="url" :src="url" lazy />
  </div>
</template>

<script>
export default {
  name: 'GoTop',
  data() {
    return {
      urls : ['https://p3.dcarimg.com/tos-cn-i-8gu37r9deh/fd115e88d4544d3e89afab6b42d3d499~noop.jpg', 'https://p3.dcarimg.com/tos-cn-i-8gu37r9deh/ecd8dad78e8642fd8998deb37c5131ca~noop.jpg', 'https://p3.dcarimg.com/tos-cn-i-8gu37r9deh/98a3d5ec82854cabbb4e909301047f3d~noop.jpg', 'https://p3.dcarimg.com/tos-cn-i-8gu37r9deh/639b86a238f743a286087eca27154049~noop.jpg', 'https://p3.dcarimg.com/tos-cn-i-8gu37r9deh/6eb728126637413b98c7e6620d0b6c7b~noop.jpg', 'https://p3.dcarimg.com/tos-cn-i-8gu37r9deh/f3630d28c8c8441087425995b8b74ed7~noop.jpg', 'https://p3.dcarimg.com/tos-cn-i-8gu37r9deh/323cf50c38af4e2c8fb6e228f1b179c3~noop.jpg', 'https://p3.dcarimg.com/tos-cn-i-8gu37r9deh/84e13fda6c024b97b17d48c42779479d~noop.jpg', 'https://p3.dcarimg.com/tos-cn-i-8gu37r9deh/c764d3c8e702438287a653fce9e49691~noop.jpg', 'https://p3.dcarimg.com/tos-cn-i-8gu37r9deh/ad321b96a95e4f34a516a398c91a1044~noop.jpg', 'https://p3.dcarimg.com/tos-cn-i-8gu37r9deh/cd9ef554b2cb4e40ad31c3065b444eb8~noop.jpg', 'https://p3.dcarimg.com/tos-cn-i-8gu37r9deh/5b6c9be0166249a9bf7e232bb95d33fe~noop.jpg', 'https://p3.dcarimg.com/tos-cn-i-8gu37r9deh/66a428493de04fc488e03513c9202577~noop.jpg', 'https://p3.dcarimg.com/tos-cn-i-8gu37r9deh/789d8ede3b70446897a4d9a24eb88050~noop.jpg', 'https://p3.dcarimg.com/tos-cn-i-8gu37r9deh/a5ccf123aab4426a8022373f9a2caa77~noop.jpg', 'https://p3.dcarimg.com/tos-cn-i-8gu37r9deh/64249bc5c7fb462094e29df291dadaed~noop.jpg', 'https://p3.dcarimg.com/tos-cn-i-8gu37r9deh/1e66da79b8aa41c3933bccbf208258a3~noop.jpg', 'https://p3.dcarimg.com/tos-cn-i-8gu37r9deh/6505cd4c39564faeb59d993ead97bb46~noop.jpg']
    }
  }
}
</script>

<style scoped>
.demo-image_lazy {
  /*height: 400px;*/
  overflow-y: auto;
}
.demo-image_lazy .el-image {
  display: block;
  min-height: 200px;
  /*margin-bottom: 10px;*/
}
.demo-image_lazy .el-image:last-child {
  margin-bottom: 0;
}
</style>