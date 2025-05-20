# Function: <code>ksys_pread64</code>

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
ssize_t ksys_pread64(unsigned int fd, char *buf, size_t count, loff_t pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8129b040)
Location: fs/read_write.c:639
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_pread
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_pread
  - fs/read_write.c:__ia32_sys_pread64
  - fs/read_write.c:__x64_sys_pread64
```
**Symbols:**

```
ffffffff8129b040-ffffffff8129b0da: ksys_pread64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t ksys_pread64(unsigned int fd, char *buf, size_t count, loff_t pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812aff40)
Location: fs/read_write.c:639
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_pread
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_pread
  - fs/read_write.c:__ia32_sys_pread64
  - fs/read_write.c:__x64_sys_pread64
```
**Symbols:**

```
ffffffff812aff40-ffffffff812affda: ksys_pread64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t ksys_pread64(unsigned int fd, char *buf, size_t count, loff_t pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812cc8c0)
Location: fs/read_write.c:652
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_pread
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_pread
  - fs/read_write.c:__ia32_sys_pread64
  - fs/read_write.c:__x64_sys_pread64
```
**Symbols:**

```
ffffffff812cc8c0-ffffffff812cc951: ksys_pread64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t ksys_pread64(unsigned int fd, char *buf, size_t count, loff_t pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812de2e0)
Location: fs/read_write.c:652
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_pread
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_pread
  - fs/read_write.c:__ia32_sys_pread64
  - fs/read_write.c:__x64_sys_pread64
```
**Symbols:**

```
ffffffff812de2e0-ffffffff812de371: ksys_pread64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t ksys_pread64(unsigned int fd, char *buf, size_t count, loff_t pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8131244b)
Location: fs/read_write.c:680
Inline: True
Inline callers:
  - fs/read_write.c:__ia32_sys_pread64
  - fs/read_write.c:__x64_sys_pread64
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_pread64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_pread64
```
**Symbols:**

```
ffffffff813150c0-ffffffff81315151: ksys_pread64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
ssize_t ksys_pread64(unsigned int fd, char *buf, size_t count, loff_t pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8131da3b)
Location: fs/read_write.c:675
Inline: True
Inline callers:
  - fs/read_write.c:__ia32_sys_pread64
  - fs/read_write.c:__x64_sys_pread64
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_pread64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_pread64
```
**Symbols:**

```
ffffffff81320440-ffffffff813204d1: ksys_pread64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
ssize_t ksys_pread64(unsigned int fd, char *buf, size_t count, loff_t pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81325edb)
Location: fs/read_write.c:673
Inline: True
Inline callers:
  - fs/read_write.c:__ia32_sys_pread64
  - fs/read_write.c:__x64_sys_pread64
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_pread64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_pread64
```
**Symbols:**

```
ffffffff81326570-ffffffff81326601: ksys_pread64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
ssize_t ksys_pread64(unsigned int fd, char *buf, size_t count, loff_t pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8137118b)
Location: fs/read_write.c:664
Inline: True
Inline callers:
  - fs/read_write.c:__ia32_sys_pread64
  - fs/read_write.c:__x64_sys_pread64
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_pread64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_pread64
```
**Symbols:**

```
ffffffff81373b10-ffffffff81373ba1: ksys_pread64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
ssize_t ksys_pread64(unsigned int fd, char *buf, size_t count, loff_t pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff813f2177)
Location: fs/read_write.c:659
Inline: True
Inline callers:
  - fs/read_write.c:__ia32_sys_pread64
  - fs/read_write.c:__x64_sys_pread64
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_pread64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_pread64
```
**Symbols:**

```
ffffffff813f28e0-ffffffff813f2981: ksys_pread64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
ssize_t ksys_pread64(unsigned int fd, char *buf, size_t count, loff_t pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8147a687)
Location: fs/read_write.c:652
Inline: True
Inline callers:
  - fs/read_write.c:__ia32_sys_pread64
  - fs/read_write.c:__x64_sys_pread64
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_pread64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_pread64
```
**Symbols:**

```
ffffffff8147b510-ffffffff8147b5b1: ksys_pread64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
ssize_t ksys_pread64(unsigned int fd, char *buf, size_t count, loff_t pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814af1b7)
Location: fs/read_write.c:652
Inline: True
Inline callers:
  - fs/read_write.c:__ia32_sys_pread64
  - fs/read_write.c:__x64_sys_pread64
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_pread64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_pread64
```
**Symbols:**

```
ffffffff814b00a0-ffffffff814b0141: ksys_pread64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t ksys_pread64(unsigned int fd, char *buf, size_t count, loff_t pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814e08f7)
Location: fs/read_write.c:658
Inline: True
Inline callers:
  - fs/read_write.c:__ia32_sys_pread64
  - fs/read_write.c:__x64_sys_pread64
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_pread64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_pread64
```
**Symbols:**

```
ffffffff814e1860-ffffffff814e1901: ksys_pread64 (STB_GLOBAL)
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
ssize_t ksys_pread64(unsigned int fd, char *buf, size_t count, loff_t pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffff800010384578)
Location: fs/read_write.c:652
Inline: False
Direct callers:
  - arch/arm64/kernel/sys32.c:__arm64_compat_sys_aarch32_pread64
  - fs/read_write.c:__arm64_sys_pread64
