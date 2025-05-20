# Function: <code>do_statx</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_statx(int dfd, const char *filename, unsigned int flags, unsigned int mask, struct statx *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8131b240)
Location: fs/stat.c:581
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_statx
  - fs/stat.c:__x64_sys_statx
  - fs/io_uring.c:io_issue_sqe
```
**Symbols:**

```
ffffffff8131b240-ffffffff8131b2b9: do_statx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_statx(int dfd, const char *filename, unsigned int flags, unsigned int mask, struct statx *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff813268a0)
Location: fs/stat.c:569
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_statx
  - fs/stat.c:__x64_sys_statx
  - fs/io_uring.c:io_issue_sqe
```
**Symbols:**

```
ffffffff813268a0-ffffffff81326919: do_statx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_statx(int dfd, const char *filename, unsigned int flags, unsigned int mask, struct statx *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8132c9b0)
Location: fs/stat.c:587
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_statx
  - fs/stat.c:__x64_sys_statx
  - fs/io_uring.c:io_issue_sqe
```
**Symbols:**

```
ffffffff8132c9b0-ffffffff8132ca29: do_statx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_statx(int dfd, const char *filename, unsigned int flags, unsigned int mask, struct statx *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8137a120)
Location: fs/stat.c:605
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_statx
  - fs/stat.c:__x64_sys_statx
  - fs/io_uring.c:io_issue_sqe
```
**Symbols:**

```
ffffffff8137a120-ffffffff8137a199: do_statx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_statx(int dfd, struct filename *filename, unsigned int flags, unsigned int mask, struct statx *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff813f97e0)
Location: fs/stat.c:618
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_statx
  - fs/stat.c:__x64_sys_statx
  - io_uring/io_uring.c:io_statx
```
**Symbols:**

```
ffffffff813f97e0-ffffffff813f988e: do_statx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_statx(int dfd, struct filename *filename, unsigned int flags, unsigned int mask, struct statx *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81483010)
Location: fs/stat.c:635
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_statx
  - fs/stat.c:__x64_sys_statx
  - io_uring/statx.c:io_statx
```
**Symbols:**

```
ffffffff81483010-ffffffff814830be: do_statx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_statx(int dfd, struct filename *filename, unsigned int flags, unsigned int mask, struct statx *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff814b7c30)
Location: fs/stat.c:643
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_statx
  - fs/stat.c:__x64_sys_statx
  - io_uring/statx.c:io_statx
```
**Symbols:**

```
ffffffff814b7c30-ffffffff814b7cdf: do_statx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_statx(int dfd, struct filename *filename, unsigned int flags, unsigned int mask, struct statx *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff814ea130)
Location: fs/stat.c:665
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_statx
  - fs/stat.c:__x64_sys_statx
  - io_uring/statx.c:io_statx
```
**Symbols:**

```
ffffffff814ea130-ffffffff814ea1df: do_statx (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<b>Param type changed. </b>
<code>const char *filename</code> ➡️ <code>struct filename *filename</code>
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
