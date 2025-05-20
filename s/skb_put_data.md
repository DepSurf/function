# Function: <code>skb_put_data</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81485797)
Location: include/linux/skbuff.h:1954
Inline: True
Inline callers:
  - lib/nlattr.c:nla_append
```
```
In net/netlink/af_netlink.c (ffffffff8180754e)
Location: include/linux/skbuff.h:1954
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/ipv6/mcast.c (ffffffff818b117d)
Location: include/linux/skbuff.h:1954
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
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
In lib/nlattr.c (ffffffff814c1927)
Location: include/linux/skbuff.h:2041
Inline: True
Inline callers:
  - lib/nlattr.c:nla_append
```
```
In net/netlink/af_netlink.c (ffffffff81886095)
Location: include/linux/skbuff.h:2041
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/ipv6/mcast.c (ffffffff819337cd)
Location: include/linux/skbuff.h:2041
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
```
```
In lib/kobject_uevent.c (ffffffff81975ab6)
Location: include/linux/skbuff.h:2041
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
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
In lib/nlattr.c (ffffffff814f2657)
Location: include/linux/skbuff.h:2052
Inline: True
Inline callers:
  - lib/nlattr.c:nla_append
```
```
In net/netlink/af_netlink.c (ffffffff818d9a55)
Location: include/linux/skbuff.h:2052
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/ipv6/mcast.c (ffffffff8198c159)
Location: include/linux/skbuff.h:2052
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
```
```
In lib/kobject_uevent.c (ffffffff819d1af3)
Location: include/linux/skbuff.h:2052
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:alloc_uevent_skb
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
In lib/nlattr.c (ffffffff81506384)
Location: include/linux/skbuff.h:2130
Inline: True
Inline callers:
  - lib/nlattr.c:nla_append
```
```
In net/netlink/af_netlink.c (ffffffff819064a8)
Location: include/linux/skbuff.h:2130
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/ipv6/mcast.c (ffffffff819c2be0)
Location: include/linux/skbuff.h:2130
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
```
```
In lib/kobject_uevent.c (ffffffff81a0b9f0)
Location: include/linux/skbuff.h:2130
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:alloc_uevent_skb
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
In lib/nlattr.c (ffffffff81534d4b)
Location: include/linux/skbuff.h:2218
Inline: True
Inline callers:
  - lib/nlattr.c:nla_append
```
```
In net/netlink/af_netlink.c (ffffffff819676e2)
Location: include/linux/skbuff.h:2218
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/ipv6/mcast.c (ffffffff81a319f7)
Location: include/linux/skbuff.h:2218
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
```
```
In lib/kobject_uevent.c (ffffffff81a7b3d0)
Location: include/linux/skbuff.h:2218
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:alloc_uevent_skb
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
In lib/nlattr.c (ffffffff81555b7b)
Location: include/linux/skbuff.h:2232
Inline: True
Inline callers:
  - lib/nlattr.c:nla_append
```
```
In net/netlink/af_netlink.c (ffffffff8199e172)
Location: include/linux/skbuff.h:2232
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/ipv6/mcast.c (ffffffff81a68547)
Location: include/linux/skbuff.h:2232
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
```
```
In lib/kobject_uevent.c (ffffffff81ab2730)
Location: include/linux/skbuff.h:2232
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:alloc_uevent_skb
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
In lib/nlattr.c (ffffffff815de931)
Location: include/linux/skbuff.h:2255
Inline: True
Inline callers:
  - lib/nlattr.c:nla_append
```
```
In lib/kobject_uevent.c (ffffffff815eccc2)
Location: include/linux/skbuff.h:2255
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_broadcast
  - lib/kobject_uevent.c:alloc_uevent_skb
```
```
In net/netlink/af_netlink.c (ffffffff81a76d44)
Location: include/linux/skbuff.h:2255
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81b61817)
Location: include/linux/skbuff.h:2255
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
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
In lib/nlattr.c (ffffffff815fbfd1)
Location: include/linux/skbuff.h:2276
Inline: True
Inline callers:
  - lib/nlattr.c:nla_append
```
```
In lib/kobject_uevent.c (ffffffff816114a2)
Location: include/linux/skbuff.h:2276
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_broadcast
  - lib/kobject_uevent.c:alloc_uevent_skb
