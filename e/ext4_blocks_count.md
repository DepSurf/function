# Function: <code>ext4_blocks_count</code>

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
In fs/ext4/balloc.c (0)
Location: fs/ext4/ext4.h:2717
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: fs/ext4/ext4.h:2717
Inline: True
```
```
In fs/ext4/super.c (ffffffff81322b52)
Location: fs/ext4/ext4.h:2717
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/resize.c (ffffffff812c0b1f)
Location: fs/ext4/ext4.h:2717
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
```
```
In fs/ext4/migrate.c (0)
Location: fs/ext4/ext4.h:2717
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff812d56b2)
Location: fs/ext4/ext4.h:2717
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
```
In fs/ext4/block_validity.c (0)
Location: fs/ext4/ext4.h:2717
Inline: True
```
```
In fs/ext4/mmp.c (0)
Location: fs/ext4/ext4.h:2717
Inline: True
```
```
In fs/ext4/sysfs.c (0)
Location: fs/ext4/ext4.h:2717
Inline: True
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
In fs/ext4/balloc.c (ffffffff812bd88d)
Location: fs/ext4/ext4.h:2752
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
  - fs/ext4/balloc.c:num_clusters_in_group
```
```
In fs/ext4/inode.c (ffffffff812c4490)
Location: fs/ext4/ext4.h:2752
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
```
In fs/ext4/super.c (ffffffff812e112c)
Location: fs/ext4/ext4.h:2752
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/resize.c (ffffffff812f15f2)
Location: fs/ext4/ext4.h:2752
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/migrate.c (ffffffff812fc779)
Location: fs/ext4/ext4.h:2752
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/mballoc.c (ffffffff8130535c)
Location: fs/ext4/ext4.h:2752
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_initialize_context
```
```
In fs/ext4/block_validity.c (ffffffff8130614d)
Location: fs/ext4/ext4.h:2752
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_data_block_valid
```
```
In fs/ext4/mmp.c (ffffffff81307e93)
Location: fs/ext4/ext4.h:2752
Inline: True
Inline callers:
  - fs/ext4/mmp.c:ext4_multi_mount_protect
```
```
In fs/ext4/sysfs.c (ffffffff813138f7)
Location: fs/ext4/ext4.h:2752
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
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
In fs/ext4/balloc.c (ffffffff812d2edd)
Location: fs/ext4/ext4.h:2730
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
  - fs/ext4/balloc.c:num_clusters_in_group
