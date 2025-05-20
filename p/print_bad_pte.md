# Function: <code>print_bad_pte</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void print_bad_pte(struct vm_area_struct *vma, long unsigned int addr, pte_t pte, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811bbe30)
Location: mm/memory.c:647
Inline: False
Direct callers:
  - mm/memory.c:vm_normal_page
  - mm/memory.c:vm_normal_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
```
**Symbols:**

```
ffffffff811bbe30-ffffffff811bc0cd: print_bad_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void print_bad_pte(struct vm_area_struct *vma, long unsigned int addr, pte_t pte, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811d68e0)
Location: mm/memory.c:652
Inline: False
Direct callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:vm_normal_page
  - mm/memory.c:vm_normal_page
```
**Symbols:**

```
ffffffff811d68e0-ffffffff811d6b8d: print_bad_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void print_bad_pte(struct vm_area_struct *vma, long unsigned int addr, pte_t pte, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811e65c0)
Location: mm/memory.c:654
Inline: False
Direct callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:vm_normal_page
  - mm/memory.c:vm_normal_page
```
**Symbols:**

```
ffffffff811e65c0-ffffffff811e686d: print_bad_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void print_bad_pte(struct vm_area_struct *vma, long unsigned int addr, pte_t pte, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f16c0)
Location: mm/memory.c:719
Inline: False
Direct callers:
  - mm/memory.c:vm_normal_page
  - mm/memory.c:vm_normal_page
