# Function: <code>do_set_pmd</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811da21e)
Location: mm/memory.c:2938
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811e9d4e)
Location: mm/memory.c:2959
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f4e50)
Location: mm/memory.c:3155
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8120cf50)
Location: mm/memory.c:3324
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8122db08)
Location: mm/memory.c:3369
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
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
In mm/memory.c (ffffffff8124128b)
Location: mm/memory.c:3129
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
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
In mm/memory.c (ffffffff81253746)
Location: mm/memory.c:3179
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
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
In mm/memory.c (ffffffff81261ca6)
Location: mm/memory.c:3204
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
vm_fault_t do_set_pmd(struct vm_fault *vmf, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8128c700)
Location: mm/memory.c:3570
Inline: False
Direct callers:
  - mm/memory.c:alloc_set_pte
```
**Symbols:**

```
ffffffff8128c700-ffffffff8128c977: do_set_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
vm_fault_t do_set_pmd(struct vm_fault *vmf, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81297990)
Location: mm/memory.c:3729
Inline: False
Direct callers:
  - mm/memory.c:alloc_set_pte
```
**Symbols:**

```
ffffffff81297990-ffffffff81297bec: do_set_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
vm_fault_t do_set_pmd(struct vm_fault *vmf, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812a1730)
Location: mm/memory.c:3758
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pmd
  - mm/memory.c:finish_fault
```
**Symbols:**

```
ffffffff812a1730-ffffffff812a198f: do_set_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
vm_fault_t do_set_pmd(struct vm_fault *vmf, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812e2700)
Location: mm/memory.c:3894
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pmd
  - mm/memory.c:finish_fault
```
**Symbols:**

```
ffffffff812e2700-ffffffff812e295a: do_set_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
vm_fault_t do_set_pmd(struct vm_fault *vmf, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81342f00)
Location: mm/memory.c:4210
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pmd
  - mm/memory.c:finish_fault
```
**Symbols:**

```
ffffffff81342f00-ffffffff813431d4: do_set_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
vm_fault_t do_set_pmd(struct vm_fault *vmf, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813baea0)
Location: mm/memory.c:4211
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pmd
  - mm/memory.c:finish_fault
  - mm/khugepaged.c:set_huge_pmd
```
**Symbols:**

```
ffffffff813baea0-ffffffff813bb116: do_set_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
vm_fault_t do_set_pmd(struct vm_fault *vmf, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813ef9c0)
Location: mm/memory.c:4243
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pmd
  - mm/memory.c:finish_fault
  - mm/khugepaged.c:set_huge_pmd
```
**Symbols:**

```
ffffffff813ef9c0-ffffffff813efc62: do_set_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
vm_fault_t do_set_pmd(struct vm_fault *vmf, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8141b000)
Location: mm/memory.c:4440
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pmd
  - mm/memory.c:finish_fault
  - mm/khugepaged.c:set_huge_pmd
```
**Symbols:**

```
ffffffff8141b000-ffffffff8141b26a: do_set_pmd (STB_GLOBAL)
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
In mm/memory.c (ffff8000102f8c34)
Location: mm/memory.c:3204
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003c2460)
Location: mm/memory.c:3204
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125a2f6)
Location: mm/memory.c:3204
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
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
In mm/memory.c (ffffffff8124c715)
Location: mm/memory.c:3204
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
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
In mm/memory.c (ffffffff81258096)
Location: mm/memory.c:3204
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
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
In mm/memory.c (ffffffff81267a80)
Location: mm/memory.c:3204
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
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
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
