# Function: <code>ksys_pwrite64</code>

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
ssize_t ksys_pwrite64(unsigned int fd, const char *buf, size_t count, loff_t pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8129b120)
Location: fs/read_write.c:665
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_pwrite
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_pwrite
  - fs/read_write.c:__ia32_sys_pwrite64
  - fs/read_write.c:__x64_sys_pwrite64
```
**Symbols:**

```
ffffffff8129b120-ffffffff8129b1ba: ksys_pwrite64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t ksys_pwrite64(unsigned int fd, const char *buf, size_t count, loff_t pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812b0020)
Location: fs/read_write.c:665
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_pwrite
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_pwrite
  - fs/read_write.c:__ia32_sys_pwrite64
  - fs/read_write.c:__x64_sys_pwrite64
```
**Symbols:**

```
ffffffff812b0020-ffffffff812b00ba: ksys_pwrite64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t ksys_pwrite64(unsigned int fd, const char *buf, size_t count, loff_t pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812cc9a0)
Location: fs/read_write.c:678
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_pwrite
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_pwrite
  - fs/read_write.c:__ia32_sys_pwrite64
  - fs/read_write.c:__x64_sys_pwrite64
```
**Symbols:**

```
ffffffff812cc9a0-ffffffff812cca31: ksys_pwrite64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t ksys_pwrite64(unsigned int fd, const char *buf, size_t count, loff_t pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812de3c0)
Location: fs/read_write.c:678
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_pwrite
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_pwrite
  - fs/read_write.c:__ia32_sys_pwrite64
  - fs/read_write.c:__x64_sys_pwrite64
```
**Symbols:**

```
ffffffff812de3c0-ffffffff812de451: ksys_pwrite64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t ksys_pwrite64(unsigned int fd, const char *buf, size_t count, loff_t pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8131288b)
Location: fs/read_write.c:706
Inline: True
Inline callers:
  - fs/read_write.c:__ia32_sys_pwrite64
  - fs/read_write.c:__x64_sys_pwrite64
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_pwrite64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_pwrite64
```
**Symbols:**

```
ffffffff81315160-ffffffff813151f1: ksys_pwrite64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
ssize_t ksys_pwrite64(unsigned int fd, const char *buf, size_t count, loff_t pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8131df2b)
Location: fs/read_write.c:701
Inline: True
Inline callers:
  - fs/read_write.c:__ia32_sys_pwrite64
  - fs/read_write.c:__x64_sys_pwrite64
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_pwrite64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_pwrite64
```
**Symbols:**

```
ffffffff813204e0-ffffffff81320571: ksys_pwrite64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
ssize_t ksys_pwrite64(unsigned int fd, const char *buf, size_t count, loff_t pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff813262ab)
Location: fs/read_write.c:699
Inline: True
Inline callers:
  - fs/read_write.c:__ia32_sys_pwrite64
  - fs/read_write.c:__x64_sys_pwrite64
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_pwrite64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_pwrite64
```
**Symbols:**

```
ffffffff81326610-ffffffff813266a1: ksys_pwrite64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
ssize_t ksys_pwrite64(unsigned int fd, const char *buf, size_t count, loff_t pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8137156b)
Location: fs/read_write.c:690
Inline: True
Inline callers:
  - fs/read_write.c:__ia32_sys_pwrite64
  - fs/read_write.c:__x64_sys_pwrite64
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_pwrite64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_pwrite64
```
**Symbols:**

```
ffffffff81373bb0-ffffffff81373c41: ksys_pwrite64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
ssize_t ksys_pwrite64(unsigned int fd, const char *buf, size_t count, loff_t pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff813f2597)
Location: fs/read_write.c:693
Inline: True
Inline callers:
  - fs/read_write.c:__ia32_sys_pwrite64
  - fs/read_write.c:__x64_sys_pwrite64
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_pwrite64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_pwrite64
```
**Symbols:**

```
ffffffff813f2990-ffffffff813f2a31: ksys_pwrite64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
ssize_t ksys_pwrite64(unsigned int fd, const char *buf, size_t count, loff_t pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8147b157)
Location: fs/read_write.c:686
Inline: True
Inline callers:
  - fs/read_write.c:__ia32_sys_pwrite64
  - fs/read_write.c:__x64_sys_pwrite64
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_pwrite64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_pwrite64
```
**Symbols:**

```
ffffffff8147b5d0-ffffffff8147b671: ksys_pwrite64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
ssize_t ksys_pwrite64(unsigned int fd, const char *buf, size_t count, loff_t pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814afce7)
Location: fs/read_write.c:686
Inline: True
Inline callers:
  - fs/read_write.c:__ia32_sys_pwrite64
  - fs/read_write.c:__x64_sys_pwrite64
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_pwrite64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_pwrite64
```
**Symbols:**

```
ffffffff814b0160-ffffffff814b0201: ksys_pwrite64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t ksys_pwrite64(unsigned int fd, const char *buf, size_t count, loff_t pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814e14a7)
Location: fs/read_write.c:692
Inline: True
Inline callers:
  - fs/read_write.c:__ia32_sys_pwrite64
  - fs/read_write.c:__x64_sys_pwrite64
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_pwrite64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_pwrite64
```
**Symbols:**

```
ffffffff814e1920-ffffffff814e19c1: ksys_pwrite64 (STB_GLOBAL)
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
ssize_t ksys_pwrite64(unsigned int fd, const char *buf, size_t count, loff_t pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffff800010384670)
Location: fs/read_write.c:678
Inline: False
Direct callers:
  - arch/arm64/kernel/sys32.c:__arm64_compat_sys_aarch32_pwrite64
  - fs/read_write.c:__arm64_sys_pwrite64
