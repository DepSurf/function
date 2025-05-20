# Function: <code>ext4_chksum</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/bitmap.c (ffffffff81290455)
Location: fs/ext4/ext4.h:1957
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
```
```
In fs/ext4/ialloc.c (ffffffff81322631)
Location: fs/ext4/ext4.h:1957
Inline: True
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff81297b45)
Location: fs/ext4/ext4.h:1957
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
```
```
In fs/ext4/namei.c (ffffffff812a1b58)
Location: fs/ext4/ext4.h:1957
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirent_node
```
```
In fs/ext4/super.c (ffffffff812acf30)
Location: fs/ext4/ext4.h:1957
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
```
```
In fs/ext4/extents.c (ffffffff812c283f)
Location: fs/ext4/ext4.h:1957
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_extent_block_csum
```
```
In fs/ext4/mmp.c (ffffffff812d7a33)
Location: fs/ext4/ext4.h:1957
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/xattr.c (ffffffff812dcdbc)
Location: fs/ext4/ext4.h:1957
Inline: True
```
**Symbols:**

```
ffffffff81322631-ffffffff81322690: ext4_chksum.isra.13.constprop.17 (STB_LOCAL)
ffffffff812acf30-ffffffff812acf8c: ext4_chksum.isra.176 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/bitmap.c (ffffffff812bdce9)
Location: fs/ext4/ext4.h:2031
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/ialloc.c (ffffffff813579b6)
Location: fs/ext4/ext4.h:2031
Inline: True
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff812c7c57)
Location: fs/ext4/ext4.h:2031
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
```
```
In fs/ext4/namei.c (ffffffff812d0a82)
Location: fs/ext4/ext4.h:2031
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirent_node
```
```
In fs/ext4/super.c (ffffffff812eb230)
Location: fs/ext4/ext4.h:2031
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
```
```
In fs/ext4/extents.c (ffffffff812f21ff)
Location: fs/ext4/ext4.h:2031
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_extent_block_csum
```
```
In fs/ext4/mmp.c (ffffffff81307793)
Location: fs/ext4/ext4.h:2031
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/xattr.c (ffffffff8130c816)
Location: fs/ext4/ext4.h:2031
Inline: True
```
**Symbols:**

```
ffffffff813579b6-ffffffff81357a15: ext4_chksum.isra.14.constprop.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/bitmap.c (ffffffff812d3339)
Location: fs/ext4/ext4.h:2016
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/ialloc.c (ffffffff8136deb3)
Location: fs/ext4/ext4.h:2016
Inline: True
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff812dd7b7)
Location: fs/ext4/ext4.h:2016
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
```
```
In fs/ext4/namei.c (ffffffff812e6802)
Location: fs/ext4/ext4.h:2016
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirent_node
```
```
In fs/ext4/super.c (ffffffff813010f2)
Location: fs/ext4/ext4.h:2016
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
```
```
In fs/ext4/extents.c (ffffffff813081cf)
Location: fs/ext4/ext4.h:2016
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_extent_block_csum
```
```
In fs/ext4/mmp.c (ffffffff8131d783)
Location: fs/ext4/ext4.h:2016
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/xattr.c (ffffffff81322736)
Location: fs/ext4/ext4.h:2016
Inline: True
```
**Symbols:**

```
ffffffff8136deb3-ffffffff8136df12: ext4_chksum.isra.13.constprop.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/bitmap.c (ffffffff812e4831)
Location: fs/ext4/ext4.h:2036
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/extents.c (ffffffff812e69df)
Location: fs/ext4/ext4.h:2036
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_extent_block_csum
```
```
In fs/ext4/ialloc.c (ffffffff812f6d3b)
Location: fs/ext4/ext4.h:2036
Inline: True
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff81301899)
Location: fs/ext4/ext4.h:2036
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
```
```
In fs/ext4/mmp.c (ffffffff81314479)
Location: fs/ext4/ext4.h:2036
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff81316412)
Location: fs/ext4/ext4.h:2036
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirent_node
```
```
In fs/ext4/super.c (ffffffff81335fb4)
Location: fs/ext4/ext4.h:2036
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
```
```
In fs/ext4/xattr.c (ffffffff8133b7a3)
Location: fs/ext4/ext4.h:2036
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_get
```
**Symbols:**

```
ffffffff812f6d3b-ffffffff812f6d9a: ext4_chksum.isra.14.constprop.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/bitmap.c (ffffffff81309261)
Location: fs/ext4/ext4.h:1996
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/extents.c (ffffffff8130b5c6)
Location: fs/ext4/ext4.h:1996
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/ialloc.c (ffffffff8131b376)
Location: fs/ext4/ext4.h:1996
Inline: True
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff81326259)
Location: fs/ext4/ext4.h:1996
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
```
```
In fs/ext4/mmp.c (ffffffff81338c39)
Location: fs/ext4/ext4.h:1996
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff8133ac82)
Location: fs/ext4/ext4.h:1996
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirent_node
```
```
In fs/ext4/super.c (ffffffff8135a53a)
Location: fs/ext4/ext4.h:1996
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
```
```
In fs/ext4/xattr.c (ffffffff8135fbaf)
Location: fs/ext4/ext4.h:1996
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_get
```
**Symbols:**

```
ffffffff8131b376-ffffffff8131b3d5: ext4_chksum.isra.17.constprop.21 (STB_LOCAL)
ffffffff81350070-ffffffff813500cc: ext4_chksum.isra.182 (STB_LOCAL)
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
In fs/ext4/bitmap.c (ffffffff8133718d)
Location: fs/ext4/ext4.h:1999
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/extents.c (ffffffff813397d1)
Location: fs/ext4/ext4.h:1999
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/ialloc.c (ffffffff81348429)
Location: fs/ext4/ext4.h:1999
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff813545f4)
Location: fs/ext4/ext4.h:1999
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
```
```
In fs/ext4/mmp.c (ffffffff81367159)
Location: fs/ext4/ext4.h:1999
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff81369252)
Location: fs/ext4/ext4.h:1999
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirent_node
```
```
In fs/ext4/super.c (ffffffff81386975)
Location: fs/ext4/ext4.h:1999
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
```
```
In fs/ext4/xattr.c (ffffffff8138de02)
Location: fs/ext4/ext4.h:1999
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_get
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
In fs/ext4/bitmap.c (ffffffff8134e40d)
Location: fs/ext4/ext4.h:2012
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/extents.c (ffffffff81350971)
Location: fs/ext4/ext4.h:2012
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/ialloc.c (ffffffff813605d9)
Location: fs/ext4/ext4.h:2012
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff8136c91c)
Location: fs/ext4/ext4.h:2012
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff81373af1)
Location: fs/ext4/ext4.h:2012
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:reset_inode_seed
  - fs/ext4/ioctl.c:reset_inode_seed
  - fs/ext4/ioctl.c:reset_inode_seed
  - fs/ext4/ioctl.c:reset_inode_seed