```
```
In fs/ext4/inode.c (ffffffff812d9b40)
Location: fs/ext4/ext4.h:2730
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
```
In fs/ext4/super.c (ffffffff812f6c5c)
Location: fs/ext4/ext4.h:2730
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/resize.c (ffffffff813075c2)
Location: fs/ext4/ext4.h:2730
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/migrate.c (ffffffff81312729)
Location: fs/ext4/ext4.h:2730
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/mballoc.c (ffffffff8131b32c)
Location: fs/ext4/ext4.h:2730
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_initialize_context
```
```
In fs/ext4/block_validity.c (ffffffff8131c10d)
Location: fs/ext4/ext4.h:2730
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_data_block_valid
```
```
In fs/ext4/mmp.c (ffffffff8131de83)
Location: fs/ext4/ext4.h:2730
Inline: True
Inline callers:
  - fs/ext4/mmp.c:ext4_multi_mount_protect
```
```
In fs/ext4/sysfs.c (ffffffff81329897)
Location: fs/ext4/ext4.h:2730
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
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
In fs/ext4/balloc.c (ffffffff812e44ed)
Location: fs/ext4/ext4.h:2746
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
  - fs/ext4/balloc.c:num_clusters_in_group
```
```
In fs/ext4/block_validity.c (ffffffff812e4cdc)
Location: fs/ext4/ext4.h:2746
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_data_block_valid
```
```
In fs/ext4/fsmap.c (ffffffff812f2ce2)
Location: fs/ext4/ext4.h:2746
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
```
In fs/ext4/inode.c (ffffffff812fda5d)
Location: fs/ext4/ext4.h:2746
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
```
In fs/ext4/mballoc.c (ffffffff8131271c)
Location: fs/ext4/ext4.h:2746
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_initialize_context
```
```
In fs/ext4/migrate.c (ffffffff813141db)
Location: fs/ext4/ext4.h:2746
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/mmp.c (ffffffff81314a93)
Location: fs/ext4/ext4.h:2746
Inline: True
Inline callers:
  - fs/ext4/mmp.c:ext4_multi_mount_protect
```
```
In fs/ext4/resize.c (ffffffff81321db2)
Location: fs/ext4/ext4.h:2746
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff8132b53c)
Location: fs/ext4/ext4.h:2746
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/sysfs.c (ffffffff81339483)
Location: fs/ext4/ext4.h:2746
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
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
In fs/ext4/balloc.c (ffffffff81308f1e)
Location: fs/ext4/ext4.h:2703
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
  - fs/ext4/balloc.c:num_clusters_in_group
```
```
In fs/ext4/block_validity.c (ffffffff8130970c)
Location: fs/ext4/ext4.h:2703
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_data_block_valid
```
```
In fs/ext4/fsmap.c (ffffffff81317272)
Location: fs/ext4/ext4.h:2703
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
```
In fs/ext4/inode.c (ffffffff8132223d)
Location: fs/ext4/ext4.h:2703
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
```
In fs/ext4/mballoc.c (ffffffff81336eec)
Location: fs/ext4/ext4.h:2703
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_initialize_context
```
```
In fs/ext4/migrate.c (ffffffff8133899b)
Location: fs/ext4/ext4.h:2703
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/mmp.c (ffffffff81339253)
Location: fs/ext4/ext4.h:2703
Inline: True
Inline callers:
  - fs/ext4/mmp.c:ext4_multi_mount_protect
```
```
In fs/ext4/resize.c (ffffffff813464f2)
Location: fs/ext4/ext4.h:2703
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff8134f99c)
Location: fs/ext4/ext4.h:2703
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/sysfs.c (ffffffff8135d7f3)
Location: fs/ext4/ext4.h:2703
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
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
In fs/ext4/balloc.c (ffffffff81336e43)
Location: fs/ext4/ext4.h:2708
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:num_clusters_in_group
```
```
In fs/ext4/block_validity.c (ffffffff813375ed)
Location: fs/ext4/ext4.h:2708
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_data_block_valid
```
```
In fs/ext4/fsmap.c (ffffffff81344c52)
Location: fs/ext4/ext4.h:2708
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
```
In fs/ext4/ialloc.c (ffffffff81346a60)
Location: fs/ext4/ext4.h:2708
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff8135132d)
Location: fs/ext4/ext4.h:2708
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
```
In fs/ext4/mballoc.c (ffffffff813654f9)
Location: fs/ext4/ext4.h:2708
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_initialize_context
```
```
In fs/ext4/migrate.c (ffffffff81366ed1)
Location: fs/ext4/ext4.h:2708
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/mmp.c (ffffffff813677a3)
Location: fs/ext4/ext4.h:2708
Inline: True
Inline callers:
  - fs/ext4/mmp.c:ext4_multi_mount_protect
```
```
In fs/ext4/resize.c (ffffffff81374355)
Location: fs/ext4/ext4.h:2708
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813833e6)
Location: fs/ext4/ext4.h:2708
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/sysfs.c (ffffffff8138bf79)
Location: fs/ext4/ext4.h:2708
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
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
In fs/ext4/balloc.c (ffffffff8134e0c3)
Location: fs/ext4/ext4.h:2735
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:num_clusters_in_group
```
```
In fs/ext4/block_validity.c (ffffffff8134e86d)
Location: fs/ext4/ext4.h:2735
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_data_block_valid
```
```
In fs/ext4/fsmap.c (ffffffff8135cda2)
Location: fs/ext4/ext4.h:2735
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
```
In fs/ext4/ialloc.c (ffffffff8135ec10)
Location: fs/ext4/ext4.h:2735
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff8136a1cd)
Location: fs/ext4/ext4.h:2735
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
```
In fs/ext4/mballoc.c (ffffffff8137d8b9)
Location: fs/ext4/ext4.h:2735
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_initialize_context
```
```
In fs/ext4/migrate.c (ffffffff8137f345)
Location: fs/ext4/ext4.h:2735
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/mmp.c (ffffffff8137fc23)
Location: fs/ext4/ext4.h:2735
Inline: True
Inline callers:
  - fs/ext4/mmp.c:ext4_multi_mount_protect
```
```
In fs/ext4/resize.c (ffffffff8138c78a)
Location: fs/ext4/ext4.h:2735
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff8139be06)
Location: fs/ext4/ext4.h:2735
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/sysfs.c (ffffffff813a4b09)
Location: fs/ext4/ext4.h:2735
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
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
In fs/ext4/balloc.c (ffffffff81376a77)
Location: fs/ext4/ext4.h:2815
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:num_clusters_in_group
```
```
In fs/ext4/block_validity.c (ffffffff8137705d)
Location: fs/ext4/ext4.h:2815
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_data_block_valid
```
```
In fs/ext4/fsmap.c (ffffffff81385f25)
Location: fs/ext4/ext4.h:2815
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
```
In fs/ext4/ialloc.c (ffffffff81387e70)
Location: fs/ext4/ext4.h:2815
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff81393621)
Location: fs/ext4/ext4.h:2815
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff813a747b)
Location: fs/ext4/ext4.h:2815
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_initialize_context
```
```
In fs/ext4/migrate.c (ffffffff813a87ad)
Location: fs/ext4/ext4.h:2815
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/mmp.c (ffffffff813a9073)
Location: fs/ext4/ext4.h:2815
Inline: True
Inline callers:
  - fs/ext4/mmp.c:ext4_multi_mount_protect
