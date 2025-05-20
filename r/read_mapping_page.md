# Function: <code>read_mapping_page</code>

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
In kernel/events/uprobes.c (ffffffff81187415)
Location: include/linux/pagemap.h:384
Inline: True
Inline callers:
  - kernel/events/uprobes.c:prepare_uprobe
```
```
In mm/swapfile.c (ffffffff811d6404)
Location: include/linux/pagemap.h:384
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapon
```
```
In fs/namei.c (ffffffff81217e66)
Location: include/linux/pagemap.h:384
Inline: True
```
```
In fs/ext4/symlink.c (ffffffff812be6a4)
Location: include/linux/pagemap.h:384
Inline: True
Inline callers:
  - fs/ext4/symlink.c:ext4_encrypted_follow_link
```
```
In fs/ecryptfs/mmap.c (ffffffff81304476)
Location: include/linux/pagemap.h:384
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In block/partition-generic.c (ffffffff813ccff6)
Location: include/linux/pagemap.h:384
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
In kernel/events/uprobes.c (ffffffff811999cd)
Location: include/linux/pagemap.h:359
Inline: True
Inline callers:
  - kernel/events/uprobes.c:prepare_uprobe
```
```
In mm/swapfile.c (ffffffff811f44d8)
Location: include/linux/pagemap.h:359
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapon
```
```
In fs/namei.c (ffffffff8123d931)
Location: include/linux/pagemap.h:359
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/ext4/symlink.c (ffffffff812edfed)
Location: include/linux/pagemap.h:359
Inline: True
Inline callers:
  - fs/ext4/symlink.c:ext4_encrypted_get_link
```
```
In fs/ecryptfs/mmap.c (ffffffff81338536)
Location: include/linux/pagemap.h:359
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In block/partition-generic.c (ffffffff81411454)
Location: include/linux/pagemap.h:359
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
In kernel/events/uprobes.c (ffffffff811a912d)
Location: include/linux/pagemap.h:369
Inline: True
Inline callers:
  - kernel/events/uprobes.c:prepare_uprobe
```
```
In mm/swapfile.c (ffffffff81205008)
Location: include/linux/pagemap.h:369
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapon
```
```
In fs/read_write.c (ffffffff8124456a)
Location: include/linux/pagemap.h:369
Inline: True
```
```
In fs/namei.c (ffffffff81250731)
Location: include/linux/pagemap.h:369
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/iomap.c (ffffffff812b1751)
Location: include/linux/pagemap.h:369
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dirty_actor
```
```
In fs/ext4/symlink.c (ffffffff81303f8c)
Location: include/linux/pagemap.h:369
Inline: True
Inline callers:
  - fs/ext4/symlink.c:ext4_encrypted_get_link
```
```
In fs/ecryptfs/mmap.c (ffffffff8134e2f6)
Location: include/linux/pagemap.h:369
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In block/partition-generic.c (ffffffff8142c7ee)
Location: include/linux/pagemap.h:369
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
In kernel/events/uprobes.c (ffffffff811b0de2)
Location: include/linux/pagemap.h:385
Inline: True
```
```
In mm/swapfile.c (ffffffff812106c7)
Location: include/linux/pagemap.h:385
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapon
```
```
In fs/read_write.c (ffffffff8124ffca)
Location: include/linux/pagemap.h:385
Inline: True
```
```
In fs/namei.c (ffffffff8125c8bd)
Location: include/linux/pagemap.h:385
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/iomap.c (ffffffff812beb51)
Location: include/linux/pagemap.h:385
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dirty_actor
```
```
In fs/ext4/symlink.c (ffffffff8133912f)
Location: include/linux/pagemap.h:385
Inline: True
Inline callers:
  - fs/ext4/symlink.c:ext4_encrypted_get_link
```
```
In fs/ecryptfs/mmap.c (ffffffff81362e76)
Location: include/linux/pagemap.h:385
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In block/partition-generic.c (ffffffff81439ad6)
Location: include/linux/pagemap.h:385
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
In kernel/events/uprobes.c (ffffffff811c4972)
Location: include/linux/pagemap.h:398
Inline: True
```
```
In mm/swapfile.c (ffffffff81227b88)
Location: include/linux/pagemap.h:398
Inline: True
Inline callers:
  - mm/swapfile.c:SYSC_swapon
```
```
In fs/read_write.c (ffffffff81271eba)
Location: include/linux/pagemap.h:398
Inline: True
```
```
In fs/namei.c (ffffffff8127ebdd)
Location: include/linux/pagemap.h:398
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/iomap.c (ffffffff812e2551)
Location: include/linux/pagemap.h:398
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dirty_actor
```
```
In fs/ext4/symlink.c (ffffffff8135d42f)
Location: include/linux/pagemap.h:398
Inline: True
Inline callers:
  - fs/ext4/symlink.c:ext4_encrypted_get_link
