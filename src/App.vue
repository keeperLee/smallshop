<template>
    <div class="docker" id="nav">
        <div class="docker__item docker__item--active">
            <div class="iconfont">&#xe600;</div>
            <div class="docker__title">首页</div>
        </div>
        <div class="docker__item">
            <div class="iconfont">&#xe601;</div>
            <div class="docker__title">购物车</div>
        </div>
        <div class="docker__item">
            <div class="iconfont">&#xe602;</div>
            <div class="docker__title">订单</div>
        </div>
        <div class="docker__item">
            <div class="iconfont">&#xe7c7;</div>
            <div class="docker__title">我的</div>
        </div>
    </div>
</template>

<style lang="scss">
.docker {
    box-sizing: border-box;
    position: absolute;
    display: flex;
    padding: 0 .18rem;
    left: 0;
    bottom: 0;
    width: 100%;
    height: 0.49rem;
    border-top: 1px solid #f1f1f1;

    &__item {
        flex: 1;
        text-align: center;

        .iconfont {
            margin: .07rem 0 .02rem 0;
            font-size: .18rem;
        }

        &--active {
            color: rebeccapurple;
        }
    }

    &__title {
        font-size: 20px;
        transform: scale(.5, .5);
        transform-origin: center top;
    }
}
</style>
