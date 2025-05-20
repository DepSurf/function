# Function: <code>read_mapping_folio</code>

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
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/remap_range.c (ffffffff81441dad)
Location: include/linux/pagemap.h:762
Inline: True
```
```
In drivers/scsi/scsicam.c (ffffffff819fa8a5)
Location: include/linux/pagemap.h:762
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/remap_range.c (ffffffff814d090d)
Location: include/linux/pagemap.h:758
Inline: True
```
```
In block/partitions/core.c (ffffffff8175520d)
Location: include/linux/pagemap.h:758
Inline: True
Inline callers:
  - block/partitions/core.c:read_part_sector
```
```
In drivers/scsi/scsicam.c (ffffffff81b788a5)
Location: include/linux/pagemap.h:758
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/remap_range.c (ffffffff8150700d)
Location: include/linux/pagemap.h:779
Inline: True
```
```
In fs/ext4/verity.c (ffffffff81611db2)
Location: include/linux/pagemap.h:779
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:pagecache_read
```
```
In block/partitions/core.c (ffffffff817914eb)
Location: include/linux/pagemap.h:779
Inline: True
Inline callers:
  - block/partitions/core.c:read_part_sector
```
```
In drivers/scsi/scsicam.c (ffffffff81bcc535)
Location: include/linux/pagemap.h:779
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/remap_range.c (ffffffff8153c334)
Location: include/linux/pagemap.h:891
Inline: True
```
```
In fs/ext4/verity.c (ffffffff8164ab60)
Location: include/linux/pagemap.h:891
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:pagecache_read
```
```
In block/partitions/core.c (ffffffff817d4ded)
Location: include/linux/pagemap.h:891
Inline: True
Inline callers:
  - block/partitions/core.c:read_part_sector
```
```
In drivers/scsi/scsicam.c (ffffffff81c21165)
Location: include/linux/pagemap.h:891
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
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
