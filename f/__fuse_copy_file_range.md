# Function: <code>__fuse_copy_file_range</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t __fuse_copy_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81410b40)
Location: fs/fuse/file.c:3115
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_copy_file_range
```
**Symbols:**

```
ffffffff81410b40-ffffffff81410e8c: __fuse_copy_file_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t __fuse_copy_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8142a750)
Location: fs/fuse/file.c:3249
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_copy_file_range
```
**Symbols:**

```
ffffffff8142a750-ffffffff8142aa92: __fuse_copy_file_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t __fuse_copy_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8147a8a0)
Location: fs/fuse/file.c:3274
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_copy_file_range
```
**Symbols:**

```
ffffffff8147a8a0-ffffffff8147ac2b: __fuse_copy_file_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t __fuse_copy_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81495520)
Location: fs/fuse/file.c:3333
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_copy_file_range
```
**Symbols:**

```
ffffffff81495520-ffffffff814958b4: __fuse_copy_file_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t __fuse_copy_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8149a580)
Location: fs/fuse/file.c:2987
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_copy_file_range
```
**Symbols:**

```
ffffffff8149a580-ffffffff8149a911: __fuse_copy_file_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t __fuse_copy_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814f1ff0)
Location: fs/fuse/file.c:3022
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_copy_file_range
```
**Symbols:**

```
ffffffff814f1ff0-ffffffff814f2365: __fuse_copy_file_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t __fuse_copy_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81581960)
Location: fs/fuse/file.c:3047
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_copy_file_range
```
**Symbols:**

```
ffffffff81581960-ffffffff81581cd5: __fuse_copy_file_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t __fuse_copy_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff816277e0)
Location: fs/fuse/file.c:3082
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_copy_file_range
```
**Symbols:**

```
ffffffff816277e0-ffffffff81627b55: __fuse_copy_file_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t __fuse_copy_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8165fbb0)
Location: fs/fuse/file.c:3059
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_copy_file_range
```
**Symbols:**

```
ffffffff8165fbb0-ffffffff8165ff33: __fuse_copy_file_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t __fuse_copy_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81699a10)
Location: fs/fuse/file.c:3082
Inline: False
```
**Symbols:**

```
ffffffff81699a10-ffffffff81699d93: __fuse_copy_file_range (STB_LOCAL)
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
ssize_t __fuse_copy_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffff80001050e718)
Location: fs/fuse/file.c:3249
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_copy_file_range
```
**Symbols:**

```
ffff80001050e718-ffff80001050e9c4: __fuse_copy_file_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t __fuse_copy_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (c06c9e70)
Location: fs/fuse/file.c:3249
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_copy_file_range
```
**Symbols:**

```
c06c9e70-c06ca178: __fuse_copy_file_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t __fuse_copy_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (c0000000006558b0)
Location: fs/fuse/file.c:3249
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_copy_file_range
```
**Symbols:**

```
c0000000006558b0-c000000000655c18: __fuse_copy_file_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t __fuse_copy_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffe0003792e0)
Location: fs/fuse/file.c:3249
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_copy_file_range
```
**Symbols:**

```
ffffffe0003792e0-ffffffe00037953e: __fuse_copy_file_range (STB_LOCAL)
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
ssize_t __fuse_copy_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81422d30)
Location: fs/fuse/file.c:3249
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_copy_file_range
```
**Symbols:**

```
ffffffff81422d30-ffffffff81423072: __fuse_copy_file_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t __fuse_copy_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814137b0)
Location: fs/fuse/file.c:3249
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_copy_file_range
```
**Symbols:**

```
ffffffff814137b0-ffffffff81413af2: __fuse_copy_file_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t __fuse_copy_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8141eed0)
Location: fs/fuse/file.c:3249
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_copy_file_range
```
**Symbols:**

```
ffffffff8141eed0-ffffffff8141f212: __fuse_copy_file_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t __fuse_copy_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81435c50)
Location: fs/fuse/file.c:3249
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_copy_file_range
```
**Symbols:**

```
ffffffff81435c50-ffffffff81435f92: __fuse_copy_file_range (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
