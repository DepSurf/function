# Function: <code>skb_frag_off_set</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff817ce0d3)
Location: include/linux/skbuff.h:2918
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff8191947e)
Location: include/linux/skbuff.h:2918
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff8189a052)
Location: include/linux/skbuff.h:2941
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff819f2b32)
Location: include/linux/skbuff.h:2941
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff818a91ab)
Location: include/linux/skbuff.h:2967
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff819f2b24)
Location: include/linux/skbuff.h:2967
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff8188c3c8)
Location: include/linux/skbuff.h:3031
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff819d8d56)
Location: include/linux/skbuff.h:3031
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff8191f7b1)
Location: include/linux/skbuff.h:3060
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff81a88cee)
Location: include/linux/skbuff.h:3060
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81a74884)
Location: include/linux/skbuff.h:3429
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (0)
Location: include/linux/skbuff.h:3429
Inline: True
```
```
In net/core/gro.c (ffffffff81c54cf3)
Location: include/linux/skbuff.h:3429
Inline: True
Inline callers:
  - net/core/gro.c:skb_gro_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81c08ae4)
Location: include/linux/skbuff.h:3322
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (0)
Location: include/linux/skbuff.h:3322
Inline: True
```
```
In net/core/gro.c (ffffffff81e0a487)
Location: include/linux/skbuff.h:3322
Inline: True
Inline callers:
  - net/core/gro.c:skb_gro_receive
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
In drivers/net/xen-netfront.c (ffffffff81c6e24b)
Location: include/linux/skbuff.h:3376
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
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
In drivers/net/xen-netfront.c (ffffffff81d22b33)
Location: include/linux/skbuff.h:3399
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffff800010a088b8)
Location: include/linux/skbuff.h:2918
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffff800010bb2524)
Location: include/linux/skbuff.h:2918
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
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
In net/core/skbuff.c (c0ccfd4c)
Location: include/linux/skbuff.h:2918
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
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
In net/core/skbuff.c (c000000000c882f8)
Location: include/linux/skbuff.h:2918
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
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
In net/core/skbuff.c (ffffffe000743d8a)
Location: include/linux/skbuff.h:2918
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81792cf3)
Location: include/linux/skbuff.h:2918
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff818b947e)
Location: include/linux/skbuff.h:2918
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
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
In net/core/skbuff.c (ffffffff818733ce)
Location: include/linux/skbuff.h:2918
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff817c2f53)
Location: include/linux/skbuff.h:2918
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff8190a47e)
Location: include/linux/skbuff.h:2918
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff817dd213)
Location: include/linux/skbuff.h:2918
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff8192b57e)
Location: include/linux/skbuff.h:2918
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
</details>
</li>
</ul>

## Differences
