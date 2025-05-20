# Function: <code>lru_deactivate_fn</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void lru_deactivate_fn(struct page *page, struct lruvec *lruvec, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811b2430)
Location: mm/swap.c:562
Inline: True
```
**Symbols:**

```
ffffffff811b2430-ffffffff811b26a8: lru_deactivate_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void lru_deactivate_fn(struct page *page, struct lruvec *lruvec, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811c27e0)
Location: mm/swap.c:563
Inline: True
```
**Symbols:**

```
ffffffff811c27e0-ffffffff811c2a6a: lru_deactivate_fn (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void lru_deactivate_fn(struct page *page, struct lruvec *lruvec, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff812312d0)
Location: mm/swap.c:542
Inline: True
```
**Symbols:**

```
ffffffff812312d0-ffffffff81231568: lru_deactivate_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void lru_deactivate_fn(struct page *page, struct lruvec *lruvec, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swap.c (ffffffff8125ebb0)
Location: mm/swap.c:577
Inline: True
```
**Symbols:**

```
ffffffff8125ebb0-ffffffff8125ee0e: lru_deactivate_fn.part.0 (STB_LOCAL)
ffffffff8125ee10-ffffffff8125ee4d: lru_deactivate_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void lru_deactivate_fn(struct page *page, struct lruvec *lruvec);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swap.c (ffffffff81268cb0)
Location: mm/swap.c:564
Inline: True
```
**Symbols:**

```
ffffffff81268cb0-ffffffff81268ef4: lru_deactivate_fn.part.0 (STB_LOCAL)
ffffffff81268f00-ffffffff81268f40: lru_deactivate_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void lru_deactivate_fn(struct page *page, struct lruvec *lruvec);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swap.c (ffffffff8126cec0)
Location: mm/swap.c:570
Inline: True
```
**Symbols:**

```
ffffffff8126cec0-ffffffff8126d1e0: lru_deactivate_fn.part.0 (STB_LOCAL)
ffffffff8126d1e0-ffffffff8126d220: lru_deactivate_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void lru_deactivate_fn(struct page *page, struct lruvec *lruvec);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swap.c (ffffffff812aa150)
Location: mm/swap.c:548
Inline: True
```
**Symbols:**

```
ffffffff812aa150-ffffffff812aa503: lru_deactivate_fn.part.0 (STB_LOCAL)
ffffffff812aa510-ffffffff812aa550: lru_deactivate_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void lru_deactivate_fn(struct page *page, struct lruvec *lruvec);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swap.c (ffffffff81303520)
Location: mm/swap.c:552
Inline: True
```
**Symbols:**

```
ffffffff81303520-ffffffff81303a3a: lru_deactivate_fn.part.0 (STB_LOCAL)
ffffffff81303a40-ffffffff81303af5: lru_deactivate_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void lru_deactivate_fn(struct lruvec *lruvec, struct folio *folio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swap.c (ffffffff8136eca0)
Location: mm/swap.c:632
Inline: True
```
**Symbols:**

```
ffffffff8136eca0-ffffffff8136eff9: lru_deactivate_fn.part.0 (STB_LOCAL)
ffffffff8136f010-ffffffff8136f053: lru_deactivate_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void lru_deactivate_fn(struct lruvec *lruvec, struct folio *folio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swap.c (ffffffff813a0dd0)
Location: mm/swap.c:602
Inline: True
```
**Symbols:**

```
ffffffff813a0dd0-ffffffff813a1129: lru_deactivate_fn.part.0 (STB_LOCAL)
ffffffff813a1140-ffffffff813a117a: lru_deactivate_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void lru_deactivate_fn(struct lruvec *lruvec, struct folio *folio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swap.c (ffffffff813caa50)
Location: mm/swap.c:602
Inline: True
```
**Symbols:**

```
ffffffff813caa50-ffffffff813cada2: lru_deactivate_fn.part.0 (STB_LOCAL)
ffffffff813cadc0-ffffffff813cadfb: lru_deactivate_fn (STB_LOCAL)
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
void lru_deactivate_fn(struct page *page, struct lruvec *lruvec, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffff8000102c0d48)
Location: mm/swap.c:542
Inline: True
```
**Symbols:**

```
ffff8000102c0d48-ffff8000102c1004: lru_deactivate_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void lru_deactivate_fn(struct page *page, struct lruvec *lruvec, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (c04ed5cc)
Location: mm/swap.c:542
Inline: True
```
**Symbols:**

```
c04ed5cc-c04ed7c8: lru_deactivate_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void lru_deactivate_fn(struct page *page, struct lruvec *lruvec, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (c00000000037a880)
Location: mm/swap.c:542
Inline: True
```
**Symbols:**

```
c00000000037a880-c00000000037ac2c: lru_deactivate_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void lru_deactivate_fn(struct page *page, struct lruvec *lruvec, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffe0001e37aa)
Location: mm/swap.c:542
Inline: True
```
**Symbols:**

```
ffffffe0001e37aa-ffffffe0001e399c: lru_deactivate_fn (STB_LOCAL)
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
void lru_deactivate_fn(struct page *page, struct lruvec *lruvec, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81229920)
Location: mm/swap.c:542
Inline: True
```
**Symbols:**

```
ffffffff81229920-ffffffff81229bb8: lru_deactivate_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void lru_deactivate_fn(struct page *page, struct lruvec *lruvec, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8121ca40)
Location: mm/swap.c:542
Inline: True
```
**Symbols:**

```
ffffffff8121ca40-ffffffff8121ccd8: lru_deactivate_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void lru_deactivate_fn(struct page *page, struct lruvec *lruvec, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff812276c0)
Location: mm/swap.c:542
Inline: True
```
**Symbols:**

```
ffffffff812276c0-ffffffff81227958: lru_deactivate_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void lru_deactivate_fn(struct page *page, struct lruvec *lruvec, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff812369f0)
Location: mm/swap.c:542
Inline: True
```
**Symbols:**

```
ffffffff812369f0-ffffffff81236c88: lru_deactivate_fn (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
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
