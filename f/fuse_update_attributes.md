# Function: <code>fuse_update_attributes</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fuse_update_attributes(struct inode *inode, struct kstat *stat, struct file *file, bool *refreshed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81314000)
Location: fs/fuse/dir.c:909
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff81314000-ffffffff8131406f: fuse_update_attributes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fuse_update_attributes(struct inode *inode, struct kstat *stat, struct file *file, bool *refreshed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81348630)
Location: fs/fuse/dir.c:913
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_lseek
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
```
**Symbols:**

```
ffffffff81348630-ffffffff8134869f: fuse_update_attributes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fuse_update_attributes(struct inode *inode, struct kstat *stat, struct file *file, bool *refreshed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8135dfb0)
Location: fs/fuse/dir.c:926
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_lseek
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
```
**Symbols:**

```
ffffffff8135dfb0-ffffffff8135e03a: fuse_update_attributes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fuse_update_attributes(struct inode *inode, struct kstat *stat, struct file *file, bool *refreshed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81372a90)
Location: fs/fuse/dir.c:926
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_lseek
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
```
**Symbols:**

```
ffffffff81372a90-ffffffff81372b1b: fuse_update_attributes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fuse_update_attributes(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff813977a0)
Location: fs/fuse/dir.c:944
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_lseek
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
```
**Symbols:**

```
ffffffff813977a0-ffffffff813977dc: fuse_update_attributes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int fuse_update_attributes(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff813c6a00)
Location: fs/fuse/dir.c:953
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_lseek
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
```
**Symbols:**

```
ffffffff813c6a00-ffffffff813c6a3c: fuse_update_attributes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int fuse_update_attributes(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff813dfbc0)
Location: fs/fuse/dir.c:953
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_lseek
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
ffffffff813dfbc0-ffffffff813dfc09: fuse_update_attributes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fuse_update_attributes(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8140b7c0)
Location: fs/fuse/dir.c:940
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_lseek
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
ffffffff8140b7c0-ffffffff8140b813: fuse_update_attributes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fuse_update_attributes(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81425270)
Location: fs/fuse/dir.c:998
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_lseek
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
ffffffff81425270-ffffffff814252c3: fuse_update_attributes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fuse_update_attributes(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff814749a0)
Location: fs/fuse/dir.c:998
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_lseek
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/readdir.c:fuse_readdir_cached
```
**Symbols:**

```
ffffffff814749a0-ffffffff814749f3: fuse_update_attributes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fuse_update_attributes(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8148f380)
Location: fs/fuse/dir.c:1098
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_lseek
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/readdir.c:fuse_readdir_cached
```
**Symbols:**

```
ffffffff8148f380-ffffffff8148f3d3: fuse_update_attributes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fuse_update_attributes(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81494da0)
Location: fs/fuse/dir.c:1115
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_lseek
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/readdir.c:fuse_readdir_cached
```
**Symbols:**

```
ffffffff81494da0-ffffffff81494df3: fuse_update_attributes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fuse_update_attributes(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff814ec830)
Location: fs/fuse/dir.c:1063
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_lseek
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/readdir.c:fuse_readdir_cached
```
**Symbols:**

```
ffffffff814ec830-ffffffff814ec883: fuse_update_attributes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fuse_update_attributes(struct inode *inode, struct file *file, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8157b560)
Location: fs/fuse/dir.c:1145
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_lseek
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/readdir.c:fuse_readdir_cached
```
**Symbols:**

```
ffffffff8157b560-ffffffff8157b5dc: fuse_update_attributes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fuse_update_attributes(struct inode *inode, struct file *file, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81620e70)
Location: fs/fuse/dir.c:1168
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_lseek
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/readdir.c:fuse_readdir_cached
```
**Symbols:**

```
ffffffff81620e70-ffffffff81620eec: fuse_update_attributes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fuse_update_attributes(struct inode *inode, struct file *file, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff816592c0)
Location: fs/fuse/dir.c:1234
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_lseek
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/readdir.c:fuse_readdir_cached
```
**Symbols:**

```
ffffffff816592c0-ffffffff8165933c: fuse_update_attributes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fuse_update_attributes(struct inode *inode, struct file *file, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81693000)
Location: fs/fuse/dir.c:1335
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_lseek
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/readdir.c:fuse_readdir_cached
```
**Symbols:**

```
ffffffff81693000-ffffffff81693026: fuse_update_attributes (STB_GLOBAL)
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
int fuse_update_attributes(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffff800010508980)
Location: fs/fuse/dir.c:998
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_lseek
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
ffff800010508980-ffff8000105089f4: fuse_update_attributes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fuse_update_attributes(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (c06c4900)
Location: fs/fuse/dir.c:998
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/readdir.c:fuse_readdir_cached
```
**Symbols:**

```
c06c4900-c06c4930: fuse_update_attributes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fuse_update_attributes(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (c00000000064e390)
Location: fs/fuse/dir.c:998
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_lseek
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/readdir.c:fuse_readdir_cached
```
**Symbols:**

```
c00000000064e390-c00000000064e414: fuse_update_attributes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fuse_update_attributes(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffe000374554)
Location: fs/fuse/dir.c:998
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_lseek
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
ffffffe000374554-ffffffe0003745bc: fuse_update_attributes (STB_GLOBAL)
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
int fuse_update_attributes(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8141d850)
Location: fs/fuse/dir.c:998
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_lseek
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
ffffffff8141d850-ffffffff8141d8a3: fuse_update_attributes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fuse_update_attributes(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8140e2d0)
Location: fs/fuse/dir.c:998
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_lseek
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
ffffffff8140e2d0-ffffffff8140e323: fuse_update_attributes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fuse_update_attributes(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff814199f0)
Location: fs/fuse/dir.c:998
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_lseek
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
ffffffff814199f0-ffffffff81419a43: fuse_update_attributes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fuse_update_attributes(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81430760)
Location: fs/fuse/dir.c:998
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_lseek
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
ffffffff81430760-ffffffff814307b3: fuse_update_attributes (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct kstat *stat</code>
</li>
<li>
<b>Param removed. </b>
<code>bool *refreshed</code>
</li>
<li>
<b>Param reordered. </b>
<code>inode, stat, file, refreshed</code> ➡️ <code>inode, file</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 mask</code>
</li>
</ul>
</details>
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
