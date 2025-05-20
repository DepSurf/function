# Function: <code>__do_compat_sys_ia32_fstatat64</code>

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
long int __do_compat_sys_ia32_fstatat64(unsigned int dfd, const char *filename, struct stat64 *statbuf, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sys_ia32.c (ffffffff8103a5e0)
Location: arch/x86/kernel/sys_ia32.c:195
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__x32_compat_sys_ia32_fstatat64
  - arch/x86/kernel/sys_ia32.c:__ia32_compat_sys_ia32_fstatat64
```
**Symbols:**

```
ffffffff8103a5e0-ffffffff8103a645: __do_compat_sys_ia32_fstatat64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_compat_sys_ia32_fstatat64(unsigned int dfd, const char *filename, struct stat64 *statbuf, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sys_ia32.c (ffffffff8103ae10)
Location: arch/x86/kernel/sys_ia32.c:195
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__x32_compat_sys_ia32_fstatat64
  - arch/x86/kernel/sys_ia32.c:__ia32_compat_sys_ia32_fstatat64
```
**Symbols:**

```
ffffffff8103ae10-ffffffff8103ae6a: __do_compat_sys_ia32_fstatat64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_compat_sys_ia32_fstatat64(unsigned int dfd, const char *filename, struct stat64 *statbuf, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sys_ia32.c (ffffffff8103c7e0)
Location: arch/x86/kernel/sys_ia32.c:195
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__x32_compat_sys_ia32_fstatat64
  - arch/x86/kernel/sys_ia32.c:__ia32_compat_sys_ia32_fstatat64
```
**Symbols:**

```
ffffffff8103c7e0-ffffffff8103c83a: __do_compat_sys_ia32_fstatat64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __do_compat_sys_ia32_fstatat64(unsigned int dfd, const char *filename, struct stat64 *statbuf, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sys_ia32.c (ffffffff810422e0)
Location: arch/x86/kernel/sys_ia32.c:195
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__x64_compat_sys_ia32_fstatat64
  - arch/x86/kernel/sys_ia32.c:__ia32_compat_sys_ia32_fstatat64
```
**Symbols:**

```
ffffffff810422e0-ffffffff8104233a: __do_compat_sys_ia32_fstatat64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_compat_sys_ia32_fstatat64(unsigned int dfd, const char *filename, struct stat64 *statbuf, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sys_ia32.c (ffffffff81049ff0)
Location: arch/x86/kernel/sys_ia32.c:195
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_compat_sys_ia32_fstatat64
```
**Symbols:**

```
ffffffff81049ff0-ffffffff8104a074: __do_compat_sys_ia32_fstatat64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_compat_sys_ia32_fstatat64(unsigned int dfd, const char *filename, struct stat64 *statbuf, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sys_ia32.c (ffffffff81055220)
Location: arch/x86/kernel/sys_ia32.c:195
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_compat_sys_ia32_fstatat64
```
**Symbols:**

```
ffffffff81055220-ffffffff810552a4: __do_compat_sys_ia32_fstatat64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_compat_sys_ia32_fstatat64(unsigned int dfd, const char *filename, struct stat64 *statbuf, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sys_ia32.c (ffffffff81056430)
Location: arch/x86/kernel/sys_ia32.c:195
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_compat_sys_ia32_fstatat64
```
**Symbols:**

```
ffffffff81056430-ffffffff810564b4: __do_compat_sys_ia32_fstatat64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __do_compat_sys_ia32_fstatat64(unsigned int dfd, const char *filename, struct stat64 *statbuf, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sys_ia32.c (ffffffff8105d680)
Location: arch/x86/kernel/sys_ia32.c:195
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_compat_sys_ia32_fstatat64
```
**Symbols:**

```
ffffffff8105d680-ffffffff8105d704: __do_compat_sys_ia32_fstatat64 (STB_LOCAL)
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
