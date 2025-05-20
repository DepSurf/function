# Function: <code>__do_compat_sys_ia32_fstat64</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __do_compat_sys_ia32_fstat64(unsigned int fd, struct stat64 *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sys_ia32.c (ffffffff8103a690)
Location: arch/x86/kernel/sys_ia32.c:185
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__x32_compat_sys_ia32_fstat64
  - arch/x86/kernel/sys_ia32.c:__ia32_compat_sys_ia32_fstat64
```
**Symbols:**

```
ffffffff8103a690-ffffffff8103a6f3: __do_compat_sys_ia32_fstat64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_compat_sys_ia32_fstat64(unsigned int fd, struct stat64 *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sys_ia32.c (ffffffff8103aeb0)
Location: arch/x86/kernel/sys_ia32.c:185
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__x32_compat_sys_ia32_fstat64
  - arch/x86/kernel/sys_ia32.c:__ia32_compat_sys_ia32_fstat64
```
**Symbols:**

```
ffffffff8103aeb0-ffffffff8103af0c: __do_compat_sys_ia32_fstat64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_compat_sys_ia32_fstat64(unsigned int fd, struct stat64 *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sys_ia32.c (ffffffff8103c880)
Location: arch/x86/kernel/sys_ia32.c:185
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__x32_compat_sys_ia32_fstat64
  - arch/x86/kernel/sys_ia32.c:__ia32_compat_sys_ia32_fstat64
```
**Symbols:**

```
ffffffff8103c880-ffffffff8103c8dc: __do_compat_sys_ia32_fstat64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __do_compat_sys_ia32_fstat64(unsigned int fd, struct stat64 *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sys_ia32.c (ffffffff81042380)
Location: arch/x86/kernel/sys_ia32.c:185
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__x64_compat_sys_ia32_fstat64
  - arch/x86/kernel/sys_ia32.c:__ia32_compat_sys_ia32_fstat64
```
**Symbols:**

```
ffffffff81042380-ffffffff810423dc: __do_compat_sys_ia32_fstat64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_compat_sys_ia32_fstat64(unsigned int fd, struct stat64 *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sys_ia32.c (ffffffff8104a0b0)
Location: arch/x86/kernel/sys_ia32.c:185
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_compat_sys_ia32_fstat64
```
**Symbols:**

```
ffffffff8104a0b0-ffffffff8104a12d: __do_compat_sys_ia32_fstat64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_compat_sys_ia32_fstat64(unsigned int fd, struct stat64 *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sys_ia32.c (ffffffff81055300)
Location: arch/x86/kernel/sys_ia32.c:185
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_compat_sys_ia32_fstat64
```
**Symbols:**

```
ffffffff81055300-ffffffff8105537d: __do_compat_sys_ia32_fstat64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_compat_sys_ia32_fstat64(unsigned int fd, struct stat64 *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sys_ia32.c (ffffffff81056510)
Location: arch/x86/kernel/sys_ia32.c:185
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_compat_sys_ia32_fstat64
```
**Symbols:**

```
ffffffff81056510-ffffffff8105658d: __do_compat_sys_ia32_fstat64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __do_compat_sys_ia32_fstat64(unsigned int fd, struct stat64 *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sys_ia32.c (ffffffff8105d760)
Location: arch/x86/kernel/sys_ia32.c:185
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_compat_sys_ia32_fstat64
```
**Symbols:**

```
ffffffff8105d760-ffffffff8105d7dd: __do_compat_sys_ia32_fstat64 (STB_LOCAL)
```
</details>
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