```
```
In fs/ext4/mmp.c (ffffffff8137f5d9)
Location: fs/ext4/ext4.h:2012
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff813816f2)
Location: fs/ext4/ext4.h:2012
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirent_node
  - fs/ext4/namei.c:ext4_handle_dirty_dirent_node
```
```
In fs/ext4/super.c (ffffffff8139f475)
Location: fs/ext4/ext4.h:2012
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
  - fs/ext4/super.c:ext4_superblock_csum_set
```
```
In fs/ext4/xattr.c (ffffffff813a6382)
Location: fs/ext4/ext4.h:2012
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_inode_get
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
In fs/ext4/bitmap.c (ffffffff81376dcd)
Location: fs/ext4/ext4.h:2034
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/extents.c (ffffffff813795e6)
Location: fs/ext4/ext4.h:2034
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/ialloc.c (ffffffff81389759)
Location: fs/ext4/ext4.h:2034
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff81395ef1)
Location: fs/ext4/ext4.h:2034
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff8139d11d)
Location: fs/ext4/ext4.h:2034
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:reset_inode_seed
  - fs/ext4/ioctl.c:reset_inode_seed
  - fs/ext4/ioctl.c:reset_inode_seed
  - fs/ext4/ioctl.c:reset_inode_seed
```
```
In fs/ext4/mmp.c (ffffffff813a8a58)
Location: fs/ext4/ext4.h:2034
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff813aa991)
Location: fs/ext4/ext4.h:2034
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
```
```
In fs/ext4/super.c (ffffffff813c91c3)
Location: fs/ext4/ext4.h:2034
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
  - fs/ext4/super.c:ext4_superblock_csum_set
