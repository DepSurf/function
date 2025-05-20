# Function: <code>do_linkat</code>

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
int do_linkat(int olddfd, const char *oldname, int newdfd, const char *newname, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812ade60)
Location: fs/namei.c:4275
Inline: False
Direct callers:
  - init/initramfs.c:maybe_link
  - fs/namei.c:__ia32_sys_link
  - fs/namei.c:__x64_sys_link
  - fs/namei.c:__ia32_sys_linkat
  - fs/namei.c:__x64_sys_linkat
```
**Symbols:**

```
ffffffff812ade60-ffffffff812ae16a: do_linkat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int do_linkat(int olddfd, const char *oldname, int newdfd, const char *newname, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812c2f70)
Location: fs/namei.c:4264
Inline: False
Direct callers:
  - init/initramfs.c:maybe_link
  - fs/namei.c:__ia32_sys_link
  - fs/namei.c:__x64_sys_link
  - fs/namei.c:__ia32_sys_linkat
  - fs/namei.c:__x64_sys_linkat
```
**Symbols:**

```
ffffffff812c2f70-ffffffff812c327a: do_linkat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int do_linkat(int olddfd, const char *oldname, int newdfd, const char *newname, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812df6b0)
Location: fs/namei.c:4265
Inline: False
Direct callers:
  - init/initramfs.c:maybe_link
  - fs/namei.c:__ia32_sys_link
  - fs/namei.c:__x64_sys_link
  - fs/namei.c:__ia32_sys_linkat
  - fs/namei.c:__x64_sys_linkat
```
**Symbols:**

```
ffffffff812df6b0-ffffffff812df9e9: do_linkat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int do_linkat(int olddfd, const char *oldname, int newdfd, const char *newname, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f11c0)
Location: fs/namei.c:4260
Inline: False
Direct callers:
  - init/initramfs.c:maybe_link
  - fs/namei.c:__ia32_sys_link
  - fs/namei.c:__x64_sys_link
  - fs/namei.c:__ia32_sys_linkat
  - fs/namei.c:__x64_sys_linkat
```
**Symbols:**

```
ffffffff812f11c0-ffffffff812f14f9: do_linkat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_linkat(int olddfd, const char *oldname, int newdfd, const char *newname, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813294c0)
Location: fs/namei.c:4091
Inline: False
Direct callers:
  - init/initramfs.c:maybe_link
  - fs/namei.c:__ia32_sys_link
  - fs/namei.c:__x64_sys_link
  - fs/namei.c:__ia32_sys_linkat
  - fs/namei.c:__x64_sys_linkat
```
**Symbols:**

```
ffffffff813294c0-ffffffff81329793: do_linkat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_linkat(int olddfd, const char *oldname, int newdfd, const char *newname, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81333740)
Location: fs/namei.c:4091
Inline: False
Direct callers:
  - fs/namei.c:__ia32_sys_link
  - fs/namei.c:__x64_sys_link
  - fs/namei.c:__ia32_sys_linkat
  - fs/namei.c:__x64_sys_linkat
```
**Symbols:**

```
ffffffff81333740-ffffffff81333a13: do_linkat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_linkat(int olddfd, const char *oldname, int newdfd, const char *newname, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81339800)
Location: fs/namei.c:4324
Inline: False
Direct callers:
  - fs/namei.c:__ia32_sys_link
  - fs/namei.c:__x64_sys_link
  - fs/namei.c:__ia32_sys_linkat
  - fs/namei.c:__x64_sys_linkat
```
**Symbols:**

```
ffffffff81339800-ffffffff81339ae8: do_linkat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_linkat(int olddfd, struct filename *old, int newdfd, struct filename *new, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81387f70)
Location: fs/namei.c:4402
Inline: False
Direct callers:
  - fs/namei.c:__ia32_sys_link
  - fs/namei.c:__x64_sys_link
  - fs/namei.c:__ia32_sys_linkat
  - fs/namei.c:__x64_sys_linkat
  - fs/io_uring.c:io_issue_sqe
```
**Symbols:**

```
ffffffff81387f70-ffffffff8138823f: do_linkat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_linkat(int olddfd, struct filename *old, int newdfd, struct filename *new, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81408ea0)
Location: fs/namei.c:4497
Inline: False
Direct callers:
  - fs/namei.c:__ia32_sys_link
  - fs/namei.c:__x64_sys_link
  - fs/namei.c:__ia32_sys_linkat
  - fs/namei.c:__x64_sys_linkat
  - io_uring/io_uring.c:io_linkat
```
**Symbols:**

```
ffffffff81408ea0-ffffffff8140919e: do_linkat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_linkat(int olddfd, struct filename *old, int newdfd, struct filename *new, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814934f0)
Location: fs/namei.c:4553
Inline: False
Direct callers:
  - fs/namei.c:__ia32_sys_link
  - fs/namei.c:__x64_sys_link
  - fs/namei.c:__ia32_sys_linkat
  - fs/namei.c:__x64_sys_linkat
  - io_uring/fs.c:io_linkat
