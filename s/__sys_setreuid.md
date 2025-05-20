# Function: <code>__sys_setreuid</code>

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
long int __sys_setreuid(uid_t ruid, uid_t euid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810a6a80)
Location: kernel/sys.c:493
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setreuid
  - kernel/sys.c:__x64_sys_setreuid
  - kernel/uid16.c:__ia32_sys_setreuid16
  - kernel/uid16.c:__x64_sys_setreuid16
```
**Symbols:**

```
ffffffff810a6a80-ffffffff810a6c70: __sys_setreuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __sys_setreuid(uid_t ruid, uid_t euid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810af790)
Location: kernel/sys.c:493
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setreuid
  - kernel/sys.c:__x64_sys_setreuid
  - kernel/uid16.c:__ia32_sys_setreuid16
  - kernel/uid16.c:__x64_sys_setreuid16
```
**Symbols:**

```
ffffffff810af790-ffffffff810af980: __sys_setreuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int __sys_setreuid(uid_t ruid, uid_t euid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b5110)
Location: kernel/sys.c:493
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setreuid
  - kernel/sys.c:__x64_sys_setreuid
  - kernel/uid16.c:__ia32_sys_setreuid16
  - kernel/uid16.c:__x64_sys_setreuid16
```
**Symbols:**

```
ffffffff810b5110-ffffffff810b5326: __sys_setreuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __sys_setreuid(uid_t ruid, uid_t euid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810bb700)
Location: kernel/sys.c:493
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setreuid
  - kernel/sys.c:__x64_sys_setreuid
  - kernel/uid16.c:__ia32_sys_setreuid16
  - kernel/uid16.c:__x64_sys_setreuid16
```
**Symbols:**

```
ffffffff810bb700-ffffffff810bb916: __sys_setreuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __sys_setreuid(uid_t ruid, uid_t euid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810c30b0)
Location: kernel/sys.c:502
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setreuid
  - kernel/sys.c:__x64_sys_setreuid
  - kernel/uid16.c:__ia32_sys_setreuid16
  - kernel/uid16.c:__x64_sys_setreuid16
```
**Symbols:**

```
ffffffff810c30b0-ffffffff810c3283: __sys_setreuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __sys_setreuid(uid_t ruid, uid_t euid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810be4c0)
Location: kernel/sys.c:503
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setreuid
  - kernel/sys.c:__x64_sys_setreuid
  - kernel/uid16.c:__ia32_sys_setreuid16
  - kernel/uid16.c:__x64_sys_setreuid16
```
**Symbols:**

```
ffffffff810be4c0-ffffffff810be693: __sys_setreuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __sys_setreuid(uid_t ruid, uid_t euid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810bfe00)
Location: kernel/sys.c:508
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setreuid
  - kernel/sys.c:__x64_sys_setreuid
  - kernel/uid16.c:__ia32_sys_setreuid16
  - kernel/uid16.c:__x64_sys_setreuid16
```
**Symbols:**

```
ffffffff810bfe00-ffffffff810bffea: __sys_setreuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __sys_setreuid(uid_t ruid, uid_t euid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810d2870)
Location: kernel/sys.c:514
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setreuid
  - kernel/sys.c:__x64_sys_setreuid
  - kernel/uid16.c:__ia32_sys_setreuid16
  - kernel/uid16.c:__x64_sys_setreuid16
```
**Symbols:**

```
ffffffff810d2870-ffffffff810d2a70: __sys_setreuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __sys_setreuid(uid_t ruid, uid_t euid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810eb960)
Location: kernel/sys.c:521
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setreuid
  - kernel/sys.c:__x64_sys_setreuid
  - kernel/uid16.c:__ia32_sys_setreuid16
  - kernel/uid16.c:__x64_sys_setreuid16
```
**Symbols:**

```
ffffffff810eb960-ffffffff810ebca3: __sys_setreuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __sys_setreuid(uid_t ruid, uid_t euid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff8110cbc0)
Location: kernel/sys.c:522
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setreuid
  - kernel/sys.c:__x64_sys_setreuid
  - kernel/uid16.c:__ia32_sys_setreuid16
  - kernel/uid16.c:__x64_sys_setreuid16
