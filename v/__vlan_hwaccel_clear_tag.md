# Function: <code>__vlan_hwaccel_clear_tag</code>

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
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818a1ea5)
Location: include/linux/if_vlan.h:481
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_pop
```
```
In net/core/dev.c (ffffffff818b617d)
Location: include/linux/if_vlan.h:481
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff818e7fee)
Location: include/linux/if_vlan.h:481
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8196bce0)
Location: include/linux/if_vlan.h:481
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/8021q/vlan_core.c (ffffffff819ec852)
Location: include/linux/if_vlan.h:481
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
In net/core/skbuff.c (ffffffff818ec885)
Location: include/linux/if_vlan.h:476
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_pop
```
```
In net/core/dev.c (ffffffff819025ce)
Location: include/linux/if_vlan.h:476
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff8193795f)
Location: include/linux/if_vlan.h:476
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819d2a30)
Location: include/linux/if_vlan.h:476
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/8021q/vlan_core.c (ffffffff81a5ba02)
Location: include/linux/if_vlan.h:476
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
In net/core/skbuff.c (ffffffff8191e9b5)
Location: include/linux/if_vlan.h:465
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_pop
```
```
In net/core/dev.c (ffffffff8193480e)
Location: include/linux/if_vlan.h:465
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff8196a81f)
Location: include/linux/if_vlan.h:465
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a095a0)
Location: include/linux/if_vlan.h:465
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/8021q/vlan_core.c (ffffffff81a92632)
Location: include/linux/if_vlan.h:465
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
In net/core/skbuff.c (ffffffff819f1235)
Location: include/linux/if_vlan.h:467
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_pop
```
```
In net/core/dev.c (ffffffff81a012cb)
Location: include/linux/if_vlan.h:467
Inline: True
Inline callers:
  - net/core/dev.c:napi_reuse_skb
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:validate_xmit_vlan
```
```
In net/core/netpoll.c (ffffffff81a3df1f)
Location: include/linux/if_vlan.h:467
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af8ec0)
Location: include/linux/if_vlan.h:467
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/8021q/vlan_core.c (ffffffff81b8dae2)
Location: include/linux/if_vlan.h:467
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
In net/core/skbuff.c (ffffffff819f11bd)
Location: include/linux/if_vlan.h:467
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_pop
```
```
In net/core/dev.c (ffffffff81a01abb)
Location: include/linux/if_vlan.h:467
Inline: True
Inline callers:
  - net/core/dev.c:napi_reuse_skb
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:validate_xmit_vlan
```
```
In net/core/netpoll.c (ffffffff81a40c41)
Location: include/linux/if_vlan.h:467
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/sched/sch_frag.c (ffffffff81a6f440)
Location: include/linux/if_vlan.h:467
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b06eb0)
Location: include/linux/if_vlan.h:467
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/8021q/vlan_core.c (ffffffff81b9d798)
Location: include/linux/if_vlan.h:467
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
In net/core/skbuff.c (ffffffff819d6465)
Location: include/linux/if_vlan.h:467
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_pop
```
```
In net/core/dev.c (ffffffff819e8a6b)
Location: include/linux/if_vlan.h:467
Inline: True
Inline callers:
  - net/core/dev.c:napi_reuse_skb
  - net/core/dev.c:validate_xmit_vlan
```
```
In net/core/netpoll.c (ffffffff81a258ff)
Location: include/linux/if_vlan.h:467
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/sched/sch_frag.c (0)
Location: include/linux/if_vlan.h:467
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af2608)
Location: include/linux/if_vlan.h:467
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/8021q/vlan_core.c (ffffffff81b8c8a7)
Location: include/linux/if_vlan.h:467
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
In net/core/skbuff.c (ffffffff81a86ab5)
Location: include/linux/if_vlan.h:467
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_pop
```
```
In net/core/dev.c (ffffffff81a9620b)
Location: include/linux/if_vlan.h:467
Inline: True
Inline callers:
  - net/core/dev.c:napi_reuse_skb
  - net/core/dev.c:validate_xmit_vlan
