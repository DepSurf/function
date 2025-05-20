# Function: <code>find_next_best_node</code>

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
In mm/page_alloc.c (ffffffff81191f4c)
Location: mm/page_alloc.c:4004
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
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
In mm/page_alloc.c (ffffffff811a6a19)
Location: mm/page_alloc.c:4501
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
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
In mm/page_alloc.c (ffffffff811b6d77)
Location: mm/page_alloc.c:4659
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
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
In mm/page_alloc.c (ffffffff811becb2)
Location: mm/page_alloc.c:4948
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
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
In mm/page_alloc.c (ffffffff811d3979)
Location: mm/page_alloc.c:5003
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
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
In mm/page_alloc.c (ffffffff811f4c3f)
Location: mm/page_alloc.c:5142
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
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
In mm/page_alloc.c (ffffffff8120701f)
Location: mm/page_alloc.c:5308
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
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
In mm/page_alloc.c (ffffffff8126d080)
Location: mm/page_alloc.c:5495
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
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
In mm/page_alloc.c (ffffffff8127c100)
Location: mm/page_alloc.c:5513
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int find_next_best_node(int node, nodemask_t *used_node_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812ae420)
Location: mm/page_alloc.c:5602
Inline: False
Direct callers:
  - mm/page_alloc.c:build_zonelists
```
**Symbols:**

```
ffffffff812ae420-ffffffff812ae544: find_next_best_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int find_next_best_node(int node, nodemask_t *used_node_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812ba040)
Location: mm/page_alloc.c:5768
Inline: False
Direct callers:
  - mm/page_alloc.c:build_zonelists
```
**Symbols:**

```
ffffffff812ba040-ffffffff812ba164: find_next_best_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int find_next_best_node(int node, nodemask_t *used_node_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812beff0)
Location: mm/page_alloc.c:5970
Inline: False
Direct callers:
  - mm/page_alloc.c:build_zonelists
```
**Symbols:**

```
ffffffff812beff0-ffffffff812bf110: find_next_best_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int find_next_best_node(int node, nodemask_t *used_node_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81308d20)
Location: mm/page_alloc.c:6153
Inline: False
Direct callers:
  - mm/page_alloc.c:build_zonelists
  - mm/migrate.c:__set_migration_target_nodes
```
**Symbols:**

```
ffffffff81308d20-ffffffff81308e8e: find_next_best_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int find_next_best_node(int node, nodemask_t *used_node_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff813711f0)
Location: mm/page_alloc.c:6209
Inline: False
Direct callers:
  - mm/page_alloc.c:build_zonelists
  - mm/migrate.c:__set_migration_target_nodes
```
**Symbols:**

```
ffffffff813711f0-ffffffff81371365: find_next_best_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int find_next_best_node(int node, nodemask_t *used_node_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff813ee860)
Location: mm/page_alloc.c:6377
Inline: False
Direct callers:
  - mm/page_alloc.c:build_zonelists
  - mm/memory-tiers.c:establish_demotion_targets
```
**Symbols:**

```
ffffffff813ee860-ffffffff813ee9c5: find_next_best_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int find_next_best_node(int node, nodemask_t *used_node_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81422630)
Location: mm/page_alloc.c:4925
Inline: False
Direct callers:
  - mm/page_alloc.c:build_zonelists
  - mm/memory-tiers.c:establish_demotion_targets
```
**Symbols:**

```
ffffffff81422630-ffffffff81422794: find_next_best_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int find_next_best_node(int node, nodemask_t *used_node_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8144f430)
Location: mm/page_alloc.c:5014
Inline: False
Direct callers:
  - mm/page_alloc.c:build_zonelists
  - mm/memory-tiers.c:establish_demotion_targets
```
**Symbols:**

```
ffffffff8144f430-ffffffff8144f59f: find_next_best_node (STB_GLOBAL)
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
In mm/page_alloc.c (ffff8000103136ec)
Location: mm/page_alloc.c:5513
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003e4b50)
Location: mm/page_alloc.c:5513
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In mm/page_alloc.c (ffffffff81274750)
Location: mm/page_alloc.c:5513
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
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
In mm/page_alloc.c (ffffffff812666c0)
Location: mm/page_alloc.c:5513
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
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
In mm/page_alloc.c (ffffffff812724f0)
Location: mm/page_alloc.c:5513
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
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
In mm/page_alloc.c (ffffffff81281e20)
Location: mm/page_alloc.c:5513
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
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
