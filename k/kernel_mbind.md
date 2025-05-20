# Function: <code>kernel_mbind</code>

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
long int kernel_mbind(long unsigned int start, long unsigned int len, long unsigned int mode, const long unsigned int *nmask, long unsigned int maxnode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8125c370)
Location: mm/mempolicy.c:1315
Inline: False
Direct callers:
  - mm/mempolicy.c:__do_compat_sys_mbind
  - mm/mempolicy.c:__ia32_sys_mbind
  - mm/mempolicy.c:__x64_sys_mbind
```
**Symbols:**

```
ffffffff8125c370-ffffffff8125c9d9: kernel_mbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int kernel_mbind(long unsigned int start, long unsigned int len, long unsigned int mode, const long unsigned int *nmask, long unsigned int maxnode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81270c50)
Location: mm/mempolicy.c:1355
Inline: False
Direct callers:
  - mm/mempolicy.c:__do_compat_sys_mbind
  - mm/mempolicy.c:__ia32_sys_mbind
  - mm/mempolicy.c:__x64_sys_mbind
```
**Symbols:**

```
ffffffff81270c50-ffffffff812712b9: kernel_mbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int kernel_mbind(long unsigned int start, long unsigned int len, long unsigned int mode, const long unsigned int *nmask, long unsigned int maxnode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8128c270)
Location: mm/mempolicy.c:1401
Inline: False
Direct callers:
  - mm/mempolicy.c:__do_compat_sys_mbind
  - mm/mempolicy.c:__ia32_sys_mbind
  - mm/mempolicy.c:__x64_sys_mbind
```
**Symbols:**

```
ffffffff8128c270-ffffffff8128c8c9: kernel_mbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int kernel_mbind(long unsigned int start, long unsigned int len, long unsigned int mode, const long unsigned int *nmask, long unsigned int maxnode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8129be40)
Location: mm/mempolicy.c:1404
Inline: False
Direct callers:
  - mm/mempolicy.c:__do_compat_sys_mbind
  - mm/mempolicy.c:__ia32_sys_mbind
  - mm/mempolicy.c:__x64_sys_mbind
```
**Symbols:**

```
ffffffff8129be40-ffffffff8129c4f2: kernel_mbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int kernel_mbind(long unsigned int start, long unsigned int len, long unsigned int mode, const long unsigned int *nmask, long unsigned int maxnode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812d0090)
Location: mm/mempolicy.c:1473
Inline: False
Direct callers:
  - mm/mempolicy.c:__do_compat_sys_mbind
  - mm/mempolicy.c:__ia32_sys_mbind
  - mm/mempolicy.c:__x64_sys_mbind
```
**Symbols:**

```
ffffffff812d0090-ffffffff812d014a: kernel_mbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int kernel_mbind(long unsigned int start, long unsigned int len, long unsigned int mode, const long unsigned int *nmask, long unsigned int maxnode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812dbbb0)
Location: mm/mempolicy.c:1449
Inline: False
Direct callers:
  - mm/mempolicy.c:__do_compat_sys_mbind
  - mm/mempolicy.c:__ia32_sys_mbind
  - mm/mempolicy.c:__x64_sys_mbind
```
**Symbols:**

```
ffffffff812dbbb0-ffffffff812dbc6a: kernel_mbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int kernel_mbind(long unsigned int start, long unsigned int len, long unsigned int mode, const long unsigned int *nmask, long unsigned int maxnode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812e3430)
Location: mm/mempolicy.c:1463
Inline: False
Direct callers:
  - mm/mempolicy.c:__do_compat_sys_mbind
  - mm/mempolicy.c:__ia32_sys_mbind
  - mm/mempolicy.c:__x64_sys_mbind
```
**Symbols:**

```
ffffffff812e3430-ffffffff812e34ed: kernel_mbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int kernel_mbind(long unsigned int start, long unsigned int len, long unsigned int mode, const long unsigned int *nmask, long unsigned int maxnode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8132a7b0)
Location: mm/mempolicy.c:1459
Inline: False
Direct callers:
  - mm/mempolicy.c:__ia32_sys_mbind
  - mm/mempolicy.c:__x64_sys_mbind
```
**Symbols:**

```
ffffffff8132a7b0-ffffffff8132a87a: kernel_mbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int kernel_mbind(long unsigned int start, long unsigned int len, long unsigned int mode, const long unsigned int *nmask, long unsigned int maxnode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8139a100)
Location: mm/mempolicy.c:1452
Inline: False
Direct callers:
  - mm/mempolicy.c:__ia32_sys_mbind
  - mm/mempolicy.c:__x64_sys_mbind
