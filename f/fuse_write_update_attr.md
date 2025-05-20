# Function: <code>fuse_write_update_attr</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool fuse_write_update_attr(struct inode *inode, loff_t pos, ssize_t written);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81581360)
Location: fs/fuse/file.c:1093
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/dax.c:fuse_dax_write_iter
```
**Symbols:**

```
ffffffff81581360-ffffffff815813f6: fuse_write_update_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool fuse_write_update_attr(struct inode *inode, loff_t pos, ssize_t written);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff816271b0)
Location: fs/fuse/file.c:1093
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/dax.c:fuse_dax_write_iter
```
**Symbols:**

```
ffffffff816271b0-ffffffff81627246: fuse_write_update_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool fuse_write_update_attr(struct inode *inode, loff_t pos, ssize_t written);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8165f570)
Location: fs/fuse/file.c:1094
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/dax.c:fuse_dax_write_iter
```
**Symbols:**

```
ffffffff8165f570-ffffffff8165f606: fuse_write_update_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool fuse_write_update_attr(struct inode *inode, loff_t pos, ssize_t written);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff816993b0)
Location: fs/fuse/file.c:1095
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/dax.c:fuse_dax_write_iter
```
**Symbols:**

```
ffffffff816993b0-ffffffff81699446: fuse_write_update_attr (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
