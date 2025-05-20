# Function: <code>file_update_time</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int file_update_time(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81227680)
Location: fs/inode.c:1771
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/prfile.c:vma_do_file_update_time
  - mm/prfile.c:vma_do_file_update_time
  - mm/memory.c:handle_mm_fault
  - fs/pipe.c:pipe_write
  - fs/dax.c:dax_pmd_fault
  - fs/dax.c:dax_pfn_mkwrite
  - fs/dax.c:dax_fault
  - fs/kernfs/file.c:kernfs_vma_page_mkwrite
  - fs/ext4/file.c:ext4_dax_pmd_fault
  - fs/ext4/file.c:ext4_dax_fault
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_file_write_iter
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
**Symbols:**

```
ffffffff81227680-ffffffff8122778d: file_update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int file_update_time(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff8124fd90)
Location: fs/inode.c:1788
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/prfile.c:vma_do_file_update_time
  - mm/prfile.c:vma_do_file_update_time
  - mm/memory.c:handle_mm_fault
  - fs/pipe.c:pipe_write
  - fs/kernfs/file.c:kernfs_vma_page_mkwrite
  - fs/ext4/file.c:ext4_dax_pfn_mkwrite
  - fs/ext4/file.c:ext4_dax_pmd_fault
  - fs/ext4/file.c:ext4_dax_fault
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_finish_open
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
**Symbols:**

```
ffffffff8124fd90-ffffffff8124fe9d: file_update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int file_update_time(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81262eb0)
Location: fs/inode.c:1838
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/prfile.c:vma_do_file_update_time
  - mm/prfile.c:vma_do_file_update_time
  - fs/pipe.c:pipe_write
  - fs/kernfs/file.c:kernfs_vma_page_mkwrite
  - fs/ext4/file.c:ext4_dax_pfn_mkwrite
  - fs/ext4/file.c:ext4_dax_pmd_fault
  - fs/ext4/file.c:ext4_dax_fault
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_finish_open
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
**Symbols:**

```
ffffffff81262eb0-ffffffff81262fbc: file_update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int file_update_time(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81270750)
Location: fs/inode.c:1838
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/prfile.c:vma_do_file_update_time
  - mm/prfile.c:vma_do_file_update_time
  - fs/pipe.c:pipe_write
  - fs/kernfs/file.c:kernfs_vma_page_mkwrite
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_finish_open
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
**Symbols:**

```
ffffffff81270750-ffffffff81270853: file_update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int file_update_time(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81293090)
Location: fs/inode.c:1851
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/prfile.c:vma_do_file_update_time
  - mm/prfile.c:vma_do_file_update_time
  - fs/pipe.c:pipe_write
  - fs/kernfs/file.c:kernfs_vma_page_mkwrite
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_finish_open
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
**Symbols:**

```
ffffffff81293090-ffffffff81293196: file_update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int file_update_time(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812b8ce0)
Location: fs/inode.c:1843
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/prfile.c:vma_do_file_update_time
  - mm/prfile.c:vma_do_file_update_time
  - fs/pipe.c:pipe_write
  - fs/kernfs/file.c:kernfs_vma_page_mkwrite
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_finish_open
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
**Symbols:**

```
ffffffff812b8ce0-ffffffff812b8e09: file_update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int file_update_time(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812cde20)
Location: fs/inode.c:1850
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/prfile.c:vma_do_file_update_time
  - mm/prfile.c:vma_do_file_update_time
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/pipe.c:pipe_write
  - fs/kernfs/file.c:kernfs_vma_page_mkwrite
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/fuse/file.c:fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_finish_open
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
**Symbols:**

