# Function: <code>blk_get_integrity</code>

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
In fs/block_dev.c (0)
Location: include/linux/blkdev.h:1503
Inline: True
```
```
In block/bio-integrity.c (ffffffff813e6f1b)
Location: include/linux/blkdev.h:1503
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_enabled
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:bio_integrity_trim
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_verify_fn
```
```
In drivers/md/md.c (ffffffff8168d956)
Location: include/linux/blkdev.h:1503
Inline: True
Inline callers:
  - drivers/md/md.c:md_integrity_register
```
```
In drivers/md/dm-table.c (ffffffff816a67dd)
Location: include/linux/blkdev.h:1503
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
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
In fs/block_dev.c (0)
Location: include/linux/blkdev.h:1532
Inline: True
```
```
In block/bio-integrity.c (ffffffff8142d60f)
Location: include/linux/blkdev.h:1532
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_trim
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_enabled
```
```
In drivers/md/md.c (ffffffff816eefba)
Location: include/linux/blkdev.h:1532
Inline: True
Inline callers:
  - drivers/md/md.c:md_integrity_register
```
```
In drivers/md/dm-table.c (ffffffff81706a01)
Location: include/linux/blkdev.h:1532
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
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
In fs/block_dev.c (0)
Location: include/linux/blkdev.h:1757
Inline: True
```
```
In block/bio-integrity.c (ffffffff814473ef)
Location: include/linux/blkdev.h:1757
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_trim
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_enabled
```
```
In drivers/md/md.c (ffffffff8172110a)
Location: include/linux/blkdev.h:1757
Inline: True
Inline callers:
  - drivers/md/md.c:md_integrity_register
```
```
In drivers/md/dm-table.c (ffffffff817388bc)
Location: include/linux/blkdev.h:1757
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
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
In fs/block_dev.c (0)
Location: include/linux/blkdev.h:1807
Inline: True
```
```
In block/bio-integrity.c (ffffffff814554c9)
Location: include/linux/blkdev.h:1807
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_trim
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_process
```
```
In drivers/md/md.c (ffffffff817381ba)
Location: include/linux/blkdev.h:1807
Inline: True
Inline callers:
  - drivers/md/md.c:md_integrity_register
```
```
In drivers/md/dm-table.c (ffffffff81751d87)
Location: include/linux/blkdev.h:1807
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
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
In fs/block_dev.c (0)
Location: include/linux/blkdev.h:1822
Inline: True
```
```
In block/bio-integrity.c (ffffffff81481159)
Location: include/linux/blkdev.h:1822
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_trim
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_process
```
```
In drivers/md/md.c (ffffffff817aa9ea)
Location: include/linux/blkdev.h:1822
Inline: True
Inline callers:
  - drivers/md/md.c:md_integrity_register
```
```
In drivers/md/dm-table.c (ffffffff817c3f76)
Location: include/linux/blkdev.h:1822
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
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
In fs/block_dev.c (ffffffff812db562)
Location: include/linux/blkdev.h:1827
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
```
```
In block/bio-integrity.c (ffffffff814b5d50)
Location: include/linux/blkdev.h:1827
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_trim
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_process
```
```
In drivers/md/md.c (ffffffff817f295d)
Location: include/linux/blkdev.h:1827
Inline: True
Inline callers:
  - drivers/md/md.c:md_integrity_register
  - drivers/md/md.c:md_integrity_register
```
```
In drivers/md/dm-table.c (ffffffff8180d5b5)
Location: include/linux/blkdev.h:1827
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
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
In fs/block_dev.c (ffffffff812f0ab2)
Location: include/linux/blkdev.h:1509
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
```
```
In block/bio-integrity.c (ffffffff814c9610)
Location: include/linux/blkdev.h:1509
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_trim
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_process
```
```
In drivers/md/md.c (ffffffff8181e85d)
Location: include/linux/blkdev.h:1509
Inline: True
Inline callers:
  - drivers/md/md.c:md_integrity_register
  - drivers/md/md.c:md_integrity_register
