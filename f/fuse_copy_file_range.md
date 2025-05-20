# Function: <code>fuse_copy_file_range</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t fuse_copy_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813e50c0)
Location: fs/fuse/file.c:3029
Inline: False
```
**Symbols:**

```
ffffffff813e50c0-ffffffff813e5325: fuse_copy_file_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t fuse_copy_file_range(struct file *src_file, loff_t src_off, struct file *dst_file, loff_t dst_off, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81410e90)
Location: fs/fuse/file.c:3205
Inline: False
```
**Symbols:**

```
ffffffff81410e90-ffffffff81410f00: fuse_copy_file_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t fuse_copy_file_range(struct file *src_file, loff_t src_off, struct file *dst_file, loff_t dst_off, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8142aaa0)
Location: fs/fuse/file.c:3339
Inline: False
```
**Symbols:**

```
ffffffff8142aaa0-ffffffff8142ab10: fuse_copy_file_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t fuse_copy_file_range(struct file *src_file, loff_t src_off, struct file *dst_file, loff_t dst_off, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8147ac30)
Location: fs/fuse/file.c:3382
Inline: False
```
**Symbols:**

```
ffffffff8147ac30-ffffffff8147aca0: fuse_copy_file_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t fuse_copy_file_range(struct file *src_file, loff_t src_off, struct file *dst_file, loff_t dst_off, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814958c0)
Location: fs/fuse/file.c:3442
Inline: False
```
**Symbols:**

```
ffffffff814958c0-ffffffff81495930: fuse_copy_file_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t fuse_copy_file_range(struct file *src_file, loff_t src_off, struct file *dst_file, loff_t dst_off, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8149a920)
Location: fs/fuse/file.c:3096
Inline: False
```
**Symbols:**

```
ffffffff8149a920-ffffffff8149a990: fuse_copy_file_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t fuse_copy_file_range(struct file *src_file, loff_t src_off, struct file *dst_file, loff_t dst_off, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814f2370)
Location: fs/fuse/file.c:3133
Inline: False
```
**Symbols:**

```
ffffffff814f2370-ffffffff814f23e0: fuse_copy_file_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t fuse_copy_file_range(struct file *src_file, loff_t src_off, struct file *dst_file, loff_t dst_off, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81581ce0)
Location: fs/fuse/file.c:3154
Inline: False
```
**Symbols:**

```
ffffffff81581ce0-ffffffff81581d74: fuse_copy_file_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t fuse_copy_file_range(struct file *src_file, loff_t src_off, struct file *dst_file, loff_t dst_off, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81627b70)
Location: fs/fuse/file.c:3189
Inline: False
```
**Symbols:**

```
ffffffff81627b70-ffffffff81627c04: fuse_copy_file_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t fuse_copy_file_range(struct file *src_file, loff_t src_off, struct file *dst_file, loff_t dst_off, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8165ff50)
Location: fs/fuse/file.c:3166
Inline: False
```
**Symbols:**

```
ffffffff8165ff50-ffffffff8165ffe4: fuse_copy_file_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t fuse_copy_file_range(struct file *src_file, loff_t src_off, struct file *dst_file, loff_t dst_off, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81699db0)
Location: fs/fuse/file.c:3189
Inline: True
```
**Symbols:**

```
ffffffff81699db0-ffffffff81699e4a: fuse_copy_file_range (STB_LOCAL)
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
ssize_t fuse_copy_file_range(struct file *src_file, loff_t src_off, struct file *dst_file, loff_t dst_off, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffff80001050e9c8)
Location: fs/fuse/file.c:3339
Inline: False
```
**Symbols:**

```
ffff80001050e9c8-ffff80001050ea68: fuse_copy_file_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t fuse_copy_file_range(struct file *src_file, loff_t src_off, struct file *dst_file, loff_t dst_off, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (c06ca178)
Location: fs/fuse/file.c:3339
Inline: False
```
**Symbols:**

```
c06ca178-c06ca200: fuse_copy_file_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t fuse_copy_file_range(struct file *src_file, loff_t src_off, struct file *dst_file, loff_t dst_off, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (c000000000655c20)
Location: fs/fuse/file.c:3339
Inline: False
```
**Symbols:**

```
c000000000655c20-c000000000655cf8: fuse_copy_file_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t fuse_copy_file_range(struct file *src_file, loff_t src_off, struct file *dst_file, loff_t dst_off, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffe00037953e)
Location: fs/fuse/file.c:3339
Inline: False
```
**Symbols:**

```
ffffffe00037953e-ffffffe0003795b4: fuse_copy_file_range (STB_LOCAL)
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
ssize_t fuse_copy_file_range(struct file *src_file, loff_t src_off, struct file *dst_file, loff_t dst_off, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81423080)
Location: fs/fuse/file.c:3339
Inline: False
```
**Symbols:**

```
ffffffff81423080-ffffffff814230f0: fuse_copy_file_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t fuse_copy_file_range(struct file *src_file, loff_t src_off, struct file *dst_file, loff_t dst_off, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81413b00)
Location: fs/fuse/file.c:3339
Inline: False
```
**Symbols:**

```
ffffffff81413b00-ffffffff81413b70: fuse_copy_file_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t fuse_copy_file_range(struct file *src_file, loff_t src_off, struct file *dst_file, loff_t dst_off, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8141f220)
Location: fs/fuse/file.c:3339
Inline: False
```
**Symbols:**

```
ffffffff8141f220-ffffffff8141f290: fuse_copy_file_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t fuse_copy_file_range(struct file *src_file, loff_t src_off, struct file *dst_file, loff_t dst_off, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81435fa0)
Location: fs/fuse/file.c:3339
Inline: False
```
**Symbols:**

```
ffffffff81435fa0-ffffffff81436010: fuse_copy_file_range (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct file *src_file</code>
</li>
<li>
<b>Param added. </b>
<code>loff_t src_off</code>
</li>
<li>
<b>Param added. </b>
<code>struct file *dst_file</code>
</li>
<li>
<b>Param added. </b>
<code>loff_t dst_off</code>
</li>
<li>
<b>Param removed. </b>
<code>struct file *file_in</code>
</li>
<li>
<b>Param removed. </b>
<code>loff_t pos_in</code>
</li>
<li>
<b>Param removed. </b>
<code>struct file *file_out</code>
</li>
<li>
<b>Param removed. </b>
<code>loff_t pos_out</code>
</li>
</ul>
</details>
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
