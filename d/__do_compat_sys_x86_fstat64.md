# Function: <code>__do_compat_sys_x86_fstat64</code>

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
long int __do_compat_sys_x86_fstat64(unsigned int fd, struct stat64 *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/sys_ia32.c (ffffffff81085210)
Location: arch/x86/ia32/sys_ia32.c:121
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fstat64
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fstat64
```
**Symbols:**

```
ffffffff81085210-ffffffff81085276: __do_compat_sys_x86_fstat64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __do_compat_sys_x86_fstat64(unsigned int fd, struct stat64 *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/sys_ia32.c (ffffffff8108bf80)
Location: arch/x86/ia32/sys_ia32.c:121
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fstat64
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fstat64
```
**Symbols:**

```
ffffffff8108bf80-ffffffff8108bfe6: __do_compat_sys_x86_fstat64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int __do_compat_sys_x86_fstat64(unsigned int fd, struct stat64 *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/sys_ia32.c (ffffffff8108fd80)
Location: arch/x86/ia32/sys_ia32.c:121
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fstat64
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fstat64
```
**Symbols:**

```
ffffffff8108fd80-ffffffff8108fde8: __do_compat_sys_x86_fstat64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __do_compat_sys_x86_fstat64(unsigned int fd, struct stat64 *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/sys_ia32.c (ffffffff810908e0)
Location: arch/x86/ia32/sys_ia32.c:121
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fstat64
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fstat64
```
**Symbols:**

```
ffffffff810908e0-ffffffff81090948: __do_compat_sys_x86_fstat64 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
long int __do_compat_sys_x86_fstat64(unsigned int fd, struct stat64 *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/sys_ia32.c (ffffffff8108f8a0)
Location: arch/x86/ia32/sys_ia32.c:121
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fstat64
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fstat64
```
**Symbols:**

```
ffffffff8108f8a0-ffffffff8108f908: __do_compat_sys_x86_fstat64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __do_compat_sys_x86_fstat64(unsigned int fd, struct stat64 *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/sys_ia32.c (ffffffff8107e3b0)
Location: arch/x86/ia32/sys_ia32.c:121
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fstat64
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fstat64
```
**Symbols:**

```
ffffffff8107e3b0-ffffffff8107e418: __do_compat_sys_x86_fstat64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __do_compat_sys_x86_fstat64(unsigned int fd, struct stat64 *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/sys_ia32.c (ffffffff8108f850)
Location: arch/x86/ia32/sys_ia32.c:121
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fstat64
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fstat64
```
**Symbols:**

```
ffffffff8108f850-ffffffff8108f8b8: __do_compat_sys_x86_fstat64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __do_compat_sys_x86_fstat64(unsigned int fd, struct stat64 *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/sys_ia32.c (ffffffff81091c30)
Location: arch/x86/ia32/sys_ia32.c:121
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fstat64
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fstat64
```
**Symbols:**

```
ffffffff81091c30-ffffffff81091c98: __do_compat_sys_x86_fstat64 (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
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