```
ffffffff812cde20-ffffffff812cdf49: file_update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int file_update_time(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812eac50)
Location: fs/inode.c:1868
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/prfile.c:vma_do_file_update_time
  - mm/prfile.c:vma_do_file_update_time
  - fs/pipe.c:pipe_write
  - fs/kernfs/file.c:kernfs_vma_page_mkwrite
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_finish_open
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
**Symbols:**

```
ffffffff812eac50-ffffffff812ead85: file_update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int file_update_time(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812fc780)
Location: fs/inode.c:1879
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/prfile.c:vma_do_file_update_time
  - mm/prfile.c:vma_do_file_update_time
  - mm/memory.c:fault_dirty_shared_page
  - fs/pipe.c:pipe_write
  - fs/kernfs/file.c:kernfs_vma_page_mkwrite
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_finish_open
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
**Symbols:**

```
ffffffff812fc780-ffffffff812fc8b5: file_update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int file_update_time(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff813358e0)
Location: fs/inode.c:1963
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/prfile.c:vma_do_file_update_time
  - mm/prfile.c:vma_do_file_update_time
  - mm/memory.c:fault_dirty_shared_page
  - fs/pipe.c:pipe_write
  - fs/kernfs/file.c:kernfs_vma_page_mkwrite
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/file.c:fuse_finish_open
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
**Symbols:**

```
ffffffff813358e0-ffffffff81335a1b: file_update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int file_update_time(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81341260)
Location: fs/inode.c:1964
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/prfile.c:vma_do_file_update_time
  - mm/prfile.c:vma_do_file_update_time
  - mm/memory.c:fault_dirty_shared_page
  - fs/pipe.c:pipe_write
  - fs/kernfs/file.c:kernfs_vma_page_mkwrite
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/file.c:fuse_finish_open
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
**Symbols:**

```
ffffffff81341260-ffffffff8134139b: file_update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int file_update_time(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff813475a0)
Location: fs/inode.c:1973
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:filemap_page_mkwrite
  - mm/memory.c:fault_dirty_shared_page
  - fs/pipe.c:pipe_write
  - fs/kernfs/file.c:kernfs_vma_page_mkwrite
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/file.c:fuse_finish_open
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
**Symbols:**

```
ffffffff813475a0-ffffffff813476db: file_update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int file_update_time(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff813950c0)
Location: fs/inode.c:1978
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/prfile.c:vma_do_file_update_time
  - mm/prfile.c:vma_do_file_update_time
  - mm/memory.c:fault_dirty_shared_page
  - fs/pipe.c:pipe_write
  - fs/kernfs/file.c:kernfs_vma_page_mkwrite
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/file.c:fuse_finish_open
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
**Symbols:**

```
ffffffff813950c0-ffffffff813951fb: file_update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int file_update_time(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81417f00)
Location: fs/inode.c:2059
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/prfile.c:vma_do_file_update_time
  - mm/prfile.c:vma_do_file_update_time
  - mm/memory.c:fault_dirty_shared_page
  - fs/pipe.c:pipe_write
  - fs/kernfs/file.c:kernfs_vma_page_mkwrite
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/file.c:fuse_finish_open
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
**Symbols:**

```
ffffffff81417f00-ffffffff81418053: file_update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int file_update_time(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814a36d0)
Location: fs/inode.c:2078
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/prfile.c:vma_do_file_update_time
  - mm/prfile.c:vma_do_file_update_time
  - mm/memory.c:fault_dirty_shared_page
  - fs/pipe.c:pipe_write
  - fs/kernfs/file.c:kernfs_vma_page_mkwrite
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/file.c:fuse_finish_open
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
**Symbols:**

```
ffffffff814a36d0-ffffffff814a3799: file_update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int file_update_time(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814d8830)
Location: fs/inode.c:2122
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:filemap_page_mkwrite
  - mm/memory.c:fault_dirty_shared_page
  - fs/pipe.c:pipe_write
  - fs/kernfs/file.c:kernfs_vma_page_mkwrite
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/file.c:fuse_finish_open
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
**Symbols:**

```
ffffffff814d8830-ffffffff814d8905: file_update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int file_update_time(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff8150a230)
Location: fs/inode.c:2127
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:filemap_page_mkwrite
  - mm/shmem.c:shmem_file_write_iter
  - mm/memory.c:fault_dirty_shared_page
  - fs/pipe.c:pipe_write
  - fs/kernfs/file.c:kernfs_vma_page_mkwrite
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/file.c:fuse_finish_open
  - block/fops.c:blkdev_write_iter
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
**Symbols:**

