# Function: <code>PageError</code>

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
In mm/page-writeback.c (ffffffff81199455)
Location: include/linux/page-flags.h:210
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/migrate.c (ffffffff811f1c1c)
Location: include/linux/page-flags.h:210
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In fs/buffer.c (ffffffff81243fcf)
Location: include/linux/page-flags.h:210
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:block_read_full_page
```
```
In block/partition-generic.c (ffffffff813cd025)
Location: include/linux/page-flags.h:210
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
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
In mm/page-writeback.c (ffffffff811afd81)
Location: include/linux/page-flags.h:256
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/migrate.c (ffffffff812105e1)
Location: include/linux/page-flags.h:256
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In fs/buffer.c (ffffffff8126d9b5)
Location: include/linux/page-flags.h:256
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/squashfs/file.c (ffffffff81322797)
Location: include/linux/page-flags.h:256
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
```
```
In block/partition-generic.c (ffffffff8141140d)
Location: include/linux/page-flags.h:256
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
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
In mm/page-writeback.c (ffffffff811c0441)
Location: include/linux/page-flags.h:266
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/migrate.c (ffffffff8122271c)
Location: include/linux/page-flags.h:266
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In fs/buffer.c (ffffffff81280bda)
Location: include/linux/page-flags.h:266
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/squashfs/file.c (ffffffff81338624)
Location: include/linux/page-flags.h:266
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
```
```
In block/partition-generic.c (ffffffff8142c7ad)
Location: include/linux/page-flags.h:266
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
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
In mm/migrate.c (ffffffff8122e1bc)
Location: include/linux/page-flags.h:266
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In fs/buffer.c (ffffffff8128e4c7)
Location: include/linux/page-flags.h:266
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/squashfs/file.c (ffffffff8134d59e)
Location: include/linux/page-flags.h:266
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
```
```
In block/partition-generic.c (ffffffff81439b05)
Location: include/linux/page-flags.h:266
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
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
In mm/migrate.c (ffffffff8124928c)
Location: include/linux/page-flags.h:267
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/buffer.c (ffffffff812b10c0)
Location: include/linux/page-flags.h:267
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/squashfs/file.c (ffffffff81371c4e)
Location: include/linux/page-flags.h:267
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
```
```
In block/partition-generic.c (ffffffff81465b05)
Location: include/linux/page-flags.h:267
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
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
In mm/migrate.c (ffffffff8126cd05)
Location: include/linux/page-flags.h:274
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/buffer.c (ffffffff812d90b0)
Location: include/linux/page-flags.h:274
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/squashfs/file.c (ffffffff813a020b)
Location: include/linux/page-flags.h:274
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
```
```
In block/partition-generic.c (ffffffff814994d5)
Location: include/linux/page-flags.h:274
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81281505)
Location: include/linux/page-flags.h:283
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/buffer.c (ffffffff812ee581)
Location: include/linux/page-flags.h:283
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/iomap.c (ffffffff813234d8)
Location: include/linux/page-flags.h:283
Inline: True
Inline callers:
  - fs/iomap.c:iomap_set_range_uptodate
```
```
In fs/squashfs/file.c (ffffffff813b8f8c)
Location: include/linux/page-flags.h:283
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
```
```
In block/partition-generic.c (ffffffff814b3735)
Location: include/linux/page-flags.h:283
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8129d795)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/buffer.c (ffffffff8130fd86)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/iomap/buffered-io.c (ffffffff8134b578)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_set_range_uptodate
```
```
In fs/squashfs/file.c (ffffffff813e3d9e)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
```
```
In block/partition-generic.c (ffffffff814e1cbf)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812ad095)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/buffer.c (ffffffff81322d33)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/verity/verify.c (ffffffff813517f8)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffffffff81363828)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_set_range_uptodate
```
```
In fs/ext4/readpage.c (ffffffff813cc263)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/squashfs/file.c (ffffffff813fdde0)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
```
```
In block/partition-generic.c (ffffffff814fb06f)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812e2bd5)
Location: include/linux/page-flags.h:322
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/buffer.c (ffffffff8135c413)
Location: include/linux/page-flags.h:322
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/verity/verify.c (ffffffff8139829a)
Location: include/linux/page-flags.h:322
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffffffff813aaca5)
Location: include/linux/page-flags.h:322
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff81418331)
Location: include/linux/page-flags.h:322
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/squashfs/file.c (ffffffff8144b83e)
Location: include/linux/page-flags.h:322
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
```
```
In block/partitions/core.c (ffffffff8155ddaf)
Location: include/linux/page-flags.h:322
Inline: True
Inline callers:
  - block/partitions/core.c:read_part_sector
```
```
In drivers/scsi/scsicam.c (ffffffff81830297)
Location: include/linux/page-flags.h:322
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812ee005)
Location: include/linux/page-flags.h:330
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/buffer.c (ffffffff81369aa5)
Location: include/linux/page-flags.h:330
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/verity/verify.c (ffffffff813a9b1a)
Location: include/linux/page-flags.h:330
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffffffff813bc4f5)
Location: include/linux/page-flags.h:330
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff8142be91)
Location: include/linux/page-flags.h:330
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/squashfs/file.c (ffffffff81467f1e)
Location: include/linux/page-flags.h:330
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
```
```
In block/partitions/core.c (ffffffff81579bbe)
Location: include/linux/page-flags.h:330
Inline: True
Inline callers:
  - block/partitions/core.c:read_part_sector
