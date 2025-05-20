# Function: <code>__do_compat_sys_ia32_stat64</code>

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
long int __do_compat_sys_ia32_stat64(const char *filename, struct stat64 *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sys_ia32.c (ffffffff8103a480)
Location: arch/x86/kernel/sys_ia32.c:164
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__x32_compat_sys_ia32_stat64
  - arch/x86/kernel/sys_ia32.c:__ia32_compat_sys_ia32_stat64
```
**Symbols:**

```
ffffffff8103a480-ffffffff8103a4ef: __do_compat_sys_ia32_stat64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_compat_sys_ia32_stat64(const char *filename, struct stat64 *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sys_ia32.c (ffffffff8103acb0)
Location: arch/x86/kernel/sys_ia32.c:164
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__x32_compat_sys_ia32_stat64
  - arch/x86/kernel/sys_ia32.c:__ia32_compat_sys_ia32_stat64
```
**Symbols:**

```
ffffffff8103acb0-ffffffff8103ad16: __do_compat_sys_ia32_stat64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_compat_sys_ia32_stat64(const char *filename, struct stat64 *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sys_ia32.c (ffffffff8103c680)
Location: arch/x86/kernel/sys_ia32.c:164
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__x32_compat_sys_ia32_stat64
  - arch/x86/kernel/sys_ia32.c:__ia32_compat_sys_ia32_stat64
```
**Symbols:**

```
ffffffff8103c680-ffffffff8103c6e6: __do_compat_sys_ia32_stat64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __do_compat_sys_ia32_stat64(const char *filename, struct stat64 *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sys_ia32.c (ffffffff81042180)
Location: arch/x86/kernel/sys_ia32.c:164
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__x64_compat_sys_ia32_stat64
  - arch/x86/kernel/sys_ia32.c:__ia32_compat_sys_ia32_stat64
```
**Symbols:**

```
ffffffff81042180-ffffffff810421e6: __do_compat_sys_ia32_stat64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_compat_sys_ia32_stat64(const char *filename, struct stat64 *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sys_ia32.c (ffffffff81049e90)
Location: arch/x86/kernel/sys_ia32.c:164
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_compat_sys_ia32_stat64
```
**Symbols:**

```
ffffffff81049e90-ffffffff81049f17: __do_compat_sys_ia32_stat64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_compat_sys_ia32_stat64(const char *filename, struct stat64 *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sys_ia32.c (ffffffff81055080)
Location: arch/x86/kernel/sys_ia32.c:164
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_compat_sys_ia32_stat64
```
**Symbols:**

```
ffffffff81055080-ffffffff81055107: __do_compat_sys_ia32_stat64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_compat_sys_ia32_stat64(const char *filename, struct stat64 *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sys_ia32.c (ffffffff81056290)
Location: arch/x86/kernel/sys_ia32.c:164
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_compat_sys_ia32_stat64
```
**Symbols:**

```
ffffffff81056290-ffffffff81056317: __do_compat_sys_ia32_stat64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __do_compat_sys_ia32_stat64(const char *filename, struct stat64 *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sys_ia32.c (ffffffff8105d4e0)
Location: arch/x86/kernel/sys_ia32.c:164
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_compat_sys_ia32_stat64
```
**Symbols:**

```
ffffffff8105d4e0-ffffffff8105d567: __do_compat_sys_ia32_stat64 (STB_LOCAL)
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
