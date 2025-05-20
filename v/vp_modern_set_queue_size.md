# Function: <code>vp_modern_set_queue_size</code>

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
void vp_modern_set_queue_size(struct virtio_pci_modern_device *mdev, u16 index, u16 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern_dev.c (ffffffff8170ce50)
Location: drivers/virtio/virtio_pci_modern_dev.c:546
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
```
**Symbols:**

```
ffffffff8170ce50-ffffffff8170ce8a: vp_modern_set_queue_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void vp_modern_set_queue_size(struct virtio_pci_modern_device *mdev, u16 index, u16 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern_dev.c (ffffffff81789270)
Location: drivers/virtio/virtio_pci_modern_dev.c:567
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
```
**Symbols:**

```
ffffffff81789270-ffffffff817892aa: vp_modern_set_queue_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void vp_modern_set_queue_size(struct virtio_pci_modern_device *mdev, u16 index, u16 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern_dev.c (ffffffff818c0880)
Location: drivers/virtio/virtio_pci_modern_dev.c:578
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
```
**Symbols:**

```
ffffffff818c0880-ffffffff818c08c6: vp_modern_set_queue_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void vp_modern_set_queue_size(struct virtio_pci_modern_device *mdev, u16 index, u16 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern_dev.c (ffffffff81a10480)
Location: drivers/virtio/virtio_pci_modern_dev.c:617
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:vp_active_vq
```
**Symbols:**

```
ffffffff81a10480-ffffffff81a104c6: vp_modern_set_queue_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void vp_modern_set_queue_size(struct virtio_pci_modern_device *mdev, u16 index, u16 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern_dev.c (ffffffff81a594d0)
Location: drivers/virtio/virtio_pci_modern_dev.c:626
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:vp_active_vq
```
**Symbols:**

```
ffffffff81a594d0-ffffffff81a59516: vp_modern_set_queue_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void vp_modern_set_queue_size(struct virtio_pci_modern_device *mdev, u16 index, u16 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern_dev.c (ffffffff81aaa8b0)
Location: drivers/virtio/virtio_pci_modern_dev.c:635
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:vp_active_vq
```
**Symbols:**

```
ffffffff81aaa8b0-ffffffff81aaa8f6: vp_modern_set_queue_size (STB_GLOBAL)
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
