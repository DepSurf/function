# Function: <code>_set_pages_array</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int _set_pages_array(struct page **pages, int addrinarray, enum page_cache_mode new_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8106eae0)
Location: arch/x86/mm/pageattr.c:1732
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:set_pages_array_uc
  - arch/x86/mm/pageattr.c:set_pages_array_wc
  - arch/x86/mm/pageattr.c:set_pages_array_wt
```
**Symbols:**

```
ffffffff8106eae0-ffffffff8106ec60: _set_pages_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int _set_pages_array(struct page **pages, int addrinarray, enum page_cache_mode new_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8106e890)
Location: arch/x86/mm/pageattr.c:1740
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:set_pages_array_wt
  - arch/x86/mm/pageattr.c:set_pages_array_wc
  - arch/x86/mm/pageattr.c:set_pages_array_uc
```
**Symbols:**

```
ffffffff8106e890-ffffffff8106ea11: _set_pages_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int _set_pages_array(struct page **pages, int addrinarray, enum page_cache_mode new_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81072540)
Location: arch/x86/mm/pageattr.c:1740
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:set_pages_array_wt
  - arch/x86/mm/pageattr.c:set_pages_array_wc
  - arch/x86/mm/pageattr.c:set_pages_array_uc
```
**Symbols:**

```
ffffffff81072540-ffffffff8107269c: _set_pages_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int _set_pages_array(struct page **pages, int addrinarray, enum page_cache_mode new_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81071b20)
Location: arch/x86/mm/pageattr.c:1786
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:set_pages_array_wt
  - arch/x86/mm/pageattr.c:set_pages_array_wc
  - arch/x86/mm/pageattr.c:set_pages_array_uc
```
**Symbols:**

```
ffffffff81071b20-ffffffff81071c4d: _set_pages_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int _set_pages_array(struct page **pages, int addrinarray, enum page_cache_mode new_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810771c0)
Location: arch/x86/mm/pageattr.c:1850
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:set_pages_array_wt
  - arch/x86/mm/pageattr.c:set_pages_array_wc
  - arch/x86/mm/pageattr.c:set_pages_array_uc
```
**Symbols:**

```
ffffffff810771c0-ffffffff810772ed: _set_pages_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int _set_pages_array(struct page **pages, int addrinarray, enum page_cache_mode new_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81079c20)
Location: arch/x86/mm/pageattr.c:1901
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:set_pages_array_wt
  - arch/x86/mm/pageattr.c:set_pages_array_wc
  - arch/x86/mm/pageattr.c:set_pages_array_uc
```
**Symbols:**

```
ffffffff81079c20-ffffffff81079d5d: _set_pages_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int _set_pages_array(struct page **pages, int numpages, enum page_cache_mode new_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81080430)
Location: arch/x86/mm/pageattr.c:2085
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:set_pages_array_wt
  - arch/x86/mm/pageattr.c:set_pages_array_wc
  - arch/x86/mm/pageattr.c:set_pages_array_uc
```
**Symbols:**

```
ffffffff81080430-ffffffff8108056d: _set_pages_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int _set_pages_array(struct page **pages, int numpages, enum page_cache_mode new_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81083ef0)
Location: arch/x86/mm/pageattr.c:2096
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:set_pages_array_wt
  - arch/x86/mm/pageattr.c:set_pages_array_wc
  - arch/x86/mm/pageattr.c:set_pages_array_uc
```
**Symbols:**

```
ffffffff81083ef0-ffffffff81084051: _set_pages_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int _set_pages_array(struct page **pages, int numpages, enum page_cache_mode new_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81084c30)
Location: arch/x86/mm/pageattr.c:2002
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:set_pages_array_wt
  - arch/x86/mm/pageattr.c:set_pages_array_wc
  - arch/x86/mm/pageattr.c:set_pages_array_uc
```
**Symbols:**

```
ffffffff81084c30-ffffffff81084d91: _set_pages_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int _set_pages_array(struct page **pages, int numpages, enum page_cache_mode new_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108e800)
Location: arch/x86/mm/pat/set_memory.c:2038
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:set_pages_array_wt
  - arch/x86/mm/pat/set_memory.c:set_pages_array_wc
  - arch/x86/mm/pat/set_memory.c:set_pages_array_uc
