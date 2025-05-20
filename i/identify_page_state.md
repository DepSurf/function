# Function: <code>identify_page_state</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int identify_page_state(long unsigned int pfn, struct page *p, long unsigned int page_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff812443b0)
Location: mm/memory-failure.c:1025
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff812443b0-ffffffff812444cd: identify_page_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int identify_page_state(long unsigned int pfn, struct page *p, long unsigned int page_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81264230)
Location: mm/memory-failure.c:1025
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff81264230-ffffffff81264353: identify_page_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int identify_page_state(long unsigned int pfn, struct page *p, long unsigned int page_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:1058
Inline: False
```
**Symbols:**

```
ffffffff81288490-ffffffff812885a4: identify_page_state (STB_LOCAL)
ffffffff8128a94c-ffffffff8128a97d: identify_page_state.cold.37 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int identify_page_state(long unsigned int pfn, struct page *p, long unsigned int page_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:1060
Inline: False
```
**Symbols:**

```
ffffffff8129d460-ffffffff8129d574: identify_page_state (STB_LOCAL)
ffffffff8129f8b3-ffffffff8129f8e4: identify_page_state.cold.38 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int identify_page_state(long unsigned int pfn, struct page *p, long unsigned int page_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:1057
Inline: False
```
**Symbols:**

```
ffffffff812b8550-ffffffff812b8666: identify_page_state (STB_LOCAL)
ffffffff812baaae-ffffffff812baadf: identify_page_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int identify_page_state(long unsigned int pfn, struct page *p, long unsigned int page_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:1061
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff812ca430-ffffffff812ca546: identify_page_state (STB_LOCAL)
ffffffff812cc98a-ffffffff812cc9bb: identify_page_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int identify_page_state(long unsigned int pfn, struct page *p, long unsigned int page_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:1084
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
```
**Symbols:**

```
ffffffff81300570-ffffffff81300689: identify_page_state (STB_LOCAL)
ffffffff81302c95-ffffffff81302cc6: identify_page_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int identify_page_state(long unsigned int pfn, struct page *p, long unsigned int page_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:1175
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
```
**Symbols:**

```
ffffffff8130c710-ffffffff8130c829: identify_page_state (STB_LOCAL)
ffffffff81be9fd0-ffffffff81bea001: identify_page_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int identify_page_state(long unsigned int pfn, struct page *p, long unsigned int page_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:1235
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
```
**Symbols:**

```
ffffffff81312dd0-ffffffff81312ee6: identify_page_state (STB_LOCAL)
ffffffff81bdbfa3-ffffffff81bdbfd4: identify_page_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int identify_page_state(long unsigned int pfn, struct page *p, long unsigned int page_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff8135e920)
Location: mm/memory-failure.c:1377
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
```
**Symbols:**

```
ffffffff8135e920-ffffffff8135ea7b: identify_page_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int identify_page_state(long unsigned int pfn, struct page *p, long unsigned int page_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff813d8c20)
Location: mm/memory-failure.c:1462
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:try_memory_failure_hugetlb
```
**Symbols:**

```
ffffffff813d8c20-ffffffff813d8ced: identify_page_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int identify_page_state(long unsigned int pfn, struct page *p, long unsigned int page_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff8145eec0)
Location: mm/memory-failure.c:1523
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:try_memory_failure_hugetlb
```
**Symbols:**

```
ffffffff8145eec0-ffffffff8145ef73: identify_page_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int identify_page_state(long unsigned int pfn, struct page *p, long unsigned int page_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81494e70)
Location: mm/memory-failure.c:1651
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:try_memory_failure_hugetlb
```
**Symbols:**

```
ffffffff81494e70-ffffffff81494f23: identify_page_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int identify_page_state(long unsigned int pfn, struct page *p, long unsigned int page_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff814c4770)
Location: mm/memory-failure.c:1662
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:try_memory_failure_hugetlb
```
**Symbols:**

```
ffffffff814c4770-ffffffff814c4823: identify_page_state (STB_LOCAL)
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
int identify_page_state(long unsigned int pfn, struct page *p, long unsigned int page_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffff80001036e118)
Location: mm/memory-failure.c:1061
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffff80001036e118-ffff80001036e294: identify_page_state (STB_LOCAL)
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
int identify_page_state(long unsigned int pfn, struct page *p, long unsigned int page_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (c00000000045e500)
Location: mm/memory-failure.c:1061
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
c00000000045e500-c00000000045e70c: identify_page_state (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int identify_page_state(long unsigned int pfn, struct page *p, long unsigned int page_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:1061
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff812c2a10-ffffffff812c2b26: identify_page_state (STB_LOCAL)
ffffffff812c4f6a-ffffffff812c4f9b: identify_page_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int identify_page_state(long unsigned int pfn, struct page *p, long unsigned int page_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:1061
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff812b3a60-ffffffff812b3b76: identify_page_state (STB_LOCAL)
ffffffff812b5faa-ffffffff812b5fdb: identify_page_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int identify_page_state(long unsigned int pfn, struct page *p, long unsigned int page_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:1061
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff812c0820-ffffffff812c0936: identify_page_state (STB_LOCAL)
ffffffff812c2d7a-ffffffff812c2dab: identify_page_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int identify_page_state(long unsigned int pfn, struct page *p, long unsigned int page_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:1061
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff812d12e0-ffffffff812d13f6: identify_page_state (STB_LOCAL)
ffffffff812d381a-ffffffff812d384b: identify_page_state.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
