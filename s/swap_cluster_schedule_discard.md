# Function: <code>swap_cluster_schedule_discard</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff811d3ed9)
Location: mm/swapfile.c:264
Inline: True
Inline callers:
  - mm/swapfile.c:swap_entry_free
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff811f1ced)
Location: mm/swapfile.c:261
Inline: True
Inline callers:
  - mm/swapfile.c:swap_entry_free
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
In mm/swapfile.c (ffffffff812026dd)
Location: mm/swapfile.c:308
Inline: True
Inline callers:
  - mm/swapfile.c:swap_entry_free
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
In mm/swapfile.c (ffffffff8120d035)
Location: mm/swapfile.c:365
Inline: True
Inline callers:
  - mm/swapfile.c:free_cluster
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
In mm/swapfile.c (ffffffff81226ef5)
Location: mm/swapfile.c:377
Inline: True
Inline callers:
  - mm/swapfile.c:free_cluster
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
In mm/swapfile.c (ffffffff81248ef5)
Location: mm/swapfile.c:377
Inline: True
Inline callers:
  - mm/swapfile.c:free_cluster
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
In mm/swapfile.c (ffffffff8125d935)
Location: mm/swapfile.c:405
Inline: True
Inline callers:
  - mm/swapfile.c:free_cluster
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
In mm/swapfile.c (ffffffff81278ba7)
Location: mm/swapfile.c:440
Inline: True
Inline callers:
  - mm/swapfile.c:free_cluster
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
In mm/swapfile.c (ffffffff81288697)
Location: mm/swapfile.c:440
Inline: True
Inline callers:
  - mm/swapfile.c:free_cluster
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void swap_cluster_schedule_discard(struct swap_info_struct *si, unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812bb0d0)
Location: mm/swapfile.c:439
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:swap_free_cluster
```
**Symbols:**

```
ffffffff812bb0d0-ffffffff812bb1b3: swap_cluster_schedule_discard (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void swap_cluster_schedule_discard(struct swap_info_struct *si, unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812c6b70)
Location: mm/swapfile.c:452
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:swap_free_cluster
```
**Symbols:**

```
ffffffff812c6b70-ffffffff812c6c53: swap_cluster_schedule_discard (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void swap_cluster_schedule_discard(struct swap_info_struct *si, unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812cd710)
Location: mm/swapfile.c:451
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
```
**Symbols:**

```
ffffffff812cd710-ffffffff812cd7f5: swap_cluster_schedule_discard (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void swap_cluster_schedule_discard(struct swap_info_struct *si, unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81312ab0)
Location: mm/swapfile.c:451
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
```
**Symbols:**

```
ffffffff81312ab0-ffffffff81312b95: swap_cluster_schedule_discard (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void swap_cluster_schedule_discard(struct swap_info_struct *si, unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8137dc30)
Location: mm/swapfile.c:453
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
```
**Symbols:**

```
ffffffff8137dc30-ffffffff8137dd21: swap_cluster_schedule_discard (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void swap_cluster_schedule_discard(struct swap_info_struct *si, unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff813fb7f0)
Location: mm/swapfile.c:457
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_folio
```
**Symbols:**

```
ffffffff813fb7f0-ffffffff813fb8e1: swap_cluster_schedule_discard (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void swap_cluster_schedule_discard(struct swap_info_struct *si, unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8142e770)
Location: mm/swapfile.c:458
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:swap_free_cluster
```
**Symbols:**

```
ffffffff8142e770-ffffffff8142e861: swap_cluster_schedule_discard (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void swap_cluster_schedule_discard(struct swap_info_struct *si, unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81468230)
Location: mm/swapfile.c:460
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:swap_free_cluster
```
**Symbols:**

```
ffffffff81468230-ffffffff81468321: swap_cluster_schedule_discard (STB_LOCAL)
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
In mm/swapfile.c (ffff8000103246e0)
Location: mm/swapfile.c:440
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
In mm/swapfile.c (c053c384)
Location: mm/swapfile.c:440
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
In mm/swapfile.c (c0000000003fa6b4)
Location: mm/swapfile.c:440
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
In mm/swapfile.c (ffffffe000224e3a)
Location: mm/swapfile.c:440
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81280c77)
Location: mm/swapfile.c:440
Inline: True
Inline callers:
  - mm/swapfile.c:free_cluster
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
In mm/swapfile.c (ffffffff81272ae7)
Location: mm/swapfile.c:440
Inline: True
Inline callers:
  - mm/swapfile.c:free_cluster
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
In mm/swapfile.c (ffffffff8127ea87)
Location: mm/swapfile.c:440
Inline: True
Inline callers:
  - mm/swapfile.c:free_cluster
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
In mm/swapfile.c (ffffffff8128e647)
Location: mm/swapfile.c:440
Inline: True
Inline callers:
  - mm/swapfile.c:free_cluster
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
