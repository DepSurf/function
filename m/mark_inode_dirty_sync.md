# Function: <code>mark_inode_dirty_sync</code>

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
In fs/inode.c (ffffffff81227f00)
Location: include/linux/fs.h:1885
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8123b1f2)
Location: include/linux/fs.h:1885
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
```
```
In fs/sync.c (ffffffff81240613)
Location: include/linux/fs.h:1885
Inline: True
Inline callers:
  - fs/sync.c:vfs_fsync_range
```
```
In fs/quota/dquot.c (ffffffff81273776)
Location: include/linux/fs.h:1885
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
```
```
In fs/ext4/balloc.c (ffffffff8128f68e)
Location: include/linux/fs.h:1885
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_new_meta_blocks
```
```
In fs/ext4/inode.c (ffffffff81298a31)
Location: include/linux/fs.h:1885
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffff812d432b)
Location: include/linux/fs.h:1885
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
```
In fs/ext4/xattr.c (ffffffff812dd270)
Location: include/linux/fs.h:1885
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/ecryptfs/read_write.c (ffffffff8130491c)
Location: include/linux/fs.h:1885
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower
```
```
In fs/fuse/dir.c (ffffffff81312637)
Location: include/linux/fs.h:1885
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_removexattr
  - fs/fuse/dir.c:fuse_setxattr
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
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
In fs/inode.c (ffffffff81250632)
Location: include/linux/fs.h:1978
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812630ac)
Location: include/linux/fs.h:1978
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
```
```
In fs/sync.c (ffffffff81268953)
Location: include/linux/fs.h:1978
Inline: True
Inline callers:
  - fs/sync.c:vfs_fsync_range
```
```
In fs/quota/dquot.c (ffffffff8129ffa3)
Location: include/linux/fs.h:1978
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
```
```
In fs/ext4/balloc.c (ffffffff812bcbbe)
Location: include/linux/fs.h:1978
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_new_meta_blocks
```
```
In fs/ext4/inode.c (ffffffff812c5bdc)
Location: include/linux/fs.h:1978
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffff81304b3a)
Location: include/linux/fs.h:1978
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/xattr.c (ffffffff8130d537)
Location: include/linux/fs.h:1978
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/ecryptfs/read_write.c (ffffffff81338a3c)
Location: include/linux/fs.h:1978
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower
```
```
In fs/fuse/dir.c (ffffffff81346b01)
Location: include/linux/fs.h:1978
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_removexattr
  - fs/fuse/dir.c:fuse_setxattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
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
In fs/inode.c (ffffffff812636d2)
Location: include/linux/fs.h:1951
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812764fc)
Location: include/linux/fs.h:1951
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
```
```
In fs/sync.c (ffffffff8127b973)
Location: include/linux/fs.h:1951
Inline: True
Inline callers:
  - fs/sync.c:vfs_fsync_range
```
```
In fs/quota/dquot.c (ffffffff812b54e5)
Location: include/linux/fs.h:1951
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
```
```
In fs/ext4/balloc.c (ffffffff812d220e)
Location: include/linux/fs.h:1951
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_new_meta_blocks
```
```
In fs/ext4/inode.c (ffffffff812db40c)
Location: include/linux/fs.h:1951
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffff8131aafa)
Location: include/linux/fs.h:1951
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/xattr.c (ffffffff8132342c)
Location: include/linux/fs.h:1951
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/ecryptfs/read_write.c (ffffffff8134e7dc)
Location: include/linux/fs.h:1951
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower
```
```
In fs/fuse/dir.c (ffffffff8135c112)
Location: include/linux/fs.h:1951
Inline: True
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
In fs/inode.c (ffffffff81271091)
Location: include/linux/fs.h:2001
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81283986)
Location: include/linux/fs.h:2001
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
```
```
In fs/sync.c (ffffffff81288d03)
Location: include/linux/fs.h:2001
Inline: True
Inline callers:
  - fs/sync.c:vfs_fsync_range
```
```
In fs/quota/dquot.c (ffffffff812c1db3)
Location: include/linux/fs.h:2001
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
```
```
In fs/ext4/balloc.c (ffffffff812e38aa)
Location: include/linux/fs.h:2001
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_new_meta_blocks
```
```
In fs/ext4/inode.c (ffffffff812ffcbe)
Location: include/linux/fs.h:2001
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffff81311eb9)
Location: include/linux/fs.h:2001
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/xattr.c (ffffffff8133c887)
Location: include/linux/fs.h:2001
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/ecryptfs/read_write.c (ffffffff813632fc)
Location: include/linux/fs.h:2001
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower
```
```
In fs/fuse/dir.c (ffffffff81370aa4)
Location: include/linux/fs.h:2001
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
In fs/inode.c (ffffffff812939b5)
Location: include/linux/fs.h:2031
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812a651f)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
```
```
In fs/sync.c (ffffffff812ab849)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/sync.c:vfs_fsync_range
```
```
In fs/quota/dquot.c (ffffffff812e5bf0)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
```
```
In fs/ext4/balloc.c (ffffffff8130829a)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_new_meta_blocks
```
```
In fs/ext4/inode.c (ffffffff813244d0)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffff813366d2)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/xattr.c (ffffffff81360e0d)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/ecryptfs/read_write.c (ffffffff81387fcf)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower
```
```
In fs/fuse/dir.c (ffffffff813957a4)
Location: include/linux/fs.h:2031
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
In fs/inode.c (ffffffff812b9cd5)
Location: include/linux/fs.h:2062
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812cd0de)
Location: include/linux/fs.h:2062
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
```
```
In fs/sync.c (ffffffff812d248d)
Location: include/linux/fs.h:2062
Inline: True
Inline callers:
  - fs/sync.c:vfs_fsync_range
```
```
In fs/quota/dquot.c (ffffffff81313085)
Location: include/linux/fs.h:2062
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
```
```
In fs/ext4/balloc.c (ffffffff8133619a)
Location: include/linux/fs.h:2062
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_new_meta_blocks
```
```
In fs/ext4/inode.c (ffffffff81352656)
Location: include/linux/fs.h:2062
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffff81364d0f)
Location: include/linux/fs.h:2062
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/xattr.c (ffffffff8138f763)
Location: include/linux/fs.h:2062
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/ecryptfs/read_write.c (ffffffff813b6e3a)
Location: include/linux/fs.h:2062
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower
```
```
In fs/fuse/dir.c (ffffffff813c49c5)
Location: include/linux/fs.h:2062
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
In fs/inode.c (ffffffff812cec45)
Location: include/linux/fs.h:2147
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812e23fe)
Location: include/linux/fs.h:2147
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
```
```
In fs/sync.c (ffffffff812e786d)
Location: include/linux/fs.h:2147
Inline: True
Inline callers:
  - fs/sync.c:vfs_fsync_range
```
```
In fs/quota/dquot.c (ffffffff8132a015)
Location: include/linux/fs.h:2147
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
```
```
In fs/ext4/balloc.c (ffffffff8134d41b)
Location: include/linux/fs.h:2147
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_new_meta_blocks
```
```
In fs/ext4/extents.c (ffffffff81350555)
Location: include/linux/fs.h:2147
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_rereserve_cluster
```
```
In fs/ext4/inode.c (ffffffff8136a777)
Location: include/linux/fs.h:2147
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/ioctl.c (ffffffff81374a2a)
Location: include/linux/fs.h:2147
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/mballoc.c (ffffffff8137d177)
Location: include/linux/fs.h:2147
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/xattr.c (ffffffff813a80e9)
Location: include/linux/fs.h:2147
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/ecryptfs/read_write.c (ffffffff813d038a)
Location: include/linux/fs.h:2147
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower
```
```
In fs/fuse/dir.c (ffffffff813ddf55)
Location: include/linux/fs.h:2147
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
In fs/inode.c (ffffffff812ebb62)
Location: include/linux/fs.h:2154
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81300e12)
Location: include/linux/fs.h:2154
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
```
```
In fs/sync.c (ffffffff8130611f)
Location: include/linux/fs.h:2154
Inline: True
Inline callers:
  - fs/sync.c:vfs_fsync_range
```
```
In fs/quota/dquot.c (ffffffff81351b8f)
Location: include/linux/fs.h:2154
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
```
```
In fs/ext4/balloc.c (ffffffff81375e11)
Location: include/linux/fs.h:2154
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_new_meta_blocks
```
```
In fs/ext4/extents.c (ffffffff81379215)
Location: include/linux/fs.h:2154
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_rereserve_cluster
```
```
In fs/ext4/inode.c (ffffffff81393d1f)
Location: include/linux/fs.h:2154
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/ioctl.c (ffffffff8139d4fd)
Location: include/linux/fs.h:2154
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffffffff813a6e14)
Location: include/linux/fs.h:2154
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/xattr.c (ffffffff813d25d8)
Location: include/linux/fs.h:2154
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/ecryptfs/read_write.c (ffffffff813faf8a)
Location: include/linux/fs.h:2154
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower
```
```
In fs/fuse/dir.c (ffffffff8140a018)
Location: include/linux/fs.h:2154
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
In fs/inode.c (ffffffff812fd695)
Location: include/linux/fs.h:2189
Inline: True
```
```
In fs/fs-writeback.c (ffffffff813134e2)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
```
```
In fs/sync.c (ffffffff8131919f)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/sync.c:vfs_fsync_range
```
```
In fs/quota/dquot.c (ffffffff81369f0f)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
```
```
In fs/ext4/balloc.c (ffffffff8138e081)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_new_meta_blocks
```
```
In fs/ext4/extents.c (ffffffff813915c5)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_rereserve_cluster
```
```
In fs/ext4/inode.c (ffffffff813ac6b3)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/ioctl.c (ffffffff813b5f6d)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffffffff813bfc97)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/xattr.c (ffffffff813ebcb8)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/ecryptfs/read_write.c (ffffffff81414e5a)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower
```
```
In fs/fuse/dir.c (ffffffff81423558)
Location: include/linux/fs.h:2189
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
In fs/inode.c (ffffffff81336a3f)
Location: include/linux/fs.h:2222
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8134ce1a)
Location: include/linux/fs.h:2222
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
```
```
In fs/sync.c (ffffffff81352e0f)
Location: include/linux/fs.h:2222
Inline: True
```
```
In fs/ext4/balloc.c (ffffffff813d95a1)
Location: include/linux/fs.h:2222
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_new_meta_blocks
```
```
In fs/ext4/extents.c (ffffffff813dd0a5)
Location: include/linux/fs.h:2222
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_rereserve_cluster
```
```
In fs/ext4/inode.c (ffffffff813f897a)
Location: include/linux/fs.h:2222
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/ioctl.c (ffffffff81401989)
Location: include/linux/fs.h:2222
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffffffff8140bd7e)
Location: include/linux/fs.h:2222
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/xattr.c (ffffffff81438e9c)
Location: include/linux/fs.h:2222
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/ecryptfs/read_write.c (ffffffff8146316d)
Location: include/linux/fs.h:2222
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
```
In fs/fuse/dir.c (ffffffff81474149)
Location: include/linux/fs.h:2222
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
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
In fs/inode.c (ffffffff81342397)
Location: include/linux/fs.h:2191
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81359c61)
Location: include/linux/fs.h:2191
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
```
```
In fs/sync.c (ffffffff8135f6ef)
Location: include/linux/fs.h:2191
Inline: True
```
```
In fs/ext4/balloc.c (ffffffff813eb231)
Location: include/linux/fs.h:2191
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_new_meta_blocks
```
```
In fs/ext4/extents.c (ffffffff813ee9c5)
Location: include/linux/fs.h:2191
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_rereserve_cluster
```
```
In fs/ext4/inode.c (ffffffff8140b047)
Location: include/linux/fs.h:2191
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/ioctl.c (ffffffff81414387)
Location: include/linux/fs.h:2191
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffffffff8141f227)
Location: include/linux/fs.h:2191
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/xattr.c (ffffffff814519c5)
Location: include/linux/fs.h:2191
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/ecryptfs/read_write.c (ffffffff8147e9bd)
Location: include/linux/fs.h:2191
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
```
In fs/fuse/dir.c (ffffffff8148ea9c)
Location: include/linux/fs.h:2191
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
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
In fs/inode.c (ffffffff8134879d)
Location: include/linux/fs.h:2407
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81360923)
Location: include/linux/fs.h:2407
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
```
```
In fs/sync.c (ffffffff8136617f)
Location: include/linux/fs.h:2407
Inline: True
```
```
In fs/ext4/balloc.c (ffffffff813f1761)
Location: include/linux/fs.h:2407
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_new_meta_blocks
```
```
In fs/ext4/extents.c (ffffffff813f4f95)
Location: include/linux/fs.h:2407
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_rereserve_cluster
```
```
In fs/ext4/inode.c (ffffffff81411207)
Location: include/linux/fs.h:2407
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/ioctl.c (ffffffff8141a5fc)
Location: include/linux/fs.h:2407
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffffffff81425b64)
Location: include/linux/fs.h:2407
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/xattr.c (ffffffff814570f5)
Location: include/linux/fs.h:2407
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/ecryptfs/read_write.c (ffffffff8148454d)
Location: include/linux/fs.h:2407
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
```
In fs/fuse/dir.c (ffffffff814944cc)
Location: include/linux/fs.h:2407
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
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
In fs/inode.c (ffffffff8139632c)
Location: include/linux/fs.h:2461
Inline: True
```
```
In fs/fs-writeback.c (ffffffff813aef9d)
Location: include/linux/fs.h:2461
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
```
```
In fs/sync.c (ffffffff813b4acf)
Location: include/linux/fs.h:2461
Inline: True
```
```
In fs/ext4/balloc.c (ffffffff8144377a)
Location: include/linux/fs.h:2461
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_new_meta_blocks
```
```
In fs/ext4/extents.c (ffffffff81447200)
Location: include/linux/fs.h:2461
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_rereserve_cluster
```
```
In fs/ext4/inode.c (ffffffff8146403d)
Location: include/linux/fs.h:2461
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/ioctl.c (ffffffff8146d7ec)
Location: include/linux/fs.h:2461
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffffffff814793d7)
Location: include/linux/fs.h:2461
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/xattr.c (ffffffff814ab189)
Location: include/linux/fs.h:2461
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/ecryptfs/read_write.c (ffffffff814dbbcd)
Location: include/linux/fs.h:2461
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
```
In fs/fuse/dir.c (ffffffff814ec1ec)
Location: include/linux/fs.h:2461
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
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
In fs/inode.c (ffffffff81417731)
Location: include/linux/fs.h:2335
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8143379e)
Location: include/linux/fs.h:2335
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
```
```
In fs/sync.c (ffffffff81439e29)
Location: include/linux/fs.h:2335
Inline: True
```
```
In fs/ext4/balloc.c (ffffffff814bf5e4)
Location: include/linux/fs.h:2335
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_new_meta_blocks
```
```
In fs/ext4/extents.c (ffffffff814c36ef)
Location: include/linux/fs.h:2335
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_rereserve_cluster
```
```
In fs/ext4/inode.c (ffffffff814e3537)
Location: include/linux/fs.h:2335
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/ioctl.c (ffffffff814ee0ad)
Location: include/linux/fs.h:2335
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffffffff814f5a9b)
Location: include/linux/fs.h:2335
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/xattr.c (ffffffff81532e62)
Location: include/linux/fs.h:2335
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/ecryptfs/read_write.c (ffffffff8156983d)
Location: include/linux/fs.h:2335
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
```
In fs/fuse/dir.c (ffffffff8157ae5a)
Location: include/linux/fs.h:2335
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_entry_unlinked
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
In fs/inode.c (ffffffff814a2eb1)
Location: include/linux/fs.h:2468
Inline: True
```
```
In fs/fs-writeback.c (ffffffff814c19fe)
Location: include/linux/fs.h:2468
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
```
```
In fs/sync.c (ffffffff814c81a9)
Location: include/linux/fs.h:2468
Inline: True
```
```
In fs/ext4/balloc.c (ffffffff81557554)
Location: include/linux/fs.h:2468
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_new_meta_blocks
```
```
In fs/ext4/extents.c (ffffffff8155b9ff)
Location: include/linux/fs.h:2468
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_rereserve_cluster
```
```
In fs/ext4/inode.c (ffffffff8157ca17)
Location: include/linux/fs.h:2468
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/ioctl.c (ffffffff81587f8f)
Location: include/linux/fs.h:2468
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffffffff81590020)
Location: include/linux/fs.h:2468
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/xattr.c (ffffffff815d1332)
Location: include/linux/fs.h:2468
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/ecryptfs/read_write.c (ffffffff8160d45d)
Location: include/linux/fs.h:2468
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
```
In fs/fuse/dir.c (ffffffff8162064a)
Location: include/linux/fs.h:2468
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_entry_unlinked
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
In fs/inode.c (ffffffff814d8000)
Location: include/linux/fs.h:2157
Inline: True
```
```
In fs/fs-writeback.c (ffffffff814f6d8e)
Location: include/linux/fs.h:2157
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
```
```
In fs/sync.c (ffffffff814fe3dc)
Location: include/linux/fs.h:2157
Inline: True
```
```
In fs/ext4/balloc.c (ffffffff8158f3d4)
Location: include/linux/fs.h:2157
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_new_meta_blocks
```
```
In fs/ext4/extents.c (ffffffff8159381f)
Location: include/linux/fs.h:2157
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_rereserve_cluster
```
```
In fs/ext4/inode.c (ffffffff815b3e17)
Location: include/linux/fs.h:2157
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/ioctl.c (ffffffff815be813)
Location: include/linux/fs.h:2157
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffffffff815c6fb9)
Location: include/linux/fs.h:2157
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/xattr.c (ffffffff81608ed2)
Location: include/linux/fs.h:2157
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/ecryptfs/read_write.c (ffffffff8164531d)
Location: include/linux/fs.h:2157
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
```
In fs/fuse/dir.c (ffffffff81658a8f)
Location: include/linux/fs.h:2157
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_entry_unlinked
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
In fs/inode.c (ffffffff8150a7e0)
Location: include/linux/fs.h:2385
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8152b4ce)
Location: include/linux/fs.h:2385
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
```
```
In fs/sync.c (ffffffff81532fdc)
Location: include/linux/fs.h:2385
Inline: True
```
```
In fs/ext4/balloc.c (ffffffff815c80e4)
Location: include/linux/fs.h:2385
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_new_meta_blocks
```
```
In fs/ext4/extents.c (ffffffff815cc50f)
Location: include/linux/fs.h:2385
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_rereserve_cluster
```
```
In fs/ext4/inode.c (ffffffff815ecb5f)
Location: include/linux/fs.h:2385
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/ioctl.c (ffffffff815f75bc)
Location: include/linux/fs.h:2385
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffffffff81601c62)
Location: include/linux/fs.h:2385
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/xattr.c (ffffffff81641c12)
Location: include/linux/fs.h:2385
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/ecryptfs/read_write.c (ffffffff8167e841)
Location: include/linux/fs.h:2385
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
```
In fs/fuse/dir.c (ffffffff816927d1)
Location: include/linux/fs.h:2385
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_entry_unlinked
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
In fs/inode.c (ffff8000103ae13c)
Location: include/linux/fs.h:2189
Inline: True
```
```
In fs/fs-writeback.c (ffff8000103c8d20)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
```
```
In fs/sync.c (ffff8000103d0184)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/sync.c:vfs_fsync_range
```
```
In fs/quota/dquot.c (ffff80001043229c)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
```
```
In fs/ext4/balloc.c (ffff8000104601e0)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_new_meta_blocks
```
```
In fs/ext4/extents.c (ffff800010464a10)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_rereserve_cluster
```
```
In fs/ext4/inode.c (ffff800010480e48)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/ioctl.c (ffff80001048a8d8)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffff800010496858)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/xattr.c (ffff8000104c4b50)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/ecryptfs/read_write.c (ffff8000104f64e0)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower
```
```
In fs/fuse/dir.c (ffff80001050671c)
Location: include/linux/fs.h:2189
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
In fs/inode.c (c058e294)
Location: include/linux/fs.h:2189
Inline: True
```
```
In fs/fs-writeback.c (c05a56d8)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
```
```
In fs/sync.c (c05ab508)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/sync.c:vfs_fsync_range
```
```
In fs/quota/dquot.c (c05fa244)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
```
```
In fs/ext4/balloc.c (c0620a20)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_new_meta_blocks
```
```
In fs/ext4/extents.c (c0625204)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_rereserve_cluster
```
```
In fs/ext4/inode.c (c0641e70)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/ioctl.c (c064cc38)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (c0658754)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/xattr.c (c0688ba8)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/ecryptfs/read_write.c (c06b3eac)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower
```
```
In fs/fuse/dir.c (c06c27bc)
Location: include/linux/fs.h:2189
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
In fs/inode.c (c0000000004a9248)
Location: include/linux/fs.h:2189
Inline: True
```
```
In fs/fs-writeback.c (c0000000004ca450)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
```
```
In fs/sync.c (c0000000004d278c)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/sync.c:vfs_fsync_range
```
```
In fs/quota/dquot.c (c0000000005435b8)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
```
```
In fs/ext4/balloc.c (c00000000057c5fc)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_new_meta_blocks
```
```
In fs/ext4/extents.c (c0000000005822dc)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_rereserve_cluster
```
```
In fs/ext4/inode.c (c0000000005a5260)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/ioctl.c (c0000000005b1d24)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (c0000000005c0980)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/xattr.c (c0000000005fc4a8)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/ecryptfs/read_write.c (c0000000006373b4)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower
```
```
In fs/fuse/dir.c (c00000000064be64)
Location: include/linux/fs.h:2189
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
In fs/inode.c (ffffffe0002729fc)
Location: include/linux/fs.h:2189
Inline: True
```
```
In fs/fs-writeback.c (ffffffe0002873fc)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
```
```
In fs/sync.c (ffffffe00028c486)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/sync.c:vfs_fsync_range
```
```
In fs/quota/dquot.c (ffffffe0002ce542)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
```
```
In fs/ext4/balloc.c (ffffffe0002ef84e)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_new_meta_blocks
```
```
In fs/ext4/extents.c (ffffffe0002f3096)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_rereserve_cluster
```
```
In fs/ext4/inode.c (ffffffe000309b20)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/ioctl.c (ffffffe000311c46)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffffffe00031b36a)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/xattr.c (ffffffe00033f438)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/ecryptfs/read_write.c (ffffffe0003651de)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower
```
```
In fs/fuse/dir.c (ffffffe000372bda)
Location: include/linux/fs.h:2189
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
In fs/inode.c (ffffffff812f5c75)
Location: include/linux/fs.h:2189
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8130bac2)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
```
```
In fs/sync.c (ffffffff8131177f)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/sync.c:vfs_fsync_range
```
```
In fs/quota/dquot.c (ffffffff813624ef)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
```
```
In fs/ext4/balloc.c (ffffffff81386661)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_new_meta_blocks
```
```
In fs/ext4/extents.c (ffffffff81389ba5)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_rereserve_cluster
```
```
In fs/ext4/inode.c (ffffffff813a4c93)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/ioctl.c (ffffffff813ae54d)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffffffff813b8277)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/xattr.c (ffffffff813e4298)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/ecryptfs/read_write.c (ffffffff8140d43a)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower
```
```
In fs/fuse/dir.c (ffffffff8141bb38)
Location: include/linux/fs.h:2189
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
In fs/inode.c (ffffffff812e6895)
Location: include/linux/fs.h:2189
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812fc6e2)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
```
```
In fs/sync.c (ffffffff8130238f)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/sync.c:vfs_fsync_range
```
```
In fs/quota/dquot.c (ffffffff8135318f)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
```
```
In fs/ext4/balloc.c (ffffffff813770f1)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_new_meta_blocks
```
```
In fs/ext4/extents.c (ffffffff8137a635)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_rereserve_cluster
```
```
In fs/ext4/inode.c (ffffffff81395723)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/ioctl.c (ffffffff8139efdd)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffffffff813a8d07)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/xattr.c (ffffffff813d4d18)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/ecryptfs/read_write.c (ffffffff813fdeba)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower
```
```
In fs/fuse/dir.c (ffffffff8140c5b8)
Location: include/linux/fs.h:2189
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
In fs/inode.c (ffffffff812f3a85)
Location: include/linux/fs.h:2189
Inline: True
```
```
In fs/fs-writeback.c (ffffffff813098b2)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
```
```
In fs/sync.c (ffffffff8130f56f)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/sync.c:vfs_fsync_range
```
```
In fs/quota/dquot.c (ffffffff8135ffbf)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
```
```
In fs/ext4/balloc.c (ffffffff81384131)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_new_meta_blocks
```
```
In fs/ext4/extents.c (ffffffff81387505)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_rereserve_cluster
```
```
In fs/ext4/inode.c (ffffffff813a24f3)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/ioctl.c (ffffffff813abdad)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffffffff813b5ad7)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/xattr.c (ffffffff813e1618)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/ecryptfs/read_write.c (ffffffff8140a7ba)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower
```
```
In fs/fuse/dir.c (ffffffff81417cd8)
Location: include/linux/fs.h:2189
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
In fs/inode.c (ffffffff81304eac)
Location: include/linux/fs.h:2189
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8131a297)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
```
```
In fs/sync.c (ffffffff81320d6f)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/sync.c:vfs_fsync_range
```
```
In fs/quota/dquot.c (ffffffff81372a7b)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
```
```
In fs/ext4/balloc.c (ffffffff81397c91)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_new_meta_blocks
```
```
In fs/ext4/extents.c (ffffffff8139b1e5)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_rereserve_cluster
```
```
In fs/ext4/inode.c (ffffffff813b6b95)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/ioctl.c (ffffffff813c074d)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffffffff813ca7b2)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/xattr.c (ffffffff813f6a29)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/ecryptfs/read_write.c (ffffffff814204aa)
Location: include/linux/fs.h:2189
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower
```
```
In fs/fuse/dir.c (ffffffff8142ebd8)
Location: include/linux/fs.h:2189
Inline: True
```
</details>
</li>
</ul>

## Differences