```
```
In fs/ext4/resize.c (ffffffff813b6e67)
Location: fs/ext4/ext4.h:2815
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:verify_group_input
```
```
In fs/ext4/super.c (ffffffff813c4942)
Location: fs/ext4/ext4.h:2815
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_check_descriptors
```
```
In fs/ext4/sysfs.c (ffffffff813cedc8)
Location: fs/ext4/ext4.h:2815
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
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
In fs/ext4/balloc.c (ffffffff8138ece7)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:num_clusters_in_group
```
```
In fs/ext4/block_validity.c (ffffffff8138f2b8)
Location: fs/ext4/ext4.h:2877
Inline: True
```
```
In fs/ext4/fsmap.c (ffffffff8139e975)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
```
In fs/ext4/ialloc.c (ffffffff813a0820)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff813abfd5)
Location: fs/ext4/ext4.h:2877
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff813c030b)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_initialize_context
```
```
In fs/ext4/migrate.c (ffffffff813c16b5)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/mmp.c (ffffffff813c1f93)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/mmp.c:ext4_multi_mount_protect
```
```
In fs/ext4/resize.c (ffffffff813cfd8d)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:verify_group_input
```
```
In fs/ext4/super.c (ffffffff813ddcc2)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_check_descriptors
```
```
In fs/ext4/sysfs.c (ffffffff813e8498)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
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
In fs/ext4/balloc.c (ffffffff813da297)
Location: fs/ext4/ext4.h:2988
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
```
```
In fs/ext4/block_validity.c (ffffffff813dac44)
Location: fs/ext4/ext4.h:2988
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_inode_block_valid
```
```
In fs/ext4/fsmap.c (ffffffff813eac0c)
Location: fs/ext4/ext4.h:2988
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
```
In fs/ext4/ialloc.c (ffffffff813ecbe3)
Location: fs/ext4/ext4.h:2988
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff813f83c3)
Location: fs/ext4/ext4.h:2988
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff8140c43b)
Location: fs/ext4/ext4.h:2988
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_initialize_context
```
```
In fs/ext4/migrate.c (ffffffff8140d9a4)
Location: fs/ext4/ext4.h:2988
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/mmp.c (ffffffff8140e2b1)
Location: fs/ext4/ext4.h:2988
Inline: True
Inline callers:
  - fs/ext4/mmp.c:ext4_multi_mount_protect
