# Function: <code>fget_many</code>

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
struct file *fget_many(unsigned int fd, unsigned int refs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812eec90)
Location: fs/file.c:733
Inline: False
Direct callers:
  - fs/io_uring.c:io_submit_sqe
```
**Symbols:**

```
ffffffff812eec90-ffffffff812eeca7: fget_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct file *fget_many(unsigned int fd, unsigned int refs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81300750)
Location: fs/file.c:733
Inline: False
Direct callers:
  - fs/io_uring.c:io_submit_sqe
```
**Symbols:**

```
ffffffff81300750-ffffffff81300767: fget_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct file *fget_many(unsigned int fd, unsigned int refs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81339900)
Location: fs/file.c:746
Inline: False
Direct callers:
  - fs/io_uring.c:io_file_get
```
**Symbols:**

```
ffffffff81339900-ffffffff8133992d: fget_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct file *fget_many(unsigned int fd, unsigned int refs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81345530)
Location: fs/file.c:846
Inline: False
Direct callers:
  - fs/io_uring.c:io_file_get
```
**Symbols:**

```
ffffffff81345530-ffffffff8134555d: fget_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct file *fget_many(unsigned int fd, unsigned int refs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8134b8d0)
Location: fs/file.c:858
Inline: False
Direct callers:
  - fs/io_uring.c:io_file_get
```
**Symbols:**

```
ffffffff8134b8d0-ffffffff8134b8fd: fget_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct file *fget_many(unsigned int fd, unsigned int refs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81399710)
Location: fs/file.c:918
Inline: False
```
**Symbols:**

```
ffffffff81399710-ffffffff8139973d: fget_many (STB_GLOBAL)
```
</details>
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
struct file *fget_many(unsigned int fd, unsigned int refs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffff8000103b2548)
Location: fs/file.c:733
Inline: False
Direct callers:
  - fs/io_uring.c:io_submit_sqe
```
**Symbols:**

```
ffff8000103b2548-ffff8000103b2580: fget_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct file *fget_many(unsigned int fd, unsigned int refs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (c05918ac)
Location: fs/file.c:733
Inline: False
Direct callers:
  - fs/io_uring.c:io_submit_sqe
```
**Symbols:**

```
c05918ac-c05918d0: fget_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct file *fget_many(unsigned int fd, unsigned int refs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (c0000000004ae3f0)
Location: fs/file.c:733
Inline: False
Direct callers:
  - fs/io_uring.c:io_submit_sqe
```
**Symbols:**

```
c0000000004ae3f0-c0000000004ae40c: fget_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct file *fget_many(unsigned int fd, unsigned int refs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffe00027659c)
Location: fs/file.c:733
Inline: False
Direct callers:
  - fs/io_uring.c:io_submit_sqe
```
**Symbols:**

```
ffffffe00027659c-ffffffe0002765d0: fget_many (STB_GLOBAL)
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
struct file *fget_many(unsigned int fd, unsigned int refs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812f8d30)
Location: fs/file.c:733
Inline: False
Direct callers:
  - fs/io_uring.c:io_submit_sqe
```
**Symbols:**

```
ffffffff812f8d30-ffffffff812f8d47: fget_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct file *fget_many(unsigned int fd, unsigned int refs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812e9950)
Location: fs/file.c:733
Inline: False
Direct callers:
  - fs/io_uring.c:io_submit_sqe
```
**Symbols:**

```
ffffffff812e9950-ffffffff812e9967: fget_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct file *fget_many(unsigned int fd, unsigned int refs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812f6b40)
Location: fs/file.c:733
Inline: False
Direct callers:
  - fs/io_uring.c:io_submit_sqe
```
**Symbols:**

```
ffffffff812f6b40-ffffffff812f6b57: fget_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct file *fget_many(unsigned int fd, unsigned int refs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81307d90)
Location: fs/file.c:733
Inline: False
Direct callers:
  - fs/io_uring.c:io_submit_sqe
```
**Symbols:**

```
ffffffff81307d90-ffffffff81307da7: fget_many (STB_GLOBAL)
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
