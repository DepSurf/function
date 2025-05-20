# Function: <code>do_splice</code>

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
In fs/splice.c (ffffffff8123f9fd)
Location: fs/splice.c:1350
Inline: True
Inline callers:
  - fs/splice.c:SyS_splice
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
In fs/splice.c (ffffffff81267d40)
Location: fs/splice.c:1354
Inline: True
Inline callers:
  - fs/splice.c:SyS_splice
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
In fs/splice.c (ffffffff8127acb0)
Location: fs/splice.c:1117
Inline: True
Inline callers:
  - fs/splice.c:SyS_splice
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
In fs/splice.c (ffffffff812880f5)
Location: fs/splice.c:1113
Inline: True
Inline callers:
  - fs/splice.c:SyS_splice
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
In fs/splice.c (ffffffff812aac25)
Location: fs/splice.c:1097
Inline: True
Inline callers:
  - fs/splice.c:SyS_splice
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int do_splice(struct file *in, loff_t *off_in, struct file *out, loff_t *off_out, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff812d0890)
Location: fs/splice.c:1098
Inline: False
Direct callers:
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__x64_sys_splice
```
**Symbols:**

```
ffffffff812d0890-ffffffff812d0e15: do_splice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int do_splice(struct file *in, loff_t *off_in, struct file *out, loff_t *off_out, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff812e5ab0)
Location: fs/splice.c:1102
Inline: False
Direct callers:
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__x64_sys_splice
```
**Symbols:**

```
ffffffff812e5ab0-ffffffff812e6050: do_splice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int do_splice(struct file *in, loff_t *off_in, struct file *out, loff_t *off_out, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81304610)
Location: fs/splice.c:1099
Inline: False
Direct callers:
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__x64_sys_splice
```
**Symbols:**

```
ffffffff81304610-ffffffff81304c49: do_splice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int do_splice(struct file *in, loff_t *off_in, struct file *out, loff_t *off_out, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81317690)
Location: fs/splice.c:1100
Inline: False
Direct callers:
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__x64_sys_splice
```
**Symbols:**

```
ffffffff81317690-ffffffff81317cd9: do_splice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int do_splice(struct file *in, loff_t *off_in, struct file *out, loff_t *off_out, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81352370)
Location: fs/splice.c:1093
Inline: False
Direct callers:
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__x64_sys_splice
  - fs/io_uring.c:io_issue_sqe
```
**Symbols:**

```
ffffffff81352370-ffffffff81352736: do_splice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int do_splice(struct file *in, loff_t *off_in, struct file *out, loff_t *off_out, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8135ead0)
Location: fs/splice.c:1010
Inline: False
Direct callers:
  - fs/splice.c:__do_splice
  - fs/io_uring.c:io_issue_sqe
```
**Symbols:**

```
ffffffff8135ead0-ffffffff8135eeb4: do_splice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int do_splice(struct file *in, loff_t *off_in, struct file *out, loff_t *off_out, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81365480)
Location: fs/splice.c:1028
Inline: False
Direct callers:
  - fs/splice.c:__do_splice
  - fs/io_uring.c:io_issue_sqe
```
**Symbols:**

```
ffffffff81365480-ffffffff813657bb: do_splice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int do_splice(struct file *in, loff_t *off_in, struct file *out, loff_t *off_out, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff813b3d70)
Location: fs/splice.c:1030
Inline: False
Direct callers:
  - fs/splice.c:__do_splice
  - fs/io_uring.c:io_issue_sqe
```
**Symbols:**

```
ffffffff813b3d70-ffffffff813b40ab: do_splice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int do_splice(struct file *in, loff_t *off_in, struct file *out, loff_t *off_out, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81439080)
Location: fs/splice.c:1026
Inline: False
Direct callers:
  - fs/splice.c:__do_splice
  - io_uring/io_uring.c:io_splice
