# Function: <code>dev_core_stats</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81a67052)
Location: include/linux/netdevice.h:3903
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_xdp_act
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/dev.c (ffffffff81c1a2e4)
Location: include/linux/netdevice.h:3903
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81c49116)
Location: include/linux/netdevice.h:3903
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/core/gro_cells.c (ffffffff81c8a0a1)
Location: include/linux/netdevice.h:3903
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/ipv4/ip_input.c (ffffffff81cd52ca)
Location: include/linux/netdevice.h:3903
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/xfrm/xfrm_device.c (ffffffff81d7a55a)
Location: include/linux/netdevice.h:3903
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_input.c (ffffffff81d8cdb4)
Location: include/linux/netdevice.h:3903
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
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
In drivers/net/tun.c (ffffffff81bf2947)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_xdp_act
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/dev.c (ffffffff81dcb384)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81dfdab4)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/core/gro_cells.c (ffffffff81e44c81)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/ipv4/ip_input.c (ffffffff81e9579a)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/xfrm/xfrm_device.c (ffffffff81f471c5)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_input.c (ffffffff81f5afc4)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
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
In drivers/net/tun.c (ffffffff81c4b64e)
Location: include/linux/netdevice.h:4006
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_xdp_act
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/net/net_failover.c (ffffffff81c6f2c9)
Location: include/linux/netdevice.h:4006
Inline: True
Inline callers:
  - drivers/net/net_failover.c:net_failover_start_xmit
```
```
In net/core/dev.c (ffffffff81e3bf14)
Location: include/linux/netdevice.h:4006
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81e6f003)
Location: include/linux/netdevice.h:4006
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/core/gro_cells.c (ffffffff81e9fa81)
Location: include/linux/netdevice.h:4006
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/ipv4/ip_input.c (ffffffff81ef3fe3)
Location: include/linux/netdevice.h:4006
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/xfrm/xfrm_device.c (ffffffff81fa6bf4)
Location: include/linux/netdevice.h:4006
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_input.c (ffffffff81fbad74)
Location: include/linux/netdevice.h:4006
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
