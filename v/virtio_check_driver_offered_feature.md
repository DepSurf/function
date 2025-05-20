# Function: <code>virtio_check_driver_offered_feature</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void virtio_check_driver_offered_feature(const struct virtio_device *vdev, unsigned int fbit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff814bed00)
Location: drivers/virtio/virtio.c:108
Inline: True
Direct callers:
  - drivers/virtio/virtio_balloon.c:fill_balloon
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:virtballoon_oom_notify
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/block/virtio_blk.c:virtblk_ioctl
  - drivers/block/virtio_blk.c:virtblk_get_cache_mode
  - drivers/block/virtio_blk.c:virtblk_get_cache_mode
  - drivers/block/virtio_blk.c:virtblk_getgeo
  - drivers/block/virtio_blk.c:init_vq
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/net/virtio_net.c:virtnet_send_command
  - drivers/net/virtio_net.c:virtnet_set_mac_address
  - drivers/net/virtio_net.c:virtnet_set_mac_address
  - drivers/net/virtio_net.c:virtnet_set_queues
  - drivers/net/virtio_net.c:virtnet_set_rx_mode
  - drivers/net/virtio_net.c:virtnet_config_changed_work
  - drivers/net/virtio_net.c:virtnet_find_vqs
  - drivers/net/virtio_net.c:virtnet_find_vqs
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
```
**Symbols:**

```
ffffffff814bed00-ffffffff814bed79: virtio_check_driver_offered_feature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void virtio_check_driver_offered_feature(const struct virtio_device *vdev, unsigned int fbit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff8150ea10)
Location: drivers/virtio/virtio.c:108
Inline: True
Direct callers:
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:virtballoon_oom_notify
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_get_cache_mode
  - drivers/block/virtio_blk.c:virtblk_get_cache_mode
  - drivers/block/virtio_blk.c:init_vq
  - drivers/block/virtio_blk.c:virtblk_getgeo
  - drivers/block/virtio_blk.c:virtblk_ioctl
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_find_vqs
  - drivers/net/virtio_net.c:virtnet_find_vqs
  - drivers/net/virtio_net.c:virtnet_config_changed_work
  - drivers/net/virtio_net.c:virtnet_set_rx_mode
  - drivers/net/virtio_net.c:virtnet_set_queues
  - drivers/net/virtio_net.c:virtnet_set_mac_address
  - drivers/net/virtio_net.c:virtnet_set_mac_address
  - drivers/net/virtio_net.c:virtnet_send_command
