# 入群提示

![](../../.gitbook/assets/image%20%281%29.png)

{% hint style="danger" %}
## 本功能严禁填写违法信息。
{% endhint %}

![&#x8BED;&#x97F3;&#x6307;&#x4EE4;](../../.gitbook/assets/image%20%2843%29.png)

## 变量

 如下面的按钮所示，\[ \]括起来的是变量，

例如入群通知，入群的时候填写`[@QQ]`，入群就会输出 `@嗨娘`

## 高级变量

<table>
  <thead>
    <tr>
      <th style="text-align:left">&#x53D8;&#x91CF;</th>
      <th style="text-align:left">&#x4F8B;&#x5B50;</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">[or]</td>
      <td style="text-align:left">1[or]2
        <br />&#x4F1A;&#x968F;&#x673A;&#x53D1;1&#x6216;&#x8005;2</td>
    </tr>
    <tr>
      <td style="text-align:left">[and]</td>
      <td style="text-align:left">
        <p>1[and]2
          <br />&#x4F1A;&#x8FDE;&#x7EED;&#x53D1;&#x4E24;&#x6761;&#x4FE1;&#x606F;&#xFF1A;</p>
        <p>1</p>
        <p>2</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">[&#x6570;&#x5B57;r&#x6570;&#x5B57;]</td>
      <td style="text-align:left">[1r123]&#xFF1A;1&#x5230;123&#x968F;&#x673A;&#x6570;</td>
    </tr>
    <tr>
      <td style="text-align:left">[&#x5012;&#x8BA1;&#x65F6;-&#x65E5;-xxxx&#x5E74;xx&#x6708;x&#x65E5;x&#x65F6;x&#x5206;x&#x79D2;]</td>
      <td
      style="text-align:left">[&#x5012;&#x8BA1;&#x65F6;-&#x65E5;-2050&#x5E74;6&#x6708;7&#x65E5;8&#x65F6;0&#x5206;0&#x79D2;]
        <br
        />&#x5012;&#x8BA1;&#x65F6;
        <br />&#x3010;&#x65E5;&#x3011;&#x53EF;&#x4EE5;&#x6539;&#x4E3A;&#xFF1A;&#x5E74;&#x6708;&#x65E5;&#x65F6;&#x5206;&#x79D2;
        <br
        />[&#x5012;&#x8BA1;&#x65F6;-&#x79D2;-2050&#x5E74;6&#x6708;7&#x65E5;8&#x65F6;0&#x5206;0&#x79D2;]</td>
    </tr>
  </tbody>
</table>

## 地狱难度（仅供词库功能使用）

| 例子 | 说明 |
| :--- | :--- |
| $D\*\*\[$123$\]\*\*\[$xx$\]\*\*D$ | 如果这一行里有一个 \[$ $\] 里面的为空 则删除 $D 和 D$ 之间的内容 |
| $IF\[子爵\|男爵\]\*\*\*\*\*IF$ | 如果这一行里出现"子爵"或者"男爵"这字 则显示 $IF 和 IF$ 之间的内容 |
| $NOT\[假\|null\]\*\*\*\*\*NOT$ | 如果这一行里出现"假"或者"null"这字 则删除 $NOT 和 NOT$ 之间的内容 |

