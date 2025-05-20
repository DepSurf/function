# Function: <code>ksys_mmap_pgoff</code>

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
long unsigned int ksys_mmap_pgoff(long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, long unsigned int fd, long unsigned int pgoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81235860)
Location: mm/mmap.c:1543
Inline: False
Direct callers:
  - arch/x86/kernel/sys_x86_64.c:__ia32_sys_mmap
  - arch/x86/kernel/sys_x86_64.c:__x64_sys_mmap
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_mmap
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_mmap
  - mm/mmap.c:__ia32_sys_mmap_pgoff
  - mm/mmap.c:__x64_sys_mmap_pgoff
```
**Symbols:**

```
ffffffff81235860-ffffffff81235aca: ksys_mmap_pgoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int ksys_mmap_pgoff(long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, long unsigned int fd, long unsigned int pgoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81249060)
Location: mm/mmap.c:1567
Inline: False
Direct callers:
  - arch/x86/kernel/sys_x86_64.c:__ia32_sys_mmap
  - arch/x86/kernel/sys_x86_64.c:__x64_sys_mmap
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_mmap
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_mmap
  - mm/mmap.c:__ia32_sys_mmap_pgoff
  - mm/mmap.c:__x64_sys_mmap_pgoff
```
**Symbols:**

```
ffffffff81249060-ffffffff812492ca: ksys_mmap_pgoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int ksys_mmap_pgoff(long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, long unsigned int fd, long unsigned int pgoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8125b340)
Location: mm/mmap.c:1569
Inline: False
Direct callers:
  - arch/x86/kernel/sys_x86_64.c:__ia32_sys_mmap
  - arch/x86/kernel/sys_x86_64.c:__x64_sys_mmap
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_mmap
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_mmap
  - mm/mmap.c:__ia32_sys_mmap_pgoff
  - mm/mmap.c:__x64_sys_mmap_pgoff
```
**Symbols:**

```
ffffffff8125b340-ffffffff8125b5df: ksys_mmap_pgoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int ksys_mmap_pgoff(long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, long unsigned int fd, long unsigned int pgoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81269a20)
Location: mm/mmap.c:1577
Inline: False
Direct callers:
  - arch/x86/kernel/sys_x86_64.c:__ia32_sys_mmap
  - arch/x86/kernel/sys_x86_64.c:__x64_sys_mmap
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_mmap
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_mmap
  - mm/mmap.c:__ia32_sys_mmap_pgoff
  - mm/mmap.c:__x64_sys_mmap_pgoff
```
**Symbols:**

```
ffffffff81269a20-ffffffff81269cbf: ksys_mmap_pgoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int ksys_mmap_pgoff(long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, long unsigned int fd, long unsigned int pgoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8129a250)
Location: mm/mmap.c:1553
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__x32_compat_sys_ia32_mmap
  - arch/x86/kernel/sys_ia32.c:__ia32_compat_sys_ia32_mmap
  - arch/x86/kernel/sys_x86_64.c:__ia32_sys_mmap
  - arch/x86/kernel/sys_x86_64.c:__x64_sys_mmap
  - mm/mmap.c:__ia32_sys_mmap_pgoff
  - mm/mmap.c:__x64_sys_mmap_pgoff
```
**Symbols:**

```
ffffffff8129a250-ffffffff8129a4ef: ksys_mmap_pgoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int ksys_mmap_pgoff(long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, long unsigned int fd, long unsigned int pgoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812a5460)
Location: mm/mmap.c:1591
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__x32_compat_sys_ia32_mmap
  - arch/x86/kernel/sys_ia32.c:__ia32_compat_sys_ia32_mmap
  - arch/x86/kernel/sys_x86_64.c:__ia32_sys_mmap
  - arch/x86/kernel/sys_x86_64.c:__x64_sys_mmap
  - mm/mmap.c:__ia32_sys_mmap_pgoff
  - mm/mmap.c:__x64_sys_mmap_pgoff
```
**Symbols:**

```
ffffffff812a5460-ffffffff812a56c8: ksys_mmap_pgoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int ksys_mmap_pgoff(long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, long unsigned int fd, long unsigned int pgoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812aac00)
Location: mm/mmap.c:1595
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__x32_compat_sys_ia32_mmap
  - arch/x86/kernel/sys_ia32.c:__ia32_compat_sys_ia32_mmap
  - arch/x86/kernel/sys_x86_64.c:__ia32_sys_mmap
  - arch/x86/kernel/sys_x86_64.c:__x64_sys_mmap
  - mm/mmap.c:__ia32_sys_mmap_pgoff
  - mm/mmap.c:__x64_sys_mmap_pgoff