```
**Symbols:**

```
ffff800010384670-ffff800010384730: ksys_pwrite64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t ksys_pwrite64(unsigned int fd, const char *buf, size_t count, loff_t pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c056d3f4)
Location: fs/read_write.c:678
Inline: False
Direct callers:
  - fs/read_write.c:__se_sys_pwrite64
```
**Symbols:**

```
c056d3f4-c056d490: ksys_pwrite64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t ksys_pwrite64(unsigned int fd, const char *buf, size_t count, loff_t pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c00000000047a750)
Location: fs/read_write.c:678
Inline: False
Direct callers:
  - arch/powerpc/kernel/sys_ppc32.c:compat_sys_pwrite64
  - fs/read_write.c:__se_sys_pwrite64
```
**Symbols:**

```
c00000000047a750-c00000000047a830: ksys_pwrite64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t ksys_pwrite64(unsigned int fd, const char *buf, size_t count, loff_t pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffe000257728)
Location: fs/read_write.c:678
Inline: False
Direct callers:
  - fs/read_write.c:__se_sys_pwrite64
```
**Symbols:**

```
ffffffe000257728-ffffffe0002577ba: ksys_pwrite64 (STB_GLOBAL)
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
ssize_t ksys_pwrite64(unsigned int fd, const char *buf, size_t count, loff_t pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d69a0)
Location: fs/read_write.c:678
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_pwrite
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_pwrite
  - fs/read_write.c:__ia32_sys_pwrite64
  - fs/read_write.c:__x64_sys_pwrite64
```
**Symbols:**

```
ffffffff812d69a0-ffffffff812d6a31: ksys_pwrite64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t ksys_pwrite64(unsigned int fd, const char *buf, size_t count, loff_t pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c7620)
Location: fs/read_write.c:678
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_pwrite
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_pwrite
  - fs/read_write.c:__ia32_sys_pwrite64
  - fs/read_write.c:__x64_sys_pwrite64
```
**Symbols:**

```
ffffffff812c7620-ffffffff812c76b1: ksys_pwrite64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t ksys_pwrite64(unsigned int fd, const char *buf, size_t count, loff_t pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d47b0)
Location: fs/read_write.c:678
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_pwrite
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_pwrite
  - fs/read_write.c:__ia32_sys_pwrite64
  - fs/read_write.c:__x64_sys_pwrite64
```
**Symbols:**

```
ffffffff812d47b0-ffffffff812d4841: ksys_pwrite64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t ksys_pwrite64(unsigned int fd, const char *buf, size_t count, loff_t pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812e5610)
Location: fs/read_write.c:678
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_pwrite
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_pwrite
  - fs/read_write.c:__ia32_sys_pwrite64
  - fs/read_write.c:__x64_sys_pwrite64
```
**Symbols:**

```
ffffffff812e5610-ffffffff812e56a1: ksys_pwrite64 (STB_GLOBAL)
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