```
**Symbols:**

```
ffffffff8150ea10-ffffffff8150ea89: virtio_check_driver_offered_feature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void virtio_check_driver_offered_feature(const struct virtio_device *vdev, unsigned int fbit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff8153ab70)
Location: drivers/virtio/virtio.c:108
Inline: True
Direct callers:
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:virtballoon_oom_notify
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
ffffffff8153ab70-ffffffff8153abe9: virtio_check_driver_offered_feature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void virtio_check_driver_offered_feature(const struct virtio_device *vdev, unsigned int fbit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff8154e3c0)
Location: drivers/virtio/virtio.c:103
Inline: True
Direct callers:
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:virtballoon_oom_notify
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
ffffffff8154e3c0-ffffffff8154e437: virtio_check_driver_offered_feature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void virtio_check_driver_offered_feature(const struct virtio_device *vdev, unsigned int fbit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff815b1ac0)
Location: drivers/virtio/virtio.c:103
Inline: True
Direct callers:
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:virtballoon_oom_notify
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
ffffffff815b1ac0-ffffffff815b1b37: virtio_check_driver_offered_feature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void virtio_check_driver_offered_feature(const struct virtio_device *vdev, unsigned int fbit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff815e9f00)
Location: drivers/virtio/virtio.c:103
Inline: True
Direct callers:
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:virtballoon_oom_notify
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
ffffffff815e9f00-ffffffff815e9f76: virtio_check_driver_offered_feature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void virtio_check_driver_offered_feature(const struct virtio_device *vdev, unsigned int fbit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff81604410)
Location: drivers/virtio/virtio.c:103
Inline: True
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
ffffffff81604410-ffffffff81604486: virtio_check_driver_offered_feature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void virtio_check_driver_offered_feature(const struct virtio_device *vdev, unsigned int fbit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff81636e10)
Location: drivers/virtio/virtio.c:104
Inline: True
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
ffffffff81636e10-ffffffff81636e78: virtio_check_driver_offered_feature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void virtio_check_driver_offered_feature(const struct virtio_device *vdev, unsigned int fbit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff81658b70)
Location: drivers/virtio/virtio.c:104
Inline: True
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
ffffffff81658b70-ffffffff81658bd8: virtio_check_driver_offered_feature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void virtio_check_driver_offered_feature(const struct virtio_device *vdev, unsigned int fbit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff81709060)
Location: drivers/virtio/virtio.c:104
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/virtio/virtio_balloon.c:fill_balloon
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
ffffffff81709060-ffffffff817090c8: virtio_check_driver_offered_feature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void virtio_check_driver_offered_feature(const struct virtio_device *vdev, unsigned int fbit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff81726010)
Location: drivers/virtio/virtio.c:104
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/virtio/virtio_balloon.c:fill_balloon
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
ffffffff81726010-ffffffff81726078: virtio_check_driver_offered_feature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void virtio_check_driver_offered_feature(const struct virtio_device *vdev, unsigned int fbit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff81709c20)
Location: drivers/virtio/virtio.c:104
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/virtio/virtio_balloon.c:fill_balloon
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
ffffffff81709c20-ffffffff81709c88: virtio_check_driver_offered_feature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void virtio_check_driver_offered_feature(const struct virtio_device *vdev, unsigned int fbit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff817855d0)
Location: drivers/virtio/virtio.c:105
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/virtio/virtio_balloon.c:fill_balloon
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
```
**Symbols:**

```
ffffffff817855d0-ffffffff81785638: virtio_check_driver_offered_feature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void virtio_check_driver_offered_feature(const struct virtio_device *vdev, unsigned int fbit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff818bc310)
Location: drivers/virtio/virtio.c:106
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/virtio/virtio_balloon.c:fill_balloon
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_attach_dev
```
**Symbols:**

```
ffffffff818bc310-ffffffff818bc38c: virtio_check_driver_offered_feature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void virtio_check_driver_offered_feature(const struct virtio_device *vdev, unsigned int fbit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff81a0af00)
Location: drivers/virtio/virtio.c:106
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/virtio/virtio_balloon.c:fill_balloon
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_attach_dev
```
**Symbols:**

```
ffffffff81a0af00-ffffffff81a0af7c: virtio_check_driver_offered_feature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void virtio_check_driver_offered_feature(const struct virtio_device *vdev, unsigned int fbit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff81a53d90)
Location: drivers/virtio/virtio.c:106
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/virtio/virtio_balloon.c:fill_balloon
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_attach_dev
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_attrs_are_visible
  - drivers/block/virtio_blk.c:cache_type_store
  - drivers/block/virtio_blk.c:virtblk_get_cache_mode
  - drivers/block/virtio_blk.c:virtblk_get_cache_mode
  - drivers/block/virtio_blk.c:init_vq
  - drivers/block/virtio_blk.c:virtblk_getgeo
  - drivers/block/virtio_blk.c:virtblk_probe_zoned_device
  - drivers/scsi/virtio_scsi.c:virtscsi_restore
  - drivers/scsi/virtio_scsi.c:virtscsi_remove
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_queuecommand
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_validate
  - drivers/net/virtio_net.c:virtnet_validate
  - drivers/net/virtio_net.c:virtnet_validate
  - drivers/net/virtio_net.c:virtnet_validate
  - drivers/net/virtio_net.c:virtnet_validate
  - drivers/net/virtio_net.c:virtnet_validate
  - drivers/net/virtio_net.c:virtnet_validate
  - drivers/net/virtio_net.c:virtnet_validate
  - drivers/net/virtio_net.c:virtnet_find_vqs
  - drivers/net/virtio_net.c:virtnet_find_vqs
  - drivers/net/virtio_net.c:virtnet_config_changed_work
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_set_rx_mode
  - drivers/net/virtio_net.c:_virtnet_set_queues
  - drivers/net/virtio_net.c:virtnet_set_mac_address
  - drivers/net/virtio_net.c:virtnet_set_mac_address
  - drivers/net/virtio_net.c:virtnet_send_command
