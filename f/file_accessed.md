# Function: <code>file_accessed</code>

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
In mm/filemap.c (ffffffff8118d36c)
Location: include/linux/fs.h:1931
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_readonly_mmap
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
```
```
In mm/shmem.c (ffffffff811a704a)
Location: include/linux/fs.h:1931
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mmap
  - mm/shmem.c:shmem_file_splice_read
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/pipe.c (ffffffff8121538e)
Location: include/linux/fs.h:1931
Inline: True
Inline callers:
  - fs/pipe.c:pipe_read
```
```
In fs/readdir.c (ffffffff8122044b)
Location: include/linux/fs.h:1931
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/splice.c (ffffffff8123dd9e)
Location: include/linux/fs.h:1931
Inline: True
Inline callers:
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:generic_file_splice_read
```
```
In fs/ext4/file.c (ffffffff81292a67)
Location: include/linux/fs.h:1931
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff812f3b36)
Location: include/linux/fs.h:1931
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fuse/file.c (ffffffff8131551f)
Location: include/linux/fs.h:1931
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_mmap
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
In mm/filemap.c (ffffffff8119ffa9)
Location: include/linux/fs.h:2024
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_readonly_mmap
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
```
```
In mm/shmem.c (ffffffff811c1a47)
Location: include/linux/fs.h:2024
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_splice_read
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/pipe.c (ffffffff8123c214)
Location: include/linux/fs.h:2024
Inline: True
Inline callers:
  - fs/pipe.c:pipe_read
```
```
In fs/readdir.c (ffffffff81247f81)
Location: include/linux/fs.h:2024
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/splice.c (ffffffff81265e6e)
Location: include/linux/fs.h:2024
Inline: True
Inline callers:
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:generic_file_splice_read
```
```
In fs/ext4/file.c (ffffffff812bffda)
Location: include/linux/fs.h:2024
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff81327056)
Location: include/linux/fs.h:2024
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fuse/file.c (ffffffff81349d6f)
Location: include/linux/fs.h:2024
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_mmap
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
In mm/filemap.c (ffffffff811af5a9)
Location: include/linux/fs.h:1996
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_readonly_mmap
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
```
```
In mm/shmem.c (ffffffff811d349f)
Location: include/linux/fs.h:1996
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/pipe.c (ffffffff8124ef76)
Location: include/linux/fs.h:1996
Inline: True
Inline callers:
  - fs/pipe.c:pipe_read
```
```
In fs/readdir.c (ffffffff8125afc1)
Location: include/linux/fs.h:1996
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/splice.c (ffffffff8127980a)
Location: include/linux/fs.h:1996
Inline: True
Inline callers:
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:generic_file_splice_read
```
```
In fs/ext4/file.c (ffffffff812d51ea)
Location: include/linux/fs.h:1996
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff8133cdc6)
Location: include/linux/fs.h:1996
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fuse/file.c (ffffffff8135f6af)
Location: include/linux/fs.h:1996
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_mmap
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
In mm/filemap.c (ffffffff811b64a9)
Location: include/linux/fs.h:2046
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_readonly_mmap
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
```
```
In mm/shmem.c (ffffffff811dbd79)
Location: include/linux/fs.h:2046
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/pipe.c (ffffffff8125aea1)
Location: include/linux/fs.h:2046
Inline: True
Inline callers:
  - fs/pipe.c:pipe_read
```
```
In fs/readdir.c (ffffffff812679bf)
Location: include/linux/fs.h:2046
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/splice.c (ffffffff81286d68)
Location: include/linux/fs.h:2046
Inline: True
Inline callers:
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:generic_file_splice_read
```
```
In fs/ext4/file.c (ffffffff812f13f0)
Location: include/linux/fs.h:2046
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/hugetlbfs/inode.c (ffffffff813519b0)
Location: include/linux/fs.h:2046
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fuse/file.c (ffffffff8137424f)
Location: include/linux/fs.h:2046
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_mmap
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
In mm/filemap.c (ffffffff811ca7b9)
Location: include/linux/fs.h:2076
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_readonly_mmap
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
```
```
In mm/shmem.c (ffffffff811f1ba5)
Location: include/linux/fs.h:2076
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/pipe.c (ffffffff8127d248)
Location: include/linux/fs.h:2076
Inline: True
Inline callers:
  - fs/pipe.c:pipe_read