```
**Symbols:**

```
ffffffff8139a100-ffffffff8139a1ed: kernel_mbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int kernel_mbind(long unsigned int start, long unsigned int len, long unsigned int mode, const long unsigned int *nmask, long unsigned int maxnode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8141a0e0)
Location: mm/mempolicy.c:1467
Inline: False
Direct callers:
  - mm/mempolicy.c:__ia32_sys_mbind
  - mm/mempolicy.c:__x64_sys_mbind
```
**Symbols:**

```
ffffffff8141a0e0-ffffffff8141a1cd: kernel_mbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int kernel_mbind(long unsigned int start, long unsigned int len, long unsigned int mode, const long unsigned int *nmask, long unsigned int maxnode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8144d670)
Location: mm/mempolicy.c:1484
Inline: False
Direct callers:
  - mm/mempolicy.c:__ia32_sys_mbind
  - mm/mempolicy.c:__x64_sys_mbind
```
**Symbols:**

```
ffffffff8144d670-ffffffff8144d766: kernel_mbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int kernel_mbind(long unsigned int start, long unsigned int len, long unsigned int mode, const long unsigned int *nmask, long unsigned int maxnode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff814872a0)
Location: mm/mempolicy.c:1468
Inline: False
Direct callers:
  - mm/mempolicy.c:__ia32_sys_mbind
  - mm/mempolicy.c:__x64_sys_mbind
```
**Symbols:**

```
ffffffff814872a0-ffffffff81487396: kernel_mbind (STB_LOCAL)
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
long int kernel_mbind(long unsigned int start, long unsigned int len, long unsigned int mode, const long unsigned int *nmask, long unsigned int maxnode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffff80001033ae28)
Location: mm/mempolicy.c:1404
Inline: False
Direct callers:
  - mm/mempolicy.c:__arm64_compat_sys_mbind
  - mm/mempolicy.c:__arm64_sys_mbind
```
**Symbols:**

```
ffff80001033ae28-ffff80001033b364: kernel_mbind (STB_LOCAL)
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
long int kernel_mbind(long unsigned int start, long unsigned int len, long unsigned int mode, const long unsigned int *nmask, long unsigned int maxnode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (c000000000416070)
Location: mm/mempolicy.c:1404
Inline: False
Direct callers:
  - mm/mempolicy.c:__se_compat_sys_mbind
  - mm/mempolicy.c:__se_sys_mbind
```
**Symbols:**

```
c000000000416070-c000000000416198: kernel_mbind (STB_LOCAL)
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
long int kernel_mbind(long unsigned int start, long unsigned int len, long unsigned int mode, const long unsigned int *nmask, long unsigned int maxnode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81294420)
Location: mm/mempolicy.c:1404
Inline: False
Direct callers:
  - mm/mempolicy.c:__do_compat_sys_mbind
  - mm/mempolicy.c:__ia32_sys_mbind
  - mm/mempolicy.c:__x64_sys_mbind
```
**Symbols:**

```
ffffffff81294420-ffffffff81294ad2: kernel_mbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int kernel_mbind(long unsigned int start, long unsigned int len, long unsigned int mode, const long unsigned int *nmask, long unsigned int maxnode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81286030)
Location: mm/mempolicy.c:1404
Inline: False
Direct callers:
  - mm/mempolicy.c:__do_compat_sys_mbind
  - mm/mempolicy.c:__ia32_sys_mbind
  - mm/mempolicy.c:__x64_sys_mbind
```
**Symbols:**

```
ffffffff81286030-ffffffff812866e2: kernel_mbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int kernel_mbind(long unsigned int start, long unsigned int len, long unsigned int mode, const long unsigned int *nmask, long unsigned int maxnode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81292230)
Location: mm/mempolicy.c:1404
Inline: False
Direct callers:
  - mm/mempolicy.c:__do_compat_sys_mbind
  - mm/mempolicy.c:__ia32_sys_mbind
  - mm/mempolicy.c:__x64_sys_mbind
```
**Symbols:**

```
ffffffff81292230-ffffffff812928e2: kernel_mbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int kernel_mbind(long unsigned int start, long unsigned int len, long unsigned int mode, const long unsigned int *nmask, long unsigned int maxnode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812a2030)
Location: mm/mempolicy.c:1404
Inline: False
Direct callers:
  - mm/mempolicy.c:__do_compat_sys_mbind
  - mm/mempolicy.c:__ia32_sys_mbind
  - mm/mempolicy.c:__x64_sys_mbind
```
**Symbols:**

```
ffffffff812a2030-ffffffff812a26b5: kernel_mbind (STB_LOCAL)
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
