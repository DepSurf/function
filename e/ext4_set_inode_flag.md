# Function: <code>ext4_set_inode_flag</code>

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
In fs/ext4/ialloc.c (ffffffff8129534f)
Location: fs/ext4/ext4.h:1504
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff8129b2b1)
Location: fs/ext4/ext4.h:1504
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
```
```
In fs/ext4/ioctl.c (ffffffff812a0969)
Location: fs/ext4/ext4.h:1504
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/namei.c (ffffffff812a5a5f)
Location: fs/ext4/ext4.h:1504
Inline: True
```
```
In fs/ext4/extents.c (ffffffff812c35db)
Location: fs/ext4/ext4.h:1504
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fallocate
```
```
In fs/ext4/migrate.c (ffffffff812ccaba)
Location: fs/ext4/ext4.h:1504
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/inline.c (ffffffff812df8de)
Location: fs/ext4/ext4.h:1504
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
```
```
In fs/ext4/crypto_policy.c (ffffffff812e4a06)
Location: fs/ext4/ext4.h:1504
Inline: True
Inline callers:
  - fs/ext4/crypto_policy.c:ext4_process_policy
  - fs/ext4/crypto_policy.c:ext4_inherit_context
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
In fs/ext4/ialloc.c (ffffffff812c2c10)
Location: fs/ext4/ext4.h:1581
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff812cd80b)
Location: fs/ext4/ext4.h:1581
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/ioctl.c (ffffffff812cff70)
Location: fs/ext4/ext4.h:1581
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/namei.c (ffffffff812d4b07)
Location: fs/ext4/ext4.h:1581
Inline: True
Inline callers:
  - fs/ext4/namei.c:make_indexed_dir
```
```
In fs/ext4/super.c (ffffffff812e738f)
Location: fs/ext4/ext4.h:1581
Inline: True
```
```
In fs/ext4/extents.c (ffffffff812fa839)
Location: fs/ext4/ext4.h:1581
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fallocate
```
```
In fs/ext4/migrate.c (ffffffff812fc433)
Location: fs/ext4/ext4.h:1581
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/inline.c (ffffffff8130f75b)
Location: fs/ext4/ext4.h:1581
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_create_inline_data
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
In fs/ext4/ialloc.c (ffffffff812d81fb)
Location: fs/ext4/ext4.h:1586
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff812e35d3)
Location: fs/ext4/ext4.h:1586
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/ioctl.c (ffffffff812e5d4a)
Location: fs/ext4/ext4.h:1586
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/namei.c (ffffffff812ea812)
Location: fs/ext4/ext4.h:1586
Inline: True
Inline callers:
  - fs/ext4/namei.c:make_indexed_dir
```
```
In fs/ext4/super.c (ffffffff812fd0bf)
Location: fs/ext4/ext4.h:1586
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/super.c:ext4_set_context
```
```
In fs/ext4/extents.c (ffffffff813107d9)
Location: fs/ext4/ext4.h:1586
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fallocate
```
```
In fs/ext4/migrate.c (ffffffff813123e3)
Location: fs/ext4/ext4.h:1586
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/inline.c (ffffffff81325583)
Location: fs/ext4/ext4.h:1586
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_create_inline_data
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
In fs/ext4/extents.c (ffffffff812eed3b)
Location: fs/ext4/ext4.h:1591
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_alloc_file_blocks
```
```
In fs/ext4/ialloc.c (ffffffff812f6550)
Location: fs/ext4/ext4.h:1591
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (ffffffff812f9602)
Location: fs/ext4/ext4.h:1591
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff813077a8)
Location: fs/ext4/ext4.h:1591
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/ioctl.c (ffffffff813097d3)
Location: fs/ext4/ext4.h:1591
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/migrate.c (ffffffff81313dcb)
Location: fs/ext4/ext4.h:1591
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff8131a4dc)
Location: fs/ext4/ext4.h:1591
Inline: True
Inline callers:
  - fs/ext4/namei.c:make_indexed_dir
