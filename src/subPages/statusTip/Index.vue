<template>
  <page-wraper>
    <demo-block :title="$t('sou-suo-wu-jie-guo')">
      <wd-status-tip image="search" tip="当前搜索无结果" />
    </demo-block>

    <demo-block :title="$t('404-ye-mian')">
      <wd-status-tip image="network" tip="当前网络不可用，请检查你的网络设置" />
    </demo-block>

    <demo-block :title="$t('ye-mian-zan-wu-nei-rong')">
      <wd-status-tip image="content" tip="暂无内容" />
    </demo-block>

    <demo-block :title="$t('wo-de-shou-cang-wei-kong')">
      <wd-status-tip image="collect" tip="暂无收藏" />
    </demo-block>

    <demo-block :title="$t('wo-de-ping-lun-wei-kong')">
      <wd-status-tip image="comment" tip="暂无评论" />
    </demo-block>

    <demo-block :title="$t('zhi-fu-shi-bai')">
      <wd-status-tip image="halo" tip="支付失败，请重新订购" />
    </demo-block>

    <demo-block :title="$t('yi-ding-yue-quan-bu-xiao-xi')">
      <wd-status-tip image="message" tip="已订阅全部消息" />
    </demo-block>

    <demo-block :title="$t('zi-ding-yi-da-xiao')">
      <wd-status-tip
        :image-size="{
          height: 200,
          width: 300
        }"
        image="search"
        :tip="$t('dang-qian-sou-suo-wu-jie-guo')"
      />
    </demo-block>

    <demo-block :title="$t('zi-ding-yi-tu-pian')">
      <wd-status-tip image="https://registry.npmmirror.com/wot-design-uni-assets/*/files/panda.jpg" tip="查看我的头像" />
    </demo-block>

    <demo-block :title="$t('cha-cao-zi-ding-yi-tu-pian-nei-rong')">
      <wd-status-tip :tip="$t('cha-cao-zi-ding-yi-tu-pian-nei-rong')">
        <template #image>
          <wd-icon name="ie-filled" size="100px"></wd-icon>
        </template>
      </wd-status-tip>
    </demo-block>
  </page-wraper>
</template>
<script lang="ts" setup></script>
<style lang="scss" scoped></style>
