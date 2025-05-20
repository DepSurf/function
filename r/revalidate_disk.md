# Function: <code>revalidate_disk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int revalidate_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812481f0)
Location: fs/block_dev.c:1094
Inline: False
Direct callers:
  - drivers/block/virtio_blk.c:virtblk_update_cache_mode
  - drivers/block/virtio_blk.c:virtblk_update_cache_mode
  - drivers/block/virtio_blk.c:virtblk_config_changed_work
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/scsi/sd.c:sd_rescan
  - drivers/scsi/sd.c:cache_type_store
  - drivers/md/md.c:array_size_store
  - drivers/md/md.c:update_size
  - drivers/md/md.c:do_md_stop
```
**Symbols:**

```
ffffffff812481f0-ffffffff81248276: revalidate_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int revalidate_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81270970)
Location: fs/block_dev.c:1166
Inline: False
Direct callers:
  - drivers/block/virtio_blk.c:virtblk_update_cache_mode
  - drivers/block/virtio_blk.c:virtblk_config_changed_work
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/scsi/sd.c:sd_rescan
  - drivers/scsi/sd.c:cache_type_store
  - drivers/md/md.c:update_size
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:array_size_store
```
**Symbols:**

```
ffffffff81270970-ffffffff812709f6: revalidate_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int revalidate_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812842e0)
Location: fs/block_dev.c:1418
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/scsi/sd.c:sd_rescan
  - drivers/scsi/sd.c:cache_type_store
  - drivers/md/md.c:update_size
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:array_size_store
```
**Symbols:**

```
ffffffff812842e0-ffffffff81284363: revalidate_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int revalidate_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81291990)
Location: fs/block_dev.c:1343
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/scsi/sd.c:sd_rescan
  - drivers/scsi/sd.c:cache_type_store
  - drivers/md/md.c:update_size
  - drivers/md/md.c:do_md_stop
```
**Symbols:**

```
ffffffff81291990-ffffffff81291a0d: revalidate_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int revalidate_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812b46f0)
Location: fs/block_dev.c:1333
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/scsi/sd.c:sd_rescan
  - drivers/scsi/sd.c:cache_type_store
  - drivers/md/md.c:update_size
  - drivers/md/md.c:do_md_stop
```
**Symbols:**

```
ffffffff812b46f0-ffffffff812b4770: revalidate_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int revalidate_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812ddd40)
Location: fs/block_dev.c:1359
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/scsi/sd.c:sd_rescan
  - drivers/scsi/sd.c:cache_type_store
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:update_size
  - drivers/md/md.c:do_md_stop
```
**Symbols:**

```
ffffffff812ddd40-ffffffff812dddc3: revalidate_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int revalidate_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812f3330)
Location: fs/block_dev.c:1398
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/scsi/sd.c:sd_rescan
  - drivers/scsi/sd.c:cache_type_store
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:update_size
  - drivers/md/md.c:do_md_stop
```
**Symbols:**

```
ffffffff812f3330-ffffffff812f33b3: revalidate_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int revalidate_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81314d90)
Location: fs/block_dev.c:1450
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/scsi/sd.c:sd_rescan
  - drivers/scsi/sd.c:cache_type_store
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:update_size
  - drivers/md/md.c:do_md_stop
```
**Symbols:**

```
ffffffff81314d90-ffffffff81314e2a: revalidate_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int revalidate_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff813273b0)
Location: fs/block_dev.c:1446
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/scsi/sd.c:sd_rescan
  - drivers/scsi/sd.c:cache_type_store
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:update_size
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_run
```
**Symbols:**

```
ffffffff813273b0-ffffffff8132744a: revalidate_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int revalidate_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81360100)
Location: fs/block_dev.c:1428
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_rescan
  - drivers/scsi/sd.c:cache_type_store
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:update_size
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_run
```
**Symbols:**

```
ffffffff81360100-ffffffff81360193: revalidate_disk (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int revalidate_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffff8000103e2318)
Location: fs/block_dev.c:1446
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/scsi/sd.c:sd_rescan
  - drivers/scsi/sd.c:cache_type_store
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:update_size
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_run
```
**Symbols:**

```
ffff8000103e2318-ffff8000103e23d8: revalidate_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int revalidate_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c05ba514)
Location: fs/block_dev.c:1446
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_rescan
  - drivers/scsi/sd.c:cache_type_store
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:update_size
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_run
```
**Symbols:**

```
c05ba514-c05ba5ac: revalidate_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int revalidate_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c0000000004e7ea0)
Location: fs/block_dev.c:1446
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_rescan
  - drivers/scsi/sd.c:cache_type_store
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:update_size
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_run
```
**Symbols:**

```
c0000000004e7ea0-c0000000004e7fd4: revalidate_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int revalidate_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffe000298908)
Location: fs/block_dev.c:1446
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_rescan
  - drivers/scsi/sd.c:cache_type_store
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:update_size
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_run
```
**Symbols:**

```
ffffffe000298908-ffffffe00029899a: revalidate_disk (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int revalidate_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131f990)
Location: fs/block_dev.c:1446
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/scsi/sd.c:sd_rescan
  - drivers/scsi/sd.c:cache_type_store
  - drivers/nvme/host/core.c:nvme_validate_ns
  - drivers/nvme/host/core.c:__nvme_revalidate_disk
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:update_size
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_run
```
**Symbols:**

```
ffffffff8131f990-ffffffff8131fa2a: revalidate_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int revalidate_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81310530)
Location: fs/block_dev.c:1446
Inline: False
Direct callers:
  - drivers/nvdimm/pmem.c:pmem_attach_disk
  - drivers/nvdimm/blk.c:nd_blk_probe
  - drivers/scsi/sd.c:sd_rescan
  - drivers/scsi/sd.c:cache_type_store
  - drivers/nvme/host/core.c:nvme_validate_ns
  - drivers/nvme/host/core.c:__nvme_revalidate_disk
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:update_size
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_run
```
**Symbols:**

```
ffffffff81310530-ffffffff813105ca: revalidate_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int revalidate_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131d460)
Location: fs/block_dev.c:1446
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/scsi/sd.c:sd_rescan
  - drivers/scsi/sd.c:cache_type_store
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:update_size
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_run
```
**Symbols:**

```
ffffffff8131d460-ffffffff8131d4fa: revalidate_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int revalidate_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8132f160)
Location: fs/block_dev.c:1446
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/scsi/sd.c:sd_rescan
  - drivers/scsi/sd.c:cache_type_store
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:update_size
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_run
```
**Symbols:**

```
ffffffff8132f160-ffffffff8132f1fa: revalidate_disk (STB_GLOBAL)
```
</details>
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
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
