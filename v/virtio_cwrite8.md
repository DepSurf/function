# Function: <code>virtio_cwrite8</code>

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
In drivers/block/virtio_blk.c (ffffffff81571aad)
Location: include/linux/virtio_config.h:342
Inline: True
```
```
In drivers/net/virtio_net.c (ffffffff815f1e42)
Location: include/linux/virtio_config.h:342
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_set_mac_address
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
In drivers/block/virtio_blk.c (ffffffff815c7258)
Location: include/linux/virtio_config.h:355
Inline: True
```
```
In drivers/net/virtio_net.c (ffffffff81651772)
Location: include/linux/virtio_config.h:355
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_set_mac_address
```
</details>
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/virtio_blk.c (ffffffff81b7fc69)
Location: include/linux/virtio_config.h:537
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:cache_type_store
```
```
In drivers/net/virtio_net.c (ffffffff81c4dd62)
Location: include/linux/virtio_config.h:537
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_set_mac_address
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
In drivers/block/virtio_blk.c (ffffffff81bd3e39)
Location: include/linux/virtio_config.h:541
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:cache_type_store
```
```
In drivers/net/virtio_net.c (ffffffff81d03dd2)
Location: include/linux/virtio_config.h:541
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_set_mac_address
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