```
```
In fs/readdir.c (ffffffff8128a241)
Location: include/linux/fs.h:2076
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/splice.c (ffffffff812a9561)
Location: include/linux/fs.h:2076
Inline: True
Inline callers:
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:generic_file_splice_read
```
```
In fs/ext4/file.c (ffffffff81315fb0)
Location: include/linux/fs.h:2076
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/hugetlbfs/inode.c (ffffffff813764e8)
Location: include/linux/fs.h:2076
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fuse/file.c (ffffffff81398fcf)
Location: include/linux/fs.h:2076
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_mmap
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
In mm/filemap.c (ffffffff811eb86c)
Location: include/linux/fs.h:2092
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_readonly_mmap
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/shmem.c (ffffffff81212091)
Location: include/linux/fs.h:2092
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/pipe.c (ffffffff812a41e7)
Location: include/linux/fs.h:2092
Inline: True
Inline callers:
  - fs/pipe.c:pipe_read
```
```
In fs/readdir.c (ffffffff812b05c8)
Location: include/linux/fs.h:2092
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/splice.c (ffffffff812d005e)
Location: include/linux/fs.h:2092
Inline: True
Inline callers:
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:generic_file_splice_read
```
```
In fs/ext4/file.c (ffffffff81343c2a)
Location: include/linux/fs.h:2092
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/hugetlbfs/inode.c (ffffffff813a4df8)
Location: include/linux/fs.h:2092
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fuse/file.c (ffffffff813c8abf)
Location: include/linux/fs.h:2092
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_mmap
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
In mm/filemap.c (ffffffff811fc3ec)
Location: include/linux/fs.h:2178
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_readonly_mmap
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/shmem.c (ffffffff8122623e)
Location: include/linux/fs.h:2178
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/pipe.c (ffffffff812b9327)
Location: include/linux/fs.h:2178
Inline: True
Inline callers:
  - fs/pipe.c:pipe_read
```
```
In fs/readdir.c (ffffffff812c5722)
Location: include/linux/fs.h:2178
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/splice.c (ffffffff812e5492)
Location: include/linux/fs.h:2178
Inline: True
Inline callers:
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:generic_file_splice_read
```
```
In fs/ext4/file.c (ffffffff8135bd6a)
Location: include/linux/fs.h:2178
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/hugetlbfs/inode.c (ffffffff813bdbf8)
Location: include/linux/fs.h:2178
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fuse/file.c (ffffffff813e1ccf)
Location: include/linux/fs.h:2178
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_mmap
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
In mm/filemap.c (ffffffff81213aac)
Location: include/linux/fs.h:2185
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_readonly_mmap
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/shmem.c (ffffffff81235bf9)
Location: include/linux/fs.h:2185
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/pipe.c (ffffffff812d5f70)
Location: include/linux/fs.h:2185
Inline: True
Inline callers:
  - fs/pipe.c:pipe_read
```
```
In fs/readdir.c (ffffffff812e21a3)
Location: include/linux/fs.h:2185
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/splice.c (ffffffff81303c51)
Location: include/linux/fs.h:2185
Inline: True
Inline callers:
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:generic_file_splice_read
```
```
In fs/ext4/file.c (ffffffff81384e27)
Location: include/linux/fs.h:2185
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/hugetlbfs/inode.c (ffffffff813e84eb)
Location: include/linux/fs.h:2185
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fuse/file.c (ffffffff81410d34)
Location: include/linux/fs.h:2185
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
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
In mm/filemap.c (ffffffff8122127c)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_readonly_mmap
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/shmem.c (ffffffff81243e39)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/pipe.c (ffffffff812e7ae0)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - fs/pipe.c:pipe_read
```
```
In fs/readdir.c (ffffffff812f3c73)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/splice.c (ffffffff81316cd2)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:generic_file_splice_read
```
```
In fs/ext4/file.c (ffffffff8139d897)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/hugetlbfs/inode.c (ffffffff8140258b)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fuse/file.c (ffffffff8142a93a)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
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
In mm/filemap.c (ffffffff8124e95c)
Location: include/linux/fs.h:2253
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_readonly_mmap
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/shmem.c (ffffffff8126f5c9)
Location: include/linux/fs.h:2253
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_mmap
```
```
In fs/pipe.c (ffffffff8131f2a1)
Location: include/linux/fs.h:2253
Inline: True
Inline callers:
  - fs/pipe.c:pipe_read
