# Function: <code>mminit_validate_memmodel_limits</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void mminit_validate_memmodel_limits(long unsigned int *start_pfn, long unsigned int *end_pfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8181eebf)
Location: mm/sparse.c:144
Inline: True
Direct callers:
  - mm/sparse.c:node_memmap_size_bytes
  - mm/sparse.c:memory_present
```
**Symbols:**

```
ffffffff8181eebf-ffffffff8181ef47: mminit_validate_memmodel_limits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void mminit_validate_memmodel_limits(long unsigned int *start_pfn, long unsigned int *end_pfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff818993e1)
Location: mm/sparse.c:146
Inline: True
Direct callers:
  - mm/sparse.c:memory_present
  - mm/sparse.c:node_memmap_size_bytes
```
**Symbols:**

```
ffffffff818993e1-ffffffff81899469: mminit_validate_memmodel_limits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void mminit_validate_memmodel_limits(long unsigned int *start_pfn, long unsigned int *end_pfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff818cda99)
Location: mm/sparse.c:146
Inline: True
Direct callers:
  - mm/sparse.c:memory_present
  - mm/sparse.c:node_memmap_size_bytes
```
**Symbols:**

```
ffffffff818cda99-ffffffff818cdb21: mminit_validate_memmodel_limits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void mminit_validate_memmodel_limits(long unsigned int *start_pfn, long unsigned int *end_pfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81904f93)
Location: mm/sparse.c:146
Inline: True
Direct callers:
  - mm/sparse.c:memory_present
  - mm/sparse.c:node_memmap_size_bytes
```
**Symbols:**

```
ffffffff81904f93-ffffffff81904fbc: mminit_validate_memmodel_limits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void mminit_validate_memmodel_limits(long unsigned int *start_pfn, long unsigned int *end_pfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8198ef67)
Location: mm/sparse.c:142
Inline: True
Direct callers:
  - mm/sparse.c:memory_present
  - mm/sparse.c:node_memmap_size_bytes
```
**Symbols:**

```
ffffffff8198ef67-ffffffff8198ef90: mminit_validate_memmodel_limits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void mminit_validate_memmodel_limits(long unsigned int *start_pfn, long unsigned int *end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff819eb816)
Location: mm/sparse.c:142
Inline: False
Direct callers:
  - mm/sparse.c:memory_present
```
**Symbols:**

```
ffffffff819eb816-ffffffff819eb83e: mminit_validate_memmodel_limits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void mminit_validate_memmodel_limits(long unsigned int *start_pfn, long unsigned int *end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81a26aa6)
Location: mm/sparse.c:143
Inline: False
Direct callers:
  - mm/sparse.c:memory_present
```
**Symbols:**

```
ffffffff81a26aa6-ffffffff81a26ace: mminit_validate_memmodel_limits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void mminit_validate_memmodel_limits(long unsigned int *start_pfn, long unsigned int *end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81a97261)
Location: mm/sparse.c:154
Inline: False
Direct callers:
  - mm/sparse.c:memory_present
```
**Symbols:**

```
ffffffff81a97261-ffffffff81a97283: mminit_validate_memmodel_limits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void mminit_validate_memmodel_limits(long unsigned int *start_pfn, long unsigned int *end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81aceb18)
Location: mm/sparse.c:156
Inline: False
Direct callers:
  - mm/sparse.c:memory_present
```
**Symbols:**

```
ffffffff81aceb18-ffffffff81aceb3a: mminit_validate_memmodel_limits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mminit_validate_memmodel_limits(long unsigned int *start_pfn, long unsigned int *end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81bc762b)
Location: mm/sparse.c:155
Inline: False
Direct callers:
  - mm/sparse.c:memory_present
```
**Symbols:**

```
ffffffff81bc762b-ffffffff81bc766a: mminit_validate_memmodel_limits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mminit_validate_memmodel_limits(long unsigned int *start_pfn, long unsigned int *end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81c40357)
Location: mm/sparse.c:154
Inline: False
Direct callers:
  - mm/sparse.c:memory_present
