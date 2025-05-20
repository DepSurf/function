# Function: <code>file_check_and_advance_wb_err</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int file_check_and_advance_wb_err(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b6050)
Location: mm/filemap.c:611
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_write_and_wait_range
  - fs/libfs.c:__generic_file_fsync
  - fs/libfs.c:__generic_file_fsync
```
**Symbols:**

```
ffffffff811b6050-ffffffff811b6117: file_check_and_advance_wb_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int file_check_and_advance_wb_err(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ca2f0)
Location: mm/filemap.c:705
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_fdatawait_range
  - fs/libfs.c:__generic_file_fsync
  - fs/libfs.c:__generic_file_fsync
  - fs/fuse/file.c:fuse_fsync_common
```
**Symbols:**

```
ffffffff811ca2f0-ffffffff811ca3c5: file_check_and_advance_wb_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int file_check_and_advance_wb_err(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811eb3a0)
Location: mm/filemap.c:705
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_fdatawait_range
  - fs/libfs.c:__generic_file_fsync
  - fs/libfs.c:__generic_file_fsync
  - fs/fuse/file.c:fuse_fsync_common
```
**Symbols:**

```
ffffffff811eb3a0-ffffffff811eb477: file_check_and_advance_wb_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int file_check_and_advance_wb_err(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811fbfc0)
Location: mm/filemap.c:682
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_fdatawait_range
  - fs/libfs.c:__generic_file_fsync
  - fs/libfs.c:__generic_file_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fuse/file.c:fuse_fsync
```
**Symbols:**

```
ffffffff811fbfc0-ffffffff811fc097: file_check_and_advance_wb_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int file_check_and_advance_wb_err(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812136c0)
Location: mm/filemap.c:723
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_fdatawait_range
  - fs/libfs.c:__generic_file_fsync
  - fs/libfs.c:__generic_file_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fuse/file.c:fuse_fsync
```
**Symbols:**

```
ffffffff812136c0-ffffffff8121379a: file_check_and_advance_wb_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int file_check_and_advance_wb_err(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81220e90)
Location: mm/filemap.c:732
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_fdatawait_range
  - fs/libfs.c:__generic_file_fsync
  - fs/libfs.c:__generic_file_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fuse/file.c:fuse_fsync
```
**Symbols:**

```
ffffffff81220e90-ffffffff81220f6a: file_check_and_advance_wb_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int file_check_and_advance_wb_err(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8124eaf0)
Location: mm/filemap.c:710
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_fdatawait_range
  - fs/libfs.c:__generic_file_fsync
  - fs/libfs.c:__generic_file_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fuse/file.c:fuse_fsync
```
**Symbols:**

```
ffffffff8124eaf0-ffffffff8124ebc7: file_check_and_advance_wb_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int file_check_and_advance_wb_err(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812590f0)
Location: mm/filemap.c:711
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_fdatawait_range
  - fs/libfs.c:__generic_file_fsync
  - fs/libfs.c:__generic_file_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fuse/file.c:fuse_fsync
```
**Symbols:**

```
ffffffff812590f0-ffffffff812591b4: file_check_and_advance_wb_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int file_check_and_advance_wb_err(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125e320)
Location: mm/filemap.c:742
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_fdatawait_range
  - fs/libfs.c:__generic_file_fsync
  - fs/libfs.c:__generic_file_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fuse/file.c:fuse_fsync
```
**Symbols:**

```
ffffffff8125e320-ffffffff8125e3e1: file_check_and_advance_wb_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int file_check_and_advance_wb_err(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8129af30)
Location: mm/filemap.c:760
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_fdatawait_range
  - fs/libfs.c:__generic_file_fsync
  - fs/libfs.c:__generic_file_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fuse/file.c:fuse_fsync
```
**Symbols:**

```
ffffffff8129af30-ffffffff8129aff7: file_check_and_advance_wb_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int file_check_and_advance_wb_err(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812efb50)
Location: mm/filemap.c:729
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_fdatawait_range
  - fs/libfs.c:__generic_file_fsync
  - fs/libfs.c:__generic_file_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fuse/file.c:fuse_fsync
```
**Symbols:**

```
ffffffff812efb50-ffffffff812efc35: file_check_and_advance_wb_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int file_check_and_advance_wb_err(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8135a800)
Location: mm/filemap.c:724
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_fdatawait_range
  - fs/libfs.c:__generic_file_fsync
  - fs/libfs.c:__generic_file_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fuse/file.c:fuse_fsync