```
```
In fs/readdir.c (ffffffff8132c432)
Location: include/linux/fs.h:2253
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/splice.c (ffffffff813520cb)
Location: include/linux/fs.h:2253
Inline: True
Inline callers:
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:generic_file_splice_read
```
```
In fs/ext4/file.c (ffffffff813e9828)
Location: include/linux/fs.h:2253
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_mmap
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/hugetlbfs/inode.c (ffffffff814500eb)
Location: include/linux/fs.h:2253
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fuse/file.c (ffffffff8147ab7e)
Location: include/linux/fs.h:2253
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
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
In mm/filemap.c (ffffffff81258dcc)
Location: include/linux/fs.h:2222
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_readonly_mmap
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/shmem.c (ffffffff8127a936)
Location: include/linux/fs.h:2222
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_mmap
```
```
In fs/pipe.c (ffffffff8132a7d1)
Location: include/linux/fs.h:2222
Inline: True
Inline callers:
  - fs/pipe.c:pipe_read
```
```
In fs/readdir.c (ffffffff81337a0c)
Location: include/linux/fs.h:2222
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/splice.c (ffffffff8135d14b)
Location: include/linux/fs.h:2222
Inline: True
Inline callers:
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:generic_file_splice_read
```
```
In fs/ext4/file.c (ffffffff813fb928)
Location: include/linux/fs.h:2222
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_mmap
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/hugetlbfs/inode.c (ffffffff8146c5fb)
Location: include/linux/fs.h:2222
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fuse/file.c (ffffffff81495807)
Location: include/linux/fs.h:2222
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_mmap
```
```
In fs/fuse/dax.c (ffffffff8149e025)
Location: include/linux/fs.h:2222
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_mmap
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
In mm/filemap.c (ffffffff8125d3ac)
Location: include/linux/fs.h:2453
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_readonly_mmap
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:filemap_read
```
```
In mm/shmem.c (ffffffff8127fa7a)
Location: include/linux/fs.h:2453
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/pipe.c (ffffffff81330787)
Location: include/linux/fs.h:2453
Inline: True
Inline callers:
  - fs/pipe.c:pipe_read
```
```
In fs/readdir.c (ffffffff8133e16c)
Location: include/linux/fs.h:2453
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/splice.c (ffffffff81363bf1)
Location: include/linux/fs.h:2453
Inline: True
Inline callers:
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:generic_file_splice_read
```
```
In fs/ext4/file.c (ffffffff81401c23)
Location: include/linux/fs.h:2453
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_mmap
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/hugetlbfs/inode.c (ffffffff814723e4)
Location: include/linux/fs.h:2453
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fuse/file.c (ffffffff8149a864)
Location: include/linux/fs.h:2453
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_mmap
```
```
In fs/fuse/dax.c (ffffffff814a3ff5)
Location: include/linux/fs.h:2453
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_mmap
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
In mm/filemap.c (ffffffff812992ff)
Location: include/linux/fs.h:2509
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_readonly_mmap
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:filemap_read
```
```
In mm/shmem.c (ffffffff812bdda8)
Location: include/linux/fs.h:2509
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/pipe.c (ffffffff8137df5f)
Location: include/linux/fs.h:2509
Inline: True
Inline callers:
  - fs/pipe.c:pipe_read
```
```
In fs/readdir.c (ffffffff8138bafc)
Location: include/linux/fs.h:2509
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/splice.c (ffffffff813b23e1)
Location: include/linux/fs.h:2509
Inline: True
Inline callers:
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:generic_file_splice_read
```
```
In fs/ext4/file.c (ffffffff81454393)
Location: include/linux/fs.h:2509
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_mmap
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/hugetlbfs/inode.c (ffffffff814c8be0)
Location: include/linux/fs.h:2509
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fuse/file.c (ffffffff814f22bf)
Location: include/linux/fs.h:2509
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_mmap
```
```
In fs/fuse/dax.c (ffffffff814fc095)
Location: include/linux/fs.h:2509
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_mmap
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
In mm/filemap.c (ffffffff812ef96f)
Location: include/linux/fs.h:2383
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_readonly_mmap
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:filemap_read
```
```
In mm/shmem.c (ffffffff8131b694)
Location: include/linux/fs.h:2383
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_mmap
```
```
In fs/pipe.c (ffffffff813fd762)
Location: include/linux/fs.h:2383
Inline: True
Inline callers:
  - fs/pipe.c:pipe_read