```
**Symbols:**

```
ffff800010384578-ffff800010384638: ksys_pread64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t ksys_pread64(unsigned int fd, char *buf, size_t count, loff_t pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c056d32c)
Location: fs/read_write.c:652
Inline: False
Direct callers:
  - fs/read_write.c:__se_sys_pread64
```
**Symbols:**

```
c056d32c-c056d3c8: ksys_pread64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t ksys_pread64(unsigned int fd, char *buf, size_t count, loff_t pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c00000000047a650)
Location: fs/read_write.c:652
Inline: False
Direct callers:
  - arch/powerpc/kernel/sys_ppc32.c:compat_sys_pread64
  - fs/read_write.c:__se_sys_pread64
```
**Symbols:**

```
c00000000047a650-c00000000047a730: ksys_pread64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t ksys_pread64(unsigned int fd, char *buf, size_t count, loff_t pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffe000257652)
Location: fs/read_write.c:652
Inline: False
Direct callers:
  - fs/read_write.c:__se_sys_pread64
```
**Symbols:**

```
ffffffe000257652-ffffffe0002576e4: ksys_pread64 (STB_GLOBAL)
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
ssize_t ksys_pread64(unsigned int fd, char *buf, size_t count, loff_t pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d68c0)
Location: fs/read_write.c:652
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_pread
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_pread
  - fs/read_write.c:__ia32_sys_pread64
  - fs/read_write.c:__x64_sys_pread64
```
**Symbols:**

```
ffffffff812d68c0-ffffffff812d6951: ksys_pread64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t ksys_pread64(unsigned int fd, char *buf, size_t count, loff_t pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c7540)
Location: fs/read_write.c:652
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_pread
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_pread
  - fs/read_write.c:__ia32_sys_pread64
  - fs/read_write.c:__x64_sys_pread64
```
**Symbols:**

```
ffffffff812c7540-ffffffff812c75d1: ksys_pread64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t ksys_pread64(unsigned int fd, char *buf, size_t count, loff_t pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d46d0)
Location: fs/read_write.c:652
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_pread
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_pread
  - fs/read_write.c:__ia32_sys_pread64
  - fs/read_write.c:__x64_sys_pread64
```
**Symbols:**

```
ffffffff812d46d0-ffffffff812d4761: ksys_pread64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t ksys_pread64(unsigned int fd, char *buf, size_t count, loff_t pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812e5530)
Location: fs/read_write.c:652
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_pread
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_pread
  - fs/read_write.c:__ia32_sys_pread64
  - fs/read_write.c:__x64_sys_pread64
```
**Symbols:**

```
ffffffff812e5530-ffffffff812e55c1: ksys_pread64 (STB_GLOBAL)
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