```
**Symbols:**

```
ffffffff8108e800-ffffffff8108e93b: _set_pages_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int _set_pages_array(struct page **pages, int numpages, enum page_cache_mode new_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108e5d0)
Location: arch/x86/mm/pat/set_memory.c:2038
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:set_pages_array_wt
  - arch/x86/mm/pat/set_memory.c:set_pages_array_wc
  - arch/x86/mm/pat/set_memory.c:set_pages_array_uc
```
**Symbols:**

```
ffffffff8108e5d0-ffffffff8108e70b: _set_pages_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int _set_pages_array(struct page **pages, int numpages, enum page_cache_mode new_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108f180)
Location: arch/x86/mm/pat/set_memory.c:2046
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:set_pages_array_wt
  - arch/x86/mm/pat/set_memory.c:set_pages_array_wc
  - arch/x86/mm/pat/set_memory.c:set_pages_array_uc
```
**Symbols:**

```
ffffffff8108f180-ffffffff8108f2bb: _set_pages_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int _set_pages_array(struct page **pages, int numpages, enum page_cache_mode new_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8109ec30)
Location: arch/x86/mm/pat/set_memory.c:2046
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:set_pages_array_wt
  - arch/x86/mm/pat/set_memory.c:set_pages_array_wc
  - arch/x86/mm/pat/set_memory.c:set_pages_array_uc
```
**Symbols:**

```
ffffffff8109ec30-ffffffff8109ed6b: _set_pages_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int _set_pages_array(struct page **pages, int numpages, enum page_cache_mode new_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810b2660)
Location: arch/x86/mm/pat/set_memory.c:2103
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:set_pages_array_wc
  - arch/x86/mm/pat/set_memory.c:set_pages_array_uc
```
**Symbols:**

```
ffffffff810b2660-ffffffff810b27aa: _set_pages_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int _set_pages_array(struct page **pages, int numpages, enum page_cache_mode new_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810ccfa0)
Location: arch/x86/mm/pat/set_memory.c:2207
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:set_pages_array_wc
  - arch/x86/mm/pat/set_memory.c:set_pages_array_uc
```
**Symbols:**

```
ffffffff810ccfa0-ffffffff810cd0ea: _set_pages_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int _set_pages_array(struct page **pages, int numpages, enum page_cache_mode new_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810d05d0)
Location: arch/x86/mm/pat/set_memory.c:2206
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:set_pages_array_wc
  - arch/x86/mm/pat/set_memory.c:set_pages_array_uc
```
**Symbols:**

```
ffffffff810d05d0-ffffffff810d071a: _set_pages_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int _set_pages_array(struct page **pages, int numpages, enum page_cache_mode new_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810d8cb0)
Location: arch/x86/mm/pat/set_memory.c:2210
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:set_pages_array_wc
  - arch/x86/mm/pat/set_memory.c:set_pages_array_uc
```
**Symbols:**

```
ffffffff810d8cb0-ffffffff810d8dfa: _set_pages_array (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int _set_pages_array(struct page **pages, int numpages, enum page_cache_mode new_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81083c30)
Location: arch/x86/mm/pageattr.c:2002
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:set_pages_array_wt
  - arch/x86/mm/pageattr.c:set_pages_array_wc
  - arch/x86/mm/pageattr.c:set_pages_array_uc
```
**Symbols:**

```
ffffffff81083c30-ffffffff81083d91: _set_pages_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int _set_pages_array(struct page **pages, int numpages, enum page_cache_mode new_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81072880)
Location: arch/x86/mm/pageattr.c:2002
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:set_pages_array_wt
  - arch/x86/mm/pageattr.c:set_pages_array_wc
  - arch/x86/mm/pageattr.c:set_pages_array_uc
```
**Symbols:**

```
ffffffff81072880-ffffffff810729e1: _set_pages_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int _set_pages_array(struct page **pages, int numpages, enum page_cache_mode new_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81083be0)
Location: arch/x86/mm/pageattr.c:2002
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:set_pages_array_wt
  - arch/x86/mm/pageattr.c:set_pages_array_wc
  - arch/x86/mm/pageattr.c:set_pages_array_uc
```
**Symbols:**

```
ffffffff81083be0-ffffffff81083d41: _set_pages_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int _set_pages_array(struct page **pages, int numpages, enum page_cache_mode new_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81085d20)
Location: arch/x86/mm/pageattr.c:2002
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:set_pages_array_wt
  - arch/x86/mm/pageattr.c:set_pages_array_wc
  - arch/x86/mm/pageattr.c:set_pages_array_uc
```
**Symbols:**

```
ffffffff81085d20-ffffffff81085e81: _set_pages_array (STB_LOCAL)
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
