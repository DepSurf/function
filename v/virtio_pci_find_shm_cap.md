# Function: <code>virtio_pci_find_shm_cap</code>

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
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int virtio_pci_find_shm_cap(struct pci_dev *dev, u8 required_id, u8 *bar, u64 *offset, u64 *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_pci_modern.c (0)
Location: drivers/virtio/virtio_pci_modern.c:447
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:vp_get_shm_region
```
**Symbols:**

```
ffffffff81729ec0-ffffffff8172a01a: virtio_pci_find_shm_cap (STB_LOCAL)
ffffffff81c047cd-ffffffff81c047ef: virtio_pci_find_shm_cap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern.c (ffffffff8170e7b7)
Location: drivers/virtio/virtio_pci_modern.c:289
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:vp_get_shm_region
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern.c (ffffffff8178b047)
Location: drivers/virtio/virtio_pci_modern.c:289
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:vp_get_shm_region
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int virtio_pci_find_shm_cap(struct pci_dev *dev, u8 required_id, u8 *bar, u64 *offset, u64 *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_pci_modern.c (0)
Location: drivers/virtio/virtio_pci_modern.c:289
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:vp_get_shm_region
```
**Symbols:**

```
ffffffff818c29f0-ffffffff818c2b99: virtio_pci_find_shm_cap (STB_LOCAL)
ffffffff81ebd168-ffffffff81ebd18a: virtio_pci_find_shm_cap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int virtio_pci_find_shm_cap(struct pci_dev *dev, u8 required_id, u8 *bar, u64 *offset, u64 *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern.c (ffffffff81a12c40)
Location: drivers/virtio/virtio_pci_modern.c:385
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:vp_get_shm_region
```
**Symbols:**

```
ffffffff81a12c40-ffffffff81a12e07: virtio_pci_find_shm_cap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int virtio_pci_find_shm_cap(struct pci_dev *dev, u8 required_id, u8 *bar, u64 *offset, u64 *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern.c (ffffffff81a5bcb0)
Location: drivers/virtio/virtio_pci_modern.c:395
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:vp_get_shm_region
```
**Symbols:**

```
ffffffff81a5bcb0-ffffffff81a5be77: virtio_pci_find_shm_cap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int virtio_pci_find_shm_cap(struct pci_dev *dev, u8 required_id, u8 *bar, u64 *offset, u64 *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern.c (ffffffff81aacf40)
Location: drivers/virtio/virtio_pci_modern.c:640
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:vp_get_shm_region
```
**Symbols:**

```
ffffffff81aacf40-ffffffff81aad107: virtio_pci_find_shm_cap (STB_LOCAL)
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
