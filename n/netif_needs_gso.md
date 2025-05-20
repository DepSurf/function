# Function: <code>netif_needs_gso</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff815faca5)
Location: include/linux/netdevice.h:3831
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff8171c654)
Location: include/linux/netdevice.h:3831
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff8165ab87)
Location: include/linux/netdevice.h:4113
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff81785008)
Location: include/linux/netdevice.h:4113
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81688914)
Location: include/linux/netdevice.h:4067
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff817b2618)
Location: include/linux/netdevice.h:4067
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff8169e0c5)
Location: include/linux/netdevice.h:4120
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff817cfe1d)
Location: include/linux/netdevice.h:4120
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81709265)
Location: include/linux/netdevice.h:4154
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff8184976d)
Location: include/linux/netdevice.h:4154
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81747da9)
Location: include/linux/netdevice.h:4261
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff8189375b)
Location: include/linux/netdevice.h:4261
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff8176be8a)
Location: include/linux/netdevice.h:4498
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff818b417a)
Location: include/linux/netdevice.h:4498
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff817a9c82)
Location: include/linux/netdevice.h:4524
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff81900a6b)
Location: include/linux/netdevice.h:4524
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff817cd6f2)
Location: include/linux/netdevice.h:4537
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff81932d9b)
Location: include/linux/netdevice.h:4537
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
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
In drivers/net/xen-netfront.c (ffffffff818991d6)
Location: include/linux/netdevice.h:4730
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff81a07ca4)
Location: include/linux/netdevice.h:4730
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
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
In drivers/net/xen-netfront.c (ffffffff818a76d6)
Location: include/linux/netdevice.h:4926
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff81a09374)
Location: include/linux/netdevice.h:4926
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
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
In drivers/net/xen-netfront.c (ffffffff8188af84)
Location: include/linux/netdevice.h:5057
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff819efcf4)
Location: include/linux/netdevice.h:5057
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
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
In drivers/net/xen-netfront.c (ffffffff8191daed)
Location: include/linux/netdevice.h:5105
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff81aa1129)
Location: include/linux/netdevice.h:5105
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
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
In drivers/net/xen-netfront.c (ffffffff81a751a8)
Location: include/linux/netdevice.h:4926
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff81c18fce)
Location: include/linux/netdevice.h:4926
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
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
In drivers/net/xen-netfront.c (ffffffff81c06b35)
Location: include/linux/netdevice.h:4970
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff81dc9fa4)
Location: include/linux/netdevice.h:4970
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81c6c23e)
Location: include/linux/netdevice.h:5018
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff81e3ab24)
Location: include/linux/netdevice.h:5018
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81d20bee)
Location: include/linux/netdevice.h:5094
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff81ef8ec8)
Location: include/linux/netdevice.h:5094
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
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
In drivers/net/xen-netfront.c (ffff800010a09464)
Location: include/linux/netdevice.h:4537
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffff800010bd0d80)
Location: include/linux/netdevice.h:4537
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
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
In net/core/dev.c (c0ceb9c0)
Location: include/linux/netdevice.h:4537
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
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
In net/core/dev.c (c000000000caee2c)
Location: include/linux/netdevice.h:4537
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
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
In net/core/dev.c (ffffffe00075b3e4)
Location: include/linux/netdevice.h:4537
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
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
In drivers/net/xen-netfront.c (ffffffff81792312)
Location: include/linux/netdevice.h:4537
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff818d2d9b)
Location: include/linux/netdevice.h:4537
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
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
In net/core/dev.c (ffffffff8188cc2b)
Location: include/linux/netdevice.h:4537
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
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
In drivers/net/xen-netfront.c (ffffffff817c2572)
Location: include/linux/netdevice.h:4537
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff81923d9b)
Location: include/linux/netdevice.h:4537
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
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
In drivers/net/xen-netfront.c (ffffffff817dc832)
Location: include/linux/netdevice.h:4537
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff8194520b)
Location: include/linux/netdevice.h:4537
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
</details>
</li>
</ul>

## Differences
