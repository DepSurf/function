# Function: <code>eth_hw_addr_set</code>

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
In drivers/net/xen-netfront.c (ffffffff81a731a3)
Location: include/linux/etherdevice.h:317
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:talk_to_netback
```
```
In net/ethernet/eth.c (ffffffff81c93afc)
Location: include/linux/etherdevice.h:317
Inline: True
Inline callers:
  - net/ethernet/eth.c:device_get_ethdev_address
  - net/ethernet/eth.c:platform_get_ethdev_address
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
In drivers/net/xen-netfront.c (ffffffff81c05963)
Location: include/linux/etherdevice.h:317
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:talk_to_netback
```
```
In net/ethernet/eth.c (ffffffff81e4f25c)
Location: include/linux/etherdevice.h:317
Inline: True
Inline callers:
  - net/ethernet/eth.c:device_get_ethdev_address
  - net/ethernet/eth.c:platform_get_ethdev_address
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
In drivers/net/virtio_net.c (ffffffff81c51ee9)
Location: include/linux/etherdevice.h:317
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_probe
```
```
In drivers/net/xen-netfront.c (ffffffff81c6b068)
Location: include/linux/etherdevice.h:317
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:talk_to_netback
```
```
In net/ethernet/eth.c (ffffffff81eaa8fc)
Location: include/linux/etherdevice.h:317
Inline: True
Inline callers:
  - net/ethernet/eth.c:device_get_ethdev_address
  - net/ethernet/eth.c:platform_get_ethdev_address
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
In drivers/net/virtio_net.c (ffffffff81d08110)
Location: include/linux/etherdevice.h:317
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_probe
```
```
In drivers/net/xen-netfront.c (ffffffff81d1fa48)
Location: include/linux/etherdevice.h:317
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:talk_to_netback
```
```
In net/ethernet/eth.c (ffffffff81f6d3ac)
Location: include/linux/etherdevice.h:317
Inline: True
Inline callers:
  - net/ethernet/eth.c:device_get_ethdev_address
  - net/ethernet/eth.c:platform_get_ethdev_address
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
