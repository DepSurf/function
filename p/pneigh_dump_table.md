# Function: <code>pneigh_dump_table</code>

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
In net/core/neighbour.c (ffffffff81726fca)
Location: net/core/neighbour.c:2322
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
In net/core/neighbour.c (ffffffff81790ae1)
Location: net/core/neighbour.c:2320
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
In net/core/neighbour.c (ffffffff817be380)
Location: net/core/neighbour.c:2319
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
In net/core/neighbour.c (ffffffff817dd641)
Location: net/core/neighbour.c:2369
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
In net/core/neighbour.c (ffffffff818579c1)
Location: net/core/neighbour.c:2369
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
In net/core/neighbour.c (ffffffff818a2b32)
Location: net/core/neighbour.c:2392
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
In net/core/neighbour.c (ffffffff818c5d52)
Location: net/core/neighbour.c:2574
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
In net/core/neighbour.c (ffffffff81911d9d)
Location: net/core/neighbour.c:2595
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
In net/core/neighbour.c (ffffffff8194440d)
Location: net/core/neighbour.c:2592
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
int pneigh_dump_table(struct neigh_table *tbl, struct sk_buff *skb, struct netlink_callback *cb, struct neigh_dump_filter *filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81a12450)
Location: net/core/neighbour.c:2596
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_dump_info
```
**Symbols:**

```
ffffffff81a12450-ffffffff81a12639: pneigh_dump_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pneigh_dump_table(struct neigh_table *tbl, struct sk_buff *skb, struct netlink_callback *cb, struct neigh_dump_filter *filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81a127e0)
Location: net/core/neighbour.c:2598
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_dump_info
```
**Symbols:**

```
ffffffff81a127e0-ffffffff81a129c9: pneigh_dump_table (STB_LOCAL)
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
In net/core/neighbour.c (ffffffff819fb116)
Location: net/core/neighbour.c:2602
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
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
In net/core/neighbour.c (ffffffff81aacf69)
Location: net/core/neighbour.c:2609
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
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
In net/core/neighbour.c (ffffffff81c26158)
Location: net/core/neighbour.c:2711
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
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
In net/core/neighbour.c (ffffffff81dd8568)
Location: net/core/neighbour.c:2760
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
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
In net/core/neighbour.c (ffffffff81e49188)
Location: net/core/neighbour.c:2739
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
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
In net/core/neighbour.c (ffffffff81f07e78)
Location: net/core/neighbour.c:2751
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
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
In net/core/neighbour.c (ffff800010be58e8)
Location: net/core/neighbour.c:2592
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
In net/core/neighbour.c (c0cffcf0)
Location: net/core/neighbour.c:2592
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
In net/core/neighbour.c (c000000000cc92c4)
Location: net/core/neighbour.c:2592
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
In net/core/neighbour.c (ffffffe00076be08)
Location: net/core/neighbour.c:2592
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
In net/core/neighbour.c (ffffffff818e43dd)
Location: net/core/neighbour.c:2592
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
In net/core/neighbour.c (ffffffff8189e21d)
Location: net/core/neighbour.c:2592
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
In net/core/neighbour.c (ffffffff8193540d)
Location: net/core/neighbour.c:2592
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
In net/core/neighbour.c (ffffffff81956b1d)
Location: net/core/neighbour.c:2592
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
</ul>
