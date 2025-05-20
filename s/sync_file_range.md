# Function: <code>sync_file_range</code>

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
int sync_file_range(struct file *file, loff_t offset, loff_t nbytes, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff81306500)
Location: fs/sync.c:238
Inline: False
Direct callers:
  - fs/sync.c:ksys_sync_file_range
  - fs/io_uring.c:__io_submit_sqe
```
**Symbols:**

```
ffffffff81306500-ffffffff813065ef: sync_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sync_file_range(struct file *file, loff_t offset, loff_t nbytes, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff81319580)
Location: fs/sync.c:238
Inline: False
Direct callers:
  - fs/sync.c:ksys_sync_file_range
  - fs/io_uring.c:__io_submit_sqe
```
**Symbols:**

```
ffffffff81319580-ffffffff8131966f: sync_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sync_file_range(struct file *file, loff_t offset, loff_t nbytes, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff813533d0)
Location: fs/sync.c:241
Inline: False
Direct callers:
  - fs/sync.c:__ia32_sys_sync_file_range2
  - fs/sync.c:__x64_sys_sync_file_range2
  - fs/sync.c:__ia32_sys_sync_file_range
  - fs/sync.c:__x64_sys_sync_file_range
  - fs/io_uring.c:io_issue_sqe
```
**Symbols:**

```
ffffffff813533d0-ffffffff813534bf: sync_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sync_file_range(struct file *file, loff_t offset, loff_t nbytes, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff8135fcb0)
Location: fs/sync.c:241
Inline: False
Direct callers:
  - fs/sync.c:__ia32_sys_sync_file_range2
  - fs/sync.c:__x64_sys_sync_file_range2
  - fs/sync.c:__ia32_sys_sync_file_range
  - fs/sync.c:__x64_sys_sync_file_range
  - fs/io_uring.c:io_issue_sqe
```
**Symbols:**

```
ffffffff8135fcb0-ffffffff8135fd9f: sync_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sync_file_range(struct file *file, loff_t offset, loff_t nbytes, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff81366740)
Location: fs/sync.c:240
Inline: False
Direct callers:
  - fs/sync.c:__ia32_sys_sync_file_range2
  - fs/sync.c:__x64_sys_sync_file_range2
  - fs/sync.c:__ia32_sys_sync_file_range
  - fs/sync.c:__x64_sys_sync_file_range
  - fs/io_uring.c:io_issue_sqe
```
**Symbols:**

```
ffffffff81366740-ffffffff8136682c: sync_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sync_file_range(struct file *file, loff_t offset, loff_t nbytes, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff813b5290)
Location: fs/sync.c:241
Inline: False
Direct callers:
  - fs/sync.c:__ia32_sys_sync_file_range2
  - fs/sync.c:__x64_sys_sync_file_range2
  - fs/sync.c:__ia32_sys_sync_file_range
  - fs/sync.c:__x64_sys_sync_file_range
  - fs/io_uring.c:io_issue_sqe
```
**Symbols:**

```
ffffffff813b5290-ffffffff813b537c: sync_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sync_file_range(struct file *file, loff_t offset, loff_t nbytes, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff8143a4a0)
Location: fs/sync.c:228
Inline: False
Direct callers:
  - fs/sync.c:__ia32_sys_sync_file_range2
  - fs/sync.c:__x64_sys_sync_file_range2
  - fs/sync.c:__ia32_sys_sync_file_range
  - fs/sync.c:__x64_sys_sync_file_range
  - io_uring/io_uring.c:io_sync_file_range
```
**Symbols:**

```
ffffffff8143a4a0-ffffffff8143a5ba: sync_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sync_file_range(struct file *file, loff_t offset, loff_t nbytes, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff814c88f0)
Location: fs/sync.c:228
Inline: False
Direct callers:
  - fs/sync.c:__ia32_sys_sync_file_range2
  - fs/sync.c:__x64_sys_sync_file_range2
  - fs/sync.c:__ia32_sys_sync_file_range
  - fs/sync.c:__x64_sys_sync_file_range
  - io_uring/sync.c:io_sync_file_range
