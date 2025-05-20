# Function: <code>__kernel_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t __kernel_write(struct file *file, const char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8120c290)
Location: fs/read_write.c:521
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/splice.c:write_pipe_buf
  - fs/coredump.c:dump_emit
```
**Symbols:**

```
ffffffff8120c290-ffffffff8120c378: __kernel_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t __kernel_write(struct file *file, const char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812325e0)
Location: fs/read_write.c:542
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/splice.c:write_pipe_buf
  - fs/coredump.c:dump_emit
```
**Symbols:**

```
ffffffff812325e0-ffffffff812326cc: __kernel_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t __kernel_write(struct file *file, const char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81244f50)
Location: fs/read_write.c:542
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/splice.c:write_pipe_buf
  - fs/coredump.c:dump_emit
```
**Symbols:**

```
ffffffff81244f50-ffffffff81245038: __kernel_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t __kernel_write(struct file *file, const char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812504c0)
Location: fs/read_write.c:500
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/splice.c:write_pipe_buf
  - fs/coredump.c:dump_emit
```
**Symbols:**

```
ffffffff812504c0-ffffffff812505a8: __kernel_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t __kernel_write(struct file *file, const void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81273df0)
Location: fs/read_write.c:512
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/splice.c:write_pipe_buf
  - fs/coredump.c:dump_emit
```
**Symbols:**

```
ffffffff81273df0-ffffffff81273ede: __kernel_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t __kernel_write(struct file *file, const void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8129ab40)
Location: fs/read_write.c:517
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/splice.c:write_pipe_buf
  - fs/coredump.c:dump_emit
```
**Symbols:**

```
ffffffff8129ab40-ffffffff8129ac36: __kernel_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t __kernel_write(struct file *file, const void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812afa40)
Location: fs/read_write.c:517
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/splice.c:write_pipe_buf
  - fs/coredump.c:dump_emit
```
**Symbols:**

```
ffffffff812afa40-ffffffff812afb3d: __kernel_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t __kernel_write(struct file *file, const void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c95a0)
Location: fs/read_write.c:526
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/splice.c:write_pipe_buf
  - fs/coredump.c:dump_emit
```
**Symbols:**

```
ffffffff812c95a0-ffffffff812c96a1: __kernel_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t __kernel_write(struct file *file, const void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812dafb0)
Location: fs/read_write.c:526
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/splice.c:write_pipe_buf
  - fs/coredump.c:dump_emit
```
**Symbols:**

```
ffffffff812dafb0-ffffffff812db0b1: __kernel_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t __kernel_write(struct file *file, const void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81311bd0)
Location: fs/read_write.c:536
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/splice.c:write_pipe_buf
  - fs/coredump.c:dump_emit
```
**Symbols:**

```
ffffffff81311bd0-ffffffff81311d33: __kernel_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
ssize_t __kernel_write(struct file *file, const void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/read_write.c (0)
Location: fs/read_write.c:527
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/coredump.c:dump_skip
```
**Symbols:**

```
ffffffff81bea4c4-ffffffff81bea4df: __kernel_write.cold (STB_LOCAL)
ffffffff8131d3f0-ffffffff8131d6b6: __kernel_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
ssize_t __kernel_write(struct file *file, const void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/read_write.c (0)
Location: fs/read_write.c:526
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/coredump.c:dump_emit
```
**Symbols:**

```
ffffffff81bdc4fe-ffffffff81bdc519: __kernel_write.cold (STB_LOCAL)
ffffffff81323560-ffffffff81323821: __kernel_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t __kernel_write(struct file *file, const void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/read_write.c (0)
Location: fs/read_write.c:516
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/coredump.c:dump_emit
```
**Symbols:**

```
ffffffff81cc37f6-ffffffff81cc3811: __kernel_write.cold (STB_LOCAL)
ffffffff81370a50-ffffffff81370d23: __kernel_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t __kernel_write(struct file *file, const void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/read_write.c (0)
Location: fs/read_write.c:512
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/coredump.c:dump_emit
```
**Symbols:**

```
ffffffff81e75f58-ffffffff81e75f6c: __kernel_write.cold (STB_LOCAL)
ffffffff813efde0-ffffffff813f00d1: __kernel_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
ssize_t __kernel_write(struct file *file, const void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8147a980)
Location: fs/read_write.c:529
Inline: True
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/coredump.c:dump_emit
  - fs/coredump.c:__dump_skip
```
**Symbols:**

```
ffffffff8147a980-ffffffff8147aa36: __kernel_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
ssize_t __kernel_write(struct file *file, const void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814af4e0)
Location: fs/read_write.c:529
Inline: True
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/coredump.c:dump_emit
  - fs/coredump.c:__dump_skip
```
**Symbols:**

```
ffffffff814af4e0-ffffffff814af596: __kernel_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t __kernel_write(struct file *file, const void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814e0c60)
Location: fs/read_write.c:535
Inline: True
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/coredump.c:dump_emit
  - fs/coredump.c:__dump_skip
```
**Symbols:**

```
ffffffff814e0c60-ffffffff814e0d16: __kernel_write (STB_GLOBAL)
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
ssize_t __kernel_write(struct file *file, const void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffff800010380f90)
Location: fs/read_write.c:526
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/splice.c:write_pipe_buf
  - fs/coredump.c:dump_emit
```
**Symbols:**

```
ffff800010380f90-ffff800010381108: __kernel_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t __kernel_write(struct file *file, const void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c056a918)
Location: fs/read_write.c:526
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/splice.c:write_pipe_buf
  - fs/coredump.c:dump_emit
```
**Symbols:**

```
c056a918-c056aa58: __kernel_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t __kernel_write(struct file *file, const void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c0000000004766b0)
Location: fs/read_write.c:526
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/splice.c:write_pipe_buf
  - fs/coredump.c:dump_emit
```
**Symbols:**

```
c0000000004766b0-c000000000476868: __kernel_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t __kernel_write(struct file *file, const void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffe00025612e)
Location: fs/read_write.c:526
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/splice.c:write_pipe_buf
  - fs/coredump.c:dump_emit
```
**Symbols:**

```
ffffffe00025612e-ffffffe00025622c: __kernel_write (STB_GLOBAL)
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
ssize_t __kernel_write(struct file *file, const void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d3590)
Location: fs/read_write.c:526
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/splice.c:write_pipe_buf
  - fs/coredump.c:dump_emit
```
**Symbols:**

```
ffffffff812d3590-ffffffff812d3691: __kernel_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t __kernel_write(struct file *file, const void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c4210)
Location: fs/read_write.c:526
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/splice.c:write_pipe_buf
  - fs/coredump.c:dump_emit
```
**Symbols:**

```
ffffffff812c4210-ffffffff812c4311: __kernel_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t __kernel_write(struct file *file, const void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d13a0)
Location: fs/read_write.c:526
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/splice.c:write_pipe_buf
  - fs/coredump.c:dump_emit
```
**Symbols:**

```
ffffffff812d13a0-ffffffff812d14a1: __kernel_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t __kernel_write(struct file *file, const void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812e21d0)
Location: fs/read_write.c:526
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/splice.c:write_pipe_buf
  - fs/coredump.c:dump_emit
```
**Symbols:**

```
ffffffff812e21d0-ffffffff812e22d1: __kernel_write (STB_GLOBAL)
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
<b>Param type changed. </b>
<code>const char *buf</code> ➡️ <code>const void *buf</code>
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
