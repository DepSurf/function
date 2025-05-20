# Function: <code>ksys_fadvise64_64</code>

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
int ksys_fadvise64_64(int fd, loff_t offset, loff_t len, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (ffffffff812446e0)
Location: mm/fadvise.c:30
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fadvise64
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fadvise64
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fadvise64_64
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fadvise64_64
  - mm/fadvise.c:__ia32_sys_fadvise64
  - mm/fadvise.c:__x64_sys_fadvise64
  - mm/fadvise.c:__ia32_sys_fadvise64_64
  - mm/fadvise.c:__x64_sys_fadvise64_64
```
**Symbols:**

```
ffffffff812446e0-ffffffff81244987: ksys_fadvise64_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ksys_fadvise64_64(int fd, loff_t offset, loff_t len, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (ffffffff81206270)
Location: mm/fadvise.c:193
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fadvise64
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fadvise64
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fadvise64_64
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fadvise64_64
  - mm/fadvise.c:__ia32_sys_fadvise64
  - mm/fadvise.c:__x64_sys_fadvise64
  - mm/fadvise.c:__ia32_sys_fadvise64_64
  - mm/fadvise.c:__x64_sys_fadvise64_64
```
**Symbols:**

```
ffffffff81206270-ffffffff812062e9: ksys_fadvise64_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ksys_fadvise64_64(int fd, loff_t offset, loff_t len, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (ffffffff8121d5f0)
Location: mm/fadvise.c:193
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fadvise64
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fadvise64
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fadvise64_64
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fadvise64_64
  - mm/fadvise.c:__ia32_sys_fadvise64
  - mm/fadvise.c:__x64_sys_fadvise64
  - mm/fadvise.c:__ia32_sys_fadvise64_64
  - mm/fadvise.c:__x64_sys_fadvise64_64
```
**Symbols:**

```
ffffffff8121d5f0-ffffffff8121d669: ksys_fadvise64_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ksys_fadvise64_64(int fd, loff_t offset, loff_t len, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (ffffffff8122afd0)
Location: mm/fadvise.c:193
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fadvise64
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fadvise64
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fadvise64_64
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fadvise64_64
  - mm/fadvise.c:__ia32_sys_fadvise64
  - mm/fadvise.c:__x64_sys_fadvise64
  - mm/fadvise.c:__ia32_sys_fadvise64_64
  - mm/fadvise.c:__x64_sys_fadvise64_64
```
**Symbols:**

```
ffffffff8122afd0-ffffffff8122b049: ksys_fadvise64_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ksys_fadvise64_64(int fd, loff_t offset, loff_t len, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (ffffffff81257d90)
Location: mm/fadvise.c:191
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_fadvise64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_fadvise64
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_fadvise64_64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_fadvise64_64
```
**Symbols:**

```
ffffffff81257d90-ffffffff81257e20: ksys_fadvise64_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ksys_fadvise64_64(int fd, loff_t offset, loff_t len, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (ffffffff81262660)
Location: mm/fadvise.c:192
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_fadvise64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_fadvise64
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_fadvise64_64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_fadvise64_64
```
**Symbols:**

```
ffffffff81262660-ffffffff812626f0: ksys_fadvise64_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ksys_fadvise64_64(int fd, loff_t offset, loff_t len, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (ffffffff812670f0)
Location: mm/fadvise.c:192
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_fadvise64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_fadvise64
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_fadvise64_64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_fadvise64_64
```
**Symbols:**

```
ffffffff812670f0-ffffffff81267180: ksys_fadvise64_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ksys_fadvise64_64(int fd, loff_t offset, loff_t len, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (ffffffff812a3b30)
Location: mm/fadvise.c:192
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_fadvise64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_fadvise64
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_fadvise64_64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_fadvise64_64
```
**Symbols:**

```
ffffffff812a3b30-ffffffff812a3bc0: ksys_fadvise64_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ksys_fadvise64_64(int fd, loff_t offset, loff_t len, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (ffffffff812fba50)
Location: mm/fadvise.c:191
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_fadvise64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_fadvise64
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_fadvise64_64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_fadvise64_64
```
**Symbols:**

```
ffffffff812fba50-ffffffff812fbafc: ksys_fadvise64_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ksys_fadvise64_64(int fd, loff_t offset, loff_t len, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (ffffffff81365bd0)
Location: mm/fadvise.c:191
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_fadvise64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_fadvise64
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_fadvise64_64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_fadvise64_64
```
**Symbols:**

```
ffffffff81365bd0-ffffffff81365c7c: ksys_fadvise64_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ksys_fadvise64_64(int fd, loff_t offset, loff_t len, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (ffffffff813980b0)
Location: mm/fadvise.c:191
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_fadvise64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_fadvise64
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_fadvise64_64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_fadvise64_64
```
**Symbols:**

```
ffffffff813980b0-ffffffff8139815f: ksys_fadvise64_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ksys_fadvise64_64(int fd, loff_t offset, loff_t len, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (ffffffff813c1ee0)
Location: mm/fadvise.c:191
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_fadvise64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_fadvise64
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_fadvise64_64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_fadvise64_64
```
**Symbols:**

```
ffffffff813c1ee0-ffffffff813c1f8f: ksys_fadvise64_64 (STB_GLOBAL)
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
int ksys_fadvise64_64(int fd, loff_t offset, loff_t len, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (ffff8000102b92d8)
Location: mm/fadvise.c:193
Inline: False
Direct callers:
  - arch/arm64/kernel/sys32.c:__arm64_compat_sys_aarch32_fadvise64_64
  - mm/fadvise.c:__arm64_sys_fadvise64_64
```
**Symbols:**

```
ffff8000102b92d8-ffff8000102b9374: ksys_fadvise64_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ksys_fadvise64_64(int fd, loff_t offset, loff_t len, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (c04e5ac0)
Location: mm/fadvise.c:193
Inline: False
Direct callers:
  - arch/arm/kernel/sys_arm.c:sys_arm_fadvise64_64
  - mm/fadvise.c:__se_sys_fadvise64_64
```
**Symbols:**

```
c04e5ac0-c04e5b44: ksys_fadvise64_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ksys_fadvise64_64(int fd, loff_t offset, loff_t len, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (c000000000371600)
Location: mm/fadvise.c:193
Inline: False
Direct callers:
  - arch/powerpc/kernel/syscalls.c:ppc_fadvise64_64
  - arch/powerpc/kernel/sys_ppc32.c:ppc32_fadvise64
  - mm/fadvise.c:__se_sys_fadvise64
  - mm/fadvise.c:__se_sys_fadvise64_64
```
**Symbols:**

```
c000000000371600-c0000000003716dc: ksys_fadvise64_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ksys_fadvise64_64(int fd, loff_t offset, loff_t len, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (ffffffe0001dce9e)
Location: mm/fadvise.c:193
Inline: False
Direct callers:
  - mm/fadvise.c:__se_sys_fadvise64_64
```
**Symbols:**

```
ffffffe0001dce9e-ffffffe0001dcf12: ksys_fadvise64_64 (STB_GLOBAL)
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
int ksys_fadvise64_64(int fd, loff_t offset, loff_t len, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (ffffffff81223620)
Location: mm/fadvise.c:193
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fadvise64
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fadvise64
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fadvise64_64
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fadvise64_64
  - mm/fadvise.c:__ia32_sys_fadvise64
  - mm/fadvise.c:__x64_sys_fadvise64
  - mm/fadvise.c:__ia32_sys_fadvise64_64
  - mm/fadvise.c:__x64_sys_fadvise64_64
```
**Symbols:**

```
ffffffff81223620-ffffffff81223699: ksys_fadvise64_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ksys_fadvise64_64(int fd, loff_t offset, loff_t len, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (ffffffff812167d0)
Location: mm/fadvise.c:193
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fadvise64
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fadvise64
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fadvise64_64
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fadvise64_64
  - mm/fadvise.c:__ia32_sys_fadvise64
  - mm/fadvise.c:__x64_sys_fadvise64
  - mm/fadvise.c:__ia32_sys_fadvise64_64
  - mm/fadvise.c:__x64_sys_fadvise64_64
```
**Symbols:**

```
ffffffff812167d0-ffffffff81216849: ksys_fadvise64_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ksys_fadvise64_64(int fd, loff_t offset, loff_t len, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (ffffffff812213c0)
Location: mm/fadvise.c:193
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fadvise64
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fadvise64
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fadvise64_64
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fadvise64_64
  - mm/fadvise.c:__ia32_sys_fadvise64
  - mm/fadvise.c:__x64_sys_fadvise64
  - mm/fadvise.c:__ia32_sys_fadvise64_64
  - mm/fadvise.c:__x64_sys_fadvise64_64
```
**Symbols:**

```
ffffffff812213c0-ffffffff81221439: ksys_fadvise64_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ksys_fadvise64_64(int fd, loff_t offset, loff_t len, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (ffffffff81230580)
Location: mm/fadvise.c:193
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fadvise64
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fadvise64
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fadvise64_64
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fadvise64_64
  - mm/fadvise.c:__ia32_sys_fadvise64
  - mm/fadvise.c:__x64_sys_fadvise64
  - mm/fadvise.c:__ia32_sys_fadvise64_64
  - mm/fadvise.c:__x64_sys_fadvise64_64
```
**Symbols:**

```
ffffffff81230580-ffffffff812305f9: ksys_fadvise64_64 (STB_GLOBAL)
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