```
```
In drivers/scsi/scsicam.c (ffffffff81840f0e)
Location: include/linux/page-flags.h:330
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812f3af5)
Location: include/linux/page-flags.h:330
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/buffer.c (ffffffff813708b5)
Location: include/linux/page-flags.h:330
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/verity/verify.c (ffffffff813b106b)
Location: include/linux/page-flags.h:330
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffffffff813c3245)
Location: include/linux/page-flags.h:330
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff81432b51)
Location: include/linux/page-flags.h:330
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/squashfs/file.c (ffffffff8146d521)
Location: include/linux/page-flags.h:330
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
```
```
In block/partitions/core.c (ffffffff815818f1)
Location: include/linux/page-flags.h:330
Inline: True
Inline callers:
  - block/partitions/core.c:read_part_sector
```
```
In drivers/scsi/scsicam.c (ffffffff818240fe)
Location: include/linux/page-flags.h:330
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8133e495)
Location: include/linux/page-flags.h:344
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/buffer.c (ffffffff813bf484)
Location: include/linux/page-flags.h:344
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/verity/verify.c (ffffffff81400d54)
Location: include/linux/page-flags.h:344
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffffffff81412bc5)
Location: include/linux/page-flags.h:344
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff81486321)
Location: include/linux/page-flags.h:344
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/squashfs/file.c (ffffffff814c3db9)
Location: include/linux/page-flags.h:344
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
```
```
In block/partitions/core.c (ffffffff815e6cf6)
Location: include/linux/page-flags.h:344
Inline: True
Inline callers:
  - block/partitions/core.c:read_part_sector
```
```
In drivers/scsi/scsicam.c (ffffffff818af93e)
Location: include/linux/page-flags.h:344
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81445e1b)
Location: include/linux/page-flags.h:494
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/verity/verify.c (ffffffff81474dfa)
Location: include/linux/page-flags.h:494
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/ext4/readpage.c (ffffffff81509bc8)
Location: include/linux/page-flags.h:494
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/squashfs/file.c (ffffffff8154eb38)
Location: include/linux/page-flags.h:494
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_read_folio
```
```
In block/partitions/core.c (ffffffff81695e7e)
Location: include/linux/page-flags.h:494
Inline: True
Inline callers:
  - block/partitions/core.c:read_part_sector
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffff80001034f350)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/buffer.c (ffff8000103dbda0)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/verity/verify.c (ffff800010413910)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffff80001042af2c)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_set_range_uptodate
```
```
In fs/ext4/readpage.c (ffff8000104a469c)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/squashfs/file.c (ffff8000104dbe80)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
```
```
In block/partition-generic.c (ffff8000105fd09c)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/migrate.c (c05512d0)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/buffer.c (c05b511c)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/verity/verify.c (c05dfbb8)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (c05f2cfc)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_set_range_uptodate
```
```
In fs/ext4/readpage.c (c0666288)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/squashfs/file.c (c069d688)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
```
```
In block/partition-generic.c (c07a78c4)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/migrate.c (c000000000431744)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/buffer.c (c0000000004e11dc)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/verity/verify.c (c000000000521914)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (c00000000053a6d0)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_set_range_uptodate
```
```
In fs/ext4/readpage.c (c0000000005d1644)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/squashfs/file.c (c000000000617140)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
```
```
In block/partition-generic.c (c0000000007966e4)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffe00023e3c0)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/buffer.c (ffffffe00029432a)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/verity/verify.c (ffffffe0002bb31a)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffffffe0002c7c86)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_set_range_uptodate
```
```
In fs/ext4/readpage.c (ffffffe00032587c)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/squashfs/file.c (ffffffe000350b04)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
```
```
In block/partition-generic.c (ffffffe000438ca0)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
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
In mm/migrate.c (ffffffff812a5675)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/buffer.c (ffffffff8131b313)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/verity/verify.c (ffffffff81349dd8)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffffffff8135be08)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_set_range_uptodate
```
```
In fs/ext4/readpage.c (ffffffff813c4843)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/squashfs/file.c (ffffffff813f63c0)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
```
```
In block/partition-generic.c (ffffffff814f364f)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
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
In mm/migrate.c (ffffffff81297145)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/buffer.c (ffffffff8130beb3)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/verity/verify.c (ffffffff8133aab8)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffffffff8134caa8)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_set_range_uptodate
```
```
In fs/ext4/readpage.c (ffffffff813b52c3)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/squashfs/file.c (ffffffff813e6e40)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
```
```
In block/partition-generic.c (ffffffff814e3b5f)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812a3485)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/buffer.c (ffffffff81318de3)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/verity/verify.c (ffffffff813478a8)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffffffff813598d8)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_set_range_uptodate
```
```
In fs/ext4/readpage.c (ffffffff813c1cd3)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/squashfs/file.c (ffffffff813f3740)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
```
```
In block/partition-generic.c (ffffffff814ef6df)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812b3c95)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/buffer.c (ffffffff8132aa0d)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/verity/verify.c (ffffffff8135aba8)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffffffff8136cfc8)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_set_range_uptodate
```
```
In fs/ext4/readpage.c (ffffffff813d6e53)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/squashfs/file.c (ffffffff81409364)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
```
```
In block/partition-generic.c (ffffffff8150876f)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
</details>
</li>
</ul>

## Differences
