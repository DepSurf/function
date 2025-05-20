# Function: <code>vlan_insert_tag</code>

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
In net/core/dev.c (ffffffff8171c5d1)
Location: include/linux/if_vlan.h:332
Inline: True
```
```
In net/core/netpoll.c (ffffffff81738b14)
Location: include/linux/if_vlan.h:332
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/8021q/vlan_core.c (ffffffff81809672)
Location: include/linux/if_vlan.h:332
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
In net/core/dev.c (ffffffff81784f48)
Location: include/linux/if_vlan.h:332
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff817a4de8)
Location: include/linux/if_vlan.h:332
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/8021q/vlan_core.c (ffffffff8187b187)
Location: include/linux/if_vlan.h:332
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
In net/core/dev.c (ffffffff817b2558)
Location: include/linux/if_vlan.h:350
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff817d3858)
Location: include/linux/if_vlan.h:350
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/8021q/vlan_core.c (ffffffff818afa47)
Location: include/linux/if_vlan.h:350
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
In net/core/dev.c (ffffffff817cfd73)
Location: include/linux/if_vlan.h:350
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff817f2bb3)
Location: include/linux/if_vlan.h:350
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/8021q/vlan_core.c (ffffffff818d62ad)
Location: include/linux/if_vlan.h:350
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
In net/core/dev.c (ffffffff818496c3)
Location: include/linux/if_vlan.h:350
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff8186e17d)
Location: include/linux/if_vlan.h:350
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/8021q/vlan_core.c (ffffffff8195be47)
Location: include/linux/if_vlan.h:350
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/dev.c (ffffffff818936b5)
Location: include/linux/if_vlan.h:436
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff818bf12d)
Location: include/linux/if_vlan.h:436
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
In net/core/dev.c (ffffffff818b40da)
Location: include/linux/if_vlan.h:447
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff818e7f63)
Location: include/linux/if_vlan.h:447
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
In net/core/dev.c (ffffffff819009b0)
Location: include/linux/if_vlan.h:442
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff819378c9)
Location: include/linux/if_vlan.h:442
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
In net/core/dev.c (ffffffff81932ce0)
Location: include/linux/if_vlan.h:431
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff8196a789)
Location: include/linux/if_vlan.h:431
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
In net/core/dev.c (ffffffff81a04a04)
Location: include/linux/if_vlan.h:433
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_vlan
```
```
In net/core/netpoll.c (ffffffff81a3de89)
Location: include/linux/if_vlan.h:433
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
In net/core/dev.c (ffffffff81a05784)
Location: include/linux/if_vlan.h:433
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_vlan
```
```
In net/core/netpoll.c (ffffffff81a40ba9)
Location: include/linux/if_vlan.h:433
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
In net/core/dev.c (ffffffff819ee114)
Location: include/linux/if_vlan.h:433
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_vlan
```
```
In net/core/netpoll.c (ffffffff81a25869)
Location: include/linux/if_vlan.h:433
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
In net/core/dev.c (ffffffff81a9f3b4)
Location: include/linux/if_vlan.h:433
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_vlan
```
```
In net/core/netpoll.c (ffffffff81ada5a9)
Location: include/linux/if_vlan.h:433
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
In net/core/dev.c (ffffffff81c18efb)
Location: include/linux/if_vlan.h:438
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff81c5bd8a)
Location: include/linux/if_vlan.h:438
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
In net/core/dev.c (ffffffff81dc9ecc)
Location: include/linux/if_vlan.h:438
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff81e121eb)
Location: include/linux/if_vlan.h:438
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
In net/core/dev.c (ffffffff81e3aa58)
Location: include/linux/if_vlan.h:447
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff81e85a2b)
Location: include/linux/if_vlan.h:447
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
In net/core/dev.c (ffffffff81ef8e08)
Location: include/linux/if_vlan.h:447
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff81f4795b)
Location: include/linux/if_vlan.h:447
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
In net/core/dev.c (ffff800010bd0cf0)
Location: include/linux/if_vlan.h:431
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffff800010c10b34)
Location: include/linux/if_vlan.h:431
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ceb930)
Location: include/linux/if_vlan.h:431
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (c0d28a74)
Location: include/linux/if_vlan.h:431
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000caed6c)
Location: include/linux/if_vlan.h:431
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (c000000000cfd728)
Location: include/linux/if_vlan.h:431
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe00075b356)
Location: include/linux/if_vlan.h:431
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffe00078d268)
Location: include/linux/if_vlan.h:431
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
In net/core/dev.c (ffffffff818d2ce0)
Location: include/linux/if_vlan.h:431
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff8190a759)
Location: include/linux/if_vlan.h:431
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188cb70)
Location: include/linux/if_vlan.h:431
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff818c47a9)
Location: include/linux/if_vlan.h:431
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
In net/core/dev.c (ffffffff81923ce0)
Location: include/linux/if_vlan.h:431
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff8195b789)
Location: include/linux/if_vlan.h:431
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
In net/core/dev.c (ffffffff81945150)
Location: include/linux/if_vlan.h:431
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff8197d9a9)
Location: include/linux/if_vlan.h:431
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
</details>
</li>
</ul>

## Differences
