# Function: <code>ida_remove</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ida_remove(struct ida *ida, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff813ea490)
Location: lib/idr.c:1010
Inline: False
Direct callers:
  - fs/super.c:get_anon_bdev
  - fs/super.c:free_anon_bdev
  - fs/namespace.c:cleanup_group_ids
  - fs/proc/generic.c:proc_alloc_inum
  - fs/proc/generic.c:proc_free_inum
  - fs/devpts/inode.c:devpts_new_index
  - fs/devpts/inode.c:devpts_kill_index
  - lib/idr.c:ida_simple_get
  - drivers/iommu/iommu.c:iommu_group_release
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/scsi/sd.c:scsi_disk_release
  - drivers/scsi/sd.c:sd_probe
  - net/core/net_namespace.c:unregister_pernet_operations
```
**Symbols:**

```
ffffffff813ea490-ffffffff813ea5ad: ida_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ida_remove(struct ida *ida, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81430840)
Location: lib/idr.c:1010
Inline: False
Direct callers:
  - fs/super.c:free_anon_bdev
  - fs/super.c:get_anon_bdev
  - fs/namespace.c:cleanup_group_ids
  - fs/proc/generic.c:proc_free_inum
  - fs/proc/generic.c:proc_alloc_inum
  - fs/devpts/inode.c:devpts_kill_index
  - fs/devpts/inode.c:devpts_new_index
  - lib/idr.c:ida_simple_get
  - drivers/scsi/sd.c:scsi_disk_release
  - drivers/scsi/sd.c:sd_probe
  - drivers/mmc/core/host.c:mmc_host_classdev_release
  - net/core/net_namespace.c:unregister_pernet_operations
```
**Symbols:**

```
ffffffff81430840-ffffffff8143095c: ida_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ida_remove(struct ida *ida, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff8144ca10)
Location: lib/idr.c:1013
Inline: False
Direct callers:
  - fs/super.c:free_anon_bdev
  - fs/super.c:get_anon_bdev
  - fs/namespace.c:cleanup_group_ids
  - fs/proc/generic.c:proc_free_inum
  - fs/proc/generic.c:proc_alloc_inum
  - fs/devpts/inode.c:devpts_kill_index
  - fs/devpts/inode.c:devpts_new_index
  - lib/idr.c:ida_simple_get
  - drivers/scsi/sd.c:scsi_disk_release
  - drivers/scsi/sd.c:sd_probe
  - drivers/mmc/core/host.c:mmc_host_classdev_release
  - net/core/net_namespace.c:unregister_pernet_operations
```
**Symbols:**

```
ffffffff8144ca10-ffffffff8144cb2c: ida_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ida_remove(struct ida *ida, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff818ed050)
Location: lib/idr.c:346
Inline: False
Direct callers:
  - fs/super.c:free_anon_bdev
  - fs/super.c:get_anon_bdev
  - fs/namespace.c:cleanup_group_ids
  - fs/devpts/inode.c:devpts_kill_index
  - fs/devpts/inode.c:devpts_new_index
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:chan_dev_release
  - drivers/scsi/sd.c:scsi_disk_release
  - drivers/scsi/sd.c:sd_probe
  - net/core/net_namespace.c:unregister_pernet_operations
  - lib/idr.c:ida_simple_get
```
**Symbols:**

```
ffffffff818ed050-ffffffff818ed169: ida_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ida_remove(struct ida *ida, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81973070)
Location: lib/idr.c:354
Inline: False
Direct callers:
  - fs/super.c:free_anon_bdev
  - fs/super.c:get_anon_bdev
  - fs/namespace.c:cleanup_group_ids
  - fs/devpts/inode.c:devpts_kill_index
  - fs/devpts/inode.c:devpts_new_index
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:chan_dev_release
  - drivers/scsi/sd.c:scsi_disk_release
  - drivers/scsi/sd.c:sd_probe
  - net/core/net_namespace.c:unregister_pernet_operations
  - lib/idr.c:ida_simple_get
```
**Symbols:**

```
ffffffff81973070-ffffffff8197318f: ida_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ida_remove(struct ida *ida, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff819cf610)
Location: lib/idr.c:484
Inline: False
Direct callers:
  - fs/super.c:free_anon_bdev
  - fs/super.c:get_anon_bdev
  - fs/namespace.c:cleanup_group_ids
  - fs/devpts/inode.c:devpts_kill_index
  - fs/devpts/inode.c:devpts_new_index
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:chan_dev_release
  - drivers/scsi/sd.c:scsi_disk_release
  - drivers/scsi/sd.c:sd_probe
  - net/core/net_namespace.c:unregister_pernet_operations
  - lib/idr.c:ida_simple_get
```
**Symbols:**

```
ffffffff819cf610-ffffffff819cf717: ida_remove (STB_GLOBAL)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
