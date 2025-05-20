# Function: <code>do_symlinkat</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int do_symlinkat(const char *oldname, int newdfd, const char *newname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812adce0)
Location: fs/namei.c:4144
Inline: False
Direct callers:
  - init/initramfs.c:do_symlink
  - fs/namei.c:__ia32_sys_symlink
  - fs/namei.c:__x64_sys_symlink
  - fs/namei.c:__ia32_sys_symlinkat
  - fs/namei.c:__x64_sys_symlinkat
```
**Symbols:**

```
ffffffff812adce0-ffffffff812addd1: do_symlinkat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int do_symlinkat(const char *oldname, int newdfd, const char *newname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812c2df0)
Location: fs/namei.c:4133
Inline: False
Direct callers:
  - init/initramfs.c:do_symlink
  - fs/namei.c:__ia32_sys_symlink
  - fs/namei.c:__x64_sys_symlink
  - fs/namei.c:__ia32_sys_symlinkat
  - fs/namei.c:__x64_sys_symlinkat
```
**Symbols:**

```
ffffffff812c2df0-ffffffff812c2ee1: do_symlinkat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int do_symlinkat(const char *oldname, int newdfd, const char *newname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812df540)
Location: fs/namei.c:4134
Inline: False
Direct callers:
  - init/initramfs.c:do_symlink
  - fs/namei.c:__ia32_sys_symlink
  - fs/namei.c:__x64_sys_symlink
  - fs/namei.c:__ia32_sys_symlinkat
  - fs/namei.c:__x64_sys_symlinkat
```
**Symbols:**

```
ffffffff812df540-ffffffff812df62b: do_symlinkat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int do_symlinkat(const char *oldname, int newdfd, const char *newname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f1050)
Location: fs/namei.c:4129
Inline: False
Direct callers:
  - init/initramfs.c:do_symlink
  - fs/namei.c:__ia32_sys_symlink
  - fs/namei.c:__x64_sys_symlink
  - fs/namei.c:__ia32_sys_symlinkat
  - fs/namei.c:__x64_sys_symlinkat
```
**Symbols:**

```
ffffffff812f1050-ffffffff812f113b: do_symlinkat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int do_symlinkat(const char *oldname, int newdfd, const char *newname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81329310)
Location: fs/namei.c:3960
Inline: False
Direct callers:
  - init/initramfs.c:do_symlink
  - fs/namei.c:__ia32_sys_symlink
  - fs/namei.c:__x64_sys_symlink
  - fs/namei.c:__ia32_sys_symlinkat
  - fs/namei.c:__x64_sys_symlinkat
```
**Symbols:**

```
ffffffff81329310-ffffffff81329435: do_symlinkat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int do_symlinkat(const char *oldname, int newdfd, const char *newname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81333140)
Location: fs/namei.c:3960
Inline: False
Direct callers:
  - fs/namei.c:__ia32_sys_symlink
  - fs/namei.c:__x64_sys_symlink
  - fs/namei.c:__ia32_sys_symlinkat
  - fs/namei.c:__x64_sys_symlinkat
```
**Symbols:**

```
ffffffff81333140-ffffffff81333265: do_symlinkat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int do_symlinkat(const char *oldname, int newdfd, const char *newname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813391d0)
Location: fs/namei.c:4179
Inline: False
Direct callers:
  - fs/namei.c:__ia32_sys_symlink
  - fs/namei.c:__x64_sys_symlink
  - fs/namei.c:__ia32_sys_symlinkat
  - fs/namei.c:__x64_sys_symlinkat
```
**Symbols:**

```
ffffffff813391d0-ffffffff813392fd: do_symlinkat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_symlinkat(struct filename *from, int newdfd, struct filename *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81387d00)
Location: fs/namei.c:4257
Inline: False
Direct callers:
  - fs/namei.c:__ia32_sys_symlink
  - fs/namei.c:__x64_sys_symlink
  - fs/namei.c:__ia32_sys_symlinkat
  - fs/namei.c:__x64_sys_symlinkat
  - fs/io_uring.c:io_issue_sqe
```
**Symbols:**

```
ffffffff81387d00-ffffffff81387e22: do_symlinkat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_symlinkat(struct filename *from, int newdfd, struct filename *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81408bf0)
Location: fs/namei.c:4352
Inline: False
Direct callers:
  - fs/namei.c:__ia32_sys_symlink
  - fs/namei.c:__x64_sys_symlink
  - fs/namei.c:__ia32_sys_symlinkat
  - fs/namei.c:__x64_sys_symlinkat
  - io_uring/io_uring.c:io_symlinkat
```
**Symbols:**

```
ffffffff81408bf0-ffffffff81408d35: do_symlinkat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_symlinkat(struct filename *from, int newdfd, struct filename *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814931f0)
Location: fs/namei.c:4408
Inline: False
Direct callers:
  - fs/namei.c:__ia32_sys_symlink
  - fs/namei.c:__x64_sys_symlink
  - fs/namei.c:__ia32_sys_symlinkat
  - fs/namei.c:__x64_sys_symlinkat
  - io_uring/fs.c:io_symlinkat
