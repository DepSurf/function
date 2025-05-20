# Function: <code>ext4_get_groups_count</code>

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
In fs/ext4/balloc.c (ffffffff8128ed95)
Location: fs/ext4/ext4.h:2789
Inline: True
Inline callers:
  - fs/ext4/balloc.c:num_clusters_in_group
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/balloc.c:ext4_count_free_clusters
```
```
In fs/ext4/ialloc.c (ffffffff8129306e)
Location: fs/ext4/ext4.h:2789
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:ext4_count_dirs
```
```
In fs/ext4/inode.c (ffffffff81295f37)
Location: fs/ext4/ext4.h:2789
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_meta_trans_blocks
```
```
In fs/ext4/super.c (ffffffff812bb6bb)
Location: fs/ext4/ext4.h:2789
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
```
```
In fs/ext4/mballoc.c (ffffffff812ccfc8)
Location: fs/ext4/ext4.h:2789
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_start
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_next
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/block_validity.c (ffffffff812d62b9)
Location: fs/ext4/ext4.h:2789
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
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
In fs/ext4/balloc.c (ffffffff812bcc02)
Location: fs/ext4/ext4.h:2824
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/balloc.c:num_clusters_in_group
```
```
In fs/ext4/ialloc.c (ffffffff812c2f20)
Location: fs/ext4/ext4.h:2824
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/inode.c (ffffffff812c34fe)
Location: fs/ext4/ext4.h:2824
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_meta_trans_blocks
```
```
In fs/ext4/super.c (ffffffff812ea6a7)
Location: fs/ext4/ext4.h:2824
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
```
```
In fs/ext4/mballoc.c (ffffffff81303e04)
Location: fs/ext4/ext4.h:2824
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_next
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_start
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/block_validity.c (ffffffff81305f59)
Location: fs/ext4/ext4.h:2824
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
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
In fs/ext4/balloc.c (ffffffff812d2252)
Location: fs/ext4/ext4.h:2802
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/balloc.c:num_clusters_in_group
```
```
In fs/ext4/ialloc.c (ffffffff812d8510)
Location: fs/ext4/ext4.h:2802
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/inode.c (ffffffff812d8b8e)
Location: fs/ext4/ext4.h:2802
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_meta_trans_blocks
```
```
In fs/ext4/super.c (ffffffff8130044e)
Location: fs/ext4/ext4.h:2802
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
```
```
In fs/ext4/mballoc.c (ffffffff81319dc4)
Location: fs/ext4/ext4.h:2802
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_next
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_start
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/block_validity.c (ffffffff8131bf19)
Location: fs/ext4/ext4.h:2802
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
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
In fs/ext4/balloc.c (ffffffff812e38d2)
Location: fs/ext4/ext4.h:2820
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/balloc.c:num_clusters_in_group
```
```
In fs/ext4/block_validity.c (ffffffff812e4ad9)
Location: fs/ext4/ext4.h:2820
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/ialloc.c (ffffffff812f6930)
Location: fs/ext4/ext4.h:2820
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/inode.c (ffffffff812fce2e)
Location: fs/ext4/ext4.h:2820
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_meta_trans_blocks
```
```
In fs/ext4/mballoc.c (ffffffff813111d0)
Location: fs/ext4/ext4.h:2820
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_next
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_start
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (ffffffff81335296)
Location: fs/ext4/ext4.h:2820
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
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
In fs/ext4/balloc.c (ffffffff813082c2)
Location: fs/ext4/ext4.h:2777
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/balloc.c:num_clusters_in_group
```
```
In fs/ext4/block_validity.c (ffffffff81309509)
Location: fs/ext4/ext4.h:2777
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/ialloc.c (ffffffff8131af60)
Location: fs/ext4/ext4.h:2777
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/inode.c (ffffffff8132172e)
Location: fs/ext4/ext4.h:2777
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_meta_trans_blocks
```
```
In fs/ext4/mballoc.c (ffffffff81335d8e)
Location: fs/ext4/ext4.h:2777
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_next
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_start
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (ffffffff813597a6)
Location: fs/ext4/ext4.h:2777
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
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
In fs/ext4/balloc.c (ffffffff813361b5)
Location: fs/ext4/ext4.h:2782
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/balloc.c:num_clusters_in_group
```
```
In fs/ext4/block_validity.c (ffffffff81337435)
Location: fs/ext4/ext4.h:2782
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/ialloc.c (ffffffff81348e75)
Location: fs/ext4/ext4.h:2782
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/inode.c (ffffffff8134f785)
Location: fs/ext4/ext4.h:2782
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_meta_trans_blocks
```
```
In fs/ext4/mballoc.c (ffffffff8136407c)
Location: fs/ext4/ext4.h:2782
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_next
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_start
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (ffffffff81388128)
Location: fs/ext4/ext4.h:2782
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
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
In fs/ext4/balloc.c (ffffffff8134d435)
Location: fs/ext4/ext4.h:2809
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/balloc.c:num_clusters_in_group
```
```
In fs/ext4/block_validity.c (ffffffff8134e6b5)
Location: fs/ext4/ext4.h:2809
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/ialloc.c (ffffffff81361035)
Location: fs/ext4/ext4.h:2809
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/inode.c (ffffffff81367965)
Location: fs/ext4/ext4.h:2809
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_meta_trans_blocks
```
```
In fs/ext4/mballoc.c (ffffffff8137c31e)
Location: fs/ext4/ext4.h:2809
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_next
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_start
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (ffffffff813a0cf8)
Location: fs/ext4/ext4.h:2809
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
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
In fs/ext4/balloc.c (ffffffff81375e35)
Location: fs/ext4/ext4.h:2889
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/balloc.c:num_clusters_in_group
```
```
In fs/ext4/block_validity.c (ffffffff813770e8)
Location: fs/ext4/ext4.h:2889
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/ialloc.c (ffffffff8138a0d5)
Location: fs/ext4/ext4.h:2889
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/inode.c (ffffffff81390c65)
Location: fs/ext4/ext4.h:2889
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_meta_trans_blocks
```
```
In fs/ext4/mballoc.c (ffffffff813a638f)
Location: fs/ext4/ext4.h:2889
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_next
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_start
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (ffffffff813cb5a8)
Location: fs/ext4/ext4.h:2889
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
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
In fs/ext4/balloc.c (ffffffff8138e0a5)
Location: fs/ext4/ext4.h:2951
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/balloc.c:num_clusters_in_group
```
```
In fs/ext4/block_validity.c (ffffffff8138f365)
Location: fs/ext4/ext4.h:2951
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/ialloc.c (ffffffff813a2af5)
Location: fs/ext4/ext4.h:2951
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/inode.c (ffffffff813a9625)
Location: fs/ext4/ext4.h:2951
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_meta_trans_blocks
```
```
In fs/ext4/mballoc.c (ffffffff813bf1ff)
Location: fs/ext4/ext4.h:2951
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_next
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_start
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (ffffffff813e4968)
Location: fs/ext4/ext4.h:2951
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
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
In fs/ext4/balloc.c (ffffffff813d95c5)
Location: fs/ext4/ext4.h:3062
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
```
```
In fs/ext4/block_validity.c (ffffffff813da869)
Location: fs/ext4/ext4.h:3062
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/ialloc.c (ffffffff813eec25)
Location: fs/ext4/ext4.h:3062
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/inode.c (ffffffff813f5a85)
Location: fs/ext4/ext4.h:3062
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_meta_trans_blocks
```
```
In fs/ext4/mballoc.c (ffffffff81407a95)
Location: fs/ext4/ext4.h:3062
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_next
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_start
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (ffffffff81431da5)
Location: fs/ext4/ext4.h:3062
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:count_overhead
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
In fs/ext4/balloc.c (ffffffff813eb255)
Location: fs/ext4/ext4.h:3236
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
```
```
In fs/ext4/block_validity.c (ffffffff813ec539)
Location: fs/ext4/ext4.h:3236
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/ialloc.c (ffffffff81401395)
Location: fs/ext4/ext4.h:3236
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/inode.c (ffffffff814084d5)
Location: fs/ext4/ext4.h:3236
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_meta_trans_blocks
```
```
In fs/ext4/mballoc.c (ffffffff8141a015)
Location: fs/ext4/ext4.h:3236
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_next
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_start
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_prefetch_fini
  - fs/ext4/mballoc.c:ext4_mb_prefetch
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (ffffffff8144abb5)
Location: fs/ext4/ext4.h:3236
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:count_overhead
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
In fs/ext4/balloc.c (ffffffff813f1785)
Location: fs/ext4/ext4.h:3298
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
```
```
In fs/ext4/block_validity.c (ffffffff813f2a79)
Location: fs/ext4/ext4.h:3298
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/ialloc.c (ffffffff814078d5)
Location: fs/ext4/ext4.h:3298
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/inode.c (ffffffff8140ec65)
Location: fs/ext4/ext4.h:3298
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_meta_trans_blocks
```
```
In fs/ext4/mballoc.c (ffffffff81425030)
Location: fs/ext4/ext4.h:3298
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_next
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_start
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_prefetch_fini
  - fs/ext4/mballoc.c:ext4_mb_prefetch
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (ffffffff81450555)
Location: fs/ext4/ext4.h:3298
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:count_overhead
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
In fs/ext4/balloc.c (ffffffff814437d5)
Location: fs/ext4/ext4.h:3368
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
```
```
In fs/ext4/block_validity.c (ffffffff81444a59)
Location: fs/ext4/ext4.h:3368
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/ialloc.c (ffffffff8145a175)
Location: fs/ext4/ext4.h:3368
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/inode.c (ffffffff81461f35)
Location: fs/ext4/ext4.h:3368
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_meta_trans_blocks
```
```
In fs/ext4/mballoc.c (ffffffff814738e3)
Location: fs/ext4/ext4.h:3368
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_discard_preallocations_should_retry
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_next
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_start
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_prefetch_fini
  - fs/ext4/mballoc.c:ext4_mb_prefetch
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (ffffffff814a3835)
Location: fs/ext4/ext4.h:3368
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:count_overhead
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
In fs/ext4/balloc.c (ffffffff814bf655)
Location: fs/ext4/ext4.h:3331
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
```
```
In fs/ext4/block_validity.c (ffffffff814c09f9)
Location: fs/ext4/ext4.h:3331
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/ialloc.c (ffffffff814d7e45)
Location: fs/ext4/ext4.h:3331
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/inode.c (ffffffff814e0685)
Location: fs/ext4/ext4.h:3331
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_meta_trans_blocks
```
```
In fs/ext4/ioctl.c (ffffffff814ed917)
Location: fs/ext4/ext4.h:3331
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_update_superblocks_fn
```
```
In fs/ext4/mballoc.c (ffffffff814f5073)
Location: fs/ext4/ext4.h:3331
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_discard_preallocations_should_retry
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_next
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_start
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_prefetch_fini
  - fs/ext4/mballoc.c:ext4_mb_prefetch
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (ffffffff8152acd7)
Location: fs/ext4/ext4.h:3331
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:count_overhead
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
In fs/ext4/balloc.c (ffffffff815575d5)
Location: fs/ext4/ext4.h:3344
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
```
```
In fs/ext4/block_validity.c (ffffffff81558ad9)
Location: fs/ext4/ext4.h:3344
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/ialloc.c (ffffffff81570bb5)
Location: fs/ext4/ext4.h:3344
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/inode.c (ffffffff81579b45)
Location: fs/ext4/ext4.h:3344
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_meta_trans_blocks
```
```
In fs/ext4/ioctl.c (ffffffff8158776d)
Location: fs/ext4/ext4.h:3344
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_update_superblocks_fn
```
```
In fs/ext4/mballoc.c (ffffffff8158f334)
Location: fs/ext4/ext4.h:3344
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_discard_preallocations_should_retry
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_next
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_start
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_prefetch_fini
  - fs/ext4/mballoc.c:ext4_mb_prefetch
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (ffffffff815c9b55)
Location: fs/ext4/ext4.h:3344
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:count_overhead
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
In fs/ext4/balloc.c (ffffffff8158f455)
Location: fs/ext4/ext4.h:3323
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
```
```
In fs/ext4/block_validity.c (ffffffff81590929)
Location: fs/ext4/ext4.h:3323
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/ialloc.c (ffffffff815a8985)
Location: fs/ext4/ext4.h:3323
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/inode.c (ffffffff815b10e5)
Location: fs/ext4/ext4.h:3323
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_meta_trans_blocks
```
```
In fs/ext4/ioctl.c (ffffffff815bde2d)
Location: fs/ext4/ext4.h:3323
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_update_superblocks_fn
```
```
In fs/ext4/mballoc.c (ffffffff815cbcc3)
Location: fs/ext4/ext4.h:3323
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks_simple
  - fs/ext4/mballoc.c:ext4_mb_new_blocks_simple
  - fs/ext4/mballoc.c:ext4_mb_discard_preallocations_should_retry
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_next
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_start
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_prefetch_fini
  - fs/ext4/mballoc.c:ext4_mb_prefetch
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (ffffffff81601a15)
Location: fs/ext4/ext4.h:3323
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:count_overhead
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
In fs/ext4/balloc.c (ffffffff815c8165)
Location: fs/ext4/ext4.h:3343
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
```
```
In fs/ext4/block_validity.c (ffffffff815c9669)
Location: fs/ext4/ext4.h:3343
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/ialloc.c (ffffffff815e1735)
Location: fs/ext4/ext4.h:3343
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/inode.c (ffffffff815e9795)
Location: fs/ext4/ext4.h:3343
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_meta_trans_blocks
```
```
In fs/ext4/ioctl.c (ffffffff815f6bed)
Location: fs/ext4/ext4.h:3343
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_update_superblocks_fn
```
```
In fs/ext4/mballoc.c (ffffffff815ff349)
Location: fs/ext4/ext4.h:3343
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_mb_new_blocks_simple
  - fs/ext4/mballoc.c:ext4_mb_new_blocks_simple
  - fs/ext4/mballoc.c:ext4_mb_discard_preallocations_should_retry
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_next
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_start
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_prefetch_fini
  - fs/ext4/mballoc.c:ext4_mb_prefetch
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (ffffffff8163a7b5)
Location: fs/ext4/ext4.h:3343
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:count_overhead
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
In fs/ext4/balloc.c (ffff800010460214)
Location: fs/ext4/ext4.h:2951
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/balloc.c:num_clusters_in_group
```
```
In fs/ext4/block_validity.c (ffff800010461c10)
Location: fs/ext4/ext4.h:2951
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/ialloc.c (ffff800010476274)
Location: fs/ext4/ext4.h:2951
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/inode.c (ffff80001047d4d4)
Location: fs/ext4/ext4.h:2951
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_meta_trans_blocks
```
```
In fs/ext4/mballoc.c (ffff800010495f30)
Location: fs/ext4/ext4.h:2951
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_next
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_start
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (ffff8000104bded8)
Location: fs/ext4/ext4.h:2951
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
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
In fs/ext4/balloc.c (c0620a48)
Location: fs/ext4/ext4.h:2951
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/balloc.c:num_clusters_in_group
```
```
In fs/ext4/block_validity.c (c06220f8)
Location: fs/ext4/ext4.h:2951
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/ialloc.c (c0637c68)
Location: fs/ext4/ext4.h:2951
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/inode.c (c063ede4)
Location: fs/ext4/ext4.h:2951
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_meta_trans_blocks
```
```
In fs/ext4/mballoc.c (c0657b68)
Location: fs/ext4/ext4.h:2951
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_next
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_start
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (c06816a0)
Location: fs/ext4/ext4.h:2951
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
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
In fs/ext4/balloc.c (c00000000057c63c)
Location: fs/ext4/ext4.h:2951
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/balloc.c:num_clusters_in_group
```
```
In fs/ext4/block_validity.c (c00000000057e3ac)
Location: fs/ext4/ext4.h:2951
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/ialloc.c (c0000000005981dc)
Location: fs/ext4/ext4.h:2951
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/inode.c (c0000000005a1148)
Location: fs/ext4/ext4.h:2951
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_meta_trans_blocks
```
```
In fs/ext4/mballoc.c (c0000000005bfd14)
Location: fs/ext4/ext4.h:2951
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_next
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_start
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (c0000000005f41c8)
Location: fs/ext4/ext4.h:2951
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
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
In fs/ext4/balloc.c (ffffffe0002ef87a)
Location: fs/ext4/ext4.h:2951
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/balloc.c:num_clusters_in_group
```
```
In fs/ext4/block_validity.c (ffffffe0002f0b52)
Location: fs/ext4/ext4.h:2951
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/ialloc.c (ffffffe000301bba)
Location: fs/ext4/ext4.h:2951
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/inode.c (ffffffe000306f6c)
Location: fs/ext4/ext4.h:2951
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_meta_trans_blocks
```
```
In fs/ext4/mballoc.c (ffffffe00031aa86)
Location: fs/ext4/ext4.h:2951
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_next
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_start
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (ffffffe0003399a2)
Location: fs/ext4/ext4.h:2951
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
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
In fs/ext4/balloc.c (ffffffff81386685)
Location: fs/ext4/ext4.h:2951
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/balloc.c:num_clusters_in_group
```
```
In fs/ext4/block_validity.c (ffffffff81387945)
Location: fs/ext4/ext4.h:2951
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/ialloc.c (ffffffff8139b0d5)
Location: fs/ext4/ext4.h:2951
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/inode.c (ffffffff813a1c05)
Location: fs/ext4/ext4.h:2951
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_meta_trans_blocks
```
```
In fs/ext4/mballoc.c (ffffffff813b77df)
Location: fs/ext4/ext4.h:2951
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_next
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_start
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (ffffffff813dcf48)
Location: fs/ext4/ext4.h:2951
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
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
In fs/ext4/balloc.c (ffffffff81377115)
Location: fs/ext4/ext4.h:2951
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/balloc.c:num_clusters_in_group
```
```
In fs/ext4/block_validity.c (ffffffff813783d5)
Location: fs/ext4/ext4.h:2951
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/ialloc.c (ffffffff8138bb65)
Location: fs/ext4/ext4.h:2951
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/inode.c (ffffffff81392695)
Location: fs/ext4/ext4.h:2951
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_meta_trans_blocks
```
```
In fs/ext4/mballoc.c (ffffffff813a826f)
Location: fs/ext4/ext4.h:2951
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_next
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_start
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (ffffffff813cd9c8)
Location: fs/ext4/ext4.h:2951
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
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
In fs/ext4/balloc.c (ffffffff81384155)
Location: fs/ext4/ext4.h:2951
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/balloc.c:num_clusters_in_group
```
```
In fs/ext4/block_validity.c (ffffffff81385415)
Location: fs/ext4/ext4.h:2951
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/ialloc.c (ffffffff81398935)
Location: fs/ext4/ext4.h:2951
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/inode.c (ffffffff8139f465)
Location: fs/ext4/ext4.h:2951
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_meta_trans_blocks
```
```
In fs/ext4/mballoc.c (ffffffff813b503f)
Location: fs/ext4/ext4.h:2951
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_next
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_start
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (ffffffff813da3e8)
Location: fs/ext4/ext4.h:2951
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
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
In fs/ext4/balloc.c (ffffffff81397cb5)
Location: fs/ext4/ext4.h:2951
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/balloc.c:num_clusters_in_group
```
```
In fs/ext4/block_validity.c (ffffffff81398f95)
Location: fs/ext4/ext4.h:2951
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/ialloc.c (ffffffff813acd45)
Location: fs/ext4/ext4.h:2951
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/inode.c (ffffffff813b3b05)
Location: fs/ext4/ext4.h:2951
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_meta_trans_blocks
```
```
In fs/ext4/mballoc.c (ffffffff813c9c8e)
Location: fs/ext4/ext4.h:2951
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_next
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_start
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (ffffffff813ef6c8)
Location: fs/ext4/ext4.h:2951
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
```
</details>
</li>
</ul>

## Differences