```
```
In fs/ext4/resize.c (ffffffff8141c9f2)
Location: fs/ext4/ext4.h:2988
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_setup_next_flex_gd
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:verify_group_input
```
```
In fs/ext4/super.c (ffffffff81427631)
Location: fs/ext4/ext4.h:2988
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_check_descriptors
```
```
In fs/ext4/sysfs.c (ffffffff814354e0)
Location: fs/ext4/ext4.h:2988
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
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
In fs/ext4/balloc.c (ffffffff813ebf68)
Location: fs/ext4/ext4.h:3165
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
```
```
In fs/ext4/block_validity.c (ffffffff813ec915)
Location: fs/ext4/ext4.h:3165
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_inode_block_valid
```
```
In fs/ext4/fsmap.c (ffffffff813fceb9)
Location: fs/ext4/ext4.h:3165
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
```
In fs/ext4/ialloc.c (ffffffff813fede3)
Location: fs/ext4/ext4.h:3165
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff8140a056)
Location: fs/ext4/ext4.h:3165
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff8141f87a)
Location: fs/ext4/ext4.h:3165
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_initialize_context
```
```
In fs/ext4/migrate.c (ffffffff81420e04)
Location: fs/ext4/ext4.h:3165
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/mmp.c (ffffffff81421754)
Location: fs/ext4/ext4.h:3165
Inline: True
Inline callers:
  - fs/ext4/mmp.c:ext4_multi_mount_protect
```
```
In fs/ext4/resize.c (ffffffff814307bc)
Location: fs/ext4/ext4.h:3165
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_setup_next_flex_gd
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:verify_group_input
```
```
In fs/ext4/super.c (ffffffff8143f408)
Location: fs/ext4/ext4.h:3165
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_check_descriptors
```
```
In fs/ext4/sysfs.c (ffffffff8144df13)
Location: fs/ext4/ext4.h:3165
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
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
In fs/ext4/balloc.c (ffffffff813f249a)
Location: fs/ext4/ext4.h:3227
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
```
```
In fs/ext4/block_validity.c (ffffffff813f2e55)
Location: fs/ext4/ext4.h:3227
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_inode_block_valid
```
```
In fs/ext4/fsmap.c (ffffffff81403309)
Location: fs/ext4/ext4.h:3227
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
```
In fs/ext4/ialloc.c (ffffffff81404ff0)
Location: fs/ext4/ext4.h:3227
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff81410186)
Location: fs/ext4/ext4.h:3227
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff8142614b)
Location: fs/ext4/ext4.h:3227
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_initialize_context
```
```
In fs/ext4/migrate.c (ffffffff814275c4)
Location: fs/ext4/ext4.h:3227
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/mmp.c (ffffffff81427f7b)
Location: fs/ext4/ext4.h:3227
Inline: True
Inline callers:
  - fs/ext4/mmp.c:ext4_multi_mount_protect
