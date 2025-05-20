# Function: <code>fuse_file_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct fuse_file *fuse_file_get(struct fuse_file *ff);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81314efe)
Location: fs/fuse/file.c:78
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_write_file_get
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_do_open
  - fs/fuse/file.c:fuse_writepages_send
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
```
**Symbols:**

```
ffffffff813174e0-ffffffff813174f2: fuse_file_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct fuse_file *fuse_file_get(struct fuse_file *ff);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8134e9b2)
Location: fs/fuse/file.c:78
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:__fuse_write_file_get
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_do_open
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
```
**Symbols:**

```
ffffffff8134be00-ffffffff8134be12: fuse_file_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct fuse_file *fuse_file_get(struct fuse_file *ff);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813642c2)
Location: fs/fuse/file.c:78
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:__fuse_write_file_get
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_do_open
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
```
**Symbols:**

```
ffffffff81361710-ffffffff81361722: fuse_file_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81378ad2)
Location: fs/fuse/file.c:78
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:__fuse_write_file_get
  - fs/fuse/file.c:fuse_writepage_end
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct fuse_file *fuse_file_get(struct fuse_file *ff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813986c0)
Location: fs/fuse/file.c:78
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:__fuse_write_file_get
  - fs/fuse/file.c:fuse_writepage_end
```
**Symbols:**

```
ffffffff813986c0-ffffffff813986d8: fuse_file_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct fuse_file *fuse_file_get(struct fuse_file *ff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813c78c0)
Location: fs/fuse/file.c:78
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:__fuse_write_file_get
  - fs/fuse/file.c:fuse_writepage_end
```
**Symbols:**

```
ffffffff813c78c0-ffffffff813c78d8: fuse_file_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct fuse_file *fuse_file_get(struct fuse_file *ff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813e0b10)
Location: fs/fuse/file.c:81
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:__fuse_write_file_get
  - fs/fuse/file.c:fuse_writepage_end
```
**Symbols:**

```
ffffffff813e0b10-ffffffff813e0b28: fuse_file_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct fuse_file *fuse_file_get(struct fuse_file *ff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8140c740)
Location: fs/fuse/file.c:77
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_end
```
**Symbols:**

```
ffffffff8140c740-ffffffff8140c758: fuse_file_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct fuse_file *fuse_file_get(struct fuse_file *ff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81426270)
Location: fs/fuse/file.c:96
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_end
```
**Symbols:**

```
ffffffff81426270-ffffffff81426288: fuse_file_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8147ba7c)
Location: fs/fuse/file.c:97
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_write_inode
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_send_readpages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81496dd7)
Location: fs/fuse/file.c:103
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_write_inode
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_send_readpages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8149bed6)
Location: fs/fuse/file.c:91
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_write_inode
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_readahead
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814f336c)
Location: fs/fuse/file.c:91
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_write_inode
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_readahead
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81582dac)
Location: fs/fuse/file.c:91
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_write_inode
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_readahead
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81628d1c)
Location: fs/fuse/file.c:91
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_write_inode
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_readahead
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81660f3c)
Location: fs/fuse/file.c:92
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_write_inode
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_readahead
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8169adfc)
Location: fs/fuse/file.c:93
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_write_inode
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_readahead
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffff80001050fb9c)
Location: fs/fuse/file.c:96
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_end
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (c06cb3dc)
Location: fs/fuse/file.c:96
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_send_readpages
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (c00000000065730c)
Location: fs/fuse/file.c:96
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_send_readpages
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffe00037a428)
Location: fs/fuse/file.c:96
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_send_readpages
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
struct fuse_file *fuse_file_get(struct fuse_file *ff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8141e850)
Location: fs/fuse/file.c:96
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_end
```
**Symbols:**

```
ffffffff8141e850-ffffffff8141e868: fuse_file_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct fuse_file *fuse_file_get(struct fuse_file *ff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8140f2d0)
Location: fs/fuse/file.c:96
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_end
```
**Symbols:**

```
ffffffff8140f2d0-ffffffff8140f2e8: fuse_file_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct fuse_file *fuse_file_get(struct fuse_file *ff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8141a9f0)
Location: fs/fuse/file.c:96
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_end
```
**Symbols:**

```
ffffffff8141a9f0-ffffffff8141aa08: fuse_file_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct fuse_file *fuse_file_get(struct fuse_file *ff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81431790)
Location: fs/fuse/file.c:96
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_end
```
**Symbols:**

```
ffffffff81431790-ffffffff814317a8: fuse_file_get (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
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
