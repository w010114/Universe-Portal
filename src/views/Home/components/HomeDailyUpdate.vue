<script setup>
import Carbonlist from "./Carbonlist.vue";
const list = [
  {
    id: 1,
    imgsrc: "https://www.cyfengchao.com/wp-content/uploads/2021/11/bradley-jasper-ybanez-a1xlQq3HoJ0-unsplash.jpg",
    author: "星际迷航",
    laud: "99万+",
    title: "虚拟身份",
    fenlei: "女生1",
  },
  {
    id: 2,
    imgsrc: "https://www.cyfengchao.com/wp-content/uploads/2021/11/bradley-jasper-ybanez-a1xlQq3HoJ0-unsplash.jpg",
    author: "星际迷航",
    laud: "99万+",
    title: "虚拟身份",
    fenlei: "女生2",
  },
  {
    id: 3,
    imgsrc: "https://www.cyfengchao.com/wp-content/uploads/2021/11/bradley-jasper-ybanez-a1xlQq3HoJ0-unsplash.jpg",
    author: "星际迷航",
    laud: "99万+",
    title: "虚拟身份",
    fenlei: "女生3",
  },
  {
    id: 4,
    imgsrc: "https://www.cyfengchao.com/wp-content/uploads/2021/11/bradley-jasper-ybanez-a1xlQq3HoJ0-unsplash.jpg",
    author: "星际迷航",
    laud: "99万+",
    title: "虚拟身份",
    fenlei: "女生4",
  },
  {
    id: 5,
    imgsrc: "https://www.cyfengchao.com/wp-content/uploads/2021/11/bradley-jasper-ybanez-a1xlQq3HoJ0-unsplash.jpg",
    author: "星际迷航",
    laud: "99万+",
    title: "虚拟身份",
    fenlei: "女生5",
  },
  {
    id: 6,
    imgsrc: "https://www.cyfengchao.com/wp-content/uploads/2021/11/bradley-jasper-ybanez-a1xlQq3HoJ0-unsplash.jpg",
    author: "星际迷航",
    laud: "99万+",
    title: "虚拟身份",
    fenlei: "女生6",
  },
  {
    id: 7,
    imgsrc: "https://www.cyfengchao.com/wp-content/uploads/2021/11/bradley-jasper-ybanez-a1xlQq3HoJ0-unsplash.jpg",
    author: "星际迷航",
    laud: "99万+",
    title: "虚拟身份",
    fenlei: "女生1",
  },
  {
    id: 8,
    imgsrc: "https://www.cyfengchao.com/wp-content/uploads/2021/11/bradley-jasper-ybanez-a1xlQq3HoJ0-unsplash.jpg",
    author: "星际迷航",
    laud: "99万+",
    title: "虚拟身份",
    fenlei: "女生2",
  },
  {
    id: 9,
    imgsrc: "https://www.cyfengchao.com/wp-content/uploads/2021/11/bradley-jasper-ybanez-a1xlQq3HoJ0-unsplash.jpg",
    author: "星际迷航",
    laud: "99万+",
    title: "虚拟身份",
    fenlei: "女生3",
  },
  {
    id: 10,
    imgsrc: "https://www.cyfengchao.com/wp-content/uploads/2021/11/bradley-jasper-ybanez-a1xlQq3HoJ0-unsplash.jpg",
    author: "星际迷航",
    laud: "99万+",
    title: "虚拟身份",
    fenlei: "女生4",
  },
];
</script>



<template>
  <div class="HomeContributeArea">
    <div class="homecontent cls">
      <div class="header cls">
        <h3 class="title fl">每日更新</h3>
        <div class="tab fl">
          <span class="tab-item">今天</span>
          <span class="tab-item">昨天</span>
          <span class="tab-item">周一</span>
          <span class="tab-item">周日</span>
          <span class="tab-item">周六</span>
          <span class="tab-item">周五</span>
          <span class="tab-item">周四</span>
        </div>
        <a class="more fr"> 更多 </a>
      </div>
      <Carbonlist :itemlist="list" :style="1" :colomns="5" :type="1" />
    </div>
  </div>
</template> 


<style lang="scss" scoped>
.HomeContributeArea {
  margin-top: 32px;
  .homecontent {
    .header {
      .title {
        color: var(--text-color);
        font-size: 24px;
        font-weight: 400;
        line-height: 32px;
        margin-right: 30px;
      }
      .tab {
        margin-top: 6px;
        .tab-item {
          color: var(--text-color);
          cursor: pointer;
          display: inline-block;
          font-size: 16px;
          line-height: 22px;
          margin-right: 30px;
        }
        .tab-item.active {
          color: #f5a623;
        }
      }
      .more {
        border: 1px solid #edeff2;
        border-radius: 2px;
        color: var(--text-color);
        cursor: pointer;
        display: inline-block;
        font-size: 16px;
        height: 30px;
        line-height: 30px;
        text-align: center;
        width: 59px;
      }
    }
    .content {
      display: flex;
      flex-wrap: wrap;
    }
  }
}
</style>