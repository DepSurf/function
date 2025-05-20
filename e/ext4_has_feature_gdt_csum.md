# Function: <code>ext4_has_feature_gdt_csum</code>

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
In fs/ext4/ialloc.c (ffffffff81294dc9)
Location: fs/ext4/ext4.h:1697
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff812965e9)
Location: fs/ext4/ext4.h:1697
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/ioctl.c (ffffffff812a14b5)
Location: fs/ext4/ext4.h:1697
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff812adb2b)
Location: fs/ext4/ext4.h:1697
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum_set
```
```
In fs/ext4/resize.c (ffffffff812c0815)
Location: fs/ext4/ext4.h:1697
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
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
In fs/ext4/ialloc.c (ffffffff812c237b)
Location: fs/ext4/ext4.h:1765
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff812c3be3)
Location: fs/ext4/ext4.h:1765
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/ioctl.c (ffffffff812d008e)
Location: fs/ext4/ext4.h:1765
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff812e9c1c)
Location: fs/ext4/ext4.h:1765
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum
```
```
In fs/ext4/resize.c (ffffffff812f16c6)
Location: fs/ext4/ext4.h:1765
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_flex_group_add
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
In fs/ext4/ialloc.c (ffffffff812d79c6)
Location: fs/ext4/ext4.h:1750
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff812d9293)
Location: fs/ext4/ext4.h:1750
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/ioctl.c (ffffffff812e5e54)
Location: fs/ext4/ext4.h:1750
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff812ff98c)
Location: fs/ext4/ext4.h:1750
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum
```
```
In fs/ext4/resize.c (ffffffff81307696)
Location: fs/ext4/ext4.h:1750
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_flex_group_add
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
In fs/ext4/ialloc.c (ffffffff812f5d72)
Location: fs/ext4/ext4.h:1755
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff812ff936)
Location: fs/ext4/ext4.h:1755
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/ioctl.c (ffffffff813098a1)
Location: fs/ext4/ext4.h:1755
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/resize.c (ffffffff81322197)
Location: fs/ext4/ext4.h:1755
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff8133477c)
Location: fs/ext4/ext4.h:1755
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum_verify
  - fs/ext4/super.c:ext4_group_desc_csum
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
In fs/ext4/ialloc.c (ffffffff8131a40d)
Location: fs/ext4/ext4.h:1715
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff813240e9)
Location: fs/ext4/ext4.h:1715
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/ioctl.c (ffffffff8132d7a1)
Location: fs/ext4/ext4.h:1715
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
```
```
In fs/ext4/resize.c (ffffffff813468ec)
Location: fs/ext4/ext4.h:1715
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff81358c85)
Location: fs/ext4/ext4.h:1715
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum_verify
  - fs/ext4/super.c:ext4_group_desc_csum
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
In fs/ext4/balloc.c (ffffffff81336902)
Location: fs/ext4/ext4.h:1718
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff8134895b)
Location: fs/ext4/ext4.h:1718
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff81350adb)
Location: fs/ext4/ext4.h:1718
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/ioctl.c (ffffffff8135c1d7)
Location: fs/ext4/ext4.h:1718
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
```
```
In fs/ext4/mballoc.c (ffffffff813626a6)
Location: fs/ext4/ext4.h:1718
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
```
In fs/ext4/resize.c (ffffffff813746f2)
Location: fs/ext4/ext4.h:1718
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff81387f60)
Location: fs/ext4/ext4.h:1718
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum_verify
  - fs/ext4/super.c:ext4_group_desc_csum
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
In fs/ext4/balloc.c (ffffffff8134db82)
Location: fs/ext4/ext4.h:1731
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff81360b0b)
Location: fs/ext4/ext4.h:1731
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff81369f6b)
Location: fs/ext4/ext4.h:1731
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/ioctl.c (ffffffff813745a6)
Location: fs/ext4/ext4.h:1731
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
```
```
In fs/ext4/mballoc.c (ffffffff8137a8b6)
Location: fs/ext4/ext4.h:1731
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
```
In fs/ext4/resize.c (ffffffff8138cc7c)
Location: fs/ext4/ext4.h:1731
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813a0b20)
Location: fs/ext4/ext4.h:1731
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum_verify
  - fs/ext4/super.c:ext4_group_desc_csum
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
In fs/ext4/balloc.c (ffffffff81376555)
Location: fs/ext4/ext4.h:1751
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff81389bd7)
Location: fs/ext4/ext4.h:1751
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff813933b1)
Location: fs/ext4/ext4.h:1751
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/ioctl.c (ffffffff8139ddc7)
Location: fs/ext4/ext4.h:1751
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
```
```
In fs/ext4/mballoc.c (ffffffff813a49df)
Location: fs/ext4/ext4.h:1751
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
```
In fs/ext4/resize.c (ffffffff813b732a)
Location: fs/ext4/ext4.h:1751
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_setup_new_descs
```
```
In fs/ext4/super.c (ffffffff813cb36f)
Location: fs/ext4/ext4.h:1751
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum_verify
  - fs/ext4/super.c:ext4_group_desc_csum
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
In fs/ext4/balloc.c (ffffffff8138e7c5)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff813a2592)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff813abd58)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/ioctl.c (ffffffff813b6a72)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
```
```
In fs/ext4/mballoc.c (ffffffff813bd84f)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
```
In fs/ext4/resize.c (ffffffff813d02b2)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_setup_new_descs
```
```
In fs/ext4/super.c (ffffffff813e4711)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum_verify
  - fs/ext4/super.c:ext4_group_desc_csum
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
In fs/ext4/balloc.c (ffffffff813d9f8b)
Location: fs/ext4/ext4.h:1904
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff813eddf4)
Location: fs/ext4/ext4.h:1904
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff813f80bc)
Location: fs/ext4/ext4.h:1904
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/ioctl.c (ffffffff81402a18)
Location: fs/ext4/ext4.h:1904
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
```
```
In fs/ext4/mballoc.c (ffffffff81409807)
Location: fs/ext4/ext4.h:1904
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
```
```
In fs/ext4/resize.c (ffffffff8141a3c6)
Location: fs/ext4/ext4.h:1904
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_setup_next_flex_gd
  - fs/ext4/resize.c:ext4_setup_next_flex_gd
  - fs/ext4/resize.c:ext4_setup_new_descs