```
```
In fs/ext4/super.c (ffffffff81331d13)
Location: fs/ext4/ext4.h:1591
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/super.c:ext4_set_context
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
In fs/ext4/extents.c (ffffffff81313843)
Location: fs/ext4/ext4.h:1551
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_alloc_file_blocks
```
```
In fs/ext4/ialloc.c (ffffffff8131ab27)
Location: fs/ext4/ext4.h:1551
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (ffffffff8131dc3a)
Location: fs/ext4/ext4.h:1551
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff8132c3f6)
Location: fs/ext4/ext4.h:1551
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/ioctl.c (ffffffff8132e2a1)
Location: fs/ext4/ext4.h:1551
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/migrate.c (ffffffff8133858b)
Location: fs/ext4/ext4.h:1551
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff8133ec1c)
Location: fs/ext4/ext4.h:1551
Inline: True
Inline callers:
  - fs/ext4/namei.c:make_indexed_dir
```
```
In fs/ext4/super.c (ffffffff81356148)
Location: fs/ext4/ext4.h:1551
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/super.c:ext4_set_context
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
In fs/ext4/extents.c (ffffffff813417cc)
Location: fs/ext4/ext4.h:1554
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_alloc_file_blocks
```
```
In fs/ext4/ialloc.c (ffffffff81348a82)
Location: fs/ext4/ext4.h:1554
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (ffffffff8134bc1d)
Location: fs/ext4/ext4.h:1554
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff8135a954)
Location: fs/ext4/ext4.h:1554
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/ioctl.c (ffffffff8135ca76)
Location: fs/ext4/ext4.h:1554
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/migrate.c (ffffffff81366b4c)
Location: fs/ext4/ext4.h:1554
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff8136cbf5)
Location: fs/ext4/ext4.h:1554
Inline: True
Inline callers:
  - fs/ext4/namei.c:make_indexed_dir
```
```
In fs/ext4/super.c (ffffffff813844d8)
Location: fs/ext4/ext4.h:1554
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/super.c:ext4_set_context
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
In fs/ext4/extents.c (ffffffff81358e1a)
Location: fs/ext4/ext4.h:1567
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_alloc_file_blocks
```
```
In fs/ext4/ialloc.c (ffffffff81360c32)
Location: fs/ext4/ext4.h:1567
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (ffffffff81363d5d)
Location: fs/ext4/ext4.h:1567
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff81372c14)
Location: fs/ext4/ext4.h:1567
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/ioctl.c (ffffffff8137521c)
Location: fs/ext4/ext4.h:1567
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/migrate.c (ffffffff8137efbd)
Location: fs/ext4/ext4.h:1567
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff81385075)
Location: fs/ext4/ext4.h:1567
Inline: True
Inline callers:
  - fs/ext4/namei.c:make_indexed_dir
```
```
In fs/ext4/super.c (ffffffff8139cfb8)
Location: fs/ext4/ext4.h:1567
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/super.c:ext4_set_context
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
In fs/ext4/extents.c (ffffffff8137a6e8)
Location: fs/ext4/ext4.h:1584
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
```
```
In fs/ext4/ialloc.c (ffffffff81389cb7)
Location: fs/ext4/ext4.h:1584
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (ffffffff8138d35e)
Location: fs/ext4/ext4.h:1584
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff8139c063)
Location: fs/ext4/ext4.h:1584
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/ioctl.c (ffffffff8139ced7)
Location: fs/ext4/ext4.h:1584
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (ffffffff813a83c0)
Location: fs/ext4/ext4.h:1584
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff813aef64)
Location: fs/ext4/ext4.h:1584
Inline: True
Inline callers:
  - fs/ext4/namei.c:make_indexed_dir
