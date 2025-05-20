# Function: <code>inode_unlock_shared</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81242612)
Location: include/linux/fs.h:750
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:lookup_slow
```
```
In fs/readdir.c (ffffffff81247eae)
Location: include/linux/fs.h:750
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/libfs.c (ffffffff8125cf56)
Location: include/linux/fs.h:750
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/ext4/dir.c (ffffffff812be6a6)
Location: include/linux/fs.h:750
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/fat/dir.c (ffffffff8132c60f)
Location: include/linux/fs.h:750
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_ioctl_readdir
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
In fs/namei.c (ffffffff81255509)
Location: include/linux/fs.h:703
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:lookup_slow
```
```
In fs/readdir.c (ffffffff8125aeee)
Location: include/linux/fs.h:703
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/libfs.c (ffffffff81270496)
Location: include/linux/fs.h:703
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/ext4/dir.c (ffffffff812d3d1a)
Location: include/linux/fs.h:703
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/file.c (ffffffff812d5599)
Location: include/linux/fs.h:703
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/ext4/inode.c (ffffffff812e1953)
Location: include/linux/fs.h:703
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/fat/dir.c (ffffffff8134234f)
Location: include/linux/fs.h:703
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_ioctl_readdir
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
In fs/namei.c (ffffffff812614ca)
Location: include/linux/fs.h:722
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:lookup_slow
```
```
In fs/readdir.c (ffffffff812678dc)
Location: include/linux/fs.h:722
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/libfs.c (ffffffff8127dbb6)
Location: include/linux/fs.h:722
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/ext4/dir.c (ffffffff812e56f8)
Location: include/linux/fs.h:722
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/file.c (ffffffff812f13e0)
Location: include/linux/fs.h:722
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/inode.c (ffffffff81305d5b)
Location: include/linux/fs.h:722
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/fat/dir.c (ffffffff81356b04)
Location: include/linux/fs.h:722
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_ioctl_readdir
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
In fs/namei.c (ffffffff81283bed)
Location: include/linux/fs.h:726
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:lookup_slow
```
```
In fs/readdir.c (ffffffff8128a24a)
Location: include/linux/fs.h:726
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/libfs.c (ffffffff812a0666)
Location: include/linux/fs.h:726
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/ext4/dir.c (ffffffff8130a125)
Location: include/linux/fs.h:726
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/file.c (ffffffff81315993)
Location: include/linux/fs.h:726
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/inode.c (ffffffff8132a8ab)
Location: include/linux/fs.h:726
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/fat/dir.c (ffffffff8137b744)
Location: include/linux/fs.h:726
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_ioctl_readdir
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
In fs/namei.c (ffffffff812aad89)
Location: include/linux/fs.h:728
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:lookup_slow
```
```
In fs/readdir.c (ffffffff812b05e7)
Location: include/linux/fs.h:728
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/libfs.c (ffffffff812c7248)
Location: include/linux/fs.h:728
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/ext4/dir.c (ffffffff8133802d)
Location: include/linux/fs.h:728
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/file.c (ffffffff813437cd)
Location: include/linux/fs.h:728
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/inode.c (ffffffff81358c29)
Location: include/linux/fs.h:728
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/fat/dir.c (ffffffff813aa13d)
Location: include/linux/fs.h:728
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_ioctl_readdir
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
In fs/namei.c (ffffffff812bfc12)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:lookup_slow
```
```
In fs/readdir.c (ffffffff812c5741)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/libfs.c (ffffffff812dc3b6)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/ext4/dir.c (ffffffff8134f2be)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/file.c (ffffffff8135b90d)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/inode.c (ffffffff81370f58)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/fat/dir.c (ffffffff813c2f1d)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_ioctl_readdir
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
In fs/namei.c (ffffffff812dcfa8)
Location: include/linux/fs.h:791
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:lookup_slow
```
```
In fs/readdir.c (ffffffff812e21c3)
Location: include/linux/fs.h:791
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/libfs.c (ffffffff812faa75)
Location: include/linux/fs.h:791
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/ext4/dir.c (ffffffff8137830b)
Location: include/linux/fs.h:791
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/file.c (ffffffff813849a1)
Location: include/linux/fs.h:791
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/inode.c (ffffffff8139a92b)
Location: include/linux/fs.h:791
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/fat/dir.c (ffffffff813ed770)
Location: include/linux/fs.h:791
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_ioctl_readdir
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
In fs/namei.c (ffffffff812eeabb)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:lookup_slow
```
```
In fs/readdir.c (ffffffff812f3c93)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/libfs.c (ffffffff8130ce9d)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/ext4/dir.c (ffffffff813906ab)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/file.c (ffffffff8139d421)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/inode.c (ffffffff813b3441)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/fat/dir.c (ffffffff81407890)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_ioctl_readdir
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
In fs/namei.c (ffffffff81326159)
Location: include/linux/fs.h:823
Inline: True
Inline callers:
  - fs/namei.c:open_last_lookups
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:walk_component
```
```
In fs/readdir.c (ffffffff8132c452)
Location: include/linux/fs.h:823
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/libfs.c (ffffffff813468c5)
Location: include/linux/fs.h:823
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/ext4/dir.c (ffffffff813dbcb8)
Location: include/linux/fs.h:823
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/file.c (ffffffff813e9651)
Location: include/linux/fs.h:823
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_dio_write_checks
  - fs/ext4/file.c:ext4_dio_write_checks
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/fat/dir.c (ffffffff81455388)
Location: include/linux/fs.h:823
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_ioctl_readdir
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
In fs/namei.c (ffffffff81331695)
Location: include/linux/fs.h:786
Inline: True
Inline callers:
  - fs/namei.c:open_last_lookups
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:walk_component
```
```
In fs/readdir.c (ffffffff81337a2c)
Location: include/linux/fs.h:786
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/libfs.c (ffffffff81352db5)
Location: include/linux/fs.h:786
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/ext4/dir.c (ffffffff813ed76c)
Location: include/linux/fs.h:786
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/file.c (ffffffff813fb301)
Location: include/linux/fs.h:786
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_dio_write_checks
  - fs/ext4/file.c:ext4_dio_write_checks
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/fat/dir.c (ffffffff81471828)
Location: include/linux/fs.h:786
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_ioctl_readdir
```
```
In fs/fat/file.c (ffffffff81474cd3)
Location: include/linux/fs.h:786
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/fuse/dax.c (ffffffff8149de5d)
Location: include/linux/fs.h:786
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_read_iter
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
In fs/namei.c (ffffffff81338055)
Location: include/linux/fs.h:787
Inline: True
Inline callers:
  - fs/namei.c:open_last_lookups
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:walk_component
```
```
In fs/readdir.c (ffffffff8133e18c)
Location: include/linux/fs.h:787
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/libfs.c (ffffffff81359985)
Location: include/linux/fs.h:787
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/ext4/dir.c (ffffffff813f3de8)
Location: include/linux/fs.h:787
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/file.c (ffffffff814017d1)
Location: include/linux/fs.h:787
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/fat/dir.c (ffffffff81477230)
Location: include/linux/fs.h:787
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_ioctl_readdir
```
```
In fs/fat/file.c (ffffffff8147a6b6)
Location: include/linux/fs.h:787
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/fuse/dax.c (ffffffff814a3e2d)
Location: include/linux/fs.h:787
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_read_iter
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
In fs/namei.c (ffffffff81385a55)
Location: include/linux/fs.h:799
Inline: True
Inline callers:
  - fs/namei.c:open_last_lookups
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:walk_component
```
```
In fs/readdir.c (ffffffff8138bb1c)
Location: include/linux/fs.h:799
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/libfs.c (ffffffff813a7e25)
Location: include/linux/fs.h:799
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/ext4/dir.c (ffffffff81445ed4)
Location: include/linux/fs.h:799
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/file.c (ffffffff81453d61)
Location: include/linux/fs.h:799
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/fat/dir.c (ffffffff814ce950)
Location: include/linux/fs.h:799
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_ioctl_readdir
```
```
In fs/fat/file.c (ffffffff814d1d26)
Location: include/linux/fs.h:799
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/fuse/dax.c (ffffffff814fbead)
Location: include/linux/fs.h:799
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_read_iter
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
In fs/namei.c (ffffffff814068c0)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/namei.c:open_last_lookups
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:walk_component
```
```
In fs/readdir.c (ffffffff8140d079)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/libfs.c (ffffffff8142aa9d)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/ext4/dir.c (ffffffff814c1f30)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/file.c (ffffffff814d0d70)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/inode.c (ffffffff814e011a)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_bmap
```
```
In fs/fat/dir.c (ffffffff8155b1ce)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_ioctl_readdir
```
```
In fs/fat/file.c (ffffffff8155ea46)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/fuse/dax.c (ffffffff8158c3fc)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_read_iter
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
In fs/namei.c (ffffffff81490bfb)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/namei.c:open_last_lookups
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:walk_component
```
```
In fs/readdir.c (ffffffff81497b19)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/libfs.c (ffffffff814b922d)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/ext4/dir.c (ffffffff8155a19f)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/file.c (ffffffff81569790)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/inode.c (ffffffff815793ca)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_bmap
```
```
In fs/fat/dir.c (ffffffff815fbfde)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_ioctl_readdir
```
```
In fs/fat/file.c (ffffffff81600c46)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/fuse/file.c (ffffffff81628712)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
```
In fs/fuse/dax.c (ffffffff81632c5c)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_read_iter
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
In fs/namei.c (ffffffff814c6539)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/namei.c:open_last_lookups
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:walk_component
```
```
In fs/readdir.c (ffffffff814ccaed)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/libfs.c (ffffffff814ecd80)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/ext4/dir.c (ffffffff81591f97)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/file.c (ffffffff815a14c9)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/inode.c (ffffffff815b0889)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_bmap
```
```
In fs/fat/dir.c (ffffffff81633f6e)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_ioctl_readdir
```
```
In fs/fat/file.c (ffffffff81638b39)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/fuse/file.c (ffffffff8166093c)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
```
In fs/fuse/dax.c (ffffffff8166af0f)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_read_iter
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
In fs/namei.c (ffffffff814f8e2b)
Location: include/linux/fs.h:817
Inline: True
Inline callers:
  - fs/namei.c:open_last_lookups
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:walk_component
```
```
In fs/readdir.c (ffffffff814ff68f)
Location: include/linux/fs.h:817
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/libfs.c (ffffffff81520d41)
Location: include/linux/fs.h:817
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/ext4/dir.c (ffffffff815cad07)
Location: include/linux/fs.h:817
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/file.c (ffffffff815da289)
Location: include/linux/fs.h:817
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_dio_write_checks
  - fs/ext4/file.c:ext4_dio_write_checks
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/inode.c (ffffffff815e9679)
Location: include/linux/fs.h:817
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_bmap
```
```
In fs/fat/dir.c (ffffffff8166d43e)
Location: include/linux/fs.h:817
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_ioctl_readdir
```
```
In fs/fat/file.c (ffffffff81672029)
Location: include/linux/fs.h:817
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/fuse/file.c (ffffffff8169a752)
Location: include/linux/fs.h:817
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:fuse_direct_write_iter
```
```
In fs/fuse/dax.c (ffffffff816a524f)
Location: include/linux/fs.h:817
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_read_iter
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
In fs/namei.c (ffff800010398268)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:lookup_slow
```
```
In fs/readdir.c (ffff80001039f278)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/libfs.c (ffff8000103c175c)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/ext4/dir.c (ffff800010462f74)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/file.c (ffff8000104708fc)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/inode.c (ffff800010487c5c)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/fat/dir.c (ffff8000104e65cc)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_ioctl_readdir
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
In fs/namei.c (c057e86c)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:lookup_slow
```
```
In fs/readdir.c (c05840f4)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/libfs.c (c059cdb0)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/ext4/dir.c (c062330c)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/file.c (c0631ee0)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
```
```
In fs/ext4/inode.c (c0649e1c)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/fat/dir.c (c06a5f48)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_dir_ioctl
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
In fs/namei.c (c000000000492470)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:lookup_slow
```
```
In fs/readdir.c (c000000000499a20)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/libfs.c (c0000000004beac4)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/ext4/dir.c (c00000000057f9b4)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/file.c (c000000000590d04)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/inode.c (c0000000005ae34c)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/fat/dir.c (c0000000006246f8)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_ioctl_readdir
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
In fs/namei.c (ffffffe00026609e)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:lookup_slow
```
```
In fs/readdir.c (ffffffe00026a0f4)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/libfs.c (ffffffe000281a2a)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/ext4/dir.c (ffffffe0002f1612)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/file.c (ffffffe0002fcd06)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/inode.c (ffffffe00030f574)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/fat/dir.c (ffffffe000359106)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_dir_ioctl
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
In fs/namei.c (ffffffff812e709b)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:lookup_slow
```
```
In fs/readdir.c (ffffffff812ec273)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/libfs.c (ffffffff8130547d)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/ext4/dir.c (ffffffff81388c8b)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/file.c (ffffffff81395a01)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/inode.c (ffffffff813aba21)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/fat/dir.c (ffffffff813ffe70)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_ioctl_readdir
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
In fs/namei.c (ffffffff812d7cdb)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:lookup_slow
```
```
In fs/readdir.c (ffffffff812dcea3)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/libfs.c (ffffffff812f609d)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/ext4/dir.c (ffffffff8137971b)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/file.c (ffffffff81386491)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/inode.c (ffffffff8139c4b1)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/fat/dir.c (ffffffff813f08f0)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_ioctl_readdir
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
In fs/namei.c (ffffffff812e4eab)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:lookup_slow
```
```
In fs/readdir.c (ffffffff812ea083)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/libfs.c (ffffffff8130326d)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/ext4/dir.c (ffffffff813865eb)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/file.c (ffffffff81393361)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/inode.c (ffffffff813a9281)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/fat/dir.c (ffffffff813fd1f0)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_ioctl_readdir
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
In fs/namei.c (ffffffff812f5e2b)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:lookup_slow
```
```
In fs/readdir.c (ffffffff812fb073)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/libfs.c (ffffffff813142f3)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/ext4/dir.c (ffffffff8139a2d5)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/file.c (ffffffff813a73f1)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/inode.c (ffffffff813bdb31)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/fat/dir.c (ffffffff81412e20)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_ioctl_readdir
```
</details>
</li>
</ul>

## Differences