```
```
In drivers/md/dm-table.c (ffffffff818394ed)
Location: include/linux/blkdev.h:1509
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
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
In fs/block_dev.c (ffffffff8131242b)
Location: include/linux/blkdev.h:1518
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
```
```
In block/bio-integrity.c (ffffffff814f7e90)
Location: include/linux/blkdev.h:1518
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_trim
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_process
```
```
In drivers/md/md.c (ffffffff81860d30)
Location: include/linux/blkdev.h:1518
Inline: True
Inline callers:
  - drivers/md/md.c:md_integrity_register
  - drivers/md/md.c:md_integrity_register
```
```
In drivers/md/dm-table.c (ffffffff8187bfaf)
Location: include/linux/blkdev.h:1518
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
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
In fs/block_dev.c (ffffffff8132537b)
Location: include/linux/blkdev.h:1549
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
```
```
In block/bio-integrity.c (ffffffff81515d20)
Location: include/linux/blkdev.h:1549
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_trim
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_process
```
```
In drivers/md/md.c (ffffffff81892960)
Location: include/linux/blkdev.h:1549
Inline: True
Inline callers:
  - drivers/md/md.c:md_integrity_register
  - drivers/md/md.c:md_integrity_register
```
```
In drivers/md/dm-table.c (ffffffff818add8f)
Location: include/linux/blkdev.h:1549
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
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
In fs/block_dev.c (ffffffff8136189b)
Location: include/linux/blkdev.h:1573
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
```
```
In block/bio-integrity.c (ffffffff81576455)
Location: include/linux/blkdev.h:1573
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_trim
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_process
```
```
In drivers/md/md.c (ffffffff81960b49)
Location: include/linux/blkdev.h:1573
Inline: True
Inline callers:
  - drivers/md/md.c:md_integrity_register
  - drivers/md/md.c:md_integrity_register
```
```
In drivers/md/dm-table.c (ffffffff8197e006)
Location: include/linux/blkdev.h:1573
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
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
In fs/block_dev.c (ffffffff8136e635)
Location: include/linux/blkdev.h:1687
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
```
```
In block/bio-integrity.c (ffffffff815933c5)
Location: include/linux/blkdev.h:1687
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_trim
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_process
```
```
In drivers/md/md.c (ffffffff81967459)
Location: include/linux/blkdev.h:1687
Inline: True
Inline callers:
  - drivers/md/md.c:md_integrity_register
  - drivers/md/md.c:md_integrity_register
```
```
In drivers/md/dm-table.c (ffffffff819825df)
Location: include/linux/blkdev.h:1687
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
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
In fs/block_dev.c (ffffffff81374f45)
Location: include/linux/blkdev.h:1684
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
```
```
In block/bio-integrity.c (ffffffff8159a1c5)
Location: include/linux/blkdev.h:1684
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_trim
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_process
```
```
In drivers/md/md.c (ffffffff8194b6c9)
Location: include/linux/blkdev.h:1684
Inline: True
Inline callers:
  - drivers/md/md.c:md_integrity_register
  - drivers/md/md.c:md_integrity_register
```
```
In drivers/md/dm-table.c (ffffffff819669a2)
Location: include/linux/blkdev.h:1684
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
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
In block/bdev.c (ffffffff815c4925)
Location: include/linux/blkdev.h:1675
Inline: True
Inline callers:
  - block/bdev.c:bdev_write_page
  - block/bdev.c:bdev_read_page
```
```
In block/bio-integrity.c (ffffffff816028ff)
Location: include/linux/blkdev.h:1675
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_trim
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_process
```
```
In drivers/md/md.c (ffffffff819f0889)
Location: include/linux/blkdev.h:1675
Inline: True
Inline callers:
  - drivers/md/md.c:md_integrity_register
  - drivers/md/md.c:md_integrity_register
```
```
In drivers/md/dm-table.c (ffffffff81a0ebb2)
Location: include/linux/blkdev.h:1675
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
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
In block/bdev.c (ffffffff8166f355)
Location: include/linux/blk-integrity.h:46
Inline: True
Inline callers:
  - block/bdev.c:bdev_write_page
  - block/bdev.c:bdev_read_page
```
```
In block/bio-integrity.c (ffffffff816b544f)
Location: include/linux/blk-integrity.h:46
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_trim
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_process
```
```
In drivers/md/md.c (ffffffff81b599c9)
Location: include/linux/blk-integrity.h:46
Inline: True
Inline callers:
  - drivers/md/md.c:md_integrity_register
  - drivers/md/md.c:md_integrity_register
