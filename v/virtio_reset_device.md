# Function: <code>virtio_reset_device</code>

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
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void virtio_reset_device(struct virtio_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff818bc9dc)
Location: drivers/virtio/virtio.c:220
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:register_virtio_device
Direct callers:
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/iommu/virtio-iommu.c:viommu_remove
```
**Symbols:**

```
ffffffff818bc250-ffffffff818bc273: virtio_reset_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void virtio_reset_device(struct virtio_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff81a0b6fc)
Location: drivers/virtio/virtio.c:220
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:register_virtio_device
Direct callers:
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/iommu/virtio-iommu.c:viommu_remove
```
**Symbols:**

```
ffffffff81a0ae10-ffffffff81a0ae33: virtio_reset_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void virtio_reset_device(struct virtio_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff81a5458c)
Location: drivers/virtio/virtio.c:220
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:register_virtio_device
Direct callers:
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/iommu/virtio-iommu.c:viommu_remove
  - drivers/block/virtio_blk.c:virtblk_freeze
  - drivers/block/virtio_blk.c:virtblk_remove
  - drivers/scsi/virtio_scsi.c:virtscsi_freeze
  - drivers/scsi/virtio_scsi.c:virtscsi_remove
  - drivers/scsi/virtio_scsi.c:virtscsi_init
  - drivers/net/virtio_net.c:remove_vq_common
  - drivers/net/virtio_net.c:virtnet_probe
```
**Symbols:**

```
ffffffff81a53ca0-ffffffff81a53cc3: virtio_reset_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void virtio_reset_device(struct virtio_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff81aa522c)
Location: drivers/virtio/virtio.c:220
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:register_virtio_device
Direct callers:
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/iommu/virtio-iommu.c:viommu_remove
  - drivers/block/virtio_blk.c:virtblk_freeze
  - drivers/block/virtio_blk.c:virtblk_remove
  - drivers/scsi/virtio_scsi.c:virtscsi_freeze
  - drivers/scsi/virtio_scsi.c:virtscsi_remove
  - drivers/scsi/virtio_scsi.c:virtscsi_init
  - drivers/net/virtio_net.c:remove_vq_common
  - drivers/net/virtio_net.c:virtnet_probe
```
**Symbols:**

```
ffffffff81aa4900-ffffffff81aa4923: virtio_reset_device (STB_GLOBAL)
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
