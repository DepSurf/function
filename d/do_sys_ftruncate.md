# Function: <code>do_sys_ftruncate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/open.c (ffffffff8120a3d0)
Location: fs/open.c:158
Inline: True
Direct callers:
  - fs/open.c:SyS_ftruncate
  - fs/open.c:compat_SyS_ftruncate
```
**Symbols:**

```
ffffffff8120a3d0-ffffffff8120a537: do_sys_ftruncate.constprop.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/open.c (ffffffff81230090)
Location: fs/open.c:158
Inline: True
Direct callers:
  - fs/open.c:compat_SyS_ftruncate
  - fs/open.c:SyS_ftruncate
```
**Symbols:**

```
ffffffff81230090-ffffffff81230201: do_sys_ftruncate.constprop.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/open.c (ffffffff81242640)
Location: fs/open.c:169
Inline: True
Direct callers:
  - fs/open.c:compat_SyS_ftruncate
  - fs/open.c:SyS_ftruncate
```
**Symbols:**

```
ffffffff81242640-ffffffff812427b1: do_sys_ftruncate.constprop.15 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/open.c (ffffffff8124dd30)
Location: fs/open.c:169
Inline: True
Direct callers:
  - fs/open.c:compat_SyS_ftruncate
  - fs/open.c:SyS_ftruncate
```
**Symbols:**

```
ffffffff8124dd30-ffffffff8124dea6: do_sys_ftruncate.constprop.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/open.c (ffffffff8126fa20)
Location: fs/open.c:169
Inline: True
Direct callers:
  - fs/open.c:compat_SyS_ftruncate
  - fs/open.c:SyS_ftruncate
```
**Symbols:**

```
ffffffff8126fa20-ffffffff8126fb96: do_sys_ftruncate.constprop.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int do_sys_ftruncate(unsigned int fd, loff_t length, int small);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81295cc0)
Location: fs/open.c:169
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_ftruncate64
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_ftruncate64
  - fs/open.c:__x32_compat_sys_ftruncate
  - fs/open.c:__ia32_sys_ftruncate
  - fs/open.c:__x64_sys_ftruncate
```
**Symbols:**

```
ffffffff81295cc0-ffffffff81295e7c: do_sys_ftruncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int do_sys_ftruncate(unsigned int fd, loff_t length, int small);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812aaab0)
Location: fs/open.c:158
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_ftruncate64
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_ftruncate64
  - fs/open.c:__x32_compat_sys_ftruncate
  - fs/open.c:__ia32_sys_ftruncate
  - fs/open.c:__x64_sys_ftruncate
```
**Symbols:**

```
ffffffff812aaab0-ffffffff812aac6c: do_sys_ftruncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int do_sys_ftruncate(unsigned int fd, loff_t length, int small);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812c7290)
Location: fs/open.c:159
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_ftruncate64
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_ftruncate64
  - fs/open.c:__x32_compat_sys_ftruncate
  - fs/open.c:__ia32_compat_sys_ftruncate
  - fs/open.c:__ia32_sys_ftruncate
  - fs/open.c:__x64_sys_ftruncate
```
**Symbols:**

```
ffffffff812c7290-ffffffff812c744c: do_sys_ftruncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int do_sys_ftruncate(unsigned int fd, loff_t length, int small);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812d8ca0)
Location: fs/open.c:159
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_ftruncate64
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_ftruncate64
  - fs/open.c:__x32_compat_sys_ftruncate
  - fs/open.c:__ia32_compat_sys_ftruncate
  - fs/open.c:__ia32_sys_ftruncate
  - fs/open.c:__x64_sys_ftruncate
```
**Symbols:**

```
ffffffff812d8ca0-ffffffff812d8e5c: do_sys_ftruncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int do_sys_ftruncate(unsigned int fd, loff_t length, int small);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8130eae0)
Location: fs/open.c:156
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_ftruncate64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_ftruncate64
  - fs/open.c:__x32_compat_sys_ftruncate
  - fs/open.c:__x64_sys_ftruncate
```
**Symbols:**

```
ffffffff8130eae0-ffffffff8130ec9c: do_sys_ftruncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int do_sys_ftruncate(unsigned int fd, loff_t length, int small);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8131adb0)
Location: fs/open.c:156
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_ftruncate64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_ftruncate64
  - fs/open.c:__x32_compat_sys_ftruncate
  - fs/open.c:__x64_sys_ftruncate
```
**Symbols:**

```
ffffffff8131adb0-ffffffff8131afd7: do_sys_ftruncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int do_sys_ftruncate(unsigned int fd, loff_t length, int small);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81320f50)
Location: fs/open.c:157
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_ftruncate64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_ftruncate64
  - fs/open.c:__x32_compat_sys_ftruncate
  - fs/open.c:__x64_sys_ftruncate
```
**Symbols:**

```
ffffffff81320f50-ffffffff813210e6: do_sys_ftruncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int do_sys_ftruncate(unsigned int fd, loff_t length, int small);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8136e430)
Location: fs/open.c:156
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_ftruncate64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_ftruncate64
  - fs/open.c:__x64_compat_sys_ftruncate
  - fs/open.c:__x64_sys_ftruncate
