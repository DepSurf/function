# Function: <code>vp_modern_map_capability</code>

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
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_pci_modern_dev.c (0)
Location: drivers/virtio/virtio_pci_modern_dev.c:21
Inline: True
Direct callers:
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_map_vq_notify
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
```
**Symbols:**

```
ffffffff8170cfb0-ffffffff8170d140: vp_modern_map_capability.isra.0 (STB_LOCAL)
ffffffff81bf6271-ffffffff81bf6329: vp_modern_map_capability.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_pci_modern_dev.c (0)
Location: drivers/virtio/virtio_pci_modern_dev.c:21
Inline: True
Direct callers:
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_map_vq_notify
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
```
**Symbols:**

```
ffffffff817893d0-ffffffff817896ea: vp_modern_map_capability.isra.0 (STB_LOCAL)
ffffffff81cf4d82-ffffffff81cf4e23: vp_modern_map_capability.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void *vp_modern_map_capability(struct virtio_pci_modern_device *mdev, int off, size_t minlen, u32 align, u32 start, u32 size, size_t *len, resource_size_t *pa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_pci_modern_dev.c (0)
Location: drivers/virtio/virtio_pci_modern_dev.c:21
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_map_vq_notify
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
```
**Symbols:**

```
ffffffff818c0350-ffffffff818c068e: vp_modern_map_capability (STB_LOCAL)
ffffffff81ebcede-ffffffff81ebcf6c: vp_modern_map_capability.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *vp_modern_map_capability(struct virtio_pci_modern_device *mdev, int off, size_t minlen, u32 align, u32 start, u32 size, size_t *len, resource_size_t *pa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern_dev.c (ffffffff81a0fe00)
Location: drivers/virtio/virtio_pci_modern_dev.c:22
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_map_vq_notify
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
```
**Symbols:**

```
ffffffff81a0fe00-ffffffff81a10201: vp_modern_map_capability (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *vp_modern_map_capability(struct virtio_pci_modern_device *mdev, int off, size_t minlen, u32 align, u32 start, u32 size, size_t *len, resource_size_t *pa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern_dev.c (ffffffff81a58ea0)
Location: drivers/virtio/virtio_pci_modern_dev.c:22
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_map_vq_notify
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
```
**Symbols:**

```
ffffffff81a58ea0-ffffffff81a59253: vp_modern_map_capability (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *vp_modern_map_capability(struct virtio_pci_modern_device *mdev, int off, size_t minlen, u32 align, u32 start, u32 size, size_t *len, resource_size_t *pa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern_dev.c (ffffffff81aaa280)
Location: drivers/virtio/virtio_pci_modern_dev.c:22
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_map_vq_notify
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
```
**Symbols:**

```
ffffffff81aaa280-ffffffff81aaa633: vp_modern_map_capability (STB_LOCAL)
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