```
**Symbols:**

```
ffffffff81c40357-ffffffff81c40396: mminit_validate_memmodel_limits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mminit_validate_memmodel_limits(long unsigned int *start_pfn, long unsigned int *end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81c322ce)
Location: mm/sparse.c:154
Inline: False
Direct callers:
  - mm/sparse.c:memory_present
```
**Symbols:**

```
ffffffff81c322ce-ffffffff81c3230d: mminit_validate_memmodel_limits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mminit_validate_memmodel_limits(long unsigned int *start_pfn, long unsigned int *end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81d50cce)
Location: mm/sparse.c:129
Inline: False
Direct callers:
  - mm/sparse.c:memory_present
```
**Symbols:**

```
ffffffff81d50cce-ffffffff81d50d09: mminit_validate_memmodel_limits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff83491b37)
Location: mm/sparse.c:129
Inline: True
Inline callers:
  - mm/sparse.c:memory_present
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff83ec4bf4)
Location: mm/sparse.c:129
Inline: True
Inline callers:
  - mm/sparse.c:memory_present
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
In mm/sparse.c (ffffffff836e9d04)
Location: mm/sparse.c:129
Inline: True
Inline callers:
  - mm/sparse.c:memory_present
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
In mm/sparse.c (ffffffff8391d0c4)
Location: mm/sparse.c:129
Inline: True
Inline callers:
  - mm/sparse.c:memory_present
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
void mminit_validate_memmodel_limits(long unsigned int *start_pfn, long unsigned int *end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffff800010da068c)
Location: mm/sparse.c:156
Inline: False
Direct callers:
  - mm/sparse.c:memory_present
```
**Symbols:**

```
ffff800010da068c-ffff800010da06c4: mminit_validate_memmodel_limits (STB_GLOBAL)
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
void mminit_validate_memmodel_limits(long unsigned int *start_pfn, long unsigned int *end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (c000000000eed578)
Location: mm/sparse.c:156
Inline: False
Direct callers:
  - mm/sparse.c:memory_present
```
**Symbols:**

```
c000000000eed578-c000000000eed5b4: mminit_validate_memmodel_limits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void mminit_validate_memmodel_limits(long unsigned int *start_pfn, long unsigned int *end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffe000048cc6)
Location: mm/sparse.c:156
Inline: False
Direct callers:
  - mm/sparse.c:memory_present
```
**Symbols:**

```
ffffffe000048cc6-ffffffe000048cee: mminit_validate_memmodel_limits (STB_GLOBAL)
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
void mminit_validate_memmodel_limits(long unsigned int *start_pfn, long unsigned int *end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81a6d988)
Location: mm/sparse.c:156
Inline: False
Direct callers:
  - mm/sparse.c:memory_present
```
**Symbols:**

```
ffffffff81a6d988-ffffffff81a6d9aa: mminit_validate_memmodel_limits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void mminit_validate_memmodel_limits(long unsigned int *start_pfn, long unsigned int *end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81a29ecf)
Location: mm/sparse.c:156
Inline: False
Direct callers:
  - mm/sparse.c:memory_present
```
**Symbols:**

```
ffffffff81a29ecf-ffffffff81a29ef1: mminit_validate_memmodel_limits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void mminit_validate_memmodel_limits(long unsigned int *start_pfn, long unsigned int *end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81ad9d98)
Location: mm/sparse.c:156
Inline: False
Direct callers:
  - mm/sparse.c:memory_present
```
**Symbols:**

```
ffffffff81ad9d98-ffffffff81ad9dba: mminit_validate_memmodel_limits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void mminit_validate_memmodel_limits(long unsigned int *start_pfn, long unsigned int *end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81ae624e)
Location: mm/sparse.c:156
Inline: False
Direct callers:
  - mm/sparse.c:memory_present
```
**Symbols:**

```
ffffffff81ae624e-ffffffff81ae6270: mminit_validate_memmodel_limits (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
