# Function: <code>neigh_parms_data_state_setall</code>

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
In net/ipv4/devinet.c (ffffffff81791ac9)
Location: include/net/neighbour.h:101
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv4/ipmr.c (ffffffff817a7de2)
Location: include/net/neighbour.h:101
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
```
```
In net/ipv6/addrconf.c (ffffffff817ca62f)
Location: include/net/neighbour.h:101
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
In net/ipv4/devinet.c (ffffffff8180000c)
Location: include/net/neighbour.h:101
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/ipmr.c (ffffffff818905b5)
Location: include/net/neighbour.h:101
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
```
```
In net/ipv6/addrconf.c (ffffffff81837832)
Location: include/net/neighbour.h:101
Inline: True
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
In net/ipv4/devinet.c (ffffffff81830f6c)
Location: include/net/neighbour.h:101
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/ipmr.c (ffffffff818c4bcf)
Location: include/net/neighbour.h:101
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
```
```
In net/ipv6/addrconf.c (ffffffff81869322)
Location: include/net/neighbour.h:101
Inline: True
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
In net/ipv4/devinet.c (ffffffff81852215)
Location: include/net/neighbour.h:102
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/ipmr.c (ffffffff81868d96)
Location: include/net/neighbour.h:102
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
```
```
In net/ipv6/addrconf.c (ffffffff81890090)
Location: include/net/neighbour.h:102
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
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
In net/ipv4/devinet.c (ffffffff818d2023)
Location: include/net/neighbour.h:103
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/ipmr.c (ffffffff818e92d6)
Location: include/net/neighbour.h:103
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
```
```
In net/ipv6/addrconf.c (ffffffff8191162d)
Location: include/net/neighbour.h:103
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
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
In net/ipv4/devinet.c (ffffffff81928548)
Location: include/net/neighbour.h:103
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/ipmr.c (ffffffff8193eda7)
Location: include/net/neighbour.h:103
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
```
```
In net/ipv6/addrconf.c (ffffffff81968a3e)
Location: include/net/neighbour.h:103
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
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
In net/ipv4/devinet.c (ffffffff8195799d)
Location: include/net/neighbour.h:103
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/ipmr.c (ffffffff8196f669)
Location: include/net/neighbour.h:103
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
```
```
In net/ipv6/addrconf.c (ffffffff8199e375)
Location: include/net/neighbour.h:103
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
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
In net/ipv4/devinet.c (ffffffff819bc322)
Location: include/net/neighbour.h:103
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/ipmr.c (ffffffff819d8dbd)
Location: include/net/neighbour.h:103
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
```
```
In net/ipv6/addrconf.c (ffffffff81a0a401)
Location: include/net/neighbour.h:103
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
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
In net/ipv4/devinet.c (ffffffff819f301f)
Location: include/net/neighbour.h:102
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/ipmr.c (ffffffff81a0fb2d)
Location: include/net/neighbour.h:102
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
```
```
In net/ipv6/addrconf.c (ffffffff81a410b1)
Location: include/net/neighbour.h:102
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
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
In net/ipv4/devinet.c (ffffffff81ae1a0d)
Location: include/net/neighbour.h:102
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:rtm_to_ifaddr
```
```
In net/ipv4/ipmr.c (ffffffff81b00c6d)
Location: include/net/neighbour.h:102
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
```
```
In net/ipv6/addrconf.c (ffffffff81b36b7e)
Location: include/net/neighbour.h:102
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
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
In net/ipv4/devinet.c (ffffffff81aee8ad)
Location: include/net/neighbour.h:102
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:rtm_to_ifaddr
```
```
In net/ipv4/ipmr.c (ffffffff81b0ed4d)
Location: include/net/neighbour.h:102
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
```
```
In net/ipv6/addrconf.c (ffffffff81b458ae)
Location: include/net/neighbour.h:102
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
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
In net/ipv4/devinet.c (ffffffff81ad9fa7)
Location: include/net/neighbour.h:102
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:rtm_to_ifaddr
```
```
In net/ipv4/ipmr.c (ffffffff81afca4d)
Location: include/net/neighbour.h:102
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
```
```
In net/ipv6/addrconf.c (ffffffff81b335f1)
Location: include/net/neighbour.h:102
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
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
In net/ipv4/devinet.c (ffffffff81b990e7)
Location: include/net/neighbour.h:102
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:rtm_to_ifaddr
```
```
In net/ipv4/ipmr.c (ffffffff81bbe1cf)
Location: include/net/neighbour.h:102
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
```
```
In net/ipv6/addrconf.c (ffffffff81bf9c61)
Location: include/net/neighbour.h:102
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
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
In net/ipv4/devinet.c (ffffffff81d2b003)
Location: include/net/neighbour.h:103
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
```
```
In net/ipv4/ipmr.c (ffffffff81d530e8)
Location: include/net/neighbour.h:103
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
```
```
In net/ipv6/addrconf.c (ffffffff81d9303e)
Location: include/net/neighbour.h:103
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
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
In net/ipv4/devinet.c (ffffffff81ef2c1c)
Location: include/net/neighbour.h:105
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv4/ipmr.c (ffffffff81f1c406)
Location: include/net/neighbour.h:105
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
```
```
In net/ipv6/addrconf.c (ffffffff81f617d5)
Location: include/net/neighbour.h:105
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
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
In net/ipv4/devinet.c (ffffffff81f527ca)
Location: include/net/neighbour.h:105
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv4/ipmr.c (ffffffff81f7bee6)
Location: include/net/neighbour.h:105
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
```
```
In net/ipv6/addrconf.c (ffffffff81fc1607)
Location: include/net/neighbour.h:105
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
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
In net/ipv4/devinet.c (ffffffff82018aac)
Location: include/net/neighbour.h:105
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv4/ipmr.c (ffffffff820425d6)
Location: include/net/neighbour.h:105
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
```
```
In net/ipv6/addrconf.c (ffffffff8208eb3f)
Location: include/net/neighbour.h:105
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
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
In net/ipv4/devinet.c (ffff800010ca93b8)
Location: include/net/neighbour.h:102
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/ipmr.c (ffff800010cc97f0)
Location: include/net/neighbour.h:102
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
```
```
In net/ipv6/addrconf.c (ffff800010d02b64)
Location: include/net/neighbour.h:102
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
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
In net/ipv4/devinet.c (c0db59c8)
Location: include/net/neighbour.h:102
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/ipmr.c (c0dd4f24)
Location: include/net/neighbour.h:102
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
```
```
In net/ipv6/addrconf.c (c0e09834)
Location: include/net/neighbour.h:102
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
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
In net/ipv4/devinet.c (c000000000dbe528)
Location: include/net/neighbour.h:102
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/ipmr.c (c000000000de77a0)
Location: include/net/neighbour.h:102
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
```
```
In net/ipv6/addrconf.c (c000000000e2a54c)
Location: include/net/neighbour.h:102
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
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
In net/ipv4/devinet.c (ffffffe000803e78)
Location: include/net/neighbour.h:102
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/ipmr.c (ffffffe00081d2a2)
Location: include/net/neighbour.h:102
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
```
```
In net/ipv6/addrconf.c (ffffffe00084bec4)
Location: include/net/neighbour.h:102
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
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
In net/ipv4/devinet.c (ffffffff81992dbf)
Location: include/net/neighbour.h:102
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/ipmr.c (ffffffff819af54d)
Location: include/net/neighbour.h:102
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
```
```
In net/ipv6/addrconf.c (ffffffff819e0741)
Location: include/net/neighbour.h:102
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
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
In net/ipv4/devinet.c (ffffffff8194c87f)
Location: include/net/neighbour.h:102
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/ipmr.c (ffffffff8196bb7d)
Location: include/net/neighbour.h:102
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
```
```
In net/ipv6/addrconf.c (ffffffff8199d501)
Location: include/net/neighbour.h:102
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
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
In net/ipv4/devinet.c (ffffffff819fd65f)
Location: include/net/neighbour.h:102
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/ipmr.c (ffffffff81a19ded)
Location: include/net/neighbour.h:102
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
```
```
In net/ipv6/addrconf.c (ffffffff81a4b1c1)
Location: include/net/neighbour.h:102
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
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
In net/ipv4/devinet.c (ffffffff81a079ef)
Location: include/net/neighbour.h:102
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/ipmr.c (ffffffff81a24c1d)
Location: include/net/neighbour.h:102
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
```
```
In net/ipv6/addrconf.c (ffffffff81a5711b)
Location: include/net/neighbour.h:102
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
</details>
</li>
</ul>

## Differences
