# Function: <code>do_sys_truncate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int do_sys_truncate(const char *pathname, loff_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81209a10)
Location: fs/open.c:124
Inline: False
Direct callers:
  - fs/open.c:SyS_truncate
  - fs/open.c:compat_SyS_truncate
```
**Symbols:**

```
ffffffff81209a10-ffffffff81209ab7: do_sys_truncate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int do_sys_truncate(const char *pathname, loff_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8122f830)
Location: fs/open.c:124
Inline: False
Direct callers:
  - fs/open.c:compat_SyS_truncate
  - fs/open.c:SyS_truncate
```
**Symbols:**

```
ffffffff8122f830-ffffffff8122f8e1: do_sys_truncate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int do_sys_truncate(const char *pathname, loff_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81241dd0)
Location: fs/open.c:135
Inline: False
Direct callers:
  - fs/open.c:compat_SyS_truncate
  - fs/open.c:SyS_truncate
```
**Symbols:**

```
ffffffff81241dd0-ffffffff81241e81: do_sys_truncate (STB_LOCAL)
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
In fs/open.c (ffffffff8124e078)
Location: fs/open.c:135
Inline: True
Inline callers:
  - fs/open.c:compat_SyS_truncate
  - fs/open.c:SyS_truncate
Direct callers:
  - fs/open.c:compat_SyS_truncate
  - fs/open.c:SyS_truncate
```
**Symbols:**

```
ffffffff8124d3f0-ffffffff8124d490: do_sys_truncate.part.12 (STB_LOCAL)
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
In fs/open.c (ffffffff8126fff8)
Location: fs/open.c:135
Inline: True
Inline callers:
  - fs/open.c:compat_SyS_truncate
  - fs/open.c:SyS_truncate
Direct callers:
  - fs/open.c:compat_SyS_truncate
  - fs/open.c:SyS_truncate