```
```
In fs/readdir.c (ffffffff8140d059)
Location: include/linux/fs.h:2383
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/splice.c (ffffffff814373fb)
Location: include/linux/fs.h:2383
Inline: True
Inline callers:
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:generic_file_splice_read
```
```
In fs/ext4/file.c (ffffffff814d1acf)
Location: include/linux/fs.h:2383
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_mmap
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/hugetlbfs/inode.c (ffffffff8155425a)
Location: include/linux/fs.h:2383
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fuse/file.c (ffffffff81581b79)
Location: include/linux/fs.h:2383
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_mmap
```
```
In fs/fuse/dax.c (ffffffff8158c615)
Location: include/linux/fs.h:2383
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_mmap
```
```
In block/fops.c (ffffffff81670db1)
Location: include/linux/fs.h:2383
Inline: True
Inline callers:
  - block/fops.c:blkdev_read_iter
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
In mm/filemap.c (ffffffff8135a3af)
Location: include/linux/fs.h:2516
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_readonly_mmap
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:filemap_read
```
```
In mm/shmem.c (ffffffff8138f3d9)
Location: include/linux/fs.h:2516
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_mmap
```
```
In fs/pipe.c (ffffffff81487352)
Location: include/linux/fs.h:2516
Inline: True
Inline callers:
  - fs/pipe.c:pipe_read
```
```
In fs/readdir.c (ffffffff81497af9)
Location: include/linux/fs.h:2516
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/splice.c (ffffffff814c54e8)
Location: include/linux/fs.h:2516
Inline: True
Inline callers:
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:generic_file_splice_read
```
```
In fs/ext4/file.c (ffffffff8156a538)
Location: include/linux/fs.h:2516
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_mmap
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/hugetlbfs/inode.c (ffffffff815f5b24)
Location: include/linux/fs.h:2516
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fuse/file.c (ffffffff816279f9)
Location: include/linux/fs.h:2516
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_mmap
```
```
In fs/fuse/dax.c (ffffffff81632ec5)
Location: include/linux/fs.h:2516
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_mmap
```
```
In block/fops.c (ffffffff8172c4e1)
Location: include/linux/fs.h:2516
Inline: True
Inline callers:
  - block/fops.c:blkdev_read_iter
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
In mm/filemap.c (ffffffff8138c01a)
Location: include/linux/fs.h:2205
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_readonly_mmap
  - mm/filemap.c:filemap_splice_read
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:filemap_read
```
```
In mm/shmem.c (ffffffff813c099d)
Location: include/linux/fs.h:2205
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_splice_read
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_mmap
```
```
In fs/pipe.c (ffffffff814bc14d)
Location: include/linux/fs.h:2205
Inline: True
Inline callers:
  - fs/pipe.c:pipe_read
```
```
In fs/readdir.c (ffffffff814ccad8)
Location: include/linux/fs.h:2205
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/splice.c (ffffffff814faca4)
Location: include/linux/fs.h:2205
Inline: True
Inline callers:
  - fs/splice.c:splice_direct_to_actor
```
```
In fs/ext4/file.c (ffffffff815a26c2)
Location: include/linux/fs.h:2205
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_mmap
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/hugetlbfs/inode.c (ffffffff8162e386)
Location: include/linux/fs.h:2205
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fuse/file.c (ffffffff8165fdcf)
Location: include/linux/fs.h:2205
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_mmap
```
```
In fs/fuse/dax.c (ffffffff8166b185)
Location: include/linux/fs.h:2205
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_mmap
```
```
In block/fops.c (ffffffff817685d4)
Location: include/linux/fs.h:2205
Inline: True
Inline callers:
  - block/fops.c:blkdev_read_iter
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
In mm/filemap.c (ffffffff813b5b8a)
Location: include/linux/fs.h:2433
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_readonly_mmap
  - mm/filemap.c:filemap_splice_read
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:filemap_read
```
```
In mm/shmem.c (ffffffff813eb627)
Location: include/linux/fs.h:2433
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_splice_read
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_mmap
```
```
In fs/pipe.c (ffffffff814ee66a)
Location: include/linux/fs.h:2433
Inline: True
Inline callers:
  - fs/pipe.c:pipe_read
```
```
In fs/readdir.c (ffffffff814ff685)
Location: include/linux/fs.h:2433
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/splice.c (ffffffff8152f794)
Location: include/linux/fs.h:2433
Inline: True
Inline callers:
  - fs/splice.c:splice_direct_to_actor