```
**Symbols:**

```
ffffffff814931f0-ffffffff81493339: do_symlinkat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_symlinkat(struct filename *from, int newdfd, struct filename *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814c8240)
Location: fs/namei.c:4484
Inline: False
Direct callers:
  - fs/namei.c:__ia32_sys_symlink
  - fs/namei.c:__x64_sys_symlink
  - fs/namei.c:__ia32_sys_symlinkat
  - fs/namei.c:__x64_sys_symlinkat
  - io_uring/fs.c:io_symlinkat
```
**Symbols:**

```
ffffffff814c8240-ffffffff814c8385: do_symlinkat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_symlinkat(struct filename *from, int newdfd, struct filename *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814faae0)
Location: fs/namei.c:4491
Inline: False
Direct callers:
  - fs/namei.c:__ia32_sys_symlink
  - fs/namei.c:__x64_sys_symlink
  - fs/namei.c:__ia32_sys_symlinkat
  - fs/namei.c:__x64_sys_symlinkat
  - io_uring/fs.c:io_symlinkat
```
**Symbols:**

```
ffffffff814faae0-ffffffff814fac25: do_symlinkat (STB_GLOBAL)
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
long int do_symlinkat(const char *oldname, int newdfd, const char *newname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff80001039a778)
Location: fs/namei.c:4129
Inline: False
Direct callers:
  - init/initramfs.c:do_symlink
  - fs/namei.c:__arm64_sys_symlink
  - fs/namei.c:__arm64_sys_symlinkat
```
**Symbols:**

```
ffff80001039a778-ffff80001039a89c: do_symlinkat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int do_symlinkat(const char *oldname, int newdfd, const char *newname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c0580c24)
Location: fs/namei.c:4129
Inline: False
Direct callers:
  - init/initramfs.c:do_symlink
  - fs/namei.c:__se_sys_symlink
  - fs/namei.c:__se_sys_symlinkat
```
**Symbols:**

```
c0580c24-c0580d40: do_symlinkat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int do_symlinkat(const char *oldname, int newdfd, const char *newname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c0000000004954e0)
Location: fs/namei.c:4129
Inline: False
Direct callers:
  - init/initramfs.c:do_symlink
  - fs/namei.c:__se_sys_symlink
  - fs/namei.c:__se_sys_symlinkat
```
**Symbols:**

```
c0000000004954e0-c0000000004956a4: do_symlinkat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int do_symlinkat(const char *oldname, int newdfd, const char *newname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe000267e42)
Location: fs/namei.c:4129
Inline: False
Direct callers:
  - init/initramfs.c:do_symlink
  - fs/namei.c:__se_sys_symlink
  - fs/namei.c:__se_sys_symlinkat
```
**Symbols:**

```
ffffffe000267e42-ffffffe000267f36: do_symlinkat (STB_GLOBAL)
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
long int do_symlinkat(const char *oldname, int newdfd, const char *newname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e9630)
Location: fs/namei.c:4129
Inline: False
Direct callers:
  - init/initramfs.c:do_symlink
  - fs/namei.c:__ia32_sys_symlink
  - fs/namei.c:__x64_sys_symlink
  - fs/namei.c:__ia32_sys_symlinkat
  - fs/namei.c:__x64_sys_symlinkat
```
**Symbols:**

```
ffffffff812e9630-ffffffff812e971b: do_symlinkat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int do_symlinkat(const char *oldname, int newdfd, const char *newname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812da270)
Location: fs/namei.c:4129
Inline: False
Direct callers:
  - init/initramfs.c:do_symlink
  - fs/namei.c:__ia32_sys_symlink
  - fs/namei.c:__x64_sys_symlink
  - fs/namei.c:__ia32_sys_symlinkat
  - fs/namei.c:__x64_sys_symlinkat
```
**Symbols:**

```
ffffffff812da270-ffffffff812da35b: do_symlinkat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int do_symlinkat(const char *oldname, int newdfd, const char *newname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e7440)
Location: fs/namei.c:4129
Inline: False
Direct callers:
  - init/initramfs.c:do_symlink
  - fs/namei.c:__ia32_sys_symlink
  - fs/namei.c:__x64_sys_symlink
  - fs/namei.c:__ia32_sys_symlinkat
  - fs/namei.c:__x64_sys_symlinkat
```
**Symbols:**

```
ffffffff812e7440-ffffffff812e752b: do_symlinkat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int do_symlinkat(const char *oldname, int newdfd, const char *newname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f83c0)
Location: fs/namei.c:4129
Inline: False
Direct callers:
  - init/initramfs.c:do_symlink
  - fs/namei.c:__ia32_sys_symlink
  - fs/namei.c:__x64_sys_symlink
  - fs/namei.c:__ia32_sys_symlinkat
  - fs/namei.c:__x64_sys_symlinkat
```
**Symbols:**

```
ffffffff812f83c0-ffffffff812f84ab: do_symlinkat (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct filename *from</code>
</li>
<li>
<b>Param added. </b>
<code>struct filename *to</code>
</li>
<li>
<b>Param removed. </b>
<code>const char *oldname</code>
</li>
<li>
<b>Param removed. </b>
<code>const char *newname</code>
</li>
<li>
<b>Return type changed. </b>
<code>long int</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
