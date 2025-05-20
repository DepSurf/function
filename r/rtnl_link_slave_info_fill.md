# Function: <code>rtnl_link_slave_info_fill</code>

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
In net/core/rtnetlink.c (ffffffff8172e858)
Location: net/core/rtnetlink.c:530
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
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
In net/core/rtnetlink.c (ffffffff8179828e)
Location: net/core/rtnetlink.c:552
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
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
In net/core/rtnetlink.c (ffffffff817c6012)
Location: net/core/rtnetlink.c:553
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
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
In net/core/rtnetlink.c (ffffffff817e4889)
Location: net/core/rtnetlink.c:555
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
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
In net/core/rtnetlink.c (ffffffff8185f9b5)
Location: net/core/rtnetlink.c:528
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
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
In net/core/rtnetlink.c (ffffffff818aba68)
Location: net/core/rtnetlink.c:611
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
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
In net/core/rtnetlink.c (ffffffff818cf728)
Location: net/core/rtnetlink.c:621
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
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
In net/core/rtnetlink.c (ffffffff8191c46d)
Location: net/core/rtnetlink.c:616
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
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
In net/core/rtnetlink.c (ffffffff8194ea96)
Location: net/core/rtnetlink.c:616
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rtnl_link_slave_info_fill(struct sk_buff *skb, const struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a1db50)
Location: net/core/rtnetlink.c:616
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_link_fill
```
**Symbols:**

```
ffffffff81a1db50-ffffffff81a1dc55: rtnl_link_slave_info_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rtnl_link_slave_info_fill(struct sk_buff *skb, const struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a1de80)
Location: net/core/rtnetlink.c:618
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_link_fill
```
**Symbols:**

```
ffffffff81a1de80-ffffffff81a1df85: rtnl_link_slave_info_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a05c12)
Location: net/core/rtnetlink.c:620
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_link_fill
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81ab8052)
Location: net/core/rtnetlink.c:620
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_link_fill
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81c31c9d)
Location: net/core/rtnetlink.c:657
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_link_fill
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81de505d)
Location: net/core/rtnetlink.c:658
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_link_fill
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81e56a7d)
Location: net/core/rtnetlink.c:661
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_link_fill
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81f15dcd)
Location: net/core/rtnetlink.c:656
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_link_fill
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
In net/core/rtnetlink.c (ffff800010bf08dc)
Location: net/core/rtnetlink.c:616
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
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
In net/core/rtnetlink.c (c0d08fcc)
Location: net/core/rtnetlink.c:616
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
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
In net/core/rtnetlink.c (c000000000cd4ec8)
Location: net/core/rtnetlink.c:616
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
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
In net/core/rtnetlink.c (ffffffe000772936)
Location: net/core/rtnetlink.c:616
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
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
In net/core/rtnetlink.c (ffffffff818eea66)
Location: net/core/rtnetlink.c:616
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
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
In net/core/rtnetlink.c (ffffffff818a88a6)
Location: net/core/rtnetlink.c:616
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
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
In net/core/rtnetlink.c (ffffffff8193fa96)
Location: net/core/rtnetlink.c:616
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
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
In net/core/rtnetlink.c (ffffffff81961379)
Location: net/core/rtnetlink.c:616
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
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
</ul>