```
```
In fs/ext4/xattr.c (ffffffff813d0c1f)
Location: fs/ext4/ext4.h:2034
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_inode_get
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
In fs/ext4/bitmap.c (ffffffff8138f03d)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/extents.c (ffffffff8139185f)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_extent_block_csum
```
```
In fs/ext4/ialloc.c (ffffffff813a2089)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff813ae8e1)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff813b5b8d)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:reset_inode_seed
  - fs/ext4/ioctl.c:reset_inode_seed
  - fs/ext4/ioctl.c:reset_inode_seed
  - fs/ext4/ioctl.c:reset_inode_seed
```
```
In fs/ext4/mmp.c (ffffffff813c1968)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff813c38c1)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
```
```
In fs/ext4/super.c (ffffffff813e2571)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
  - fs/ext4/super.c:ext4_superblock_csum_set
```
```
In fs/ext4/xattr.c (ffffffff813ea2ef)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_inode_get
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
In fs/ext4/bitmap.c (ffffffff813da5cd)
Location: fs/ext4/ext4.h:2190
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/extents.c (ffffffff813dd616)
Location: fs/ext4/ext4.h:2190
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/ialloc.c (ffffffff813ee183)
Location: fs/ext4/ext4.h:2190
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff813fa937)
Location: fs/ext4/ext4.h:2190
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
```
```
In fs/ext4/ioctl.c (ffffffff8140156b)
Location: fs/ext4/ext4.h:2190
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:reset_inode_seed
  - fs/ext4/ioctl.c:reset_inode_seed
  - fs/ext4/ioctl.c:reset_inode_seed
  - fs/ext4/ioctl.c:reset_inode_seed
```
```
In fs/ext4/mmp.c (ffffffff8140db59)
Location: fs/ext4/ext4.h:2190
Inline: True
```
```
In fs/ext4/namei.c (ffffffff8140ff0f)
Location: fs/ext4/ext4.h:2190
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
```
```
In fs/ext4/super.c (ffffffff8142e62a)
Location: fs/ext4/ext4.h:2190
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
  - fs/ext4/super.c:ext4_superblock_csum_set
```
```
In fs/ext4/xattr.c (ffffffff814375c2)
Location: fs/ext4/ext4.h:2190
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
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
In fs/ext4/bitmap.c (ffffffff813ec2a1)
Location: fs/ext4/ext4.h:2315
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/extents.c (ffffffff813eef06)
Location: fs/ext4/ext4.h:2315
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/ialloc.c (ffffffff814007c7)
Location: fs/ext4/ext4.h:2315
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff8140cfaf)
Location: fs/ext4/ext4.h:2315
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
```
```
In fs/ext4/ioctl.c (ffffffff81413f5b)
Location: fs/ext4/ext4.h:2315
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_reset_inode_seed
  - fs/ext4/ioctl.c:ext4_reset_inode_seed
  - fs/ext4/ioctl.c:ext4_reset_inode_seed
  - fs/ext4/ioctl.c:ext4_reset_inode_seed
```
```
In fs/ext4/mmp.c (ffffffff81420fc9)
Location: fs/ext4/ext4.h:2315
Inline: True
```
```
In fs/ext4/namei.c (ffffffff814233df)
Location: fs/ext4/ext4.h:2315
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
```
```
In fs/ext4/super.c (ffffffff814449d4)
Location: fs/ext4/ext4.h:2315
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
```
```
In fs/ext4/xattr.c (ffffffff814500f2)
Location: fs/ext4/ext4.h:2315
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
```
```
In fs/ext4/fast_commit.c (ffffffff814549a4)
Location: fs/ext4/ext4.h:2315
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_reserve_space
  - fs/ext4/fast_commit.c:ext4_fc_reserve_space
  - fs/ext4/fast_commit.c:ext4_fc_reserve_space
  - fs/ext4/fast_commit.c:ext4_fc_reserve_space
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
In fs/ext4/bitmap.c (ffffffff813f27e4)
Location: fs/ext4/ext4.h:2366
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/extents.c (ffffffff813f53a4)
Location: fs/ext4/ext4.h:2366
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/ialloc.c (ffffffff81406c77)
Location: fs/ext4/ext4.h:2366
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff8141312b)
Location: fs/ext4/ext4.h:2366
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
```
```
In fs/ext4/ioctl.c (ffffffff8141a1cb)
Location: fs/ext4/ext4.h:2366
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_reset_inode_seed
  - fs/ext4/ioctl.c:ext4_reset_inode_seed
  - fs/ext4/ioctl.c:ext4_reset_inode_seed
  - fs/ext4/ioctl.c:ext4_reset_inode_seed
