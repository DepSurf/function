# Function: <code>vp_modern_queue_address</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void vp_modern_queue_address(struct virtio_pci_modern_device *mdev, u16 index, u64 desc_addr, u64 driver_addr, u64 device_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern_dev.c (ffffffff8170d200)
Location: drivers/virtio/virtio_pci_modern_dev.c:493
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
```
**Symbols:**

```
ffffffff8170d200-ffffffff8170d289: vp_modern_queue_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void vp_modern_queue_address(struct virtio_pci_modern_device *mdev, u16 index, u64 desc_addr, u64 driver_addr, u64 device_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern_dev.c (ffffffff817897b0)
Location: drivers/virtio/virtio_pci_modern_dev.c:514
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
```
**Symbols:**

```
ffffffff817897b0-ffffffff81789839: vp_modern_queue_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void vp_modern_queue_address(struct virtio_pci_modern_device *mdev, u16 index, u64 desc_addr, u64 driver_addr, u64 device_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern_dev.c (ffffffff818c0b00)
Location: drivers/virtio/virtio_pci_modern_dev.c:525
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
```
**Symbols:**

```
ffffffff818c0b00-ffffffff818c0b9a: vp_modern_queue_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void vp_modern_queue_address(struct virtio_pci_modern_device *mdev, u16 index, u64 desc_addr, u64 driver_addr, u64 device_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern_dev.c (ffffffff81a10870)
Location: drivers/virtio/virtio_pci_modern_dev.c:564
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:vp_active_vq
```
**Symbols:**

```
ffffffff81a10870-ffffffff81a1090a: vp_modern_queue_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void vp_modern_queue_address(struct virtio_pci_modern_device *mdev, u16 index, u64 desc_addr, u64 driver_addr, u64 device_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern_dev.c (ffffffff81a598c0)
Location: drivers/virtio/virtio_pci_modern_dev.c:573
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:vp_active_vq
```
**Symbols:**

```
ffffffff81a598c0-ffffffff81a5995a: vp_modern_queue_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void vp_modern_queue_address(struct virtio_pci_modern_device *mdev, u16 index, u64 desc_addr, u64 driver_addr, u64 device_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern_dev.c (ffffffff81aaad00)
Location: drivers/virtio/virtio_pci_modern_dev.c:582
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:vp_active_vq
```
**Symbols:**

```
ffffffff81aaad00-ffffffff81aaad9a: vp_modern_queue_address (STB_GLOBAL)
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