```
```
In fs/ext4/file.c (ffffffff815db1d2)
Location: include/linux/fs.h:2433
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_mmap
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/hugetlbfs/inode.c (ffffffff81667836)
Location: include/linux/fs.h:2433
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fuse/file.c (ffffffff81699c2f)
Location: include/linux/fs.h:2433
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_mmap
```
```
In fs/fuse/dax.c (ffffffff816a54c5)
Location: include/linux/fs.h:2433
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_mmap
```
```
In block/fops.c (ffffffff817aa514)
Location: include/linux/fs.h:2433
Inline: True
Inline callers:
  - block/fops.c:blkdev_read_iter
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
In mm/filemap.c (ffff8000102adf40)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_readonly_mmap
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/shmem.c (ffff8000102d6028)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/pipe.c (ffff8000103907ec)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - fs/pipe.c:pipe_read
```
```
In fs/readdir.c (ffff80001039f264)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/splice.c (ffff8000103cd70c)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:generic_file_splice_read
```
```
In fs/ext4/file.c (ffff800010470dec)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/hugetlbfs/inode.c (ffff8000104e094c)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fuse/file.c (ffff80001050e894)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
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
In mm/filemap.c (c04db434)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_readonly_mmap
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/shmem.c (c04fe364)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_mmap
```
```
In fs/pipe.c (c05772f8)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - fs/pipe.c:pipe_read
```
```
In fs/readdir.c (c05840dc)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/splice.c (c05a927c)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:generic_file_splice_read
```
```
In fs/ext4/file.c (c0631e14)
Location: include/linux/fs.h:2220
Inline: True
```
```
In fs/fuse/file.c (c06ca040)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
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
In mm/filemap.c (c000000000362edc)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_readonly_mmap
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/shmem.c (c00000000039616c)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/pipe.c (c0000000004885b0)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - fs/pipe.c:pipe_read
```
```
In fs/readdir.c (c000000000499974)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/splice.c (c0000000004cf63c)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:generic_file_splice_read
```
```
In fs/ext4/file.c (c000000000591510)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/hugetlbfs/inode.c (c00000000061d400)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fuse/file.c (c000000000655a9c)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
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
In mm/filemap.c (ffffffe0001d4afe)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_readonly_mmap
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/shmem.c (ffffffe0001f1980)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_mmap
```
```
In fs/pipe.c (ffffffe0002600e8)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - fs/pipe.c:pipe_read
```
```
In fs/readdir.c (ffffffe00026a0de)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/splice.c (ffffffe00028a9f6)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:generic_file_splice_read
```
```
In fs/ext4/file.c (ffffffe0002fd13a)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/hugetlbfs/inode.c (ffffffe000354bc6)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fuse/file.c (ffffffe00037945e)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
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
In mm/filemap.c (ffffffff812198cc)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_readonly_mmap
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/shmem.c (ffffffff8123c489)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/pipe.c (ffffffff812e00c0)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - fs/pipe.c:pipe_read
```
```
In fs/readdir.c (ffffffff812ec253)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/splice.c (ffffffff8130f2b2)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:generic_file_splice_read
```
```
In fs/ext4/file.c (ffffffff81395e77)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/hugetlbfs/inode.c (ffffffff813fab6b)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fuse/file.c (ffffffff81422f1a)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
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
In mm/filemap.c (ffffffff8120cadc)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_readonly_mmap
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/shmem.c (ffffffff8122f489)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/pipe.c (ffffffff812d0d00)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - fs/pipe.c:pipe_read
```
```
In fs/readdir.c (ffffffff812dce83)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/splice.c (ffffffff812ffec2)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:generic_file_splice_read
```
```
In fs/ext4/file.c (ffffffff81386907)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/hugetlbfs/inode.c (ffffffff813eb5eb)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fuse/file.c (ffffffff8141399a)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
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
In mm/filemap.c (ffffffff8121766c)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_readonly_mmap
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/shmem.c (ffffffff8123a229)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/pipe.c (ffffffff812dded0)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - fs/pipe.c:pipe_read
```
```
In fs/readdir.c (ffffffff812ea063)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/splice.c (ffffffff8130d0a2)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:generic_file_splice_read
```
```
In fs/ext4/file.c (ffffffff813937d7)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/hugetlbfs/inode.c (ffffffff813f7eeb)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fuse/file.c (ffffffff8141f0ba)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
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
In mm/filemap.c (ffffffff8122671c)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_readonly_mmap
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/shmem.c (ffffffff81249914)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/pipe.c (ffffffff812eee50)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - fs/pipe.c:pipe_read
```
```
In fs/readdir.c (ffffffff812fb053)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/splice.c (ffffffff8131e892)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:generic_file_splice_read
```
```
In fs/ext4/file.c (ffffffff813a7867)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/hugetlbfs/inode.c (ffffffff8140dc3b)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fuse/file.c (ffffffff81435e3a)
Location: include/linux/fs.h:2220
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
```
</details>
</li>
</ul>

## Differences
