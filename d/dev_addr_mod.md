# Function: <code>dev_addr_mod</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
void dev_addr_mod(struct net_device *dev, unsigned int offset, const void *addr, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_addr_lists.c (ffffffff81c21490)
Location: net/core/dev_addr_lists.c:572
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:talk_to_netback
  - net/core/rtnetlink.c:rtnl_create_link
  - net/ethernet/eth.c:device_get_ethdev_address
  - net/ethernet/eth.c:platform_get_ethdev_address
```
**Symbols:**

```
ffffffff81c21490-ffffffff81c216bc: dev_addr_mod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dev_addr_mod(struct net_device *dev, unsigned int offset, const void *addr, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_addr_lists.c (ffffffff81dd3620)
Location: net/core/dev_addr_lists.c:572
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:talk_to_netback
  - net/core/rtnetlink.c:rtnl_create_link
  - net/ethernet/eth.c:device_get_ethdev_address
  - net/ethernet/eth.c:platform_get_ethdev_address
```
**Symbols:**

```
ffffffff81dd3620-ffffffff81dd384c: dev_addr_mod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void dev_addr_mod(struct net_device *dev, unsigned int offset, const void *addr, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev_addr_lists.c (0)
Location: net/core/dev_addr_lists.c:572
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/net_failover.c:net_failover_create
  - net/core/rtnetlink.c:rtnl_create_link
  - net/ethernet/eth.c:device_get_ethdev_address
  - net/ethernet/eth.c:platform_get_ethdev_address
```
**Symbols:**

```
ffffffff8212d210-ffffffff8212d25e: dev_addr_mod.cold (STB_LOCAL)
ffffffff81e441e0-ffffffff81e44609: dev_addr_mod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void dev_addr_mod(struct net_device *dev, unsigned int offset, const void *addr, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev_addr_lists.c (0)
Location: net/core/dev_addr_lists.c:572
Inline: False
Direct callers:
  - drivers/net/netkit.c:netkit_new_link
  - drivers/net/netkit.c:netkit_new_link
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/net_failover.c:net_failover_create
  - net/core/rtnetlink.c:rtnl_create_link
  - net/ethernet/eth.c:device_get_ethdev_address
  - net/ethernet/eth.c:platform_get_ethdev_address
```
**Symbols:**

```
ffffffff8220ef3c-ffffffff8220ef8a: dev_addr_mod.cold (STB_LOCAL)
ffffffff81f02e40-ffffffff81f03269: dev_addr_mod (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
