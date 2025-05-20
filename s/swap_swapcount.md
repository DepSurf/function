# Function: <code>swap_swapcount</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8120f32e)
Location: mm/swapfile.c:1261
Inline: True
Inline callers:
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:__swp_swapcount
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
In mm/swapfile.c (ffffffff812299e0)
Location: mm/swapfile.c:1338
Inline: True
Inline callers:
  - mm/swapfile.c:__swp_swapcount
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
In mm/swapfile.c (ffffffff8124aca0)
Location: mm/swapfile.c:1338
Inline: True
Inline callers:
  - mm/swapfile.c:__swp_swapcount
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
In mm/swapfile.c (ffffffff8125f2d0)
Location: mm/swapfile.c:1355
Inline: True
Inline callers:
  - mm/swapfile.c:__swp_swapcount
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
In mm/swapfile.c (ffffffff81279f9b)
Location: mm/swapfile.c:1462
Inline: True
Inline callers:
  - mm/swapfile.c:__swp_swapcount
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
In mm/swapfile.c (ffffffff81289a7b)
Location: mm/swapfile.c:1462
Inline: True
Inline callers:
  - mm/swapfile.c:__swp_swapcount
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812bc93b)
Location: mm/swapfile.c:1499
Inline: True
Inline callers:
  - mm/swapfile.c:__swp_swapcount
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812c846d)
Location: mm/swapfile.c:1517
Inline: True
Inline callers:
  - mm/swapfile.c:__swp_swapcount
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
In mm/swapfile.c (ffffffff812cee13)
Location: mm/swapfile.c:1516
Inline: True
Inline callers:
  - mm/swapfile.c:__swp_swapcount
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
In mm/swapfile.c (ffffffff81314383)
Location: mm/swapfile.c:1485
Inline: True
Inline callers:
  - mm/swapfile.c:__swp_swapcount
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8137f843)
Location: mm/swapfile.c:1468
Inline: True
Inline callers:
  - mm/swapfile.c:__swp_swapcount
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff813fe631)
Location: mm/swapfile.c:1453
Inline: True
Inline callers:
  - mm/swapfile.c:folio_free_swap
  - mm/swapfile.c:__swp_swapcount
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int swap_swapcount(struct swap_info_struct *si, swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81431340)
Location: mm/swapfile.c:1453
Inline: False
Direct callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swapfile.c:folio_free_swap
```
**Symbols:**

```
ffffffff81431340-ffffffff814313bd: swap_swapcount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int swap_swapcount(struct swap_info_struct *si, swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8146a760)
Location: mm/swapfile.c:1453
Inline: False
Direct callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swapfile.c:folio_free_swap
```
**Symbols:**

```
ffffffff8146a760-ffffffff8146a7dd: swap_swapcount (STB_GLOBAL)
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
In mm/swapfile.c (ffff80001032491c)
Location: mm/swapfile.c:1462
Inline: True
Inline callers:
  - mm/swapfile.c:__swp_swapcount
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
In mm/swapfile.c (c053c524)
Location: mm/swapfile.c:1462
Inline: True
Inline callers:
  - mm/swapfile.c:__swp_swapcount
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
In mm/swapfile.c (c0000000003fa968)
Location: mm/swapfile.c:1462
Inline: True
Inline callers:
  - mm/swapfile.c:__swp_swapcount
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
In mm/swapfile.c (ffffffe000225062)
Location: mm/swapfile.c:1462
Inline: True
Inline callers:
  - mm/swapfile.c:__swp_swapcount
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
In mm/swapfile.c (ffffffff8128205b)
Location: mm/swapfile.c:1462
Inline: True
Inline callers:
  - mm/swapfile.c:__swp_swapcount
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
In mm/swapfile.c (ffffffff81273b7b)
Location: mm/swapfile.c:1462
Inline: True
Inline callers:
  - mm/swapfile.c:__swp_swapcount
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
In mm/swapfile.c (ffffffff8127fe6b)
Location: mm/swapfile.c:1462
Inline: True
Inline callers:
  - mm/swapfile.c:__swp_swapcount
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
In mm/swapfile.c (ffffffff8128fb4d)
Location: mm/swapfile.c:1462
Inline: True
Inline callers:
  - mm/swapfile.c:__swp_swapcount
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
