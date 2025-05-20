# Function: <code>swap_range_alloc</code>

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
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void swap_range_alloc(struct swap_info_struct *si, long unsigned int offset, unsigned int nr_entries);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8120d0e0)
Location: mm/swapfile.c:583
Inline: True
Direct callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
ffffffff8120d0e0-ffffffff8120d16e: swap_range_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void swap_range_alloc(struct swap_info_struct *si, long unsigned int offset, unsigned int nr_entries);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81226fb0)
Location: mm/swapfile.c:610
Inline: True
Direct callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
ffffffff81226fb0-ffffffff81227017: swap_range_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void swap_range_alloc(struct swap_info_struct *si, long unsigned int offset, unsigned int nr_entries);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81248fb0)
Location: mm/swapfile.c:610
Inline: True
Direct callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
ffffffff81248fb0-ffffffff81249038: swap_range_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void swap_range_alloc(struct swap_info_struct *si, long unsigned int offset, unsigned int nr_entries);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8125ddd0)
Location: mm/swapfile.c:638
Inline: True
Direct callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
ffffffff8125ddd0-ffffffff8125de3a: swap_range_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void swap_range_alloc(struct swap_info_struct *si, long unsigned int offset, unsigned int nr_entries);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81278f60)
Location: mm/swapfile.c:673
Inline: True
Direct callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
ffffffff81278f60-ffffffff81278fe0: swap_range_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void swap_range_alloc(struct swap_info_struct *si, long unsigned int offset, unsigned int nr_entries);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81288a40)
Location: mm/swapfile.c:673
Inline: True
Direct callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
ffffffff81288a40-ffffffff81288ac0: swap_range_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void swap_range_alloc(struct swap_info_struct *si, long unsigned int offset, unsigned int nr_entries);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812bb1c0)
Location: mm/swapfile.c:667
Inline: True
Direct callers:
  - mm/swapfile.c:swap_alloc_cluster
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
ffffffff812bb1c0-ffffffff812bb244: swap_range_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void swap_range_alloc(struct swap_info_struct *si, long unsigned int offset, unsigned int nr_entries);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812c6c60)
Location: mm/swapfile.c:680
Inline: True
Direct callers:
  - mm/swapfile.c:swap_alloc_cluster
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
ffffffff812c6c60-ffffffff812c6ce4: swap_range_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void swap_range_alloc(struct swap_info_struct *si, long unsigned int offset, unsigned int nr_entries);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812cd800)
Location: mm/swapfile.c:679
Inline: True
Direct callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
ffffffff812cd800-ffffffff812cd884: swap_range_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void swap_range_alloc(struct swap_info_struct *si, long unsigned int offset, unsigned int nr_entries);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81312ba0)
Location: mm/swapfile.c:687
Inline: True
Direct callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
ffffffff81312ba0-ffffffff81312c24: swap_range_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void swap_range_alloc(struct swap_info_struct *si, long unsigned int offset, unsigned int nr_entries);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8137d180)
Location: mm/swapfile.c:689
Inline: True
Direct callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
ffffffff8137d180-ffffffff8137d20b: swap_range_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void swap_range_alloc(struct swap_info_struct *si, long unsigned int offset, unsigned int nr_entries);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff813fb140)
Location: mm/swapfile.c:693
Inline: True
Direct callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
ffffffff813fb140-ffffffff813fb1cb: swap_range_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void swap_range_alloc(struct swap_info_struct *si, long unsigned int offset, unsigned int nr_entries);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8142e1c0)
Location: mm/swapfile.c:695
Inline: True
Direct callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
ffffffff8142e1c0-ffffffff8142e24b: swap_range_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void swap_range_alloc(struct swap_info_struct *si, long unsigned int offset, unsigned int nr_entries);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81467c80)
Location: mm/swapfile.c:697
Inline: True
Direct callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
ffffffff81467c80-ffffffff81467d0b: swap_range_alloc (STB_LOCAL)
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
In mm/swapfile.c (ffff800010325204)
Location: mm/swapfile.c:673
Inline: True
Inline callers:
  - mm/swapfile.c:scan_swap_map_slots
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
In mm/swapfile.c (c053cc5c)
Location: mm/swapfile.c:673
Inline: True
Inline callers:
  - mm/swapfile.c:scan_swap_map_slots
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
In mm/swapfile.c (c0000000003fb5c4)
Location: mm/swapfile.c:673
Inline: True
Inline callers:
  - mm/swapfile.c:scan_swap_map_slots
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
In mm/swapfile.c (ffffffe0002258ee)
Location: mm/swapfile.c:673
Inline: True
Inline callers:
  - mm/swapfile.c:scan_swap_map_slots
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void swap_range_alloc(struct swap_info_struct *si, long unsigned int offset, unsigned int nr_entries);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81281020)
Location: mm/swapfile.c:673
Inline: True
Direct callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
ffffffff81281020-ffffffff812810a0: swap_range_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void swap_range_alloc(struct swap_info_struct *si, long unsigned int offset, unsigned int nr_entries);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81272e90)
Location: mm/swapfile.c:673
Inline: True
Direct callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
ffffffff81272e90-ffffffff81272f10: swap_range_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void swap_range_alloc(struct swap_info_struct *si, long unsigned int offset, unsigned int nr_entries);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8127ee30)
Location: mm/swapfile.c:673
Inline: True
Direct callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
ffffffff8127ee30-ffffffff8127eeb0: swap_range_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void swap_range_alloc(struct swap_info_struct *si, long unsigned int offset, unsigned int nr_entries);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8128ed40)
Location: mm/swapfile.c:673
Inline: True
Direct callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
ffffffff8128ed40-ffffffff8128edbe: swap_range_alloc (STB_LOCAL)
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
