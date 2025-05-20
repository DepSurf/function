# Function: <code>__vlan_hwaccel_push_inside</code>

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
Location: include/linux/if_vlan.h:376
Inline: True
```
```
In net/core/netpoll.c (ffffffff81738b14)
Location: include/linux/if_vlan.h:376
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
Location: include/linux/if_vlan.h:376
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff817a4de8)
Location: include/linux/if_vlan.h:376
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
Location: include/linux/if_vlan.h:394
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff817d3858)
Location: include/linux/if_vlan.h:394
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
In net/core/dev.c (ffffffff817cfd5b)
Location: include/linux/if_vlan.h:394
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff817f2bb3)
Location: include/linux/if_vlan.h:394
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
In net/core/dev.c (ffffffff818496ab)
Location: include/linux/if_vlan.h:394
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff8186e17d)
Location: include/linux/if_vlan.h:394
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
In net/core/dev.c (ffffffff818936a7)
Location: include/linux/if_vlan.h:473
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff818bf120)
Location: include/linux/if_vlan.h:473
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
In net/core/dev.c (ffffffff818b40c4)
Location: include/linux/if_vlan.h:509
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff818e7f4d)
Location: include/linux/if_vlan.h:509
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
In net/core/dev.c (ffffffff81900997)
Location: include/linux/if_vlan.h:504
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff819378b0)
Location: include/linux/if_vlan.h:504
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
In net/core/dev.c (ffffffff81932cc7)
Location: include/linux/if_vlan.h:493
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff8196a770)
Location: include/linux/if_vlan.h:493
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
In net/core/dev.c (ffffffff81a049eb)
Location: include/linux/if_vlan.h:495
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_vlan
```
```
In net/core/netpoll.c (ffffffff81a3de70)
Location: include/linux/if_vlan.h:495
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
In net/core/dev.c (ffffffff81a0576b)
Location: include/linux/if_vlan.h:495
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_vlan
```
```
In net/core/netpoll.c (ffffffff81a40b90)
Location: include/linux/if_vlan.h:495
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
In net/core/dev.c (ffffffff819ee0fb)
Location: include/linux/if_vlan.h:495
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_vlan
```
```
In net/core/netpoll.c (ffffffff81a25850)
Location: include/linux/if_vlan.h:495
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
In net/core/dev.c (ffffffff81a9f39b)
Location: include/linux/if_vlan.h:495
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_vlan
```
```
In net/core/netpoll.c (ffffffff81ada590)
Location: include/linux/if_vlan.h:495
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
Location: include/linux/if_vlan.h:500
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff81c5bd8a)
Location: include/linux/if_vlan.h:500
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
Location: include/linux/if_vlan.h:498
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff81e121eb)
Location: include/linux/if_vlan.h:498
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
Location: include/linux/if_vlan.h:507
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff81e85a2b)
Location: include/linux/if_vlan.h:507
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
Location: include/linux/if_vlan.h:507
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff81f4795b)
Location: include/linux/if_vlan.h:507
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
In net/core/dev.c (ffff800010bd0ce4)
Location: include/linux/if_vlan.h:493
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffff800010c10b24)
Location: include/linux/if_vlan.h:493
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
In net/core/dev.c (c0ceb91c)
Location: include/linux/if_vlan.h:493
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (c0d28a60)
Location: include/linux/if_vlan.h:493
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
In net/core/dev.c (c000000000caed58)
Location: include/linux/if_vlan.h:493
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (c000000000cfd714)
Location: include/linux/if_vlan.h:493
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
Location: include/linux/if_vlan.h:493
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffe00078d268)
Location: include/linux/if_vlan.h:493
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
In net/core/dev.c (ffffffff818d2cc7)
Location: include/linux/if_vlan.h:493
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff8190a740)
Location: include/linux/if_vlan.h:493
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
In net/core/dev.c (ffffffff8188cb57)
Location: include/linux/if_vlan.h:493
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff818c4790)
Location: include/linux/if_vlan.h:493
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
In net/core/dev.c (ffffffff81923cc7)
Location: include/linux/if_vlan.h:493
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff8195b770)
Location: include/linux/if_vlan.h:493
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
In net/core/dev.c (ffffffff81945137)
Location: include/linux/if_vlan.h:493
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff8197d990)
Location: include/linux/if_vlan.h:493
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
</details>
</li>
</ul>

## Differences
