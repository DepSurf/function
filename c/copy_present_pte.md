# Function: <code>copy_present_pte</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812999a4)
Location: mm/memory.c:851
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129ebc6)
Location: mm/memory.c:862
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812dfe09)
Location: mm/memory.c:936
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int copy_present_pte(struct vm_area_struct *dst_vma, struct vm_area_struct *src_vma, pte_t *dst_pte, pte_t *src_pte, long unsigned int addr, int *rss, struct page **prealloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813401a0)
Location: mm/memory.c:934
Inline: False
Direct callers:
  - mm/memory.c:copy_pte_range
```
**Symbols:**

```
ffffffff813401a0-ffffffff8134042b: copy_present_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int copy_present_pte(struct vm_area_struct *dst_vma, struct vm_area_struct *src_vma, pte_t *dst_pte, pte_t *src_pte, long unsigned int addr, int *rss, struct page **prealloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813b8130)
Location: mm/memory.c:891
Inline: False
Direct callers:
  - mm/memory.c:copy_pte_range
```
**Symbols:**

```
ffffffff813b8130-ffffffff813b83bb: copy_present_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int copy_present_pte(struct vm_area_struct *dst_vma, struct vm_area_struct *src_vma, pte_t *dst_pte, pte_t *src_pte, long unsigned int addr, int *rss, struct folio **prealloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813ecf00)
Location: mm/memory.c:923
Inline: False
Direct callers:
  - mm/memory.c:copy_pte_range
```
**Symbols:**

```
ffffffff813ecf00-ffffffff813ed18a: copy_present_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int copy_present_pte(struct vm_area_struct *dst_vma, struct vm_area_struct *src_vma, pte_t *dst_pte, pte_t *src_pte, long unsigned int addr, int *rss, struct folio **prealloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81418460)
Location: mm/memory.c:938
Inline: False
Direct callers:
  - mm/memory.c:copy_pte_range
```
**Symbols:**

```
ffffffff81418460-ffffffff8141875c: copy_present_pte (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct page **prealloc</code> ➡️ <code>struct folio **prealloc</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