```
ffffffff8150a230-ffffffff8150a2b8: file_update_time (STB_GLOBAL)
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
int file_update_time(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffff8000103ac208)
Location: fs/inode.c:1879
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/prfile.c:vma_do_file_update_time
  - mm/prfile.c:vma_do_file_update_time
  - mm/memory.c:fault_dirty_shared_page
  - fs/pipe.c:pipe_write
  - fs/kernfs/file.c:kernfs_vma_page_mkwrite
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_finish_open
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
**Symbols:**

```
ffff8000103ac208-ffff8000103ac338: file_update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int file_update_time(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (c058d4d4)
Location: fs/inode.c:1879
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/prfile.c:vma_do_file_update_time
  - mm/prfile.c:vma_do_file_update_time
  - mm/memory.c:fault_dirty_shared_page
  - fs/pipe.c:pipe_write
  - fs/kernfs/file.c:kernfs_vma_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_finish_open
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
**Symbols:**

```
c058d4d4-c058d634: file_update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int file_update_time(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (c0000000004a7780)
Location: fs/inode.c:1879
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/prfile.c:vma_do_file_update_time
  - mm/prfile.c:vma_do_file_update_time
  - mm/memory.c:fault_dirty_shared_page
  - fs/pipe.c:pipe_write
  - fs/kernfs/file.c:kernfs_vma_page_mkwrite
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_finish_open
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
**Symbols:**

```
c0000000004a7780-c0000000004a7934: file_update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int file_update_time(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffe00027178e)
Location: fs/inode.c:1879
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/prfile.c:vma_do_file_update_time
  - mm/prfile.c:vma_do_file_update_time
  - mm/memory.c:fault_dirty_shared_page
  - fs/pipe.c:pipe_write
  - fs/kernfs/file.c:kernfs_vma_page_mkwrite
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_finish_open
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
**Symbols:**

```
ffffffe00027178e-ffffffe000271870: file_update_time (STB_GLOBAL)
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
int file_update_time(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f4d60)
Location: fs/inode.c:1879
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/prfile.c:vma_do_file_update_time
  - mm/prfile.c:vma_do_file_update_time
  - mm/memory.c:fault_dirty_shared_page
  - fs/pipe.c:pipe_write
  - fs/kernfs/file.c:kernfs_vma_page_mkwrite
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_finish_open
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
**Symbols:**

```
ffffffff812f4d60-ffffffff812f4e95: file_update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int file_update_time(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812e5980)
Location: fs/inode.c:1879
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/prfile.c:vma_do_file_update_time
  - mm/prfile.c:vma_do_file_update_time
  - mm/memory.c:fault_dirty_shared_page
  - fs/pipe.c:pipe_write
  - fs/kernfs/file.c:kernfs_vma_page_mkwrite
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_finish_open
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
**Symbols:**

```
ffffffff812e5980-ffffffff812e5ab5: file_update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int file_update_time(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f2b70)
Location: fs/inode.c:1879
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/prfile.c:vma_do_file_update_time
  - mm/prfile.c:vma_do_file_update_time
  - mm/memory.c:fault_dirty_shared_page
  - fs/pipe.c:pipe_write
  - fs/kernfs/file.c:kernfs_vma_page_mkwrite
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_finish_open
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
**Symbols:**

```
ffffffff812f2b70-ffffffff812f2ca5: file_update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int file_update_time(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81304280)
Location: fs/inode.c:1879
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/prfile.c:vma_do_file_update_time
  - mm/prfile.c:vma_do_file_update_time
  - mm/memory.c:fault_dirty_shared_page
  - fs/pipe.c:pipe_write
  - fs/kernfs/file.c:kernfs_vma_page_mkwrite
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_finish_open
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
**Symbols:**

```
ffffffff81304280-ffffffff813043b5: file_update_time (STB_GLOBAL)
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
