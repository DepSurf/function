# Function: <code>file_modified</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int file_modified(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812eb010)
Location: fs/inode.c:1904
Inline: True
Direct callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/fuse/file.c:__fuse_copy_file_range
```
**Symbols:**

```
ffffffff812eb010-ffffffff812eb03b: file_modified (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int file_modified(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812fcb50)
Location: fs/inode.c:1915
Inline: True
Direct callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/fuse/file.c:__fuse_copy_file_range
```
**Symbols:**

```
ffffffff812fcb50-ffffffff812fcb7b: file_modified (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int file_modified(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81335a20)
Location: fs/inode.c:1999
Inline: True
Direct callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dio_write_checks
  - fs/ext4/file.c:ext4_buffered_write_iter
  - fs/fuse/file.c:__fuse_copy_file_range
```
**Symbols:**

```
ffffffff81335a20-ffffffff81335a4d: file_modified (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int file_modified(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff813413a0)
Location: fs/inode.c:2000
Inline: True
Direct callers:
  - fs/remap_range.c:generic_remap_file_range_prep
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dio_write_checks
  - fs/ext4/file.c:ext4_buffered_write_iter
  - fs/fuse/file.c:__fuse_copy_file_range
```
**Symbols:**

```
ffffffff813413a0-ffffffff813413cd: file_modified (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int file_modified(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff813476e0)
Location: fs/inode.c:2009
Inline: True
Direct callers:
  - fs/remap_range.c:generic_remap_file_range_prep
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_buffered_write_iter
  - fs/fuse/file.c:__fuse_copy_file_range
```
**Symbols:**

```
ffffffff813476e0-ffffffff8134770d: file_modified (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int file_modified(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81395200)
Location: fs/inode.c:2014
Inline: True
Direct callers:
  - fs/remap_range.c:generic_remap_file_range_prep
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_buffered_write_iter
  - fs/fuse/file.c:__fuse_copy_file_range
```
**Symbols:**

```
ffffffff81395200-ffffffff8139522d: file_modified (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int file_modified(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81418060)
Location: fs/inode.c:2095
Inline: True
Direct callers:
  - fs/remap_range.c:generic_remap_file_range_prep
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_buffered_write_iter
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/fuse/file.c:__fuse_copy_file_range
```
**Symbols:**

```
ffffffff81418060-ffffffff81418090: file_modified (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int file_modified(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814a38c0)
Location: fs/inode.c:2144
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fallocate
  - fs/remap_range.c:__generic_remap_file_range_prep
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_buffered_write_iter
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_file_fallocate
```
**Symbols:**

```
ffffffff814a38c0-ffffffff814a38da: file_modified (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int file_modified(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814d8a40)
Location: fs/inode.c:2188
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fallocate
  - fs/remap_range.c:__generic_remap_file_range_prep
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_buffered_write_iter
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_file_fallocate
```
**Symbols:**

```
ffffffff814d8a40-ffffffff814d8a5a: file_modified (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int file_modified(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff8150ae60)
Location: fs/inode.c:2191
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fallocate
  - fs/remap_range.c:__generic_remap_file_range_prep
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dio_write_checks
  - fs/ext4/file.c:ext4_buffered_write_iter
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_file_fallocate
```
**Symbols:**

```
ffffffff8150ae60-ffffffff8150af1c: file_modified (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int file_modified(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffff8000103ac588)
Location: fs/inode.c:1915
Inline: True
Direct callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/fuse/file.c:__fuse_copy_file_range
```
**Symbols:**

```
ffff8000103ac588-ffff8000103ac5c8: file_modified (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int file_modified(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (c058da50)
Location: fs/inode.c:1915
Inline: True
Direct callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/fuse/file.c:__fuse_copy_file_range
```
**Symbols:**

```
c058da50-c058da8c: file_modified (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int file_modified(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (c0000000004a8340)
Location: fs/inode.c:1915
Inline: True
Direct callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/fuse/file.c:__fuse_copy_file_range
```
**Symbols:**

```
c0000000004a8340-c0000000004a83b4: file_modified (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int file_modified(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffe000271b54)
Location: fs/inode.c:1915
Inline: True
Direct callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/fuse/file.c:__fuse_copy_file_range
```
**Symbols:**

```
ffffffe000271b54-ffffffe000271b94: file_modified (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int file_modified(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f5130)
Location: fs/inode.c:1915
Inline: True
Direct callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/fuse/file.c:__fuse_copy_file_range
```
**Symbols:**

```
ffffffff812f5130-ffffffff812f515b: file_modified (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int file_modified(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812e5d50)
Location: fs/inode.c:1915
Inline: True
Direct callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/fuse/file.c:__fuse_copy_file_range
```
**Symbols:**

```
ffffffff812e5d50-ffffffff812e5d7b: file_modified (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int file_modified(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f2f40)
Location: fs/inode.c:1915
Inline: True
Direct callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/fuse/file.c:__fuse_copy_file_range
```
**Symbols:**

```
ffffffff812f2f40-ffffffff812f2f6b: file_modified (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int file_modified(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81304870)
Location: fs/inode.c:1915
Inline: True
Direct callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/fuse/file.c:__fuse_copy_file_range
```
**Symbols:**

```
ffffffff81304870-ffffffff8130489b: file_modified (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
