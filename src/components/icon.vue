<template>
<i :class="`icon icon-${name}`"></i>
</template>

<style lang="scss" scoped>
.icon {
  display: inline-block;
  background-size: 100%;
  vertical-align: middle;
}
.icon-archive {
  background-image: url(/static/icons/archive.png);
  width: (28px / 2);
  height: (24px / 2);
}
.icon-back {
  background-image: url(/static/icons/back.png);
  width: (28px / 2);
  height: (20px / 2);
}
.icon-delete {
  background-image: url(/static/icons/delete.png);
  width: (24px / 2);
  height: (30px / 2);
}
.icon-down {
  background-image: url(/static/icons/down.png);
  width: (14px / 2);
  height: (8px / 2);
}
.icon-next {
  background-image: url(/static/icons/next.png);
  width: (16px / 2);
  height: (26px / 2);
}
.icon-prev {
  background-image: url(/static/icons/prev.png);
  width: (16px / 2);
  height: (26px / 2);
}
.icon-refresh {
  background-image: url(/static/icons/refresh.png);
  width: (28px / 2);
  height: (28px / 2);
}
.icon-reply {
  background-image: url(/static/icons/reply.png);
  width: (26px / 2);
  height: (23px / 2);
}
.icon-search {
  background-image: url(/static/icons/search.png);
  width: (31px / 2);
  height: (30px / 2);
}
.icon-spam {
  background-image: url(/static/icons/spam.png);
  width: (28px / 2);
  height: (28px / 2);
}
</style>

<script>
export default {
  name: 'icon',
  props: ['name']
}
</script>