```
```
In drivers/md/dm-table.c (ffffffff81b77271)
Location: include/linux/blk-integrity.h:46
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
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
In block/bdev.c (ffffffff8172a6d5)
Location: include/linux/blk-integrity.h:46
Inline: True
Inline callers:
  - block/bdev.c:bdev_write_page
  - block/bdev.c:bdev_read_page
```
```
In block/bio-integrity.c (ffffffff81774fff)
Location: include/linux/blk-integrity.h:46
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_trim
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_process
```
```
In drivers/md/md.c (ffffffff81cf1579)
Location: include/linux/blk-integrity.h:46
Inline: True
Inline callers:
  - drivers/md/md.c:md_integrity_register
  - drivers/md/md.c:md_integrity_register
```
```
In drivers/md/dm-table.c (ffffffff81d14662)
Location: include/linux/blk-integrity.h:46
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
```
```
In drivers/md/dm-io-rewind.c (ffffffff81d1fd53)
Location: include/linux/blk-integrity.h:46
Inline: True
Inline callers:
  - drivers/md/dm-io-rewind.c:dm_io_rewind
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
In block/bio-integrity.c (ffffffff817b4d1f)
Location: include/linux/blk-integrity.h:46
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_trim
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_process
```
```
In drivers/scsi/virtio_scsi.c (ffffffff81be28d1)
Location: include/linux/blk-integrity.h:46
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_queuecommand
```
```
In drivers/md/md.c (ffffffff81d59979)
Location: include/linux/blk-integrity.h:46
Inline: True
Inline callers:
  - drivers/md/md.c:md_integrity_register
  - drivers/md/md.c:md_integrity_register
```
```
In drivers/md/dm-table.c (ffffffff81d7d796)
Location: include/linux/blk-integrity.h:46
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
```
```
In drivers/md/dm-io-rewind.c (ffffffff81d88f44)
Location: include/linux/blk-integrity.h:46
Inline: True
Inline callers:
  - drivers/md/dm-io-rewind.c:dm_io_rewind
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
In block/bio-integrity.c (ffffffff817f8dbf)
Location: include/linux/blk-integrity.h:46
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_trim
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_process
```
```
In drivers/scsi/virtio_scsi.c (ffffffff81c37ab0)
Location: include/linux/blk-integrity.h:46
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_queuecommand
```
```
In drivers/md/md.c (ffffffff81e10a39)
Location: include/linux/blk-integrity.h:46
Inline: True
Inline callers:
  - drivers/md/md.c:md_integrity_register
  - drivers/md/md.c:md_integrity_register
```
```
In drivers/md/dm-table.c (ffffffff81e34b63)
Location: include/linux/blk-integrity.h:46
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
```
```
In drivers/md/dm-io-rewind.c (ffffffff81e40684)
Location: include/linux/blk-integrity.h:46
Inline: True
Inline callers:
  - drivers/md/dm-io-rewind.c:dm_io_rewind