```
**Symbols:**

```
ffffffff81439080-ffffffff81439400: do_splice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int do_splice(struct file *in, loff_t *off_in, struct file *out, loff_t *off_out, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff814c7370)
Location: fs/splice.c:1025
Inline: False
Direct callers:
  - fs/splice.c:__do_splice
  - io_uring/splice.c:io_splice
```
**Symbols:**

```
ffffffff814c7370-ffffffff814c76f0: do_splice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int do_splice(struct file *in, loff_t *off_in, struct file *out, loff_t *off_out, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff814fd150)
Location: fs/splice.c:1246
Inline: False
Direct callers:
  - fs/splice.c:__do_splice
  - fs/splice.c:__do_splice
  - fs/splice.c:__do_splice
  - io_uring/splice.c:io_splice
```
**Symbols:**

```
ffffffff814fd150-ffffffff814fd683: do_splice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t do_splice(struct file *in, loff_t *off_in, struct file *out, loff_t *off_out, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81531d80)
Location: fs/splice.c:1305
Inline: False
Direct callers:
  - fs/splice.c:__do_splice
  - fs/splice.c:__do_splice
  - fs/splice.c:__do_splice
  - io_uring/splice.c:io_splice
```
**Symbols:**

```
ffffffff81531d80-ffffffff81532283: do_splice (STB_GLOBAL)
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
long int do_splice(struct file *in, loff_t *off_in, struct file *out, loff_t *off_out, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffff8000103ced80)
Location: fs/splice.c:1100
Inline: False
Direct callers:
  - fs/splice.c:__arm64_sys_splice
```
**Symbols:**

```
ffff8000103ced80-ffff8000103cf30c: do_splice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int do_splice(struct file *in, loff_t *off_in, struct file *out, loff_t *off_out, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (c05a9fb8)
Location: fs/splice.c:1100
Inline: False
Direct callers:
  - fs/splice.c:__se_sys_splice
```
**Symbols:**

```
c05a9fb8-c05aa664: do_splice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int do_splice(struct file *in, loff_t *off_in, struct file *out, loff_t *off_out, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (c0000000004d0660)
Location: fs/splice.c:1100
Inline: False
Direct callers:
  - fs/splice.c:__se_sys_splice
```
**Symbols:**

```
c0000000004d0660-c0000000004d0ddc: do_splice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int do_splice(struct file *in, loff_t *off_in, struct file *out, loff_t *off_out, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffe00028af54)
Location: fs/splice.c:1100
Inline: False
Direct callers:
  - fs/splice.c:__se_sys_splice
```
**Symbols:**

```
ffffffe00028af54-ffffffe00028b3ce: do_splice (STB_LOCAL)
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
long int do_splice(struct file *in, loff_t *off_in, struct file *out, loff_t *off_out, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8130fc70)
Location: fs/splice.c:1100
Inline: False
Direct callers:
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__x64_sys_splice
```
**Symbols:**

```
ffffffff8130fc70-ffffffff813102b9: do_splice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int do_splice(struct file *in, loff_t *off_in, struct file *out, loff_t *off_out, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81300880)
Location: fs/splice.c:1100
Inline: False
Direct callers:
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__x64_sys_splice
```
**Symbols:**

```
ffffffff81300880-ffffffff81300ec9: do_splice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int do_splice(struct file *in, loff_t *off_in, struct file *out, loff_t *off_out, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8130da60)
Location: fs/splice.c:1100
Inline: False
Direct callers:
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__x64_sys_splice
```
**Symbols:**

```
ffffffff8130da60-ffffffff8130e0a9: do_splice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int do_splice(struct file *in, loff_t *off_in, struct file *out, loff_t *off_out, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8131f260)
Location: fs/splice.c:1100
Inline: False
Direct callers:
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__x64_sys_splice
```
**Symbols:**

```
ffffffff8131f260-ffffffff8131f8a9: do_splice (STB_LOCAL)
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
