# Function: <code>dev_core_stats_tx_dropped_inc</code>

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
In drivers/net/tun.c (ffffffff81a60a4b)
Location: include/linux/netdevice.h:3924
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/dev.c (ffffffff81c1a2e4)
Location: include/linux/netdevice.h:3924
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
```
```
In net/xfrm/xfrm_device.c (ffffffff81d7a55a)
Location: include/linux/netdevice.h:3924
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void dev_core_stats_tx_dropped_inc(struct net_device *dev);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81bed02d)
Location: include/linux/netdevice.h:3968
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/dev.c (ffffffff81dcb384)
Location: include/linux/netdevice.h:3968
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
```
```
In net/xfrm/xfrm_device.c (ffffffff81f471c5)
Location: include/linux/netdevice.h:3968
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
Direct callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
**Symbols:**

```
ffffffff81f46360-ffffffff81f46393: dev_core_stats_tx_dropped_inc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void dev_core_stats_tx_dropped_inc(struct net_device *dev);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81c45532)
Location: include/linux/netdevice.h:4027
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/net/net_failover.c (ffffffff81c6f2c9)
Location: include/linux/netdevice.h:4027
Inline: True
Inline callers:
  - drivers/net/net_failover.c:net_failover_start_xmit
```
```
In net/core/dev.c (ffffffff81e3bf14)
Location: include/linux/netdevice.h:4027
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
```
```
In net/xfrm/xfrm_device.c (ffffffff81fa6bf4)
Location: include/linux/netdevice.h:4027
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
Direct callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
**Symbols:**

```
ffffffff81fa5c80-ffffffff81fa5cb3: dev_core_stats_tx_dropped_inc (STB_LOCAL)
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
In drivers/net/netkit.c (ffffffff81ce531f)
Location: include/linux/netdevice.h:4093
Inline: True
Inline callers:
  - drivers/net/netkit.c:netkit_xmit
```
```
In drivers/net/tun.c (ffffffff81cfae6b)
Location: include/linux/netdevice.h:4093
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/net/net_failover.c (ffffffff81d23b99)
Location: include/linux/netdevice.h:4093
Inline: True
Inline callers:
  - drivers/net/net_failover.c:net_failover_start_xmit
```
```
In net/core/dev.c (ffffffff81efa454)
Location: include/linux/netdevice.h:4093
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
```
```
In net/xfrm/xfrm_device.c (ffffffff82073ee4)
Location: include/linux/netdevice.h:4093
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
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
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
</ul>