```
```
In fs/ext4/super.c (ffffffff813c71d8)
Location: fs/ext4/ext4.h:1584
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/super.c:ext4_set_context
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
In fs/ext4/extents.c (ffffffff81392bb8)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
```
```
In fs/ext4/ialloc.c (ffffffff813a26ba)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (ffffffff813a5dbe)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff813b4b73)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/ioctl.c (ffffffff813b5957)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (ffffffff813c1281)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff813c7eb4)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/namei.c:make_indexed_dir
```
```
In fs/ext4/super.c (ffffffff813e0598)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/super.c:ext4_set_context
```
```
In fs/ext4/verity.c (ffffffff813ef433)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
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
In fs/ext4/ialloc.c (ffffffff813ee7ad)
Location: fs/ext4/ext4.h:1724
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (ffffffff813f234e)
Location: fs/ext4/ext4.h:1724
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff813fffff)
Location: fs/ext4/ext4.h:1724
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
```
```
In fs/ext4/ioctl.c (ffffffff814011c4)
Location: fs/ext4/ext4.h:1724
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (ffffffff8140d184)
Location: fs/ext4/ext4.h:1724
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
```
```
In fs/ext4/namei.c (ffffffff81413e13)
Location: fs/ext4/ext4.h:1724
Inline: True
Inline callers:
  - fs/ext4/namei.c:make_indexed_dir
```
```
In fs/ext4/super.c (ffffffff8142d2e5)
Location: fs/ext4/ext4.h:1724
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/super.c:ext4_set_context
```
```
In fs/ext4/verity.c (ffffffff8143c24b)
Location: fs/ext4/ext4.h:1724
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
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
In fs/ext4/ialloc.c (ffffffff81400e5b)
Location: fs/ext4/ext4.h:1841
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (ffffffff81404a9e)
Location: fs/ext4/ext4.h:1841
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff8141276f)
Location: fs/ext4/ext4.h:1841
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
```
```
In fs/ext4/ioctl.c (ffffffff81413a84)
Location: fs/ext4/ext4.h:1841
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (ffffffff814205e4)
Location: fs/ext4/ext4.h:1841
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
```
```
In fs/ext4/namei.c (ffffffff814273f3)
Location: fs/ext4/ext4.h:1841
Inline: True
Inline callers:
  - fs/ext4/namei.c:make_indexed_dir
```
```
In fs/ext4/super.c (ffffffff814460b5)
Location: fs/ext4/ext4.h:1841
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/super.c:ext4_set_context
```
```
In fs/ext4/verity.c (ffffffff814585b8)
Location: fs/ext4/ext4.h:1841
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
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
In fs/ext4/ialloc.c (ffffffff814073ed)
Location: fs/ext4/ext4.h:1850
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (ffffffff8140b05e)
Location: fs/ext4/ext4.h:1850
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff81418bcf)
Location: fs/ext4/ext4.h:1850
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
```
```
In fs/ext4/ioctl.c (ffffffff81419d1b)
Location: fs/ext4/ext4.h:1850
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (ffffffff81426cb4)
Location: fs/ext4/ext4.h:1850
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
```
```
In fs/ext4/namei.c (ffffffff8142deff)
Location: fs/ext4/ext4.h:1850
Inline: True
Inline callers:
  - fs/ext4/namei.c:make_indexed_dir
```
```
In fs/ext4/super.c (ffffffff8144b865)
Location: fs/ext4/ext4.h:1850
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/super.c:ext4_set_context
```
```
In fs/ext4/verity.c (ffffffff8145df5a)
Location: fs/ext4/ext4.h:1850
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
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
In fs/ext4/ialloc.c (ffffffff81459c8b)
Location: fs/ext4/ext4.h:1912
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (ffffffff8145dcc8)
Location: fs/ext4/ext4.h:1912
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff8146bdee)
Location: fs/ext4/ext4.h:1912
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
```
```
In fs/ext4/ioctl.c (ffffffff8146cf0b)
Location: fs/ext4/ext4.h:1912
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (ffffffff8147a944)
Location: fs/ext4/ext4.h:1912
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
```
```
In fs/ext4/namei.c (ffffffff81481e25)
Location: fs/ext4/ext4.h:1912
Inline: True
Inline callers:
  - fs/ext4/namei.c:make_indexed_dir
```
```
In fs/ext4/super.c (ffffffff8149f865)
Location: fs/ext4/ext4.h:1912
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/super.c:ext4_set_context
```
```
In fs/ext4/verity.c (ffffffff814b3479)
Location: fs/ext4/ext4.h:1912
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
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
In fs/ext4/ialloc.c (ffffffff814d7917)
Location: fs/ext4/ext4.h:1914
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (ffffffff814db4db)
Location: fs/ext4/ext4.h:1914
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff814ebe85)
Location: fs/ext4/ext4.h:1914
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_fill_raw_inode
```
```
In fs/ext4/ioctl.c (ffffffff814ec8b9)
Location: fs/ext4/ext4.h:1914
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (ffffffff814fcd2d)
Location: fs/ext4/ext4.h:1914
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
```
```
In fs/ext4/namei.c (ffffffff81504dae)
Location: fs/ext4/ext4.h:1914
Inline: True
Inline callers:
  - fs/ext4/namei.c:make_indexed_dir
