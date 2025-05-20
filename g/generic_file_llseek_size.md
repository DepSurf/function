# Function: <code>generic_file_llseek_size</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
loff_t generic_file_llseek_size(struct file *file, loff_t offset, int whence, loff_t maxsize, loff_t eof);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8120bcc0)
Location: fs/read_write.c:85
Inline: True
Direct callers:
  - mm/shmem.c:shmem_file_llseek
  - fs/read_write.c:generic_file_llseek
  - fs/read_write.c:fixed_size_llseek
  - fs/libfs.c:empty_dir_llseek
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffff8120bcc0-ffffffff8120bdca: generic_file_llseek_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
loff_t generic_file_llseek_size(struct file *file, loff_t offset, int whence, loff_t maxsize, loff_t eof);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81231b10)
Location: fs/read_write.c:87
Inline: True
Direct callers:
  - mm/shmem.c:shmem_file_llseek
  - fs/read_write.c:no_seek_end_llseek_size
  - fs/read_write.c:no_seek_end_llseek
  - fs/read_write.c:fixed_size_llseek
  - fs/read_write.c:generic_file_llseek
  - fs/libfs.c:empty_dir_llseek
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffff81231b10-ffffffff81231bf0: generic_file_llseek_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
loff_t generic_file_llseek_size(struct file *file, loff_t offset, int whence, loff_t maxsize, loff_t eof);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812440c0)
Location: fs/read_write.c:87
Inline: True
Direct callers:
  - mm/shmem.c:shmem_file_llseek
  - fs/read_write.c:no_seek_end_llseek_size
  - fs/read_write.c:no_seek_end_llseek
  - fs/read_write.c:fixed_size_llseek
  - fs/read_write.c:generic_file_llseek
  - fs/libfs.c:empty_dir_llseek
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffff812440c0-ffffffff812441a0: generic_file_llseek_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
loff_t generic_file_llseek_size(struct file *file, loff_t offset, int whence, loff_t maxsize, loff_t eof);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8124f6e0)
Location: fs/read_write.c:85
Inline: True
Direct callers:
  - mm/shmem.c:shmem_file_llseek
  - fs/read_write.c:no_seek_end_llseek_size
  - fs/read_write.c:no_seek_end_llseek
  - fs/read_write.c:fixed_size_llseek
  - fs/read_write.c:generic_file_llseek
  - fs/libfs.c:empty_dir_llseek
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffff8124f6e0-ffffffff8124f7c0: generic_file_llseek_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
loff_t generic_file_llseek_size(struct file *file, loff_t offset, int whence, loff_t maxsize, loff_t eof);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81271620)
Location: fs/read_write.c:86
Inline: True
Direct callers:
  - mm/shmem.c:shmem_file_llseek
  - fs/read_write.c:no_seek_end_llseek_size
  - fs/read_write.c:no_seek_end_llseek
  - fs/read_write.c:fixed_size_llseek
  - fs/read_write.c:generic_file_llseek
  - fs/libfs.c:empty_dir_llseek
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffff81271620-ffffffff81271700: generic_file_llseek_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
loff_t generic_file_llseek_size(struct file *file, loff_t offset, int whence, loff_t maxsize, loff_t eof);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81297330)
Location: fs/read_write.c:86
Inline: True
Direct callers:
  - mm/shmem.c:shmem_file_llseek
  - fs/read_write.c:no_seek_end_llseek_size
  - fs/read_write.c:no_seek_end_llseek
  - fs/read_write.c:fixed_size_llseek
  - fs/read_write.c:generic_file_llseek
  - fs/libfs.c:empty_dir_llseek
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffff81297330-ffffffff81297424: generic_file_llseek_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
loff_t generic_file_llseek_size(struct file *file, loff_t offset, int whence, loff_t maxsize, loff_t eof);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812abfe0)
Location: fs/read_write.c:86
Inline: True
Direct callers:
  - mm/shmem.c:shmem_file_llseek
  - fs/read_write.c:no_seek_end_llseek_size
  - fs/read_write.c:no_seek_end_llseek
  - fs/read_write.c:fixed_size_llseek
  - fs/read_write.c:generic_file_llseek
  - fs/libfs.c:empty_dir_llseek
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffff812abfe0-ffffffff812ac0d4: generic_file_llseek_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
loff_t generic_file_llseek_size(struct file *file, loff_t offset, int whence, loff_t maxsize, loff_t eof);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c8820)
Location: fs/read_write.c:86
Inline: True
Direct callers:
  - mm/shmem.c:shmem_file_llseek
  - fs/read_write.c:no_seek_end_llseek_size
  - fs/read_write.c:no_seek_end_llseek
  - fs/read_write.c:fixed_size_llseek
  - fs/read_write.c:generic_file_llseek
  - fs/libfs.c:empty_dir_llseek
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffff812c8820-ffffffff812c8913: generic_file_llseek_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
loff_t generic_file_llseek_size(struct file *file, loff_t offset, int whence, loff_t maxsize, loff_t eof);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812da230)
Location: fs/read_write.c:86
Inline: True
Direct callers:
  - mm/shmem.c:shmem_file_llseek
  - fs/read_write.c:no_seek_end_llseek_size
  - fs/read_write.c:no_seek_end_llseek
  - fs/read_write.c:fixed_size_llseek
  - fs/read_write.c:generic_file_llseek
  - fs/libfs.c:empty_dir_llseek
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffff812da230-ffffffff812da323: generic_file_llseek_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
loff_t generic_file_llseek_size(struct file *file, loff_t offset, int whence, loff_t maxsize, loff_t eof);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff813104c0)
Location: fs/read_write.c:86
Inline: False
Direct callers:
  - mm/shmem.c:shmem_file_llseek
  - fs/read_write.c:no_seek_end_llseek_size
  - fs/read_write.c:no_seek_end_llseek
  - fs/read_write.c:fixed_size_llseek
  - fs/read_write.c:generic_file_llseek
  - fs/libfs.c:empty_dir_llseek
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffff813104c0-ffffffff813105b3: generic_file_llseek_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
loff_t generic_file_llseek_size(struct file *file, loff_t offset, int whence, loff_t maxsize, loff_t eof);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8131c770)
Location: fs/read_write.c:86
Inline: False
Direct callers:
  - mm/shmem.c:shmem_file_llseek
  - fs/read_write.c:no_seek_end_llseek_size
  - fs/read_write.c:no_seek_end_llseek
  - fs/read_write.c:fixed_size_llseek
  - fs/read_write.c:generic_file_llseek
  - fs/libfs.c:empty_dir_llseek
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffff8131c770-ffffffff8131c863: generic_file_llseek_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
loff_t generic_file_llseek_size(struct file *file, loff_t offset, int whence, loff_t maxsize, loff_t eof);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff813228e0)
Location: fs/read_write.c:86
Inline: False
Direct callers:
  - mm/shmem.c:shmem_file_llseek
  - fs/read_write.c:no_seek_end_llseek_size
  - fs/read_write.c:no_seek_end_llseek
  - fs/read_write.c:fixed_size_llseek
  - fs/read_write.c:generic_file_llseek
  - fs/libfs.c:empty_dir_llseek
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffff813228e0-ffffffff813229d3: generic_file_llseek_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
loff_t generic_file_llseek_size(struct file *file, loff_t offset, int whence, loff_t maxsize, loff_t eof);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8136fdd0)
Location: fs/read_write.c:86
Inline: False
Direct callers:
  - mm/shmem.c:shmem_file_llseek
  - fs/read_write.c:no_seek_end_llseek_size
  - fs/read_write.c:no_seek_end_llseek
  - fs/read_write.c:fixed_size_llseek
  - fs/read_write.c:generic_file_llseek
  - fs/libfs.c:empty_dir_llseek
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffff8136fdd0-ffffffff8136fec3: generic_file_llseek_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
loff_t generic_file_llseek_size(struct file *file, loff_t offset, int whence, loff_t maxsize, loff_t eof);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff813ee770)
Location: fs/read_write.c:86
Inline: False
Direct callers:
  - mm/shmem.c:shmem_file_llseek
  - fs/read_write.c:no_seek_end_llseek_size
  - fs/read_write.c:no_seek_end_llseek
  - fs/read_write.c:fixed_size_llseek
  - fs/read_write.c:generic_file_llseek
  - fs/libfs.c:empty_dir_llseek
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffff813ee770-ffffffff813ee87e: generic_file_llseek_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
loff_t generic_file_llseek_size(struct file *file, loff_t offset, int whence, loff_t maxsize, loff_t eof);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81476ff0)
Location: fs/read_write.c:86
Inline: False
Direct callers:
  - mm/shmem.c:shmem_file_llseek
  - fs/read_write.c:no_seek_end_llseek_size
  - fs/read_write.c:no_seek_end_llseek
  - fs/read_write.c:fixed_size_llseek
  - fs/read_write.c:generic_file_llseek
  - fs/libfs.c:empty_dir_llseek
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffff81476ff0-ffffffff814770fe: generic_file_llseek_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
loff_t generic_file_llseek_size(struct file *file, loff_t offset, int whence, loff_t maxsize, loff_t eof);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814ab940)
Location: fs/read_write.c:86
Inline: False
Direct callers:
  - mm/shmem.c:shmem_file_llseek
  - fs/read_write.c:no_seek_end_llseek_size
  - fs/read_write.c:no_seek_end_llseek
  - fs/read_write.c:fixed_size_llseek
  - fs/read_write.c:generic_file_llseek
  - fs/libfs.c:empty_dir_llseek
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffff814ab940-ffffffff814aba5a: generic_file_llseek_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
loff_t generic_file_llseek_size(struct file *file, loff_t offset, int whence, loff_t maxsize, loff_t eof);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814dcde0)
Location: fs/read_write.c:86
Inline: False
Direct callers:
  - mm/shmem.c:shmem_file_llseek
  - fs/read_write.c:no_seek_end_llseek_size
  - fs/read_write.c:no_seek_end_llseek
  - fs/read_write.c:fixed_size_llseek
  - fs/read_write.c:generic_file_llseek
  - fs/libfs.c:empty_dir_llseek
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffff814dcde0-ffffffff814dcefa: generic_file_llseek_size (STB_GLOBAL)
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
loff_t generic_file_llseek_size(struct file *file, loff_t offset, int whence, loff_t maxsize, loff_t eof);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffff80001037f910)
Location: fs/read_write.c:86
Inline: True
Direct callers:
  - mm/shmem.c:shmem_file_llseek
  - fs/read_write.c:no_seek_end_llseek_size
  - fs/read_write.c:no_seek_end_llseek
  - fs/read_write.c:fixed_size_llseek
  - fs/read_write.c:generic_file_llseek
  - fs/libfs.c:empty_dir_llseek
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffff80001037f910-ffff80001037fa80: generic_file_llseek_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
loff_t generic_file_llseek_size(struct file *file, loff_t offset, int whence, loff_t maxsize, loff_t eof);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c0569f90)
Location: fs/read_write.c:86
Inline: True
Direct callers:
  - mm/shmem.c:shmem_file_llseek
  - fs/read_write.c:no_seek_end_llseek_size
  - fs/read_write.c:no_seek_end_llseek
  - fs/read_write.c:fixed_size_llseek
  - fs/read_write.c:generic_file_llseek
  - fs/libfs.c:empty_dir_llseek
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
c0569f90-c056a118: generic_file_llseek_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
loff_t generic_file_llseek_size(struct file *file, loff_t offset, int whence, loff_t maxsize, loff_t eof);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c0000000004755b0)
Location: fs/read_write.c:86
Inline: True
Direct callers:
  - mm/shmem.c:shmem_file_llseek
  - fs/read_write.c:no_seek_end_llseek_size
  - fs/read_write.c:no_seek_end_llseek
  - fs/read_write.c:fixed_size_llseek
  - fs/read_write.c:generic_file_llseek
  - fs/libfs.c:empty_dir_llseek
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/file.c:ext4_llseek
  - drivers/char/nvram.c:nvram_misc_llseek
