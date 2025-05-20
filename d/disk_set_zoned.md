# Function: <code>disk_set_zoned</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void disk_set_zoned(struct gendisk *disk, enum blk_zoned_model model);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff8173a060)
Location: block/blk-settings.c:909
Inline: False
Direct callers:
  - block/partitions/core.c:add_partition
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_block_characteristics
```
**Symbols:**

```
ffffffff8173a060-ffffffff8173a1ac: disk_set_zoned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void disk_set_zoned(struct gendisk *disk, enum blk_zoned_model model);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81776740)
Location: block/blk-settings.c:918
Inline: False
Direct callers:
  - block/partitions/core.c:add_partition
  - drivers/block/virtio_blk.c:virtblk_config_changed_work
  - drivers/block/virtio_blk.c:virtblk_probe_zoned_device
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_block_characteristics
```
**Symbols:**

```
ffffffff81776740-ffffffff81776899: disk_set_zoned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void disk_set_zoned(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff817b89c0)
Location: block/blk-settings.c:891
Inline: False
Direct callers:
  - drivers/block/virtio_blk.c:virtblk_probe_zoned_device
  - drivers/scsi/sd.c:sd_read_block_characteristics
```
**Symbols:**

```
ffffffff817b89c0-ffffffff817b8a1b: disk_set_zoned (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>enum blk_zoned_model model</code>
</li>
</ul>
</details>
</li>
</ul>