```
```
In fs/ext4/mmp.c (ffffffff81427779)
Location: fs/ext4/ext4.h:2366
Inline: True
```
```
In fs/ext4/namei.c (ffffffff81429be2)
Location: fs/ext4/ext4.h:2366
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:ext4_dirblock_csum_verify
  - fs/ext4/namei.c:ext4_dirblock_csum_verify
```
```
In fs/ext4/super.c (ffffffff8144a25e)
Location: fs/ext4/ext4.h:2366
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
```
```
In fs/ext4/xattr.c (ffffffff814558e7)
Location: fs/ext4/ext4.h:2366
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
```
```
In fs/ext4/fast_commit.c (ffffffff8145a0d8)
Location: fs/ext4/ext4.h:2366
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_reserve_space
  - fs/ext4/fast_commit.c:ext4_fc_reserve_space
  - fs/ext4/fast_commit.c:ext4_fc_reserve_space
  - fs/ext4/fast_commit.c:ext4_fc_reserve_space
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
In fs/ext4/bitmap.c (ffffffff814447c4)
Location: fs/ext4/ext4.h:2436
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/extents.c (ffffffff81447ae3)
Location: fs/ext4/ext4.h:2436
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/ialloc.c (ffffffff814594fb)
Location: fs/ext4/ext4.h:2436
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff81466486)
Location: fs/ext4/ext4.h:2436
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
```
```
In fs/ext4/ioctl.c (ffffffff8146d3bb)
Location: fs/ext4/ext4.h:2436
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_reset_inode_seed
  - fs/ext4/ioctl.c:ext4_reset_inode_seed
```
```
In fs/ext4/mmp.c (ffffffff8147b509)
Location: fs/ext4/ext4.h:2436
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff8147d972)
Location: fs/ext4/ext4.h:2436
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:ext4_dirblock_csum_verify
```
```
In fs/ext4/super.c (ffffffff814a0ba4)
Location: fs/ext4/ext4.h:2436
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
```
```
In fs/ext4/xattr.c (ffffffff814a9907)
Location: fs/ext4/ext4.h:2436
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
```
```
In fs/ext4/fast_commit.c (ffffffff814adf58)
Location: fs/ext4/ext4.h:2436
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_reserve_space
  - fs/ext4/fast_commit.c:ext4_fc_reserve_space
```
```
In fs/ext4/orphan.c (ffffffff814b21ac)
Location: fs/ext4/ext4.h:2436
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_init_orphan_info
  - fs/ext4/orphan.c:ext4_init_orphan_info
  - fs/ext4/orphan.c:ext4_orphan_file_block_trigger
  - fs/ext4/orphan.c:ext4_orphan_file_block_trigger
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
In fs/ext4/bitmap.c (ffffffff814c0734)
Location: fs/ext4/ext4.h:2441
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/extents.c (ffffffff814c4016)
Location: fs/ext4/ext4.h:2441
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/ialloc.c (ffffffff814d6ee2)
Location: fs/ext4/ext4.h:2441
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff814e5fa2)
Location: fs/ext4/ext4.h:2441
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
```
```
In fs/ext4/ioctl.c (ffffffff814edc30)
Location: fs/ext4/ext4.h:2441
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_reset_inode_seed
  - fs/ext4/ioctl.c:ext4_reset_inode_seed
