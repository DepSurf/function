# Function: <code>lru_lazyfree_fn</code>

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
void lru_lazyfree_fn(struct page *page, struct lruvec *lruvec, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811ca4e0)
Location: mm/swap.c:574
Inline: True
```
**Symbols:**

```
ffffffff811ca4e0-ffffffff811ca76d: lru_lazyfree_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void lru_lazyfree_fn(struct page *page, struct lruvec *lruvec, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811df3e0)
Location: mm/swap.c:574
Inline: True
```
**Symbols:**

```
ffffffff811df3e0-ffffffff811df6a2: lru_lazyfree_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void lru_lazyfree_fn(struct page *page, struct lruvec *lruvec, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81200ba0)
Location: mm/swap.c:547
Inline: True
```
**Symbols:**

```
ffffffff81200ba0-ffffffff81200e83: lru_lazyfree_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void lru_lazyfree_fn(struct page *page, struct lruvec *lruvec, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81213510)
Location: mm/swap.c:541
Inline: True
```
**Symbols:**

```
ffffffff81213510-ffffffff812137f8: lru_lazyfree_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void lru_lazyfree_fn(struct page *page, struct lruvec *lruvec, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81222f40)
Location: mm/swap.c:542
Inline: True
```
**Symbols:**

```
ffffffff81222f40-ffffffff81223215: lru_lazyfree_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void lru_lazyfree_fn(struct page *page, struct lruvec *lruvec, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff812309f0)
Location: mm/swap.c:559
Inline: True
```
**Symbols:**

```
ffffffff812309f0-ffffffff81230cc5: lru_lazyfree_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void lru_lazyfree_fn(struct page *page, struct lruvec *lruvec, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swap.c (ffffffff8125f120)
Location: mm/swap.c:595
Inline: True
```
**Symbols:**

```
ffffffff8125f120-ffffffff8125f3a6: lru_lazyfree_fn.part.0 (STB_LOCAL)
ffffffff8125f3b0-ffffffff8125f3ec: lru_lazyfree_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void lru_lazyfree_fn(struct page *page, struct lruvec *lruvec);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swap.c (ffffffff81269730)
Location: mm/swap.c:581
Inline: True
```
**Symbols:**

```
ffffffff81269730-ffffffff812699a6: lru_lazyfree_fn.part.0 (STB_LOCAL)
ffffffff812699b0-ffffffff812699ef: lru_lazyfree_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void lru_lazyfree_fn(struct page *page, struct lruvec *lruvec);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swap.c (ffffffff8126e070)
Location: mm/swap.c:586
Inline: True
```
**Symbols:**

```
ffffffff8126e070-ffffffff8126e402: lru_lazyfree_fn.part.0 (STB_LOCAL)
ffffffff8126e410-ffffffff8126e44f: lru_lazyfree_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void lru_lazyfree_fn(struct page *page, struct lruvec *lruvec);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swap.c (ffffffff812aafc0)
Location: mm/swap.c:564
Inline: True
```
**Symbols:**

```
ffffffff812aafc0-ffffffff812ab407: lru_lazyfree_fn.part.0 (STB_LOCAL)
ffffffff812ab410-ffffffff812ab44f: lru_lazyfree_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void lru_lazyfree_fn(struct page *page, struct lruvec *lruvec);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swap.c (ffffffff81304b30)
Location: mm/swap.c:568
Inline: True
```
**Symbols:**

```
ffffffff81304b30-ffffffff81305156: lru_lazyfree_fn.part.0 (STB_LOCAL)
ffffffff81305160-ffffffff81305214: lru_lazyfree_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void lru_lazyfree_fn(struct lruvec *lruvec, struct folio *folio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swap.c (ffffffff8136fbe0)
Location: mm/swap.c:648
Inline: True
```
**Symbols:**

```
ffffffff8136fbe0-ffffffff8136ff58: lru_lazyfree_fn.part.0 (STB_LOCAL)
ffffffff8136ff70-ffffffff8136ffb7: lru_lazyfree_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void lru_lazyfree_fn(struct lruvec *lruvec, struct folio *folio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swap.c (ffffffff813a1d60)
Location: mm/swap.c:618
Inline: True
```
**Symbols:**

```
ffffffff813a1d60-ffffffff813a20d8: lru_lazyfree_fn.part.0 (STB_LOCAL)
ffffffff813a20f0-ffffffff813a2137: lru_lazyfree_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void lru_lazyfree_fn(struct lruvec *lruvec, struct folio *folio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swap.c (ffffffff813cb9e0)
Location: mm/swap.c:618
Inline: True
```
**Symbols:**

```
ffffffff813cb9e0-ffffffff813cbd51: lru_lazyfree_fn.part.0 (STB_LOCAL)
ffffffff813cbd70-ffffffff813cbdb7: lru_lazyfree_fn (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void lru_lazyfree_fn(struct page *page, struct lruvec *lruvec, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffff8000102c13e8)
Location: mm/swap.c:559
Inline: True
```
**Symbols:**

```
ffff8000102c13e8-ffff8000102c16ec: lru_lazyfree_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void lru_lazyfree_fn(struct page *page, struct lruvec *lruvec, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (c04ebcec)
Location: mm/swap.c:559
Inline: True
```
**Symbols:**

```
c04ebcec-c04ebf08: lru_lazyfree_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void lru_lazyfree_fn(struct page *page, struct lruvec *lruvec, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (c000000000379760)
Location: mm/swap.c:559
Inline: True
```
**Symbols:**

```
c000000000379760-c000000000379b68: lru_lazyfree_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void lru_lazyfree_fn(struct page *page, struct lruvec *lruvec, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffe0001e21e0)
Location: mm/swap.c:559
Inline: True
```
**Symbols:**

```
ffffffe0001e21e0-ffffffe0001e240a: lru_lazyfree_fn (STB_LOCAL)
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
void lru_lazyfree_fn(struct page *page, struct lruvec *lruvec, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81229040)
Location: mm/swap.c:559
Inline: True
```
**Symbols:**

```
ffffffff81229040-ffffffff81229315: lru_lazyfree_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void lru_lazyfree_fn(struct page *page, struct lruvec *lruvec, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8121c180)
Location: mm/swap.c:559
Inline: True
```
**Symbols:**

```
ffffffff8121c180-ffffffff8121c43f: lru_lazyfree_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void lru_lazyfree_fn(struct page *page, struct lruvec *lruvec, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81226de0)
Location: mm/swap.c:559
Inline: True
```
**Symbols:**

```
ffffffff81226de0-ffffffff812270b5: lru_lazyfree_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void lru_lazyfree_fn(struct page *page, struct lruvec *lruvec, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81236110)
Location: mm/swap.c:559
Inline: True
```
**Symbols:**

```
ffffffff81236110-ffffffff812363e5: lru_lazyfree_fn (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>void *arg</code>
</li>
</ul>
</details>
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
<code>struct folio *folio</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *page</code>
</li>
<li>
<b>Param reordered. </b>
<code>page, lruvec</code> ➡️ <code>lruvec, folio</code>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
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
