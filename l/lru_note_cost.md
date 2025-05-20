# Function: <code>lru_note_cost</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void lru_note_cost(struct lruvec *lruvec, bool file, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8125fbd0)
Location: mm/swap.c:281
Inline: False
Direct callers:
  - mm/swap.c:lru_note_cost_page
  - mm/vmscan.c:shrink_inactive_list
```
**Symbols:**

```
ffffffff8125fbd0-ffffffff8125fd32: lru_note_cost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void lru_note_cost(struct lruvec *lruvec, bool file, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8126a180)
Location: mm/swap.c:262
Inline: False
Direct callers:
  - mm/swap.c:lru_note_cost_page
  - mm/swap.c:lru_note_cost_page
  - mm/vmscan.c:shrink_inactive_list
```
**Symbols:**

```
ffffffff8126a180-ffffffff8126a346: lru_note_cost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void lru_note_cost(struct lruvec *lruvec, bool file, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8126f2a0)
Location: mm/swap.c:274
Inline: False
Direct callers:
  - mm/swap.c:lru_note_cost_page
  - mm/swap.c:lru_note_cost_page
  - mm/vmscan.c:shrink_inactive_list
```
**Symbols:**

```
ffffffff8126f2a0-ffffffff8126f44a: lru_note_cost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void lru_note_cost(struct lruvec *lruvec, bool file, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff812ac420)
Location: mm/swap.c:252
Inline: False
Direct callers:
  - mm/swap.c:lru_note_cost_page
  - mm/swap.c:lru_note_cost_page
  - mm/vmscan.c:shrink_inactive_list
```
**Symbols:**

```
ffffffff812ac420-ffffffff812ac5a0: lru_note_cost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void lru_note_cost(struct lruvec *lruvec, bool file, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81306560)
Location: mm/swap.c:264
Inline: False
Direct callers:
  - mm/swap.c:lru_note_cost_folio
  - mm/swap.c:lru_note_cost_folio
  - mm/vmscan.c:shrink_inactive_list
```
**Symbols:**

```
ffffffff81306560-ffffffff81306704: lru_note_cost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void lru_note_cost(struct lruvec *lruvec, bool file, unsigned int nr_io, unsigned int nr_rotated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81370610)
Location: mm/swap.c:299
Inline: False
Direct callers:
  - mm/swap.c:lru_note_cost_refault
  - mm/swap.c:lru_note_cost_refault
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
```
**Symbols:**

```
ffffffff81370610-ffffffff813707bd: lru_note_cost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void lru_note_cost(struct lruvec *lruvec, bool file, unsigned int nr_io, unsigned int nr_rotated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff813a27c0)
Location: mm/swap.c:269
Inline: False
Direct callers:
  - mm/swap.c:lru_note_cost_refault
  - mm/swap.c:lru_note_cost_refault
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
```
**Symbols:**

```
ffffffff813a27c0-ffffffff813a296d: lru_note_cost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void lru_note_cost(struct lruvec *lruvec, bool file, unsigned int nr_io, unsigned int nr_rotated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff813cc440)
Location: mm/swap.c:269
Inline: False
Direct callers:
  - mm/swap.c:lru_note_cost_refault
  - mm/swap.c:lru_note_cost_refault
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
```
**Symbols:**

```
ffffffff813cc440-ffffffff813cc5ed: lru_note_cost (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int nr_io</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int nr_rotated</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int nr_pages</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
