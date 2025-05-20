# Function: <code>shrink_lruvec</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void shrink_lruvec(struct lruvec *lruvec, int swappiness, struct scan_control *sc, long unsigned int *lru_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811a4270)
Location: mm/vmscan.c:2182
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_zone
  - mm/vmscan.c:mem_cgroup_shrink_node_zone
```
**Symbols:**

```
ffffffff811a4270-ffffffff811a49b7: shrink_lruvec (STB_LOCAL)
```
</details>
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
void shrink_lruvec(struct lruvec *lruvec, struct scan_control *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812685e0)
Location: mm/vmscan.c:2426
Inline: False
Direct callers:
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:shrink_node_memcgs
```
**Symbols:**

```
ffffffff812685e0-ffffffff812688d3: shrink_lruvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void shrink_lruvec(struct lruvec *lruvec, struct scan_control *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81273060)
Location: mm/vmscan.c:2434
Inline: False
Direct callers:
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:shrink_node_memcgs
```
**Symbols:**

```
ffffffff81273060-ffffffff81273355: shrink_lruvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void shrink_lruvec(struct lruvec *lruvec, struct scan_control *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81278350)
Location: mm/vmscan.c:2632
Inline: False
Direct callers:
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:shrink_node_memcgs
```
**Symbols:**

```
ffffffff81278350-ffffffff81278680: shrink_lruvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void shrink_lruvec(struct lruvec *lruvec, struct scan_control *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812b5fe0)
Location: mm/vmscan.c:2786
Inline: False
Direct callers:
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:shrink_node_memcgs
```
**Symbols:**

```
ffffffff812b5fe0-ffffffff812b63d2: shrink_lruvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void shrink_lruvec(struct lruvec *lruvec, struct scan_control *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81311430)
Location: mm/vmscan.c:2892
Inline: False
Direct callers:
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:shrink_node_memcgs
```
**Symbols:**

```
ffffffff81311430-ffffffff81311877: shrink_lruvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void shrink_lruvec(struct lruvec *lruvec, struct scan_control *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81384a10)
Location: mm/vmscan.c:5912
Inline: False
Direct callers:
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:shrink_node_memcgs
```
**Symbols:**

```
ffffffff81384a10-ffffffff81384e7d: shrink_lruvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void shrink_lruvec(struct lruvec *lruvec, struct scan_control *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813b64a0)
Location: mm/vmscan.c:6271
Inline: False
Direct callers:
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:shrink_node_memcgs
```
**Symbols:**

```
ffffffff813b64a0-ffffffff813b69df: shrink_lruvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void shrink_lruvec(struct lruvec *lruvec, struct scan_control *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813df360)
Location: mm/vmscan.c:5635
Inline: False
Direct callers:
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:shrink_node_memcgs
```
**Symbols:**

```
ffffffff813df360-ffffffff813df89f: shrink_lruvec (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
