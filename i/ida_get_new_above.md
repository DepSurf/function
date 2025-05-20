# Function: <code>ida_get_new_above</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ida_get_new_above(struct ida *ida, int starting_id, int *p_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff813eabe0)
Location: lib/idr.c:932
Inline: False
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
ffffffff813eabe0-ffffffff813eadf0: ida_get_new_above (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ida_get_new_above(struct ida *ida, int starting_id, int *p_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81430f60)
Location: lib/idr.c:932
Inline: False
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
ffffffff81430f60-ffffffff8143116f: ida_get_new_above (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ida_get_new_above(struct ida *ida, int starting_id, int *p_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff8144d170)
Location: lib/idr.c:935
Inline: False
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
ffffffff8144d170-ffffffff8144d3d7: ida_get_new_above (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ida_get_new_above(struct ida *ida, int start, int *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff818ecc50)
Location: lib/idr.c:250
Inline: False
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
ffffffff818ecc50-ffffffff818ecf65: ida_get_new_above (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ida_get_new_above(struct ida *ida, int start, int *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81972c70)
Location: lib/idr.c:258
Inline: False
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
ffffffff81972c70-ffffffff81972f85: ida_get_new_above (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ida_get_new_above(struct ida *ida, int start, int *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff819cf250)
Location: lib/idr.c:390
Inline: False
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
ffffffff819cf250-ffffffff819cf526: ida_get_new_above (STB_GLOBAL)
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
<code>int start</code>
</li>
<li>
<b>Param added. </b>
<code>int *id</code>
</li>
<li>
<b>Param removed. </b>
<code>int starting_id</code>
</li>
<li>
<b>Param removed. </b>
<code>int *p_id</code>
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
