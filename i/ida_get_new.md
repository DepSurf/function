# Function: <code>ida_get_new</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8127f117)
Location: include/linux/idr.h:179
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_alloc_inum
```
```
In fs/devpts/inode.c (ffffffff8128e23c)
Location: include/linux/idr.h:179
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In drivers/iommu/iommu.c (ffffffff8152b071)
Location: include/linux/idr.h:179
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_alloc
```
```
In drivers/scsi/sd.c (ffffffff815bd0a3)
Location: include/linux/idr.h:179
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff812ac157)
Location: include/linux/idr.h:193
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_alloc_inum
```
```
In fs/devpts/inode.c (ffffffff812bb8c1)
Location: include/linux/idr.h:193
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In drivers/scsi/sd.c (ffffffff816164d3)
Location: include/linux/idr.h:193
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
```
```
In drivers/mmc/core/host.c (ffffffff81724c20)
Location: include/linux/idr.h:193
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_alloc_host
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff812c1a47)
Location: include/linux/idr.h:218
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_alloc_inum
```
```
In fs/devpts/inode.c (ffffffff812d0f11)
Location: include/linux/idr.h:218
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In drivers/scsi/sd.c (ffffffff81645a95)
Location: include/linux/idr.h:218
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
```
```
In drivers/mmc/core/host.c (ffffffff81757ba0)
Location: include/linux/idr.h:218
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_alloc_host
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff812e257b)
Location: include/linux/idr.h:207
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In drivers/dma/dmaengine.c (ffffffff8154d31d)
Location: include/linux/idr.h:207
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/scsi/sd.c (ffffffff81659208)
Location: include/linux/idr.h:207
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff81306fab)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In drivers/dma/dmaengine.c (ffffffff815b08e2)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/scsi/sd.c (ffffffff816c285d)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff81334f3b)
Location: include/linux/idr.h:249
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In drivers/dma/dmaengine.c (ffffffff815e8d2e)
Location: include/linux/idr.h:249
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/scsi/sd.c (ffffffff81700272)
Location: include/linux/idr.h:249
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
```
</details>
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
In <code>5.19</code>: Absent ⚠️
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
