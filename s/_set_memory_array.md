# Function: <code>_set_memory_array</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int _set_memory_array(long unsigned int *addr, int addrinarray, enum page_cache_mode new_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8106e750)
Location: arch/x86/mm/pageattr.c:1532
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:set_memory_array_uc
  - arch/x86/mm/pageattr.c:set_memory_array_wc
  - arch/x86/mm/pageattr.c:set_memory_array_wt
```
**Symbols:**

```
ffffffff8106e750-ffffffff8106e932: _set_memory_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int _set_memory_array(long unsigned int *addr, int addrinarray, enum page_cache_mode new_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8106e520)
Location: arch/x86/mm/pageattr.c:1540
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:set_memory_array_wt
  - arch/x86/mm/pageattr.c:set_memory_array_wc
  - arch/x86/mm/pageattr.c:set_memory_array_uc
```
**Symbols:**

```
ffffffff8106e520-ffffffff8106e6f1: _set_memory_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int _set_memory_array(long unsigned int *addr, int addrinarray, enum page_cache_mode new_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810721d0)
Location: arch/x86/mm/pageattr.c:1540
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:set_memory_array_wt
  - arch/x86/mm/pageattr.c:set_memory_array_wc
  - arch/x86/mm/pageattr.c:set_memory_array_uc
```
**Symbols:**

```
ffffffff810721d0-ffffffff810723a1: _set_memory_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int _set_memory_array(long unsigned int *addr, int addrinarray, enum page_cache_mode new_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81071810)
Location: arch/x86/mm/pageattr.c:1586
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:set_memory_array_wt
  - arch/x86/mm/pageattr.c:set_memory_array_wc
  - arch/x86/mm/pageattr.c:set_memory_array_uc
```
**Symbols:**

```
ffffffff81071810-ffffffff810719a1: _set_memory_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int _set_memory_array(long unsigned int *addr, int addrinarray, enum page_cache_mode new_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81076eb0)
Location: arch/x86/mm/pageattr.c:1586
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:set_memory_array_wt
  - arch/x86/mm/pageattr.c:set_memory_array_wc
  - arch/x86/mm/pageattr.c:set_memory_array_uc
```
**Symbols:**

```
ffffffff81076eb0-ffffffff81077041: _set_memory_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int _set_memory_array(long unsigned int *addr, int addrinarray, enum page_cache_mode new_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81079920)
Location: arch/x86/mm/pageattr.c:1616
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:set_memory_array_wt
  - arch/x86/mm/pageattr.c:set_memory_array_wc
  - arch/x86/mm/pageattr.c:set_memory_array_uc
```
**Symbols:**

```
ffffffff81079920-ffffffff81079aad: _set_memory_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int _set_memory_array(long unsigned int *addr, int numpages, enum page_cache_mode new_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81080130)
Location: arch/x86/mm/pageattr.c:1811
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:set_memory_array_wt
  - arch/x86/mm/pageattr.c:set_memory_array_wc
  - arch/x86/mm/pageattr.c:set_memory_array_uc
```
**Symbols:**

```
ffffffff81080130-ffffffff810802bd: _set_memory_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int _set_memory_array(long unsigned int *addr, int numpages, enum page_cache_mode new_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81083bd0)
Location: arch/x86/mm/pageattr.c:1822
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:set_memory_array_wt
  - arch/x86/mm/pageattr.c:set_memory_array_wc
  - arch/x86/mm/pageattr.c:set_memory_array_uc
```
**Symbols:**

```
ffffffff81083bd0-ffffffff81083d79: _set_memory_array (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.4</code>: Absent ⚠️
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int numpages</code>
</li>
<li>
<b>Param removed. </b>
<code>int addrinarray</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
</ul>
