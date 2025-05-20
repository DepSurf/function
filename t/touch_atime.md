# Function: <code>touch_atime</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void touch_atime(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81229120)
Location: fs/inode.c:1634
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - mm/filemap.c:generic_file_readonly_mmap
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/shmem.c:shmem_mmap
  - mm/shmem.c:shmem_file_splice_read
  - mm/shmem.c:shmem_file_read_iter
  - fs/stat.c:SyS_readlink
  - fs/pipe.c:pipe_read
  - fs/namei.c:trailing_symlink
  - fs/namei.c:trailing_symlink
  - fs/namei.c:link_path_walk
  - fs/namei.c:link_path_walk
  - fs/readdir.c:iterate_dir
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:generic_file_splice_read
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
  - fs/ecryptfs/file.c:ecryptfs_read_update_atime
  - fs/fuse/file.c:fuse_file_mmap
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff81229120-ffffffff812291e8: touch_atime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void touch_atime(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81251830)
Location: fs/inode.c:1651
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
  - mm/filemap.c:generic_file_readonly_mmap
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/shmem.c:shmem_file_splice_read
  - mm/shmem.c:shmem_file_read_iter
  - fs/stat.c:SyS_readlink
  - fs/pipe.c:pipe_read
  - fs/namei.c:trailing_symlink
  - fs/namei.c:trailing_symlink
  - fs/namei.c:link_path_walk
  - fs/namei.c:link_path_walk
  - fs/readdir.c:iterate_dir
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:generic_file_splice_read
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
  - fs/ecryptfs/file.c:ecryptfs_read_update_atime
  - fs/fuse/file.c:fuse_file_mmap
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff81251830-ffffffff812518f8: touch_atime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void touch_atime(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81264a00)
Location: fs/inode.c:1701
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
  - mm/filemap.c:generic_file_readonly_mmap
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - fs/stat.c:SyS_readlink
  - fs/pipe.c:pipe_read
  - fs/namei.c:trailing_symlink
  - fs/namei.c:trailing_symlink
  - fs/namei.c:link_path_walk
  - fs/namei.c:link_path_walk
  - fs/readdir.c:iterate_dir
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:generic_file_splice_read
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
  - fs/ecryptfs/file.c:ecryptfs_read_update_atime
  - fs/fuse/file.c:fuse_file_mmap
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff81264a00-ffffffff81264ac9: touch_atime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void touch_atime(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81272230)
Location: fs/inode.c:1701
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - mm/filemap.c:generic_file_readonly_mmap
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - fs/stat.c:SyS_readlink
  - fs/pipe.c:pipe_read
  - fs/namei.c:trailing_symlink
  - fs/namei.c:trailing_symlink
  - fs/namei.c:link_path_walk
  - fs/namei.c:link_path_walk
  - fs/readdir.c:iterate_dir
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:generic_file_splice_read
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
  - fs/ecryptfs/file.c:ecryptfs_read_update_atime
  - fs/fuse/file.c:fuse_file_mmap
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff81272230-ffffffff812722fb: touch_atime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void touch_atime(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81294b40)
Location: fs/inode.c:1714
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - mm/filemap.c:generic_file_readonly_mmap
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - fs/stat.c:SyS_readlink
  - fs/pipe.c:pipe_read
  - fs/namei.c:trailing_symlink
  - fs/namei.c:trailing_symlink
  - fs/namei.c:link_path_walk
  - fs/namei.c:link_path_walk
  - fs/readdir.c:iterate_dir
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:generic_file_splice_read
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
  - fs/ecryptfs/file.c:ecryptfs_read_update_atime
  - fs/fuse/file.c:fuse_file_mmap
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff81294b40-ffffffff81294c12: touch_atime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void touch_atime(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812bace0)
Location: fs/inode.c:1708
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - mm/filemap.c:generic_file_readonly_mmap
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_buffered_read
  - mm/shmem.c:shmem_file_read_iter
  - fs/stat.c:do_readlinkat
  - fs/pipe.c:pipe_read
  - fs/namei.c:trailing_symlink
  - fs/namei.c:trailing_symlink
  - fs/namei.c:link_path_walk
  - fs/namei.c:link_path_walk
  - fs/readdir.c:iterate_dir
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:generic_file_splice_read
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
  - fs/ecryptfs/file.c:ecryptfs_read_update_atime
  - fs/fuse/file.c:fuse_file_mmap
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff812bace0-ffffffff812badc0: touch_atime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void touch_atime(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812cfed0)
Location: fs/inode.c:1715
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - mm/filemap.c:generic_file_readonly_mmap
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_buffered_read
  - mm/shmem.c:shmem_file_read_iter
  - fs/stat.c:do_readlinkat
  - fs/pipe.c:pipe_read
  - fs/namei.c:trailing_symlink
  - fs/namei.c:trailing_symlink
  - fs/readdir.c:iterate_dir
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:generic_file_splice_read
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
  - fs/ecryptfs/file.c:ecryptfs_read_update_atime
  - fs/fuse/file.c:fuse_file_mmap
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff812cfed0-ffffffff812cffae: touch_atime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void touch_atime(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812ece10)
Location: fs/inode.c:1728
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - mm/filemap.c:generic_file_readonly_mmap
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_buffered_read
  - mm/shmem.c:shmem_file_read_iter
  - fs/stat.c:do_readlinkat
  - fs/pipe.c:pipe_read
  - fs/namei.c:trailing_symlink
  - fs/namei.c:trailing_symlink
  - fs/readdir.c:iterate_dir
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:generic_file_splice_read
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
  - fs/ecryptfs/file.c:ecryptfs_read_update_atime
  - fs/fuse/file.c:__fuse_copy_file_range
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff812ece10-ffffffff812eceee: touch_atime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void touch_atime(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812fe9a0)
Location: fs/inode.c:1739
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - mm/filemap.c:generic_file_readonly_mmap
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_buffered_read
  - mm/shmem.c:shmem_file_read_iter
  - fs/stat.c:do_readlinkat
  - fs/pipe.c:pipe_read
  - fs/namei.c:trailing_symlink
  - fs/namei.c:trailing_symlink
  - fs/readdir.c:iterate_dir
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:generic_file_splice_read
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
  - fs/ecryptfs/file.c:ecryptfs_read_update_atime
  - fs/fuse/file.c:__fuse_copy_file_range
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff812fe9a0-ffffffff812fea7e: touch_atime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void touch_atime(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81337a40)
Location: fs/inode.c:1823
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_do_get
  - mm/filemap.c:generic_file_readonly_mmap
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_buffered_read
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_mmap
  - fs/stat.c:do_readlinkat
  - fs/pipe.c:pipe_read
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/readdir.c:iterate_dir
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:generic_file_splice_read
  - fs/ext4/file.c:ext4_file_mmap
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
  - fs/ecryptfs/file.c:ecryptfs_read_update_atime
  - fs/fuse/file.c:__fuse_copy_file_range
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff81337a40-ffffffff81337b3b: touch_atime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void touch_atime(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81343380)
Location: fs/inode.c:1824
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_do_get
  - mm/filemap.c:generic_file_readonly_mmap
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_buffered_read
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_mmap
  - fs/stat.c:do_readlinkat
  - fs/pipe.c:pipe_read
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/readdir.c:iterate_dir
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:generic_file_splice_read
  - fs/ext4/file.c:ext4_file_mmap
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
  - fs/ecryptfs/file.c:ecryptfs_read_update_atime
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_mmap
  - fs/fuse/dax.c:fuse_dax_mmap
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff81343380-ffffffff813434b8: touch_atime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void touch_atime(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81349670)
Location: fs/inode.c:1832
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - mm/filemap.c:generic_file_readonly_mmap
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:filemap_read
  - mm/shmem.c:shmem_file_read_iter
  - fs/stat.c:do_readlinkat
  - fs/pipe.c:pipe_read
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/readdir.c:iterate_dir
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:generic_file_splice_read
  - fs/ext4/file.c:ext4_file_mmap
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
  - fs/ecryptfs/file.c:ecryptfs_read_update_atime
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_mmap
  - fs/fuse/dax.c:fuse_dax_mmap
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff81349670-ffffffff813497af: touch_atime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void touch_atime(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff813973c0)
Location: fs/inode.c:1837
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - mm/filemap.c:generic_file_readonly_mmap
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:filemap_read
  - mm/shmem.c:shmem_file_read_iter
  - fs/stat.c:do_readlinkat
  - fs/pipe.c:pipe_read
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/readdir.c:iterate_dir
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:generic_file_splice_read
  - fs/ext4/file.c:ext4_file_mmap
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
  - fs/ecryptfs/file.c:ecryptfs_read_update_atime
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_mmap
  - fs/fuse/dax.c:fuse_dax_mmap
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff813973c0-ffffffff813974ff: touch_atime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void touch_atime(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81419560)
Location: fs/inode.c:1918
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - mm/filemap.c:generic_file_readonly_mmap
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:filemap_read
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_mmap
  - fs/stat.c:do_readlinkat
  - fs/pipe.c:pipe_read
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/readdir.c:iterate_dir
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:generic_file_splice_read
  - fs/ext4/file.c:ext4_file_mmap
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
  - fs/ecryptfs/file.c:ecryptfs_read_update_atime
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_mmap
  - fs/fuse/dax.c:fuse_dax_mmap
  - block/fops.c:blkdev_read_iter
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff81419560-ffffffff81419716: touch_atime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void touch_atime(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814a4fa0)
Location: fs/inode.c:1920
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - mm/filemap.c:generic_file_readonly_mmap
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:filemap_read
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_mmap
  - fs/stat.c:do_readlinkat
  - fs/pipe.c:pipe_read
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/readdir.c:iterate_dir
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:generic_file_splice_read
  - fs/ext4/file.c:ext4_file_mmap
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
  - fs/ecryptfs/file.c:ecryptfs_read_update_atime
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_mmap
  - fs/fuse/dax.c:fuse_dax_mmap
  - block/fops.c:blkdev_read_iter
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff814a4fa0-ffffffff814a5156: touch_atime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void touch_atime(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814da220)
Location: fs/inode.c:1964
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - mm/filemap.c:generic_file_readonly_mmap
  - mm/filemap.c:filemap_splice_read
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:filemap_read
  - mm/shmem.c:shmem_file_splice_read
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_mmap
  - fs/stat.c:do_readlinkat
  - fs/pipe.c:pipe_read
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/readdir.c:iterate_dir
  - fs/splice.c:splice_direct_to_actor
  - fs/ext4/file.c:ext4_file_mmap
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
  - fs/ecryptfs/file.c:ecryptfs_read_update_atime
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_mmap
  - fs/fuse/dax.c:fuse_dax_mmap
  - block/fops.c:blkdev_read_iter
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff814da220-ffffffff814da3d6: touch_atime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void touch_atime(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff8150c850)
Location: fs/inode.c:1968
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - mm/filemap.c:generic_file_readonly_mmap
  - mm/filemap.c:filemap_splice_read
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:filemap_read
  - mm/shmem.c:shmem_file_splice_read
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_mmap
  - fs/stat.c:do_readlinkat
  - fs/pipe.c:pipe_read
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/readdir.c:iterate_dir
  - fs/splice.c:splice_direct_to_actor
  - fs/ext4/file.c:ext4_file_mmap
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
  - fs/ecryptfs/file.c:ecryptfs_read_update_atime
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_mmap
  - fs/fuse/dax.c:fuse_dax_mmap
  - block/fops.c:blkdev_read_iter
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff8150c850-ffffffff8150c970: touch_atime (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void touch_atime(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffff8000103af8b0)
Location: fs/inode.c:1739
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - mm/filemap.c:generic_file_readonly_mmap
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_buffered_read
  - mm/shmem.c:shmem_file_read_iter
  - fs/stat.c:do_readlinkat
  - fs/pipe.c:pipe_read
  - fs/namei.c:trailing_symlink
  - fs/namei.c:trailing_symlink
  - fs/readdir.c:iterate_dir
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:generic_file_splice_read
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
  - fs/ecryptfs/file.c:ecryptfs_read_update_atime
  - fs/fuse/file.c:__fuse_copy_file_range
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffff8000103af8b0-ffff8000103af9a4: touch_atime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void touch_atime(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (c058f694)
Location: fs/inode.c:1739
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - mm/filemap.c:generic_file_readonly_mmap
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_buffered_read
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_mmap
  - fs/stat.c:do_readlinkat
  - fs/pipe.c:pipe_read
  - fs/namei.c:trailing_symlink
  - fs/namei.c:trailing_symlink
  - fs/readdir.c:iterate_dir
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:generic_file_splice_read
  - fs/ecryptfs/file.c:ecryptfs_read_update_atime
  - fs/fuse/file.c:__fuse_copy_file_range
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
c058f694-c058f794: touch_atime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void touch_atime(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (c0000000004ab480)
Location: fs/inode.c:1739
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - mm/filemap.c:generic_file_readonly_mmap
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_buffered_read
  - mm/shmem.c:shmem_file_read_iter
  - fs/stat.c:do_readlinkat
  - fs/pipe.c:pipe_read
  - fs/namei.c:trailing_symlink
  - fs/namei.c:trailing_symlink
  - fs/readdir.c:iterate_dir
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:generic_file_splice_read
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
  - fs/ecryptfs/file.c:ecryptfs_read_update_atime
  - fs/fuse/file.c:__fuse_copy_file_range
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
c0000000004ab480-c0000000004ab5c4: touch_atime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void touch_atime(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffe000274302)
Location: fs/inode.c:1739
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - mm/filemap.c:generic_file_readonly_mmap
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_buffered_read
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_mmap
  - fs/stat.c:do_readlinkat
  - fs/pipe.c:pipe_read
  - fs/namei.c:trailing_symlink
  - fs/namei.c:trailing_symlink
  - fs/readdir.c:iterate_dir
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:generic_file_splice_read
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
  - fs/ecryptfs/file.c:ecryptfs_read_update_atime
  - fs/fuse/file.c:__fuse_copy_file_range
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffe000274302-ffffffe0002743b4: touch_atime (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void touch_atime(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f6f80)
Location: fs/inode.c:1739
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - mm/filemap.c:generic_file_readonly_mmap
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_buffered_read
  - mm/shmem.c:shmem_file_read_iter
  - fs/stat.c:do_readlinkat
  - fs/pipe.c:pipe_read
  - fs/namei.c:trailing_symlink
  - fs/namei.c:trailing_symlink
  - fs/readdir.c:iterate_dir
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:generic_file_splice_read
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
  - fs/ecryptfs/file.c:ecryptfs_read_update_atime
  - fs/fuse/file.c:__fuse_copy_file_range
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff812f6f80-ffffffff812f705e: touch_atime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void touch_atime(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812e7ba0)
Location: fs/inode.c:1739
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - mm/filemap.c:generic_file_readonly_mmap
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_buffered_read
  - mm/shmem.c:shmem_file_read_iter
  - fs/stat.c:do_readlinkat
  - fs/pipe.c:pipe_read
  - fs/namei.c:trailing_symlink
  - fs/namei.c:trailing_symlink
  - fs/readdir.c:iterate_dir
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:generic_file_splice_read
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
  - fs/ecryptfs/file.c:ecryptfs_read_update_atime
  - fs/fuse/file.c:__fuse_copy_file_range
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff812e7ba0-ffffffff812e7c7e: touch_atime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void touch_atime(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f4d90)
Location: fs/inode.c:1739
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - mm/filemap.c:generic_file_readonly_mmap
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_buffered_read
  - mm/shmem.c:shmem_file_read_iter
  - fs/stat.c:do_readlinkat
  - fs/pipe.c:pipe_read
  - fs/namei.c:trailing_symlink
  - fs/namei.c:trailing_symlink
  - fs/readdir.c:iterate_dir
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:generic_file_splice_read
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
  - fs/ecryptfs/file.c:ecryptfs_read_update_atime
  - fs/fuse/file.c:__fuse_copy_file_range
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff812f4d90-ffffffff812f4e6e: touch_atime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void touch_atime(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81305f20)
Location: fs/inode.c:1739
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - mm/filemap.c:generic_file_readonly_mmap
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_buffered_read
  - mm/shmem.c:shmem_file_read_iter
  - fs/stat.c:do_readlinkat
  - fs/pipe.c:pipe_read
  - fs/namei.c:trailing_symlink
  - fs/readdir.c:iterate_dir
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:generic_file_splice_read
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
  - fs/ecryptfs/file.c:ecryptfs_read_update_atime
  - fs/fuse/file.c:__fuse_copy_file_range
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff81305f20-ffffffff81305ffe: touch_atime (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
