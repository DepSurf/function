# Function: <code>__vlan_insert_tag</code>

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
In net/core/skbuff.c (ffffffff81708ef6)
Location: include/linux/if_vlan.h:295
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
```
```
In net/core/dev.c (ffffffff8171c5d1)
Location: include/linux/if_vlan.h:295
Inline: True
```
```
In net/core/netpoll.c (ffffffff81738b14)
Location: include/linux/if_vlan.h:295
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/8021q/vlan_core.c (ffffffff81809724)
Location: include/linux/if_vlan.h:295
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff81770a21)
Location: include/linux/if_vlan.h:295
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
```
```
In net/core/dev.c (ffffffff81784f48)
Location: include/linux/if_vlan.h:295
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff817a4de8)
Location: include/linux/if_vlan.h:295
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/8021q/vlan_core.c (ffffffff8187b225)
Location: include/linux/if_vlan.h:295
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff8179dacd)
Location: include/linux/if_vlan.h:313
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
```
```
In net/core/dev.c (ffffffff817b2558)
Location: include/linux/if_vlan.h:313
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff817d3858)
Location: include/linux/if_vlan.h:313
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/8021q/vlan_core.c (ffffffff818afae5)
Location: include/linux/if_vlan.h:313
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff817bb99c)
Location: include/linux/if_vlan.h:313
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
```
```
In net/core/dev.c (ffffffff817cfd73)
Location: include/linux/if_vlan.h:313
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff817f2bb3)
Location: include/linux/if_vlan.h:313
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/8021q/vlan_core.c (ffffffff818d62ad)
Location: include/linux/if_vlan.h:313
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff81834a4c)
Location: include/linux/if_vlan.h:313
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
```
```
In net/core/dev.c (ffffffff818496c3)
Location: include/linux/if_vlan.h:313
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff8186e17d)
Location: include/linux/if_vlan.h:313
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/8021q/vlan_core.c (ffffffff8195be47)
Location: include/linux/if_vlan.h:313
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff8187f882)
Location: include/linux/if_vlan.h:386
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
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
In net/core/skbuff.c (ffffffff8189fae4)
Location: include/linux/if_vlan.h:397
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
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
In net/core/skbuff.c (ffffffff818ea504)
Location: include/linux/if_vlan.h:392
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
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
In net/core/skbuff.c (ffffffff8191c674)
Location: include/linux/if_vlan.h:381
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819f0326)
Location: include/linux/if_vlan.h:383
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819f0586)
Location: include/linux/if_vlan.h:383
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
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
In net/core/skbuff.c (ffffffff819d4ec4)
Location: include/linux/if_vlan.h:383
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
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
In net/core/skbuff.c (ffffffff81a84c54)
Location: include/linux/if_vlan.h:383
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
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
In net/core/skbuff.c (ffffffff81bfac38)
Location: include/linux/if_vlan.h:388
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
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
In net/core/skbuff.c (ffffffff81da9722)
Location: include/linux/if_vlan.h:388
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
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
In net/core/skbuff.c (ffffffff81e186e2)
Location: include/linux/if_vlan.h:397
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
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
In net/core/skbuff.c (ffffffff81ed5b82)
Location: include/linux/if_vlan.h:397
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
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
In net/core/skbuff.c (ffff800010bb6c48)
Location: include/linux/if_vlan.h:381
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
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
In net/core/skbuff.c (c0cd3aa0)
Location: include/linux/if_vlan.h:381
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
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
In net/core/skbuff.c (c000000000c8e5b8)
Location: include/linux/if_vlan.h:381
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
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
In net/core/skbuff.c (ffffffe0007468a0)
Location: include/linux/if_vlan.h:381
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
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
In net/core/skbuff.c (ffffffff818bc674)
Location: include/linux/if_vlan.h:381
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
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
In net/core/skbuff.c (ffffffff818765b4)
Location: include/linux/if_vlan.h:381
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
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
In net/core/skbuff.c (ffffffff8190d674)
Location: include/linux/if_vlan.h:381
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
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
In net/core/skbuff.c (ffffffff8192e7a4)
Location: include/linux/if_vlan.h:381
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
```
</details>
</li>
</ul>

## Differences
