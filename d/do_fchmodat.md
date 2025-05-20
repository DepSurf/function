# Function: <code>do_fchmodat</code>

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
int do_fchmodat(int dfd, const char *filename, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812965b0)
Location: fs/open.c:586
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
  - fs/open.c:__ia32_sys_chmod
  - fs/open.c:__x64_sys_chmod
  - fs/open.c:__ia32_sys_fchmodat
  - fs/open.c:__x64_sys_fchmodat
```
**Symbols:**

```
ffffffff812965b0-ffffffff81296659: do_fchmodat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int do_fchmodat(int dfd, const char *filename, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812ab3a0)
Location: fs/open.c:575
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
  - fs/open.c:__ia32_sys_chmod
  - fs/open.c:__x64_sys_chmod
  - fs/open.c:__ia32_sys_fchmodat
  - fs/open.c:__x64_sys_fchmodat
```
**Symbols:**

```
ffffffff812ab3a0-ffffffff812ab449: do_fchmodat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int do_fchmodat(int dfd, const char *filename, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812c7ba0)
Location: fs/open.c:595
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
  - fs/open.c:__ia32_sys_chmod
  - fs/open.c:__x64_sys_chmod
  - fs/open.c:__ia32_sys_fchmodat
  - fs/open.c:__x64_sys_fchmodat
```
**Symbols:**

```
ffffffff812c7ba0-ffffffff812c7c4d: do_fchmodat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int do_fchmodat(int dfd, const char *filename, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812d95b0)
Location: fs/open.c:595
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
  - fs/open.c:__ia32_sys_chmod
  - fs/open.c:__x64_sys_chmod
  - fs/open.c:__ia32_sys_fchmodat
  - fs/open.c:__x64_sys_fchmodat
```
**Symbols:**

```
ffffffff812d95b0-ffffffff812d965d: do_fchmodat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_fchmodat(int dfd, const char *filename, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8130f370)
Location: fs/open.c:624
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
  - fs/open.c:__ia32_sys_chmod
  - fs/open.c:__x64_sys_chmod
  - fs/open.c:__ia32_sys_fchmodat
  - fs/open.c:__x64_sys_fchmodat
```
**Symbols:**

```
ffffffff8130f370-ffffffff8130f41d: do_fchmodat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_fchmodat(int dfd, const char *filename, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8131b260)
Location: fs/open.c:614
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_chmod
  - fs/open.c:__x64_sys_chmod
  - fs/open.c:__ia32_sys_fchmodat
  - fs/open.c:__x64_sys_fchmodat
```
**Symbols:**

```
ffffffff8131b260-ffffffff8131b30d: do_fchmodat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_fchmodat(int dfd, const char *filename, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81321370)
Location: fs/open.c:616
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_chmod
  - fs/open.c:__x64_sys_chmod
  - fs/open.c:__ia32_sys_fchmodat
  - fs/open.c:__x64_sys_fchmodat
```
**Symbols:**

```
ffffffff81321370-ffffffff8132141d: do_fchmodat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_fchmodat(int dfd, const char *filename, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8136e850)
Location: fs/open.c:613
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_chmod
  - fs/open.c:__x64_sys_chmod
  - fs/open.c:__ia32_sys_fchmodat
  - fs/open.c:__x64_sys_fchmodat
```
**Symbols:**

```
ffffffff8136e850-ffffffff8136e8fd: do_fchmodat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_fchmodat(int dfd, const char *filename, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff813ecff0)
Location: fs/open.c:637
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_chmod
  - fs/open.c:__x64_sys_chmod
  - fs/open.c:__ia32_sys_fchmodat
  - fs/open.c:__x64_sys_fchmodat
```
**Symbols:**

```
ffffffff813ecff0-ffffffff813ed0b8: do_fchmodat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_fchmodat(int dfd, const char *filename, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814755e0)
Location: fs/open.c:637
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_chmod
  - fs/open.c:__x64_sys_chmod
  - fs/open.c:__ia32_sys_fchmodat
  - fs/open.c:__x64_sys_fchmodat
