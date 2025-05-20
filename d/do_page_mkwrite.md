# Function: <code>do_page_mkwrite</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int do_page_mkwrite(struct vm_area_struct *vma, struct page *page, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811bbd80)
Location: mm/memory.c:1958
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:handle_mm_fault
```
**Symbols:**

```
ffffffff811bbd80-ffffffff811bbe2c: do_page_mkwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int do_page_mkwrite(struct vm_area_struct *vma, struct page *page, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811d6b90)
Location: mm/memory.c:2037
Inline: False
Direct callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff811d6b90-ffffffff811d6c78: do_page_mkwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int do_page_mkwrite(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811e6870)
Location: mm/memory.c:2037
Inline: False
Direct callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff811e6870-ffffffff811e68fc: do_page_mkwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_page_mkwrite(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f1970)
Location: mm/memory.c:2243
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff811f1970-ffffffff811f19f9: do_page_mkwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_page_mkwrite(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812083f0)
Location: mm/memory.c:2360
Inline: False
Direct callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff812083f0-ffffffff8120847f: do_page_mkwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int do_page_mkwrite(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81229430)
Location: mm/memory.c:2402
Inline: False
Direct callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff81229430-ffffffff812294c0: do_page_mkwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
vm_fault_t do_page_mkwrite(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8123ca30)
Location: mm/memory.c:2138
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff8123ca30-ffffffff8123cac0: do_page_mkwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
vm_fault_t do_page_mkwrite(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8124e6a0)
Location: mm/memory.c:2192
Inline: False
Direct callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff8124e6a0-ffffffff8124e730: do_page_mkwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
vm_fault_t do_page_mkwrite(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125cc10)
Location: mm/memory.c:2197
Inline: False
Direct callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff8125cc10-ffffffff8125ccc5: do_page_mkwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
vm_fault_t do_page_mkwrite(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8128bd70)
Location: mm/memory.c:2526
Inline: False
Direct callers:
  - mm/memory.c:do_shared_fault
  - mm/memory.c:wp_page_shared
```
**Symbols:**

```
ffffffff8128bd70-ffffffff8128be25: do_page_mkwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
vm_fault_t do_page_mkwrite(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81296cf0)
Location: mm/memory.c:2703
Inline: False
Direct callers:
  - mm/memory.c:do_shared_fault
  - mm/memory.c:wp_page_shared
```
**Symbols:**

```
ffffffff81296cf0-ffffffff81296da5: do_page_mkwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
vm_fault_t do_page_mkwrite(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129c940)
Location: mm/memory.c:2764
Inline: False
Direct callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff8129c940-ffffffff8129c9f5: do_page_mkwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
vm_fault_t do_page_mkwrite(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812dd710)
Location: mm/memory.c:2859
Inline: False
Direct callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff812dd710-ffffffff812dd7c5: do_page_mkwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
vm_fault_t do_page_mkwrite(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8133d310)
Location: mm/memory.c:2952
Inline: False
Direct callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff8133d310-ffffffff8133d3c6: do_page_mkwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
vm_fault_t do_page_mkwrite(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813b4f80)
Location: mm/memory.c:2932
Inline: False
Direct callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff813b4f80-ffffffff813b5030: do_page_mkwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
vm_fault_t do_page_mkwrite(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813e9ca0)
Location: mm/memory.c:2931
Inline: False
Direct callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff813e9ca0-ffffffff813e9d53: do_page_mkwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
vm_fault_t do_page_mkwrite(struct vm_fault *vmf, struct folio *folio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81414b40)
Location: mm/memory.c:2956
Inline: False
Direct callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff81414b40-ffffffff81414bed: do_page_mkwrite (STB_LOCAL)
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
vm_fault_t do_page_mkwrite(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffff8000102f4338)
Location: mm/memory.c:2197
Inline: False
Direct callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffff8000102f4338-ffff8000102f4450: do_page_mkwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
vm_fault_t do_page_mkwrite(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0516bd4)
Location: mm/memory.c:2197
Inline: False
Direct callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
c0516bd4-c0516cf4: do_page_mkwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
vm_fault_t do_page_mkwrite(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003bac20)
Location: mm/memory.c:2197
Inline: False
Direct callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
c0000000003bac20-c0000000003bad68: do_page_mkwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
vm_fault_t do_page_mkwrite(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe000205edc)
Location: mm/memory.c:2197
Inline: False
Direct callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffe000205edc-ffffffe000205f8e: do_page_mkwrite (STB_LOCAL)
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
vm_fault_t do_page_mkwrite(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81255260)
Location: mm/memory.c:2197
Inline: False
Direct callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff81255260-ffffffff81255315: do_page_mkwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
vm_fault_t do_page_mkwrite(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81247b80)
Location: mm/memory.c:2197
Inline: False
Direct callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff81247b80-ffffffff81247c35: do_page_mkwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
vm_fault_t do_page_mkwrite(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81253000)
Location: mm/memory.c:2197
Inline: False
Direct callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff81253000-ffffffff812530b5: do_page_mkwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
vm_fault_t do_page_mkwrite(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81262960)
Location: mm/memory.c:2197
Inline: False
Direct callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff81262960-ffffffff81262a10: do_page_mkwrite (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vm_fault *vmf</code>
</li>
<li>
<b>Param removed. </b>
<code>struct vm_area_struct *vma</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *page</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int address</code>
</li>
</ul>
</details>
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
<b>Return type changed. </b>
<code>int</code> ➡️ <code>vm_fault_t</code>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio *folio</code>
</li>
</ul>
</details>
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