```
```
In fs/ext4/mmp.c (ffffffff814fd98f)
Location: fs/ext4/ext4.h:2441
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff81500666)
Location: fs/ext4/ext4.h:2441
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:ext4_dirblock_csum_verify
```
```
In fs/ext4/super.c (ffffffff81527687)
Location: fs/ext4/ext4.h:2441
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
```
```
In fs/ext4/xattr.c (ffffffff81531c47)
Location: fs/ext4/ext4.h:2441
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
```
```
In fs/ext4/fast_commit.c (ffffffff81536494)
Location: fs/ext4/ext4.h:2441
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_memcpy
  - fs/ext4/fast_commit.c:ext4_fc_reserve_space
  - fs/ext4/fast_commit.c:ext4_fc_reserve_space
```
```
In fs/ext4/orphan.c (ffffffff8153ad8f)
Location: fs/ext4/ext4.h:2441
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_init_orphan_info
  - fs/ext4/orphan.c:ext4_init_orphan_info
  - fs/ext4/orphan.c:ext4_orphan_file_block_trigger
  - fs/ext4/orphan.c:ext4_orphan_file_block_trigger
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
In fs/ext4/bitmap.c (ffffffff815587d4)
Location: fs/ext4/ext4.h:2451
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/extents.c (ffffffff8155c632)
Location: fs/ext4/ext4.h:2451
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/ialloc.c (ffffffff8156fc67)
Location: fs/ext4/ext4.h:2451
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff8157f721)
Location: fs/ext4/ext4.h:2451
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
```
```
In fs/ext4/ioctl.c (ffffffff81587ae0)
Location: fs/ext4/ext4.h:2451
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_reset_inode_seed
  - fs/ext4/ioctl.c:ext4_reset_inode_seed
```
```
In fs/ext4/mmp.c (ffffffff8159816f)
Location: fs/ext4/ext4.h:2451
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff8159b146)
Location: fs/ext4/ext4.h:2451
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:ext4_dirblock_csum_verify
```
```
In fs/ext4/super.c (ffffffff815c5767)
Location: fs/ext4/ext4.h:2451
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_init_metadata_csum
  - fs/ext4/super.c:ext4_init_metadata_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
```
```
In fs/ext4/xattr.c (ffffffff815d01f2)
Location: fs/ext4/ext4.h:2451
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
```
```
In fs/ext4/fast_commit.c (ffffffff815d4f30)
Location: fs/ext4/ext4.h:2451
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_write_tail
  - fs/ext4/fast_commit.c:ext4_fc_reserve_space
```
```
In fs/ext4/orphan.c (ffffffff815d934f)
Location: fs/ext4/ext4.h:2451
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_init_orphan_info
  - fs/ext4/orphan.c:ext4_init_orphan_info
  - fs/ext4/orphan.c:ext4_orphan_file_block_trigger
  - fs/ext4/orphan.c:ext4_orphan_file_block_trigger
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
In fs/ext4/bitmap.c (ffffffff81590624)
Location: fs/ext4/ext4.h:2445
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/extents.c (ffffffff81594432)
Location: fs/ext4/ext4.h:2445
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/ialloc.c (ffffffff815a7ae9)
Location: fs/ext4/ext4.h:2445
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff815b6bd2)
Location: fs/ext4/ext4.h:2445
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
```
```
In fs/ext4/ioctl.c (ffffffff815be360)
Location: fs/ext4/ext4.h:2445
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_reset_inode_seed
  - fs/ext4/ioctl.c:ext4_reset_inode_seed
```
```
In fs/ext4/mmp.c (ffffffff815cec1f)
Location: fs/ext4/ext4.h:2445
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block_thawed
```
```
In fs/ext4/namei.c (ffffffff815d19c6)
Location: fs/ext4/ext4.h:2445
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:ext4_dirblock_csum_verify
```
```
In fs/ext4/super.c (ffffffff815fd389)
Location: fs/ext4/ext4.h:2445
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_init_metadata_csum
  - fs/ext4/super.c:ext4_init_metadata_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
```
```
In fs/ext4/xattr.c (ffffffff81607a12)
Location: fs/ext4/ext4.h:2445
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
```
```
In fs/ext4/fast_commit.c (ffffffff8160cb00)
Location: fs/ext4/ext4.h:2445
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_write_tail
  - fs/ext4/fast_commit.c:ext4_fc_reserve_space