```
```
In fs/ext4/super.c (ffffffff81431b82)
Location: fs/ext4/ext4.h:1904
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum
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
In fs/ext4/balloc.c (ffffffff813ebc42)
Location: fs/ext4/ext4.h:2029
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff81400db7)
Location: fs/ext4/ext4.h:2029
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff81409d97)
Location: fs/ext4/ext4.h:2029
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/ioctl.c (ffffffff81415322)
Location: fs/ext4/ext4.h:2029
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
```
```
In fs/ext4/mballoc.c (ffffffff8141d8dc)
Location: fs/ext4/ext4.h:2029
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_prefetch_fini
  - fs/ext4/mballoc.c:ext4_mb_prefetch
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
```
```
In fs/ext4/resize.c (ffffffff8142e0e8)
Location: fs/ext4/ext4.h:2029
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_setup_next_flex_gd
  - fs/ext4/resize.c:ext4_setup_next_flex_gd
  - fs/ext4/resize.c:ext4_setup_new_descs
```
```
In fs/ext4/super.c (ffffffff8144a9a8)
Location: fs/ext4/ext4.h:2029
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum
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
In fs/ext4/balloc.c (ffffffff813f2182)
Location: fs/ext4/ext4.h:2038
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff814072c9)
Location: fs/ext4/ext4.h:2038
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff8140ff5e)
Location: fs/ext4/ext4.h:2038
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/ioctl.c (ffffffff8141b391)
Location: fs/ext4/ext4.h:2038
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
```
```
In fs/ext4/mballoc.c (ffffffff8142404d)
Location: fs/ext4/ext4.h:2038
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_prefetch_fini
  - fs/ext4/mballoc.c:ext4_mb_prefetch
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
```
```
In fs/ext4/resize.c (ffffffff81434da5)
Location: fs/ext4/ext4.h:2038
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_setup_next_flex_gd
  - fs/ext4/resize.c:ext4_setup_next_flex_gd
  - fs/ext4/resize.c:ext4_setup_new_descs
