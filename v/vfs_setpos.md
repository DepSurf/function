# Function: <code>vfs_setpos</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_setpos(struct file *file, loff_t offset, loff_t maxsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8120b9d0)
Location: fs/read_write.c:53
Inline: True
Direct callers:
  - mm/shmem.c:shmem_file_llseek
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffff8120b9d0-ffffffff8120ba11: vfs_setpos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_setpos(struct file *file, loff_t offset, loff_t maxsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812316e0)
Location: fs/read_write.c:55
Inline: True
Direct callers:
  - mm/shmem.c:shmem_file_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/fuse/file.c:fuse_lseek
```
**Symbols:**

```
ffffffff812316e0-ffffffff8123171c: vfs_setpos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_setpos(struct file *file, loff_t offset, loff_t maxsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81243c90)
Location: fs/read_write.c:55
Inline: True
Direct callers:
  - mm/shmem.c:shmem_file_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/fuse/file.c:fuse_lseek
```
**Symbols:**

```
ffffffff81243c90-ffffffff81243ccc: vfs_setpos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_setpos(struct file *file, loff_t offset, loff_t maxsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8124f4a0)
Location: fs/read_write.c:53
Inline: True
Direct callers:
  - mm/shmem.c:shmem_file_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/fuse/file.c:fuse_lseek
```
**Symbols:**

```
ffffffff8124f4a0-ffffffff8124f4dc: vfs_setpos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_setpos(struct file *file, loff_t offset, loff_t maxsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81271430)
Location: fs/read_write.c:54
Inline: True
Direct callers:
  - mm/shmem.c:shmem_file_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/fuse/file.c:fuse_lseek
```
**Symbols:**

```
ffffffff81271430-ffffffff8127146c: vfs_setpos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_setpos(struct file *file, loff_t offset, loff_t maxsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81297130)
Location: fs/read_write.c:54
Inline: True
Direct callers:
  - mm/shmem.c:shmem_file_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/fuse/file.c:fuse_lseek
```
**Symbols:**

```
ffffffff81297130-ffffffff8129716c: vfs_setpos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_setpos(struct file *file, loff_t offset, loff_t maxsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812abde0)
Location: fs/read_write.c:54
Inline: True
Direct callers:
  - mm/shmem.c:shmem_file_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/fuse/file.c:fuse_lseek
```
**Symbols:**

```
ffffffff812abde0-ffffffff812abe1c: vfs_setpos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_setpos(struct file *file, loff_t offset, loff_t maxsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c85f0)
Location: fs/read_write.c:54
Inline: True
Direct callers:
  - mm/shmem.c:shmem_file_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/fuse/file.c:fuse_lseek
```
**Symbols:**

```
ffffffff812c85f0-ffffffff812c862c: vfs_setpos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_setpos(struct file *file, loff_t offset, loff_t maxsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812da000)
Location: fs/read_write.c:54
Inline: True
Direct callers:
  - mm/shmem.c:shmem_file_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/fuse/file.c:fuse_lseek
```
**Symbols:**

```
ffffffff812da000-ffffffff812da03c: vfs_setpos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_setpos(struct file *file, loff_t offset, loff_t maxsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff813104ec)
Location: fs/read_write.c:54
Inline: True
Inline callers:
  - fs/read_write.c:generic_file_llseek_size
  - fs/read_write.c:generic_file_llseek_size
Direct callers:
  - mm/shmem.c:shmem_file_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/fuse/file.c:fuse_lseek
```
**Symbols:**

```
ffffffff81310480-ffffffff813104bc: vfs_setpos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_setpos(struct file *file, loff_t offset, loff_t maxsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8131c79c)
Location: fs/read_write.c:54
Inline: True
Inline callers:
  - fs/read_write.c:generic_file_llseek_size
  - fs/read_write.c:generic_file_llseek_size
Direct callers:
  - mm/shmem.c:shmem_file_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/fuse/file.c:fuse_lseek
```
**Symbols:**

```
ffffffff8131c730-ffffffff8131c76c: vfs_setpos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_setpos(struct file *file, loff_t offset, loff_t maxsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8132290c)
Location: fs/read_write.c:54
Inline: True
Inline callers:
  - fs/read_write.c:generic_file_llseek_size
  - fs/read_write.c:generic_file_llseek_size
Direct callers:
  - mm/shmem.c:shmem_file_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/fuse/file.c:fuse_lseek
```
**Symbols:**

```
ffffffff813228a0-ffffffff813228dc: vfs_setpos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_setpos(struct file *file, loff_t offset, loff_t maxsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8136fdfc)
Location: fs/read_write.c:54
Inline: True
Inline callers:
  - fs/read_write.c:generic_file_llseek_size
  - fs/read_write.c:generic_file_llseek_size
Direct callers:
  - mm/shmem.c:shmem_file_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/fuse/file.c:fuse_lseek