```
**Symbols:**

```
ffffffff8136e430-ffffffff8136e5c6: do_sys_ftruncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int do_sys_ftruncate(unsigned int fd, loff_t length, int small);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff813ecb40)
Location: fs/open.c:156
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_ftruncate64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_ftruncate64
  - fs/open.c:__x64_sys_ftruncate
```
**Symbols:**

```
ffffffff813ecb40-ffffffff813ecd18: do_sys_ftruncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int do_sys_ftruncate(unsigned int fd, loff_t length, int small);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814750d0)
Location: fs/open.c:156
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_ftruncate64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_ftruncate64
  - fs/open.c:__x64_sys_ftruncate
```
**Symbols:**

```
ffffffff814750d0-ffffffff814752a8: do_sys_ftruncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int do_sys_ftruncate(unsigned int fd, loff_t length, int small);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814a9a60)
Location: fs/open.c:157
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_ftruncate64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_ftruncate64
  - fs/open.c:__x64_sys_ftruncate
```
**Symbols:**

```
ffffffff814a9a60-ffffffff814a9c40: do_sys_ftruncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int do_sys_ftruncate(unsigned int fd, loff_t length, int small);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814daba0)
Location: fs/open.c:157
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_ftruncate64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_ftruncate64
  - fs/open.c:__x64_sys_ftruncate
```
**Symbols:**

```
ffffffff814daba0-ffffffff814dad80: do_sys_ftruncate (STB_GLOBAL)
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
long int do_sys_ftruncate(unsigned int fd, loff_t length, int small);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffff80001037e030)
Location: fs/open.c:159
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - arch/arm64/kernel/sys32.c:__arm64_compat_sys_aarch32_ftruncate64
  - fs/open.c:__arm64_compat_sys_ftruncate
  - fs/open.c:__arm64_sys_ftruncate
```
**Symbols:**

```
ffff80001037e030-ffff80001037e1ec: do_sys_ftruncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int do_sys_ftruncate(unsigned int fd, loff_t length, int small);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (c0568980)
Location: fs/open.c:159
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - fs/open.c:__se_sys_ftruncate64
  - fs/open.c:__se_sys_ftruncate
```
**Symbols:**

```
c0568980-c0568b5c: do_sys_ftruncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int do_sys_ftruncate(unsigned int fd, loff_t length, int small);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (c000000000473a10)
Location: fs/open.c:159
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - arch/powerpc/kernel/sys_ppc32.c:compat_sys_ftruncate64
  - fs/open.c:__se_compat_sys_ftruncate
  - fs/open.c:__se_sys_ftruncate
```
**Symbols:**

```
c000000000473a10-c000000000473c1c: do_sys_ftruncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int do_sys_ftruncate(unsigned int fd, loff_t length, int small);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffe000253dbe)
Location: fs/open.c:159
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - fs/open.c:__se_sys_ftruncate
```
**Symbols:**

```
ffffffe000253dbe-ffffffe000253f1e: do_sys_ftruncate (STB_GLOBAL)
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
long int do_sys_ftruncate(unsigned int fd, loff_t length, int small);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812d1280)
Location: fs/open.c:159
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_ftruncate64
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_ftruncate64
  - fs/open.c:__x32_compat_sys_ftruncate
  - fs/open.c:__ia32_compat_sys_ftruncate
  - fs/open.c:__ia32_sys_ftruncate
  - fs/open.c:__x64_sys_ftruncate
```
**Symbols:**

```
ffffffff812d1280-ffffffff812d143c: do_sys_ftruncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int do_sys_ftruncate(unsigned int fd, loff_t length, int small);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812c1f00)
Location: fs/open.c:159
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_ftruncate64
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_ftruncate64
  - fs/open.c:__x32_compat_sys_ftruncate
  - fs/open.c:__ia32_compat_sys_ftruncate
  - fs/open.c:__ia32_sys_ftruncate
  - fs/open.c:__x64_sys_ftruncate
```
**Symbols:**

```
ffffffff812c1f00-ffffffff812c20bc: do_sys_ftruncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int do_sys_ftruncate(unsigned int fd, loff_t length, int small);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812cf090)
Location: fs/open.c:159
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_ftruncate64
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_ftruncate64
  - fs/open.c:__x32_compat_sys_ftruncate
  - fs/open.c:__ia32_compat_sys_ftruncate
  - fs/open.c:__ia32_sys_ftruncate
  - fs/open.c:__x64_sys_ftruncate
```
**Symbols:**

```
ffffffff812cf090-ffffffff812cf24c: do_sys_ftruncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int do_sys_ftruncate(unsigned int fd, loff_t length, int small);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812dfea0)
Location: fs/open.c:159
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_ftruncate64
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_ftruncate64
  - fs/open.c:__x32_compat_sys_ftruncate
  - fs/open.c:__ia32_compat_sys_ftruncate
  - fs/open.c:__ia32_sys_ftruncate
  - fs/open.c:__x64_sys_ftruncate
```
**Symbols:**

```
ffffffff812dfea0-ffffffff812e005c: do_sys_ftruncate (STB_GLOBAL)
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
