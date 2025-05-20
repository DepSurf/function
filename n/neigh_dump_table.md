# Function: <code>neigh_dump_table</code>

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
In net/core/neighbour.c (ffffffff817270f9)
Location: net/core/neighbour.c:2260
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
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
In net/core/neighbour.c (ffffffff81790c02)
Location: net/core/neighbour.c:2258
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
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
In net/core/neighbour.c (ffffffff817be2db)
Location: net/core/neighbour.c:2260
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
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
In net/core/neighbour.c (ffffffff817dd5a2)
Location: net/core/neighbour.c:2310
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
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
In net/core/neighbour.c (ffffffff81857922)
Location: net/core/neighbour.c:2310
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
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
In net/core/neighbour.c (ffffffff818a2d15)
Location: net/core/neighbour.c:2329
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
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
In net/core/neighbour.c (ffffffff818c5e80)
Location: net/core/neighbour.c:2527
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
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
In net/core/neighbour.c (ffffffff81911ec3)
Location: net/core/neighbour.c:2548
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
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
In net/core/neighbour.c (ffffffff81944533)
Location: net/core/neighbour.c:2545
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int neigh_dump_table(struct neigh_table *tbl, struct sk_buff *skb, struct netlink_callback *cb, struct neigh_dump_filter *filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81a14370)
Location: net/core/neighbour.c:2549
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_dump_info
```
**Symbols:**

```
ffffffff81a14370-ffffffff81a1455c: neigh_dump_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int neigh_dump_table(struct neigh_table *tbl, struct sk_buff *skb, struct netlink_callback *cb, struct neigh_dump_filter *filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81a14680)
Location: net/core/neighbour.c:2551
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_dump_info
```
**Symbols:**

```
ffffffff81a14680-ffffffff81a1486c: neigh_dump_table (STB_LOCAL)
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
In net/core/neighbour.c (ffffffff819fb38a)
Location: net/core/neighbour.c:2555
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int neigh_dump_table(struct neigh_table *tbl, struct sk_buff *skb, struct netlink_callback *cb, struct neigh_dump_filter *filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:2562
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_dump_info
```
**Symbols:**

```
ffffffff81aacc50-ffffffff81aace41: neigh_dump_table (STB_LOCAL)
ffffffff81d36b45-ffffffff81d36b63: neigh_dump_table.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int neigh_dump_table(struct neigh_table *tbl, struct sk_buff *skb, struct netlink_callback *cb, struct neigh_dump_filter *filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:2664
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_dump_info
```
**Symbols:**

```
ffffffff81c25c80-ffffffff81c25eac: neigh_dump_table (STB_LOCAL)
ffffffff81f03442-ffffffff81f03470: neigh_dump_table.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int neigh_dump_table(struct neigh_table *tbl, struct sk_buff *skb, struct netlink_callback *cb, struct neigh_dump_filter *filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:2713
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_dump_info
```
**Symbols:**

```
ffffffff81dd7ef0-ffffffff81dd811c: neigh_dump_table (STB_LOCAL)
ffffffff820abc39-ffffffff820abc67: neigh_dump_table.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int neigh_dump_table(struct neigh_table *tbl, struct sk_buff *skb, struct netlink_callback *cb, struct neigh_dump_filter *filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:2692
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_dump_info
```
**Symbols:**

```
ffffffff81e48c60-ffffffff81e48e65: neigh_dump_table (STB_LOCAL)
ffffffff8212d398-ffffffff8212d3c4: neigh_dump_table.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int neigh_dump_table(struct neigh_table *tbl, struct sk_buff *skb, struct netlink_callback *cb, struct neigh_dump_filter *filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:2704
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_dump_info
```
**Symbols:**

```
ffffffff81f07820-ffffffff81f07a25: neigh_dump_table (STB_LOCAL)
ffffffff8220f08a-ffffffff8220f0b6: neigh_dump_table.cold (STB_LOCAL)
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
In net/core/neighbour.c (ffff800010be5ad0)
Location: net/core/neighbour.c:2545
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
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
In net/core/neighbour.c (c0cffe50)
Location: net/core/neighbour.c:2545
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
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
In net/core/neighbour.c (c000000000cc9580)
Location: net/core/neighbour.c:2545
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
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
In net/core/neighbour.c (ffffffe00076bee0)
Location: net/core/neighbour.c:2545
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
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
In net/core/neighbour.c (ffffffff818e4503)
Location: net/core/neighbour.c:2545
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
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
In net/core/neighbour.c (ffffffff8189e343)
Location: net/core/neighbour.c:2545
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
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
In net/core/neighbour.c (ffffffff81935533)
Location: net/core/neighbour.c:2545
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
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
In net/core/neighbour.c (ffffffff81956c43)
Location: net/core/neighbour.c:2545
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
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
