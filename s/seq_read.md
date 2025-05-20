# Function: <code>seq_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t seq_read(struct file *file, char *buf, size_t size, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81230a60)
Location: fs/seq_file.c:168
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/pstore/inode.c:pstore_file_read
```
**Symbols:**

```
ffffffff81230a60-ffffffff81230de3: seq_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t seq_read(struct file *file, char *buf, size_t size, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81259730)
Location: fs/seq_file.c:169
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/pstore/inode.c:pstore_file_read
```
**Symbols:**

```
ffffffff81259730-ffffffff81259aee: seq_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t seq_read(struct file *file, char *buf, size_t size, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8126cef0)
Location: fs/seq_file.c:169
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/pstore/inode.c:pstore_file_read
```
**Symbols:**

```
ffffffff8126cef0-ffffffff8126d2bf: seq_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t seq_read(struct file *file, char *buf, size_t size, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81279d80)
Location: fs/seq_file.c:155
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/pstore/inode.c:pstore_file_read
```
**Symbols:**

```
ffffffff81279d80-ffffffff8127a16d: seq_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t seq_read(struct file *file, char *buf, size_t size, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8129c7c0)
Location: fs/seq_file.c:156
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/pstore/inode.c:pstore_file_read
```
**Symbols:**

```
ffffffff8129c7c0-ffffffff8129cbed: seq_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t seq_read(struct file *file, char *buf, size_t size, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812c3990)
Location: fs/seq_file.c:159
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/pstore/inode.c:pstore_file_read
```
**Symbols:**

```
ffffffff812c3990-ffffffff812c3ddc: seq_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t seq_read(struct file *file, char *buf, size_t size, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812d8b30)
Location: fs/seq_file.c:153
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/pstore/inode.c:pstore_file_read
```
**Symbols:**

```
ffffffff812d8b30-ffffffff812d8f30: seq_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t seq_read(struct file *file, char *buf, size_t size, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812f6fc0)
Location: fs/seq_file.c:153
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/pstore/inode.c:pstore_file_read
```
**Symbols:**

```
ffffffff812f6fc0-ffffffff812f73ee: seq_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t seq_read(struct file *file, char *buf, size_t size, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff813088e0)
Location: fs/seq_file.c:153
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/pstore/inode.c:pstore_file_read
```
**Symbols:**

```
ffffffff813088e0-ffffffff81308d46: seq_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
ssize_t seq_read(struct file *file, char *buf, size_t size, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/seq_file.c (0)
Location: fs/seq_file.c:147
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/pstore/inode.c:pstore_file_read
```
**Symbols:**

```
ffffffff81342902-ffffffff81342923: seq_read.cold (STB_LOCAL)
ffffffff81342200-ffffffff81342662: seq_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t seq_read(struct file *file, char *buf, size_t size, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8134df30)
Location: fs/seq_file.c:148
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_file_read
```
**Symbols:**

```
ffffffff8134df30-ffffffff8134e06d: seq_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t seq_read(struct file *file, char *buf, size_t size, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81355260)
Location: fs/seq_file.c:151
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_file_read
```
**Symbols:**

```
ffffffff81355260-ffffffff81355392: seq_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t seq_read(struct file *file, char *buf, size_t size, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff813a3670)
Location: fs/seq_file.c:151
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_file_read
```
**Symbols:**

```
ffffffff813a3670-ffffffff813a37a5: seq_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t seq_read(struct file *file, char *buf, size_t size, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff814273f0)
Location: fs/seq_file.c:151
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_file_read
```
**Symbols:**

```
ffffffff814273f0-ffffffff81427537: seq_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t seq_read(struct file *file, char *buf, size_t size, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff814b3ee0)
Location: fs/seq_file.c:151
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_file_read
```
**Symbols:**

```
ffffffff814b3ee0-ffffffff814b3fe4: seq_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t seq_read(struct file *file, char *buf, size_t size, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff814e8f70)
Location: fs/seq_file.c:151
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_file_read
```
**Symbols:**

```
ffffffff814e8f70-ffffffff814e9074: seq_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t seq_read(struct file *file, char *buf, size_t size, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8151ce00)
Location: fs/seq_file.c:151
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_file_read
```
**Symbols:**

```
ffffffff8151ce00-ffffffff8151cf5f: seq_read (STB_GLOBAL)
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
ssize_t seq_read(struct file *file, char *buf, size_t size, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffff8000103bcb08)
Location: fs/seq_file.c:153
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/pstore/inode.c:pstore_file_read
```
**Symbols:**

```
ffff8000103bcb08-ffff8000103bd058: seq_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t seq_read(struct file *file, char *buf, size_t size, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (c0599d80)
Location: fs/seq_file.c:153
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/pstore/inode.c:pstore_file_read
```
**Symbols:**

```
c0599d80-c059a33c: seq_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t seq_read(struct file *file, char *buf, size_t size, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (c0000000004ba1a0)
Location: fs/seq_file.c:153
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/pstore/inode.c:pstore_file_read
```
**Symbols:**

```
c0000000004ba1a0-c0000000004ba7a4: seq_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t seq_read(struct file *file, char *buf, size_t size, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffe00027e0aa)
Location: fs/seq_file.c:153
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/pstore/inode.c:pstore_file_read
```
**Symbols:**

```
ffffffe00027e0aa-ffffffe00027e3b4: seq_read (STB_GLOBAL)
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
ssize_t seq_read(struct file *file, char *buf, size_t size, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81300ec0)
Location: fs/seq_file.c:153
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/pstore/inode.c:pstore_file_read
```
**Symbols:**

```
ffffffff81300ec0-ffffffff81301326: seq_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t seq_read(struct file *file, char *buf, size_t size, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812f1ae0)
Location: fs/seq_file.c:153
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/pstore/inode.c:pstore_file_read
```
**Symbols:**

```
ffffffff812f1ae0-ffffffff812f1f46: seq_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t seq_read(struct file *file, char *buf, size_t size, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812fecb0)
Location: fs/seq_file.c:153
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/pstore/inode.c:pstore_file_read
```
**Symbols:**

```
ffffffff812fecb0-ffffffff812ff116: seq_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t seq_read(struct file *file, char *buf, size_t size, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8130fff0)
Location: fs/seq_file.c:153
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/pstore/inode.c:pstore_file_read
```
**Symbols:**

```
ffffffff8130fff0-ffffffff81310456: seq_read (STB_GLOBAL)
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
