# Function: <code>__dev_xmit_skb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8171ce33)
Location: net/core/dev.c:2870
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8178566c)
Location: net/core/dev.c:3069
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817b2c71)
Location: net/core/dev.c:3067
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817d0477)
Location: net/core/dev.c:3147
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81849e52)
Location: net/core/dev.c:3185
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8189416f)
Location: net/core/dev.c:3212
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b4c05)
Location: net/core/dev.c:3456
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8190153e)
Location: net/core/dev.c:3458
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8193386e)
Location: net/core/dev.c:3376
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __dev_xmit_skb(struct sk_buff *skb, struct Qdisc *q, struct net_device *dev, struct netdev_queue *txq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a070d0)
Location: net/core/dev.c:3734
Inline: False
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
```
**Symbols:**

```
ffffffff81a070d0-ffffffff81a073fd: __dev_xmit_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __dev_xmit_skb(struct sk_buff *skb, struct Qdisc *q, struct net_device *dev, struct netdev_queue *txq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a08680)
Location: net/core/dev.c:3764
Inline: False
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
```
**Symbols:**

```
ffffffff81a08680-ffffffff81a089ad: __dev_xmit_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __dev_xmit_skb(struct sk_buff *skb, struct Qdisc *q, struct net_device *dev, struct netdev_queue *txq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819eede0)
Location: net/core/dev.c:3843
Inline: False
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
```
**Symbols:**

```
ffffffff819eede0-ffffffff819ef1fd: __dev_xmit_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __dev_xmit_skb(struct sk_buff *skb, struct Qdisc *q, struct net_device *dev, struct netdev_queue *txq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81aa0180)
Location: net/core/dev.c:3785
Inline: False
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
```
**Symbols:**

```
ffffffff81aa0180-ffffffff81aa06ca: __dev_xmit_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __dev_xmit_skb(struct sk_buff *skb, struct Qdisc *q, struct net_device *dev, struct netdev_queue *txq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c17f90)
Location: net/core/dev.c:3791
Inline: False
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
```
**Symbols:**

```
ffffffff81c17f90-ffffffff81c18523: __dev_xmit_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __dev_xmit_skb(struct sk_buff *skb, struct Qdisc *q, struct net_device *dev, struct netdev_queue *txq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dc8ed0)
Location: net/core/dev.c:3778
Inline: False
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
```
**Symbols:**

```
ffffffff81dc8ed0-ffffffff81dc9441: __dev_xmit_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __dev_xmit_skb(struct sk_buff *skb, struct Qdisc *q, struct net_device *dev, struct netdev_queue *txq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e37430)
Location: net/core/dev.c:3738
Inline: False
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
```
**Symbols:**

```
ffffffff81e37430-ffffffff81e379a1: __dev_xmit_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __dev_xmit_skb(struct sk_buff *skb, struct Qdisc *q, struct net_device *dev, struct netdev_queue *txq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81ef5450)
Location: net/core/dev.c:3748
Inline: False
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
```
**Symbols:**

```
ffffffff81ef5450-ffffffff81ef59c5: __dev_xmit_skb (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bd19b4)
Location: net/core/dev.c:3376
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0cec50c)
Location: net/core/dev.c:3376
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000cafe30)
Location: net/core/dev.c:3376
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe00075bd94)
Location: net/core/dev.c:3376
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818d386e)
Location: net/core/dev.c:3376
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188d6fe)
Location: net/core/dev.c:3376
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8192486e)
Location: net/core/dev.c:3376
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81945d12)
Location: net/core/dev.c:3376
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
