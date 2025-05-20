# Function: <code>fuse_flush_time_update</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void fuse_flush_time_update(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff814ec020)
Location: fs/fuse/dir.c:741
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
```
**Symbols:**

```
ffffffff814ec020-ffffffff814ec08b: fuse_flush_time_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void fuse_flush_time_update(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8157acf0)
Location: fs/fuse/dir.c:838
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_entry_unlinked
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
```
**Symbols:**

```
ffffffff8157acf0-ffffffff8157ad65: fuse_flush_time_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fuse_flush_time_update(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff816204d0)
Location: fs/fuse/dir.c:861
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_entry_unlinked
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
```
**Symbols:**

```
ffffffff816204d0-ffffffff81620545: fuse_flush_time_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fuse_flush_time_update(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81658920)
Location: fs/fuse/dir.c:927
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_entry_unlinked
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
```
**Symbols:**

```
ffffffff81658920-ffffffff8165898f: fuse_flush_time_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fuse_flush_time_update(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81692670)
Location: fs/fuse/dir.c:924
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_entry_unlinked
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
```
**Symbols:**

```
ffffffff81692670-ffffffff816926df: fuse_flush_time_update (STB_GLOBAL)
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
