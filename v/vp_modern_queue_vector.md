# Function: <code>vp_modern_queue_vector</code>

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
u16 vp_modern_queue_vector(struct virtio_pci_modern_device *mdev, u16 index, u16 vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern_dev.c (ffffffff8170ce90)
Location: drivers/virtio/virtio_pci_modern_dev.c:453
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
```
**Symbols:**

```
ffffffff8170ce90-ffffffff8170ced2: vp_modern_queue_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u16 vp_modern_queue_vector(struct virtio_pci_modern_device *mdev, u16 index, u16 vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern_dev.c (ffffffff817892b0)
Location: drivers/virtio/virtio_pci_modern_dev.c:474
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
```
**Symbols:**

```
ffffffff817892b0-ffffffff817892f2: vp_modern_queue_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u16 vp_modern_queue_vector(struct virtio_pci_modern_device *mdev, u16 index, u16 vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern_dev.c (ffffffff818c08d0)
Location: drivers/virtio/virtio_pci_modern_dev.c:485
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
```
**Symbols:**

```
ffffffff818c08d0-ffffffff818c0919: vp_modern_queue_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u16 vp_modern_queue_vector(struct virtio_pci_modern_device *mdev, u16 index, u16 vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern_dev.c (ffffffff81a10530)
Location: drivers/virtio/virtio_pci_modern_dev.c:524
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:vp_active_vq
```
**Symbols:**

```
ffffffff81a10530-ffffffff81a10579: vp_modern_queue_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u16 vp_modern_queue_vector(struct virtio_pci_modern_device *mdev, u16 index, u16 vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern_dev.c (ffffffff81a59580)
Location: drivers/virtio/virtio_pci_modern_dev.c:533
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:vp_active_vq
```
**Symbols:**

```
ffffffff81a59580-ffffffff81a595c9: vp_modern_queue_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u16 vp_modern_queue_vector(struct virtio_pci_modern_device *mdev, u16 index, u16 vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern_dev.c (ffffffff81aaa960)
Location: drivers/virtio/virtio_pci_modern_dev.c:542
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:vp_active_vq
```
**Symbols:**

```
ffffffff81aaa960-ffffffff81aaa9a9: vp_modern_queue_vector (STB_GLOBAL)
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