```
```
In net/core/netpoll.c (ffffffff81ada63f)
Location: include/linux/if_vlan.h:467
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/sched/sch_frag.c (0)
Location: include/linux/if_vlan.h:467
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb2b18)
Location: include/linux/if_vlan.h:467
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/8021q/vlan_core.c (ffffffff81c58c67)
Location: include/linux/if_vlan.h:467
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff81bfc1fb)
Location: include/linux/if_vlan.h:472
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_pop
```
```
In net/core/dev.c (ffffffff81c18f23)
Location: include/linux/if_vlan.h:472
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/gro.c (ffffffff81c53796)
Location: include/linux/if_vlan.h:472
Inline: True
Inline callers:
  - net/core/gro.c:napi_reuse_skb
```
```
In net/core/netpoll.c (ffffffff81c5bdb5)
Location: include/linux/if_vlan.h:472
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/sched/sch_frag.c (ffffffff81c97e28)
Location: include/linux/if_vlan.h:472
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d462d8)
Location: include/linux/if_vlan.h:472
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/8021q/vlan_core.c (ffffffff81dfa35b)
Location: include/linux/if_vlan.h:472
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff81dab0ca)
Location: include/linux/if_vlan.h:472
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_pop
```
```
In net/core/dev.c (ffffffff81dc9ef4)
Location: include/linux/if_vlan.h:472
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/gro.c (ffffffff81e08e5b)
Location: include/linux/if_vlan.h:472
Inline: True
Inline callers:
  - net/core/gro.c:napi_reuse_skb
```
```
In net/core/netpoll.c (ffffffff81e1220f)
Location: include/linux/if_vlan.h:472
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/sched/sch_frag.c (ffffffff81e53dfe)
Location: include/linux/if_vlan.h:472
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0f6c8)
Location: include/linux/if_vlan.h:472
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/8021q/vlan_core.c (ffffffff81fcea7e)
Location: include/linux/if_vlan.h:472
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff81e1abca)
Location: include/linux/if_vlan.h:481
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_pop
```
```
In net/core/dev.c (ffffffff81e3aa84)
Location: include/linux/if_vlan.h:481
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/gro.c (ffffffff81e7b57b)
Location: include/linux/if_vlan.h:481
Inline: True
Inline callers:
  - net/core/gro.c:napi_reuse_skb
```
```
In net/core/netpoll.c (ffffffff81e85a4f)
Location: include/linux/if_vlan.h:481
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/sched/sch_frag.c (ffffffff81eaf678)
Location: include/linux/if_vlan.h:481
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6f3b8)
Location: include/linux/if_vlan.h:481
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/8021q/vlan_core.c (ffffffff8204a3e6)
Location: include/linux/if_vlan.h:481
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff81ed826a)
Location: include/linux/if_vlan.h:481
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_pop
```
```
In net/core/dev.c (ffffffff81ef8e34)
Location: include/linux/if_vlan.h:481
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/gro.c (ffffffff81f3b80b)
Location: include/linux/if_vlan.h:481
Inline: True
Inline callers:
  - net/core/gro.c:napi_reuse_skb
