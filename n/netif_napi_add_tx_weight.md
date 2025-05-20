# Function: <code>netif_napi_add_tx_weight</code>

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
In drivers/net/tun.c (ffffffff81a64813)
Location: include/linux/netdevice.h:2567
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff834cf7a9)
Location: include/linux/netdevice.h:2567
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_proto_init
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
In drivers/net/tun.c (ffffffff81befa83)
Location: include/linux/netdevice.h:2593
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff83f13048)
Location: include/linux/netdevice.h:2593
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_proto_init
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
In drivers/net/tun.c (ffffffff81c48007)
Location: include/linux/netdevice.h:2646
Inline: True
```
```
In drivers/net/virtio_net.c (ffffffff81c4ed10)
Location: include/linux/netdevice.h:2646
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_alloc_queues
```
```
In net/mptcp/protocol.c (ffffffff837396f8)
Location: include/linux/netdevice.h:2646
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_proto_init
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
In drivers/net/tun.c (ffffffff81cfd987)
Location: include/linux/netdevice.h:2714
Inline: True
```
```
In drivers/net/virtio_net.c (ffffffff81d05837)
Location: include/linux/netdevice.h:2714
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_alloc_queues
```
```
In net/mptcp/protocol.c (ffffffff8396dedd)
Location: include/linux/netdevice.h:2714
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_proto_init
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
