<template>
    <div class="left-nav">
        <ul>
            <li>
                <i class="icon iconfont icon-homepage"></i>
                <div>首页</div>
            </li>
            <li>
                <i class="icon iconfont icon-browse"></i>
                <div>发现</div>
            </li>
            <li>
                <i class="icon iconfont icon-service"></i>
                <div>集市</div>
            </li>
            <li>
                <i class="icon iconfont icon-people"></i>
                <div>我的</div>
            </li>
        </ul>
    </div>
</template>
<script>
export default{}
</script>
<style>
    .left-nav{
        color: #FFFFFF;
        font-size: 10px;
        height: 100%;
        background-color: rgb(64, 159, 223);
        float: left;
        width: 5%;
    }
    .iconfont{
        font-size: 24px;
    }
    .left-nav ul{
        padding: 0;
        margin: 0;
    }
    .left-nav li{
        list-style: none;
        text-align: center;
        border-bottom: 1px solid rgb(95, 172, 243);
        padding: 10px;
    }
</style>