```
**Symbols:**

```
ffffffff812aac00-ffffffff812aae51: ksys_mmap_pgoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long unsigned int ksys_mmap_pgoff(long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, long unsigned int fd, long unsigned int pgoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mmap.c (0)
Location: mm/mmap.c:1583
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__x64_compat_sys_ia32_mmap
  - arch/x86/kernel/sys_ia32.c:__ia32_compat_sys_ia32_mmap
  - arch/x86/kernel/sys_x86_64.c:__ia32_sys_mmap
  - arch/x86/kernel/sys_x86_64.c:__x64_sys_mmap
  - mm/mmap.c:__ia32_sys_mmap_pgoff
  - mm/mmap.c:__x64_sys_mmap_pgoff
```
**Symbols:**

```
ffffffff81cbc766-ffffffff81cbc856: ksys_mmap_pgoff.cold (STB_LOCAL)
ffffffff812ec280-ffffffff812ec52d: ksys_mmap_pgoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long unsigned int ksys_mmap_pgoff(long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, long unsigned int fd, long unsigned int pgoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mmap.c (0)
Location: mm/mmap.c:1595
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_compat_sys_ia32_mmap
  - arch/x86/kernel/sys_x86_64.c:__ia32_sys_mmap
  - arch/x86/kernel/sys_x86_64.c:__x64_sys_mmap
  - mm/mmap.c:__ia32_sys_mmap_pgoff
  - mm/mmap.c:__x64_sys_mmap_pgoff
```
**Symbols:**

```
ffffffff81e6e367-ffffffff81e6e446: ksys_mmap_pgoff.cold (STB_LOCAL)
ffffffff8134f1a0-ffffffff8134f3f3: ksys_mmap_pgoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
long unsigned int ksys_mmap_pgoff(long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, long unsigned int fd, long unsigned int pgoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mmap.c (0)
Location: mm/mmap.c:1419
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_compat_sys_ia32_mmap
  - arch/x86/kernel/sys_x86_64.c:__ia32_sys_mmap
  - arch/x86/kernel/sys_x86_64.c:__x64_sys_mmap
  - mm/mmap.c:__ia32_sys_mmap_pgoff
  - mm/mmap.c:__x64_sys_mmap_pgoff
```
**Symbols:**

```
ffffffff820642a3-ffffffff820643a0: ksys_mmap_pgoff.cold (STB_LOCAL)
ffffffff813c8790-ffffffff813c89eb: ksys_mmap_pgoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long unsigned int ksys_mmap_pgoff(long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, long unsigned int fd, long unsigned int pgoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mmap.c (0)
Location: mm/mmap.c:1368
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_compat_sys_ia32_mmap
  - arch/x86/kernel/sys_x86_64.c:__ia32_sys_mmap
  - arch/x86/kernel/sys_x86_64.c:__x64_sys_mmap
  - mm/mmap.c:__ia32_sys_mmap_pgoff
  - mm/mmap.c:__x64_sys_mmap_pgoff
```
**Symbols:**

```
ffffffff820e397e-ffffffff820e3a7e: ksys_mmap_pgoff.cold (STB_LOCAL)
ffffffff813fc990-ffffffff813fcbf1: ksys_mmap_pgoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long unsigned int ksys_mmap_pgoff(long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, long unsigned int fd, long unsigned int pgoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mmap.c (0)
Location: mm/mmap.c:1395
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_compat_sys_ia32_mmap
  - arch/x86/kernel/sys_x86_64.c:__ia32_sys_mmap
  - arch/x86/kernel/sys_x86_64.c:__x64_sys_mmap
  - mm/mmap.c:__ia32_sys_mmap_pgoff
  - mm/mmap.c:__x64_sys_mmap_pgoff
```
**Symbols:**

```
ffffffff821c0527-ffffffff821c0627: ksys_mmap_pgoff.cold (STB_LOCAL)
ffffffff81429360-ffffffff814295c1: ksys_mmap_pgoff (STB_GLOBAL)
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
long unsigned int ksys_mmap_pgoff(long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, long unsigned int fd, long unsigned int pgoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffff800010300e98)
Location: mm/mmap.c:1577
Inline: False
Direct callers:
  - arch/arm64/kernel/sys.c:__arm64_sys_mmap
  - arch/arm64/kernel/sys32.c:__arm64_compat_sys_aarch32_mmap2
  - mm/mmap.c:__arm64_sys_mmap_pgoff
```
**Symbols:**

```
ffff800010300e98-ffff8000103010cc: ksys_mmap_pgoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int ksys_mmap_pgoff(long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, long unsigned int fd, long unsigned int pgoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c051f9cc)
Location: mm/mmap.c:1577
Inline: False
Direct callers:
  - mm/mmap.c:__se_sys_old_mmap
  - mm/mmap.c:__se_sys_mmap_pgoff
```
**Symbols:**

```
c051f9cc-c051fadc: ksys_mmap_pgoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int ksys_mmap_pgoff(long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, long unsigned int fd, long unsigned int pgoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c0000000003cd180)
Location: mm/mmap.c:1577
Inline: False
Direct callers:
  - arch/powerpc/kernel/syscalls.c:__se_sys_mmap
  - arch/powerpc/kernel/syscalls.c:__se_sys_mmap2
  - mm/mmap.c:__se_sys_mmap_pgoff
```
**Symbols:**

```
c0000000003cd180-c0000000003cd460: ksys_mmap_pgoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int ksys_mmap_pgoff(long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, long unsigned int fd, long unsigned int pgoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffe00020e3fe)
Location: mm/mmap.c:1577
Inline: False
Direct callers:
  - arch/riscv/kernel/sys_riscv.c:__se_sys_mmap
  - mm/mmap.c:__se_sys_mmap_pgoff
```
**Symbols:**

```
ffffffe00020e3fe-ffffffe00020e5b8: ksys_mmap_pgoff (STB_GLOBAL)
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
long unsigned int ksys_mmap_pgoff(long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, long unsigned int fd, long unsigned int pgoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81262070)
Location: mm/mmap.c:1577
Inline: False
Direct callers:
  - arch/x86/kernel/sys_x86_64.c:__ia32_sys_mmap
  - arch/x86/kernel/sys_x86_64.c:__x64_sys_mmap
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_mmap
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_mmap
  - mm/mmap.c:__ia32_sys_mmap_pgoff
  - mm/mmap.c:__x64_sys_mmap_pgoff
```
**Symbols:**

```
ffffffff81262070-ffffffff8126230f: ksys_mmap_pgoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int ksys_mmap_pgoff(long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, long unsigned int fd, long unsigned int pgoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81254490)
Location: mm/mmap.c:1577
Inline: False
Direct callers:
  - arch/x86/kernel/sys_x86_64.c:__ia32_sys_mmap
  - arch/x86/kernel/sys_x86_64.c:__x64_sys_mmap
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_mmap
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_mmap
  - mm/mmap.c:__ia32_sys_mmap_pgoff
  - mm/mmap.c:__x64_sys_mmap_pgoff
```
**Symbols:**

```
ffffffff81254490-ffffffff8125472f: ksys_mmap_pgoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int ksys_mmap_pgoff(long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, long unsigned int fd, long unsigned int pgoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8125fe10)
Location: mm/mmap.c:1577
Inline: False
Direct callers:
  - arch/x86/kernel/sys_x86_64.c:__ia32_sys_mmap
  - arch/x86/kernel/sys_x86_64.c:__x64_sys_mmap
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_mmap
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_mmap
  - mm/mmap.c:__ia32_sys_mmap_pgoff
  - mm/mmap.c:__x64_sys_mmap_pgoff
```
**Symbols:**

```
ffffffff8125fe10-ffffffff812600af: ksys_mmap_pgoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int ksys_mmap_pgoff(long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, long unsigned int fd, long unsigned int pgoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8126f7e0)
Location: mm/mmap.c:1577
Inline: False
Direct callers:
  - arch/x86/kernel/sys_x86_64.c:__ia32_sys_mmap
  - arch/x86/kernel/sys_x86_64.c:__x64_sys_mmap
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_mmap
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_mmap
  - mm/mmap.c:__ia32_sys_mmap_pgoff
  - mm/mmap.c:__x64_sys_mmap_pgoff
```
**Symbols:**

```
ffffffff8126f7e0-ffffffff8126fa7f: ksys_mmap_pgoff (STB_GLOBAL)
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