```
**Symbols:**

```
c0000000004755b0-c000000000475734: generic_file_llseek_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
loff_t generic_file_llseek_size(struct file *file, loff_t offset, int whence, loff_t maxsize, loff_t eof);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffe0002551be)
Location: fs/read_write.c:86
Inline: True
Direct callers:
  - mm/shmem.c:shmem_file_llseek
  - fs/read_write.c:no_seek_end_llseek_size
  - fs/read_write.c:no_seek_end_llseek
  - fs/read_write.c:fixed_size_llseek
  - fs/read_write.c:generic_file_llseek
  - fs/libfs.c:empty_dir_llseek
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffe0002551be-ffffffe0002552d0: generic_file_llseek_size (STB_GLOBAL)
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
loff_t generic_file_llseek_size(struct file *file, loff_t offset, int whence, loff_t maxsize, loff_t eof);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d2810)
Location: fs/read_write.c:86
Inline: True
Direct callers:
  - mm/shmem.c:shmem_file_llseek
  - fs/read_write.c:no_seek_end_llseek_size
  - fs/read_write.c:no_seek_end_llseek
  - fs/read_write.c:fixed_size_llseek
  - fs/read_write.c:generic_file_llseek
  - fs/libfs.c:empty_dir_llseek
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffff812d2810-ffffffff812d2903: generic_file_llseek_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
loff_t generic_file_llseek_size(struct file *file, loff_t offset, int whence, loff_t maxsize, loff_t eof);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c3490)
Location: fs/read_write.c:86
Inline: True
Direct callers:
  - mm/shmem.c:shmem_file_llseek
  - fs/read_write.c:no_seek_end_llseek_size
  - fs/read_write.c:no_seek_end_llseek
  - fs/read_write.c:fixed_size_llseek
  - fs/read_write.c:generic_file_llseek
  - fs/libfs.c:empty_dir_llseek
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffff812c3490-ffffffff812c3583: generic_file_llseek_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
loff_t generic_file_llseek_size(struct file *file, loff_t offset, int whence, loff_t maxsize, loff_t eof);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d0620)
Location: fs/read_write.c:86
Inline: True
Direct callers:
  - mm/shmem.c:shmem_file_llseek
  - fs/read_write.c:no_seek_end_llseek_size
  - fs/read_write.c:no_seek_end_llseek
  - fs/read_write.c:fixed_size_llseek
  - fs/read_write.c:generic_file_llseek
  - fs/libfs.c:empty_dir_llseek
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffff812d0620-ffffffff812d0713: generic_file_llseek_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
loff_t generic_file_llseek_size(struct file *file, loff_t offset, int whence, loff_t maxsize, loff_t eof);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812e1450)
Location: fs/read_write.c:86
Inline: True
Direct callers:
  - mm/shmem.c:shmem_file_llseek
  - fs/read_write.c:no_seek_end_llseek_size
  - fs/read_write.c:no_seek_end_llseek
  - fs/read_write.c:fixed_size_llseek
  - fs/read_write.c:generic_file_llseek
  - fs/libfs.c:empty_dir_llseek
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffff812e1450-ffffffff812e1545: generic_file_llseek_size (STB_GLOBAL)
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
