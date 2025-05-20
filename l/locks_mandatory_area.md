# Function: <code>locks_mandatory_area</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int locks_mandatory_area(int read_write, struct inode *inode, struct file *filp, loff_t offset, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81260c70)
Location: fs/locks.c:1241
Inline: False
Direct callers:
  - fs/open.c:vfs_truncate
  - fs/read_write.c:rw_verify_area
  - fs/read_write.c:rw_verify_area
```
**Symbols:**

```
ffffffff81260c70-ffffffff81260e86: locks_mandatory_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int locks_mandatory_area(struct inode *inode, struct file *filp, loff_t start, loff_t end, unsigned char type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8128d160)
Location: fs/locks.c:1269
Inline: False
Direct callers:
  - fs/open.c:vfs_truncate
  - fs/open.c:vfs_truncate
  - fs/read_write.c:clone_verify_area
  - fs/read_write.c:rw_verify_area
```
**Symbols:**

```
ffffffff8128d160-ffffffff8128d36f: locks_mandatory_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int locks_mandatory_area(struct inode *inode, struct file *filp, loff_t start, loff_t end, unsigned char type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812a2de0)
Location: fs/locks.c:1293
Inline: False
Direct callers:
  - fs/open.c:vfs_truncate
  - fs/open.c:vfs_truncate
  - fs/read_write.c:clone_verify_area
  - fs/read_write.c:rw_verify_area
```
**Symbols:**

```
ffffffff812a2de0-ffffffff812a2fbb: locks_mandatory_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int locks_mandatory_area(struct inode *inode, struct file *filp, loff_t start, loff_t end, unsigned char type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812b1fd0)
Location: fs/locks.c:1293
Inline: False
Direct callers:
  - fs/open.c:vfs_truncate
  - fs/open.c:vfs_truncate
  - fs/read_write.c:clone_verify_area
  - fs/read_write.c:rw_verify_area
```
**Symbols:**

```
ffffffff812b1fd0-ffffffff812b219a: locks_mandatory_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int locks_mandatory_area(struct inode *inode, struct file *filp, loff_t start, loff_t end, unsigned char type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812d5b30)
Location: fs/locks.c:1303
Inline: False
Direct callers:
  - fs/open.c:vfs_truncate
  - fs/open.c:vfs_truncate
  - fs/read_write.c:clone_verify_area
  - fs/read_write.c:rw_verify_area
```
**Symbols:**

```
ffffffff812d5b30-ffffffff812d5cf6: locks_mandatory_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int locks_mandatory_area(struct inode *inode, struct file *filp, loff_t start, loff_t end, unsigned char type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813005e0)
Location: fs/locks.c:1303
Inline: False
Direct callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/open.c:vfs_truncate
  - fs/read_write.c:clone_verify_area
  - fs/read_write.c:rw_verify_area
```
**Symbols:**

```
ffffffff813005e0-ffffffff813007a6: locks_mandatory_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int locks_mandatory_area(struct inode *inode, struct file *filp, loff_t start, loff_t end, unsigned char type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81316170)
Location: fs/locks.c:1423
Inline: False
Direct callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/open.c:vfs_truncate
  - fs/read_write.c:remap_verify_area
  - fs/read_write.c:rw_verify_area
```
**Symbols:**

```
ffffffff81316170-ffffffff81316335: locks_mandatory_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int locks_mandatory_area(struct inode *inode, struct file *filp, loff_t start, loff_t end, unsigned char type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133d950)
Location: fs/locks.c:1419
Inline: False
Direct callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/open.c:vfs_truncate
  - fs/read_write.c:remap_verify_area
  - fs/read_write.c:rw_verify_area
```
**Symbols:**

```
ffffffff8133d950-ffffffff8133db12: locks_mandatory_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int locks_mandatory_area(struct inode *inode, struct file *filp, loff_t start, loff_t end, unsigned char type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81355f10)
Location: fs/locks.c:1444
Inline: False
Direct callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/open.c:vfs_truncate
  - fs/read_write.c:remap_verify_area
  - fs/read_write.c:rw_verify_area
```
**Symbols:**

```
ffffffff81355f10-ffffffff813560e1: locks_mandatory_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int locks_mandatory_area(struct inode *inode, struct file *filp, loff_t start, loff_t end, unsigned char type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8139cce0)
Location: fs/locks.c:1444
Inline: False
Direct callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/open.c:vfs_truncate
  - fs/read_write.c:remap_verify_area
  - fs/read_write.c:rw_verify_area