```
**Symbols:**

```
ffffffff8126f370-ffffffff8126f410: do_sys_truncate.part.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
long int do_sys_truncate(const char *pathname, loff_t length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/open.c (ffffffff81295810)
Location: fs/open.c:135
Inline: True
Inline callers:
  - fs/open.c:__x32_compat_sys_truncate
  - fs/open.c:__ia32_compat_sys_truncate
  - fs/open.c:__ia32_sys_truncate
  - fs/open.c:__x64_sys_truncate
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_truncate64
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_truncate64
  - fs/open.c:__x32_compat_sys_truncate
  - fs/open.c:__ia32_compat_sys_truncate
  - fs/open.c:__ia32_sys_truncate
  - fs/open.c:__x64_sys_truncate
```
**Symbols:**

```
ffffffff812956d0-ffffffff81295773: do_sys_truncate.part.18 (STB_LOCAL)
ffffffff81295ca0-ffffffff81295cbd: do_sys_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
long int do_sys_truncate(const char *pathname, loff_t length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/open.c (ffffffff812aa6a0)
Location: fs/open.c:124
Inline: True
Inline callers:
  - fs/open.c:__x32_compat_sys_truncate
  - fs/open.c:__ia32_compat_sys_truncate
  - fs/open.c:__ia32_sys_truncate
  - fs/open.c:__x64_sys_truncate
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_truncate64
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_truncate64
  - fs/open.c:__x32_compat_sys_truncate
  - fs/open.c:__ia32_compat_sys_truncate
  - fs/open.c:__ia32_sys_truncate
  - fs/open.c:__x64_sys_truncate
```
**Symbols:**

```
ffffffff812aa560-ffffffff812aa603: do_sys_truncate.part.16 (STB_LOCAL)
ffffffff812aaa90-ffffffff812aaaad: do_sys_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
long int do_sys_truncate(const char *pathname, loff_t length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/open.c (ffffffff812c6e6d)
Location: fs/open.c:125
Inline: True
Inline callers:
  - fs/open.c:__x32_compat_sys_truncate
  - fs/open.c:__ia32_compat_sys_truncate
  - fs/open.c:__ia32_sys_truncate
  - fs/open.c:__x64_sys_truncate
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_truncate64
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_truncate64
  - fs/open.c:__x32_compat_sys_truncate
  - fs/open.c:__ia32_compat_sys_truncate
  - fs/open.c:__ia32_sys_truncate
  - fs/open.c:__x64_sys_truncate
```
**Symbols:**

```
ffffffff812c6d30-ffffffff812c6dd3: do_sys_truncate.part.0 (STB_LOCAL)
ffffffff812c7270-ffffffff812c728d: do_sys_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
long int do_sys_truncate(const char *pathname, loff_t length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/open.c (ffffffff812d887d)
Location: fs/open.c:125
Inline: True
Inline callers:
  - fs/open.c:__x32_compat_sys_truncate
  - fs/open.c:__ia32_compat_sys_truncate
  - fs/open.c:__ia32_sys_truncate
  - fs/open.c:__x64_sys_truncate
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_truncate64
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_truncate64
  - fs/open.c:__x32_compat_sys_truncate
  - fs/open.c:__ia32_compat_sys_truncate
  - fs/open.c:__ia32_sys_truncate
  - fs/open.c:__x64_sys_truncate
```
**Symbols:**

```
ffffffff812d8740-ffffffff812d87e3: do_sys_truncate.part.0 (STB_LOCAL)
ffffffff812d8c80-ffffffff812d8c9d: do_sys_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
long int do_sys_truncate(const char *pathname, loff_t length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/open.c (ffffffff8130e90d)
Location: fs/open.c:122
Inline: True
Inline callers:
  - fs/open.c:__x32_compat_sys_truncate
  - fs/open.c:__ia32_compat_sys_truncate
  - fs/open.c:__ia32_sys_truncate
  - fs/open.c:__x64_sys_truncate
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_truncate64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_truncate64
  - fs/open.c:__x32_compat_sys_truncate
  - fs/open.c:__ia32_compat_sys_truncate
  - fs/open.c:__ia32_sys_truncate
  - fs/open.c:__x64_sys_truncate
```
**Symbols:**

```
ffffffff8130e7d0-ffffffff8130e873: do_sys_truncate.part.0 (STB_LOCAL)
ffffffff8130eac0-ffffffff8130eadd: do_sys_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
long int do_sys_truncate(const char *pathname, loff_t length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/open.c (ffffffff8131aabd)
Location: fs/open.c:122
Inline: True
Inline callers:
  - fs/open.c:__x32_compat_sys_truncate
  - fs/open.c:__ia32_compat_sys_truncate
  - fs/open.c:__ia32_sys_truncate
  - fs/open.c:__x64_sys_truncate
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_truncate64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_truncate64
  - fs/open.c:__x32_compat_sys_truncate
  - fs/open.c:__ia32_compat_sys_truncate
  - fs/open.c:__ia32_sys_truncate
  - fs/open.c:__x64_sys_truncate
```
**Symbols:**

```
ffffffff8131a980-ffffffff8131aa23: do_sys_truncate.part.0 (STB_LOCAL)
ffffffff8131ad90-ffffffff8131adad: do_sys_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
long int do_sys_truncate(const char *pathname, loff_t length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/open.c (ffffffff81320f0d)
Location: fs/open.c:123
Inline: True
Inline callers:
  - fs/open.c:__x32_compat_sys_truncate
  - fs/open.c:__ia32_compat_sys_truncate
  - fs/open.c:__ia32_sys_truncate
  - fs/open.c:__x64_sys_truncate
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_truncate64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_truncate64
  - fs/open.c:__x32_compat_sys_truncate
  - fs/open.c:__ia32_compat_sys_truncate
  - fs/open.c:__ia32_sys_truncate
  - fs/open.c:__x64_sys_truncate
```
**Symbols:**

```
ffffffff81320dd0-ffffffff81320e73: do_sys_truncate.part.0 (STB_LOCAL)
ffffffff81320f30-ffffffff81320f4d: do_sys_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
long int do_sys_truncate(const char *pathname, loff_t length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/open.c (ffffffff8136e11d)
Location: fs/open.c:122
Inline: True
Inline callers:
  - fs/open.c:__x64_compat_sys_truncate
  - fs/open.c:__ia32_compat_sys_truncate
  - fs/open.c:__ia32_sys_truncate
  - fs/open.c:__x64_sys_truncate
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_truncate64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_truncate64
  - fs/open.c:__x64_compat_sys_truncate
  - fs/open.c:__ia32_compat_sys_truncate
  - fs/open.c:__ia32_sys_truncate
  - fs/open.c:__x64_sys_truncate
```
**Symbols:**

```
ffffffff8136dfe0-ffffffff8136e083: do_sys_truncate.part.0 (STB_LOCAL)
ffffffff8136e410-ffffffff8136e42d: do_sys_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int do_sys_truncate(const char *pathname, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff813eca00)
Location: fs/open.c:122
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_truncate64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_truncate64
  - fs/open.c:__ia32_compat_sys_truncate
  - fs/open.c:__ia32_sys_truncate
  - fs/open.c:__x64_sys_truncate
```
**Symbols:**

```
ffffffff813eca00-ffffffff813ecae0: do_sys_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int do_sys_truncate(const char *pathname, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81474f50)
Location: fs/open.c:122
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_truncate64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_truncate64
  - fs/open.c:__ia32_compat_sys_truncate
  - fs/open.c:__ia32_sys_truncate
  - fs/open.c:__x64_sys_truncate
```
**Symbols:**

```
ffffffff81474f50-ffffffff81475030: do_sys_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int do_sys_truncate(const char *pathname, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814a98e0)
Location: fs/open.c:123
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_truncate64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_truncate64
  - fs/open.c:__ia32_compat_sys_truncate
  - fs/open.c:__ia32_sys_truncate
  - fs/open.c:__x64_sys_truncate
```
**Symbols:**

```
ffffffff814a98e0-ffffffff814a99c0: do_sys_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long int do_sys_truncate(const char *pathname, loff_t length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814da96b)
Location: fs/open.c:123
Inline: True
Inline callers:
  - fs/open.c:__x64_sys_truncate
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_truncate64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_truncate64
  - fs/open.c:__ia32_compat_sys_truncate
  - fs/open.c:__ia32_sys_truncate
```
**Symbols:**

```
ffffffff814daa40-ffffffff814dab23: do_sys_truncate (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
long int do_sys_truncate(const char *pathname, loff_t length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/open.c (ffff80001037da90)
Location: fs/open.c:125
Inline: True
Inline callers:
  - fs/open.c:__arm64_compat_sys_truncate
  - fs/open.c:__arm64_sys_truncate
Direct callers:
  - arch/arm64/kernel/sys32.c:__arm64_compat_sys_aarch32_truncate64
  - fs/open.c:__arm64_compat_sys_truncate
  - fs/open.c:__arm64_sys_truncate
```
**Symbols:**

```
ffff80001037d960-ffff80001037da34: do_sys_truncate.part.0 (STB_LOCAL)
ffff80001037dff0-ffff80001037e030: do_sys_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
long int do_sys_truncate(const char *pathname, loff_t length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/open.c (c0568ba4)
Location: fs/open.c:125
Inline: True
Inline callers:
  - fs/open.c:__se_sys_truncate64
  - fs/open.c:__se_sys_truncate
Direct callers:
  - fs/open.c:__se_sys_truncate64
  - fs/open.c:__se_sys_truncate
```
**Symbols:**

```
c0568494-c0568558: do_sys_truncate.part.0 (STB_LOCAL)
c0568914-c056894c: do_sys_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
long int do_sys_truncate(const char *pathname, loff_t length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/open.c (c000000000473460)
Location: fs/open.c:125
Inline: True
Inline callers:
  - fs/open.c:__se_compat_sys_truncate
  - fs/open.c:__se_sys_truncate
Direct callers:
  - arch/powerpc/kernel/sys_ppc32.c:compat_sys_truncate64
  - fs/open.c:__se_compat_sys_truncate
  - fs/open.c:__se_sys_truncate
```
**Symbols:**

```
c000000000473310-c00000000047341c: do_sys_truncate.part.0 (STB_LOCAL)
c0000000004739e0-c000000000473a04: do_sys_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
long int do_sys_truncate(const char *pathname, loff_t length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/open.c (ffffffe000253d9e)
Location: fs/open.c:125
Inline: True
Inline callers:
  - fs/open.c:__se_sys_truncate
Direct callers:
  - fs/open.c:__se_sys_truncate
```
**Symbols:**

```
ffffffe000253432-ffffffe0002534be: do_sys_truncate.part.0 (STB_LOCAL)
ffffffe000253d4a-ffffffe000253d84: do_sys_truncate (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
long int do_sys_truncate(const char *pathname, loff_t length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/open.c (ffffffff812d0e5d)
Location: fs/open.c:125
Inline: True
Inline callers:
  - fs/open.c:__x32_compat_sys_truncate
  - fs/open.c:__ia32_compat_sys_truncate
  - fs/open.c:__ia32_sys_truncate
  - fs/open.c:__x64_sys_truncate
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_truncate64
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_truncate64
  - fs/open.c:__x32_compat_sys_truncate
  - fs/open.c:__ia32_compat_sys_truncate
  - fs/open.c:__ia32_sys_truncate
  - fs/open.c:__x64_sys_truncate
```
**Symbols:**

```
ffffffff812d0d20-ffffffff812d0dc3: do_sys_truncate.part.0 (STB_LOCAL)
ffffffff812d1260-ffffffff812d127d: do_sys_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
long int do_sys_truncate(const char *pathname, loff_t length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/open.c (ffffffff812c1add)
Location: fs/open.c:125
Inline: True
Inline callers:
  - fs/open.c:__x32_compat_sys_truncate
  - fs/open.c:__ia32_compat_sys_truncate
  - fs/open.c:__ia32_sys_truncate
  - fs/open.c:__x64_sys_truncate
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_truncate64
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_truncate64
  - fs/open.c:__x32_compat_sys_truncate
  - fs/open.c:__ia32_compat_sys_truncate
  - fs/open.c:__ia32_sys_truncate
  - fs/open.c:__x64_sys_truncate
```
**Symbols:**

```
ffffffff812c19a0-ffffffff812c1a43: do_sys_truncate.part.0 (STB_LOCAL)
ffffffff812c1ee0-ffffffff812c1efd: do_sys_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
long int do_sys_truncate(const char *pathname, loff_t length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/open.c (ffffffff812cec6d)
Location: fs/open.c:125
Inline: True
Inline callers:
  - fs/open.c:__x32_compat_sys_truncate
  - fs/open.c:__ia32_compat_sys_truncate
  - fs/open.c:__ia32_sys_truncate
  - fs/open.c:__x64_sys_truncate
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_truncate64
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_truncate64
  - fs/open.c:__x32_compat_sys_truncate
  - fs/open.c:__ia32_compat_sys_truncate
  - fs/open.c:__ia32_sys_truncate
  - fs/open.c:__x64_sys_truncate
```
**Symbols:**

```
ffffffff812ceb30-ffffffff812cebd3: do_sys_truncate.part.0 (STB_LOCAL)
ffffffff812cf070-ffffffff812cf08d: do_sys_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
long int do_sys_truncate(const char *pathname, loff_t length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/open.c (ffffffff812dfa7d)
Location: fs/open.c:125
Inline: True
Inline callers:
  - fs/open.c:__x32_compat_sys_truncate
  - fs/open.c:__ia32_compat_sys_truncate
  - fs/open.c:__ia32_sys_truncate
  - fs/open.c:__x64_sys_truncate
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_truncate64
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_truncate64
  - fs/open.c:__x32_compat_sys_truncate
  - fs/open.c:__ia32_compat_sys_truncate
  - fs/open.c:__ia32_sys_truncate
  - fs/open.c:__x64_sys_truncate
```
**Symbols:**

```
ffffffff812df940-ffffffff812df9e3: do_sys_truncate.part.0 (STB_LOCAL)
ffffffff812dfe80-ffffffff812dfe9d: do_sys_truncate (STB_GLOBAL)
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
