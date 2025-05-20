# Function: <code>__mem_cgroup_largest_soft_limit_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct mem_cgroup_per_zone *__mem_cgroup_largest_soft_limit_node(struct mem_cgroup_tree_per_zone *mctz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff811fb140)
Location: mm/memcontrol.c:611
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
```
**Symbols:**

```
ffffffff811fb140-ffffffff811fb22c: __mem_cgroup_largest_soft_limit_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct mem_cgroup_per_node *__mem_cgroup_largest_soft_limit_node(struct mem_cgroup_tree_per_node *mctz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8121e6a0)
Location: mm/memcontrol.c:507
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
```
**Symbols:**

```
ffffffff8121e6a0-ffffffff8121e781: __mem_cgroup_largest_soft_limit_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct mem_cgroup_per_node *__mem_cgroup_largest_soft_limit_node(struct mem_cgroup_tree_per_node *mctz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81230c90)
Location: mm/memcontrol.c:510
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
```
**Symbols:**

```
ffffffff81230c90-ffffffff81230d71: __mem_cgroup_largest_soft_limit_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct mem_cgroup_per_node *__mem_cgroup_largest_soft_limit_node(struct mem_cgroup_tree_per_node *mctz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8123c540)
Location: mm/memcontrol.c:497
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
```
**Symbols:**

```
ffffffff8123c540-ffffffff8123c615: __mem_cgroup_largest_soft_limit_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct mem_cgroup_per_node *__mem_cgroup_largest_soft_limit_node(struct mem_cgroup_tree_per_node *mctz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8125bec0)
Location: mm/memcontrol.c:510
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
```
**Symbols:**

```
ffffffff8125bec0-ffffffff8125bf7c: __mem_cgroup_largest_soft_limit_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff81285891)
Location: mm/memcontrol.c:510
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
Direct callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
```
**Symbols:**

```
ffffffff8127f700-ffffffff8127f7bb: __mem_cgroup_largest_soft_limit_node.part.49 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff8129a79b)
Location: mm/memcontrol.c:648
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
Direct callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
```
**Symbols:**

```
ffffffff81294940-ffffffff812949ed: __mem_cgroup_largest_soft_limit_node.part.45 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct mem_cgroup_per_node *__mem_cgroup_largest_soft_limit_node(struct mem_cgroup_tree_per_node *mctz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b0650)
Location: mm/memcontrol.c:650
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
```
**Symbols:**

```
ffffffff812b0650-ffffffff812b06f5: __mem_cgroup_largest_soft_limit_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct mem_cgroup_per_node *__mem_cgroup_largest_soft_limit_node(struct mem_cgroup_tree_per_node *mctz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c20b0)
Location: mm/memcontrol.c:650
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
```
**Symbols:**

```
ffffffff812c20b0-ffffffff812c2155: __mem_cgroup_largest_soft_limit_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct mem_cgroup_per_node *__mem_cgroup_largest_soft_limit_node(struct mem_cgroup_tree_per_node *mctz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812f6800)
Location: mm/memcontrol.c:641
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
```
**Symbols:**

```
ffffffff812f6800-ffffffff812f68ae: __mem_cgroup_largest_soft_limit_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct mem_cgroup_per_node *__mem_cgroup_largest_soft_limit_node(struct mem_cgroup_tree_per_node *mctz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81301d00)
Location: mm/memcontrol.c:720
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
```
**Symbols:**

```
ffffffff81301d00-ffffffff81301dbb: __mem_cgroup_largest_soft_limit_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct mem_cgroup_per_node *__mem_cgroup_largest_soft_limit_node(struct mem_cgroup_tree_per_node *mctz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81308860)
Location: mm/memcontrol.c:599
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
```
**Symbols:**

```
ffffffff81308860-ffffffff8130891b: __mem_cgroup_largest_soft_limit_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct mem_cgroup_per_node *__mem_cgroup_largest_soft_limit_node(struct mem_cgroup_tree_per_node *mctz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:598
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
```
**Symbols:**

```
ffffffff81352810-ffffffff813528ea: __mem_cgroup_largest_soft_limit_node (STB_LOCAL)
ffffffff81cc27af-ffffffff81cc27c4: __mem_cgroup_largest_soft_limit_node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct mem_cgroup_per_node *__mem_cgroup_largest_soft_limit_node(struct mem_cgroup_tree_per_node *mctz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:533
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
```
**Symbols:**

```
ffffffff813cb550-ffffffff813cb622: __mem_cgroup_largest_soft_limit_node (STB_LOCAL)
ffffffff81e74d89-ffffffff81e74d9e: __mem_cgroup_largest_soft_limit_node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct mem_cgroup_per_node *__mem_cgroup_largest_soft_limit_node(struct mem_cgroup_tree_per_node *mctz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:526
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
```
**Symbols:**

```
ffffffff81450210-ffffffff814502e2: __mem_cgroup_largest_soft_limit_node (STB_LOCAL)
ffffffff8206807d-ffffffff82068092: __mem_cgroup_largest_soft_limit_node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct mem_cgroup_per_node *__mem_cgroup_largest_soft_limit_node(struct mem_cgroup_tree_per_node *mctz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:538
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
```
**Symbols:**

```
ffffffff81485c70-ffffffff81485d43: __mem_cgroup_largest_soft_limit_node (STB_LOCAL)
ffffffff820e7966-ffffffff820e797b: __mem_cgroup_largest_soft_limit_node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct mem_cgroup_per_node *__mem_cgroup_largest_soft_limit_node(struct mem_cgroup_tree_per_node *mctz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:542
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
```
**Symbols:**

```
ffffffff814b4ae0-ffffffff814b4bb3: __mem_cgroup_largest_soft_limit_node (STB_LOCAL)
ffffffff821c461b-ffffffff821c4630: __mem_cgroup_largest_soft_limit_node.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct mem_cgroup_per_node *__mem_cgroup_largest_soft_limit_node(struct mem_cgroup_tree_per_node *mctz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff800010364bf0)
Location: mm/memcontrol.c:650
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
```
**Symbols:**

```
ffff800010364bf0-ffff800010364c7c: __mem_cgroup_largest_soft_limit_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct mem_cgroup_per_node *__mem_cgroup_largest_soft_limit_node(struct mem_cgroup_tree_per_node *mctz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c0556a18)
Location: mm/memcontrol.c:650
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
```
**Symbols:**

```
c0556a18-c0556b10: __mem_cgroup_largest_soft_limit_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct mem_cgroup_per_node *__mem_cgroup_largest_soft_limit_node(struct mem_cgroup_tree_per_node *mctz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c000000000451650)
Location: mm/memcontrol.c:650
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
```
**Symbols:**

```
c000000000451650-c0000000004517a4: __mem_cgroup_largest_soft_limit_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct mem_cgroup_per_node *__mem_cgroup_largest_soft_limit_node(struct mem_cgroup_tree_per_node *mctz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffe0002436d0)
Location: mm/memcontrol.c:650
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
```
**Symbols:**

```
ffffffe0002436d0-ffffffe000243788: __mem_cgroup_largest_soft_limit_node (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct mem_cgroup_per_node *__mem_cgroup_largest_soft_limit_node(struct mem_cgroup_tree_per_node *mctz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812ba690)
Location: mm/memcontrol.c:650
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
```
**Symbols:**

```
ffffffff812ba690-ffffffff812ba735: __mem_cgroup_largest_soft_limit_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct mem_cgroup_per_node *__mem_cgroup_largest_soft_limit_node(struct mem_cgroup_tree_per_node *mctz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812ab850)
Location: mm/memcontrol.c:650
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
```
**Symbols:**

```
ffffffff812ab850-ffffffff812ab8f5: __mem_cgroup_largest_soft_limit_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct mem_cgroup_per_node *__mem_cgroup_largest_soft_limit_node(struct mem_cgroup_tree_per_node *mctz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b84a0)
Location: mm/memcontrol.c:650
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
```
**Symbols:**

```
ffffffff812b84a0-ffffffff812b8545: __mem_cgroup_largest_soft_limit_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct mem_cgroup_per_node *__mem_cgroup_largest_soft_limit_node(struct mem_cgroup_tree_per_node *mctz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c8bb0)
Location: mm/memcontrol.c:650
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
```
**Symbols:**

```
ffffffff812c8bb0-ffffffff812c8c6a: __mem_cgroup_largest_soft_limit_node (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct mem_cgroup_tree_per_zone *mctz</code> ➡️ <code>struct mem_cgroup_tree_per_node *mctz</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct mem_cgroup_per_zone *</code> ➡️ <code>struct mem_cgroup_per_node *</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