```
</details>
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
In fs/block_dev.c (ffff8000103df9a8)
Location: include/linux/blkdev.h:1549
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
```
```
In block/bio-integrity.c (ffff80001061ce8c)
Location: include/linux/blkdev.h:1549
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_trim
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_process
```
```
In drivers/md/md.c (ffff800010ae4154)
Location: include/linux/blkdev.h:1549
Inline: True
Inline callers:
  - drivers/md/md.c:md_integrity_register
  - drivers/md/md.c:md_integrity_register
```
```
In drivers/md/dm-table.c (ffff800010b04834)
Location: include/linux/blkdev.h:1549
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
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
In fs/block_dev.c (c05b7c74)
Location: include/linux/blkdev.h:1549
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
```
```
In block/bio-integrity.c (c07c4af4)
Location: include/linux/blkdev.h:1549
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_trim
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_process
```
```
In drivers/md/md.c (c0bc72d0)
Location: include/linux/blkdev.h:1549
Inline: True
Inline callers:
  - drivers/md/md.c:md_integrity_register
  - drivers/md/md.c:md_integrity_register
```
```
In drivers/md/dm-table.c (c0be386c)
Location: include/linux/blkdev.h:1549
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
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
In fs/block_dev.c (c0000000004e4958)
Location: include/linux/blkdev.h:1549
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
```
```
In block/bio-integrity.c (c0000000007bbaac)
Location: include/linux/blkdev.h:1549
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_trim
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_process
```
```
In drivers/md/md.c (c000000000bcee04)
Location: include/linux/blkdev.h:1549
Inline: True
Inline callers:
  - drivers/md/md.c:md_integrity_register
  - drivers/md/md.c:md_integrity_register
```
```
In drivers/md/dm-table.c (c000000000bf42e4)
Location: include/linux/blkdev.h:1549
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
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
In fs/block_dev.c (ffffffe000296760)
Location: include/linux/blkdev.h:1549
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
```
```
In block/bio-integrity.c (ffffffe00044fd66)
Location: include/linux/blkdev.h:1549
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_trim
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_process
```
```
In drivers/md/md.c (ffffffe0006db1de)
Location: include/linux/blkdev.h:1549
Inline: True
Inline callers:
  - drivers/md/md.c:md_integrity_register
  - drivers/md/md.c:md_integrity_register
```
```
In drivers/md/dm-table.c (ffffffe0006f3a18)
Location: include/linux/blkdev.h:1549
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
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
In fs/block_dev.c (ffffffff8131d95b)
Location: include/linux/blkdev.h:1549
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
```
```
In block/bio-integrity.c (ffffffff8150e300)
Location: include/linux/blkdev.h:1549
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_trim
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_process
```
```
In drivers/nvme/host/core.c (ffffffff81743304)
Location: include/linux/blkdev.h:1549
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_update_disk_info
```
```
In drivers/md/md.c (ffffffff818387e0)
Location: include/linux/blkdev.h:1549
Inline: True
Inline callers:
  - drivers/md/md.c:md_integrity_register
  - drivers/md/md.c:md_integrity_register
```
```
In drivers/md/dm-table.c (ffffffff81853c0f)
Location: include/linux/blkdev.h:1549
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
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
In fs/block_dev.c (ffffffff8130e4fb)
Location: include/linux/blkdev.h:1549
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
```
```
In block/bio-integrity.c (ffffffff814fe730)
Location: include/linux/blkdev.h:1549
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_trim
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_process
```
```
In drivers/nvme/host/core.c (ffffffff81724f94)
Location: include/linux/blkdev.h:1549
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_update_disk_info
```
```
In drivers/md/md.c (ffffffff817ffe50)
Location: include/linux/blkdev.h:1549
Inline: True
Inline callers:
  - drivers/md/md.c:md_integrity_register
  - drivers/md/md.c:md_integrity_register
```
```
In drivers/md/dm-table.c (ffffffff8181b21f)
Location: include/linux/blkdev.h:1549
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
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
In fs/block_dev.c (ffffffff8131b42b)
Location: include/linux/blkdev.h:1549
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
```
```
In block/bio-integrity.c (ffffffff8150a390)
Location: include/linux/blkdev.h:1549
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_trim
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_process
```
```
In drivers/scsi/virtio_scsi.c (ffffffff817728c1)
Location: include/linux/blkdev.h:1549
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_queuecommand
```
```
In drivers/md/md.c (ffffffff81887e10)
Location: include/linux/blkdev.h:1549
Inline: True
Inline callers:
  - drivers/md/md.c:md_integrity_register
  - drivers/md/md.c:md_integrity_register
```
```
In drivers/md/dm-table.c (ffffffff818a323f)
Location: include/linux/blkdev.h:1549
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
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
In fs/block_dev.c (ffffffff8132d0cb)
Location: include/linux/blkdev.h:1549
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
```
```
In block/bio-integrity.c (ffffffff81523a00)
Location: include/linux/blkdev.h:1549
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_trim
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_process
```
```
In drivers/md/md.c (ffffffff818a4980)
Location: include/linux/blkdev.h:1549
Inline: True
Inline callers:
  - drivers/md/md.c:md_integrity_register
  - drivers/md/md.c:md_integrity_register
```
```
In drivers/md/dm-table.c (ffffffff818bf47f)
Location: include/linux/blkdev.h:1549
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
```
</details>
</li>
</ul>

## Differences
