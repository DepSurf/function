# Function: <code>__vlan_insert_inner_tag</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8187f882)
Location: include/linux/if_vlan.h:338
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
```
```
In net/core/dev.c (ffffffff818936b5)
Location: include/linux/if_vlan.h:338
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff818bf12d)
Location: include/linux/if_vlan.h:338
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/8021q/vlan_core.c (ffffffff819b5691)
Location: include/linux/if_vlan.h:338
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff8189fae4)
Location: include/linux/if_vlan.h:349
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
```
```
In net/core/dev.c (ffffffff818b40da)
Location: include/linux/if_vlan.h:349
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff818e7f63)
Location: include/linux/if_vlan.h:349
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/8021q/vlan_core.c (ffffffff819ec959)
Location: include/linux/if_vlan.h:349
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff818ea504)
Location: include/linux/if_vlan.h:344
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
```
```
In net/core/dev.c (ffffffff819009b0)
Location: include/linux/if_vlan.h:344
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff819378c9)
Location: include/linux/if_vlan.h:344
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/8021q/vlan_core.c (ffffffff81a5bb11)
Location: include/linux/if_vlan.h:344
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff8191c674)
Location: include/linux/if_vlan.h:333
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
```
```
In net/core/dev.c (ffffffff81932ce0)
Location: include/linux/if_vlan.h:333
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff8196a789)
Location: include/linux/if_vlan.h:333
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/8021q/vlan_core.c (ffffffff81a92708)
Location: include/linux/if_vlan.h:333
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff819f0326)
Location: include/linux/if_vlan.h:335
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
```
```
In net/core/dev.c (ffffffff81a04a04)
Location: include/linux/if_vlan.h:335
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_vlan
```
```
In net/core/netpoll.c (ffffffff81a3de89)
Location: include/linux/if_vlan.h:335
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/8021q/vlan_core.c (ffffffff81b8dbb8)
Location: include/linux/if_vlan.h:335
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff819f0586)
Location: include/linux/if_vlan.h:335
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
```
```
In net/core/dev.c (ffffffff81a05784)
Location: include/linux/if_vlan.h:335
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_vlan
```
```
In net/core/netpoll.c (ffffffff81a40ba9)
Location: include/linux/if_vlan.h:335
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/8021q/vlan_core.c (ffffffff81b9d887)
Location: include/linux/if_vlan.h:335
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff819d4ec4)
Location: include/linux/if_vlan.h:335
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
```
```
In net/core/dev.c (ffffffff819ee114)
Location: include/linux/if_vlan.h:335
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_vlan
```
```
In net/core/netpoll.c (ffffffff81a25869)
Location: include/linux/if_vlan.h:335
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/8021q/vlan_core.c (ffffffff81b8c9b0)
Location: include/linux/if_vlan.h:335
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff81a84c54)
Location: include/linux/if_vlan.h:335
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
```
```
In net/core/dev.c (ffffffff81a9f3b4)
Location: include/linux/if_vlan.h:335
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_vlan
```
```
In net/core/netpoll.c (ffffffff81ada5a9)
Location: include/linux/if_vlan.h:335
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/8021q/vlan_core.c (ffffffff81c58d70)
Location: include/linux/if_vlan.h:335
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff81bfac38)
Location: include/linux/if_vlan.h:340
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
```
```
In net/core/dev.c (ffffffff81c0fc50)
Location: include/linux/if_vlan.h:340
Inline: True
Direct callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff81c5bc70)
Location: include/linux/if_vlan.h:340
Inline: True
Direct callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/8021q/vlan_core.c (ffffffff81dfa41d)
Location: include/linux/if_vlan.h:340
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff81c0fc50-ffffffff81c0fd1e: __vlan_insert_inner_tag.constprop.0 (STB_LOCAL)
ffffffff81c5bc70-ffffffff81c5bd3e: __vlan_insert_inner_tag.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff81da95d0)
Location: include/linux/if_vlan.h:340
Inline: True
Direct callers:
  - net/core/skbuff.c:skb_vlan_push
```
```
In net/core/dev.c (ffffffff81dbf920)
Location: include/linux/if_vlan.h:340
Inline: True
Direct callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff81e120c0)
Location: include/linux/if_vlan.h:340
Inline: True
Direct callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/8021q/vlan_core.c (ffffffff81fceb3e)
Location: include/linux/if_vlan.h:340
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff81da95d0-ffffffff81da96c6: __vlan_insert_inner_tag.constprop.0 (STB_LOCAL)
ffffffff81dbf920-ffffffff81dbf9ee: __vlan_insert_inner_tag.constprop.0 (STB_LOCAL)
ffffffff81e120c0-ffffffff81e1218e: __vlan_insert_inner_tag.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff81e18580)
Location: include/linux/if_vlan.h:348
Inline: True
Direct callers:
  - net/core/skbuff.c:skb_vlan_push
