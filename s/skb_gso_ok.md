# Function: <code>skb_gso_ok</code>

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
In drivers/net/xen-netfront.c (ffffffff815facba)
Location: include/linux/netdevice.h:3825
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff8171c668)
Location: include/linux/netdevice.h:3825
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff81783292)
Location: include/linux/netdevice.h:3825
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff8178b33c)
Location: include/linux/netdevice.h:3825
Inline: True
```
```
In net/ipv6/udp_offload.c (ffffffff8180167f)
Location: include/linux/netdevice.h:3825
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
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
In drivers/net/xen-netfront.c (ffffffff8165ab9c)
Location: include/linux/netdevice.h:4107
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff8178501c)
Location: include/linux/netdevice.h:4107
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/ipv4/tcp_offload.c (ffffffff817f0824)
Location: include/linux/netdevice.h:4107
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff817f8bee)
Location: include/linux/netdevice.h:4107
Inline: True
```
```
In net/ipv6/udp_offload.c (ffffffff818669ed)
Location: include/linux/netdevice.h:4107
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
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
In drivers/net/xen-netfront.c (ffffffff81688929)
Location: include/linux/netdevice.h:4061
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff817b262c)
Location: include/linux/netdevice.h:4061
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/ipv4/tcp_offload.c (ffffffff8182159b)
Location: include/linux/netdevice.h:4061
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff81829abe)
Location: include/linux/netdevice.h:4061
Inline: True
```
```
In net/ipv6/udp_offload.c (ffffffff818990ed)
Location: include/linux/netdevice.h:4061
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
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
In drivers/net/xen-netfront.c (ffffffff8169e0da)
Location: include/linux/netdevice.h:4114
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff817cfe31)
Location: include/linux/netdevice.h:4114
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/ipv4/tcp_offload.c (ffffffff8184227b)
Location: include/linux/netdevice.h:4114
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff8184ad0f)
Location: include/linux/netdevice.h:4114
Inline: True
```
```
In net/ipv6/udp_offload.c (ffffffff818bf30d)
Location: include/linux/netdevice.h:4114
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
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
In drivers/net/xen-netfront.c (ffffffff8170927a)
Location: include/linux/netdevice.h:4148
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff81849781)
Location: include/linux/netdevice.h:4148
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/ipv4/tcp_offload.c (ffffffff818c1b58)
Location: include/linux/netdevice.h:4148
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
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
In drivers/net/xen-netfront.c (ffffffff81747fef)
Location: include/linux/netdevice.h:4255
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff81893773)
Location: include/linux/netdevice.h:4255
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/ipv4/tcp_offload.c (ffffffff8191782d)
Location: include/linux/netdevice.h:4255
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
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
In drivers/net/xen-netfront.c (ffffffff8176c0bc)
Location: include/linux/netdevice.h:4492
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff818b4192)
Location: include/linux/netdevice.h:4492
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/ipv4/tcp_offload.c (ffffffff81945f64)
Location: include/linux/netdevice.h:4492
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
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
In drivers/net/xen-netfront.c (ffffffff817a9ecc)
Location: include/linux/netdevice.h:4518
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff81900a86)
Location: include/linux/netdevice.h:4518
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/ipv4/tcp_offload.c (ffffffff819aa592)
Location: include/linux/netdevice.h:4518
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
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
In drivers/net/xen-netfront.c (ffffffff817cd934)
Location: include/linux/netdevice.h:4531
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff81932db6)
Location: include/linux/netdevice.h:4531
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/ipv4/tcp_offload.c (ffffffff819e1262)
Location: include/linux/netdevice.h:4531
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
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
In drivers/net/xen-netfront.c (ffffffff818994cf)
Location: include/linux/netdevice.h:4724
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff81a07cbb)
Location: include/linux/netdevice.h:4724
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/ipv4/tcp_offload.c (ffffffff81ace8a2)
Location: include/linux/netdevice.h:4724
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
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
In drivers/net/xen-netfront.c (ffffffff818a79f2)
Location: include/linux/netdevice.h:4920
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff81a0938b)
Location: include/linux/netdevice.h:4920
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/ipv4/tcp_offload.c (ffffffff81ada8c2)
Location: include/linux/netdevice.h:4920
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
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
In drivers/net/xen-netfront.c (ffffffff8188b287)
Location: include/linux/netdevice.h:5051
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff819efd0b)
Location: include/linux/netdevice.h:5051
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/ipv4/tcp_offload.c (ffffffff81ac58f4)
Location: include/linux/netdevice.h:5051
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
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
In drivers/net/xen-netfront.c (ffffffff8191db02)
Location: include/linux/netdevice.h:5099
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff81aa1140)
Location: include/linux/netdevice.h:5099
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/ipv4/tcp_offload.c (ffffffff81b84104)
Location: include/linux/netdevice.h:5099
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
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
In drivers/net/xen-netfront.c (ffffffff81a751cc)
Location: include/linux/netdevice.h:4920
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff81c18fe6)
Location: include/linux/netdevice.h:4920
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/ipv4/tcp_offload.c (ffffffff81d148dc)
Location: include/linux/netdevice.h:4920
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
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
In drivers/net/xen-netfront.c (ffffffff81c06b5b)
Location: include/linux/netdevice.h:4964
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff81dc9fbc)
Location: include/linux/netdevice.h:4964
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/ipv4/tcp_offload.c (ffffffff81edaa1c)
Location: include/linux/netdevice.h:4964
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff81ee7611)
Location: include/linux/netdevice.h:4964
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
```
```
In net/ipv6/udp_offload.c (ffffffff81fa6576)
Location: include/linux/netdevice.h:4964
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
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
In drivers/net/xen-netfront.c (ffffffff81c6c25e)
Location: include/linux/netdevice.h:5012
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff81e3ab38)
Location: include/linux/netdevice.h:5012
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/gso.c (ffffffff81e7d70e)
Location: include/linux/netdevice.h:5012
Inline: True
Inline callers:
  - net/core/gso.c:__skb_gso_segment
