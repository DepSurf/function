# Function: <code>ida_pre_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int ida_pre_get(struct ida *ida, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff813eadf0)
Location: lib/idr.c:896
Inline: True
Direct callers:
  - fs/super.c:get_anon_bdev
  - fs/namespace.c:mnt_alloc_group_id
  - fs/namespace.c:alloc_vfsmnt
  - fs/proc/generic.c:proc_alloc_inum
  - fs/devpts/inode.c:devpts_new_index
  - lib/idr.c:ida_simple_get
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/scsi/sd.c:sd_probe
```
**Symbols:**

```
ffffffff813eadf0-ffffffff813eaec7: ida_pre_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int ida_pre_get(struct ida *ida, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81431170)
Location: lib/idr.c:896
Inline: True
Direct callers:
  - fs/super.c:get_anon_bdev
  - fs/namespace.c:alloc_vfsmnt
  - fs/namespace.c:mnt_alloc_group_id
  - fs/proc/generic.c:proc_alloc_inum
  - fs/devpts/inode.c:devpts_new_index
  - lib/idr.c:ida_simple_get
  - drivers/scsi/sd.c:sd_probe
  - drivers/mmc/core/host.c:mmc_alloc_host
```
**Symbols:**

```
ffffffff81431170-ffffffff81431247: ida_pre_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int ida_pre_get(struct ida *ida, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff8144d3e0)
Location: lib/idr.c:896
Inline: True
Direct callers:
  - fs/super.c:get_anon_bdev
  - fs/namespace.c:alloc_vfsmnt
  - fs/namespace.c:mnt_alloc_group_id
  - fs/proc/generic.c:proc_alloc_inum
  - fs/devpts/inode.c:devpts_new_index
  - lib/idr.c:ida_simple_get
  - drivers/scsi/sd.c:sd_probe
  - drivers/mmc/core/host.c:mmc_alloc_host
```
**Symbols:**

```
ffffffff8144d3e0-ffffffff8144d4b7: ida_pre_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int ida_pre_get(struct ida *ida, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff818f1550)
Location: lib/radix-tree.c:2119
Inline: True
Direct callers:
  - fs/super.c:get_anon_bdev
  - fs/namespace.c:alloc_vfsmnt
  - fs/namespace.c:mnt_alloc_group_id
  - fs/devpts/inode.c:devpts_new_index
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/scsi/sd.c:sd_probe
  - lib/idr.c:ida_simple_get
```
**Symbols:**

```
ffffffff818f1550-ffffffff818f15c6: ida_pre_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int ida_pre_get(struct ida *ida, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81977a00)
Location: lib/radix-tree.c:2116
Inline: True
Direct callers:
  - fs/super.c:get_anon_bdev
  - fs/namespace.c:alloc_vfsmnt
  - fs/namespace.c:mnt_alloc_group_id
  - fs/devpts/inode.c:devpts_new_index
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/scsi/sd.c:sd_probe
  - lib/idr.c:ida_simple_get
```
**Symbols:**

```
ffffffff81977a00-ffffffff81977a76: ida_pre_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int ida_pre_get(struct ida *ida, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff819d4370)
Location: lib/radix-tree.c:2117
Inline: True
Direct callers:
  - fs/super.c:get_anon_bdev
  - fs/namespace.c:alloc_vfsmnt
  - fs/namespace.c:mnt_alloc_group_id
  - fs/devpts/inode.c:devpts_new_index
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/scsi/sd.c:sd_probe
  - lib/idr.c:ida_simple_get
```
**Symbols:**

```
ffffffff819d4370-ffffffff819d43ec: ida_pre_get (STB_GLOBAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>gfp_t gfp</code>
</li>
<li>
<b>Param removed. </b>
<code>gfp_t gfp_mask</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