```
**Symbols:**

```
ffffffff814755e0-ffffffff814756a8: do_fchmodat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_fchmodat(int dfd, const char *filename, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814a9f70)
Location: fs/open.c:674
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_chmod
  - fs/open.c:__x64_sys_chmod
  - fs/open.c:__ia32_sys_fchmodat
  - fs/open.c:__x64_sys_fchmodat
```
**Symbols:**

```
ffffffff814a9f70-ffffffff814aa038: do_fchmodat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int do_fchmodat(int dfd, const char *filename, umode_t mode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814db5a7)
Location: fs/open.c:679
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_chmod
  - fs/open.c:__x64_sys_chmod
  - fs/open.c:__ia32_sys_fchmodat
  - fs/open.c:__x64_sys_fchmodat
Direct callers:
  - fs/open.c:__ia32_sys_fchmodat2
  - fs/open.c:__x64_sys_fchmodat2
```
**Symbols:**

```
ffffffff814db0b0-ffffffff814db195: do_fchmodat (STB_LOCAL)
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
int do_fchmodat(int dfd, const char *filename, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffff80001037e920)
Location: fs/open.c:595
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
  - fs/open.c:__arm64_sys_chmod
  - fs/open.c:__arm64_sys_fchmodat
```
**Symbols:**

```
ffff80001037e920-ffff80001037e9e0: do_fchmodat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_fchmodat(int dfd, const char *filename, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (c05692bc)
Location: fs/open.c:595
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
  - fs/open.c:__se_sys_chmod
  - fs/open.c:__se_sys_fchmodat
```
**Symbols:**

```
c05692bc-c0569378: do_fchmodat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_fchmodat(int dfd, const char *filename, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (c000000000474550)
Location: fs/open.c:595
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
  - fs/open.c:__se_sys_chmod
  - fs/open.c:__se_sys_fchmodat
```
**Symbols:**

```
c000000000474550-c00000000047463c: do_fchmodat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int do_fchmodat(int dfd, const char *filename, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffe0002545c6)
Location: fs/open.c:595
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
  - fs/open.c:__se_sys_chmod
  - fs/open.c:__se_sys_fchmodat
```
**Symbols:**

```
ffffffe0002545c6-ffffffe000254650: do_fchmodat (STB_GLOBAL)
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
int do_fchmodat(int dfd, const char *filename, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812d1b90)
Location: fs/open.c:595
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
  - fs/open.c:__ia32_sys_chmod
  - fs/open.c:__x64_sys_chmod
  - fs/open.c:__ia32_sys_fchmodat
  - fs/open.c:__x64_sys_fchmodat
```
**Symbols:**

```
ffffffff812d1b90-ffffffff812d1c3d: do_fchmodat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int do_fchmodat(int dfd, const char *filename, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812c2810)
Location: fs/open.c:595
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
  - fs/open.c:__ia32_sys_chmod
  - fs/open.c:__x64_sys_chmod
  - fs/open.c:__ia32_sys_fchmodat
  - fs/open.c:__x64_sys_fchmodat
```
**Symbols:**

```
ffffffff812c2810-ffffffff812c28bd: do_fchmodat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int do_fchmodat(int dfd, const char *filename, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812cf9a0)
Location: fs/open.c:595
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
  - fs/open.c:__ia32_sys_chmod
  - fs/open.c:__x64_sys_chmod
  - fs/open.c:__ia32_sys_fchmodat
  - fs/open.c:__x64_sys_fchmodat
```
**Symbols:**

```
ffffffff812cf9a0-ffffffff812cfa4d: do_fchmodat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int do_fchmodat(int dfd, const char *filename, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812e07b0)
Location: fs/open.c:595
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
  - fs/open.c:__ia32_sys_chmod
  - fs/open.c:__x64_sys_chmod
  - fs/open.c:__ia32_sys_fchmodat
  - fs/open.c:__x64_sys_fchmodat
```
**Symbols:**

```
ffffffff812e07b0-ffffffff812e085d: do_fchmodat (STB_GLOBAL)
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
<b>Param added. </b>
<code>unsigned int flags</code>
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