```
```
In fs/ext4/super.c (ffffffff81450351)
Location: fs/ext4/ext4.h:2038
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum
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
In fs/ext4/balloc.c (ffffffff81444162)
Location: fs/ext4/ext4.h:2104
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff81459b61)
Location: fs/ext4/ext4.h:2104
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff81463012)
Location: fs/ext4/ext4.h:2104
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/ioctl.c (ffffffff8146e54c)
Location: fs/ext4/ext4.h:2104
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
```
```
In fs/ext4/mballoc.c (ffffffff81477cc0)
Location: fs/ext4/ext4.h:2104
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_prefetch_fini
  - fs/ext4/mballoc.c:ext4_mb_prefetch
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
```
```
In fs/ext4/resize.c (ffffffff81488837)
Location: fs/ext4/ext4.h:2104
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_setup_next_flex_gd
  - fs/ext4/resize.c:ext4_setup_next_flex_gd
  - fs/ext4/resize.c:ext4_setup_new_descs
```
```
In fs/ext4/super.c (ffffffff814a6fdf)
Location: fs/ext4/ext4.h:2104
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum
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
In fs/ext4/balloc.c (ffffffff814c0055)
Location: fs/ext4/ext4.h:2106
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff814d7835)
Location: fs/ext4/ext4.h:2106
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff814e2b50)
Location: fs/ext4/ext4.h:2106
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/ioctl.c (ffffffff814ef05a)
Location: fs/ext4/ext4.h:2106
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
```
```
In fs/ext4/mballoc.c (ffffffff814fa1a5)
Location: fs/ext4/ext4.h:2106
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_prefetch_fini
  - fs/ext4/mballoc.c:ext4_mb_prefetch
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
```
```
In fs/ext4/resize.c (ffffffff8150b8b1)
Location: fs/ext4/ext4.h:2106
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_setup_next_flex_gd
  - fs/ext4/resize.c:ext4_setup_next_flex_gd
  - fs/ext4/resize.c:ext4_setup_new_descs
```
```
In fs/ext4/super.c (ffffffff8152b8fe)
Location: fs/ext4/ext4.h:2106
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum_verify
  - fs/ext4/super.c:ext4_group_desc_csum
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
In fs/ext4/balloc.c (ffffffff8155809d)
Location: fs/ext4/ext4.h:2116
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff815705a0)
Location: fs/ext4/ext4.h:2116
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff8157bfa3)
Location: fs/ext4/ext4.h:2116
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/ioctl.c (ffffffff81589307)
Location: fs/ext4/ext4.h:2116
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
```
```
In fs/ext4/mballoc.c (ffffffff815949d5)
Location: fs/ext4/ext4.h:2116
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_prefetch_fini
  - fs/ext4/mballoc.c:ext4_mb_prefetch
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
```
```
In fs/ext4/resize.c (ffffffff815a6561)
Location: fs/ext4/ext4.h:2116
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_setup_next_flex_gd
  - fs/ext4/resize.c:ext4_setup_next_flex_gd
  - fs/ext4/resize.c:ext4_setup_new_descs
```
```
In fs/ext4/super.c (ffffffff815ca92e)
Location: fs/ext4/ext4.h:2116
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum_verify
  - fs/ext4/super.c:ext4_group_desc_csum
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
In fs/ext4/balloc.c (ffffffff8158fde3)
Location: fs/ext4/ext4.h:2110
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff815a80d8)
Location: fs/ext4/ext4.h:2110
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff815b3396)
Location: fs/ext4/ext4.h:2110
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/ioctl.c (ffffffff815bfb65)
Location: fs/ext4/ext4.h:2110
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
```
```
In fs/ext4/mballoc.c (ffffffff815cb9b5)
Location: fs/ext4/ext4.h:2110
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
```
```
In fs/ext4/resize.c (ffffffff815dcdd1)
Location: fs/ext4/ext4.h:2110
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_setup_next_flex_gd
  - fs/ext4/resize.c:ext4_setup_next_flex_gd
  - fs/ext4/resize.c:ext4_setup_new_descs
```
```
In fs/ext4/super.c (ffffffff81602929)
Location: fs/ext4/ext4.h:2110
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum_verify
  - fs/ext4/super.c:ext4_group_desc_csum
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
In fs/ext4/balloc.c (ffffffff815c8972)
Location: fs/ext4/ext4.h:2128
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff815e0ea3)
Location: fs/ext4/ext4.h:2128
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff815ec1a6)
Location: fs/ext4/ext4.h:2128
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/ioctl.c (ffffffff815f88fe)
Location: fs/ext4/ext4.h:2128
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
```
```
In fs/ext4/mballoc.c (ffffffff816014e1)
Location: fs/ext4/ext4.h:2128
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_context
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
```
```
In fs/ext4/resize.c (ffffffff81615803)
Location: fs/ext4/ext4.h:2128
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_setup_next_flex_gd
  - fs/ext4/resize.c:ext4_setup_next_flex_gd
  - fs/ext4/resize.c:ext4_setup_new_descs