```
**Symbols:**

```
ffffffff811f16c0-ffffffff811f1969: print_bad_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void print_bad_pte(struct vm_area_struct *vma, long unsigned int addr, pte_t pte, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81208480)
Location: mm/memory.c:721
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:_vm_normal_page
```
**Symbols:**

```
ffffffff81208480-ffffffff81208756: print_bad_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void print_bad_pte(struct vm_area_struct *vma, long unsigned int addr, pte_t pte, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:736
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:_vm_normal_page
```
**Symbols:**

```
ffffffff812294c0-ffffffff812296b0: print_bad_pte (STB_LOCAL)
ffffffff81231b80-ffffffff81231c43: print_bad_pte.cold.104 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void print_bad_pte(struct vm_area_struct *vma, long unsigned int addr, pte_t pte, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:479
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:_vm_normal_page
```
**Symbols:**

```
ffffffff8123cac0-ffffffff8123cca4: print_bad_pte (STB_LOCAL)
ffffffff81245350-ffffffff81245413: print_bad_pte.cold.95 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void print_bad_pte(struct vm_area_struct *vma, long unsigned int addr, pte_t pte, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:481
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:vm_normal_page
```
**Symbols:**

```
ffffffff8124e730-ffffffff8124e90f: print_bad_pte (STB_LOCAL)
ffffffff81257390-ffffffff8125745a: print_bad_pte.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void print_bad_pte(struct vm_area_struct *vma, long unsigned int addr, pte_t pte, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:481
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:vm_normal_page
```
**Symbols:**

```
ffffffff8125ccd0-ffffffff8125ceaf: print_bad_pte (STB_LOCAL)
ffffffff81265920-ffffffff812659ea: print_bad_pte.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void print_bad_pte(struct vm_area_struct *vma, long unsigned int addr, pte_t pte, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:499
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:vm_normal_page
```
**Symbols:**

```
ffffffff8128c980-ffffffff8128cbc8: print_bad_pte (STB_LOCAL)
ffffffff81295c20-ffffffff81295d0e: print_bad_pte.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void print_bad_pte(struct vm_area_struct *vma, long unsigned int addr, pte_t pte, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:501
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:vm_normal_page
```
**Symbols:**

```
ffffffff81297bf0-ffffffff81297df1: print_bad_pte (STB_LOCAL)
ffffffff81be787e-ffffffff81be7936: print_bad_pte.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void print_bad_pte(struct vm_area_struct *vma, long unsigned int addr, pte_t pte, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:513
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:vm_normal_page
```
**Symbols:**

```
ffffffff8129cae0-ffffffff8129ccaf: print_bad_pte (STB_LOCAL)
ffffffff81bd96d8-ffffffff81bd9797: print_bad_pte.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void print_bad_pte(struct vm_area_struct *vma, long unsigned int addr, pte_t pte, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:512
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:vm_normal_page
```
**Symbols:**

```
ffffffff812dd8b0-ffffffff812dda8b: print_bad_pte (STB_LOCAL)
ffffffff81cbc21e-ffffffff81cbc307: print_bad_pte.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void print_bad_pte(struct vm_area_struct *vma, long unsigned int addr, pte_t pte, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:519
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:vm_normal_page
```
**Symbols:**

```
ffffffff8133d3d0-ffffffff8133d5c8: print_bad_pte (STB_LOCAL)
ffffffff81e6dd98-ffffffff81e6de75: print_bad_pte.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void print_bad_pte(struct vm_area_struct *vma, long unsigned int addr, pte_t pte, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:472
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:vm_normal_page
```
**Symbols:**

```
ffffffff813b5bc0-ffffffff813b5e51: print_bad_pte (STB_LOCAL)
ffffffff82063ea0-ffffffff82063eb9: print_bad_pte.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void print_bad_pte(struct vm_area_struct *vma, long unsigned int addr, pte_t pte, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:491
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:vm_normal_page
```
**Symbols:**

```
ffffffff813ea160-ffffffff813ea3fd: print_bad_pte (STB_LOCAL)
ffffffff820e352e-ffffffff820e3547: print_bad_pte.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void print_bad_pte(struct vm_area_struct *vma, long unsigned int addr, pte_t pte, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:489
Inline: False
Direct callers:
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:vm_normal_page
```
**Symbols:**

```
ffffffff81414e10-ffffffff81415085: print_bad_pte (STB_LOCAL)
ffffffff821bff83-ffffffff821bff9c: print_bad_pte.cold (STB_LOCAL)
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
void print_bad_pte(struct vm_area_struct *vma, long unsigned int addr, pte_t pte, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffff8000102f3ca0)
Location: mm/memory.c:481
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:vm_normal_page
```
**Symbols:**

```
ffff8000102f3ca0-ffff8000102f3e8c: print_bad_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void print_bad_pte(struct vm_area_struct *vma, long unsigned int addr, pte_t pte, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c05163a4)
Location: mm/memory.c:481
Inline: False
Direct callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:vm_normal_page
```
**Symbols:**

```
c05163a4-c051654c: print_bad_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void print_bad_pte(struct vm_area_struct *vma, long unsigned int addr, pte_t pte, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003ba5d0)
Location: mm/memory.c:481
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:vm_normal_page
```
**Symbols:**

```
c0000000003ba5d0-c0000000003ba944: print_bad_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void print_bad_pte(struct vm_area_struct *vma, long unsigned int addr, pte_t pte, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe000205a0a)
Location: mm/memory.c:481
Inline: False
Direct callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:vm_normal_page
```
**Symbols:**

```
ffffffe000205a0a-ffffffe000205bda: print_bad_pte (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void print_bad_pte(struct vm_area_struct *vma, long unsigned int addr, pte_t pte, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:481
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:vm_normal_page
```
**Symbols:**

```
ffffffff81255320-ffffffff812554ff: print_bad_pte (STB_LOCAL)
ffffffff8125df70-ffffffff8125e03a: print_bad_pte.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void print_bad_pte(struct vm_area_struct *vma, long unsigned int addr, pte_t pte, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:481
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:vm_normal_page
```
**Symbols:**

```
ffffffff81247750-ffffffff812478da: print_bad_pte (STB_LOCAL)
ffffffff812503c0-ffffffff812504be: print_bad_pte.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void print_bad_pte(struct vm_area_struct *vma, long unsigned int addr, pte_t pte, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:481
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:vm_normal_page
```
**Symbols:**

```
ffffffff812530c0-ffffffff8125329f: print_bad_pte (STB_LOCAL)
ffffffff8125bd10-ffffffff8125bdda: print_bad_pte.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void print_bad_pte(struct vm_area_struct *vma, long unsigned int addr, pte_t pte, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:481
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:vm_normal_page
```
**Symbols:**

```
ffffffff81262ad0-ffffffff81262caf: print_bad_pte (STB_LOCAL)
ffffffff8126b6f9-ffffffff8126b7c3: print_bad_pte.cold (STB_LOCAL)
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