```
**Symbols:**

```
ffffffff8110cbc0-ffffffff8110cf03: __sys_setreuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __sys_setreuid(uid_t ruid, uid_t euid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff81118d80)
Location: kernel/sys.c:529
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setreuid
  - kernel/sys.c:__x64_sys_setreuid
  - kernel/uid16.c:__ia32_sys_setreuid16
  - kernel/uid16.c:__x64_sys_setreuid16
```
**Symbols:**

```
ffffffff81118d80-ffffffff8111909d: __sys_setreuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __sys_setreuid(uid_t ruid, uid_t euid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff81122770)
Location: kernel/sys.c:529
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setreuid
  - kernel/sys.c:__x64_sys_setreuid
  - kernel/uid16.c:__ia32_sys_setreuid16
  - kernel/uid16.c:__x64_sys_setreuid16
```
**Symbols:**

```
ffffffff81122770-ffffffff81122a8d: __sys_setreuid (STB_GLOBAL)
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
long int __sys_setreuid(uid_t ruid, uid_t euid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffff800010118150)
Location: kernel/sys.c:493
Inline: False
Direct callers:
  - kernel/sys.c:__arm64_sys_setreuid
  - kernel/uid16.c:__arm64_sys_setreuid16
```
**Symbols:**

```
ffff800010118150-ffff800010118350: __sys_setreuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int __sys_setreuid(uid_t ruid, uid_t euid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (c036c164)
Location: kernel/sys.c:493
Inline: False
Direct callers:
  - kernel/sys.c:__se_sys_setreuid
  - kernel/uid16.c:__se_sys_setreuid16
```
**Symbols:**

```
c036c164-c036c34c: __sys_setreuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __sys_setreuid(uid_t ruid, uid_t euid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (c00000000015f990)
Location: kernel/sys.c:493
Inline: False
Direct callers:
  - kernel/sys.c:__se_sys_setreuid
```
**Symbols:**

```
c00000000015f990-c00000000015fc10: __sys_setreuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int __sys_setreuid(uid_t ruid, uid_t euid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffe0000d3120)
Location: kernel/sys.c:493
Inline: False
Direct callers:
  - kernel/sys.c:__se_sys_setreuid
```
**Symbols:**

```
ffffffe0000d3120-ffffffe0000d32ac: __sys_setreuid (STB_GLOBAL)
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
long int __sys_setreuid(uid_t ruid, uid_t euid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b5a70)
Location: kernel/sys.c:493
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setreuid
  - kernel/sys.c:__x64_sys_setreuid
  - kernel/uid16.c:__ia32_sys_setreuid16
  - kernel/uid16.c:__x64_sys_setreuid16
```
**Symbols:**

```
ffffffff810b5a70-ffffffff810b5c86: __sys_setreuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __sys_setreuid(uid_t ruid, uid_t euid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810a43b0)
Location: kernel/sys.c:493
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setreuid
  - kernel/sys.c:__x64_sys_setreuid
  - kernel/uid16.c:__ia32_sys_setreuid16
  - kernel/uid16.c:__x64_sys_setreuid16
```
**Symbols:**

```
ffffffff810a43b0-ffffffff810a45c6: __sys_setreuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __sys_setreuid(uid_t ruid, uid_t euid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b4fd0)
Location: kernel/sys.c:493
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setreuid
  - kernel/sys.c:__x64_sys_setreuid
  - kernel/uid16.c:__ia32_sys_setreuid16
  - kernel/uid16.c:__x64_sys_setreuid16
```
**Symbols:**

```
ffffffff810b4fd0-ffffffff810b51e6: __sys_setreuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __sys_setreuid(uid_t ruid, uid_t euid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810bd340)
Location: kernel/sys.c:493
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setreuid
  - kernel/sys.c:__x64_sys_setreuid
  - kernel/uid16.c:__ia32_sys_setreuid16
  - kernel/uid16.c:__x64_sys_setreuid16
```
**Symbols:**

```
ffffffff810bd340-ffffffff810bd556: __sys_setreuid (STB_GLOBAL)
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