```
**Symbols:**

```
ffffffff81a53d90-ffffffff81a53e0c: virtio_check_driver_offered_feature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void virtio_check_driver_offered_feature(const struct virtio_device *vdev, unsigned int fbit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff81aa4a10)
Location: drivers/virtio/virtio.c:106
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/virtio/virtio_balloon.c:fill_balloon
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_attach_dev
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_attrs_are_visible
  - drivers/block/virtio_blk.c:cache_type_store
  - drivers/block/virtio_blk.c:virtblk_get_cache_mode
  - drivers/block/virtio_blk.c:virtblk_get_cache_mode
  - drivers/block/virtio_blk.c:init_vq
  - drivers/block/virtio_blk.c:virtblk_getgeo
  - drivers/block/virtio_blk.c:virtblk_probe_zoned_device
  - drivers/scsi/virtio_scsi.c:virtscsi_restore
  - drivers/scsi/virtio_scsi.c:virtscsi_remove
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_queuecommand
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_validate
  - drivers/net/virtio_net.c:virtnet_validate
  - drivers/net/virtio_net.c:virtnet_validate_features
  - drivers/net/virtio_net.c:virtnet_validate_features
  - drivers/net/virtio_net.c:virtnet_validate_features
  - drivers/net/virtio_net.c:virtnet_validate_features
  - drivers/net/virtio_net.c:virtnet_validate_features
  - drivers/net/virtio_net.c:virtnet_validate_features
  - drivers/net/virtio_net.c:virtnet_find_vqs
  - drivers/net/virtio_net.c:virtnet_find_vqs
  - drivers/net/virtio_net.c:virtnet_config_changed_work
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_set_rx_mode
  - drivers/net/virtio_net.c:_virtnet_set_queues
  - drivers/net/virtio_net.c:virtnet_set_mac_address
  - drivers/net/virtio_net.c:virtnet_set_mac_address
  - drivers/net/virtio_net.c:virtnet_send_command
```
**Symbols:**

```
ffffffff81aa4a10-ffffffff81aa4a8c: virtio_check_driver_offered_feature (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void virtio_check_driver_offered_feature(const struct virtio_device *vdev, unsigned int fbit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffff800010820fd8)
Location: drivers/virtio/virtio.c:104
Inline: True
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
```
**Symbols:**

```
ffff800010820fd8-ffff800010821070: virtio_check_driver_offered_feature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void virtio_check_driver_offered_feature(const struct virtio_device *vdev, unsigned int fbit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (c093edf4)
Location: drivers/virtio/virtio.c:104
Inline: True
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
c093edf4-c093ee78: virtio_check_driver_offered_feature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void virtio_check_driver_offered_feature(const struct virtio_device *vdev, unsigned int fbit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (c0000000008cab90)
Location: drivers/virtio/virtio.c:104
Inline: True
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
c0000000008cab90-c0000000008cac18: virtio_check_driver_offered_feature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void virtio_check_driver_offered_feature(const struct virtio_device *vdev, unsigned int fbit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffe00051802a)
Location: drivers/virtio/virtio.c:104
Inline: True
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
ffffffe00051802a-ffffffe0005180aa: virtio_check_driver_offered_feature (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void virtio_check_driver_offered_feature(const struct virtio_device *vdev, unsigned int fbit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff8161ea10)
Location: drivers/virtio/virtio.c:104
Inline: True
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
ffffffff8161ea10-ffffffff8161ea78: virtio_check_driver_offered_feature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void virtio_check_driver_offered_feature(const struct virtio_device *vdev, unsigned int fbit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff81613100)
Location: drivers/virtio/virtio.c:104
Inline: True
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
ffffffff81613100-ffffffff81613168: virtio_check_driver_offered_feature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void virtio_check_driver_offered_feature(const struct virtio_device *vdev, unsigned int fbit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff8164c9b0)
Location: drivers/virtio/virtio.c:104
Inline: True
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_restore
  - drivers/scsi/virtio_scsi.c:virtscsi_remove
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_queuecommand
```
**Symbols:**

```
ffffffff8164c9b0-ffffffff8164ca18: virtio_check_driver_offered_feature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void virtio_check_driver_offered_feature(const struct virtio_device *vdev, unsigned int fbit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff81667080)
Location: drivers/virtio/virtio.c:104
Inline: True
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
ffffffff81667080-ffffffff816670e8: virtio_check_driver_offered_feature (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
