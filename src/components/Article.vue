<template>
  <div class="container">
    <div class="title">文章</div>
    <div class="article">
      <div class="articleTitle">
        <p>我好像甚麼事情都很悲哀</p>
        <span>作者</span> <span>2021.09.02</span>
      </div>
      <div class="articleContent">
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Officia
          magnam natus veniam rerum aut quia nihil assumenda hic necessitatibus
          maiores dolore at, excepturi quidem atque rem molestias, error fuga
          molestiae!
        </p>
        <div class="articleImg">
          <div class="img">imgA</div>
          <div class="img">imgB</div>
          <div class="img">imgC</div>
        </div>
      </div>
      <div class="articleFooter">
        <div class="tag">英文</div>
        <div class="tag">精選</div>
        <div class="tag">ao3sm</div>
        <div class="tag">精選</div>
        <div class="describe">點讚231</div>
        <div class="describe">點讚231</div>
        <div class="describe">點讚231</div>
        <div class="describe">點讚231</div>
        <div class="describe">點讚231</div>
      </div>
    </div>
    <div class="article">
      <div class="articleTitle">
        <p>我好像甚麼事情都很悲哀</p>
        <span>作者</span> <span>2021.09.02</span>
      </div>
      <div class="articleContent">
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Officia
          magnam natus veniam rerum aut quia nihil assumenda hic necessitatibus
          maiores dolore at, excepturi quidem atque rem molestias, error fuga
          molestiae!
        </p>
        <div class="articleImg">
          <div class="img">imgA</div>
          <div class="img">imgB</div>
          <div class="img">imgC</div>
        </div>
      </div>
      <div class="articleFooter">
        <div class="tag">英文</div>
        <div class="tag">精選</div>
        <div class="tag">abcdefg</div>
        <div class="tag">精選</div>
        <div class="describe">點讚231</div>
        <div class="describe">點讚231</div>
        <div class="describe">點讚231</div>
        <div class="describe">點讚231</div>
        <div class="describe">點讚231</div>
      </div>
    </div>
  </div>
</template>

<script></script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.container {
  width: 450px;
  .title {
    background-color: black;
    color: white;
  }
  .article {
    text-align: start;
    margin-bottom: 2px;
    .articleTitle {
      p {
        font-size: medium;
        font-weight: bold;
      }
    }
    .articleContent {
      p {
        overflow: hidden;
        text-overflow: ellipsis;
        white-space: nowrap;
      }
      .articleImg {
        display: flex;
        justify-content: space-between;
        .img {
          width: 130px;
          height: 100px;
          border: 1px solid black;
        }
      }
    }
    .articleFooter {
      display: flex;
      width: 100%;
      flex-wrap: wrap;
      flex-direction: row;
      .tag {
        background-color: aquamarine;
        color: azure;
        margin: 10px 5px 2px 0px;
        padding: 2px;
      }
      .describe{
        margin: 10px 5px 2px 0px;

      }
    }
  }
}

h3 {
  margin: 40px 0 0;
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