```
```
In fs/ecryptfs/mmap.c (ffffffff81387b16)
Location: include/linux/pagemap.h:398
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In block/partition-generic.c (ffffffff81465ad6)
Location: include/linux/pagemap.h:398
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
In kernel/events/uprobes.c (ffffffff811e4ef7)
Location: include/linux/pagemap.h:398
Inline: True
```
```
In mm/swapfile.c (ffffffff8124d560)
Location: include/linux/pagemap.h:398
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In fs/read_write.c (ffffffff81297e85)
Location: include/linux/pagemap.h:398
Inline: True
```
```
In fs/namei.c (ffffffff812a556d)
Location: include/linux/pagemap.h:398
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/iomap.c (ffffffff8130ed70)
Location: include/linux/pagemap.h:398
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dirty_actor
```
```
In fs/ext4/symlink.c (ffffffff8138bdda)
Location: include/linux/pagemap.h:398
Inline: True
```
```
In fs/ecryptfs/mmap.c (ffffffff813b67e0)
Location: include/linux/pagemap.h:398
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In block/partition-generic.c (ffffffff814994c0)
Location: include/linux/pagemap.h:398
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
In kernel/events/uprobes.c (ffffffff811f5509)
Location: include/linux/pagemap.h:398
Inline: True
Inline callers:
  - kernel/events/uprobes.c:prepare_uprobe
```
```
In mm/swapfile.c (ffffffff81261979)
Location: include/linux/pagemap.h:398
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In fs/read_write.c (ffffffff812acf55)
Location: include/linux/pagemap.h:398
Inline: True
```
```
In fs/namei.c (ffffffff812ba6dd)
Location: include/linux/pagemap.h:398
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/iomap.c (ffffffff81325b70)
Location: include/linux/pagemap.h:398
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dirty_actor
```
```
In fs/ext4/symlink.c (ffffffff813a496a)
Location: include/linux/pagemap.h:398
Inline: True
```
```
In fs/ecryptfs/mmap.c (ffffffff813cfd30)
Location: include/linux/pagemap.h:398
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In block/partition-generic.c (ffffffff814b3720)
Location: include/linux/pagemap.h:398
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
In kernel/events/uprobes.c (ffffffff8120d1ff)
Location: include/linux/pagemap.h:383
Inline: True
Inline callers:
  - kernel/events/uprobes.c:prepare_uprobe
```
```
In mm/swapfile.c (ffffffff8127c73c)
Location: include/linux/pagemap.h:383
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In fs/read_write.c (ffffffff812c9935)
Location: include/linux/pagemap.h:383
Inline: True
```
```
In fs/namei.c (ffffffff812d72ed)
Location: include/linux/pagemap.h:383
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/iomap/buffered-io.c (ffffffff8134cd37)
Location: include/linux/pagemap.h:383
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_dirty_actor
```
```
In fs/ext4/symlink.c (ffffffff813ceb49)
Location: include/linux/pagemap.h:383
Inline: True
```
```
In fs/ecryptfs/mmap.c (ffffffff813fa915)
Location: include/linux/pagemap.h:383
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In block/partition-generic.c (ffffffff814e1c95)
Location: include/linux/pagemap.h:383
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
In kernel/events/uprobes.c (ffffffff8121a58f)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - kernel/events/uprobes.c:prepare_uprobe
```
```
In mm/swapfile.c (ffffffff8128c21d)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In fs/read_write.c (ffffffff812db345)
Location: include/linux/pagemap.h:393
Inline: True
```
```
In fs/namei.c (ffffffff812e8e4d)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/verity/enable.c (ffffffff8134f7c9)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/iomap/buffered-io.c (ffffffff81365007)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_dirty_actor
```
```
In fs/ext4/symlink.c (ffffffff813e8219)
Location: include/linux/pagemap.h:393
Inline: True
```
```
In fs/ext4/verity.c (ffffffff813eeb95)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
```
```
In fs/ecryptfs/mmap.c (ffffffff814147e5)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In block/partition-generic.c (ffffffff814fb045)
Location: include/linux/pagemap.h:393
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
In kernel/events/uprobes.c (ffffffff81246165)
Location: include/linux/pagemap.h:434
Inline: True
Inline callers:
  - kernel/events/uprobes.c:copy_insn
