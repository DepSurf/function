# Function: <code>swap_range_free</code>

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
void swap_range_free(struct swap_info_struct *si, long unsigned int offset, unsigned int nr_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8120cbd0)
Location: mm/swapfile.c:602
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
```
**Symbols:**

```
ffffffff8120cbd0-ffffffff8120ccf7: swap_range_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void swap_range_free(struct swap_info_struct *si, long unsigned int offset, unsigned int nr_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81226ac0)
Location: mm/swapfile.c:639
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
```
**Symbols:**

```
ffffffff81226ac0-ffffffff81226ba8: swap_range_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void swap_range_free(struct swap_info_struct *si, long unsigned int offset, unsigned int nr_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81249350)
Location: mm/swapfile.c:639
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
```
**Symbols:**

```
ffffffff81249350-ffffffff81249438: swap_range_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void swap_range_free(struct swap_info_struct *si, long unsigned int offset, unsigned int nr_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8125dc20)
Location: mm/swapfile.c:667
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
```
**Symbols:**

```
ffffffff8125dc20-ffffffff8125dcf2: swap_range_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void swap_range_free(struct swap_info_struct *si, long unsigned int offset, unsigned int nr_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81278db0)
Location: mm/swapfile.c:702
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
```
**Symbols:**

```
ffffffff81278db0-ffffffff81278e7b: swap_range_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void swap_range_free(struct swap_info_struct *si, long unsigned int offset, unsigned int nr_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81288890)
Location: mm/swapfile.c:702
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
```
**Symbols:**

```
ffffffff81288890-ffffffff8128895b: swap_range_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void swap_range_free(struct swap_info_struct *si, long unsigned int offset, unsigned int nr_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812badf0)
Location: mm/swapfile.c:696
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:swap_free_cluster
```
**Symbols:**

```
ffffffff812badf0-ffffffff812baec0: swap_range_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void swap_range_free(struct swap_info_struct *si, long unsigned int offset, unsigned int nr_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812c6870)
Location: mm/swapfile.c:709
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:swap_free_cluster
```
**Symbols:**

```
ffffffff812c6870-ffffffff812c695f: swap_range_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void swap_range_free(struct swap_info_struct *si, long unsigned int offset, unsigned int nr_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812cd410)
Location: mm/swapfile.c:708
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
```
**Symbols:**

```
ffffffff812cd410-ffffffff812cd4ff: swap_range_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void swap_range_free(struct swap_info_struct *si, long unsigned int offset, unsigned int nr_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff813127a0)
Location: mm/swapfile.c:716
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
```
**Symbols:**

```
ffffffff813127a0-ffffffff8131288e: swap_range_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void swap_range_free(struct swap_info_struct *si, long unsigned int offset, unsigned int nr_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8137d330)
Location: mm/swapfile.c:718
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
```
**Symbols:**

```
ffffffff8137d330-ffffffff8137d42d: swap_range_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void swap_range_free(struct swap_info_struct *si, long unsigned int offset, unsigned int nr_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff813fb1e0)
Location: mm/swapfile.c:722
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_folio
```
**Symbols:**

```
ffffffff813fb1e0-ffffffff813fb2e3: swap_range_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void swap_range_free(struct swap_info_struct *si, long unsigned int offset, unsigned int nr_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8142d700)
Location: mm/swapfile.c:724
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:swap_free_cluster
```
**Symbols:**

```
ffffffff8142d700-ffffffff8142d800: swap_range_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void swap_range_free(struct swap_info_struct *si, long unsigned int offset, unsigned int nr_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81467100)
Location: mm/swapfile.c:724
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:swap_free_cluster
```
**Symbols:**

```
ffffffff81467100-ffffffff814671fc: swap_range_free (STB_LOCAL)
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
In mm/swapfile.c (ffff800010324528)
Location: mm/swapfile.c:702
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_free_entries
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
In mm/swapfile.c (c053c1f0)
Location: mm/swapfile.c:702
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_free_entries
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
In mm/swapfile.c (c0000000003fa498)
Location: mm/swapfile.c:702
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_free_entries
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
In mm/swapfile.c (ffffffe000224be0)
Location: mm/swapfile.c:702
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_free_entries
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
void swap_range_free(struct swap_info_struct *si, long unsigned int offset, unsigned int nr_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81280e70)
Location: mm/swapfile.c:702
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
```
**Symbols:**

```
ffffffff81280e70-ffffffff81280f3b: swap_range_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void swap_range_free(struct swap_info_struct *si, long unsigned int offset, unsigned int nr_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81272ce0)
Location: mm/swapfile.c:702
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
```
**Symbols:**

```
ffffffff81272ce0-ffffffff81272dab: swap_range_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void swap_range_free(struct swap_info_struct *si, long unsigned int offset, unsigned int nr_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8127ec80)
Location: mm/swapfile.c:702
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
```
**Symbols:**

```
ffffffff8127ec80-ffffffff8127ed4b: swap_range_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void swap_range_free(struct swap_info_struct *si, long unsigned int offset, unsigned int nr_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8128e280)
Location: mm/swapfile.c:702
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
```
**Symbols:**

```
ffffffff8128e280-ffffffff8128e34b: swap_range_free (STB_LOCAL)
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
