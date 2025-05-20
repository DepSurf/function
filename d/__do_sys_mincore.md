# Function: <code>__do_sys_mincore</code>

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
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mincore.c (ffffffff81231f44)
Location: mm/mincore.c:224
Inline: True
Inline callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mincore.c (ffffffff81245714)
Location: mm/mincore.c:224
Inline: True
Inline callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mincore.c (ffffffff812577c4)
Location: mm/mincore.c:253
Inline: True
Inline callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mincore.c (ffffffff81265d05)
Location: mm/mincore.c:252
Inline: True
Inline callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __do_sys_mincore(long unsigned int start, size_t len, unsigned char *vec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mincore.c (ffffffff81296120)
Location: mm/mincore.c:253
Inline: False
Direct callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
```
**Symbols:**

```
ffffffff81296120-ffffffff81296299: __do_sys_mincore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_sys_mincore(long unsigned int start, size_t len, unsigned char *vec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mincore.c (ffffffff812a0e60)
Location: mm/mincore.c:229
Inline: False
Direct callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
```
**Symbols:**

```
ffffffff812a0e60-ffffffff812a1082: __do_sys_mincore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_sys_mincore(long unsigned int start, size_t len, unsigned char *vec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mincore.c (ffffffff812a65a0)
Location: mm/mincore.c:230
Inline: False
Direct callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
```
**Symbols:**

```
ffffffff812a65a0-ffffffff812a688d: __do_sys_mincore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __do_sys_mincore(long unsigned int start, size_t len, unsigned char *vec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mincore.c (ffffffff812e7a70)
Location: mm/mincore.c:230
Inline: False
Direct callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
```
**Symbols:**

```
ffffffff812e7a70-ffffffff812e7d63: __do_sys_mincore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_sys_mincore(long unsigned int start, size_t len, unsigned char *vec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mincore.c (ffffffff81348ce0)
Location: mm/mincore.c:232
Inline: False
Direct callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
```
**Symbols:**

```
ffffffff81348ce0-ffffffff81348faf: __do_sys_mincore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_sys_mincore(long unsigned int start, size_t len, unsigned char *vec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mincore.c (ffffffff813c1380)
Location: mm/mincore.c:232
Inline: False
Direct callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
```
**Symbols:**

```
ffffffff813c1380-ffffffff813c1552: __do_sys_mincore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mincore.c (ffffffff813f60f2)
Location: mm/mincore.c:232
Inline: True
Inline callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mincore.c (ffffffff81421da2)
Location: mm/mincore.c:232
Inline: True
Inline callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
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
long int __do_sys_mincore(long unsigned int start, size_t len, unsigned char *vec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mincore.c (ffff8000102fd108)
Location: mm/mincore.c:252
Inline: False
Direct callers:
  - mm/mincore.c:__arm64_sys_mincore
```
**Symbols:**

```
ffff8000102fd108-ffff8000102fd4e0: __do_sys_mincore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mincore.c (c051c738)
Location: mm/mincore.c:252
Inline: True
Inline callers:
  - mm/mincore.c:__se_sys_mincore
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
In mm/mincore.c (c0000000003c7fb8)
Location: mm/mincore.c:252
Inline: True
Inline callers:
  - mm/mincore.c:__se_sys_mincore
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
In mm/mincore.c (ffffffe00020bc94)
Location: mm/mincore.c:252
Inline: True
Inline callers:
  - mm/mincore.c:__se_sys_mincore
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mincore.c (ffffffff8125e355)
Location: mm/mincore.c:252
Inline: True
Inline callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mincore.c (ffffffff812507e5)
Location: mm/mincore.c:252
Inline: True
Inline callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mincore.c (ffffffff8125c0f5)
Location: mm/mincore.c:252
Inline: True
Inline callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mincore.c (ffffffff8126bae5)
Location: mm/mincore.c:252
Inline: True
Inline callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
```
</details>
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
</ul>
<b>Arch</b>
<ul>
</ul>