```
```
In net/core/dev.c (ffffffff81e2eab0)
Location: include/linux/if_vlan.h:348
Inline: True
Direct callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff81e858e0)
Location: include/linux/if_vlan.h:348
Inline: True
Direct callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/8021q/vlan_core.c (ffffffff8204a4f4)
Location: include/linux/if_vlan.h:348
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff81e18580-ffffffff81e1868d: __vlan_insert_inner_tag.constprop.0 (STB_LOCAL)
ffffffff81e2eab0-ffffffff81e2eb9b: __vlan_insert_inner_tag.constprop.0 (STB_LOCAL)
ffffffff81e858e0-ffffffff81e859cb: __vlan_insert_inner_tag.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff81ed5a20)
Location: include/linux/if_vlan.h:348
Inline: True
Direct callers:
  - net/core/skbuff.c:skb_vlan_push
```
```
In net/core/dev.c (ffffffff81eed430)
Location: include/linux/if_vlan.h:348
Inline: True
Direct callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff81f47810)
Location: include/linux/if_vlan.h:348
Inline: True
Direct callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/8021q/vlan_core.c (ffffffff8211c960)
Location: include/linux/if_vlan.h:348
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff81ed5a20-ffffffff81ed5b2d: __vlan_insert_inner_tag.constprop.0 (STB_LOCAL)
ffffffff81eed430-ffffffff81eed51b: __vlan_insert_inner_tag.constprop.0 (STB_LOCAL)
ffffffff81f47810-ffffffff81f478fb: __vlan_insert_inner_tag.constprop.0 (STB_LOCAL)
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
In net/core/skbuff.c (ffff800010bb6c48)
Location: include/linux/if_vlan.h:333
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
```
```
In net/core/dev.c (ffff800010bd0cf0)
Location: include/linux/if_vlan.h:333
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffff800010c10b34)
Location: include/linux/if_vlan.h:333
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/8021q/vlan_core.c (ffff800010d604b4)
Location: include/linux/if_vlan.h:333
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (c0cd3aa0)
Location: include/linux/if_vlan.h:333
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
```
```
In net/core/dev.c (c0ceb930)
Location: include/linux/if_vlan.h:333
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (c0d28a74)
Location: include/linux/if_vlan.h:333
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/8021q/vlan_core.c (c0e5ff70)
Location: include/linux/if_vlan.h:333
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (c000000000c8e5b8)
Location: include/linux/if_vlan.h:333
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
```
```
In net/core/dev.c (c000000000caed6c)
Location: include/linux/if_vlan.h:333
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (c000000000cfd728)
Location: include/linux/if_vlan.h:333
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/8021q/vlan_core.c (c000000000e9b478)
Location: include/linux/if_vlan.h:333
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffe0007468a0)
Location: include/linux/if_vlan.h:333
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
```
```
In net/core/dev.c (ffffffe00075b356)
Location: include/linux/if_vlan.h:333
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffe00078d268)
Location: include/linux/if_vlan.h:333
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/8021q/vlan_core.c (ffffffe0008958ac)
Location: include/linux/if_vlan.h:333
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff818bc674)
Location: include/linux/if_vlan.h:333
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
```
```
In net/core/dev.c (ffffffff818d2ce0)
Location: include/linux/if_vlan.h:333
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff8190a759)
Location: include/linux/if_vlan.h:333
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/8021q/vlan_core.c (ffffffff81a31d98)
Location: include/linux/if_vlan.h:333
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff818765b4)
Location: include/linux/if_vlan.h:333
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
```
```
In net/core/dev.c (ffffffff8188cb70)
Location: include/linux/if_vlan.h:333
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff818c47a9)
Location: include/linux/if_vlan.h:333
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/8021q/vlan_core.c (ffffffff819eef88)
Location: include/linux/if_vlan.h:333
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff8190d674)
Location: include/linux/if_vlan.h:333
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
```
```
In net/core/dev.c (ffffffff81923ce0)
Location: include/linux/if_vlan.h:333
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff8195b789)
Location: include/linux/if_vlan.h:333
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/8021q/vlan_core.c (ffffffff81a9d948)
Location: include/linux/if_vlan.h:333
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff8192e7a4)
Location: include/linux/if_vlan.h:333
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
```
```
In net/core/dev.c (ffffffff81945150)
Location: include/linux/if_vlan.h:333
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff8197d9a9)
Location: include/linux/if_vlan.h:333
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/8021q/vlan_core.c (ffffffff81aa9b48)
Location: include/linux/if_vlan.h:333
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
</details>
</li>
</ul>

## Differences
