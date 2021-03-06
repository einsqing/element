<style>
  .demo-typo-box {
    height: 200px;
    width: 200px;
    position: relative;
    border: 1px solid #eaeefb;
    font-size: 40px;
    color: #1f2d3d;
    text-align: center;
    line-height: 162px;
    padding-bottom: 36px;
    box-sizing: border-box;
    display: inline-block;
    margin-right: 17px;

    .name {
      position: absolute;
      bottom: 0;
      width: 100%;
      height: 35px;
      border-top: 1px solid #eaeefb;
      font-size: 14px;
      color: #8492a6;
      line-height: 35px;
      text-align: left;
      text-indent: 10px;
    }
  }
  .demo-typo-size {
    .h1 {
      font-size: 20px;
    }
    .h2 {
      font-size: 18px;
    }
    .h3 {
      font-size: 16px;
    }
    .text-regular {
      font-size: 14px;
    }
    .text-small {
      font-size: 13px;
    }
    .text-smaller {
      font-size: 12px;
    }
    .color-dark-light {
      color: #99a9bf;
    }
  }
  .typo-PingFang {
    font-family: 'PingFang SC';
  }
  .typo-Hiragino {
    font-family: 'Hiragino Sans GB';
  }
  .typo-Microsoft {
    font-family: 'Microsoft YaHei';
  }
  /* 英文 */
  .typo-Helvetica-Neue {
    font-family: 'Helvetica Neue';
  }
  .typo-Helvetica {
    font-family: 'Helvetica';
  }
  .typo-Arial {
    font-family: 'Arial';
  }
</style>

## Typography 字体

我们对字体进行统一规范，力求在各个操作系统下都有最佳展示效果。

### 中文字体

<div class="demo-typo-box typo-PingFang">
  和畅惠风
  <div class="name">PingFang SC</div>
</div>
<div class="demo-typo-box typo-Hiragino">
  和畅惠风
  <div class="name">Hiragino Sans GB</div>
</div>
<div class="demo-typo-box typo-Microsoft">
  和畅惠风
  <div class="name">Microsoft YaHei</div>
</div>

### 英文／数字字体

<div class="demo-typo-box typo-Helvetica-neue">
  RGag
  <div class="name">Helvetica Neue</div>
</div>
<div class="demo-typo-box typo-Helvetica">
  RGag
  <div class="name">Helvetica</div>
</div>
<div class="demo-typo-box typo-Arial">
  RGag
  <div class="name">Arial</div>
</div>

### 字体家族 css 代码：

```css
font-family: "Helvetica Neue",Helvetica,"PingFang SC","Hiragino Sans GB","Microsoft YaHei","微软雅黑",Arial,sans-serif;
```

### 字体使用规范：

<table class="demo-typo-size">
  <tbody>
    <tr>
      <td class="h1">主标题</td>
      <td class="h1">用 Element 快速搭建页面</td>
      <td class="color-dark-light">20px  Extra large</td>
    </tr>
    <tr>
      <td class="h2">标题</td>
      <td class="h2">用 Element 快速搭建页面</td>
      <td class="color-dark-light">18px large</td>
    </tr>
    <tr>
      <td class="h3">小标题</td>
      <td class="h3">用 Element 快速搭建页面</td>
      <td class="color-dark-light">16px Medium</td>
    </tr>
    <tr>
      <td class="text-regular">正文</td>
      <td class="text-regular">用 Element 快速搭建页面</td>
      <td class="color-dark-light">14px Small</td>
    </tr>
    <tr>
      <td class="text-small">正文（小）</td>
      <td class="text-small">用 Element 快速搭建页面</td>
      <td class="color-dark-light">13px Extra Small</td>
    </tr>
    <tr>
      <td class="text-smaller">辅助文字</td>
      <td class="text-smaller">用 Element 快速搭建页面</td>
      <td class="color-dark-light">12px Extra Extra Small</td>
    </tr>
  </tbody>
</table>
