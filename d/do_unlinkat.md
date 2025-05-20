# Function: <code>do_unlinkat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int do_unlinkat(int dfd, const char *pathname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8121c9b0)
Location: fs/namei.c:3839
Inline: False
Direct callers:
  - fs/namei.c:SyS_unlinkat
  - fs/namei.c:SyS_unlink
```
**Symbols:**

```
ffffffff8121c9b0-ffffffff8121cc7a: do_unlinkat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int do_unlinkat(int dfd, const char *pathname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81243e80)
Location: fs/namei.c:3982
Inline: False
Direct callers:
  - fs/namei.c:SyS_unlink
  - fs/namei.c:SyS_unlinkat
```
**Symbols:**

```
ffffffff81243e80-ffffffff81244185: do_unlinkat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int do_unlinkat(int dfd, const char *pathname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81256de0)
Location: fs/namei.c:3939
Inline: False
Direct callers:
  - fs/namei.c:SyS_unlink
  - fs/namei.c:SyS_unlinkat
```
**Symbols:**

```
ffffffff81256de0-ffffffff812570f3: do_unlinkat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int do_unlinkat(int dfd, const char *pathname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81262f60)
Location: fs/namei.c:4004
Inline: False
Direct callers:
  - fs/namei.c:SyS_unlink
  - fs/namei.c:SyS_unlinkat
```
**Symbols:**

```
ffffffff81262f60-ffffffff81263269: do_unlinkat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int do_unlinkat(int dfd, struct filename *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81286300)
Location: fs/namei.c:4002
Inline: False
Direct callers:
  - fs/namei.c:SyS_unlink
  - fs/namei.c:SyS_unlinkat
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff81286300-ffffffff81286611: do_unlinkat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int do_unlinkat(int dfd, struct filename *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812ad8d0)
Location: fs/namei.c:4036
Inline: False
Direct callers:
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/initramfs.c:clean_path
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff812ad8d0-ffffffff812adbc6: do_unlinkat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int do_unlinkat(int dfd, struct filename *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812c2a00)
Location: fs/namei.c:4025
Inline: False
Direct callers:
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/initramfs.c:clean_path
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff812c2a00-ffffffff812c2cd3: do_unlinkat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int do_unlinkat(int dfd, struct filename *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812df150)
Location: fs/namei.c:4026
Inline: False
Direct callers:
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/initramfs.c:clean_path
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff812df150-ffffffff812df416: do_unlinkat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int do_unlinkat(int dfd, struct filename *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f0c60)
Location: fs/namei.c:4021
Inline: False
Direct callers:
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/initramfs.c:clean_path
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff812f0c60-ffffffff812f0f26: do_unlinkat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int do_unlinkat(int dfd, struct filename *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81328ec0)
Location: fs/namei.c:3852
Inline: False
Direct callers:
  - init/initramfs.c:clean_path
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff81328ec0-ffffffff81329186: do_unlinkat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int do_unlinkat(int dfd, struct filename *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81334230)
Location: fs/namei.c:3853
Inline: False
Direct callers:
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/init.c:init_unlink
  - fs/io_uring.c:io_issue_sqe
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff81334230-ffffffff813344f6: do_unlinkat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int do_unlinkat(int dfd, struct filename *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8133a300)
Location: fs/namei.c:4052
Inline: False
Direct callers:
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/init.c:init_unlink
  - fs/io_uring.c:io_issue_sqe
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff8133a300-ffffffff8133a5d3: do_unlinkat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_unlinkat(int dfd, struct filename *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813878b0)
Location: fs/namei.c:4129
Inline: False
Direct callers:
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/init.c:init_unlink
  - fs/io_uring.c:io_issue_sqe
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff813878b0-ffffffff81387b60: do_unlinkat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_unlinkat(int dfd, struct filename *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81408710)
Location: fs/namei.c:4224
Inline: False
Direct callers:
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/init.c:init_unlink
  - fs/coredump.c:do_coredump
  - io_uring/io_uring.c:io_unlinkat
```
**Symbols:**

```
ffffffff81408710-ffffffff81408a10: do_unlinkat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_unlinkat(int dfd, struct filename *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81492cb0)
Location: fs/namei.c:4280
Inline: False
Direct callers:
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/init.c:init_unlink
  - fs/coredump.c:do_coredump
  - io_uring/fs.c:io_unlinkat
```
**Symbols:**

```
ffffffff81492cb0-ffffffff81492fb4: do_unlinkat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_unlinkat(int dfd, struct filename *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814c7d00)
Location: fs/namei.c:4357
Inline: False
Direct callers:
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/init.c:init_unlink
  - fs/coredump.c:do_coredump
  - io_uring/fs.c:io_unlinkat
```
**Symbols:**

```
ffffffff814c7d00-ffffffff814c8003: do_unlinkat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_unlinkat(int dfd, struct filename *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814fa590)
Location: fs/namei.c:4366
Inline: False
Direct callers:
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/init.c:init_unlink
  - fs/coredump.c:do_coredump
  - io_uring/fs.c:io_unlinkat
```
**Symbols:**

```
ffffffff814fa590-ffffffff814fa8ab: do_unlinkat (STB_GLOBAL)
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
long int do_unlinkat(int dfd, struct filename *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff80001039a428)
Location: fs/namei.c:4021
Inline: False
Direct callers:
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/initramfs.c:clean_path
  - fs/namei.c:__arm64_sys_unlink
  - fs/namei.c:__arm64_sys_unlinkat
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffff80001039a428-ffff80001039a6c4: do_unlinkat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int do_unlinkat(int dfd, struct filename *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c05808fc)
Location: fs/namei.c:4021
Inline: False
Direct callers:
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/initramfs.c:clean_path
  - fs/namei.c:__se_sys_unlink
  - fs/namei.c:__se_sys_unlinkat
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
c05808fc-c0580ba0: do_unlinkat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int do_unlinkat(int dfd, struct filename *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c000000000495070)
Location: fs/namei.c:4021
Inline: False
Direct callers:
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/initramfs.c:clean_path
  - fs/namei.c:__se_sys_unlink
  - fs/namei.c:__se_sys_unlinkat
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
c000000000495070-c00000000049540c: do_unlinkat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int do_unlinkat(int dfd, struct filename *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe000267b30)
Location: fs/namei.c:4021
Inline: False
Direct callers:
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/initramfs.c:clean_path
  - fs/namei.c:__se_sys_unlink
  - fs/namei.c:__se_sys_unlinkat
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffe000267b30-ffffffe000267d90: do_unlinkat (STB_GLOBAL)
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
long int do_unlinkat(int dfd, struct filename *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e9240)
Location: fs/namei.c:4021
Inline: False
Direct callers:
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/initramfs.c:clean_path
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff812e9240-ffffffff812e9506: do_unlinkat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int do_unlinkat(int dfd, struct filename *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d9e80)
Location: fs/namei.c:4021
Inline: False
Direct callers:
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/initramfs.c:clean_path
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff812d9e80-ffffffff812da146: do_unlinkat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int do_unlinkat(int dfd, struct filename *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e7050)
Location: fs/namei.c:4021
Inline: False
Direct callers:
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/initramfs.c:clean_path
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff812e7050-ffffffff812e7316: do_unlinkat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int do_unlinkat(int dfd, struct filename *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f7fd0)
Location: fs/namei.c:4021
Inline: False
Direct callers:
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/initramfs.c:clean_path
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_unlinkat
  - fs/namei.c:__x64_sys_unlinkat
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff812f7fd0-ffffffff812f8296: do_unlinkat (STB_GLOBAL)
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
