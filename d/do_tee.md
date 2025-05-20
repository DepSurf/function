# Function: <code>do_tee</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81240140)
Location: fs/splice.c:1994
Inline: True
Inline callers:
  - fs/splice.c:SyS_tee
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81268416)
Location: fs/splice.c:1998
Inline: True
Inline callers:
  - fs/splice.c:SyS_tee
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8127b3e6)
Location: fs/splice.c:1708
Inline: True
Inline callers:
  - fs/splice.c:SyS_tee
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81288792)
Location: fs/splice.c:1709
Inline: True
Inline callers:
  - fs/splice.c:SyS_tee
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff812ab2c2)
Location: fs/splice.c:1693
Inline: True
Inline callers:
  - fs/splice.c:SyS_tee
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int do_tee(struct file *in, struct file *out, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff812d0f60)
Location: fs/splice.c:1706
Inline: False
Direct callers:
  - fs/splice.c:__ia32_sys_tee
  - fs/splice.c:__x64_sys_tee
```
**Symbols:**

```
ffffffff812d0f60-ffffffff812d119f: do_tee (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int do_tee(struct file *in, struct file *out, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff812e6190)
Location: fs/splice.c:1714
Inline: False
Direct callers:
  - fs/splice.c:__ia32_sys_tee
  - fs/splice.c:__x64_sys_tee
```
**Symbols:**

```
ffffffff812e6190-ffffffff812e63dd: do_tee (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int do_tee(struct file *in, struct file *out, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81304da0)
Location: fs/splice.c:1728
Inline: False
Direct callers:
  - fs/splice.c:__ia32_sys_tee
  - fs/splice.c:__x64_sys_tee
```
**Symbols:**

```
ffffffff81304da0-ffffffff81305031: do_tee (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int do_tee(struct file *in, struct file *out, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81317e30)
Location: fs/splice.c:1736
Inline: False
Direct callers:
  - fs/splice.c:__ia32_sys_tee
  - fs/splice.c:__x64_sys_tee
```
**Symbols:**

```
ffffffff81317e30-ffffffff813180c1: do_tee (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int do_tee(struct file *in, struct file *out, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81352960)
Location: fs/splice.c:1736
Inline: False
Direct callers:
  - fs/splice.c:__ia32_sys_tee
  - fs/splice.c:__x64_sys_tee
  - fs/io_uring.c:io_issue_sqe
```
**Symbols:**

```
ffffffff81352960-ffffffff81352a69: do_tee (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int do_tee(struct file *in, struct file *out, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8135f240)
Location: fs/splice.c:1660
Inline: False
Direct callers:
  - fs/splice.c:__ia32_sys_tee
  - fs/splice.c:__x64_sys_tee
  - fs/io_uring.c:io_issue_sqe
```
**Symbols:**

```
ffffffff8135f240-ffffffff8135f349: do_tee (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int do_tee(struct file *in, struct file *out, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81365b50)
Location: fs/splice.c:1665
Inline: False
Direct callers:
  - fs/splice.c:__ia32_sys_tee
  - fs/splice.c:__x64_sys_tee
  - fs/io_uring.c:io_issue_sqe
```
**Symbols:**

```
ffffffff81365b50-ffffffff81365e35: do_tee (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int do_tee(struct file *in, struct file *out, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff813b4440)
Location: fs/splice.c:1667
Inline: False
Direct callers:
  - fs/splice.c:__ia32_sys_tee
  - fs/splice.c:__x64_sys_tee
  - fs/io_uring.c:io_issue_sqe
```
**Symbols:**

```
ffffffff813b4440-ffffffff813b4725: do_tee (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int do_tee(struct file *in, struct file *out, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81439820)
Location: fs/splice.c:1663
Inline: False
Direct callers:
  - fs/splice.c:__ia32_sys_tee
  - fs/splice.c:__x64_sys_tee
  - io_uring/io_uring.c:io_tee
```
**Symbols:**

```
ffffffff81439820-ffffffff81439b13: do_tee (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int do_tee(struct file *in, struct file *out, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff814c7b50)
Location: fs/splice.c:1663
Inline: False
Direct callers:
  - fs/splice.c:__ia32_sys_tee
  - fs/splice.c:__x64_sys_tee
  - io_uring/splice.c:io_tee
```
**Symbols:**

```
ffffffff814c7b50-ffffffff814c7e43: do_tee (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int do_tee(struct file *in, struct file *out, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff814fdba0)
Location: fs/splice.c:1904
Inline: False
Direct callers:
  - fs/splice.c:__ia32_sys_tee
  - fs/splice.c:__x64_sys_tee
  - io_uring/splice.c:io_tee
```
**Symbols:**

```
ffffffff814fdba0-ffffffff814fe07c: do_tee (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t do_tee(struct file *in, struct file *out, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff815327a0)
Location: fs/splice.c:1967
Inline: False
Direct callers:
  - fs/splice.c:__ia32_sys_tee
  - fs/splice.c:__x64_sys_tee
  - io_uring/splice.c:io_tee
```
**Symbols:**

```
ffffffff815327a0-ffffffff81532c00: do_tee (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffff8000103cdf30)
Location: fs/splice.c:1736
Inline: True
Inline callers:
  - fs/splice.c:__arm64_sys_tee
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/splice.c (c05ab068)
Location: fs/splice.c:1736
Inline: True
Inline callers:
  - fs/splice.c:__se_sys_tee
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/splice.c (c0000000004d10ec)
Location: fs/splice.c:1736
Inline: True
Inline callers:
  - fs/splice.c:__se_sys_tee
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffe00028c010)
Location: fs/splice.c:1736
Inline: True
Inline callers:
  - fs/splice.c:__se_sys_tee
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
long int do_tee(struct file *in, struct file *out, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81310410)
Location: fs/splice.c:1736
Inline: False
Direct callers:
  - fs/splice.c:__ia32_sys_tee
  - fs/splice.c:__x64_sys_tee
```
**Symbols:**

```
ffffffff81310410-ffffffff813106a1: do_tee (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int do_tee(struct file *in, struct file *out, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81301020)
Location: fs/splice.c:1736
Inline: False
Direct callers:
  - fs/splice.c:__ia32_sys_tee
  - fs/splice.c:__x64_sys_tee
```
**Symbols:**

```
ffffffff81301020-ffffffff813012b1: do_tee (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int do_tee(struct file *in, struct file *out, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8130e200)
Location: fs/splice.c:1736
Inline: False
Direct callers:
  - fs/splice.c:__ia32_sys_tee
  - fs/splice.c:__x64_sys_tee
```
**Symbols:**

```
ffffffff8130e200-ffffffff8130e491: do_tee (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int do_tee(struct file *in, struct file *out, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8131fa00)
Location: fs/splice.c:1736
Inline: False
Direct callers:
  - fs/splice.c:__ia32_sys_tee
  - fs/splice.c:__x64_sys_tee
```
**Symbols:**

```
ffffffff8131fa00-ffffffff8131fc91: do_tee (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>long int</code> ➡️ <code>ssize_t</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
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
