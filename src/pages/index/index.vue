<template>
  <div class="index-main-body">
    <div class="header">
      <div class="avatar">
        <div class="avatar-img"><img src="../../image/avatar.png" /></div>
        <div class="avatar-name">Flora 您好！</div>
        <div class="avator-header-icon">
          <div class="header-icon-item">
            <img src="../../image/qrcode.png" alt="" />
          </div>
          <div class="header-icon-item">
            <img src="../../image/address.png" alt="" />
          </div>
          <div class="header-icon-item">
            <img src="../../image/notice.png" alt="" />
          </div>
        </div>
      </div>
      <div class="card">
        <div class="card-top">
          <div class="card-top-img"><img src="../../image/yuyue.png" /></div>
          <div class="card-top-text">你的下一次预约将在N天后</div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "index"
};
</script>

<style lang="less" scoped>
@shadow: #d8e9f0;
.index-main-body {
  .header {
    background-image: url("../../image/background.png");
    background-size: 100% 100%;
    background-repeat: no-repeat;
    height: 10rem;
    padding: 1.5rem 1.5rem 0 1.5rem;
    .avatar {
      display: flex;
      align-items: center;
      .avatar-img {
        width: 18%;
      }
      .avatar-name {
        width: 30%;
        font-weight: 500;
        color: #fff;
      }
      .avator-header-icon {
        display: flex;
        margin-left: auto;
      }
      .header-icon-item {
        width: 30px;
        background: #d8e9f0;
        text-align: center;
        height: 30px;
        line-height: 32px;
        border-radius: 20px;
        margin-left: 10px;
      }
    }
    .card {
      margin-top: 1.5rem;
      box-shadow: 0.2rem 0.2rem 0.2rem @shadow;
      border: 1px @shadow solid;
      border-radius: 10px;
      height: 8rem;
      background: #fff;
      padding: 16px;
      .card-top {
        display: flex;
        align-items: center;
        .card-top-img {
          margin-right: 1rem;
          line-height: 3px;
        }
        .card-top-text {
          font-size: 14px;
        }
      }
    }
  }
}
</style>
