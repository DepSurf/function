# Function: <code>ext4_journal_restart</code>

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
In fs/ext4/inode.c (ffffffff8129882a)
Location: fs/ext4/ext4_jbd2.h:341
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate_restart_trans
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/resize.c (ffffffff812bef06)
Location: fs/ext4/ext4_jbd2.h:341
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/migrate.c (ffffffff812cc125)
Location: fs/ext4/ext4_jbd2.h:341
Inline: True
Inline callers:
  - fs/ext4/migrate.c:finish_range
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
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
In fs/ext4/inode.c (ffffffff812cb653)
Location: fs/ext4/ext4_jbd2.h:349
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_truncate_restart_trans
```
```
In fs/ext4/resize.c (ffffffff812ee95d)
Location: fs/ext4/ext4_jbd2.h:349
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/migrate.c (ffffffff812fc329)
Location: fs/ext4/ext4_jbd2.h:349
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:finish_range
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
In fs/ext4/inode.c (ffffffff812e1333)
Location: fs/ext4/ext4_jbd2.h:349
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_truncate_restart_trans
```
```
In fs/ext4/resize.c (ffffffff8130492d)
Location: fs/ext4/ext4_jbd2.h:349
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/migrate.c (ffffffff813122d9)
Location: fs/ext4/ext4_jbd2.h:349
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:finish_range
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
In fs/ext4/inode.c (ffffffff812ffac7)
Location: fs/ext4/ext4_jbd2.h:345
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate_restart_trans
```
```
In fs/ext4/migrate.c (ffffffff813140d2)
Location: fs/ext4/ext4_jbd2.h:345
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/resize.c (ffffffff8131f4b5)
Location: fs/ext4/ext4_jbd2.h:345
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/xattr.c (ffffffff8133a578)
Location: fs/ext4/ext4_jbd2.h:345
Inline: True
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
In fs/ext4/inode.c (ffffffff813242d4)
Location: fs/ext4/ext4_jbd2.h:345
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate_restart_trans
```
```
In fs/ext4/migrate.c (ffffffff81338892)
Location: fs/ext4/ext4_jbd2.h:345
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/resize.c (ffffffff81343b55)
Location: fs/ext4/ext4_jbd2.h:345
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/xattr.c (ffffffff8135e948)
Location: fs/ext4/ext4_jbd2.h:345
Inline: True
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
In fs/ext4/inode.c (ffffffff8135251f)
Location: fs/ext4/ext4_jbd2.h:342
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate_restart_trans
```
```
In fs/ext4/migrate.c (ffffffff81366ae6)
Location: fs/ext4/ext4_jbd2.h:342
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:finish_range
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/resize.c (ffffffff813719f6)
Location: fs/ext4/ext4_jbd2.h:342
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/xattr.c (ffffffff8138d2a0)
Location: fs/ext4/ext4_jbd2.h:342
Inline: True
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
In fs/ext4/inode.c (ffffffff8136a63f)
Location: fs/ext4/ext4_jbd2.h:342
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate_restart_trans
```
```
In fs/ext4/migrate.c (ffffffff8137ef36)
Location: fs/ext4/ext4_jbd2.h:342
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:finish_range
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/resize.c (ffffffff81389e8f)
Location: fs/ext4/ext4_jbd2.h:342
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/xattr.c (ffffffff813a5eb0)
Location: fs/ext4/ext4_jbd2.h:342
Inline: True
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
In fs/ext4/inode.c (ffffffff81393b3f)
Location: fs/ext4/ext4_jbd2.h:342
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate_restart_trans
```
```
In fs/ext4/migrate.c (ffffffff813a869b)
Location: fs/ext4/ext4_jbd2.h:342
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:finish_range
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/resize.c (ffffffff813b48fc)
Location: fs/ext4/ext4_jbd2.h:342
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/xattr.c (ffffffff813cff01)
Location: fs/ext4/ext4_jbd2.h:342
Inline: True
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
In fs/ext4/inode.c (ffffffff813ac4df)
Location: fs/ext4/ext4_jbd2.h:342
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate_restart_trans
```
```
In fs/ext4/migrate.c (ffffffff813c1520)
Location: fs/ext4/ext4_jbd2.h:342
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:finish_range
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/resize.c (ffffffff813cd7fc)
Location: fs/ext4/ext4_jbd2.h:342
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/xattr.c (ffffffff813e95d1)
Location: fs/ext4/ext4_jbd2.h:342
Inline: True
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
In fs/ext4/extents.c (ffffffff813dff0e)
Location: fs/ext4/ext4_jbd2.h:353
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_datasem_ensure_credits
```
```
In fs/ext4/indirect.c (ffffffff813ef9c3)
Location: fs/ext4/ext4_jbd2.h:353
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
```
```
In fs/ext4/migrate.c (ffffffff8140d616)
Location: fs/ext4/ext4_jbd2.h:353
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:free_tind_blocks
  - fs/ext4/migrate.c:free_tind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
