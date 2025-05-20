# Function: <code>do_mkdirat</code>

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
long int do_mkdirat(int dfd, const char *pathname, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812ad520)
Location: fs/namei.c:3834
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - fs/namei.c:__ia32_sys_mkdir
  - fs/namei.c:__x64_sys_mkdir
  - fs/namei.c:__ia32_sys_mkdirat
  - fs/namei.c:__x64_sys_mkdirat
```
**Symbols:**

```
ffffffff812ad520-ffffffff812ad62c: do_mkdirat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int do_mkdirat(int dfd, const char *pathname, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812c2620)
Location: fs/namei.c:3823
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - fs/namei.c:__ia32_sys_mkdir
  - fs/namei.c:__x64_sys_mkdir
  - fs/namei.c:__ia32_sys_mkdirat
  - fs/namei.c:__x64_sys_mkdirat
```
**Symbols:**

```
ffffffff812c2620-ffffffff812c272c: do_mkdirat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int do_mkdirat(int dfd, const char *pathname, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812dedc0)
Location: fs/namei.c:3822
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - fs/namei.c:__ia32_sys_mkdir
  - fs/namei.c:__x64_sys_mkdir
  - fs/namei.c:__ia32_sys_mkdirat
  - fs/namei.c:__x64_sys_mkdirat
```
**Symbols:**

```
ffffffff812dedc0-ffffffff812deecd: do_mkdirat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int do_mkdirat(int dfd, const char *pathname, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f08d0)
Location: fs/namei.c:3817
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - fs/namei.c:__ia32_sys_mkdir
  - fs/namei.c:__x64_sys_mkdir
  - fs/namei.c:__ia32_sys_mkdirat
  - fs/namei.c:__x64_sys_mkdirat
```
**Symbols:**

```
ffffffff812f08d0-ffffffff812f09dd: do_mkdirat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int do_mkdirat(int dfd, const char *pathname, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81328ac0)
Location: fs/namei.c:3648
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - fs/namei.c:__ia32_sys_mkdir
  - fs/namei.c:__x64_sys_mkdir
  - fs/namei.c:__ia32_sys_mkdirat
  - fs/namei.c:__x64_sys_mkdirat
```
**Symbols:**

```
ffffffff81328ac0-ffffffff81328bff: do_mkdirat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int do_mkdirat(int dfd, const char *pathname, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81332b90)
Location: fs/namei.c:3650
Inline: False
Direct callers:
  - fs/namei.c:__ia32_sys_mkdir
  - fs/namei.c:__x64_sys_mkdir
  - fs/namei.c:__ia32_sys_mkdirat
  - fs/namei.c:__x64_sys_mkdirat
```
**Symbols:**

```
ffffffff81332b90-ffffffff81332ccf: do_mkdirat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int do_mkdirat(int dfd, const char *pathname, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81338bf0)
Location: fs/namei.c:3820
Inline: False
Direct callers:
  - fs/namei.c:__ia32_sys_mkdir
  - fs/namei.c:__x64_sys_mkdir
  - fs/namei.c:__ia32_sys_mkdirat
  - fs/namei.c:__x64_sys_mkdirat
```
**Symbols:**

```
ffffffff81338bf0-ffffffff81338d39: do_mkdirat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_mkdirat(int dfd, struct filename *name, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81387390)
Location: fs/namei.c:3892
Inline: False
Direct callers:
  - fs/namei.c:__ia32_sys_mkdir
  - fs/namei.c:__x64_sys_mkdir
  - fs/namei.c:__ia32_sys_mkdirat
  - fs/namei.c:__x64_sys_mkdirat
  - fs/io_uring.c:io_issue_sqe
```
**Symbols:**

```
ffffffff81387390-ffffffff813874d0: do_mkdirat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_mkdirat(int dfd, struct filename *name, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81408190)
Location: fs/namei.c:3986
Inline: False
Direct callers:
  - fs/namei.c:__ia32_sys_mkdir
  - fs/namei.c:__x64_sys_mkdir
  - fs/namei.c:__ia32_sys_mkdirat
  - fs/namei.c:__x64_sys_mkdirat
  - io_uring/io_uring.c:io_mkdirat
```
**Symbols:**

```
ffffffff81408190-ffffffff814082ec: do_mkdirat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_mkdirat(int dfd, struct filename *name, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81492690)
Location: fs/namei.c:4043
Inline: False
Direct callers:
  - fs/namei.c:__ia32_sys_mkdir
  - fs/namei.c:__x64_sys_mkdir
  - fs/namei.c:__ia32_sys_mkdirat
  - fs/namei.c:__x64_sys_mkdirat
  - io_uring/fs.c:io_mkdirat
