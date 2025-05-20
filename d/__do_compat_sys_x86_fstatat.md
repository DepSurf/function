# Function: <code>__do_compat_sys_x86_fstatat</code>

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
long int __do_compat_sys_x86_fstatat(unsigned int dfd, const char *filename, struct stat64 *statbuf, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/sys_ia32.c (ffffffff81085160)
Location: arch/x86/ia32/sys_ia32.c:131
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fstatat
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fstatat
```
**Symbols:**

```
ffffffff81085160-ffffffff810851c8: __do_compat_sys_x86_fstatat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __do_compat_sys_x86_fstatat(unsigned int dfd, const char *filename, struct stat64 *statbuf, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/sys_ia32.c (ffffffff8108bed0)
Location: arch/x86/ia32/sys_ia32.c:131
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fstatat
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fstatat
```
**Symbols:**

```
ffffffff8108bed0-ffffffff8108bf38: __do_compat_sys_x86_fstatat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int __do_compat_sys_x86_fstatat(unsigned int dfd, const char *filename, struct stat64 *statbuf, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/sys_ia32.c (ffffffff8108fcd0)
Location: arch/x86/ia32/sys_ia32.c:131
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fstatat
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fstatat
```
**Symbols:**

```
ffffffff8108fcd0-ffffffff8108fd3a: __do_compat_sys_x86_fstatat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __do_compat_sys_x86_fstatat(unsigned int dfd, const char *filename, struct stat64 *statbuf, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/sys_ia32.c (ffffffff81090830)
Location: arch/x86/ia32/sys_ia32.c:131
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fstatat
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fstatat
```
**Symbols:**

```
ffffffff81090830-ffffffff8109089a: __do_compat_sys_x86_fstatat (STB_LOCAL)
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
long int __do_compat_sys_x86_fstatat(unsigned int dfd, const char *filename, struct stat64 *statbuf, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/sys_ia32.c (ffffffff8108f7f0)
Location: arch/x86/ia32/sys_ia32.c:131
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fstatat
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fstatat
```
**Symbols:**

```
ffffffff8108f7f0-ffffffff8108f85a: __do_compat_sys_x86_fstatat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __do_compat_sys_x86_fstatat(unsigned int dfd, const char *filename, struct stat64 *statbuf, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/sys_ia32.c (ffffffff8107e300)
Location: arch/x86/ia32/sys_ia32.c:131
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fstatat
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fstatat
```
**Symbols:**

```
ffffffff8107e300-ffffffff8107e36a: __do_compat_sys_x86_fstatat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __do_compat_sys_x86_fstatat(unsigned int dfd, const char *filename, struct stat64 *statbuf, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/sys_ia32.c (ffffffff8108f7a0)
Location: arch/x86/ia32/sys_ia32.c:131
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fstatat
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fstatat
```
**Symbols:**

```
ffffffff8108f7a0-ffffffff8108f80a: __do_compat_sys_x86_fstatat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __do_compat_sys_x86_fstatat(unsigned int dfd, const char *filename, struct stat64 *statbuf, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/sys_ia32.c (ffffffff81091b80)
Location: arch/x86/ia32/sys_ia32.c:131
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fstatat
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fstatat
```
**Symbols:**

```
ffffffff81091b80-ffffffff81091bea: __do_compat_sys_x86_fstatat (STB_LOCAL)
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
