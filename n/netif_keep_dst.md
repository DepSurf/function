# Function: <code>netif_keep_dst</code>

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
In drivers/net/loopback.c (ffffffff815e95e7)
Location: include/linux/netdevice.h:3944
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_setup
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff815f4cb2)
Location: include/linux/netdevice.h:3944
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_setup
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
In drivers/net/loopback.c (ffffffff81647d37)
Location: include/linux/netdevice.h:4231
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_setup
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8165497d)
Location: include/linux/netdevice.h:4231
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_setup
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
In drivers/net/loopback.c (ffffffff81678e27)
Location: include/linux/netdevice.h:4185
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_setup
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81682668)
Location: include/linux/netdevice.h:4185
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_setup
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
In drivers/net/loopback.c (ffffffff8168d705)
Location: include/linux/netdevice.h:4243
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_setup
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81697a79)
Location: include/linux/netdevice.h:4243
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_setup
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
In drivers/net/loopback.c (ffffffff816f7285)
Location: include/linux/netdevice.h:4277
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_setup
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81702964)
Location: include/linux/netdevice.h:4277
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_setup
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
In drivers/net/loopback.c (ffffffff81734466)
Location: include/linux/netdevice.h:4384
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_setup
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81741685)
Location: include/linux/netdevice.h:4384
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_setup
```
```
In net/sched/cls_api.c (ffffffff818d4b15)
Location: include/linux/netdevice.h:4384
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_netif_keep_dst
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
In drivers/net/loopback.c (ffffffff817575b6)
Location: include/linux/netdevice.h:4626
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_setup
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81765795)
Location: include/linux/netdevice.h:4626
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_setup
```
```
In net/sched/cls_api.c (ffffffff818ff660)
Location: include/linux/netdevice.h:4626
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_netif_keep_dst
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
In drivers/net/loopback.c (ffffffff81793d76)
Location: include/linux/netdevice.h:4652
Inline: True
Inline callers:
  - drivers/net/loopback.c:blackhole_netdev_setup
  - drivers/net/loopback.c:loopback_setup
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817a322f)
Location: include/linux/netdevice.h:4652
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_setup
```
```
In net/sched/cls_api.c (ffffffff8195fe26)
Location: include/linux/netdevice.h:4652
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_netif_keep_dst
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
In drivers/net/loopback.c (ffffffff817b78a6)
Location: include/linux/netdevice.h:4665
Inline: True
Inline callers:
  - drivers/net/loopback.c:blackhole_netdev_setup
  - drivers/net/loopback.c:loopback_setup
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817c6c7f)
Location: include/linux/netdevice.h:4665
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_setup
```
```
In net/sched/cls_api.c (ffffffff81996ee0)
Location: include/linux/netdevice.h:4665
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_netif_keep_dst
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
In drivers/net/loopback.c (ffffffff8187e856)
Location: include/linux/netdevice.h:4858
Inline: True
Inline callers:
  - drivers/net/loopback.c:blackhole_netdev_setup
  - drivers/net/loopback.c:loopback_setup
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81890d4f)
Location: include/linux/netdevice.h:4858
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_setup
```
```
In net/sched/cls_api.c (ffffffff81a6f3e5)
Location: include/linux/netdevice.h:4858
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_netif_keep_dst
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
In drivers/net/loopback.c (ffffffff8188cdd7)
Location: include/linux/netdevice.h:5059
Inline: True
Inline callers:
  - drivers/net/loopback.c:blackhole_netdev_setup
  - drivers/net/loopback.c:loopback_setup
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8189ef2f)
Location: include/linux/netdevice.h:5059
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_setup
```
```
In net/sched/cls_api.c (ffffffff81a77dce)
Location: include/linux/netdevice.h:5059
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_netif_keep_dst
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
In drivers/net/loopback.c (ffffffff8186f735)
Location: include/linux/netdevice.h:5190
Inline: True
Inline callers:
  - drivers/net/loopback.c:blackhole_netdev_setup
  - drivers/net/loopback.c:loopback_setup
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff818819bd)
Location: include/linux/netdevice.h:5190
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_setup
```
```
In net/sched/cls_api.c (ffffffff81a638f8)
Location: include/linux/netdevice.h:5190
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_netif_keep_dst
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
In drivers/net/loopback.c (ffffffff818ffc75)
Location: include/linux/netdevice.h:5238
Inline: True
Inline callers:
  - drivers/net/loopback.c:blackhole_netdev_setup
  - drivers/net/loopback.c:loopback_setup
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8191335d)
Location: include/linux/netdevice.h:5238
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_setup
```
```
In net/sched/cls_api.c (ffffffff81b1ccf7)
Location: include/linux/netdevice.h:5238
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_netif_keep_dst
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
In drivers/net/loopback.c (ffffffff81a5191d)
Location: include/linux/netdevice.h:5058
Inline: True
Inline callers:
  - drivers/net/loopback.c:blackhole_netdev_setup
  - drivers/net/loopback.c:loopback_setup
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81a67c5e)
Location: include/linux/netdevice.h:5058
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_setup
```
```
In net/sched/cls_api.c (ffffffff81ca0f43)
Location: include/linux/netdevice.h:5058
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_netif_keep_dst
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
In drivers/net/loopback.c (ffffffff81bdad9d)
Location: include/linux/netdevice.h:5102
Inline: True
Inline callers:
  - drivers/net/loopback.c:blackhole_netdev_setup
  - drivers/net/loopback.c:loopback_setup
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81bfa5de)
Location: include/linux/netdevice.h:5102
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_setup
```
```
In net/sched/cls_api.c (ffffffff81e5cf83)
Location: include/linux/netdevice.h:5102
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_netif_keep_dst
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
In drivers/net/loopback.c (ffffffff81c3184d)
Location: include/linux/netdevice.h:5146
Inline: True
Inline callers:
  - drivers/net/loopback.c:blackhole_netdev_setup
  - drivers/net/loopback.c:loopback_setup
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81c5fc1e)
Location: include/linux/netdevice.h:5146
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_setup
```
```
In net/sched/cls_api.c (ffffffff81eb9b2b)
Location: include/linux/netdevice.h:5146
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_netif_keep_dst
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
In drivers/net/loopback.c (ffffffff81ce46c2)
Location: include/linux/netdevice.h:5227
Inline: True
Inline callers:
  - drivers/net/loopback.c:blackhole_netdev_setup
  - drivers/net/loopback.c:loopback_setup
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81d165b4)
Location: include/linux/netdevice.h:5227
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_setup
```
```
In net/sched/cls_api.c (ffffffff81f7cd37)
Location: include/linux/netdevice.h:5227
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_netif_keep_dst
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
In drivers/net/loopback.c (ffff8000109cff1c)
Location: include/linux/netdevice.h:4665
Inline: True
Inline callers:
  - drivers/net/loopback.c:blackhole_netdev_setup
  - drivers/net/loopback.c:loopback_setup
