# Function: <code>vp_legacy_queue_vector</code>

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
u16 vp_legacy_queue_vector(struct virtio_pci_legacy_device *ldev, u16 index, u16 vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_legacy_dev.c (ffffffff818c15e0)
Location: drivers/virtio/virtio_pci_legacy_dev.c:147
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
```
**Symbols:**

```
ffffffff818c15e0-ffffffff818c1632: vp_legacy_queue_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u16 vp_legacy_queue_vector(struct virtio_pci_legacy_device *ldev, u16 index, u16 vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_legacy_dev.c (ffffffff81a11460)
Location: drivers/virtio/virtio_pci_legacy_dev.c:147
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
```
**Symbols:**

```
ffffffff81a11460-ffffffff81a114b2: vp_legacy_queue_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u16 vp_legacy_queue_vector(struct virtio_pci_legacy_device *ldev, u16 index, u16 vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_legacy_dev.c (ffffffff81a5a430)
Location: drivers/virtio/virtio_pci_legacy_dev.c:147
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
```
**Symbols:**

```
ffffffff81a5a430-ffffffff81a5a482: vp_legacy_queue_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u16 vp_legacy_queue_vector(struct virtio_pci_legacy_device *ldev, u16 index, u16 vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_legacy_dev.c (ffffffff81aab870)
Location: drivers/virtio/virtio_pci_legacy_dev.c:147
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
```
**Symbols:**

```
ffffffff81aab870-ffffffff81aab8c2: vp_legacy_queue_vector (STB_GLOBAL)
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