```
**Symbols:**

```
ffffffff814934f0-ffffffff814937f1: do_linkat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_linkat(int olddfd, struct filename *old, int newdfd, struct filename *new, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814c8540)
Location: fs/namei.c:4625
Inline: False
Direct callers:
  - fs/namei.c:__ia32_sys_link
  - fs/namei.c:__x64_sys_link
  - fs/namei.c:__ia32_sys_linkat
  - fs/namei.c:__x64_sys_linkat
  - io_uring/fs.c:io_linkat
```
**Symbols:**

```
ffffffff814c8540-ffffffff814c883e: do_linkat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_linkat(int olddfd, struct filename *old, int newdfd, struct filename *new, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814fade0)
Location: fs/namei.c:4632
Inline: False
Direct callers:
  - fs/namei.c:__ia32_sys_link
  - fs/namei.c:__x64_sys_link
  - fs/namei.c:__ia32_sys_linkat
  - fs/namei.c:__x64_sys_linkat
  - io_uring/fs.c:io_linkat
```
**Symbols:**

```
ffffffff814fade0-ffffffff814fb0ec: do_linkat (STB_GLOBAL)
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
int do_linkat(int olddfd, const char *oldname, int newdfd, const char *newname, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff80001039a908)
Location: fs/namei.c:4260
Inline: False
Direct callers:
  - init/initramfs.c:maybe_link
  - fs/namei.c:__arm64_sys_link
  - fs/namei.c:__arm64_sys_linkat
```
**Symbols:**

```
ffff80001039a908-ffff80001039ac28: do_linkat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_linkat(int olddfd, const char *oldname, int newdfd, const char *newname, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c0580d80)
Location: fs/namei.c:4260
Inline: False
Direct callers:
  - init/initramfs.c:maybe_link
  - fs/namei.c:__se_sys_link
  - fs/namei.c:__se_sys_linkat
```
**Symbols:**

```
c0580d80-c05810f0: do_linkat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_linkat(int olddfd, const char *oldname, int newdfd, const char *newname, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c0000000004956f0)
Location: fs/namei.c:4260
Inline: False
Direct callers:
  - init/initramfs.c:maybe_link
  - fs/namei.c:__se_sys_link
  - fs/namei.c:__se_sys_linkat
```
**Symbols:**

```
c0000000004956f0-c000000000495b7c: do_linkat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int do_linkat(int olddfd, const char *oldname, int newdfd, const char *newname, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe000267fa8)
Location: fs/namei.c:4260
Inline: False
Direct callers:
  - init/initramfs.c:maybe_link
  - fs/namei.c:__se_sys_link
  - fs/namei.c:__se_sys_linkat
```
**Symbols:**

```
ffffffe000267fa8-ffffffe000268252: do_linkat (STB_GLOBAL)
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
int do_linkat(int olddfd, const char *oldname, int newdfd, const char *newname, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e97a0)
Location: fs/namei.c:4260
Inline: False
Direct callers:
  - init/initramfs.c:maybe_link
  - fs/namei.c:__ia32_sys_link
  - fs/namei.c:__x64_sys_link
  - fs/namei.c:__ia32_sys_linkat
  - fs/namei.c:__x64_sys_linkat
```
**Symbols:**

```
ffffffff812e97a0-ffffffff812e9ad9: do_linkat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int do_linkat(int olddfd, const char *oldname, int newdfd, const char *newname, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812da3e0)
Location: fs/namei.c:4260
Inline: False
Direct callers:
  - init/initramfs.c:maybe_link
  - fs/namei.c:__ia32_sys_link
  - fs/namei.c:__x64_sys_link
  - fs/namei.c:__ia32_sys_linkat
  - fs/namei.c:__x64_sys_linkat
```
**Symbols:**

```
ffffffff812da3e0-ffffffff812da719: do_linkat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int do_linkat(int olddfd, const char *oldname, int newdfd, const char *newname, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e75b0)
Location: fs/namei.c:4260
Inline: False
Direct callers:
  - init/initramfs.c:maybe_link
  - fs/namei.c:__ia32_sys_link
  - fs/namei.c:__x64_sys_link
  - fs/namei.c:__ia32_sys_linkat
  - fs/namei.c:__x64_sys_linkat
```
**Symbols:**

```
ffffffff812e75b0-ffffffff812e78e9: do_linkat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int do_linkat(int olddfd, const char *oldname, int newdfd, const char *newname, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f8530)
Location: fs/namei.c:4260
Inline: False
Direct callers:
  - init/initramfs.c:maybe_link
  - fs/namei.c:__ia32_sys_link
  - fs/namei.c:__x64_sys_link
  - fs/namei.c:__ia32_sys_linkat
  - fs/namei.c:__x64_sys_linkat
```
**Symbols:**

```
ffffffff812f8530-ffffffff812f8869: do_linkat (STB_GLOBAL)
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
<code>struct filename *old</code>
</li>
<li>
<b>Param added. </b>
<code>struct filename *new</code>
</li>
<li>
<b>Param removed. </b>
<code>const char *oldname</code>
</li>
<li>
<b>Param removed. </b>
<code>const char *newname</code>
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
