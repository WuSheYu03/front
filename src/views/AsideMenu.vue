<template>
  <el-menu :default-openeds="['1', '3']">
    <el-sub-menu index="1">
      <template #title><el-icon><message /></el-icon>导航一</template>
      <el-menu-item-group>
        <template #title>分组一</template>
        <el-menu-item index="1-1">选项1</el-menu-item>
        <el-menu-item index="1-2">选项2</el-menu-item>
      </el-menu-item-group>
      <el-menu-item-group title="分组2">
        <el-menu-item index="1-3">选项3</el-menu-item>
      </el-menu-item-group>
      <el-sub-menu index="1-4">
        <template #title>选项4</template>
        <el-menu-item index="1-4-1">选项4-1</el-menu-item>
      </el-sub-menu>
    </el-sub-menu>
    <el-sub-menu index="2">
      <template #title>
        <el-icon><Operation /></el-icon>导航二
      </template>
      <el-menu-item-group>
        <template #title>Group 1</template>
        <el-menu-item index="2-1">Option 1</el-menu-item>
        <el-menu-item index="2-2">Option 2</el-menu-item>
      </el-menu-item-group>
      <el-menu-item-group title="Group 2">
        <el-menu-item index="2-3">Option 3</el-menu-item>
      </el-menu-item-group>
      <el-sub-menu index="2-4">
        <template #title>Option 4</template>
        <el-menu-item index="2-4-1">Option 4-1</el-menu-item>
      </el-sub-menu>
    </el-sub-menu>
    <el-sub-menu index="3">
      <template #title>
        <el-icon><setting /></el-icon>导航三
      </template>
      <el-menu-item-group>
        <template #title>Group 1</template>
        <el-menu-item index="3-1">Option 1</el-menu-item>
        <el-menu-item index="3-2">Option 2</el-menu-item>
      </el-menu-item-group>
      <el-menu-item-group title="Group 2">
        <el-menu-item index="3-3">Option 3</el-menu-item>
      </el-menu-item-group>
      <el-sub-menu index="3-4">
        <template #title>Option 4</template>
        <el-menu-item index="3-4-1">Option 4-1</el-menu-item>
      </el-sub-menu>
    </el-sub-menu>
    </el-menu>
</template>

<script>

</script>

<style>

</style>