```
**Symbols:**

```
ffffffff8136fd90-ffffffff8136fdcc: vfs_setpos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_setpos(struct file *file, loff_t offset, loff_t maxsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff813ee79a)
Location: fs/read_write.c:54
Inline: True
Inline callers:
  - fs/read_write.c:generic_file_llseek_size
  - fs/read_write.c:generic_file_llseek_size
Direct callers:
  - mm/shmem.c:shmem_file_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/fuse/file.c:fuse_lseek
```
**Symbols:**

```
ffffffff813ee720-ffffffff813ee770: vfs_setpos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_setpos(struct file *file, loff_t offset, loff_t maxsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8147701a)
Location: fs/read_write.c:54
Inline: True
Inline callers:
  - fs/read_write.c:generic_file_llseek_size
  - fs/read_write.c:generic_file_llseek_size
Direct callers:
  - mm/shmem.c:shmem_file_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/fuse/file.c:fuse_lseek
```
**Symbols:**

```
ffffffff81476f90-ffffffff81476fe0: vfs_setpos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_setpos(struct file *file, loff_t offset, loff_t maxsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814ab96a)
Location: fs/read_write.c:54
Inline: True
Inline callers:
  - fs/read_write.c:generic_file_llseek_size
  - fs/read_write.c:generic_file_llseek_size
Direct callers:
  - mm/shmem.c:shmem_file_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/fuse/file.c:fuse_lseek
```
**Symbols:**

```
ffffffff814ab8e0-ffffffff814ab930: vfs_setpos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_setpos(struct file *file, loff_t offset, loff_t maxsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814dce0a)
Location: fs/read_write.c:54
Inline: True
Inline callers:
  - fs/read_write.c:generic_file_llseek_size
  - fs/read_write.c:generic_file_llseek_size
Direct callers:
  - mm/shmem.c:shmem_file_llseek
  - fs/libfs.c:offset_dir_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/fuse/file.c:fuse_lseek
```
**Symbols:**

```
ffffffff814dcd80-ffffffff814dcdd0: vfs_setpos (STB_GLOBAL)
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
loff_t vfs_setpos(struct file *file, loff_t offset, loff_t maxsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffff80001037f3c8)
Location: fs/read_write.c:54
Inline: True
Direct callers:
  - mm/shmem.c:shmem_file_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/fuse/file.c:fuse_lseek
```
**Symbols:**

```
ffff80001037f3c8-ffff80001037f430: vfs_setpos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_setpos(struct file *file, loff_t offset, loff_t maxsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c0569be0)
Location: fs/read_write.c:54
Inline: True
Direct callers:
  - mm/shmem.c:shmem_file_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/fuse/file.c:fuse_file_llseek
```
**Symbols:**

```
c0569be0-c0569c58: vfs_setpos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_setpos(struct file *file, loff_t offset, loff_t maxsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c000000000475270)
Location: fs/read_write.c:54
Inline: True
Direct callers:
  - mm/shmem.c:shmem_file_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/fuse/file.c:fuse_lseek
```
**Symbols:**

```
c000000000475270-c0000000004752c4: vfs_setpos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_setpos(struct file *file, loff_t offset, loff_t maxsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffe000254ee0)
Location: fs/read_write.c:54
Inline: True
Direct callers:
  - mm/shmem.c:shmem_file_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/fuse/file.c:fuse_lseek
```
**Symbols:**

```
ffffffe000254ee0-ffffffe000254f36: vfs_setpos (STB_GLOBAL)
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
loff_t vfs_setpos(struct file *file, loff_t offset, loff_t maxsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d25e0)
Location: fs/read_write.c:54
Inline: True
Direct callers:
  - mm/shmem.c:shmem_file_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/fuse/file.c:fuse_lseek
```
**Symbols:**

```
ffffffff812d25e0-ffffffff812d261c: vfs_setpos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_setpos(struct file *file, loff_t offset, loff_t maxsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c3260)
Location: fs/read_write.c:54
Inline: True
Direct callers:
  - mm/shmem.c:shmem_file_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/fuse/file.c:fuse_lseek
```
**Symbols:**

```
ffffffff812c3260-ffffffff812c329c: vfs_setpos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_setpos(struct file *file, loff_t offset, loff_t maxsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d03f0)
Location: fs/read_write.c:54
Inline: True
Direct callers:
  - mm/shmem.c:shmem_file_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/fuse/file.c:fuse_lseek
```
**Symbols:**

```
ffffffff812d03f0-ffffffff812d042c: vfs_setpos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_setpos(struct file *file, loff_t offset, loff_t maxsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812e1220)
Location: fs/read_write.c:54
Inline: True
Direct callers:
  - mm/shmem.c:shmem_file_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/fuse/file.c:fuse_lseek
```
**Symbols:**

```
ffffffff812e1220-ffffffff812e125c: vfs_setpos (STB_GLOBAL)
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