```
```
In fs/ext4/resize.c (ffffffff814373b8)
Location: fs/ext4/ext4.h:3227
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_setup_next_flex_gd
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:verify_group_input
```
```
In fs/ext4/super.c (ffffffff8144a478)
Location: fs/ext4/ext4.h:3227
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_check_descriptors
```
```
In fs/ext4/sysfs.c (ffffffff814539d3)
Location: fs/ext4/ext4.h:3227
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
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
In fs/ext4/balloc.c (ffffffff8144447b)
Location: fs/ext4/ext4.h:3297
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
```
```
In fs/ext4/block_validity.c (ffffffff81444e45)
Location: fs/ext4/ext4.h:3297
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_inode_block_valid
```
```
In fs/ext4/fsmap.c (ffffffff81455a49)
Location: fs/ext4/ext4.h:3297
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
```
In fs/ext4/ialloc.c (ffffffff814577f0)
Location: fs/ext4/ext4.h:3297
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff81465786)
Location: fs/ext4/ext4.h:3297
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff81479d5f)
Location: fs/ext4/ext4.h:3297
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_initialize_context
```
```
In fs/ext4/migrate.c (ffffffff8147b241)
Location: fs/ext4/ext4.h:3297
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/mmp.c (ffffffff8147bc2b)
Location: fs/ext4/ext4.h:3297
Inline: True
Inline callers:
  - fs/ext4/mmp.c:ext4_multi_mount_protect
```
```
In fs/ext4/resize.c (ffffffff8148b034)
Location: fs/ext4/ext4.h:3297
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_setup_next_flex_gd
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:verify_group_input
```
```
In fs/ext4/super.c (ffffffff8149df31)
Location: fs/ext4/ext4.h:3297
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_check_descriptors
```
```
In fs/ext4/sysfs.c (ffffffff814a7a43)
Location: fs/ext4/ext4.h:3297
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
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
In fs/ext4/balloc.c (ffffffff814c035b)
Location: fs/ext4/ext4.h:3260
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
```
```
In fs/ext4/block_validity.c (ffffffff814c0e41)
Location: fs/ext4/ext4.h:3260
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_sb_block_valid
```
```
In fs/ext4/fsmap.c (ffffffff814d3397)
Location: fs/ext4/ext4.h:3260
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
```
In fs/ext4/ialloc.c (ffffffff814d530c)
Location: fs/ext4/ext4.h:3260
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff814e512f)
Location: fs/ext4/ext4.h:3260
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff814fbf5f)
Location: fs/ext4/ext4.h:3260
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_initialize_context
```
```
In fs/ext4/migrate.c (ffffffff814fd69f)
Location: fs/ext4/ext4.h:3260
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/mmp.c (ffffffff814fe14c)
Location: fs/ext4/ext4.h:3260
Inline: True
Inline callers:
  - fs/ext4/mmp.c:ext4_multi_mount_protect
```
```
In fs/ext4/resize.c (ffffffff8150ee47)
Location: fs/ext4/ext4.h:3260
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_setup_next_flex_gd
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:verify_group_input
```
```
In fs/ext4/super.c (ffffffff81522531)
Location: fs/ext4/ext4.h:3260
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_check_descriptors
```
```
In fs/ext4/sysfs.c (ffffffff8152f319)
Location: fs/ext4/ext4.h:3260
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
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
In fs/ext4/balloc.c (ffffffff815583ab)
Location: fs/ext4/ext4.h:3273
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
```
```
In fs/ext4/block_validity.c (ffffffff81558fd1)
Location: fs/ext4/ext4.h:3273
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_sb_block_valid
```
```
In fs/ext4/fsmap.c (ffffffff8156bf87)
Location: fs/ext4/ext4.h:3273
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
```
In fs/ext4/ialloc.c (ffffffff8156e28c)
Location: fs/ext4/ext4.h:3273
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff815712b6)
Location: fs/ext4/ext4.h:3273
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffffffff8157bcc7)
Location: fs/ext4/ext4.h:3273
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/mballoc.c (ffffffff815966df)
Location: fs/ext4/ext4.h:3273
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_initialize_context
```
```
In fs/ext4/migrate.c (ffffffff81597e77)
Location: fs/ext4/ext4.h:3273
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/mmp.c (ffffffff8159896c)
Location: fs/ext4/ext4.h:3273
Inline: True
Inline callers:
  - fs/ext4/mmp.c:ext4_multi_mount_protect
```
```
In fs/ext4/resize.c (ffffffff815a9cea)
Location: fs/ext4/ext4.h:3273
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_setup_next_flex_gd
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:verify_group_input
```
```
In fs/ext4/super.c (ffffffff815bf351)
Location: fs/ext4/ext4.h:3273
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_geometry_check
  - fs/ext4/super.c:ext4_geometry_check
  - fs/ext4/super.c:ext4_check_descriptors
```
```
In fs/ext4/sysfs.c (ffffffff815cd029)
Location: fs/ext4/ext4.h:3273
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
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
In fs/ext4/balloc.c (ffffffff815901f7)
Location: fs/ext4/ext4.h:3265
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
```
```
In fs/ext4/block_validity.c (ffffffff81590e21)
Location: fs/ext4/ext4.h:3265
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_sb_block_valid
```
```
In fs/ext4/fsmap.c (ffffffff815a3e3c)
Location: fs/ext4/ext4.h:3265
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
```
In fs/ext4/ialloc.c (ffffffff815a614c)
Location: fs/ext4/ext4.h:3265
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff815a9029)
Location: fs/ext4/ext4.h:3265
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffffffff815b30c7)
Location: fs/ext4/ext4.h:3265
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/mballoc.c (ffffffff815cd118)
Location: fs/ext4/ext4.h:3265
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_new_blocks_simple
  - fs/ext4/mballoc.c:ext4_mb_initialize_context
