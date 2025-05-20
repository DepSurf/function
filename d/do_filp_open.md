# Function: <code>do_filp_open</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct file *do_filp_open(int dfd, struct filename *pathname, const struct open_flags *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8121ce20)
Location: fs/namei.c:3358
Inline: False
Direct callers:
  - fs/open.c:file_open_name
  - fs/open.c:do_sys_open
  - fs/exec.c:do_open_execat
  - fs/exec.c:SyS_uselib
```
**Symbols:**

```
ffffffff8121ce20-ffffffff8121cf1c: do_filp_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct file *do_filp_open(int dfd, struct filename *pathname, const struct open_flags *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81244400)
Location: fs/namei.c:3524
Inline: False
Direct callers:
  - fs/open.c:do_sys_open
  - fs/open.c:file_open_name
  - fs/exec.c:do_open_execat
  - fs/exec.c:SyS_uselib
```
**Symbols:**

```
ffffffff81244400-ffffffff812444fc: do_filp_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct file *do_filp_open(int dfd, struct filename *pathname, const struct open_flags *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81257370)
Location: fs/namei.c:3481
Inline: False
Direct callers:
  - fs/open.c:do_sys_open
  - fs/open.c:file_open_name
  - fs/exec.c:do_open_execat
  - fs/exec.c:SyS_uselib
```
**Symbols:**

```
ffffffff81257370-ffffffff8125746c: do_filp_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct file *do_filp_open(int dfd, struct filename *pathname, const struct open_flags *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812634e0)
Location: fs/namei.c:3546
Inline: False
Direct callers:
  - fs/open.c:do_sys_open
  - fs/open.c:file_open_name
  - fs/exec.c:do_open_execat
  - fs/exec.c:SyS_uselib
```
**Symbols:**

```
ffffffff812634e0-ffffffff812635e9: do_filp_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct file *do_filp_open(int dfd, struct filename *pathname, const struct open_flags *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81285a20)
Location: fs/namei.c:3544
Inline: False
Direct callers:
  - fs/open.c:do_sys_open
  - fs/open.c:file_open_name
  - fs/exec.c:do_open_execat
  - fs/exec.c:SyS_uselib
```
**Symbols:**

```
ffffffff81285a20-ffffffff81285b29: do_filp_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct file *do_filp_open(int dfd, struct filename *pathname, const struct open_flags *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812ad010)
Location: fs/namei.c:3566
Inline: False
Direct callers:
  - fs/open.c:do_sys_open
  - fs/open.c:file_open_name
  - fs/exec.c:do_open_execat
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
```
**Symbols:**

```
ffffffff812ad010-ffffffff812ad106: do_filp_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct file *do_filp_open(int dfd, struct filename *pathname, const struct open_flags *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812c2110)
Location: fs/namei.c:3556
Inline: False
Direct callers:
  - fs/open.c:do_sys_open
  - fs/open.c:file_open_name
  - fs/exec.c:do_open_execat
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
```
**Symbols:**

```
ffffffff812c2110-ffffffff812c2206: do_filp_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct file *do_filp_open(int dfd, struct filename *pathname, const struct open_flags *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812de8e0)
Location: fs/namei.c:3555
Inline: False
Direct callers:
  - fs/open.c:do_sys_open
  - fs/open.c:file_open_name
  - fs/exec.c:do_open_execat
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
```
**Symbols:**

```
ffffffff812de8e0-ffffffff812de9d6: do_filp_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct file *do_filp_open(int dfd, struct filename *pathname, const struct open_flags *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f03f0)
Location: fs/namei.c:3550
Inline: False
Direct callers:
  - fs/open.c:do_sys_open
  - fs/open.c:file_open_name
  - fs/exec.c:do_open_execat
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
```
**Symbols:**

```
ffffffff812f03f0-ffffffff812f04e6: do_filp_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct file *do_filp_open(int dfd, struct filename *pathname, const struct open_flags *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81328790)
Location: fs/namei.c:3379
Inline: False
Direct callers:
  - fs/open.c:do_sys_openat2
  - fs/open.c:file_open_name
  - fs/exec.c:do_open_execat
  - fs/exec.c:__do_sys_uselib
  - fs/io_uring.c:io_openat2
```
**Symbols:**

```
ffffffff81328790-ffffffff813288bb: do_filp_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct file *do_filp_open(int dfd, struct filename *pathname, const struct open_flags *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81333ce0)
Location: fs/namei.c:3381
Inline: False
Direct callers:
  - fs/open.c:do_sys_openat2
  - fs/open.c:file_open_name
  - fs/exec.c:do_open_execat
  - fs/exec.c:__do_sys_uselib
  - fs/io_uring.c:io_openat2
```
**Symbols:**

```
ffffffff81333ce0-ffffffff81333e0b: do_filp_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct file *do_filp_open(int dfd, struct filename *pathname, const struct open_flags *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81339db0)
Location: fs/namei.c:3513
Inline: False
Direct callers:
  - fs/open.c:do_sys_openat2
  - fs/open.c:file_open_name
  - fs/exec.c:do_open_execat
  - fs/exec.c:__do_sys_uselib
  - fs/io_uring.c:io_openat2
```
**Symbols:**

```
ffffffff81339db0-ffffffff81339ef0: do_filp_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct file *do_filp_open(int dfd, struct filename *pathname, const struct open_flags *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81387060)
Location: fs/namei.c:3580
Inline: False
Direct callers:
  - fs/open.c:do_sys_openat2
  - fs/open.c:file_open_name
  - fs/exec.c:do_open_execat
  - fs/exec.c:__do_sys_uselib
  - fs/io_uring.c:io_openat2
  - fs/io_uring.c:io_openat2
