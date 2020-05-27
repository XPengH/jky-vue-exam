<template>
  <div class="home">
    <section>
      <h1>题目1</h1>
      <p>
        请写一段css以实现图片中的效果
      </p>
      <img src="@/assets/1.png" />
      <div class="box-list">
        <div class="box">
          <div class="left">something</div>
          <div class="mid">auto width but show only one line, blablablabla</div>
          <div class="right">fit content</div>
        </div>
        <div class="box">
          <div class="left">something</div>
          <div class="mid">something short</div>
          <div class="right">fit content longer</div>
        </div>
        <div class="box">
          <div class="left">something</div>
          <div class="mid">auto width but show only one line, blablablabla</div>
          <div class="right">short</div>
        </div>
      </div>
    </section>
    <section>
      <h1>题目2</h1>
      <p>
        格式化数字，将普通数字格式化成千分位逗号分隔的数字字符串，例如 1234567 转化为
        "1,234,567"，尽可能多的写出不同实现方式
      </p>
    </section>
    <section>
      <h1>题目3</h1>
      <p>
        给定一个非负整数 num，反复将各个位上的数字相加，直到结果为一位数。
      </p>
    </section>
    <section>
      <h1>题目4</h1>
      <p>
        给定一个包含 n + 1 个整数的数组 nums，其数字都在 1 到 n 之间（包括 1 和
        n），可知至少存在一个重复的整数。
        <br />
        假设只有一个重复的整数，找出这个重复的数。
        <br />
        示例 1: 输入: [1,3,4,2,2] 输出: 2
        <br />
        示例 2: 输入: [3,1,3,4,2] 输出: 3
        <br />
        说明： 不能更改原数组（假设数组是只读的）。
        <br />
        只能使用额外的 O(1) 的空间。 时间复杂度小于 O(n2) 。
      </p>
    </section>
  </div>
</template>

<script>
export default {
  name: 'Home',
  components: {},
  methods: {
    /**
     * @param {number} num
     * @return {string}
     * 题目2
     */
    formatNumbers() {},
    /**
     * @param {number} num
     * @return {number}
     * 题目3
     */
    addDigits() {},
    /**
     * @param {number[]} nums
     * @return {number}
     * 题目4
     */
    findDuplicate() {},
  },
};
</script>
<style scoped>
div.box-list {
  width: 500px;
  border: 1px solid lightgray;
}

div.box {
}

div.left {
  background: lightsalmon;
}

div.mid {
  background: lightcyan;
}

div.right {
  background: lightgreen;
}
</style>
