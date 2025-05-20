# Function: <code>do_getpgid</code>

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
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int do_getpgid(pid_t pid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810a3b95)
Location: kernel/sys.c:1077
Inline: True
Inline callers:
  - kernel/sys.c:__x64_sys_getpgrp
Direct callers:
  - kernel/sys.c:__ia32_sys_getpgid
  - kernel/sys.c:__x64_sys_getpgid
```
**Symbols:**

```
ffffffff810a3ae0-ffffffff810a3b43: do_getpgid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int do_getpgid(pid_t pid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810ac965)
Location: kernel/sys.c:1077
Inline: True
Inline callers:
  - kernel/sys.c:__x64_sys_getpgrp
Direct callers:
  - kernel/sys.c:__ia32_sys_getpgid
  - kernel/sys.c:__x64_sys_getpgid
```
**Symbols:**

```
ffffffff810ac8b0-ffffffff810ac913: do_getpgid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int do_getpgid(pid_t pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b1e80)
Location: kernel/sys.c:1077
Inline: False
Direct callers:
  - kernel/sys.c:__x64_sys_getpgrp
  - kernel/sys.c:__ia32_sys_getpgid
  - kernel/sys.c:__x64_sys_getpgid
```
**Symbols:**

```
ffffffff810b1e80-ffffffff810b1ee6: do_getpgid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int do_getpgid(pid_t pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b8550)
Location: kernel/sys.c:1077
Inline: False
Direct callers:
  - kernel/sys.c:__x64_sys_getpgrp
  - kernel/sys.c:__ia32_sys_getpgid
  - kernel/sys.c:__x64_sys_getpgid
```
**Symbols:**

```
ffffffff810b8550-ffffffff810b85b6: do_getpgid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810c1ad5)
Location: kernel/sys.c:1091
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_getpgrp
  - kernel/sys.c:__ia32_sys_getpgid
  - kernel/sys.c:__x64_sys_getpgid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int do_getpgid(pid_t pid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810bcc75)
Location: kernel/sys.c:1092
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_getpgrp
Direct callers:
  - kernel/sys.c:__ia32_sys_getpgid
  - kernel/sys.c:__x64_sys_getpgid
```
**Symbols:**

```
ffffffff810bb110-ffffffff810bb193: do_getpgid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int do_getpgid(pid_t pid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810be505)
Location: kernel/sys.c:1109
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_getpgrp
Direct callers:
  - kernel/sys.c:__ia32_sys_getpgid
  - kernel/sys.c:__x64_sys_getpgid
```
**Symbols:**

```
ffffffff810bca50-ffffffff810bcad3: do_getpgid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int do_getpgid(pid_t pid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810d1385)
Location: kernel/sys.c:1118
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_getpgrp
Direct callers:
  - kernel/sys.c:__ia32_sys_getpgid
  - kernel/sys.c:__x64_sys_getpgid
```
**Symbols:**

```
ffffffff810cf430-ffffffff810cf4b3: do_getpgid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int do_getpgid(pid_t pid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810e9e75)
Location: kernel/sys.c:1125
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_getpgrp
Direct callers:
  - kernel/sys.c:__ia32_sys_getpgid
  - kernel/sys.c:__x64_sys_getpgid
```
**Symbols:**

```
ffffffff810e7fa0-ffffffff810e8030: do_getpgid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int do_getpgid(pid_t pid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff8110bb75)
Location: kernel/sys.c:1126
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_getpgrp
Direct callers:
  - kernel/sys.c:__ia32_sys_getpgid
  - kernel/sys.c:__x64_sys_getpgid
```
**Symbols:**

```
ffffffff81108ce0-ffffffff81108d70: do_getpgid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int do_getpgid(pid_t pid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff81117f05)
Location: kernel/sys.c:1144
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_getpgrp
Direct callers:
  - kernel/sys.c:__ia32_sys_getpgid
  - kernel/sys.c:__x64_sys_getpgid
```
**Symbols:**

```
ffffffff81114ff0-ffffffff81115080: do_getpgid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int do_getpgid(pid_t pid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff811218f5)
Location: kernel/sys.c:1144
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_getpgrp
Direct callers:
  - kernel/sys.c:__ia32_sys_getpgid
  - kernel/sys.c:__x64_sys_getpgid
```
**Symbols:**

```
ffffffff8111e9e0-ffffffff8111ea70: do_getpgid (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffff8000101147a0)
Location: kernel/sys.c:1077
Inline: True
Inline callers:
  - kernel/sys.c:__arm64_sys_getpgrp
  - kernel/sys.c:__arm64_sys_getpgid
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_getpgid(pid_t pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (c036acb4)
Location: kernel/sys.c:1077
Inline: False
Direct callers:
  - kernel/sys.c:sys_getpgrp
  - kernel/sys.c:__se_sys_getpgid
```
**Symbols:**

```
c036acb4-c036ad28: do_getpgid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (c00000000015dbdc)
Location: kernel/sys.c:1077
Inline: True
Inline callers:
  - kernel/sys.c:sys_getpgrp
  - kernel/sys.c:__se_sys_getpgid
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffe0000d3e5a)
Location: kernel/sys.c:1077
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_getpgid
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
int do_getpgid(pid_t pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b28c0)
Location: kernel/sys.c:1077
Inline: False
Direct callers:
  - kernel/sys.c:__x64_sys_getpgrp
  - kernel/sys.c:__ia32_sys_getpgid
  - kernel/sys.c:__x64_sys_getpgid
```
**Symbols:**

```
ffffffff810b28c0-ffffffff810b2926: do_getpgid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int do_getpgid(pid_t pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810a11f0)
Location: kernel/sys.c:1077
Inline: False
Direct callers:
  - kernel/sys.c:__x64_sys_getpgrp
  - kernel/sys.c:__ia32_sys_getpgid
  - kernel/sys.c:__x64_sys_getpgid
```
**Symbols:**

```
ffffffff810a11f0-ffffffff810a1256: do_getpgid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int do_getpgid(pid_t pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b1e20)
Location: kernel/sys.c:1077
Inline: False
Direct callers:
  - kernel/sys.c:__x64_sys_getpgrp
  - kernel/sys.c:__ia32_sys_getpgid
  - kernel/sys.c:__x64_sys_getpgid
```
**Symbols:**

```
ffffffff810b1e20-ffffffff810b1e86: do_getpgid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int do_getpgid(pid_t pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810ba310)
Location: kernel/sys.c:1077
Inline: False
Direct callers:
  - kernel/sys.c:__x64_sys_getpgrp
  - kernel/sys.c:__ia32_sys_getpgid
  - kernel/sys.c:__x64_sys_getpgid
```
**Symbols:**

```
ffffffff810ba310-ffffffff810ba39f: do_getpgid (STB_LOCAL)
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