```
```
In net/core/netpoll.c (ffffffff81f4797f)
Location: include/linux/if_vlan.h:481
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/sched/sch_frag.c (ffffffff81f720f8)
Location: include/linux/if_vlan.h:481
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff82035ae8)
Location: include/linux/if_vlan.h:481
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/8021q/vlan_core.c (ffffffff8211c852)
Location: include/linux/if_vlan.h:481
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffff800010bb9178)
Location: include/linux/if_vlan.h:465
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_pop
```
```
In net/core/dev.c (ffff800010bd2ac8)
Location: include/linux/if_vlan.h:465
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffff800010c10ba8)
Location: include/linux/if_vlan.h:465
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/ipv4/ip_tunnel_core.c (ffff800010cc2940)
Location: include/linux/if_vlan.h:465
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/8021q/vlan_core.c (ffff800010d6038c)
Location: include/linux/if_vlan.h:465
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
In net/core/skbuff.c (c0cd5c38)
Location: include/linux/if_vlan.h:465
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_pop
```
```
In net/core/dev.c (c0ce4bc8)
Location: include/linux/if_vlan.h:465
Inline: True
Inline callers:
  - net/core/dev.c:napi_reuse_skb
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (c0d28ae4)
Location: include/linux/if_vlan.h:465
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/ipv4/ip_tunnel_core.c (c0dce1a0)
Location: include/linux/if_vlan.h:465
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/8021q/vlan_core.c (c0e5fe8c)
Location: include/linux/if_vlan.h:465
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
In net/core/skbuff.c (c000000000c916ac)
Location: include/linux/if_vlan.h:465
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_pop
```
```
In net/core/dev.c (c000000000cb1330)
Location: include/linux/if_vlan.h:465
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (c000000000cfd7b8)
Location: include/linux/if_vlan.h:465
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/ipv4/ip_tunnel_core.c (c000000000dde1b0)
Location: include/linux/if_vlan.h:465
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/8021q/vlan_core.c (c000000000e9b3a4)
Location: include/linux/if_vlan.h:465
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
In net/core/skbuff.c (ffffffe000748756)
Location: include/linux/if_vlan.h:465
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_pop
```
```
In net/core/dev.c (ffffffe00075d17e)
Location: include/linux/if_vlan.h:465
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffe00078d2d8)
Location: include/linux/if_vlan.h:465
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/ipv4/ip_tunnel_core.c (ffffffe000817da6)
Location: include/linux/if_vlan.h:465
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/8021q/vlan_core.c (ffffffe0008957e6)
Location: include/linux/if_vlan.h:465
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
In net/core/skbuff.c (ffffffff818be9b5)
Location: include/linux/if_vlan.h:465
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_pop
```
```
In net/core/dev.c (ffffffff818d480e)
Location: include/linux/if_vlan.h:465
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff8190a7ef)
Location: include/linux/if_vlan.h:465
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819a9340)
Location: include/linux/if_vlan.h:465
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/8021q/vlan_core.c (ffffffff81a31cc2)
Location: include/linux/if_vlan.h:465
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
In net/core/skbuff.c (ffffffff818788f5)
Location: include/linux/if_vlan.h:465
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_pop
```
```
In net/core/dev.c (ffffffff8188e69e)
Location: include/linux/if_vlan.h:465
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff818c483f)
Location: include/linux/if_vlan.h:465
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81962e00)
Location: include/linux/if_vlan.h:465
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/8021q/vlan_core.c (ffffffff819eeeb2)
Location: include/linux/if_vlan.h:465
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
In net/core/skbuff.c (ffffffff8190f9b5)
Location: include/linux/if_vlan.h:465
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_pop
```
```
In net/core/dev.c (ffffffff8192580e)
Location: include/linux/if_vlan.h:465
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff8195b81f)
Location: include/linux/if_vlan.h:465
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a13be0)
Location: include/linux/if_vlan.h:465
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/8021q/vlan_core.c (ffffffff81a9d872)
Location: include/linux/if_vlan.h:465
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
In net/core/skbuff.c (ffffffff81930ae5)
Location: include/linux/if_vlan.h:465
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_pop
```
```
In net/core/dev.c (ffffffff81946d17)
Location: include/linux/if_vlan.h:465
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff8197da3f)
Location: include/linux/if_vlan.h:465
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a1e5c0)
Location: include/linux/if_vlan.h:465
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/8021q/vlan_core.c (ffffffff81aa9a72)
Location: include/linux/if_vlan.h:465
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
</details>
</li>
</ul>

## Differences