```
**Symbols:**

```
ffffffff81492690-ffffffff814927fd: do_mkdirat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_mkdirat(int dfd, struct filename *name, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814c76e0)
Location: fs/namei.c:4124
Inline: False
Direct callers:
  - fs/namei.c:__ia32_sys_mkdir
  - fs/namei.c:__x64_sys_mkdir
  - fs/namei.c:__ia32_sys_mkdirat
  - fs/namei.c:__x64_sys_mkdirat
  - io_uring/fs.c:io_mkdirat
```
**Symbols:**

```
ffffffff814c76e0-ffffffff814c7849: do_mkdirat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_mkdirat(int dfd, struct filename *name, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814f9f60)
Location: fs/namei.c:4133
Inline: False
Direct callers:
  - fs/namei.c:__ia32_sys_mkdir
  - fs/namei.c:__x64_sys_mkdir
  - fs/namei.c:__ia32_sys_mkdirat
  - fs/namei.c:__x64_sys_mkdirat
  - io_uring/fs.c:io_mkdirat
```
**Symbols:**

```
ffffffff814f9f60-ffffffff814fa0d4: do_mkdirat (STB_GLOBAL)
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
long int do_mkdirat(int dfd, const char *pathname, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff80001039a088)
Location: fs/namei.c:3817
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - fs/namei.c:__arm64_sys_mkdir
  - fs/namei.c:__arm64_sys_mkdirat
```
**Symbols:**

```
ffff80001039a088-ffff80001039a1b4: do_mkdirat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int do_mkdirat(int dfd, const char *pathname, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c058058c)
Location: fs/namei.c:3817
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - fs/namei.c:__se_sys_mkdir
  - fs/namei.c:__se_sys_mkdirat
```
**Symbols:**

```
c058058c-c05806ac: do_mkdirat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int do_mkdirat(int dfd, const char *pathname, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c000000000494ba0)
Location: fs/namei.c:3817
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - fs/namei.c:__se_sys_mkdir
  - fs/namei.c:__se_sys_mkdirat
```
**Symbols:**

```
c000000000494ba0-c000000000494d58: do_mkdirat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int do_mkdirat(int dfd, const char *pathname, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe000267806)
Location: fs/namei.c:3817
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - fs/namei.c:__se_sys_mkdir
  - fs/namei.c:__se_sys_mkdirat
```
**Symbols:**

```
ffffffe000267806-ffffffe0002678f4: do_mkdirat (STB_GLOBAL)
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
long int do_mkdirat(int dfd, const char *pathname, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e8eb0)
Location: fs/namei.c:3817
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - fs/namei.c:__ia32_sys_mkdir
  - fs/namei.c:__x64_sys_mkdir
  - fs/namei.c:__ia32_sys_mkdirat
  - fs/namei.c:__x64_sys_mkdirat
```
**Symbols:**

```
ffffffff812e8eb0-ffffffff812e8fbd: do_mkdirat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int do_mkdirat(int dfd, const char *pathname, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d9af0)
Location: fs/namei.c:3817
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - fs/namei.c:__ia32_sys_mkdir
  - fs/namei.c:__x64_sys_mkdir
  - fs/namei.c:__ia32_sys_mkdirat
  - fs/namei.c:__x64_sys_mkdirat
```
**Symbols:**

```
ffffffff812d9af0-ffffffff812d9bfd: do_mkdirat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int do_mkdirat(int dfd, const char *pathname, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e6cc0)
Location: fs/namei.c:3817
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - fs/namei.c:__ia32_sys_mkdir
  - fs/namei.c:__x64_sys_mkdir
  - fs/namei.c:__ia32_sys_mkdirat
  - fs/namei.c:__x64_sys_mkdirat
```
**Symbols:**

```
ffffffff812e6cc0-ffffffff812e6dcd: do_mkdirat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int do_mkdirat(int dfd, const char *pathname, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f7c40)
Location: fs/namei.c:3817
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - fs/namei.c:__ia32_sys_mkdir
  - fs/namei.c:__x64_sys_mkdir
  - fs/namei.c:__ia32_sys_mkdirat
  - fs/namei.c:__x64_sys_mkdirat
```
**Symbols:**

```
ffffffff812f7c40-ffffffff812f7d4d: do_mkdirat (STB_GLOBAL)
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
<code>struct filename *name</code>
</li>
<li>
<b>Param removed. </b>
<code>const char *pathname</code>
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