```
**Symbols:**

```
ffffffff8139cce0-ffffffff8139cf1c: locks_mandatory_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int locks_mandatory_area(struct inode *inode, struct file *filp, loff_t start, loff_t end, unsigned char type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813ae6b0)
Location: fs/locks.c:1445
Inline: False
Direct callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/open.c:vfs_truncate
  - fs/read_write.c:rw_verify_area
  - fs/remap_range.c:remap_verify_area
```
**Symbols:**

```
ffffffff813ae6b0-ffffffff813ae8ec: locks_mandatory_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/read_write.c (0)
Location: include/linux/fs.h:2628
Inline: True
```
```
In fs/remap_range.c (0)
Location: include/linux/fs.h:2628
Inline: True
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int locks_mandatory_area(struct inode *inode, struct file *filp, loff_t start, loff_t end, unsigned char type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffff800010418a68)
Location: fs/locks.c:1444
Inline: False
Direct callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/open.c:vfs_truncate
  - fs/read_write.c:remap_verify_area
  - fs/read_write.c:rw_verify_area
```
**Symbols:**

```
ffff800010418a68-ffff800010418c10: locks_mandatory_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int locks_mandatory_area(struct inode *inode, struct file *filp, loff_t start, loff_t end, unsigned char type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (c05e3458)
Location: fs/locks.c:1444
Inline: False
Direct callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/read_write.c:remap_verify_area
  - fs/read_write.c:rw_verify_area
```
**Symbols:**

```
c05e3458-c05e3608: locks_mandatory_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int locks_mandatory_area(struct inode *inode, struct file *filp, loff_t start, loff_t end, unsigned char type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (c000000000526650)
Location: fs/locks.c:1444
Inline: False
Direct callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/open.c:vfs_truncate
  - fs/read_write.c:remap_verify_area
  - fs/read_write.c:rw_verify_area
```
**Symbols:**

```
c000000000526650-c000000000526874: locks_mandatory_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int locks_mandatory_area(struct inode *inode, struct file *filp, loff_t start, loff_t end, unsigned char type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffe0002bf44a)
Location: fs/locks.c:1444
Inline: False
Direct callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/open.c:vfs_truncate
  - fs/read_write.c:remap_verify_area
  - fs/read_write.c:rw_verify_area
```
**Symbols:**

```
ffffffe0002bf44a-ffffffe0002bf5a2: locks_mandatory_area (STB_GLOBAL)
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
int locks_mandatory_area(struct inode *inode, struct file *filp, loff_t start, loff_t end, unsigned char type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8134e4f0)
Location: fs/locks.c:1444
Inline: False
Direct callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/open.c:vfs_truncate
  - fs/read_write.c:remap_verify_area
  - fs/read_write.c:rw_verify_area
```
**Symbols:**

```
ffffffff8134e4f0-ffffffff8134e6c1: locks_mandatory_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int locks_mandatory_area(struct inode *inode, struct file *filp, loff_t start, loff_t end, unsigned char type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133f1d0)
Location: fs/locks.c:1444
Inline: False
Direct callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/open.c:vfs_truncate
  - fs/read_write.c:remap_verify_area
  - fs/read_write.c:rw_verify_area
```
**Symbols:**

```
ffffffff8133f1d0-ffffffff8133f3a1: locks_mandatory_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int locks_mandatory_area(struct inode *inode, struct file *filp, loff_t start, loff_t end, unsigned char type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8134bfc0)
Location: fs/locks.c:1444
Inline: False
Direct callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/open.c:vfs_truncate
  - fs/read_write.c:remap_verify_area
  - fs/read_write.c:rw_verify_area
```
**Symbols:**

```
ffffffff8134bfc0-ffffffff8134c191: locks_mandatory_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int locks_mandatory_area(struct inode *inode, struct file *filp, loff_t start, loff_t end, unsigned char type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8135de20)
Location: fs/locks.c:1444
Inline: False
Direct callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/open.c:vfs_truncate
  - fs/read_write.c:remap_verify_area
  - fs/read_write.c:rw_verify_area
```
**Symbols:**

```
ffffffff8135de20-ffffffff8135dfec: locks_mandatory_area (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>loff_t start</code>
</li>
<li>
<b>Param added. </b>
<code>loff_t end</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned char type</code>
</li>
<li>
<b>Param removed. </b>
<code>int read_write</code>
</li>
<li>
<b>Param removed. </b>
<code>loff_t offset</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t count</code>
</li>
<li>
<b>Param reordered. </b>
<code>read_write, inode, filp, offset, count</code> ➡️ <code>inode, filp, start, end, type</code>
</li>
</ul>
</details>
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