```
```
In net/ipv4/tcp_offload.c (ffffffff81f39b03)
Location: include/linux/netdevice.h:5012
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff81f462ad)
Location: include/linux/netdevice.h:5012
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
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
In drivers/net/xen-netfront.c (ffffffff81d20c0e)
Location: include/linux/netdevice.h:5088
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff81ef8edc)
Location: include/linux/netdevice.h:5088
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/gso.c (ffffffff81f3e68b)
Location: include/linux/netdevice.h:5088
Inline: True
Inline callers:
  - net/core/gso.c:__skb_gso_segment
```
```
In net/ipv4/tcp_offload.c (ffffffff81fffbf3)
Location: include/linux/netdevice.h:5088
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff8200c3ed)
Location: include/linux/netdevice.h:5088
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
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
In drivers/net/xen-netfront.c (ffff800010a09474)
Location: include/linux/netdevice.h:4531
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffff800010bd0d94)
Location: include/linux/netdevice.h:4531
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/ipv4/tcp_offload.c (ffff800010c9529c)
Location: include/linux/netdevice.h:4531
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
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
In net/core/dev.c (c0ceb9d0)
Location: include/linux/netdevice.h:4531
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/ipv4/tcp_offload.c (c0da39b4)
Location: include/linux/netdevice.h:4531
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
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
In net/core/dev.c (c000000000caee44)
Location: include/linux/netdevice.h:4531
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/ipv4/tcp_offload.c (c000000000da6250)
Location: include/linux/netdevice.h:4531
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
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
In net/core/dev.c (ffffffe00075b3f2)
Location: include/linux/netdevice.h:4531
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/ipv4/tcp_offload.c (ffffffe0007f44bc)
Location: include/linux/netdevice.h:4531
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
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
In drivers/net/xen-netfront.c (ffffffff81792554)
Location: include/linux/netdevice.h:4531
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff818d2db6)
Location: include/linux/netdevice.h:4531
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/ipv4/tcp_offload.c (ffffffff819810d2)
Location: include/linux/netdevice.h:4531
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
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
In net/core/dev.c (ffffffff8188cc46)
Location: include/linux/netdevice.h:4531
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/ipv4/tcp_offload.c (ffffffff8193ab92)
Location: include/linux/netdevice.h:4531
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
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
In drivers/net/xen-netfront.c (ffffffff817c27b4)
Location: include/linux/netdevice.h:4531
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff81923db6)
Location: include/linux/netdevice.h:4531
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/ipv4/tcp_offload.c (ffffffff819eb8a2)
Location: include/linux/netdevice.h:4531
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
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
In drivers/net/xen-netfront.c (ffffffff817dca74)
Location: include/linux/netdevice.h:4531
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff81945226)
Location: include/linux/netdevice.h:4531
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/ipv4/tcp_offload.c (ffffffff819f5752)
Location: include/linux/netdevice.h:4531
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
</details>
</li>
</ul>

## Differences