```
```
In net/netlink/af_netlink.c (ffffffff81a7fac4)
Location: include/linux/skbuff.h:2276
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81b6ff99)
Location: include/linux/skbuff.h:2276
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
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
In lib/nlattr.c (ffffffff815dec11)
Location: include/linux/skbuff.h:2292
Inline: True
Inline callers:
  - lib/nlattr.c:nla_append
```
```
In lib/kobject_uevent.c (ffffffff815f4ba0)
Location: include/linux/skbuff.h:2292
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:alloc_uevent_skb
```
```
In net/netlink/af_netlink.c (ffffffff81a68b15)
Location: include/linux/skbuff.h:2292
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/ipv6/mcast.c (ffffffff81b5e25e)
Location: include/linux/skbuff.h:2292
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
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
In lib/nlattr.c (ffffffff8164a791)
Location: include/linux/skbuff.h:2321
Inline: True
Inline callers:
  - lib/nlattr.c:nla_append
```
```
In lib/kobject_uevent.c (ffffffff81661f70)
Location: include/linux/skbuff.h:2321
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:alloc_uevent_skb
```
```
In net/netlink/af_netlink.c (ffffffff81b220ac)
Location: include/linux/skbuff.h:2321
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/ipv6/mcast.c (ffffffff81c2570e)
Location: include/linux/skbuff.h:2321
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
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
In lib/nlattr.c (ffffffff81760f4b)
Location: include/linux/skbuff.h:2680
Inline: True
Inline callers:
  - lib/nlattr.c:nla_append
```
```
In lib/kobject_uevent.c (ffffffff8177bcb0)
Location: include/linux/skbuff.h:2680
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:alloc_uevent_skb
```
```
In net/netlink/af_netlink.c (ffffffff81caad08)
Location: include/linux/skbuff.h:2680
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/ipv6/mcast.c (ffffffff81dc2ea5)
Location: include/linux/skbuff.h:2680
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
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
In lib/nlattr.c (ffffffff8188fc2b)
Location: include/linux/skbuff.h:2577
Inline: True
Inline callers:
  - lib/nlattr.c:nla_append
```
```
In net/netlink/af_netlink.c (ffffffff81e67d83)
Location: include/linux/skbuff.h:2577
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81f938f5)
Location: include/linux/skbuff.h:2577
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
```
```
In lib/kobject_uevent.c (ffffffff82024f20)
Location: include/linux/skbuff.h:2577
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:alloc_uevent_skb
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
In lib/nlattr.c (ffffffff818d209b)
Location: include/linux/skbuff.h:2620
Inline: True
Inline callers:
  - lib/nlattr.c:nla_append
```
```
In drivers/net/virtio_net.c (ffffffff81c53505)
Location: include/linux/skbuff.h:2620
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:page_to_skb
```
```
In net/netlink/af_netlink.c (ffffffff81ec3be3)
Location: include/linux/skbuff.h:2620
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81ff29b0)
Location: include/linux/skbuff.h:2620
Inline: True
Direct callers:
  - net/ipv6/mcast.c:igmp6_send
```
```
In lib/kobject_uevent.c (ffffffff820a5030)
Location: include/linux/skbuff.h:2620
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:alloc_uevent_skb
```
**Symbols:**

```
ffffffff81ff29b0-ffffffff81ff29da: skb_put_data.constprop.0.isra.0 (STB_LOCAL)
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
In lib/nlattr.c (ffffffff8192406b)
Location: include/linux/skbuff.h:2627
Inline: True
Inline callers:
  - lib/nlattr.c:nla_append
```
```
In drivers/net/virtio_net.c (ffffffff81d09cb5)
Location: include/linux/skbuff.h:2627
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:page_to_skb
```
```
In net/netlink/af_netlink.c (ffffffff81f86fa0)
Location: include/linux/skbuff.h:2627
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff820c0620)
Location: include/linux/skbuff.h:2627
Inline: True
Direct callers:
  - net/ipv6/mcast.c:igmp6_send
```
```
In lib/kobject_uevent.c (ffffffff8217d190)
Location: include/linux/skbuff.h:2627
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:alloc_uevent_skb
```
**Symbols:**

```
ffffffff820c0620-ffffffff820c064a: skb_put_data.constprop.0.isra.0 (STB_LOCAL)
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
In lib/nlattr.c (ffff800010662070)
Location: include/linux/skbuff.h:2232
Inline: True
Inline callers:
  - lib/nlattr.c:nla_append
