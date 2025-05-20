# Function: <code>lru_move_tail_fn</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void lru_move_tail_fn(struct lruvec *lruvec, struct folio *folio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swap.c (ffffffff8136e520)
Location: mm/swap.c:267
Inline: True
```
**Symbols:**

```
ffffffff8136e520-ffffffff8136e83a: lru_move_tail_fn.part.0 (STB_LOCAL)
ffffffff8136e850-ffffffff8136e87f: lru_move_tail_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void lru_move_tail_fn(struct lruvec *lruvec, struct folio *folio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swap.c (ffffffff813a0740)
Location: mm/swap.c:237
Inline: True
```
**Symbols:**

```
ffffffff813a0740-ffffffff813a0a5a: lru_move_tail_fn.part.0 (STB_LOCAL)
ffffffff813a0a70-ffffffff813a0a9f: lru_move_tail_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void lru_move_tail_fn(struct lruvec *lruvec, struct folio *folio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swap.c (ffffffff813ca2c0)
Location: mm/swap.c:237
Inline: True
```
**Symbols:**

```
ffffffff813ca2c0-ffffffff813ca5d3: lru_move_tail_fn.part.0 (STB_LOCAL)
ffffffff813ca5f0-ffffffff813ca61f: lru_move_tail_fn (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
