# Function: <code>check_hwpoisoned_entry</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int check_hwpoisoned_entry(pte_t pte, long unsigned int addr, short int shift, long unsigned int poisoned_pfn, struct to_kill *tk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff8135eb20)
Location: mm/memory-failure.c:581
Inline: False
Direct callers:
  - mm/memory-failure.c:hwpoison_hugetlb_range
  - mm/memory-failure.c:hwpoison_pte_range
```
**Symbols:**

```
ffffffff8135eb20-ffffffff8135ec12: check_hwpoisoned_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int check_hwpoisoned_entry(pte_t pte, long unsigned int addr, short int shift, long unsigned int poisoned_pfn, struct to_kill *tk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff813d8fa0)
Location: mm/memory-failure.c:578
Inline: False
Direct callers:
  - mm/memory-failure.c:hwpoison_hugetlb_range
  - mm/memory-failure.c:hwpoison_pte_range
```
**Symbols:**

```
ffffffff813d8fa0-ffffffff813d90ab: check_hwpoisoned_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int check_hwpoisoned_entry(pte_t pte, long unsigned int addr, short int shift, long unsigned int poisoned_pfn, struct to_kill *tk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff8145ef90)
Location: mm/memory-failure.c:640
Inline: False
Direct callers:
  - mm/memory-failure.c:hwpoison_hugetlb_range
  - mm/memory-failure.c:hwpoison_pte_range
```
**Symbols:**

```
ffffffff8145ef90-ffffffff8145f0b1: check_hwpoisoned_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int check_hwpoisoned_entry(pte_t pte, long unsigned int addr, short int shift, long unsigned int poisoned_pfn, struct to_kill *tk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81494f40)
Location: mm/memory-failure.c:736
Inline: False
Direct callers:
  - mm/memory-failure.c:hwpoison_hugetlb_range
  - mm/memory-failure.c:hwpoison_pte_range
```
**Symbols:**

```
ffffffff81494f40-ffffffff81495061: check_hwpoisoned_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int check_hwpoisoned_entry(pte_t pte, long unsigned int addr, short int shift, long unsigned int poisoned_pfn, struct to_kill *tk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff814c4840)
Location: mm/memory-failure.c:738
Inline: False
Direct callers:
  - mm/memory-failure.c:hwpoison_hugetlb_range
  - mm/memory-failure.c:hwpoison_pte_range
```
**Symbols:**

```
ffffffff814c4840-ffffffff814c4961: check_hwpoisoned_entry (STB_LOCAL)
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