```
```
In fs/ext4/super.c (ffffffff8163b782)
Location: fs/ext4/ext4.h:2128
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum_verify
  - fs/ext4/super.c:ext4_group_desc_csum
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
In fs/ext4/balloc.c (ffff800010460b48)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffff800010475be8)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffff8000104805a0)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/ioctl.c (ffff80001048c23c)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
```
```
In fs/ext4/mballoc.c (ffff8000104944c8)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
```
In fs/ext4/resize.c (ffff8000104a8d4c)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_setup_new_descs
```
```
In fs/ext4/super.c (ffff8000104bdcd4)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum_verify
  - fs/ext4/super.c:ext4_group_desc_csum
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
In fs/ext4/balloc.c (c062120c)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (c06374cc)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (c0641a2c)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/ioctl.c (c064e26c)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/mballoc.c (c0655dbc)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
```
In fs/ext4/resize.c (c066b234)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_setup_new_descs
```
```
In fs/ext4/super.c (c0681434)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum_verify
  - fs/ext4/super.c:ext4_group_desc_csum
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
In fs/ext4/balloc.c (c00000000057d09c)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (c00000000059790c)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (c0000000005a4cbc)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/ioctl.c (c0000000005b357c)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
```
```
In fs/ext4/mballoc.c (c0000000005bd7c0)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
```
In fs/ext4/resize.c (c0000000005d69fc)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_setup_new_descs
```
```
In fs/ext4/super.c (c0000000005f3f44)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum_verify
  - fs/ext4/super.c:ext4_group_desc_csum
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
In fs/ext4/balloc.c (ffffffe0002efedc)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffe0003015c2)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffe0003092b2)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/ioctl.c (ffffffe000312658)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/mballoc.c (ffffffe0003190ac)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
```
In fs/ext4/resize.c (ffffffe0003290c0)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_setup_new_descs
```
```
In fs/ext4/super.c (ffffffe0003397fe)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum_verify
  - fs/ext4/super.c:ext4_group_desc_csum
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
In fs/ext4/balloc.c (ffffffff81386da5)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff8139ab72)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff813a4338)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/ioctl.c (ffffffff813af052)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
```
```
In fs/ext4/mballoc.c (ffffffff813b5e2f)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
```
In fs/ext4/resize.c (ffffffff813c8892)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_setup_new_descs
```
```
In fs/ext4/super.c (ffffffff813dccf1)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum_verify
  - fs/ext4/super.c:ext4_group_desc_csum
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
In fs/ext4/balloc.c (ffffffff81377835)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff8138b602)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff81394dc8)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/ioctl.c (ffffffff8139fae2)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
```
```
In fs/ext4/mballoc.c (ffffffff813a68bf)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
```
In fs/ext4/resize.c (ffffffff813b9312)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_setup_new_descs
```
```
In fs/ext4/super.c (ffffffff813cd771)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum_verify
  - fs/ext4/super.c:ext4_group_desc_csum
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
In fs/ext4/balloc.c (ffffffff81384875)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff813983d2)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff813a1b98)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/ioctl.c (ffffffff813ac8b2)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
```
```
In fs/ext4/mballoc.c (ffffffff813b368f)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
```
In fs/ext4/resize.c (ffffffff813c5d22)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_setup_new_descs
```
```
In fs/ext4/super.c (ffffffff813da191)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum_verify
  - fs/ext4/super.c:ext4_group_desc_csum
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
In fs/ext4/balloc.c (ffffffff813983f0)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff813ac7bb)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff813b67ea)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/ioctl.c (ffffffff813c1252)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
```
```
In fs/ext4/mballoc.c (ffffffff813c820f)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
```
In fs/ext4/resize.c (ffffffff813daf52)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_setup_new_descs
```
```
In fs/ext4/super.c (ffffffff813ef471)
Location: fs/ext4/ext4.h:1807
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum_verify
  - fs/ext4/super.c:ext4_group_desc_csum
```
</details>
</li>
</ul>

## Differences
