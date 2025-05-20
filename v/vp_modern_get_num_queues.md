# Function: <code>vp_modern_get_num_queues</code>

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
u16 vp_modern_get_num_queues(struct virtio_pci_modern_device *mdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern_dev.c (ffffffff8170cf90)
Location: drivers/virtio/virtio_pci_modern_dev.c:578
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
```
**Symbols:**

```
ffffffff8170cf90-ffffffff8170cfa8: vp_modern_get_num_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u16 vp_modern_get_num_queues(struct virtio_pci_modern_device *mdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern_dev.c (ffffffff817893b0)
Location: drivers/virtio/virtio_pci_modern_dev.c:599
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
```
**Symbols:**

```
ffffffff817893b0-ffffffff817893c8: vp_modern_get_num_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u16 vp_modern_get_num_queues(struct virtio_pci_modern_device *mdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern_dev.c (ffffffff818c09f0)
Location: drivers/virtio/virtio_pci_modern_dev.c:610
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
```
**Symbols:**

```
ffffffff818c09f0-ffffffff818c0a0e: vp_modern_get_num_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u16 vp_modern_get_num_queues(struct virtio_pci_modern_device *mdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern_dev.c (ffffffff81a10690)
Location: drivers/virtio/virtio_pci_modern_dev.c:649
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
```
**Symbols:**

```
ffffffff81a10690-ffffffff81a106ae: vp_modern_get_num_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u16 vp_modern_get_num_queues(struct virtio_pci_modern_device *mdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern_dev.c (ffffffff81a596e0)
Location: drivers/virtio/virtio_pci_modern_dev.c:658
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
```
**Symbols:**

```
ffffffff81a596e0-ffffffff81a596fe: vp_modern_get_num_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u16 vp_modern_get_num_queues(struct virtio_pci_modern_device *mdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern_dev.c (ffffffff81aaaac0)
Location: drivers/virtio/virtio_pci_modern_dev.c:667
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
```
**Symbols:**

```
ffffffff81aaaac0-ffffffff81aaaade: vp_modern_get_num_queues (STB_GLOBAL)
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
