<script setup>
import Carbonlist from "./Carbonlist.vue";
const list = [
  {
    id: 1,
    imgsrc: "https://inews.gtimg.com/newsapp_ls/0/14434984220/0",
    author: "Meta",
    laud: "99万+",
    title: "根本停不下来",
    fenlei: "女生1",
  },
  {
    id: 2,
    imgsrc: "https://inews.gtimg.com/newsapp_ls/0/14434984220/0",
    author: "Meta",
    laud: "99万+",
    title: "根本停不下来",
    fenlei: "女生2",
  },
  {
    id: 3,
    imgsrc: "https://inews.gtimg.com/newsapp_ls/0/14434984220/0",
    author: "Meta",
    laud: "99万+",
    title: "根本停不下来",
    fenlei: "女生3",
  },
  {
    id: 4,
    imgsrc: "https://inews.gtimg.com/newsapp_ls/0/14434984220/0",
    author: "Meta",
    laud: "99万+",
    title: "根本停不下来",
    fenlei: "女生4",
  },
  {
    id: 5,
    imgsrc: "https://inews.gtimg.com/newsapp_ls/0/14434984220/0",
    author: "Meta",
    laud: "99万+",
    title: "根本停不下来",
    fenlei: "女生5",
  },
  {
    id: 6,
    imgsrc: "https://inews.gtimg.com/newsapp_ls/0/14434984220/0",
    author: "Meta",
    laud: "99万+",
    title: "根本停不下来",
    fenlei: "女生6",
  },
  {
    id: 7,
    imgsrc: "https://inews.gtimg.com/newsapp_ls/0/14434984220/0",
    author: "Meta",
    laud: "99万+",
    title: "根本停不下来",
    fenlei: "女生1",
  },
  {
    id: 8,
    imgsrc: "https://inews.gtimg.com/newsapp_ls/0/14434984220/0",
    author: "Meta",
    laud: "99万+",
    title: "根本停不下来",
    fenlei: "女生2",
  },
  {
    id: 9,
    imgsrc: "https://inews.gtimg.com/newsapp_ls/0/14434984220/0",
    author: "Meta",
    laud: "99万+",
    title: "根本停不下来",
    fenlei: "女生3",
  },
  {
    id: 10,
    imgsrc: "https://inews.gtimg.com/newsapp_ls/0/14434984220/0",
    author: "Meta",
    laud: "99万+",
    title: "根本停不下来",
    fenlei: "女生4",
  },
  {
    id: 11,
    imgsrc: "https://inews.gtimg.com/newsapp_ls/0/14434984220/0",
    author: "Meta",
    laud: "99万+",
    title: "根本停不下来",
    fenlei: "女生3",
  },
  {
    id: 12,
    imgsrc: "https://inews.gtimg.com/newsapp_ls/0/14434984220/0",
    author: "Meta",
    laud: "99万+",
    title: "根本停不下来",
    fenlei: "女生4",
  },
];
</script>

<template>
  <div class="HomeRecommend">
    <div class="homecontent cls">
      <div class="header cls">
        <h3 class="title fl">新接口世界！人气飙升！</h3>
      </div>
      <Carbonlist :itemlist="list" :style="0" :colomns="6" :type="0" />
    </div>
  </div>
</template> 


<style lang="scss" scoped>
.HomeRecommend {
  margin-top: 32px;
  margin-bottom: 122px;
  .homecontent {
    .header {
      .title {
        color: #333;
        font-size: 24px;
        font-weight: 400;
        line-height: 32px;
        margin-right: 30px;
      }
    }
    .content {
      display: flex;
      flex-wrap: wrap;
    }
  }
}
</style>