```
```
In fs/ext4/verity.c (ffffffff8153c061)
Location: fs/ext4/ext4.h:1914
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
```
```
In fs/ext4/crypto.c (ffffffff8153c8e2)
Location: fs/ext4/ext4.h:1914
Inline: True
Inline callers:
  - fs/ext4/crypto.c:ext4_set_context
  - fs/ext4/crypto.c:ext4_set_context
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
In fs/ext4/ialloc.c (ffffffff81570674)
Location: fs/ext4/ext4.h:1924
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (ffffffff8157415b)
Location: fs/ext4/ext4.h:1924
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff81585be2)
Location: fs/ext4/ext4.h:1924
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_fill_raw_inode
```
```
In fs/ext4/ioctl.c (ffffffff8158663d)
Location: fs/ext4/ext4.h:1924
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (ffffffff815974bd)
Location: fs/ext4/ext4.h:1924
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
```
```
In fs/ext4/namei.c (ffffffff8159f994)
Location: fs/ext4/ext4.h:1924
Inline: True
Inline callers:
  - fs/ext4/namei.c:make_indexed_dir
```
```
In fs/ext4/verity.c (ffffffff815da716)
Location: fs/ext4/ext4.h:1924
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
```
```
In fs/ext4/crypto.c (ffffffff815db052)
Location: fs/ext4/ext4.h:1924
Inline: True
Inline callers:
  - fs/ext4/crypto.c:ext4_set_context
  - fs/ext4/crypto.c:ext4_set_context
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
In fs/ext4/ialloc.c (ffffffff815a84fc)
Location: fs/ext4/ext4.h:1918
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (ffffffff815abfab)
Location: fs/ext4/ext4.h:1918
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff815bc306)
Location: fs/ext4/ext4.h:1918
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_fill_raw_inode
```
```
In fs/ext4/ioctl.c (ffffffff815bcd7d)
Location: fs/ext4/ext4.h:1918
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (ffffffff815cdef6)
Location: fs/ext4/ext4.h:1918
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
```
```
In fs/ext4/namei.c (ffffffff815d62a4)
Location: fs/ext4/ext4.h:1918
Inline: True
Inline callers:
  - fs/ext4/namei.c:make_indexed_dir
```
```
In fs/ext4/verity.c (ffffffff816124e9)
Location: fs/ext4/ext4.h:1918
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
```
```
In fs/ext4/crypto.c (ffffffff81612b02)
Location: fs/ext4/ext4.h:1918
Inline: True
Inline callers:
  - fs/ext4/crypto.c:ext4_set_context
  - fs/ext4/crypto.c:ext4_set_context
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
In fs/ext4/ialloc.c (ffffffff815e12b1)
Location: fs/ext4/ext4.h:1936
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (ffffffff815e4d4b)
Location: fs/ext4/ext4.h:1936
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff815f50e6)
Location: fs/ext4/ext4.h:1936
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_fill_raw_inode
```
```
In fs/ext4/ioctl.c (ffffffff815f5b56)
Location: fs/ext4/ext4.h:1936
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (ffffffff81606776)
Location: fs/ext4/ext4.h:1936
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
```
```
In fs/ext4/namei.c (ffffffff8160e931)
Location: fs/ext4/ext4.h:1936
Inline: True
Inline callers:
  - fs/ext4/namei.c:make_indexed_dir
