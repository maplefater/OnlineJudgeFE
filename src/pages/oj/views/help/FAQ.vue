<template>
  <panel>
    <div slot="title">Frequently Asked Questions</div>
    <div class="content markdown-body">
      <ul>
        <li>无特殊说明，请使用标准输入输出。</li>
        <li>Java 代码需使用 Main 作为主类名。C/C++代码使用<code>int main()</code>，并且需要<code>return 0;</code>。</li>
        <li>C/C++ 的64位整数类型，请使用 <code>long long</code> 声明，使用 <code>cin/cout</code> 或 <code>%lld</code> 输入输出。
          使用<code>__int64</code>会导致编译错误。</li>
        <li>程序执行时间指CPU时间，占用内存按执行过程中内存消耗的峰值计，有多组测试数据时以最大的时间和内存消耗为准</li>
        <li>判题的时候会去除你的输出的最后的换行和空格，然后与去除最后的换行和空格的答案做比较，如果不一致就是 Wrong Answer。
          其余的行末空格和空行不去除，看清楚题目的要求。没有格式错误。
        </li>
      </ul>
    </div>
  </panel>
</template>

<script>
</script>

<style lang="less" scoped>
  .content {
    font-size: 16px;
    margin: 0 50px 40px 50px;
    > ul {
      list-style: disc;
      li {
        font-size: 16px;
        margin-top: 20px;
        &:first-child {
          margin-top: 0;
        }
        p {
          font-size: 14px;
          margin-top: 5px;
        }
      }
    }
  }
</style>
