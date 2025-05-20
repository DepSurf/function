# Function: <code>inode_lock_shared</code>

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
In fs/namei.c (ffffffff812425c2)
Location: include/linux/fs.h:745
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:lookup_slow
```
```
In fs/readdir.c (ffffffff81247e8e)
Location: include/linux/fs.h:745
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/libfs.c (ffffffff8125cf0f)
Location: include/linux/fs.h:745
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/ext4/dir.c (ffffffff812be6b6)
Location: include/linux/fs.h:745
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/fat/dir.c (ffffffff8132c585)
Location: include/linux/fs.h:745
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
In fs/namei.c (ffffffff812554b7)
Location: include/linux/fs.h:698
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:lookup_slow
```
```
In fs/readdir.c (ffffffff8125aece)
Location: include/linux/fs.h:698
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/libfs.c (ffffffff8127044f)
Location: include/linux/fs.h:698
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/ext4/dir.c (ffffffff812d3d2a)
Location: include/linux/fs.h:698
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/file.c (ffffffff812d529e)
Location: include/linux/fs.h:698
Inline: True
```
```
In fs/ext4/inode.c (ffffffff812e18e7)
Location: include/linux/fs.h:698
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/fat/dir.c (ffffffff813422c5)
Location: include/linux/fs.h:698
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
In fs/namei.c (ffffffff81261474)
Location: include/linux/fs.h:717
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:lookup_slow
```
```
In fs/readdir.c (ffffffff812678bc)
Location: include/linux/fs.h:717
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/libfs.c (ffffffff8127db6f)
Location: include/linux/fs.h:717
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/ext4/dir.c (ffffffff812e5707)
Location: include/linux/fs.h:717
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/file.c (ffffffff812f13be)
Location: include/linux/fs.h:717
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/inode.c (ffffffff81305cfd)
Location: include/linux/fs.h:717
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/fat/dir.c (ffffffff81356ac7)
Location: include/linux/fs.h:717
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
In fs/namei.c (ffffffff81283b9b)
Location: include/linux/fs.h:721
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:lookup_slow
```
```
In fs/libfs.c (ffffffff812a061f)
Location: include/linux/fs.h:721
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/ext4/dir.c (ffffffff8130a134)
Location: include/linux/fs.h:721
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/file.c (ffffffff8131596d)
Location: include/linux/fs.h:721
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/inode.c (ffffffff8132a84d)
Location: include/linux/fs.h:721
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/fat/dir.c (ffffffff8137b707)
Location: include/linux/fs.h:721
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
In fs/namei.c (ffffffff812aad63)
Location: include/linux/fs.h:723
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:lookup_slow
```
```
In fs/libfs.c (ffffffff812c720d)
Location: include/linux/fs.h:723
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/ext4/dir.c (ffffffff8133803c)
Location: include/linux/fs.h:723
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/file.c (ffffffff813437a6)
Location: include/linux/fs.h:723
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/inode.c (ffffffff81358bf1)
Location: include/linux/fs.h:723
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/fat/dir.c (ffffffff813aa129)
Location: include/linux/fs.h:723
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
In fs/namei.c (ffffffff812c0024)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:lookup_slow
```
```
In fs/libfs.c (ffffffff812dc37d)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/ext4/dir.c (ffffffff8134f2cd)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/file.c (ffffffff8135b8e6)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/inode.c (ffffffff81370f20)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/fat/dir.c (ffffffff813c2f09)
Location: include/linux/fs.h:771
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
In fs/namei.c (ffffffff812dcf8b)
Location: include/linux/fs.h:786
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:lookup_slow
```
```
In fs/libfs.c (ffffffff812faa3c)
Location: include/linux/fs.h:786
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/ext4/dir.c (ffffffff8137831a)
Location: include/linux/fs.h:786
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/file.c (ffffffff81384979)
Location: include/linux/fs.h:786
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/inode.c (ffffffff8139a8dd)
Location: include/linux/fs.h:786
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/fat/dir.c (ffffffff813ed75a)
Location: include/linux/fs.h:786
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
In fs/namei.c (ffffffff812eea99)
Location: include/linux/fs.h:800
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:lookup_slow
```
```
In fs/libfs.c (ffffffff8130ce30)
Location: include/linux/fs.h:800
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/ext4/dir.c (ffffffff813906ba)
Location: include/linux/fs.h:800
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/file.c (ffffffff8139d3f9)
Location: include/linux/fs.h:800
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/inode.c (ffffffff813b353c)
Location: include/linux/fs.h:800
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/fat/dir.c (ffffffff8140787a)
Location: include/linux/fs.h:800
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
In fs/namei.c (ffffffff813262c6)
Location: include/linux/fs.h:818
Inline: True
Inline callers:
  - fs/namei.c:open_last_lookups
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:walk_component
```
```
In fs/libfs.c (ffffffff81346850)
Location: include/linux/fs.h:818
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/ext4/dir.c (ffffffff813dbcc0)
Location: include/linux/fs.h:818
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/file.c (ffffffff813e9629)
Location: include/linux/fs.h:818
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/fat/dir.c (ffffffff81455373)
Location: include/linux/fs.h:818
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
In fs/namei.c (ffffffff81331720)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - fs/namei.c:open_last_lookups
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:walk_component
```
```
In fs/libfs.c (ffffffff81352d40)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/ext4/dir.c (ffffffff813ed774)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/file.c (ffffffff813fb2d9)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/fat/dir.c (ffffffff81471813)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_ioctl_readdir
```
```
In fs/fat/file.c (ffffffff81474c81)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/fuse/dax.c (ffffffff8149de6d)
Location: include/linux/fs.h:781
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
In fs/namei.c (ffffffff813380e0)
Location: include/linux/fs.h:782
Inline: True
Inline callers:
  - fs/namei.c:open_last_lookups
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:walk_component
```
```
In fs/libfs.c (ffffffff81359910)
Location: include/linux/fs.h:782
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/ext4/dir.c (ffffffff813f3df0)
Location: include/linux/fs.h:782
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/file.c (ffffffff814017a9)
Location: include/linux/fs.h:782
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/fat/dir.c (ffffffff8147721a)
Location: include/linux/fs.h:782
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_ioctl_readdir
```
```
In fs/fat/file.c (ffffffff8147a664)
Location: include/linux/fs.h:782
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/fuse/dax.c (ffffffff814a3e3d)
Location: include/linux/fs.h:782
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
In fs/namei.c (ffffffff81385b7c)
Location: include/linux/fs.h:794
Inline: True
Inline callers:
  - fs/namei.c:open_last_lookups
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:walk_component
```
```
In fs/libfs.c (ffffffff813a7db0)
Location: include/linux/fs.h:794
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/ext4/dir.c (ffffffff81445edc)
Location: include/linux/fs.h:794
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/file.c (ffffffff81453d39)
Location: include/linux/fs.h:794
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/fat/dir.c (ffffffff814ce93a)
Location: include/linux/fs.h:794
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_ioctl_readdir
```
```
In fs/fat/file.c (ffffffff814d1cd4)
Location: include/linux/fs.h:794
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/fuse/dax.c (ffffffff814fbebd)
Location: include/linux/fs.h:794
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
In fs/namei.c (ffffffff8140687b)
Location: include/linux/fs.h:749
Inline: True
Inline callers:
  - fs/namei.c:open_last_lookups
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:walk_component
```
```
In fs/libfs.c (ffffffff8142aa2b)
Location: include/linux/fs.h:749
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/ext4/dir.c (ffffffff814c1f38)
Location: include/linux/fs.h:749
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/file.c (ffffffff814d0d49)
Location: include/linux/fs.h:749
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/inode.c (ffffffff814e00a8)
Location: include/linux/fs.h:749
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_bmap
```
```
In fs/fat/dir.c (ffffffff8155b1b9)
Location: include/linux/fs.h:749
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_ioctl_readdir
```
```
In fs/fat/file.c (ffffffff8155e9f4)
Location: include/linux/fs.h:749
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/fuse/dax.c (ffffffff8158c415)
Location: include/linux/fs.h:749
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
In fs/namei.c (ffffffff81490bb6)
Location: include/linux/fs.h:764
Inline: True
Inline callers:
  - fs/namei.c:open_last_lookups
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:walk_component
```
```
In fs/libfs.c (ffffffff814b91bb)
Location: include/linux/fs.h:764
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/ext4/dir.c (ffffffff8155a1a7)
Location: include/linux/fs.h:764
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/file.c (ffffffff81569769)
Location: include/linux/fs.h:764
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/inode.c (ffffffff81579358)
Location: include/linux/fs.h:764
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_bmap
```
```
In fs/fat/dir.c (ffffffff815fbfc9)
Location: include/linux/fs.h:764
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_ioctl_readdir
```
```
In fs/fat/file.c (ffffffff81600bf4)
Location: include/linux/fs.h:764
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/fuse/file.c (ffffffff81628742)
Location: include/linux/fs.h:764
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_write_iter
```
```
In fs/fuse/dax.c (ffffffff81632c75)
Location: include/linux/fs.h:764
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
In fs/namei.c (ffffffff814c63e6)
Location: include/linux/fs.h:779
Inline: True
Inline callers:
  - fs/namei.c:open_last_lookups
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:walk_component
```
```
In fs/libfs.c (ffffffff814ecd16)
Location: include/linux/fs.h:779
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/ext4/dir.c (ffffffff81591fa7)
Location: include/linux/fs.h:779
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/file.c (ffffffff815a14a2)
Location: include/linux/fs.h:779
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/inode.c (ffffffff815b0858)
Location: include/linux/fs.h:779
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_bmap
```
```
In fs/fat/dir.c (ffffffff81633f59)
Location: include/linux/fs.h:779
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_ioctl_readdir
```
```
In fs/fat/file.c (ffffffff81638ae7)
Location: include/linux/fs.h:779
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/fuse/file.c (ffffffff81660968)
Location: include/linux/fs.h:779
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_write_iter
```
```
In fs/fuse/dax.c (ffffffff8166af28)
Location: include/linux/fs.h:779
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
In fs/namei.c (ffffffff814f8cd8)
Location: include/linux/fs.h:812
Inline: True
Inline callers:
  - fs/namei.c:open_last_lookups
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:walk_component
```
```
In fs/libfs.c (ffffffff81520c86)
Location: include/linux/fs.h:812
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/ext4/dir.c (ffffffff815cad17)
Location: include/linux/fs.h:812
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/file.c (ffffffff815da262)
Location: include/linux/fs.h:812
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/inode.c (ffffffff815e9648)
Location: include/linux/fs.h:812
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_bmap
```
```
In fs/fat/dir.c (ffffffff8166d429)
Location: include/linux/fs.h:812
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_ioctl_readdir
```
```
In fs/fat/file.c (ffffffff81671fd7)
Location: include/linux/fs.h:812
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/fuse/file.c (ffffffff8169a7b4)
Location: include/linux/fs.h:812
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_write_iter
```
```
In fs/fuse/dax.c (ffffffff816a5268)
Location: include/linux/fs.h:812
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
In fs/namei.c (ffff80001039823c)
Location: include/linux/fs.h:800
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:lookup_slow
```
```
In fs/libfs.c (ffff8000103c16e0)
Location: include/linux/fs.h:800
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/ext4/dir.c (ffff800010462f80)
Location: include/linux/fs.h:800
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/file.c (ffff8000104708d8)
Location: include/linux/fs.h:800
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/inode.c (ffff800010487da0)
Location: include/linux/fs.h:800
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/fat/dir.c (ffff8000104e65ac)
Location: include/linux/fs.h:800
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
In fs/namei.c (c057e844)
Location: include/linux/fs.h:800
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:lookup_slow
```
```
In fs/libfs.c (c059cd48)
Location: include/linux/fs.h:800
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/ext4/dir.c (c0623318)
Location: include/linux/fs.h:800
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/file.c (c0631ea8)
Location: include/linux/fs.h:800
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
```
```
In fs/ext4/inode.c (c0649ee4)
Location: include/linux/fs.h:800
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/fat/dir.c (c06a5efc)
Location: include/linux/fs.h:800
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
In fs/namei.c (c000000000492444)
Location: include/linux/fs.h:800
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:lookup_slow
```
```
In fs/libfs.c (c0000000004bea44)
Location: include/linux/fs.h:800
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/ext4/dir.c (c00000000057f9c0)
Location: include/linux/fs.h:800
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/file.c (c000000000590ccc)
Location: include/linux/fs.h:800
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/inode.c (c0000000005ae4d0)
Location: include/linux/fs.h:800
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/fat/dir.c (c0000000006246d8)
Location: include/linux/fs.h:800
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
In fs/namei.c (ffffffe000266080)
Location: include/linux/fs.h:800
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:lookup_slow
```
```
In fs/libfs.c (ffffffe0002819a8)
Location: include/linux/fs.h:800
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/ext4/dir.c (ffffffe0002f18a6)
Location: include/linux/fs.h:800
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/file.c (ffffffe0002fcce2)
Location: include/linux/fs.h:800
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/inode.c (ffffffe00030f742)
Location: include/linux/fs.h:800
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/fat/dir.c (ffffffe0003590c2)
Location: include/linux/fs.h:800
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
In fs/namei.c (ffffffff812e7079)
Location: include/linux/fs.h:800
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:lookup_slow
```
```
In fs/libfs.c (ffffffff81305410)
Location: include/linux/fs.h:800
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/ext4/dir.c (ffffffff81388c9a)
Location: include/linux/fs.h:800
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/file.c (ffffffff813959d9)
Location: include/linux/fs.h:800
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/inode.c (ffffffff813abb1c)
Location: include/linux/fs.h:800
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/fat/dir.c (ffffffff813ffe5a)
Location: include/linux/fs.h:800
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
In fs/namei.c (ffffffff812d7cb9)
Location: include/linux/fs.h:800
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:lookup_slow
```
```
In fs/libfs.c (ffffffff812f6030)
Location: include/linux/fs.h:800
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/ext4/dir.c (ffffffff8137972a)
Location: include/linux/fs.h:800
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/file.c (ffffffff81386469)
Location: include/linux/fs.h:800
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/inode.c (ffffffff8139c5ac)
Location: include/linux/fs.h:800
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/fat/dir.c (ffffffff813f08da)
Location: include/linux/fs.h:800
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
In fs/namei.c (ffffffff812e4e89)
Location: include/linux/fs.h:800
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:lookup_slow
```
```
In fs/libfs.c (ffffffff81303200)
Location: include/linux/fs.h:800
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/ext4/dir.c (ffffffff813865fa)
Location: include/linux/fs.h:800
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/file.c (ffffffff81393339)
Location: include/linux/fs.h:800
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/inode.c (ffffffff813a937c)
Location: include/linux/fs.h:800
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/fat/dir.c (ffffffff813fd1da)
Location: include/linux/fs.h:800
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
In fs/namei.c (ffffffff812f5e09)
Location: include/linux/fs.h:800
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:lookup_slow
```
```
In fs/libfs.c (ffffffff81314280)
Location: include/linux/fs.h:800
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/ext4/dir.c (ffffffff8139a2e4)
Location: include/linux/fs.h:800
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/file.c (ffffffff813a73c9)
Location: include/linux/fs.h:800
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/inode.c (ffffffff813bdc59)
Location: include/linux/fs.h:800
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/fat/dir.c (ffffffff81412e0a)
Location: include/linux/fs.h:800
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_ioctl_readdir
```
</details>
</li>
</ul>

## Differences