```
```
In fs/ext4/migrate.c (ffffffff815ce8f5)
Location: fs/ext4/ext4.h:3265
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/mmp.c (ffffffff815cf44c)
Location: fs/ext4/ext4.h:3265
Inline: True
Inline callers:
  - fs/ext4/mmp.c:ext4_multi_mount_protect
```
```
In fs/ext4/resize.c (ffffffff815e054a)
Location: fs/ext4/ext4.h:3265
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_setup_next_flex_gd
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:verify_group_input
```
```
In fs/ext4/super.c (ffffffff815f6511)
Location: fs/ext4/ext4.h:3265
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_check_geometry
  - fs/ext4/super.c:ext4_check_geometry
  - fs/ext4/super.c:ext4_check_geometry
  - fs/ext4/super.c:ext4_check_descriptors
```
```
In fs/ext4/sysfs.c (ffffffff81604fd4)
Location: fs/ext4/ext4.h:3265
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
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
In fs/ext4/balloc.c (ffffffff815c8f37)
Location: fs/ext4/ext4.h:3285
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
```
```
In fs/ext4/block_validity.c (ffffffff815c9b61)
Location: fs/ext4/ext4.h:3285
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_sb_block_valid
```
```
In fs/ext4/fsmap.c (ffffffff815dcc7c)
Location: fs/ext4/ext4.h:3285
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
```
In fs/ext4/ialloc.c (ffffffff815defbc)
Location: fs/ext4/ext4.h:3285
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff815e2279)
Location: fs/ext4/ext4.h:3285
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffffffff815ebeba)
Location: fs/ext4/ext4.h:3285
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/mballoc.c (ffffffff816059f8)
Location: fs/ext4/ext4.h:3285
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_mb_new_blocks_simple
  - fs/ext4/mballoc.c:ext4_mb_initialize_context
```
```
In fs/ext4/migrate.c (ffffffff81607175)
Location: fs/ext4/ext4.h:3285
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/mmp.c (ffffffff81607cdc)
Location: fs/ext4/ext4.h:3285
Inline: True
Inline callers:
  - fs/ext4/mmp.c:ext4_multi_mount_protect
```
```
In fs/ext4/resize.c (ffffffff81619006)
Location: fs/ext4/ext4.h:3285
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_setup_next_flex_gd
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:verify_group_input
```
```
In fs/ext4/super.c (ffffffff8162ee11)
Location: fs/ext4/ext4.h:3285
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_get_journal_blkdev
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_check_geometry
  - fs/ext4/super.c:ext4_check_geometry
  - fs/ext4/super.c:ext4_check_geometry
  - fs/ext4/super.c:ext4_check_descriptors
```
```
In fs/ext4/sysfs.c (ffffffff8163dc94)
Location: fs/ext4/ext4.h:3285
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
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
In fs/ext4/balloc.c (ffff800010461260)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:num_clusters_in_group
```
```
In fs/ext4/block_validity.c (ffff800010461b28)
Location: fs/ext4/ext4.h:2877
Inline: True
```
```
In fs/ext4/fsmap.c (ffff800010471f00)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
```
In fs/ext4/ialloc.c (ffff800010473fd0)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffff80001047eb10)
Location: fs/ext4/ext4.h:2877
Inline: True
```
```
In fs/ext4/mballoc.c (ffff800010496f44)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_initialize_context
```
```
In fs/ext4/migrate.c (ffff800010498b64)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/mmp.c (ffff800010499730)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/mmp.c:ext4_multi_mount_protect
```
```
In fs/ext4/resize.c (ffff8000104a87bc)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:verify_group_input
```
```
In fs/ext4/super.c (ffff8000104b8334)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_check_descriptors
```
```
In fs/ext4/sysfs.c (ffff8000104c11c4)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
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
In fs/ext4/balloc.c (c0621904)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:num_clusters_in_group
```
```
In fs/ext4/block_validity.c (c0621dd4)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_data_block_valid_rcu
```
```
In fs/ext4/fsmap.c (c06334c0)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
```
In fs/ext4/ialloc.c (c06353dc)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (c063f920)
Location: fs/ext4/ext4.h:2877
Inline: True
```
```
In fs/ext4/mballoc.c (c0659130)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_initialize_context
```
```
In fs/ext4/migrate.c (c065a768)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/mmp.c (c065b1c8)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/mmp.c:ext4_multi_mount_protect
```
```
In fs/ext4/resize.c (c066b114)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:verify_group_input
```
```
In fs/ext4/super.c (c0675878)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_check_descriptors
```
```
In fs/ext4/sysfs.c (c0684d14)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
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
In fs/ext4/balloc.c (c00000000057d978)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:num_clusters_in_group
```
```
In fs/ext4/block_validity.c (c00000000057df74)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_data_block_valid_rcu
```
```
In fs/ext4/fsmap.c (c000000000592a74)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
```
In fs/ext4/ialloc.c (c000000000595314)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (c0000000005a23d0)
Location: fs/ext4/ext4.h:2877
Inline: True
```
```
In fs/ext4/mballoc.c (c0000000005c1358)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_initialize_context
```
```
In fs/ext4/migrate.c (c0000000005c2f20)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/mmp.c (c0000000005c3b30)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/mmp.c:ext4_multi_mount_protect
```
```
In fs/ext4/resize.c (c0000000005d68e8)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:verify_group_input
```
```
In fs/ext4/super.c (c0000000005e5610)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_check_descriptors
```
```
In fs/ext4/sysfs.c (c0000000005f7b40)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
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
In fs/ext4/balloc.c (ffffffe0002f0504)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:num_clusters_in_group
```
```
In fs/ext4/block_validity.c (ffffffe0002f0892)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_data_block_valid_rcu
```
```
In fs/ext4/fsmap.c (ffffffe0002fdeec)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
```
In fs/ext4/ialloc.c (ffffffe0002ffa30)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffe000309544)
Location: fs/ext4/ext4.h:2877
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffe00031b97a)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_initialize_context
```
```
In fs/ext4/migrate.c (ffffffe00031ca62)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/mmp.c (ffffffe00031d1c8)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/mmp.c:ext4_multi_mount_protect
```
```
In fs/ext4/resize.c (ffffffe000328fd0)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:verify_group_input
```
```
In fs/ext4/super.c (ffffffe0003315e2)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_check_descriptors
```
```
In fs/ext4/sysfs.c (ffffffe00033c790)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
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
In fs/ext4/balloc.c (ffffffff813872c7)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:num_clusters_in_group
```
```
In fs/ext4/block_validity.c (ffffffff81387898)
Location: fs/ext4/ext4.h:2877
Inline: True
```
```
In fs/ext4/fsmap.c (ffffffff81396f55)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
```
In fs/ext4/ialloc.c (ffffffff81398e00)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff813a45b5)
Location: fs/ext4/ext4.h:2877
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff813b88eb)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_initialize_context
```
```
In fs/ext4/migrate.c (ffffffff813b9c95)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/mmp.c (ffffffff813ba573)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/mmp.c:ext4_multi_mount_protect
```
```
In fs/ext4/resize.c (ffffffff813c836d)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:verify_group_input
```
```
In fs/ext4/super.c (ffffffff813d62a2)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_check_descriptors
```
```
In fs/ext4/sysfs.c (ffffffff813e0a78)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
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
In fs/ext4/balloc.c (ffffffff81377d57)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:num_clusters_in_group
```
```
In fs/ext4/block_validity.c (ffffffff81378328)
Location: fs/ext4/ext4.h:2877
Inline: True
```
```
In fs/ext4/fsmap.c (ffffffff813879e5)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
```
In fs/ext4/ialloc.c (ffffffff81389890)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff81395045)
Location: fs/ext4/ext4.h:2877
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff813a937b)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_initialize_context
```
```
In fs/ext4/migrate.c (ffffffff813aa725)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/mmp.c (ffffffff813ab003)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/mmp.c:ext4_multi_mount_protect
```
```
In fs/ext4/resize.c (ffffffff813b8ded)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:verify_group_input
```
```
In fs/ext4/super.c (ffffffff813c6d22)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_check_descriptors
```
```
In fs/ext4/sysfs.c (ffffffff813d14f8)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
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
In fs/ext4/balloc.c (ffffffff81384d97)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:num_clusters_in_group
```
```
In fs/ext4/block_validity.c (ffffffff81385368)
Location: fs/ext4/ext4.h:2877
Inline: True
```
```
In fs/ext4/fsmap.c (ffffffff813948b5)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
```
In fs/ext4/ialloc.c (ffffffff81396660)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff813a1e15)
Location: fs/ext4/ext4.h:2877
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff813b614b)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_initialize_context
```
```
In fs/ext4/migrate.c (ffffffff813b74f5)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/mmp.c (ffffffff813b7dd3)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/mmp.c:ext4_multi_mount_protect
```
```
In fs/ext4/resize.c (ffffffff813c57fd)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:verify_group_input
```
```
In fs/ext4/super.c (ffffffff813d3732)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_check_descriptors
```
```
In fs/ext4/sysfs.c (ffffffff813dddf8)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
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
In fs/ext4/balloc.c (ffffffff81398917)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:num_clusters_in_group
```
```
In fs/ext4/block_validity.c (ffffffff81398ee8)
Location: fs/ext4/ext4.h:2877
Inline: True
```
```
In fs/ext4/fsmap.c (ffffffff813a89a5)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
```
In fs/ext4/ialloc.c (ffffffff813aa8c0)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff813b5295)
Location: fs/ext4/ext4.h:2877
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff813cae4b)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_initialize_context
```
```
In fs/ext4/migrate.c (ffffffff813cc205)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/mmp.c (ffffffff813ccad3)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/mmp.c:ext4_multi_mount_protect
```
```
In fs/ext4/resize.c (ffffffff813daa2d)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:verify_group_input
```
```
In fs/ext4/super.c (ffffffff813e4732)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_check_descriptors
```
```
In fs/ext4/sysfs.c (ffffffff813f3218)
Location: fs/ext4/ext4.h:2877
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
</details>
</li>
</ul>

## Differences