```
```
In mm/swapfile.c (ffffffff812bf13c)
Location: include/linux/pagemap.h:434
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In fs/read_write.c (ffffffff813114e5)
Location: include/linux/pagemap.h:434
Inline: True
```
```
In fs/namei.c (ffffffff813214fd)
Location: include/linux/pagemap.h:434
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/verity/enable.c (ffffffff81395c79)
Location: include/linux/pagemap.h:434
Inline: True
Inline callers:
  - fs/verity/enable.c:read_file_data_page
```
```
In fs/ext4/symlink.c (ffffffff81434d76)
Location: include/linux/pagemap.h:434
Inline: True
```
```
In fs/ext4/verity.c (ffffffff8143bcd2)
Location: include/linux/pagemap.h:434
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/ecryptfs/mmap.c (ffffffff81462b15)
Location: include/linux/pagemap.h:434
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In block/partitions/core.c (ffffffff8155dd96)
Location: include/linux/pagemap.h:434
Inline: True
Inline callers:
  - block/partitions/core.c:read_part_sector
```
```
In drivers/scsi/scsicam.c (ffffffff81830265)
Location: include/linux/pagemap.h:434
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
In kernel/events/uprobes.c (ffffffff812507d5)
Location: include/linux/pagemap.h:497
Inline: True
Inline callers:
  - kernel/events/uprobes.c:copy_insn
```
```
In mm/swapfile.c (ffffffff812cad5c)
Location: include/linux/pagemap.h:497
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In fs/namei.c (ffffffff8132ca9d)
Location: include/linux/pagemap.h:497
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/remap_range.c (ffffffff81366865)
Location: include/linux/pagemap.h:497
Inline: True
```
```
In fs/verity/enable.c (ffffffff813a797b)
Location: include/linux/pagemap.h:497
Inline: True
Inline callers:
  - fs/verity/enable.c:read_file_data_page
```
```
In fs/ext4/symlink.c (ffffffff8144d856)
Location: include/linux/pagemap.h:497
Inline: True
```
```
In fs/ext4/verity.c (ffffffff81458048)
Location: include/linux/pagemap.h:497
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/ecryptfs/mmap.c (ffffffff8147e615)
Location: include/linux/pagemap.h:497
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In block/partitions/core.c (ffffffff81579ba5)
Location: include/linux/pagemap.h:497
Inline: True
Inline callers:
  - block/partitions/core.c:read_part_sector
```
```
In drivers/scsi/scsicam.c (ffffffff81840ed5)
Location: include/linux/pagemap.h:497
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
In kernel/events/uprobes.c (ffffffff81255ce9)
Location: include/linux/pagemap.h:512
Inline: True
```
```
In mm/swapfile.c (ffffffff812d183a)
Location: include/linux/pagemap.h:512
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In fs/namei.c (ffffffff8133266d)
Location: include/linux/pagemap.h:512
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/remap_range.c (ffffffff8136d115)
Location: include/linux/pagemap.h:512
Inline: True
```
```
In fs/verity/enable.c (ffffffff813ae9d6)
Location: include/linux/pagemap.h:512
Inline: True
Inline callers:
  - fs/verity/enable.c:read_file_data_page
```
```
In fs/ext4/symlink.c (ffffffff81453359)
Location: include/linux/pagemap.h:512
Inline: True
```
```
In fs/ext4/verity.c (ffffffff8145da00)
Location: include/linux/pagemap.h:512
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/ecryptfs/mmap.c (ffffffff814840e5)
Location: include/linux/pagemap.h:512
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In block/partitions/core.c (ffffffff815818dc)
Location: include/linux/pagemap.h:512
Inline: True
Inline callers:
  - block/partitions/core.c:read_part_sector
```
```
In drivers/scsi/scsicam.c (ffffffff818240c5)
Location: include/linux/pagemap.h:512
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
In kernel/events/uprobes.c (ffffffff81291999)
Location: include/linux/pagemap.h:512
Inline: True
```
```
In mm/swapfile.c (ffffffff81316f6a)
Location: include/linux/pagemap.h:512
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In fs/namei.c (ffffffff8137fdfd)
Location: include/linux/pagemap.h:512
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/remap_range.c (ffffffff813bbdf5)
Location: include/linux/pagemap.h:512
Inline: True
```
```
In fs/verity/enable.c (ffffffff813fe573)
Location: include/linux/pagemap.h:512
Inline: True
Inline callers:
  - fs/verity/enable.c:read_file_data_page
