# Function: <code>vp_modern_set_queue_enable</code>

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
void vp_modern_set_queue_enable(struct virtio_pci_modern_device *mdev, u16 index, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern_dev.c (ffffffff8170ce10)
Location: drivers/virtio/virtio_pci_modern_dev.c:516
Inline: False
```
**Symbols:**

```
ffffffff8170ce10-ffffffff8170ce4a: vp_modern_set_queue_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void vp_modern_set_queue_enable(struct virtio_pci_modern_device *mdev, u16 index, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern_dev.c (ffffffff81789230)
Location: drivers/virtio/virtio_pci_modern_dev.c:537
Inline: False
```
**Symbols:**

```
ffffffff81789230-ffffffff8178926a: vp_modern_set_queue_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void vp_modern_set_queue_enable(struct virtio_pci_modern_device *mdev, u16 index, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern_dev.c (ffffffff818c0830)
Location: drivers/virtio/virtio_pci_modern_dev.c:548
Inline: False
```
**Symbols:**

```
ffffffff818c0830-ffffffff818c0876: vp_modern_set_queue_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void vp_modern_set_queue_enable(struct virtio_pci_modern_device *mdev, u16 index, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern_dev.c (ffffffff81a10420)
Location: drivers/virtio/virtio_pci_modern_dev.c:587
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:vp_modern_enable_vq_after_reset
```
**Symbols:**

```
ffffffff81a10420-ffffffff81a10466: vp_modern_set_queue_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void vp_modern_set_queue_enable(struct virtio_pci_modern_device *mdev, u16 index, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern_dev.c (ffffffff81a59470)
Location: drivers/virtio/virtio_pci_modern_dev.c:596
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:vp_modern_enable_vq_after_reset
```
**Symbols:**

```
ffffffff81a59470-ffffffff81a594b6: vp_modern_set_queue_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void vp_modern_set_queue_enable(struct virtio_pci_modern_device *mdev, u16 index, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern_dev.c (ffffffff81aaa850)
Location: drivers/virtio/virtio_pci_modern_dev.c:605
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:vp_modern_create_avq
  - drivers/virtio/virtio_pci_modern.c:vp_modern_enable_vq_after_reset
```
**Symbols:**

```
ffffffff81aaa850-ffffffff81aaa896: vp_modern_set_queue_enable (STB_GLOBAL)
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
