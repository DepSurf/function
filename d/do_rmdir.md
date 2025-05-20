# Function: <code>do_rmdir</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int do_rmdir(int dfd, const char *pathname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8121c7b0)
Location: fs/namei.c:3711
Inline: False
Direct callers:
  - fs/namei.c:SyS_rmdir
  - fs/namei.c:SyS_unlinkat
```
**Symbols:**

```
ffffffff8121c7b0-ffffffff8121c9a9: do_rmdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int do_rmdir(int dfd, const char *pathname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81243c30)
Location: fs/namei.c:3854
Inline: False
Direct callers:
  - fs/namei.c:SyS_unlinkat
  - fs/namei.c:SyS_rmdir
```
**Symbols:**

```
ffffffff81243c30-ffffffff81243e73: do_rmdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int do_rmdir(int dfd, const char *pathname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81256bb0)
Location: fs/namei.c:3811
Inline: False
Direct callers:
  - fs/namei.c:SyS_unlinkat
  - fs/namei.c:SyS_rmdir
```
**Symbols:**

```
ffffffff81256bb0-ffffffff81256dd7: do_rmdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int do_rmdir(int dfd, const char *pathname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81262d50)
Location: fs/namei.c:3876
Inline: False
Direct callers:
  - fs/namei.c:SyS_unlinkat
  - fs/namei.c:SyS_rmdir
```
**Symbols:**

```
ffffffff81262d50-ffffffff81262f5d: do_rmdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int do_rmdir(int dfd, const char *pathname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812855a0)
Location: fs/namei.c:3874
Inline: False
Direct callers:
  - fs/namei.c:SyS_unlinkat
  - fs/namei.c:SyS_rmdir
```
**Symbols:**

```
ffffffff812855a0-ffffffff812857ad: do_rmdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int do_rmdir(int dfd, const char *pathname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812ad6b0)
Location: fs/namei.c:3908
Inline: False
Direct callers:
  - init/initramfs.c:clean_path
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:__ia32_sys_rmdir
  - fs/namei.c:__x64_sys_rmdir
```
**Symbols:**

```
ffffffff812ad6b0-ffffffff812ad890: do_rmdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int do_rmdir(int dfd, const char *pathname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812c27b0)
Location: fs/namei.c:3897
Inline: False
Direct callers:
  - init/initramfs.c:clean_path
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:__ia32_sys_rmdir
  - fs/namei.c:__x64_sys_rmdir
```
**Symbols:**

```
ffffffff812c27b0-ffffffff812c29b3: do_rmdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int do_rmdir(int dfd, const char *pathname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812def50)
Location: fs/namei.c:3897
Inline: False
Direct callers:
  - init/initramfs.c:clean_path
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:__ia32_sys_rmdir
  - fs/namei.c:__x64_sys_rmdir
```
**Symbols:**

```
ffffffff812def50-ffffffff812df10f: do_rmdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int do_rmdir(int dfd, const char *pathname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f0a60)
Location: fs/namei.c:3892
Inline: False
Direct callers:
  - init/initramfs.c:clean_path
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:__ia32_sys_rmdir
  - fs/namei.c:__x64_sys_rmdir
```
**Symbols:**

```
ffffffff812f0a60-ffffffff812f0c1f: do_rmdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int do_rmdir(int dfd, const char *pathname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81328c80)
Location: fs/namei.c:3723
Inline: False
Direct callers:
  - init/initramfs.c:clean_path
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:__ia32_sys_rmdir
  - fs/namei.c:__x64_sys_rmdir
```
**Symbols:**

```
ffffffff81328c80-ffffffff81328e7e: do_rmdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int do_rmdir(int dfd, struct filename *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81333fa0)
Location: fs/namei.c:3725
Inline: False
Direct callers:
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:__ia32_sys_rmdir
  - fs/namei.c:__x64_sys_rmdir
  - fs/init.c:init_rmdir
  - fs/io_uring.c:io_issue_sqe
```
**Symbols:**

```
ffffffff81333fa0-ffffffff81334163: do_rmdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int do_rmdir(int dfd, struct filename *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8133a0a0)
Location: fs/namei.c:3914
Inline: False
Direct callers:
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:__ia32_sys_rmdir
  - fs/namei.c:__x64_sys_rmdir
  - fs/init.c:init_rmdir
  - fs/io_uring.c:io_issue_sqe
```
**Symbols:**

```
ffffffff8133a0a0-ffffffff8133a236: do_rmdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_rmdir(int dfd, struct filename *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81387660)
Location: fs/namei.c:3988
Inline: False
Direct callers:
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:__ia32_sys_rmdir
  - fs/namei.c:__x64_sys_rmdir
  - fs/init.c:init_rmdir
  - fs/io_uring.c:io_issue_sqe