```
```
In net/netlink/af_netlink.c (ffff800010c4b680)
Location: include/linux/skbuff.h:2232
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/ipv6/mcast.c (ffff800010d2ffd0)
Location: include/linux/skbuff.h:2232
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
```
```
In lib/kobject_uevent.c (ffff800010d8ca7c)
Location: include/linux/skbuff.h:2232
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:alloc_uevent_skb
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
In lib/nlattr.c (c080b0e4)
Location: include/linux/skbuff.h:2232
Inline: True
Inline callers:
  - lib/nlattr.c:nla_append
```
```
In net/netlink/af_netlink.c (c0d5c0ec)
Location: include/linux/skbuff.h:2232
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/ipv6/mcast.c (c0e337ec)
Location: include/linux/skbuff.h:2232
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
```
```
In lib/kobject_uevent.c (c0e86e60)
Location: include/linux/skbuff.h:2232
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:alloc_uevent_skb
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
In lib/nlattr.c (c0000000008163d8)
Location: include/linux/skbuff.h:2232
Inline: True
Inline callers:
  - lib/nlattr.c:nla_append
```
```
In net/netlink/af_netlink.c (c000000000d498ac)
Location: include/linux/skbuff.h:2232
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/ipv6/mcast.c (c000000000e6124c)
Location: include/linux/skbuff.h:2232
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
```
```
In lib/kobject_uevent.c (c000000000ecdbd4)
Location: include/linux/skbuff.h:2232
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:alloc_uevent_skb
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
In lib/nlattr.c (ffffffe00048e9fa)
Location: include/linux/skbuff.h:2232
Inline: True
Inline callers:
  - lib/nlattr.c:nla_append
```
```
In net/netlink/af_netlink.c (ffffffe0007b8d7e)
Location: include/linux/skbuff.h:2232
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/ipv6/mcast.c (ffffffe00086f72c)
Location: include/linux/skbuff.h:2232
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
```
```
In lib/kobject_uevent.c (ffffffe0008b512a)
Location: include/linux/skbuff.h:2232
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:alloc_uevent_skb
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
In lib/nlattr.c (ffffffff8154e15b)
Location: include/linux/skbuff.h:2232
Inline: True
Inline callers:
  - lib/nlattr.c:nla_append
```
```
In net/netlink/af_netlink.c (ffffffff8193dfe2)
Location: include/linux/skbuff.h:2232
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/ipv6/mcast.c (ffffffff81a07bd7)
Location: include/linux/skbuff.h:2232
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
```
```
In lib/kobject_uevent.c (ffffffff81a51580)
Location: include/linux/skbuff.h:2232
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:alloc_uevent_skb
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
In lib/nlattr.c (ffffffff8153e43b)
Location: include/linux/skbuff.h:2232
Inline: True
Inline callers:
  - lib/nlattr.c:nla_append
```
```
In net/netlink/af_netlink.c (ffffffff818f7ae2)
Location: include/linux/skbuff.h:2232
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/ipv6/mcast.c (ffffffff819c4997)
Location: include/linux/skbuff.h:2232
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
```
```
In lib/kobject_uevent.c (ffffffff81a0e680)
Location: include/linux/skbuff.h:2232
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:alloc_uevent_skb
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
In lib/nlattr.c (ffffffff81549e9b)
Location: include/linux/skbuff.h:2232
Inline: True
Inline callers:
  - lib/nlattr.c:nla_append
```
```
In net/netlink/af_netlink.c (ffffffff8198f172)
Location: include/linux/skbuff.h:2232
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/ipv6/mcast.c (ffffffff81a72657)
Location: include/linux/skbuff.h:2232
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
```
```
In lib/kobject_uevent.c (ffffffff81abd970)
Location: include/linux/skbuff.h:2232
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:alloc_uevent_skb
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
In lib/nlattr.c (ffffffff81563ceb)
Location: include/linux/skbuff.h:2232
Inline: True
Inline callers:
  - lib/nlattr.c:nla_append
```
```
In net/netlink/af_netlink.c (ffffffff819b1a5a)
Location: include/linux/skbuff.h:2232
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/ipv6/mcast.c (ffffffff81a7ece2)
Location: include/linux/skbuff.h:2232
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
```
```
In lib/kobject_uevent.c (ffffffff81ac9df0)
Location: include/linux/skbuff.h:2232
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:alloc_uevent_skb
```
</details>
</li>
</ul>

## Differences