```
```
In fs/ext4/orphan.c (ffffffff81610ecb)
Location: fs/ext4/ext4.h:2445
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_init_orphan_info
  - fs/ext4/orphan.c:ext4_init_orphan_info
  - fs/ext4/orphan.c:ext4_orphan_file_block_trigger
  - fs/ext4/orphan.c:ext4_orphan_file_block_trigger
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
In fs/ext4/bitmap.c (ffffffff815c9364)
Location: fs/ext4/ext4.h:2463
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/extents.c (ffffffff815cd122)
Location: fs/ext4/ext4.h:2463
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/ialloc.c (ffffffff815e0900)
Location: fs/ext4/ext4.h:2463
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff815ef972)
Location: fs/ext4/ext4.h:2463
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
```
```
In fs/ext4/ioctl.c (ffffffff815f7120)
Location: fs/ext4/ext4.h:2463
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_reset_inode_seed
  - fs/ext4/ioctl.c:ext4_reset_inode_seed
```
```
In fs/ext4/mmp.c (ffffffff8160749f)
Location: fs/ext4/ext4.h:2463
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block_thawed
```
```
In fs/ext4/namei.c (ffffffff8160a166)
Location: fs/ext4/ext4.h:2463
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:ext4_dirblock_csum_verify
```
```
In fs/ext4/super.c (ffffffff81635eef)
Location: fs/ext4/ext4.h:2463
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_journal_blkdev
  - fs/ext4/super.c:ext4_init_metadata_csum
  - fs/ext4/super.c:ext4_init_metadata_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
```
```
In fs/ext4/xattr.c (ffffffff81640752)
Location: fs/ext4/ext4.h:2463
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
```
```
In fs/ext4/fast_commit.c (ffffffff816458c0)
Location: fs/ext4/ext4.h:2463
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_write_tail
  - fs/ext4/fast_commit.c:ext4_fc_reserve_space
```
```
In fs/ext4/orphan.c (ffffffff81649c8b)
Location: fs/ext4/ext4.h:2463
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_init_orphan_info
  - fs/ext4/orphan.c:ext4_init_orphan_info
  - fs/ext4/orphan.c:ext4_orphan_file_block_trigger
  - fs/ext4/orphan.c:ext4_orphan_file_block_trigger
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/bitmap.c (ffff8000104614d8)
Location: fs/ext4/ext4.h:2092
Inline: True
Direct callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/extents.c (ffff8000104643e8)
Location: fs/ext4/ext4.h:2092
Inline: True
Direct callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/ialloc.c (ffff800010473c20)
Location: fs/ext4/ext4.h:2092
Inline: True
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffff80001047d9e8)
Location: fs/ext4/ext4.h:2092
Inline: True
Direct callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffff80001048a3b0)
Location: fs/ext4/ext4.h:2092
Inline: True
Direct callers:
  - fs/ext4/ioctl.c:reset_inode_seed
  - fs/ext4/ioctl.c:reset_inode_seed