```
```
In fs/ext4/resize.c (ffffffff81419bf8)
Location: fs/ext4/ext4_jbd2.h:353
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:set_flexbg_block_bitmap
```
```
In fs/ext4/xattr.c (ffffffff8143ac7c)
Location: fs/ext4/ext4_jbd2.h:353
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
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
In fs/ext4/extents.c (ffffffff813f17ce)
Location: fs/ext4/ext4_jbd2.h:345
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_datasem_ensure_credits
```
```
In fs/ext4/indirect.c (ffffffff81402118)
Location: fs/ext4/ext4_jbd2.h:345
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
```
```
In fs/ext4/migrate.c (ffffffff81420a76)
Location: fs/ext4/ext4_jbd2.h:345
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:free_tind_blocks
  - fs/ext4/migrate.c:free_tind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
```
```
In fs/ext4/resize.c (ffffffff8142d898)
Location: fs/ext4/ext4_jbd2.h:345
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:set_flexbg_block_bitmap
```
```
In fs/ext4/xattr.c (ffffffff814537ec)
Location: fs/ext4/ext4_jbd2.h:345
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
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
In fs/ext4/extents.c (ffffffff813f7c4e)
Location: fs/ext4/ext4_jbd2.h:345
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_datasem_ensure_credits
```
```
In fs/ext4/indirect.c (ffffffff81408522)
Location: fs/ext4/ext4_jbd2.h:345
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
```
```
In fs/ext4/migrate.c (ffffffff81427231)
Location: fs/ext4/ext4_jbd2.h:345
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
```
```
In fs/ext4/resize.c (ffffffff81434558)
Location: fs/ext4/ext4_jbd2.h:345
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:set_flexbg_block_bitmap
```
```
In fs/ext4/xattr.c (ffffffff8145910c)
Location: fs/ext4/ext4_jbd2.h:345
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
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
In fs/ext4/extents.c (ffffffff8144a12e)
Location: fs/ext4/ext4_jbd2.h:351
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_datasem_ensure_credits
```
```
In fs/ext4/indirect.c (ffffffff8145af6a)
Location: fs/ext4/ext4_jbd2.h:351
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
```
```
In fs/ext4/migrate.c (ffffffff8147aec8)
Location: fs/ext4/ext4_jbd2.h:351
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
```
```
In fs/ext4/resize.c (ffffffff81487fd4)
Location: fs/ext4/ext4_jbd2.h:351
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:set_flexbg_block_bitmap
```
```
In fs/ext4/xattr.c (ffffffff814ad21c)
Location: fs/ext4/ext4_jbd2.h:351
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
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
In fs/ext4/extents.c (ffffffff814c687e)
Location: fs/ext4/ext4_jbd2.h:351
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_datasem_ensure_credits
```
```
In fs/ext4/indirect.c (ffffffff814d8ce8)
Location: fs/ext4/ext4_jbd2.h:351
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
```
```
In fs/ext4/migrate.c (ffffffff814fd2f6)
Location: fs/ext4/ext4_jbd2.h:351
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
```
```
In fs/ext4/resize.c (ffffffff8150d5a5)
Location: fs/ext4/ext4_jbd2.h:351
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
```
```
In fs/ext4/xattr.c (ffffffff815352b7)
Location: fs/ext4/ext4_jbd2.h:351
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
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
In fs/ext4/extents.c (ffffffff8155ee6e)
Location: fs/ext4/ext4_jbd2.h:351
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_datasem_ensure_credits
```
```
In fs/ext4/indirect.c (ffffffff81571af8)
Location: fs/ext4/ext4_jbd2.h:351
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
```
```
In fs/ext4/migrate.c (ffffffff81597ac2)
Location: fs/ext4/ext4_jbd2.h:351
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
```
```
In fs/ext4/resize.c (ffffffff815a83b1)
Location: fs/ext4/ext4_jbd2.h:351
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
```
```
In fs/ext4/xattr.c (ffffffff815d36f7)
Location: fs/ext4/ext4_jbd2.h:351
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
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
In fs/ext4/extents.c (ffffffff81596c2e)
Location: fs/ext4/ext4_jbd2.h:351
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_datasem_ensure_credits
```
```
In fs/ext4/indirect.c (ffffffff815a9888)
Location: fs/ext4/ext4_jbd2.h:351
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
```
```
In fs/ext4/inode.c (ffffffff815b5cea)
Location: fs/ext4/ext4_jbd2.h:351
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
```
In fs/ext4/migrate.c (ffffffff815ce502)
Location: fs/ext4/ext4_jbd2.h:351
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
```
```
In fs/ext4/resize.c (ffffffff815dec31)
Location: fs/ext4/ext4_jbd2.h:351
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
```
```
In fs/ext4/xattr.c (ffffffff8160b2a7)
Location: fs/ext4/ext4_jbd2.h:351
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
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
In fs/ext4/extents.c (ffffffff815cf8dc)
Location: fs/ext4/ext4_jbd2.h:351
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_datasem_ensure_credits
```
```
In fs/ext4/indirect.c (ffffffff815e2636)
Location: fs/ext4/ext4_jbd2.h:351
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
```
```
In fs/ext4/inode.c (ffffffff815eea95)
Location: fs/ext4/ext4_jbd2.h:351
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
```
In fs/ext4/migrate.c (ffffffff81606d82)
Location: fs/ext4/ext4_jbd2.h:351
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
```
```
In fs/ext4/resize.c (ffffffff816176ed)
Location: fs/ext4/ext4_jbd2.h:351
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
```
```
In fs/ext4/xattr.c (ffffffff81644067)
Location: fs/ext4/ext4_jbd2.h:351
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
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
In fs/ext4/inode.c (ffff800010480bf8)
Location: fs/ext4/ext4_jbd2.h:342
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate_restart_trans
```
```
In fs/ext4/migrate.c (ffff800010498a38)
Location: fs/ext4/ext4_jbd2.h:342
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:finish_range
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/resize.c (ffff8000104a6e34)
Location: fs/ext4/ext4_jbd2.h:342
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/xattr.c (ffff8000104c253c)
Location: fs/ext4/ext4_jbd2.h:342
Inline: True
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
In fs/ext4/inode.c (c0641cdc)
Location: fs/ext4/ext4_jbd2.h:342
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate_restart_trans
```
```
In fs/ext4/migrate.c (c065a5f8)
Location: fs/ext4/ext4_jbd2.h:342
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:finish_range
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/resize.c (c0668be8)
Location: fs/ext4/ext4_jbd2.h:342
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/xattr.c (c068648c)
Location: fs/ext4/ext4_jbd2.h:342
Inline: True
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
In fs/ext4/inode.c (c0000000005a4f70)
Location: fs/ext4/ext4_jbd2.h:342
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate_restart_trans
```
```
In fs/ext4/migrate.c (c0000000005c2d00)
Location: fs/ext4/ext4_jbd2.h:342
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:finish_range
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/resize.c (c0000000005d34f8)
Location: fs/ext4/ext4_jbd2.h:342
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/xattr.c (c0000000005f9488)
Location: fs/ext4/ext4_jbd2.h:342
Inline: True
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
In fs/ext4/inode.c (ffffffe0003099bc)
Location: fs/ext4/ext4_jbd2.h:342
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate_restart_trans
```
```
In fs/ext4/migrate.c (ffffffe00031c914)
Location: fs/ext4/ext4_jbd2.h:342
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:finish_range
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/resize.c (ffffffe000326e04)
Location: fs/ext4/ext4_jbd2.h:342
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/xattr.c (ffffffe00033d9e8)
Location: fs/ext4/ext4_jbd2.h:342
Inline: True
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
In fs/ext4/inode.c (ffffffff813a4abf)
Location: fs/ext4/ext4_jbd2.h:342
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate_restart_trans
```
```
In fs/ext4/migrate.c (ffffffff813b9b00)
Location: fs/ext4/ext4_jbd2.h:342
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:finish_range
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/resize.c (ffffffff813c5ddc)
Location: fs/ext4/ext4_jbd2.h:342
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/xattr.c (ffffffff813e1bb1)
Location: fs/ext4/ext4_jbd2.h:342
Inline: True
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
In fs/ext4/inode.c (ffffffff8139554f)
Location: fs/ext4/ext4_jbd2.h:342
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate_restart_trans
```
```
In fs/ext4/migrate.c (ffffffff813aa590)
Location: fs/ext4/ext4_jbd2.h:342
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:finish_range
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/resize.c (ffffffff813b685c)
Location: fs/ext4/ext4_jbd2.h:342
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/xattr.c (ffffffff813d2631)
Location: fs/ext4/ext4_jbd2.h:342
Inline: True
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
In fs/ext4/inode.c (ffffffff813a231f)
Location: fs/ext4/ext4_jbd2.h:342
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate_restart_trans
```
```
In fs/ext4/migrate.c (ffffffff813b7360)
Location: fs/ext4/ext4_jbd2.h:342
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:finish_range
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/resize.c (ffffffff813c326c)
Location: fs/ext4/ext4_jbd2.h:342
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/xattr.c (ffffffff813def31)
Location: fs/ext4/ext4_jbd2.h:342
Inline: True
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
In fs/ext4/inode.c (ffffffff813b69ef)
Location: fs/ext4/ext4_jbd2.h:342
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate_restart_trans
```
```
In fs/ext4/migrate.c (ffffffff813cc06e)
Location: fs/ext4/ext4_jbd2.h:342
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:finish_range
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/resize.c (ffffffff813d8417)
Location: fs/ext4/ext4_jbd2.h:342
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/xattr.c (ffffffff813f4351)
Location: fs/ext4/ext4_jbd2.h:342
Inline: True
```
</details>
</li>
</ul>

## Differences
