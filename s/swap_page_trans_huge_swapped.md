# Function: <code>swap_page_trans_huge_swapped</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool swap_page_trans_huge_swapped(struct swap_info_struct *si, swp_entry_t entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812274e0)
Location: mm/swapfile.c:1413
Inline: False
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:free_swap_and_cache
```
**Symbols:**

```
ffffffff812274e0-ffffffff812275b3: swap_page_trans_huge_swapped (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool swap_page_trans_huge_swapped(struct swap_info_struct *si, swp_entry_t entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81249040)
Location: mm/swapfile.c:1413
Inline: False
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:free_swap_and_cache
```
**Symbols:**

```
ffffffff81249040-ffffffff81249113: swap_page_trans_huge_swapped (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool swap_page_trans_huge_swapped(struct swap_info_struct *si, swp_entry_t entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8125dd00)
Location: mm/swapfile.c:1429
Inline: False
Direct callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:free_swap_and_cache
```
**Symbols:**

```
ffffffff8125dd00-ffffffff8125ddcd: swap_page_trans_huge_swapped (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool swap_page_trans_huge_swapped(struct swap_info_struct *si, swp_entry_t entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81278e80)
Location: mm/swapfile.c:1538
Inline: False
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
```
**Symbols:**

```
ffffffff81278e80-ffffffff81278f55: swap_page_trans_huge_swapped (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool swap_page_trans_huge_swapped(struct swap_info_struct *si, swp_entry_t entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81288960)
Location: mm/swapfile.c:1538
Inline: False
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
```
**Symbols:**

```
ffffffff81288960-ffffffff81288a35: swap_page_trans_huge_swapped (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool swap_page_trans_huge_swapped(struct swap_info_struct *si, swp_entry_t entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812bb250)
Location: mm/swapfile.c:1575
Inline: False
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
```
**Symbols:**

```
ffffffff812bb250-ffffffff812bb325: swap_page_trans_huge_swapped (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool swap_page_trans_huge_swapped(struct swap_info_struct *si, swp_entry_t entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812c6cf0)
Location: mm/swapfile.c:1593
Inline: False
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
```
**Symbols:**

```
ffffffff812c6cf0-ffffffff812c6dc5: swap_page_trans_huge_swapped (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool swap_page_trans_huge_swapped(struct swap_info_struct *si, swp_entry_t entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812cd890)
Location: mm/swapfile.c:1592
Inline: False
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
```
**Symbols:**

```
ffffffff812cd890-ffffffff812cd968: swap_page_trans_huge_swapped (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool swap_page_trans_huge_swapped(struct swap_info_struct *si, swp_entry_t entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81312c30)
Location: mm/swapfile.c:1561
Inline: False
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
```
**Symbols:**

```
ffffffff81312c30-ffffffff81312d08: swap_page_trans_huge_swapped (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool swap_page_trans_huge_swapped(struct swap_info_struct *si, swp_entry_t entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8137e150)
Location: mm/swapfile.c:1544
Inline: False
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:try_to_free_swap
```
**Symbols:**

```
ffffffff8137e150-ffffffff8137e231: swap_page_trans_huge_swapped (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool swap_page_trans_huge_swapped(struct swap_info_struct *si, swp_entry_t entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff813fbd50)
Location: mm/swapfile.c:1529
Inline: False
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:folio_free_swap
```
**Symbols:**

```
ffffffff813fbd50-ffffffff813fbe31: swap_page_trans_huge_swapped (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool swap_page_trans_huge_swapped(struct swap_info_struct *si, swp_entry_t entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8142ece0)
Location: mm/swapfile.c:1511
Inline: False
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:folio_free_swap
```
**Symbols:**

```
ffffffff8142ece0-ffffffff8142edc1: swap_page_trans_huge_swapped (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool swap_page_trans_huge_swapped(struct swap_info_struct *si, swp_entry_t entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81468860)
Location: mm/swapfile.c:1511
Inline: False
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:folio_free_swap
```
**Symbols:**

```
ffffffff81468860-ffffffff81468941: swap_page_trans_huge_swapped (STB_LOCAL)
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
In mm/swapfile.c (ffff800010326394)
Location: mm/swapfile.c:1538
Inline: True
Inline callers:
  - mm/swapfile.c:free_swap_and_cache
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (c053db68)
Location: mm/swapfile.c:1538
Inline: True
Inline callers:
  - mm/swapfile.c:free_swap_and_cache
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (c0000000003fca0c)
Location: mm/swapfile.c:1538
Inline: True
Inline callers:
  - mm/swapfile.c:free_swap_and_cache
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffe00022663c)
Location: mm/swapfile.c:1538
Inline: True
Inline callers:
  - mm/swapfile.c:free_swap_and_cache
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
bool swap_page_trans_huge_swapped(struct swap_info_struct *si, swp_entry_t entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81280f40)
Location: mm/swapfile.c:1538
Inline: False
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
```
**Symbols:**

```
ffffffff81280f40-ffffffff81281015: swap_page_trans_huge_swapped (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool swap_page_trans_huge_swapped(struct swap_info_struct *si, swp_entry_t entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81272db0)
Location: mm/swapfile.c:1538
Inline: False
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
```
**Symbols:**

```
ffffffff81272db0-ffffffff81272e85: swap_page_trans_huge_swapped (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool swap_page_trans_huge_swapped(struct swap_info_struct *si, swp_entry_t entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8127ed50)
Location: mm/swapfile.c:1538
Inline: False
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
```
**Symbols:**

```
ffffffff8127ed50-ffffffff8127ee25: swap_page_trans_huge_swapped (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool swap_page_trans_huge_swapped(struct swap_info_struct *si, swp_entry_t entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8128ee60)
Location: mm/swapfile.c:1538
Inline: False
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
```
**Symbols:**

```
ffffffff8128ee60-ffffffff8128ef30: swap_page_trans_huge_swapped (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
