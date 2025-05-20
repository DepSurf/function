# Function: <code>ksys_fallocate</code>

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
int ksys_fallocate(int fd, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81295ef0)
Location: fs/open.c:340
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fallocate
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fallocate
  - fs/open.c:__ia32_sys_fallocate
  - fs/open.c:__x64_sys_fallocate
```
**Symbols:**

```
ffffffff81295ef0-ffffffff81295f69: ksys_fallocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ksys_fallocate(int fd, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812aace0)
Location: fs/open.c:329
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fallocate
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fallocate
  - fs/open.c:__ia32_sys_fallocate
  - fs/open.c:__x64_sys_fallocate
```
**Symbols:**

```
ffffffff812aace0-ffffffff812aad59: ksys_fallocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ksys_fallocate(int fd, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812c74d0)
Location: fs/open.c:330
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fallocate
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fallocate
  - fs/open.c:__ia32_sys_fallocate
  - fs/open.c:__x64_sys_fallocate
```
**Symbols:**

```
ffffffff812c74d0-ffffffff812c7549: ksys_fallocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ksys_fallocate(int fd, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812d8ee0)
Location: fs/open.c:330
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fallocate
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fallocate
  - fs/open.c:__ia32_sys_fallocate
  - fs/open.c:__x64_sys_fallocate
```
**Symbols:**

```
ffffffff812d8ee0-ffffffff812d8f59: ksys_fallocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int ksys_fallocate(int fd, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8130e5be)
Location: fs/open.c:327
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fallocate
  - fs/open.c:__x64_sys_fallocate
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_fallocate
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_fallocate
```
**Symbols:**

```
ffffffff8130ed20-ffffffff8130ed99: ksys_fallocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int ksys_fallocate(int fd, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8131a76e)
Location: fs/open.c:327
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fallocate
  - fs/open.c:__x64_sys_fallocate
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_fallocate
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_fallocate
```
**Symbols:**

```
ffffffff8131b060-ffffffff8131b0d9: ksys_fallocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int ksys_fallocate(int fd, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8132085e)
Location: fs/open.c:328
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fallocate
  - fs/open.c:__x64_sys_fallocate
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_fallocate
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_fallocate
```
**Symbols:**

```
ffffffff81321170-ffffffff813211e9: ksys_fallocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int ksys_fallocate(int fd, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8136de1e)
Location: fs/open.c:325
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fallocate
  - fs/open.c:__x64_sys_fallocate
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_fallocate
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_fallocate
```
**Symbols:**

```
ffffffff8136e650-ffffffff8136e6c9: ksys_fallocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int ksys_fallocate(int fd, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff813ec40e)
Location: fs/open.c:340
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fallocate
  - fs/open.c:__x64_sys_fallocate
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_fallocate
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_fallocate
```
**Symbols:**

```
ffffffff813ecdb0-ffffffff813ece45: ksys_fallocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int ksys_fallocate(int fd, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814748fe)
Location: fs/open.c:340
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fallocate
  - fs/open.c:__x64_sys_fallocate
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_fallocate
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_fallocate
```
**Symbols:**

```
ffffffff81475380-ffffffff81475415: ksys_fallocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int ksys_fallocate(int fd, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814a92de)
Location: fs/open.c:341
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fallocate
  - fs/open.c:__x64_sys_fallocate
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_fallocate
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_fallocate
```
**Symbols:**

```
ffffffff814a9d10-ffffffff814a9da5: ksys_fallocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int ksys_fallocate(int fd, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814da32e)
Location: fs/open.c:345
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fallocate
  - fs/open.c:__x64_sys_fallocate
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_fallocate
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_fallocate
```
**Symbols:**

```
ffffffff814dae50-ffffffff814daee5: ksys_fallocate (STB_GLOBAL)
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
int ksys_fallocate(int fd, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffff80001037e260)
Location: fs/open.c:330
Inline: False
Direct callers:
  - arch/arm64/kernel/sys32.c:__arm64_compat_sys_aarch32_fallocate
  - fs/open.c:__arm64_sys_fallocate
```
**Symbols:**

```
ffff80001037e260-ffff80001037e2fc: ksys_fallocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ksys_fallocate(int fd, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (c0568bf4)
Location: fs/open.c:330
Inline: False
Direct callers:
  - fs/open.c:__se_sys_fallocate
```
**Symbols:**

```
c0568bf4-c0568c78: ksys_fallocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ksys_fallocate(int fd, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (c000000000473c60)
Location: fs/open.c:330
Inline: False
Direct callers:
  - arch/powerpc/kernel/sys_ppc32.c:compat_sys_fallocate
  - fs/open.c:__se_sys_fallocate
```
**Symbols:**

```
c000000000473c60-c000000000473d48: ksys_fallocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ksys_fallocate(int fd, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffe000253f54)
Location: fs/open.c:330
Inline: False
Direct callers:
  - fs/open.c:__se_sys_fallocate
```
**Symbols:**

```
ffffffe000253f54-ffffffe000253fc8: ksys_fallocate (STB_GLOBAL)
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
int ksys_fallocate(int fd, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812d14c0)
Location: fs/open.c:330
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fallocate
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fallocate
  - fs/open.c:__ia32_sys_fallocate
  - fs/open.c:__x64_sys_fallocate
```
**Symbols:**

```
ffffffff812d14c0-ffffffff812d1539: ksys_fallocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ksys_fallocate(int fd, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812c2140)
Location: fs/open.c:330
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fallocate
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fallocate
  - fs/open.c:__ia32_sys_fallocate
  - fs/open.c:__x64_sys_fallocate
```
**Symbols:**

```
ffffffff812c2140-ffffffff812c21b9: ksys_fallocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ksys_fallocate(int fd, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812cf2d0)
Location: fs/open.c:330
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fallocate
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fallocate
  - fs/open.c:__ia32_sys_fallocate
  - fs/open.c:__x64_sys_fallocate
```
**Symbols:**

```
ffffffff812cf2d0-ffffffff812cf349: ksys_fallocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ksys_fallocate(int fd, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812e00e0)
Location: fs/open.c:330
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fallocate
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fallocate
  - fs/open.c:__ia32_sys_fallocate
  - fs/open.c:__x64_sys_fallocate
```
**Symbols:**

```
ffffffff812e00e0-ffffffff812e0159: ksys_fallocate (STB_GLOBAL)
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
