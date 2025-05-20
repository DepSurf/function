# Function: <code>try_to_unmap_flush</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void try_to_unmap_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff811ca610)
Location: mm/rmap.c:609
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/rmap.c:try_to_unmap_flush_dirty
```
**Symbols:**

```
ffffffff811ca610-ffffffff811ca73f: try_to_unmap_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void try_to_unmap_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff811e6fe0)
Location: mm/rmap.c:578
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/rmap.c:try_to_unmap_flush_dirty
```
**Symbols:**

```
ffffffff811e6fe0-ffffffff811e70e5: try_to_unmap_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void try_to_unmap_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff811f8380)
Location: mm/rmap.c:577
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/rmap.c:try_to_unmap_flush_dirty
```
**Symbols:**

```
ffffffff811f8380-ffffffff811f847f: try_to_unmap_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void try_to_unmap_flush();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812038fc)
Location: mm/rmap.c:579
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_flush_dirty
Direct callers:
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff812038a0-ffffffff812038d9: try_to_unmap_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void try_to_unmap_flush();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8121c5fc)
Location: mm/rmap.c:580
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_flush_dirty
Direct callers:
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff8121c5a0-ffffffff8121c5d9: try_to_unmap_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void try_to_unmap_flush();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8123e3fc)
Location: mm/rmap.c:581
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_flush_dirty
Direct callers:
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff8123e3a0-ffffffff8123e3d4: try_to_unmap_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void try_to_unmap_flush();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8125298c)
Location: mm/rmap.c:581
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_flush_dirty
Direct callers:
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff81252930-ffffffff81252964: try_to_unmap_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void try_to_unmap_flush();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81264d0c)
Location: mm/rmap.c:581
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_flush_dirty
Direct callers:
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff81264cb0-ffffffff81264ce4: try_to_unmap_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void try_to_unmap_flush();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8127359c)
Location: mm/rmap.c:582
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_flush_dirty
Direct callers:
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff81273540-ffffffff81273574: try_to_unmap_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void try_to_unmap_flush();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812a4712)
Location: mm/rmap.c:595
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_flush_dirty
Direct callers:
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff812a46b0-ffffffff812a46e7: try_to_unmap_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void try_to_unmap_flush();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812afea2)
Location: mm/rmap.c:595
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_flush_dirty
Direct callers:
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff812afe40-ffffffff812afe77: try_to_unmap_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void try_to_unmap_flush();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812b5482)
Location: mm/rmap.c:602
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_flush_dirty
Direct callers:
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff812b5420-ffffffff812b5457: try_to_unmap_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void try_to_unmap_flush();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/rmap.c (ffffffff812f70df)
Location: mm/rmap.c:603
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_flush_dirty
Direct callers:
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff81cbcd14-ffffffff81cbcd28: try_to_unmap_flush.cold (STB_LOCAL)
ffffffff812f7060-ffffffff812f70a9: try_to_unmap_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void try_to_unmap_flush();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/rmap.c (ffffffff8135c5b9)
Location: mm/rmap.c:617
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_flush_dirty
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff81e6e98e-ffffffff81e6e9a2: try_to_unmap_flush.cold (STB_LOCAL)
ffffffff8135c520-ffffffff8135c578: try_to_unmap_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void try_to_unmap_flush();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/rmap.c (ffffffff813d6c79)
Location: mm/rmap.c:612
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_flush_dirty
Direct callers:
  - mm/vmscan.c:shrink_folio_list
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff8206483d-ffffffff82064851: try_to_unmap_flush.cold (STB_LOCAL)
ffffffff813d6bd0-ffffffff813d6c28: try_to_unmap_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void try_to_unmap_flush();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/rmap.c (ffffffff8140bcd9)
Location: mm/rmap.c:614
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_flush_dirty
Direct callers:
  - mm/vmscan.c:shrink_folio_list
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:migrate_pages_batch
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff820e3f82-ffffffff820e3f96: try_to_unmap_flush.cold (STB_LOCAL)
ffffffff8140bc30-ffffffff8140bc83: try_to_unmap_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void try_to_unmap_flush();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/rmap.c (ffffffff81438589)
Location: mm/rmap.c:644
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_flush_dirty
Direct callers:
  - mm/vmscan.c:shrink_folio_list
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:migrate_pages_batch
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff821c0bb0-ffffffff821c0bc4: try_to_unmap_flush.cold (STB_LOCAL)
ffffffff814384e0-ffffffff81438533: try_to_unmap_flush (STB_GLOBAL)
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
In mm/vmscan.c (0)
Location: mm/internal.h:548
Inline: True
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
In mm/vmscan.c (0)
Location: mm/internal.h:548
Inline: True
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
In mm/vmscan.c (0)
Location: mm/internal.h:548
Inline: True
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
In mm/vmscan.c (0)
Location: mm/internal.h:548
Inline: True
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
void try_to_unmap_flush();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8126bbec)
Location: mm/rmap.c:582
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_flush_dirty
Direct callers:
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff8126bb90-ffffffff8126bbc4: try_to_unmap_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void try_to_unmap_flush();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8125dc8c)
Location: mm/rmap.c:582
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_flush_dirty
Direct callers:
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff8125dc30-ffffffff8125dc64: try_to_unmap_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void try_to_unmap_flush();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8126998c)
Location: mm/rmap.c:582
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_flush_dirty
Direct callers:
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff81269930-ffffffff81269964: try_to_unmap_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void try_to_unmap_flush();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812792fc)
Location: mm/rmap.c:582
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_flush_dirty
Direct callers:
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff812792a0-ffffffff812792d4: try_to_unmap_flush (STB_GLOBAL)
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
