# Function: <code>dev_core_stats_rx_dropped_inc</code>

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
Location: include/linux/netdevice.h:3923
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_xdp_act
```
```
In net/core/dev.c (ffffffff81c110dc)
Location: include/linux/netdevice.h:3923
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81c49116)
Location: include/linux/netdevice.h:3923
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/core/gro_cells.c (ffffffff81c8a0a1)
Location: include/linux/netdevice.h:3923
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
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
Location: include/linux/netdevice.h:3967
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_xdp_act
```
```
In net/core/dev.c (ffffffff81dc0d4c)
Location: include/linux/netdevice.h:3967
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81dfdab4)
Location: include/linux/netdevice.h:3967
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/core/gro_cells.c (ffffffff81e44c81)
Location: include/linux/netdevice.h:3967
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
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
Location: include/linux/netdevice.h:4026
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_xdp_act
```
```
In net/core/dev.c (ffffffff81e3095e)
Location: include/linux/netdevice.h:4026
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81e6f003)
Location: include/linux/netdevice.h:4026
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/core/gro_cells.c (ffffffff81e9fa81)
Location: include/linux/netdevice.h:4026
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
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
In drivers/net/tun.c (ffffffff81d00d10)
Location: include/linux/netdevice.h:4092
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_xdp_act
  - drivers/net/tun.c:tun_xdp_act
  - drivers/net/tun.c:tun_xdp_act
```
```
In net/core/dev.c (ffffffff81eeceec)
Location: include/linux/netdevice.h:4092
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81f2e663)
Location: include/linux/netdevice.h:4092
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/core/gro_cells.c (ffffffff81f622f1)
Location: include/linux/netdevice.h:4092
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
</details>
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
