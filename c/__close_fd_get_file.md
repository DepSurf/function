# Function: <code>__close_fd_get_file</code>

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
int __close_fd_get_file(unsigned int fd, struct file **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812d1440)
Location: fs/file.c:646
Inline: False
```
**Symbols:**

```
ffffffff812d1440-ffffffff812d1502: __close_fd_get_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __close_fd_get_file(unsigned int fd, struct file **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812ee460)
Location: fs/file.c:647
Inline: False
```
**Symbols:**

```
ffffffff812ee460-ffffffff812ee523: __close_fd_get_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __close_fd_get_file(unsigned int fd, struct file **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812fff20)
Location: fs/file.c:647
Inline: False
```
**Symbols:**

```
ffffffff812fff20-ffffffff812fffe3: __close_fd_get_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __close_fd_get_file(unsigned int fd, struct file **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81339060)
Location: fs/file.c:654
Inline: False
Direct callers:
  - fs/io_uring.c:io_issue_sqe
```
**Symbols:**

```
ffffffff81339060-ffffffff8133911c: __close_fd_get_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __close_fd_get_file(unsigned int fd, struct file **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81345340)
Location: fs/file.c:740
Inline: False
Direct callers:
  - fs/file.c:close_fd_get_file
  - fs/io_uring.c:io_close
```
**Symbols:**

```
ffffffff81345340-ffffffff813453bb: __close_fd_get_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __close_fd_get_file(unsigned int fd, struct file **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8134b6d0)
Location: fs/file.c:753
Inline: False
Direct callers:
  - fs/file.c:close_fd_get_file
  - fs/io_uring.c:io_issue_sqe
```
**Symbols:**

```
ffffffff8134b6d0-ffffffff8134b751: __close_fd_get_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __close_fd_get_file(unsigned int fd, struct file **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81399510)
Location: fs/file.c:769
Inline: False
Direct callers:
  - fs/file.c:close_fd_get_file
  - fs/io_uring.c:io_close
```
**Symbols:**

```
ffffffff81399510-ffffffff81399591: __close_fd_get_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct file *__close_fd_get_file(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8141bee0)
Location: fs/file.c:796
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_close
```
**Symbols:**

```
ffffffff8141bee0-ffffffff8141bf6b: __close_fd_get_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct file *__close_fd_get_file(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff814a8070)
Location: fs/file.c:796
Inline: False
Direct callers:
  - io_uring/openclose.c:io_close
```
**Symbols:**

```
ffffffff814a8070-ffffffff814a809a: __close_fd_get_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct file *__close_fd_get_file(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff814dd050)
Location: fs/file.c:797
Inline: False
Direct callers:
  - io_uring/openclose.c:io_close
```
**Symbols:**

```
ffffffff814dd050-ffffffff814dd07a: __close_fd_get_file (STB_GLOBAL)
```
</details>
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
int __close_fd_get_file(unsigned int fd, struct file **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffff8000103b13a8)
Location: fs/file.c:647
Inline: False
```
**Symbols:**

```
ffff8000103b13a8-ffff8000103b150c: __close_fd_get_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __close_fd_get_file(unsigned int fd, struct file **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (c0590e38)
Location: fs/file.c:647
Inline: False
```
**Symbols:**

```
c0590e38-c0590f60: __close_fd_get_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __close_fd_get_file(unsigned int fd, struct file **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (c0000000004ad440)
Location: fs/file.c:647
Inline: False
```
**Symbols:**

```
c0000000004ad440-c0000000004ad5e8: __close_fd_get_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __close_fd_get_file(unsigned int fd, struct file **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffe000275aaa)
Location: fs/file.c:647
Inline: False
```
**Symbols:**

```
ffffffe000275aaa-ffffffe000275bfe: __close_fd_get_file (STB_GLOBAL)
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
int __close_fd_get_file(unsigned int fd, struct file **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812f8500)
Location: fs/file.c:647
Inline: False
```
**Symbols:**

```
ffffffff812f8500-ffffffff812f85c3: __close_fd_get_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __close_fd_get_file(unsigned int fd, struct file **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812e9120)
Location: fs/file.c:647
Inline: False
```
**Symbols:**

```
ffffffff812e9120-ffffffff812e91e3: __close_fd_get_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __close_fd_get_file(unsigned int fd, struct file **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812f6310)
Location: fs/file.c:647
Inline: False
```
**Symbols:**

```
ffffffff812f6310-ffffffff812f63d3: __close_fd_get_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __close_fd_get_file(unsigned int fd, struct file **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81306dd0)
Location: fs/file.c:647
Inline: False
```
**Symbols:**

```
ffffffff81306dd0-ffffffff81306e93: __close_fd_get_file (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<b>Param removed. </b>
<code>struct file **res</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>struct file *</code>
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
