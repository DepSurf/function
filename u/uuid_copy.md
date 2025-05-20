# Function: <code>uuid_copy</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (0)
Location: include/linux/uuid.h:63
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (0)
Location: include/linux/uuid.h:63
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (0)
Location: include/linux/uuid.h:64
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (0)
Location: include/linux/uuid.h:64
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (0)
Location: include/linux/uuid.h:56
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (0)
Location: include/linux/uuid.h:56
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void uuid_copy(uuid_t *dst, const uuid_t *src);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff818a3a2b)
Location: include/linux/uuid.h:66
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_vf_token
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
**Symbols:**

```
ffffffff818a2d20-ffffffff818a2d2f: uuid_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void uuid_copy(uuid_t *dst, const uuid_t *src);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff818b2a02)
Location: include/linux/uuid.h:66
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_vf_token
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
**Symbols:**

```
ffffffff818b19c0-ffffffff818b19cf: uuid_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void uuid_copy(uuid_t *dst, const uuid_t *src);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff81895cc4)
Location: include/linux/uuid.h:66
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_vf_token
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
**Symbols:**

```
ffffffff81894d90-ffffffff81894d9f: uuid_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void uuid_copy(uuid_t *dst, const uuid_t *src);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff81929c64)
Location: include/linux/uuid.h:66
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_validate_vf_token
Direct callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl
```
**Symbols:**

```
ffffffff819289f0-ffffffff819289ff: uuid_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff81a8001f)
Location: include/linux/uuid.h:66
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_validate_vf_token
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl_feature
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (0)
Location: include/linux/uuid.h:56
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (c07ad2b8)
Location: include/linux/uuid.h:56
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (c00000000079cfc4)
Location: include/linux/uuid.h:56
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffe00043db48)
Location: include/linux/uuid.h:56
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (0)
Location: include/linux/uuid.h:56
Inline: True
```
```
In drivers/nvme/host/core.c (ffffffff817451bd)
Location: include/linux/uuid.h:56
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_report_ns_ids
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (0)
Location: include/linux/uuid.h:56
Inline: True
```
```
In drivers/nvme/host/core.c (ffffffff81726e4d)
Location: include/linux/uuid.h:56
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_report_ns_ids
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (0)
Location: include/linux/uuid.h:56
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (0)
Location: include/linux/uuid.h:56
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