```
```
In fs/ext4/mmp.c (ffff800010498dd8)
Location: fs/ext4/ext4.h:2092
Inline: True
Direct callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffff80001049b0e0)
Location: fs/ext4/ext4.h:2092
Inline: True
Direct callers:
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
```
```
In fs/ext4/super.c (ffff8000104ad490)
Location: fs/ext4/ext4.h:2092
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
```
```
In fs/ext4/xattr.c (ffff8000104c20e0)
Location: fs/ext4/ext4.h:2092
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_get
```
**Symbols:**

```
ffff8000104614d8-ffff8000104614dc: ext4_chksum.isra.0.part.0 (STB_LOCAL)
ffff8000104614e0-ffff800010461564: ext4_chksum.isra.0 (STB_LOCAL)
ffff8000104643e8-ffff80001046446c: ext4_chksum.isra.0 (STB_LOCAL)
ffff800010473c20-ffff800010473c24: ext4_chksum.isra.0.part.0 (STB_LOCAL)
ffff800010473ce0-ffff800010473d64: ext4_chksum.isra.0.constprop.0 (STB_LOCAL)
ffff80001047d9e8-ffff80001047d9ec: ext4_chksum.isra.0.part.0 (STB_LOCAL)
ffff80001047d9f0-ffff80001047da74: ext4_chksum.isra.0 (STB_LOCAL)
ffff80001048a3b0-ffff80001048a3b4: ext4_chksum.isra.0.part.0 (STB_LOCAL)
ffff80001048a3b8-ffff80001048a43c: ext4_chksum.isra.0.constprop.0 (STB_LOCAL)
ffff800010498dd8-ffff800010498e5c: ext4_chksum.isra.0.constprop.0 (STB_LOCAL)
ffff80001049b0e0-ffff80001049b0e4: ext4_chksum.isra.0.part.0 (STB_LOCAL)
ffff80001049b0e8-ffff80001049b16c: ext4_chksum.isra.0 (STB_LOCAL)
ffff8000104ad490-ffff8000104ad494: ext4_chksum.isra.0.part.0 (STB_LOCAL)
ffff8000104ad498-ffff8000104ad51c: ext4_chksum.isra.0 (STB_LOCAL)
ffff8000104c20e0-ffff8000104c20e4: ext4_chksum.isra.0.part.0 (STB_LOCAL)
ffff8000104c20e8-ffff8000104c216c: ext4_chksum.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
u32 ext4_chksum(struct ext4_sb_info *sbi, u32 crc, const void *address, unsigned int length);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/bitmap.c (c062197c)
Location: fs/ext4/ext4.h:2092
Inline: True
Direct callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/extents.c (c0624630)
Location: fs/ext4/ext4.h:2092
Inline: False
Direct callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/ialloc.c (c0635248)
Location: fs/ext4/ext4.h:2092
Inline: True
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (c063f638)
Location: fs/ext4/ext4.h:2092
Inline: True
Direct callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
```
```
In fs/ext4/ioctl.c (c064c358)
Location: fs/ext4/ext4.h:2092
Inline: True
Direct callers:
  - fs/ext4/ioctl.c:reset_inode_seed
  - fs/ext4/ioctl.c:reset_inode_seed
```
```
In fs/ext4/mmp.c (c065a890)
Location: fs/ext4/ext4.h:2092
Inline: True
Direct callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (c065cbe4)
Location: fs/ext4/ext4.h:2092
Inline: True
Direct callers:
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
```
```
In fs/ext4/super.c (c0676218)
Location: fs/ext4/ext4.h:2092
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
```
```
In fs/ext4/xattr.c (c06861c0)
Location: fs/ext4/ext4.h:2092
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
```
**Symbols:**

```
c062197c-c062198c: ext4_chksum.part.0 (STB_LOCAL)
c062198c-c0621a20: ext4_chksum (STB_LOCAL)
c0624630-c06246c4: ext4_chksum (STB_LOCAL)
c0635248-c0635258: ext4_chksum.part.0 (STB_LOCAL)
c06352d8-c0635368: ext4_chksum.constprop.0 (STB_LOCAL)
c063f638-c063f648: ext4_chksum.part.0 (STB_LOCAL)
c063f648-c063f6dc: ext4_chksum (STB_LOCAL)
c064c358-c064c368: ext4_chksum.part.0 (STB_LOCAL)
c064c368-c064c3f8: ext4_chksum.constprop.0 (STB_LOCAL)
c065a890-c065a924: ext4_chksum.constprop.0 (STB_LOCAL)
c065cbe4-c065cbf4: ext4_chksum.part.0 (STB_LOCAL)
c065cbf4-c065cc88: ext4_chksum (STB_LOCAL)
c0676218-c0676228: ext4_chksum.part.0 (STB_LOCAL)
c0676228-c06762bc: ext4_chksum (STB_LOCAL)
c06861c0-c06861d0: ext4_chksum.part.0 (STB_LOCAL)
c06861d0-c0686264: ext4_chksum (STB_LOCAL)
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
In fs/ext4/bitmap.c (c00000000057de9c)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/extents.c (c000000000581738)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/ialloc.c (c000000000597330)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (c0000000005a826c)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
```
```
In fs/ext4/ioctl.c (c0000000005b1890)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:reset_inode_seed
  - fs/ext4/ioctl.c:reset_inode_seed