```
**Symbols:**

```
ffffffff8135a800-ffffffff8135a8e5: file_check_and_advance_wb_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int file_check_and_advance_wb_err(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8138c240)
Location: mm/filemap.c:731
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_fdatawait_range
  - fs/libfs.c:__generic_file_fsync
  - fs/libfs.c:__generic_file_fsync
  - fs/buffer.c:generic_buffers_fsync_noflush
  - fs/buffer.c:generic_buffers_fsync_noflush
  - fs/buffer.c:generic_buffers_fsync_noflush
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fuse/file.c:fuse_fsync
```
**Symbols:**

```
ffffffff8138c240-ffffffff8138c31f: file_check_and_advance_wb_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int file_check_and_advance_wb_err(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff813b5db0)
Location: mm/filemap.c:726
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_fdatawait_range
  - fs/libfs.c:__generic_file_fsync
  - fs/libfs.c:__generic_file_fsync
  - fs/buffer.c:generic_buffers_fsync_noflush
  - fs/buffer.c:generic_buffers_fsync_noflush
  - fs/buffer.c:generic_buffers_fsync_noflush
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fuse/file.c:fuse_fsync
```
**Symbols:**

```
ffffffff813b5db0-ffffffff813b5e8f: file_check_and_advance_wb_err (STB_GLOBAL)
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
int file_check_and_advance_wb_err(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102af330)
Location: mm/filemap.c:732
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_fdatawait_range
  - fs/libfs.c:__generic_file_fsync
  - fs/libfs.c:__generic_file_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fuse/file.c:fuse_fsync
```
**Symbols:**

```
ffff8000102af330-ffff8000102af4bc: file_check_and_advance_wb_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int file_check_and_advance_wb_err(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c04dae8c)
Location: mm/filemap.c:732
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_fdatawait_range
  - fs/libfs.c:__generic_file_fsync
  - fs/libfs.c:__generic_file_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fuse/file.c:fuse_fsync
```
**Symbols:**

```
c04dae8c-c04daf9c: file_check_and_advance_wb_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int file_check_and_advance_wb_err(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c000000000362840)
Location: mm/filemap.c:732
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_fdatawait_range
  - fs/libfs.c:__generic_file_fsync
  - fs/libfs.c:__generic_file_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fuse/file.c:fuse_fsync
```
**Symbols:**

```
c000000000362840-c0000000003629c0: file_check_and_advance_wb_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int file_check_and_advance_wb_err(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffe0001d469e)
Location: mm/filemap.c:732
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_fdatawait_range
  - fs/libfs.c:__generic_file_fsync
  - fs/libfs.c:__generic_file_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fuse/file.c:fuse_fsync
```
**Symbols:**

```
ffffffe0001d469e-ffffffe0001d47b6: file_check_and_advance_wb_err (STB_GLOBAL)
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
int file_check_and_advance_wb_err(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812194e0)
Location: mm/filemap.c:732
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_fdatawait_range
  - fs/libfs.c:__generic_file_fsync
  - fs/libfs.c:__generic_file_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fuse/file.c:fuse_fsync
```
**Symbols:**

```
ffffffff812194e0-ffffffff812195ba: file_check_and_advance_wb_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int file_check_and_advance_wb_err(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8120c6f0)
Location: mm/filemap.c:732
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_fdatawait_range
  - fs/libfs.c:__generic_file_fsync
  - fs/libfs.c:__generic_file_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fuse/file.c:fuse_fsync
```
**Symbols:**

```
ffffffff8120c6f0-ffffffff8120c7ca: file_check_and_advance_wb_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int file_check_and_advance_wb_err(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81217280)
Location: mm/filemap.c:732
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_fdatawait_range
  - fs/libfs.c:__generic_file_fsync
  - fs/libfs.c:__generic_file_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fuse/file.c:fuse_fsync
```
**Symbols:**

```
ffffffff81217280-ffffffff8121735a: file_check_and_advance_wb_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int file_check_and_advance_wb_err(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81226310)
Location: mm/filemap.c:732
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:file_fdatawait_range
  - fs/libfs.c:__generic_file_fsync
  - fs/libfs.c:__generic_file_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fuse/file.c:fuse_fsync
```
**Symbols:**

```
ffffffff81226310-ffffffff81226403: file_check_and_advance_wb_err (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
