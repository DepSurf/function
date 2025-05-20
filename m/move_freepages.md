# Function: <code>move_freepages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int move_freepages(struct zone *zone, struct page *start_page, struct page *end_page, int migratetype);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811929a0)
Location: mm/page_alloc.c:1469
Inline: True
Inline callers:
  - mm/page_alloc.c:move_freepages_block
```
**Symbols:**

```
ffffffff811929a0-ffffffff81192a44: move_freepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int move_freepages(struct zone *zone, struct page *start_page, struct page *end_page, int migratetype);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811a83c4)
Location: mm/page_alloc.c:1828
Inline: True
Inline callers:
  - mm/page_alloc.c:move_freepages_block
```
**Symbols:**

```
ffffffff811a82b0-ffffffff811a835e: move_freepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int move_freepages(struct zone *zone, struct page *start_page, struct page *end_page, int migratetype);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811b8793)
Location: mm/page_alloc.c:1847
Inline: True
Inline callers:
  - mm/page_alloc.c:move_freepages_block
```
**Symbols:**

```
ffffffff811b8680-ffffffff811b872e: move_freepages (STB_GLOBAL)
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
In mm/page_alloc.c (ffffffff811c0539)
Location: mm/page_alloc.c:1853
Inline: True
Inline callers:
  - mm/page_alloc.c:move_freepages_block
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
In mm/page_alloc.c (ffffffff811d5019)
Location: mm/page_alloc.c:1891
Inline: True
Inline callers:
  - mm/page_alloc.c:move_freepages_block
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
In mm/page_alloc.c (ffffffff811f644d)
Location: mm/page_alloc.c:1998
Inline: True
Inline callers:
  - mm/page_alloc.c:move_freepages_block
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
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:2042
Inline: True
Inline callers:
  - mm/page_alloc.c:move_freepages_block
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
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:2233
Inline: True
Inline callers:
  - mm/page_alloc.c:move_freepages_block
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
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:2224
Inline: True
Inline callers:
  - mm/page_alloc.c:move_freepages_block
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
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:2296
Inline: True
Inline callers:
  - mm/page_alloc.c:move_freepages_block
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
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:2374
Inline: True
Inline callers:
  - mm/page_alloc.c:move_freepages_block
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
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:2425
Inline: True
Inline callers:
  - mm/page_alloc.c:move_freepages_block
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
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:2503
Inline: True
Inline callers:
  - mm/page_alloc.c:move_freepages_block
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
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:2528
Inline: True
Inline callers:
  - mm/page_alloc.c:move_freepages_block
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
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:2607
Inline: True
Inline callers:
  - mm/page_alloc.c:move_freepages_block
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:1653
Inline: True
Inline callers:
  - mm/page_alloc.c:move_freepages_block
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:1616
Inline: True
Inline callers:
  - mm/page_alloc.c:move_freepages_block
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
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:2224
Inline: True
Inline callers:
  - mm/page_alloc.c:move_freepages_block
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
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:2224
Inline: True
Inline callers:
  - mm/page_alloc.c:move_freepages_block
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
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:2224
Inline: True
Inline callers:
  - mm/page_alloc.c:move_freepages_block
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
In mm/page_alloc.c (ffffffe00021bd4e)
Location: mm/page_alloc.c:2224
Inline: True
Inline callers:
  - mm/page_alloc.c:move_freepages_block
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
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:2224
Inline: True
Inline callers:
  - mm/page_alloc.c:move_freepages_block
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
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:2224
Inline: True
Inline callers:
  - mm/page_alloc.c:move_freepages_block
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
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:2224
Inline: True
Inline callers:
  - mm/page_alloc.c:move_freepages_block
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
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:2224
Inline: True
Inline callers:
  - mm/page_alloc.c:move_freepages_block
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
</ul>
