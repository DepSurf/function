# Function: <code>nlmsg_find_attr</code>

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
In net/core/neighbour.c (ffffffff81729954)
Location: include/net/netlink.h:387
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff8172aaa2)
Location: include/net/netlink.h:387
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
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
In net/core/neighbour.c (ffffffff81793458)
Location: include/net/netlink.h:398
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff81794742)
Location: include/net/netlink.h:398
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
```
```
In net/switchdev/switchdev.c (ffffffff8188ad06)
Location: include/net/netlink.h:398
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_bridge_dellink
  - net/switchdev/switchdev.c:switchdev_port_bridge_setlink
  - net/switchdev/switchdev.c:switchdev_port_bridge_setlink
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
In net/core/neighbour.c (ffffffff817c0d28)
Location: include/net/netlink.h:398
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff817c1fc2)
Location: include/net/netlink.h:398
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
```
```
In net/switchdev/switchdev.c (ffffffff818bf0d7)
Location: include/net/netlink.h:398
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_bridge_dellink
  - net/switchdev/switchdev.c:switchdev_port_bridge_setlink
  - net/switchdev/switchdev.c:switchdev_port_bridge_setlink
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
In net/core/neighbour.c (ffffffff817df4bb)
Location: include/net/netlink.h:404
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff817e0742)
Location: include/net/netlink.h:404
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
```
```
In net/switchdev/switchdev.c (ffffffff818e5a12)
Location: include/net/netlink.h:404
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_bridge_dellink
  - net/switchdev/switchdev.c:switchdev_port_bridge_setlink
  - net/switchdev/switchdev.c:switchdev_port_bridge_setlink
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
In net/core/neighbour.c (ffffffff81859d8b)
Location: include/net/netlink.h:410
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff8185afc5)
Location: include/net/netlink.h:410
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
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
In net/core/neighbour.c (ffffffff818a5553)
Location: include/net/netlink.h:410
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff818a6880)
Location: include/net/netlink.h:410
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
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
In net/core/neighbour.c (ffffffff818c8ab6)
Location: include/net/netlink.h:553
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff818ca0e0)
Location: include/net/netlink.h:553
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
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
In net/core/neighbour.c (ffffffff81915647)
Location: include/net/netlink.h:738
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff819170b0)
Location: include/net/netlink.h:738
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
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
In net/core/neighbour.c (ffffffff81947cb7)
Location: include/net/netlink.h:738
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff819496f0)
Location: include/net/netlink.h:738
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
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
In net/core/neighbour.c (ffffffff81a17e43)
Location: include/net/netlink.h:790
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff81a19a80)
Location: include/net/netlink.h:790
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
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
In net/core/neighbour.c (ffffffff81a180e3)
Location: include/net/netlink.h:804
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff81a19c70)
Location: include/net/netlink.h:804
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
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
In net/core/neighbour.c (ffffffff819ff033)
Location: include/net/netlink.h:804
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff81a00c70)
Location: include/net/netlink.h:804
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
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
In net/core/neighbour.c (ffffffff81ab1213)
Location: include/net/netlink.h:804
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff81ab3030)
Location: include/net/netlink.h:804
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
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
In net/core/neighbour.c (ffffffff81c2a3a7)
Location: include/net/netlink.h:804
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff81c2c1ac)
Location: include/net/netlink.h:804
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
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
In net/core/neighbour.c (ffffffff81ddd0e2)
Location: include/net/netlink.h:822
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff81ddf26c)
Location: include/net/netlink.h:822
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
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
In net/core/neighbour.c (ffffffff81e4de32)
Location: include/net/netlink.h:823
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff81e5058c)
Location: include/net/netlink.h:823
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
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
In net/core/neighbour.c (ffffffff81f0cb82)
Location: include/net/netlink.h:830
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff81f0f62c)
Location: include/net/netlink.h:830
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
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
In net/core/neighbour.c (ffff800010be9110)
Location: include/net/netlink.h:738
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffff800010beb220)
Location: include/net/netlink.h:738
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
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
In net/core/neighbour.c (c0d0224c)
Location: include/net/netlink.h:738
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (c0d03f18)
Location: include/net/netlink.h:738
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
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
In net/core/neighbour.c (c000000000ccb994)
Location: include/net/netlink.h:738
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (c000000000cce638)
Location: include/net/netlink.h:738
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
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
In net/core/neighbour.c (ffffffe00076d360)
Location: include/net/netlink.h:738
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffe00076ebd0)
Location: include/net/netlink.h:738
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
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
In net/core/neighbour.c (ffffffff818e7c87)
Location: include/net/netlink.h:738
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff818e96c0)
Location: include/net/netlink.h:738
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
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
In net/core/neighbour.c (ffffffff818a1ac7)
Location: include/net/netlink.h:738
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff818a3500)
Location: include/net/netlink.h:738
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
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
In net/core/neighbour.c (ffffffff81938cb7)
Location: include/net/netlink.h:738
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff8193a6f0)
Location: include/net/netlink.h:738
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
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
In net/core/neighbour.c (ffffffff8195a4c7)
Location: include/net/netlink.h:738
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff8195bf20)
Location: include/net/netlink.h:738
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
```
</details>
</li>
</ul>

## Differences
