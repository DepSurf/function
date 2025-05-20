# Function: <code>xen_unpin_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int xen_unpin_page(struct mm_struct *mm, struct page *page, enum pt_level level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff810203d0)
Location: arch/x86/xen/mmu.c:888
Inline: True
Direct callers:
  - arch/x86/xen/mmu.c:__xen_pgd_unpin
```
**Symbols:**

```
ffffffff810203d0-ffffffff810204fa: xen_unpin_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int xen_unpin_page(struct mm_struct *mm, struct page *page, enum pt_level level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff810203c0)
Location: arch/x86/xen/mmu.c:889
Inline: True
Direct callers:
  - arch/x86/xen/mmu.c:__xen_pgd_unpin
```
**Symbols:**

```
ffffffff810203c0-ffffffff810204e1: xen_unpin_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int xen_unpin_page(struct mm_struct *mm, struct page *page, enum pt_level level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff81020a70)
Location: arch/x86/xen/mmu.c:889
Inline: True
Direct callers:
  - arch/x86/xen/mmu.c:__xen_pgd_unpin
```
**Symbols:**

```
ffffffff81020a70-ffffffff81020b8e: xen_unpin_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int xen_unpin_page(struct mm_struct *mm, struct page *page, enum pt_level level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81020d10)
Location: arch/x86/xen/mmu_pv.c:866
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
```
**Symbols:**

```
ffffffff81020d10-ffffffff81020e31: xen_unpin_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int xen_unpin_page(struct mm_struct *mm, struct page *page, enum pt_level level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810218b0)
Location: arch/x86/xen/mmu_pv.c:840
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
```
**Symbols:**

```
ffffffff810218b0-ffffffff810219d8: xen_unpin_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int xen_unpin_page(struct mm_struct *mm, struct page *page, enum pt_level level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81022360)
Location: arch/x86/xen/mmu_pv.c:869
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
```
**Symbols:**

```
ffffffff81022360-ffffffff810224cb: xen_unpin_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int xen_unpin_page(struct mm_struct *mm, struct page *page, enum pt_level level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81021cf0)
Location: arch/x86/xen/mmu_pv.c:879
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
```
**Symbols:**

```
ffffffff81021cf0-ffffffff81021e5b: xen_unpin_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int xen_unpin_page(struct mm_struct *mm, struct page *page, enum pt_level level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810250d0)
Location: arch/x86/xen/mmu_pv.c:879
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
```
**Symbols:**

```
ffffffff810250d0-ffffffff81025235: xen_unpin_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int xen_unpin_page(struct mm_struct *mm, struct page *page, enum pt_level level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810256b0)
Location: arch/x86/xen/mmu_pv.c:879
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
```
**Symbols:**

```
ffffffff810256b0-ffffffff81025815: xen_unpin_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int xen_unpin_page(struct mm_struct *mm, struct page *page, enum pt_level level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81027bb0)
Location: arch/x86/xen/mmu_pv.c:879
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
```
**Symbols:**

```
ffffffff81027bb0-ffffffff81027d15: xen_unpin_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void xen_unpin_page(struct mm_struct *mm, struct page *page, enum pt_level level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81027aa0)
Location: arch/x86/xen/mmu_pv.c:796
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
```
**Symbols:**

```
ffffffff81027aa0-ffffffff81027be8: xen_unpin_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void xen_unpin_page(struct mm_struct *mm, struct page *page, enum pt_level level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8102a140)
Location: arch/x86/xen/mmu_pv.c:796
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
```
**Symbols:**

```
ffffffff8102a140-ffffffff8102a284: xen_unpin_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void xen_unpin_page(struct mm_struct *mm, struct page *page, enum pt_level level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8102e730)
Location: arch/x86/xen/mmu_pv.c:796
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
```
**Symbols:**

```
ffffffff8102e730-ffffffff8102e871: xen_unpin_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void xen_unpin_page(struct mm_struct *mm, struct page *page, enum pt_level level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81033870)
Location: arch/x86/xen/mmu_pv.c:802
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
```
**Symbols:**

```
ffffffff81033870-ffffffff810339f1: xen_unpin_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void xen_unpin_page(struct mm_struct *mm, struct page *page, enum pt_level level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8103b2b0)
Location: arch/x86/xen/mmu_pv.c:802
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
```
**Symbols:**

```
ffffffff8103b2b0-ffffffff8103b440: xen_unpin_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void xen_unpin_page(struct mm_struct *mm, struct page *page, enum pt_level level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8103b380)
Location: arch/x86/xen/mmu_pv.c:818
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
```
**Symbols:**

```
ffffffff8103b380-ffffffff8103b515: xen_unpin_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void xen_unpin_page(struct mm_struct *mm, struct page *page, enum pt_level level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81041840)
Location: arch/x86/xen/mmu_pv.c:818
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
```
**Symbols:**

```
ffffffff81041840-ffffffff810419d5: xen_unpin_page (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int xen_unpin_page(struct mm_struct *mm, struct page *page, enum pt_level level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81025810)
Location: arch/x86/xen/mmu_pv.c:879
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
```
**Symbols:**

```
ffffffff81025810-ffffffff81025975: xen_unpin_page (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int xen_unpin_page(struct mm_struct *mm, struct page *page, enum pt_level level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81025670)
Location: arch/x86/xen/mmu_pv.c:879
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
```
**Symbols:**

```
ffffffff81025670-ffffffff810257d5: xen_unpin_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int xen_unpin_page(struct mm_struct *mm, struct page *page, enum pt_level level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810260f0)
Location: arch/x86/xen/mmu_pv.c:879
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
```
**Symbols:**

```
ffffffff810260f0-ffffffff8102626a: xen_unpin_page (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