```
```
In drivers/net/ppp/ppp_generic.c (ffff8000109fdf44)
Location: include/linux/netdevice.h:4665
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_setup
```
```
In net/sched/cls_api.c (ffff800010c43f78)
Location: include/linux/netdevice.h:4665
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_netif_keep_dst
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
In drivers/net/loopback.c (c0ab8120)
Location: include/linux/netdevice.h:4665
Inline: True
Inline callers:
  - drivers/net/loopback.c:blackhole_netdev_setup
  - drivers/net/loopback.c:loopback_setup
```
```
In drivers/net/ppp/ppp_generic.c (c0adb7ac)
Location: include/linux/netdevice.h:4665
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_setup
```
```
In net/sched/cls_api.c (c0d549bc)
Location: include/linux/netdevice.h:4665
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_netif_keep_dst
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
In drivers/net/loopback.c (c000000000a8ee84)
Location: include/linux/netdevice.h:4665
Inline: True
Inline callers:
  - drivers/net/loopback.c:blackhole_netdev_setup
  - drivers/net/loopback.c:loopback_setup
```
```
In drivers/net/ppp/ppp_generic.c (c000000000aa575c)
Location: include/linux/netdevice.h:4665
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_setup
```
```
In net/sched/cls_api.c (c000000000d3f290)
Location: include/linux/netdevice.h:4665
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_netif_keep_dst
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
In drivers/net/loopback.c (ffffffe00061cb06)
Location: include/linux/netdevice.h:4665
Inline: True
Inline callers:
  - drivers/net/loopback.c:blackhole_netdev_setup
  - drivers/net/loopback.c:loopback_setup
```
```
In drivers/net/ppp/ppp_generic.c (ffffffe00062b722)
Location: include/linux/netdevice.h:4665
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_setup
```
```
In net/sched/cls_api.c (ffffffe0007b2440)
Location: include/linux/netdevice.h:4665
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_netif_keep_dst
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
In drivers/net/loopback.c (ffffffff8177c386)
Location: include/linux/netdevice.h:4665
Inline: True
Inline callers:
  - drivers/net/loopback.c:blackhole_netdev_setup
  - drivers/net/loopback.c:loopback_setup
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8178b75f)
Location: include/linux/netdevice.h:4665
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_setup
```
```
In net/sched/cls_api.c (ffffffff81936d50)
Location: include/linux/netdevice.h:4665
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_netif_keep_dst
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
In drivers/net/loopback.c (ffffffff8175c136)
Location: include/linux/netdevice.h:4665
Inline: True
Inline callers:
  - drivers/net/loopback.c:blackhole_netdev_setup
  - drivers/net/loopback.c:loopback_setup
```
```
In drivers/net/vxlan.c (ffffffff8176c111)
Location: include/linux/netdevice.h:4665
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_setup
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8177452f)
Location: include/linux/netdevice.h:4665
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_setup
```
```
In net/sched/cls_api.c (ffffffff818f0850)
Location: include/linux/netdevice.h:4665
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_netif_keep_dst
```
```
In net/ipv4/ip_tunnel.c (ffffffff8196726a)
Location: include/linux/netdevice.h:4665
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel.c:ip_tunnel_init
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
In drivers/net/loopback.c (ffffffff817ac726)
Location: include/linux/netdevice.h:4665
Inline: True
Inline callers:
  - drivers/net/loopback.c:blackhole_netdev_setup
  - drivers/net/loopback.c:loopback_setup
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817bbaff)
Location: include/linux/netdevice.h:4665
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_setup
```
```
In net/sched/cls_api.c (ffffffff81987ee0)
Location: include/linux/netdevice.h:4665
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_netif_keep_dst
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
In drivers/net/loopback.c (ffffffff817c66b6)
Location: include/linux/netdevice.h:4665
Inline: True
Inline callers:
  - drivers/net/loopback.c:blackhole_netdev_setup
  - drivers/net/loopback.c:loopback_setup
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817d5d4f)
Location: include/linux/netdevice.h:4665
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_setup
```
```
In net/sched/cls_api.c (ffffffff819aa140)
Location: include/linux/netdevice.h:4665
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_netif_keep_dst
```
</details>
</li>
</ul>

## Differences