```
**Symbols:**

```
ffffffff814c88f0-ffffffff814c8a0a: sync_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sync_file_range(struct file *file, loff_t offset, loff_t nbytes, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff814feb30)
Location: fs/sync.c:228
Inline: False
Direct callers:
  - fs/sync.c:__ia32_sys_sync_file_range2
  - fs/sync.c:__x64_sys_sync_file_range2
  - fs/sync.c:__ia32_sys_sync_file_range
  - fs/sync.c:__x64_sys_sync_file_range
  - io_uring/sync.c:io_sync_file_range
```
**Symbols:**

```
ffffffff814feb30-ffffffff814fec4d: sync_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sync_file_range(struct file *file, loff_t offset, loff_t nbytes, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff81533760)
Location: fs/sync.c:228
Inline: False
Direct callers:
  - fs/sync.c:__ia32_sys_sync_file_range2
  - fs/sync.c:__x64_sys_sync_file_range2
  - fs/sync.c:__ia32_sys_sync_file_range
  - fs/sync.c:__x64_sys_sync_file_range
  - io_uring/sync.c:io_sync_file_range
```
**Symbols:**

```
ffffffff81533760-ffffffff8153387d: sync_file_range (STB_GLOBAL)
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
int sync_file_range(struct file *file, loff_t offset, loff_t nbytes, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffff8000103d0550)
Location: fs/sync.c:238
Inline: False
Direct callers:
  - fs/sync.c:ksys_sync_file_range
  - fs/io_uring.c:__io_submit_sqe
```
**Symbols:**

```
ffff8000103d0550-ffff8000103d065c: sync_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sync_file_range(struct file *file, loff_t offset, loff_t nbytes, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (c05ab8a4)
Location: fs/sync.c:238
Inline: False
Direct callers:
  - fs/sync.c:ksys_sync_file_range
  - fs/io_uring.c:__io_submit_sqe
```
**Symbols:**

```
c05ab8a4-c05aba10: sync_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sync_file_range(struct file *file, loff_t offset, loff_t nbytes, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (c0000000004d2d10)
Location: fs/sync.c:238
Inline: False
Direct callers:
  - fs/sync.c:ksys_sync_file_range
  - fs/io_uring.c:__io_submit_sqe
```
**Symbols:**

```
c0000000004d2d10-c0000000004d2eb8: sync_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sync_file_range(struct file *file, loff_t offset, loff_t nbytes, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffe00028c7ea)
Location: fs/sync.c:238
Inline: False
Direct callers:
  - fs/sync.c:ksys_sync_file_range
  - fs/io_uring.c:__io_submit_sqe
```
**Symbols:**

```
ffffffe00028c7ea-ffffffe00028c8be: sync_file_range (STB_GLOBAL)
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
int sync_file_range(struct file *file, loff_t offset, loff_t nbytes, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff81311b60)
Location: fs/sync.c:238
Inline: False
Direct callers:
  - fs/sync.c:ksys_sync_file_range
  - fs/io_uring.c:__io_submit_sqe
```
**Symbols:**

```
ffffffff81311b60-ffffffff81311c4f: sync_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sync_file_range(struct file *file, loff_t offset, loff_t nbytes, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff81302770)
Location: fs/sync.c:238
Inline: False
Direct callers:
  - fs/sync.c:ksys_sync_file_range
  - fs/io_uring.c:__io_submit_sqe
```
**Symbols:**

```
ffffffff81302770-ffffffff8130285f: sync_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sync_file_range(struct file *file, loff_t offset, loff_t nbytes, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff8130f950)
Location: fs/sync.c:238
Inline: False
Direct callers:
  - fs/sync.c:ksys_sync_file_range
  - fs/io_uring.c:__io_submit_sqe
```
**Symbols:**

```
ffffffff8130f950-ffffffff8130fa3f: sync_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sync_file_range(struct file *file, loff_t offset, loff_t nbytes, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff81321150)
Location: fs/sync.c:238
Inline: False
Direct callers:
  - fs/sync.c:ksys_sync_file_range
  - fs/io_uring.c:__io_submit_sqe
```
**Symbols:**

```
ffffffff81321150-ffffffff8132123f: sync_file_range (STB_GLOBAL)
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
