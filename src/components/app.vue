<style scoped>
    @import "../styles/common.css";
    .icon-loading{
        position: fixed;
        top: 10px;
        right: 10px;
        color: #0099e5;
        animation: ani-app-loading 1s linear infinite;
    }
    @keyframes ani-app-loading {
        from { transform: rotate(0deg);}
        50%  { transform: rotate(180deg);}
        to   { transform: rotate(360deg);}
    }
</style>
<template>
    <div>
        <router-view></router-view>
        <!-- <Back-top></Back-top>
        <transition name="fade">
            <div class="loading" v-show="loading">
                <Icon type="load-c" size="18" class="icon-loading"></Icon>
            </div>
        </transition> -->
        <!--<Modal v-if="lang === 'zh-CN'" v-model="fee" title="第一期前端探索交流会" width="750" :closable="false" :mask-closable="false">-->
            <!--<div class="ivu-article">-->
                <!--<p>活动介绍：前端探索交流会 FEE(Front End Explore) 是由 TalkingData 可视化团队发起的非盈利性前端开发者交流会，旨在分享、探索和传播具有创新的、有价值的思想、灵感或经验。</p>-->
                <!--<p>直播时间：2017-12-09 14:30</p>-->
                <!--<p style="font-size: 16px;font-weight: bold;">-->
                    <!--直播地址：<a href="https://live.bilibili.com/1353202" target="_blank">https://live.bilibili.com/1353202</a>-->
                <!--</p>-->
                <!--<p>-->
                    <!--关注 FEE 公众号，获取最新动态：-->
                <!--</p>-->
                <!--<row>-->
                    <!--<i-col span="12">-->
                        <!--<img src="../images/fee-code.jpg" width="200px">-->
                    <!--</i-col>-->
                <!--</row>-->
            <!--</div>-->
            <!--<div slot="footer">-->
                <!--<Button type="text" size="large" @click="feeclose">关闭</Button>-->
                <!--<Button type="primary" size="large" style="width: 100px" @click="gotofee">查看直播</Button>-->
            <!--</div>-->
        <!--</Modal>-->
    </div>
</template>
<script>
    export default {
    }
</script>
