# Function: <code>__netdev_pick_tx</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u16 __netdev_pick_tx(struct net_device *dev, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81715570)
Location: net/core/dev.c:3000
Inline: False
Direct callers:
  - net/core/dev.c:netdev_pick_tx
```
**Symbols:**

```
ffffffff81715570-ffffffff817156ae: __netdev_pick_tx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u16 __netdev_pick_tx(struct net_device *dev, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8177d5a0)
Location: net/core/dev.c:3243
Inline: False
Direct callers:
  - net/core/dev.c:netdev_pick_tx
```
**Symbols:**

```
ffffffff8177d5a0-ffffffff8177d6df: __netdev_pick_tx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u16 __netdev_pick_tx(struct net_device *dev, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817aaad0)
Location: net/core/dev.c:3247
Inline: False
Direct callers:
  - net/core/dev.c:netdev_pick_tx
```
**Symbols:**

```
ffffffff817aaad0-ffffffff817aac3c: __netdev_pick_tx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u16 __netdev_pick_tx(struct net_device *dev, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817c9120)
Location: net/core/dev.c:3326
Inline: False
Direct callers:
  - net/core/dev.c:netdev_pick_tx
```
**Symbols:**

```
ffffffff817c9120-ffffffff817c929a: __netdev_pick_tx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u16 __netdev_pick_tx(struct net_device *dev, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81842dc0)
Location: net/core/dev.c:3372
Inline: False
Direct callers:
  - net/core/dev.c:netdev_pick_tx
```
**Symbols:**

```
ffffffff81842dc0-ffffffff81842f3a: __netdev_pick_tx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u16 __netdev_pick_tx(struct net_device *dev, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188d170)
Location: net/core/dev.c:3415
Inline: False
Direct callers:
  - net/core/dev.c:netdev_pick_tx
```
**Symbols:**

```
ffffffff8188d170-ffffffff8188d364: __netdev_pick_tx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u16 __netdev_pick_tx(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818ae460)
Location: net/core/dev.c:3707
Inline: False
Direct callers:
  - net/core/dev.c:netdev_pick_tx
```
**Symbols:**

```
ffffffff818ae460-ffffffff818ae699: __netdev_pick_tx (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct net_device *sb_dev</code>
</li>
</ul>
</details>
</li>
</ul>