```
```
In fs/ext4/symlink.c (ffffffff814a7339)
Location: include/linux/pagemap.h:512
Inline: True
```
```
In fs/ext4/verity.c (ffffffff814b2ebd)
Location: include/linux/pagemap.h:512
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/ecryptfs/mmap.c (ffffffff814db765)
Location: include/linux/pagemap.h:512
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In block/partitions/core.c (ffffffff815e6cdf)
Location: include/linux/pagemap.h:512
Inline: True
Inline callers:
  - block/partitions/core.c:read_part_sector
```
```
In drivers/scsi/scsicam.c (ffffffff818af905)
Location: include/linux/pagemap.h:512
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
In kernel/events/uprobes.c (ffffffff812e70f8)
Location: include/linux/pagemap.h:756
Inline: True
```
```
In mm/swapfile.c (ffffffff8138258d)
Location: include/linux/pagemap.h:756
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In fs/namei.c (ffffffff81400761)
Location: include/linux/pagemap.h:756
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/ext4/verity.c (ffffffff8153c625)
Location: include/linux/pagemap.h:756
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/ecryptfs/mmap.c (ffffffff81569305)
Location: include/linux/pagemap.h:756
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In block/partitions/core.c (ffffffff81695e62)
Location: include/linux/pagemap.h:756
Inline: True
Inline callers:
  - block/partitions/core.c:read_part_sector
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
In kernel/events/uprobes.c (ffffffff81350bf8)
Location: include/linux/pagemap.h:752
Inline: True
```
```
In mm/swapfile.c (ffffffff813fc4f3)
Location: include/linux/pagemap.h:752
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In fs/namei.c (ffffffff8148b1e1)
Location: include/linux/pagemap.h:752
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/ext4/verity.c (ffffffff815dacfe)
Location: include/linux/pagemap.h:752
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/ecryptfs/mmap.c (ffffffff8160ce95)
Location: include/linux/pagemap.h:752
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
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
In kernel/events/uprobes.c (ffffffff81381e5a)
Location: include/linux/pagemap.h:773
Inline: True
```
```
In mm/swapfile.c (ffffffff8142f802)
Location: include/linux/pagemap.h:773
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In fs/namei.c (ffffffff814c0b0f)
Location: include/linux/pagemap.h:773
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/ecryptfs/mmap.c (ffffffff81644d45)
Location: include/linux/pagemap.h:773
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
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
In kernel/events/uprobes.c (ffffffff813ab23a)
Location: include/linux/pagemap.h:885
Inline: True
```
```
In mm/swapfile.c (ffffffff814693d5)
Location: include/linux/pagemap.h:885
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In fs/namei.c (ffffffff814f2f2f)
Location: include/linux/pagemap.h:885
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/ecryptfs/mmap.c (ffffffff8167e265)
Location: include/linux/pagemap.h:885
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
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
In kernel/events/uprobes.c (ffff8000102a61b8)
Location: include/linux/pagemap.h:393
Inline: True
```
```
In mm/swapfile.c (ffff8000103278fc)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In fs/read_write.c (ffff800010380414)
Location: include/linux/pagemap.h:393
Inline: True
```
```
In fs/namei.c (ffff8000103939b4)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/verity/enable.c (ffff8000104111b8)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/iomap/buffered-io.c (ffff80001042bb30)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_dirty_actor
```
```
In fs/ext4/symlink.c (ffff8000104c0ef0)
Location: include/linux/pagemap.h:393
Inline: True
```
```
In fs/ext4/verity.c (ffff8000104c8064)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
```
```
In fs/ecryptfs/mmap.c (ffff8000104f5ef8)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In block/partition-generic.c (ffff8000105fd07c)
Location: include/linux/pagemap.h:393
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
In kernel/events/uprobes.c (c04d539c)
Location: include/linux/pagemap.h:393
Inline: True
```
```
In mm/swapfile.c (c053ece8)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In fs/read_write.c (c056ae68)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_get_page
```
```
In fs/namei.c (c05797a0)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/verity/enable.c (c05dd850)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/iomap/buffered-io.c (c05f4fd0)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_dirty_actor
```
```
In fs/ext4/symlink.c (c0684b7c)
Location: include/linux/pagemap.h:393
Inline: True
```
```
In fs/ext4/verity.c (c068bca4)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/ecryptfs/mmap.c (c06b3774)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In block/partition-generic.c (c07a7894)
Location: include/linux/pagemap.h:393
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
In kernel/events/uprobes.c (c000000000358878)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - kernel/events/uprobes.c:prepare_uprobe
```
```
In mm/swapfile.c (c0000000003fe670)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In fs/read_write.c (c000000000476c2c)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_get_page
```
```
In fs/namei.c (c00000000048aa9c)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/verity/enable.c (c00000000051ed28)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/iomap/buffered-io.c (c00000000053ce14)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_dirty_actor
```
```
In fs/ext4/symlink.c (c0000000005f7800)
Location: include/linux/pagemap.h:393
Inline: True
```
```
In fs/ext4/verity.c (c0000000006007dc)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/ecryptfs/mmap.c (c000000000636ce0)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In block/partition-generic.c (c0000000007966b4)
Location: include/linux/pagemap.h:393
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
In mm/swapfile.c (ffffffe000227774)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In fs/read_write.c (ffffffe000255906)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_get_page
```
```
In fs/namei.c (ffffffe00026143c)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/verity/enable.c (ffffffe0002b95ec)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/iomap/buffered-io.c (ffffffe0002c9318)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_dirty_actor
```
```
In fs/ext4/symlink.c (ffffffe00033c5c2)
Location: include/linux/pagemap.h:393
Inline: True
```
```
In fs/ext4/verity.c (ffffffe000341d3a)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/ecryptfs/mmap.c (ffffffe000364cf8)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In block/partition-generic.c (ffffffe000438c84)
Location: include/linux/pagemap.h:393
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
In kernel/events/uprobes.c (ffffffff81212bdf)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - kernel/events/uprobes.c:prepare_uprobe
```
```
In mm/swapfile.c (ffffffff812847fd)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In fs/read_write.c (ffffffff812d3925)
Location: include/linux/pagemap.h:393
Inline: True
```
```
In fs/namei.c (ffffffff812e142d)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/verity/enable.c (ffffffff81347da9)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/iomap/buffered-io.c (ffffffff8135d5e7)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_dirty_actor
```
```
In fs/ext4/symlink.c (ffffffff813e07f9)
Location: include/linux/pagemap.h:393
Inline: True
```
```
In fs/ext4/verity.c (ffffffff813e7175)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
```
```
In fs/ecryptfs/mmap.c (ffffffff8140cdc5)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In block/partition-generic.c (ffffffff814f3625)
Location: include/linux/pagemap.h:393
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
In kernel/events/uprobes.c (ffffffff8120594f)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - kernel/events/uprobes.c:prepare_uprobe
```
```
In mm/swapfile.c (ffffffff8127666d)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In fs/read_write.c (ffffffff812c45a5)
Location: include/linux/pagemap.h:393
Inline: True
```
```
In fs/namei.c (ffffffff812d206d)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/verity/enable.c (ffffffff81338a89)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/iomap/buffered-io.c (ffffffff8134e287)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_dirty_actor
```
```
In fs/ext4/symlink.c (ffffffff813d1279)
Location: include/linux/pagemap.h:393
Inline: True
```
```
In fs/ext4/verity.c (ffffffff813d7bf5)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
```
```
In fs/ecryptfs/mmap.c (ffffffff813fd845)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In block/partition-generic.c (ffffffff814e3b35)
Location: include/linux/pagemap.h:393
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
In kernel/events/uprobes.c (ffffffff8121097f)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - kernel/events/uprobes.c:prepare_uprobe
```
```
In mm/swapfile.c (ffffffff8128260d)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In fs/read_write.c (ffffffff812d1735)
Location: include/linux/pagemap.h:393
Inline: True
```
```
In fs/namei.c (ffffffff812df23d)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/verity/enable.c (ffffffff81345879)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/iomap/buffered-io.c (ffffffff8135b0b7)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_dirty_actor
```
```
In fs/ext4/symlink.c (ffffffff813ddb79)
Location: include/linux/pagemap.h:393
Inline: True
```
```
In fs/ext4/verity.c (ffffffff813e44f5)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
```
```
In fs/ecryptfs/mmap.c (ffffffff8140a145)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In block/partition-generic.c (ffffffff814ef6b5)
Location: include/linux/pagemap.h:393
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
In kernel/events/uprobes.c (ffffffff8121f88f)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - kernel/events/uprobes.c:prepare_uprobe
```
```
In mm/swapfile.c (ffffffff812922fb)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In fs/read_write.c (ffffffff812e2565)
Location: include/linux/pagemap.h:393
Inline: True
```
```
In fs/namei.c (ffffffff812f062d)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/verity/enable.c (ffffffff81358b54)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/iomap/buffered-io.c (ffffffff8136e837)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_dirty_actor
```
```
In fs/ext4/symlink.c (ffffffff813f2f99)
Location: include/linux/pagemap.h:393
Inline: True
```
```
In fs/ext4/verity.c (ffffffff813f9905)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
```
```
In fs/ecryptfs/mmap.c (ffffffff8141fe45)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In block/partition-generic.c (ffffffff81508745)
Location: include/linux/pagemap.h:393
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
</details>
</li>
</ul>

## Differences