```
```
In fs/ext4/mmp.c (c0000000005c32bc)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (c0000000005c5d78)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
```
```
In fs/ext4/super.c (c0000000005f19ac)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
```
```
In fs/ext4/xattr.c (c0000000005fa7c4)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
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
In fs/ext4/bitmap.c (ffffffe0002f07f0)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/extents.c (ffffffe0002f28c2)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/ialloc.c (ffffffe0003011b2)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffe00030bac6)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
```
```
In fs/ext4/ioctl.c (ffffffe000311962)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:reset_inode_seed
  - fs/ext4/ioctl.c:reset_inode_seed
  - fs/ext4/ioctl.c:reset_inode_seed
```
```
In fs/ext4/mmp.c (ffffffe00031cc86)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffe00031e7e6)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
```
```
In fs/ext4/super.c (ffffffe000337d66)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
  - fs/ext4/super.c:ext4_superblock_csum_set
```
```
In fs/ext4/xattr.c (ffffffe00033e0c8)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
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
In fs/ext4/bitmap.c (ffffffff8138761d)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/extents.c (ffffffff81389e3f)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_extent_block_csum
```
```
In fs/ext4/ialloc.c (ffffffff8139a669)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff813a6ec1)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff813ae16d)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:reset_inode_seed
  - fs/ext4/ioctl.c:reset_inode_seed
  - fs/ext4/ioctl.c:reset_inode_seed
  - fs/ext4/ioctl.c:reset_inode_seed
```
```
In fs/ext4/mmp.c (ffffffff813b9f48)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff813bbea1)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
```
```
In fs/ext4/super.c (ffffffff813dab51)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
  - fs/ext4/super.c:ext4_superblock_csum_set
```
```
In fs/ext4/xattr.c (ffffffff813e28cf)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_inode_get
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
In fs/ext4/bitmap.c (ffffffff813780ad)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/extents.c (ffffffff8137a8cf)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_extent_block_csum
```
```
In fs/ext4/ialloc.c (ffffffff8138b0f9)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff81397951)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff8139ebfd)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:reset_inode_seed
  - fs/ext4/ioctl.c:reset_inode_seed
  - fs/ext4/ioctl.c:reset_inode_seed
  - fs/ext4/ioctl.c:reset_inode_seed
```
```
In fs/ext4/mmp.c (ffffffff813aa9d8)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff813ac931)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
```
```
In fs/ext4/super.c (ffffffff813cb5d1)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
  - fs/ext4/super.c:ext4_superblock_csum_set
```
```
In fs/ext4/xattr.c (ffffffff813d334f)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_inode_get
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
In fs/ext4/bitmap.c (ffffffff813850ed)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/extents.c (ffffffff8138779f)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_extent_block_csum
```
```
In fs/ext4/ialloc.c (ffffffff81397ec9)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff813a4721)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff813ab9cd)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:reset_inode_seed
  - fs/ext4/ioctl.c:reset_inode_seed
  - fs/ext4/ioctl.c:reset_inode_seed
  - fs/ext4/ioctl.c:reset_inode_seed
```
```
In fs/ext4/mmp.c (ffffffff813b77a8)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff813b9881)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
```
```
In fs/ext4/super.c (ffffffff813d7ff1)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
  - fs/ext4/super.c:ext4_superblock_csum_set
```
```
In fs/ext4/xattr.c (ffffffff813dfc4f)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_inode_get
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
In fs/ext4/bitmap.c (ffffffff81398c6d)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/extents.c (ffffffff8139b47f)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_extent_block_csum
```
```
In fs/ext4/ialloc.c (ffffffff813abca3)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff813b8e2e)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff813c036d)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:reset_inode_seed
  - fs/ext4/ioctl.c:reset_inode_seed
  - fs/ext4/ioctl.c:reset_inode_seed
  - fs/ext4/ioctl.c:reset_inode_seed
```
```
In fs/ext4/mmp.c (ffffffff813cc4ab)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff813ce421)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
```
```
In fs/ext4/super.c (ffffffff813ed291)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
  - fs/ext4/super.c:ext4_superblock_csum_set
```
```
In fs/ext4/xattr.c (ffffffff813f506f)
Location: fs/ext4/ext4.h:2092
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_inode_get
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
