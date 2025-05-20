# Function: <code>__do_compat_sys_getrusage</code>

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
long int __do_compat_sys_getrusage(int who, struct compat_rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810a83f0)
Location: kernel/sys.c:1816
Inline: False
Direct callers:
  - kernel/sys.c:__x32_compat_sys_getrusage
  - kernel/sys.c:__ia32_compat_sys_getrusage
```
**Symbols:**

```
ffffffff810a83f0-ffffffff810a846c: __do_compat_sys_getrusage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __do_compat_sys_getrusage(int who, struct compat_rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b1100)
Location: kernel/sys.c:1817
Inline: False
Direct callers:
  - kernel/sys.c:__x32_compat_sys_getrusage
  - kernel/sys.c:__ia32_compat_sys_getrusage
```
**Symbols:**

```
ffffffff810b1100-ffffffff810b117c: __do_compat_sys_getrusage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int __do_compat_sys_getrusage(int who, struct compat_rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b6c40)
Location: kernel/sys.c:1818
Inline: False
Direct callers:
  - kernel/sys.c:__x32_compat_sys_getrusage
  - kernel/sys.c:__ia32_compat_sys_getrusage
```
**Symbols:**

```
ffffffff810b6c40-ffffffff810b6cbf: __do_compat_sys_getrusage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __do_compat_sys_getrusage(int who, struct compat_rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810bd200)
Location: kernel/sys.c:1808
Inline: False
Direct callers:
  - kernel/sys.c:__x32_compat_sys_getrusage
  - kernel/sys.c:__ia32_compat_sys_getrusage
```
**Symbols:**

```
ffffffff810bd200-ffffffff810bd27f: __do_compat_sys_getrusage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __do_compat_sys_getrusage(int who, struct compat_rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810c4940)
Location: kernel/sys.c:1824
Inline: False
Direct callers:
  - kernel/sys.c:__x32_compat_sys_getrusage
  - kernel/sys.c:__ia32_compat_sys_getrusage
```
**Symbols:**

```
ffffffff810c4940-ffffffff810c49bb: __do_compat_sys_getrusage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_compat_sys_getrusage(int who, struct compat_rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810bfd40)
Location: kernel/sys.c:1825
Inline: False
Direct callers:
  - kernel/sys.c:__x32_compat_sys_getrusage
  - kernel/sys.c:__ia32_compat_sys_getrusage
```
**Symbols:**

```
ffffffff810bfd40-ffffffff810bfdbb: __do_compat_sys_getrusage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_compat_sys_getrusage(int who, struct compat_rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810c1770)
Location: kernel/sys.c:1842
Inline: False
Direct callers:
  - kernel/sys.c:__x32_compat_sys_getrusage
  - kernel/sys.c:__ia32_compat_sys_getrusage
```
**Symbols:**

```
ffffffff810c1770-ffffffff810c17ef: __do_compat_sys_getrusage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __do_compat_sys_getrusage(int who, struct compat_rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810d4260)
Location: kernel/sys.c:1851
Inline: False
Direct callers:
  - kernel/sys.c:__x64_compat_sys_getrusage
  - kernel/sys.c:__ia32_compat_sys_getrusage
```
**Symbols:**

```
ffffffff810d4260-ffffffff810d42df: __do_compat_sys_getrusage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_compat_sys_getrusage(int who, struct compat_rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810ecf60)
Location: kernel/sys.c:1863
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_compat_sys_getrusage
```
**Symbols:**

```
ffffffff810ecf60-ffffffff810ed002: __do_compat_sys_getrusage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_compat_sys_getrusage(int who, struct compat_rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff8110e340)
Location: kernel/sys.c:1868
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_compat_sys_getrusage
```
**Symbols:**

```
ffffffff8110e340-ffffffff8110e3e2: __do_compat_sys_getrusage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_compat_sys_getrusage(int who, struct compat_rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff8111a5a0)
Location: kernel/sys.c:1886
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_compat_sys_getrusage
```
**Symbols:**

```
ffffffff8111a5a0-ffffffff8111a642: __do_compat_sys_getrusage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __do_compat_sys_getrusage(int who, struct compat_rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff81124010)
Location: kernel/sys.c:1899
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_compat_sys_getrusage
```
**Symbols:**

```
ffffffff81124010-ffffffff811240b2: __do_compat_sys_getrusage (STB_LOCAL)
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
long int __do_compat_sys_getrusage(int who, struct compat_rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffff800010119de0)
Location: kernel/sys.c:1808
Inline: False
Direct callers:
  - kernel/sys.c:__arm64_compat_sys_getrusage
```
**Symbols:**

```
ffff800010119de0-ffff800010119e5c: __do_compat_sys_getrusage (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __do_compat_sys_getrusage(int who, struct compat_rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (c000000000161610)
Location: kernel/sys.c:1808
Inline: False
Direct callers:
  - kernel/sys.c:__se_compat_sys_getrusage
```
**Symbols:**

```
c000000000161610-c0000000001616b8: __do_compat_sys_getrusage (STB_LOCAL)
```
</details>
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
long int __do_compat_sys_getrusage(int who, struct compat_rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b7570)
Location: kernel/sys.c:1808
Inline: False
Direct callers:
  - kernel/sys.c:__x32_compat_sys_getrusage
  - kernel/sys.c:__ia32_compat_sys_getrusage
```
**Symbols:**

```
ffffffff810b7570-ffffffff810b75ef: __do_compat_sys_getrusage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __do_compat_sys_getrusage(int who, struct compat_rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810a5eb0)
Location: kernel/sys.c:1808
Inline: False
Direct callers:
  - kernel/sys.c:__x32_compat_sys_getrusage
  - kernel/sys.c:__ia32_compat_sys_getrusage
```
**Symbols:**

```
ffffffff810a5eb0-ffffffff810a5f2f: __do_compat_sys_getrusage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __do_compat_sys_getrusage(int who, struct compat_rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b6ad0)
Location: kernel/sys.c:1808
Inline: False
Direct callers:
  - kernel/sys.c:__x32_compat_sys_getrusage
  - kernel/sys.c:__ia32_compat_sys_getrusage
```
**Symbols:**

```
ffffffff810b6ad0-ffffffff810b6b4f: __do_compat_sys_getrusage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __do_compat_sys_getrusage(int who, struct compat_rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810bee50)
Location: kernel/sys.c:1808
Inline: False
Direct callers:
  - kernel/sys.c:__x32_compat_sys_getrusage
  - kernel/sys.c:__ia32_compat_sys_getrusage
```
**Symbols:**

```
ffffffff810bee50-ffffffff810beecf: __do_compat_sys_getrusage (STB_LOCAL)
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