```
```
In fs/ext4/verity.c (ffffffff8164b1b9)
Location: fs/ext4/ext4.h:1936
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
```
```
In fs/ext4/crypto.c (ffffffff8164b882)
Location: fs/ext4/ext4.h:1936
Inline: True
Inline callers:
  - fs/ext4/crypto.c:ext4_set_context
  - fs/ext4/crypto.c:ext4_set_context
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
In fs/ext4/extents.c (ffff800010465364)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
```
```
In fs/ext4/ialloc.c (ffff80001047585c)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (ffff8000104795cc)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffff8000104892e0)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/ioctl.c (ffff80001048ab98)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (ffff80001049833c)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
```
```
In fs/ext4/namei.c (ffff80001049f8ac)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/namei.c:make_indexed_dir
```
```
In fs/ext4/super.c (ffff8000104b97d0)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/super.c:ext4_set_context
```
```
In fs/ext4/verity.c (ffff8000104c8930)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
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
In fs/ext4/extents.c (c0626714)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
```
```
In fs/ext4/ialloc.c (c0637050)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (c063ab80)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (c064b800)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/ioctl.c (c064c144)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (c065a328)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (c0661d24)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
```
```
In fs/ext4/super.c (c067cf2c)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/super.c:ext4_set_context
```
```
In fs/ext4/verity.c (c068c290)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
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
In fs/ext4/extents.c (c000000000583b18)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
```
```
In fs/ext4/ialloc.c (c000000000597a18)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (c00000000059bae8)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (c0000000005b022c)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/ioctl.c (c0000000005b14c0)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (c0000000005c2a34)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (c0000000005cb6dc)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/namei.c:make_indexed_dir
```
```
In fs/ext4/super.c (c0000000005eecbc)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/super.c:ext4_set_context
```
```
In fs/ext4/verity.c (c00000000060101c)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
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
In fs/ext4/extents.c (ffffffe0002f3c30)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
```
```
In fs/ext4/ialloc.c (ffffffe0003016b4)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (ffffffe000303ee2)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffe000310b22)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/ioctl.c (ffffffe000311700)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (ffffffe00031c680)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffe000321e92)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/namei.c:make_indexed_dir
```
```
In fs/ext4/super.c (ffffffe000335f22)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/super.c:ext4_set_context
```
```
In fs/ext4/verity.c (ffffffe000342226)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
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
In fs/ext4/extents.c (ffffffff8138b198)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
```
```
In fs/ext4/ialloc.c (ffffffff8139ac9a)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (ffffffff8139e39e)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff813ad153)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/ioctl.c (ffffffff813adf37)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (ffffffff813b9861)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff813c0494)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/namei.c:make_indexed_dir
```
```
In fs/ext4/super.c (ffffffff813d8b78)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/super.c:ext4_set_context
```
```
In fs/ext4/verity.c (ffffffff813e7a13)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
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
In fs/ext4/extents.c (ffffffff8137bc28)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
```
```
In fs/ext4/ialloc.c (ffffffff8138b72a)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (ffffffff8138ee2e)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff8139dbe3)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/ioctl.c (ffffffff8139e9c7)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (ffffffff813aa2f1)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff813b0f24)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/namei.c:make_indexed_dir
```
```
In fs/ext4/super.c (ffffffff813c95f8)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/super.c:ext4_set_context
```
```
In fs/ext4/verity.c (ffffffff813d8493)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
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
In fs/ext4/extents.c (ffffffff81388af8)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
```
```
In fs/ext4/ialloc.c (ffffffff813984fa)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (ffffffff8139bbfe)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff813aa9b3)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/ioctl.c (ffffffff813ab797)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (ffffffff813b70c1)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff813bd964)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/namei.c:make_indexed_dir
```
```
In fs/ext4/super.c (ffffffff813d6008)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/super.c:ext4_set_context
```
```
In fs/ext4/verity.c (ffffffff813e4d93)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
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
In fs/ext4/extents.c (ffffffff8139c811)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
```
```
In fs/ext4/ialloc.c (ffffffff813ac9cc)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (ffffffff813b011e)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff813bf303)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/ioctl.c (ffffffff813c0137)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (ffffffff813cbdd1)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff813d2a24)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/namei.c:make_indexed_dir
```
```
In fs/ext4/super.c (ffffffff813eb2a8)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/super.c:ext4_set_context
```
```
In fs/ext4/verity.c (ffffffff813fa1e3)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
```
</details>
</li>
</ul>

## Differences