```
**Symbols:**

```
ffffffff81387660-ffffffff813877ee: do_rmdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_rmdir(int dfd, struct filename *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81408490)
Location: fs/namei.c:4083
Inline: False
Direct callers:
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:__ia32_sys_rmdir
  - fs/namei.c:__x64_sys_rmdir
  - fs/init.c:init_rmdir
  - io_uring/io_uring.c:io_unlinkat
```
**Symbols:**

```
ffffffff81408490-ffffffff81408630: do_rmdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_rmdir(int dfd, struct filename *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814929f0)
Location: fs/namei.c:4139
Inline: False
Direct callers:
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:__ia32_sys_rmdir
  - fs/namei.c:__x64_sys_rmdir
  - fs/init.c:init_rmdir
  - io_uring/fs.c:io_unlinkat
```
**Symbols:**

```
ffffffff814929f0-ffffffff81492b94: do_rmdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_rmdir(int dfd, struct filename *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814c7a40)
Location: fs/namei.c:4218
Inline: False
Direct callers:
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:__ia32_sys_rmdir
  - fs/namei.c:__x64_sys_rmdir
  - fs/init.c:init_rmdir
  - io_uring/fs.c:io_unlinkat
```
**Symbols:**

```
ffffffff814c7a40-ffffffff814c7be3: do_rmdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_rmdir(int dfd, struct filename *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814fa2d0)
Location: fs/namei.c:4227
Inline: False
Direct callers:
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:__ia32_sys_rmdir
  - fs/namei.c:__x64_sys_rmdir
  - fs/init.c:init_rmdir
  - io_uring/fs.c:io_unlinkat
```
**Symbols:**

```
ffffffff814fa2d0-ffffffff814fa47d: do_rmdir (STB_GLOBAL)
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
long int do_rmdir(int dfd, const char *pathname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff80001039a228)
Location: fs/namei.c:3892
Inline: False
Direct callers:
  - init/initramfs.c:clean_path
  - fs/namei.c:__arm64_sys_unlinkat
  - fs/namei.c:__arm64_sys_rmdir
```
**Symbols:**

```
ffff80001039a228-ffff80001039a3f4: do_rmdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int do_rmdir(int dfd, const char *pathname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c05806f4)
Location: fs/namei.c:3892
Inline: False
Direct callers:
  - init/initramfs.c:clean_path
  - fs/namei.c:__se_sys_unlinkat
  - fs/namei.c:__se_sys_rmdir
```
**Symbols:**

```
c05806f4-c05808d8: do_rmdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int do_rmdir(int dfd, const char *pathname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c000000000494db0)
Location: fs/namei.c:3892
Inline: False
Direct callers:
  - init/initramfs.c:clean_path
  - fs/namei.c:__se_sys_unlinkat
  - fs/namei.c:__se_sys_rmdir
```
**Symbols:**

```
c000000000494db0-c000000000495048: do_rmdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int do_rmdir(int dfd, const char *pathname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe00026796e)
Location: fs/namei.c:3892
Inline: False
Direct callers:
  - init/initramfs.c:clean_path
  - fs/namei.c:__se_sys_unlinkat
  - fs/namei.c:__se_sys_rmdir
```
**Symbols:**

```
ffffffe00026796e-ffffffe000267b02: do_rmdir (STB_GLOBAL)
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
long int do_rmdir(int dfd, const char *pathname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e9040)
Location: fs/namei.c:3892
Inline: False
Direct callers:
  - init/initramfs.c:clean_path
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:__ia32_sys_rmdir
  - fs/namei.c:__x64_sys_rmdir
```
**Symbols:**

```
ffffffff812e9040-ffffffff812e91ff: do_rmdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int do_rmdir(int dfd, const char *pathname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d9c80)
Location: fs/namei.c:3892
Inline: False
Direct callers:
  - init/initramfs.c:clean_path
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:__ia32_sys_rmdir
  - fs/namei.c:__x64_sys_rmdir
```
**Symbols:**

```
ffffffff812d9c80-ffffffff812d9e3f: do_rmdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int do_rmdir(int dfd, const char *pathname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e6e50)
Location: fs/namei.c:3892
Inline: False
Direct callers:
  - init/initramfs.c:clean_path
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:__ia32_sys_rmdir
  - fs/namei.c:__x64_sys_rmdir
```
**Symbols:**

```
ffffffff812e6e50-ffffffff812e700f: do_rmdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int do_rmdir(int dfd, const char *pathname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f7dd0)
Location: fs/namei.c:3892
Inline: False
Direct callers:
  - init/initramfs.c:clean_path
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/namei.c:__ia32_sys_rmdir
  - fs/namei.c:__x64_sys_rmdir
```
**Symbols:**

```
ffffffff812f7dd0-ffffffff812f7f8f: do_rmdir (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct filename *name</code>
</li>
<li>
<b>Param removed. </b>
<code>const char *pathname</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
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