```
**Symbols:**

```
ffffffff81387060-ffffffff813871b0: do_filp_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct file *do_filp_open(int dfd, struct filename *pathname, const struct open_flags *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81407e10)
Location: fs/namei.c:3676
Inline: False
Direct callers:
  - fs/open.c:do_sys_openat2
  - fs/open.c:file_open_name
  - fs/exec.c:do_open_execat
  - fs/exec.c:__do_sys_uselib
  - io_uring/io_uring.c:io_openat2
  - io_uring/io_uring.c:io_openat2
```
**Symbols:**

```
ffffffff81407e10-ffffffff81407f78: do_filp_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct file *do_filp_open(int dfd, struct filename *pathname, const struct open_flags *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814922f0)
Location: fs/namei.c:3733
Inline: False
Direct callers:
  - fs/open.c:do_sys_openat2
  - fs/open.c:file_open_name
  - fs/exec.c:do_open_execat
  - fs/exec.c:__do_sys_uselib
  - io_uring/openclose.c:io_openat2
  - io_uring/openclose.c:io_openat2
```
**Symbols:**

```
ffffffff814922f0-ffffffff81492458: do_filp_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct file *do_filp_open(int dfd, struct filename *pathname, const struct open_flags *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814c7340)
Location: fs/namei.c:3812
Inline: False
Direct callers:
  - fs/open.c:do_sys_openat2
  - fs/open.c:file_open_name
  - fs/exec.c:do_open_execat
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
  - io_uring/openclose.c:io_openat2
  - io_uring/openclose.c:io_openat2
```
**Symbols:**

```
ffffffff814c7340-ffffffff814c74a8: do_filp_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct file *do_filp_open(int dfd, struct filename *pathname, const struct open_flags *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814f9bc0)
Location: fs/namei.c:3821
Inline: False
Direct callers:
  - fs/open.c:do_sys_openat2
  - fs/open.c:file_open_name
  - fs/exec.c:do_open_execat
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
  - io_uring/openclose.c:io_openat2
  - io_uring/openclose.c:io_openat2
```
**Symbols:**

```
ffffffff814f9bc0-ffffffff814f9d28: do_filp_open (STB_GLOBAL)
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
struct file *do_filp_open(int dfd, struct filename *pathname, const struct open_flags *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff800010399b88)
Location: fs/namei.c:3550
Inline: False
Direct callers:
  - fs/open.c:do_sys_open
  - fs/open.c:file_open_name
  - fs/exec.c:do_open_execat
  - fs/exec.c:__arm64_sys_uselib
```
**Symbols:**

```
ffff800010399b88-ffff800010399c8c: do_filp_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct file *do_filp_open(int dfd, struct filename *pathname, const struct open_flags *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c05800c0)
Location: fs/namei.c:3550
Inline: False
Direct callers:
  - fs/open.c:do_sys_open
  - fs/open.c:file_open_name
  - fs/exec.c:do_open_execat
  - fs/exec.c:__se_sys_uselib
```
**Symbols:**

```
c05800c0-c05801bc: do_filp_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct file *do_filp_open(int dfd, struct filename *pathname, const struct open_flags *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c000000000494580)
Location: fs/namei.c:3550
Inline: False
Direct callers:
  - fs/open.c:do_sys_open
  - fs/open.c:file_open_name
  - fs/exec.c:do_open_execat
  - fs/exec.c:__se_sys_uselib
```
**Symbols:**

```
c000000000494580-c0000000004946a4: do_filp_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct file *do_filp_open(int dfd, struct filename *pathname, const struct open_flags *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe0002673ea)
Location: fs/namei.c:3550
Inline: False
Direct callers:
  - fs/open.c:do_sys_open
  - fs/open.c:file_open_name
  - fs/exec.c:do_open_execat
  - fs/exec.c:__se_sys_uselib
```
**Symbols:**

```
ffffffe0002673ea-ffffffe00026749e: do_filp_open (STB_GLOBAL)
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
struct file *do_filp_open(int dfd, struct filename *pathname, const struct open_flags *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e89d0)
Location: fs/namei.c:3550
Inline: False
Direct callers:
  - fs/open.c:do_sys_open
  - fs/open.c:file_open_name
  - fs/exec.c:do_open_execat
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
```
**Symbols:**

```
ffffffff812e89d0-ffffffff812e8ac6: do_filp_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct file *do_filp_open(int dfd, struct filename *pathname, const struct open_flags *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d9610)
Location: fs/namei.c:3550
Inline: False
Direct callers:
  - fs/open.c:do_sys_open
  - fs/open.c:file_open_name
  - fs/exec.c:do_open_execat
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
```
**Symbols:**

```
ffffffff812d9610-ffffffff812d9706: do_filp_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct file *do_filp_open(int dfd, struct filename *pathname, const struct open_flags *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e67e0)
Location: fs/namei.c:3550
Inline: False
Direct callers:
  - fs/open.c:do_sys_open
  - fs/open.c:file_open_name
  - fs/exec.c:do_open_execat
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
```
**Symbols:**

```
ffffffff812e67e0-ffffffff812e68d6: do_filp_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct file *do_filp_open(int dfd, struct filename *pathname, const struct open_flags *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f7760)
Location: fs/namei.c:3550
Inline: False
Direct callers:
  - fs/open.c:do_sys_open
  - fs/open.c:file_open_name
  - fs/exec.c:do_open_execat
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
```
**Symbols:**

```
ffffffff812f7760-ffffffff812f7856: do_filp_open (STB_GLOBAL)
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
