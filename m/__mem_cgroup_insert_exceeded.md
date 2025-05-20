# Function: <code>__mem_cgroup_insert_exceeded</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __mem_cgroup_insert_exceeded(struct mem_cgroup_per_zone *mz, struct mem_cgroup_tree_per_zone *mctz, long unsigned int new_usage_in_excess);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff811f9fe0)
Location: mm/memcontrol.c:497
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
```
**Symbols:**

```
ffffffff811f9fe0-ffffffff811fa05c: __mem_cgroup_insert_exceeded (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __mem_cgroup_insert_exceeded(struct mem_cgroup_per_node *mz, struct mem_cgroup_tree_per_node *mctz, long unsigned int new_usage_in_excess);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8121da80)
Location: mm/memcontrol.c:395
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
```
**Symbols:**

```
ffffffff8121da80-ffffffff8121dafc: __mem_cgroup_insert_exceeded (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __mem_cgroup_insert_exceeded(struct mem_cgroup_per_node *mz, struct mem_cgroup_tree_per_node *mctz, long unsigned int new_usage_in_excess);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81230060)
Location: mm/memcontrol.c:395
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
```
**Symbols:**

```
ffffffff81230060-ffffffff812300dc: __mem_cgroup_insert_exceeded (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __mem_cgroup_insert_exceeded(struct mem_cgroup_per_node *mz, struct mem_cgroup_tree_per_node *mctz, long unsigned int new_usage_in_excess);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8123b970)
Location: mm/memcontrol.c:382
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
```
**Symbols:**

```
ffffffff8123b970-ffffffff8123b9eb: __mem_cgroup_insert_exceeded (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __mem_cgroup_insert_exceeded(struct mem_cgroup_per_node *mz, struct mem_cgroup_tree_per_node *mctz, long unsigned int new_usage_in_excess);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8125b1f0)
Location: mm/memcontrol.c:383
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
```
**Symbols:**

```
ffffffff8125b1f0-ffffffff8125b284: __mem_cgroup_insert_exceeded (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __mem_cgroup_insert_exceeded(struct mem_cgroup_per_node *mz, struct mem_cgroup_tree_per_node *mctz, long unsigned int new_usage_in_excess);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8127ef40)
Location: mm/memcontrol.c:383
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
```
**Symbols:**

```
ffffffff8127ef40-ffffffff8127efd3: __mem_cgroup_insert_exceeded (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __mem_cgroup_insert_exceeded(struct mem_cgroup_per_node *mz, struct mem_cgroup_tree_per_node *mctz, long unsigned int new_usage_in_excess);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81293770)
Location: mm/memcontrol.c:521
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
```
**Symbols:**

```
ffffffff81293770-ffffffff81293803: __mem_cgroup_insert_exceeded (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __mem_cgroup_insert_exceeded(struct mem_cgroup_per_node *mz, struct mem_cgroup_tree_per_node *mctz, long unsigned int new_usage_in_excess);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812ae980)
Location: mm/memcontrol.c:523
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
```
**Symbols:**

```
ffffffff812ae980-ffffffff812aea18: __mem_cgroup_insert_exceeded (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __mem_cgroup_insert_exceeded(struct mem_cgroup_per_node *mz, struct mem_cgroup_tree_per_node *mctz, long unsigned int new_usage_in_excess);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c0390)
Location: mm/memcontrol.c:523
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
```
**Symbols:**

```
ffffffff812c0390-ffffffff812c0428: __mem_cgroup_insert_exceeded (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __mem_cgroup_insert_exceeded(struct mem_cgroup_per_node *mz, struct mem_cgroup_tree_per_node *mctz, long unsigned int new_usage_in_excess);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812f55a0)
Location: mm/memcontrol.c:514
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_update_tree
```
**Symbols:**

```
ffffffff812f55a0-ffffffff812f5646: __mem_cgroup_insert_exceeded (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __mem_cgroup_insert_exceeded(struct mem_cgroup_per_node *mz, struct mem_cgroup_tree_per_node *mctz, long unsigned int new_usage_in_excess);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81300c20)
Location: mm/memcontrol.c:598
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_update_tree
```
**Symbols:**

```
ffffffff81300c20-ffffffff81300cca: __mem_cgroup_insert_exceeded (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __mem_cgroup_insert_exceeded(struct mem_cgroup_per_node *mz, struct mem_cgroup_tree_per_node *mctz, long unsigned int new_usage_in_excess);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813073f0)
Location: mm/memcontrol.c:477
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
```
**Symbols:**

```
ffffffff813073f0-ffffffff8130748d: __mem_cgroup_insert_exceeded (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __mem_cgroup_insert_exceeded(struct mem_cgroup_per_node *mz, struct mem_cgroup_tree_per_node *mctz, long unsigned int new_usage_in_excess);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:476
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
```
**Symbols:**

```
ffffffff81351160-ffffffff81351220: __mem_cgroup_insert_exceeded (STB_LOCAL)
ffffffff81cc2733-ffffffff81cc2750: __mem_cgroup_insert_exceeded.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __mem_cgroup_insert_exceeded(struct mem_cgroup_per_node *mz, struct mem_cgroup_tree_per_node *mctz, long unsigned int new_usage_in_excess);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:411
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
```
**Symbols:**

```
ffffffff813c99a0-ffffffff813c9a6e: __mem_cgroup_insert_exceeded (STB_LOCAL)
ffffffff81e74ce4-ffffffff81e74d01: __mem_cgroup_insert_exceeded.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __mem_cgroup_insert_exceeded(struct mem_cgroup_per_node *mz, struct mem_cgroup_tree_per_node *mctz, long unsigned int new_usage_in_excess);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:404
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
```
**Symbols:**

```
ffffffff8144f020-ffffffff8144f0ee: __mem_cgroup_insert_exceeded (STB_LOCAL)
ffffffff82068001-ffffffff8206801e: __mem_cgroup_insert_exceeded.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __mem_cgroup_insert_exceeded(struct mem_cgroup_per_node *mz, struct mem_cgroup_tree_per_node *mctz, long unsigned int new_usage_in_excess);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:410
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:memcg_check_events
```
**Symbols:**

```
ffffffff81484a50-ffffffff81484b21: __mem_cgroup_insert_exceeded (STB_LOCAL)
ffffffff820e78d6-ffffffff820e78f3: __mem_cgroup_insert_exceeded.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __mem_cgroup_insert_exceeded(struct mem_cgroup_per_node *mz, struct mem_cgroup_tree_per_node *mctz, long unsigned int new_usage_in_excess);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:414
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:memcg_check_events
```
**Symbols:**

```
ffffffff814b3f50-ffffffff814b4021: __mem_cgroup_insert_exceeded (STB_LOCAL)
ffffffff821c45ea-ffffffff821c4607: __mem_cgroup_insert_exceeded.cold (STB_LOCAL)
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
void __mem_cgroup_insert_exceeded(struct mem_cgroup_per_node *mz, struct mem_cgroup_tree_per_node *mctz, long unsigned int new_usage_in_excess);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff800010361cf8)
Location: mm/memcontrol.c:523
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
```
**Symbols:**

```
ffff800010361cf8-ffff800010361da4: __mem_cgroup_insert_exceeded (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __mem_cgroup_insert_exceeded(struct mem_cgroup_per_node *mz, struct mem_cgroup_tree_per_node *mctz, long unsigned int new_usage_in_excess);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c0554710)
Location: mm/memcontrol.c:523
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
```
**Symbols:**

```
c0554710-c05547b4: __mem_cgroup_insert_exceeded (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __mem_cgroup_insert_exceeded(struct mem_cgroup_per_node *mz, struct mem_cgroup_tree_per_node *mctz, long unsigned int new_usage_in_excess);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c00000000044e0b0)
Location: mm/memcontrol.c:523
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
```
**Symbols:**

```
c00000000044e0b0-c00000000044e190: __mem_cgroup_insert_exceeded (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __mem_cgroup_insert_exceeded(struct mem_cgroup_per_node *mz, struct mem_cgroup_tree_per_node *mctz, long unsigned int new_usage_in_excess);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffe00024164a)
Location: mm/memcontrol.c:523
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
```
**Symbols:**

```
ffffffe00024164a-ffffffe0002416d0: __mem_cgroup_insert_exceeded (STB_LOCAL)
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
void __mem_cgroup_insert_exceeded(struct mem_cgroup_per_node *mz, struct mem_cgroup_tree_per_node *mctz, long unsigned int new_usage_in_excess);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b8970)
Location: mm/memcontrol.c:523
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
```
**Symbols:**

```
ffffffff812b8970-ffffffff812b8a08: __mem_cgroup_insert_exceeded (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __mem_cgroup_insert_exceeded(struct mem_cgroup_per_node *mz, struct mem_cgroup_tree_per_node *mctz, long unsigned int new_usage_in_excess);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812a9b40)
Location: mm/memcontrol.c:523
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
```
**Symbols:**

```
ffffffff812a9b40-ffffffff812a9bd8: __mem_cgroup_insert_exceeded (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __mem_cgroup_insert_exceeded(struct mem_cgroup_per_node *mz, struct mem_cgroup_tree_per_node *mctz, long unsigned int new_usage_in_excess);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b6780)
Location: mm/memcontrol.c:523
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
```
**Symbols:**

```
ffffffff812b6780-ffffffff812b6818: __mem_cgroup_insert_exceeded (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __mem_cgroup_insert_exceeded(struct mem_cgroup_per_node *mz, struct mem_cgroup_tree_per_node *mctz, long unsigned int new_usage_in_excess);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c7040)
Location: mm/memcontrol.c:523
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
```
**Symbols:**

```
ffffffff812c7040-ffffffff812c70d8: __mem_cgroup_insert_exceeded (STB_LOCAL)
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
<code>struct mem_cgroup_per_zone *mz</code> ➡️ <code>struct mem_cgroup_per_node *mz</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct mem_cgroup_tree_per_zone *mctz</code> ➡️ <code>struct mem_cgroup_tree_per_node *mctz</code>
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
