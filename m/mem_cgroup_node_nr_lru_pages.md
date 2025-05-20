# Function: <code>mem_cgroup_node_nr_lru_pages</code>

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
In mm/memcontrol.c (ffffffff811f9774)
Location: mm/memcontrol.c:727
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_nr_lru_pages
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int mem_cgroup_node_nr_lru_pages(struct mem_cgroup *memcg, int nid, unsigned int lru_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812208b6)
Location: mm/memcontrol.c:625
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_nr_lru_pages
Direct callers:
  - mm/workingset.c:count_shadow_nodes
```
**Symbols:**

```
ffffffff81220410-ffffffff81220446: mem_cgroup_node_nr_lru_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int mem_cgroup_node_nr_lru_pages(struct mem_cgroup *memcg, int nid, unsigned int lru_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81232aa0)
Location: mm/memcontrol.c:628
Inline: False
Direct callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_nr_lru_pages
```
**Symbols:**

```
ffffffff81232aa0-ffffffff81232b1a: mem_cgroup_node_nr_lru_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int mem_cgroup_node_nr_lru_pages(struct mem_cgroup *memcg, int nid, unsigned int lru_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8123e2b0)
Location: mm/memcontrol.c:598
Inline: False
Direct callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_nr_lru_pages
```
**Symbols:**

```
ffffffff8123e2b0-ffffffff8123e33d: mem_cgroup_node_nr_lru_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int mem_cgroup_node_nr_lru_pages(struct mem_cgroup *memcg, int nid, unsigned int lru_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8125de50)
Location: mm/memcontrol.c:612
Inline: False
Direct callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_nr_lru_pages
```
**Symbols:**

```
ffffffff8125de50-ffffffff8125dedd: mem_cgroup_node_nr_lru_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int mem_cgroup_node_nr_lru_pages(struct mem_cgroup *memcg, int nid, unsigned int lru_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812820e0)
Location: mm/memcontrol.c:583
Inline: False
Direct callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_nr_lru_pages
```
**Symbols:**

```
ffffffff812820e0-ffffffff81282164: mem_cgroup_node_nr_lru_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int mem_cgroup_node_nr_lru_pages(struct mem_cgroup *memcg, int nid, unsigned int lru_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812962c0)
Location: mm/memcontrol.c:721
Inline: False
Direct callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_nr_lru_pages
```
**Symbols:**

```
ffffffff812962c0-ffffffff81296344: mem_cgroup_node_nr_lru_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int mem_cgroup_node_nr_lru_pages(struct mem_cgroup *memcg, int nid, unsigned int lru_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812adbd0)
Location: mm/memcontrol.c:3601
Inline: False
Direct callers:
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
```
**Symbols:**

```
ffffffff812adbd0-ffffffff812adcca: mem_cgroup_node_nr_lru_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int mem_cgroup_node_nr_lru_pages(struct mem_cgroup *memcg, int nid, unsigned int lru_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bf720)
Location: mm/memcontrol.c:3794
Inline: False
Direct callers:
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
```
**Symbols:**

```
ffffffff812bf720-ffffffff812bf81a: mem_cgroup_node_nr_lru_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int mem_cgroup_node_nr_lru_pages(struct mem_cgroup *memcg, int nid, unsigned int lru_mask, bool tree);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812f7610)
Location: mm/memcontrol.c:3677
Inline: False
Direct callers:
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
```
**Symbols:**

```
ffffffff812f7610-ffffffff812f7742: mem_cgroup_node_nr_lru_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int mem_cgroup_node_nr_lru_pages(struct mem_cgroup *memcg, int nid, unsigned int lru_mask, bool tree);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81302c00)
Location: mm/memcontrol.c:3937
Inline: False
Direct callers:
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
```
**Symbols:**

```
ffffffff81302c00-ffffffff81302d3e: mem_cgroup_node_nr_lru_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int mem_cgroup_node_nr_lru_pages(struct mem_cgroup *memcg, int nid, unsigned int lru_mask, bool tree);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81309180)
Location: mm/memcontrol.c:3724
Inline: False
Direct callers:
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
```
**Symbols:**

```
ffffffff81309180-ffffffff813092c4: mem_cgroup_node_nr_lru_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int mem_cgroup_node_nr_lru_pages(struct mem_cgroup *memcg, int nid, unsigned int lru_mask, bool tree);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81352bf0)
Location: mm/memcontrol.c:3891
Inline: False
Direct callers:
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
```
**Symbols:**

```
ffffffff81352bf0-ffffffff81352d9d: mem_cgroup_node_nr_lru_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int mem_cgroup_node_nr_lru_pages(struct mem_cgroup *memcg, int nid, unsigned int lru_mask, bool tree);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813cd090)
Location: mm/memcontrol.c:3842
Inline: False
Direct callers:
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
```
**Symbols:**

```
ffffffff813cd090-ffffffff813cd25f: mem_cgroup_node_nr_lru_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int mem_cgroup_node_nr_lru_pages(struct mem_cgroup *memcg, int nid, unsigned int lru_mask, bool tree);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81451830)
Location: mm/memcontrol.c:3947
Inline: False
Direct callers:
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
```
**Symbols:**

```
ffffffff81451830-ffffffff81451a1d: mem_cgroup_node_nr_lru_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int mem_cgroup_node_nr_lru_pages(struct mem_cgroup *memcg, int nid, unsigned int lru_mask, bool tree);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81486d90)
Location: mm/memcontrol.c:3974
Inline: False
Direct callers:
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
```
**Symbols:**

```
ffffffff81486d90-ffffffff81486f7d: mem_cgroup_node_nr_lru_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int mem_cgroup_node_nr_lru_pages(struct mem_cgroup *memcg, int nid, unsigned int lru_mask, bool tree);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814b5510)
Location: mm/memcontrol.c:4171
Inline: False
Direct callers:
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
```
**Symbols:**

```
ffffffff814b5510-ffffffff814b564f: mem_cgroup_node_nr_lru_pages (STB_LOCAL)
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
long unsigned int mem_cgroup_node_nr_lru_pages(struct mem_cgroup *memcg, int nid, unsigned int lru_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff800010361458)
Location: mm/memcontrol.c:3794
Inline: False
Direct callers:
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
```
**Symbols:**

```
ffff800010361458-ffff800010361578: mem_cgroup_node_nr_lru_pages (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int mem_cgroup_node_nr_lru_pages(struct mem_cgroup *memcg, int nid, unsigned int lru_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c00000000044d020)
Location: mm/memcontrol.c:3794
Inline: False
Direct callers:
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
```
**Symbols:**

```
c00000000044d020-c00000000044d198: mem_cgroup_node_nr_lru_pages (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
long unsigned int mem_cgroup_node_nr_lru_pages(struct mem_cgroup *memcg, int nid, unsigned int lru_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b7d00)
Location: mm/memcontrol.c:3794
Inline: False
Direct callers:
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
```
**Symbols:**

```
ffffffff812b7d00-ffffffff812b7dfa: mem_cgroup_node_nr_lru_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int mem_cgroup_node_nr_lru_pages(struct mem_cgroup *memcg, int nid, unsigned int lru_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812a8ed0)
Location: mm/memcontrol.c:3794
Inline: False
Direct callers:
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
```
**Symbols:**

```
ffffffff812a8ed0-ffffffff812a8fca: mem_cgroup_node_nr_lru_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int mem_cgroup_node_nr_lru_pages(struct mem_cgroup *memcg, int nid, unsigned int lru_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b5b10)
Location: mm/memcontrol.c:3794
Inline: False
Direct callers:
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
```
**Symbols:**

```
ffffffff812b5b10-ffffffff812b5c0a: mem_cgroup_node_nr_lru_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int mem_cgroup_node_nr_lru_pages(struct mem_cgroup *memcg, int nid, unsigned int lru_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c6030)
Location: mm/memcontrol.c:3794
Inline: False
Direct callers:
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
```
**Symbols:**

```
ffffffff812c6030-ffffffff812c612a: mem_cgroup_node_nr_lru_pages (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool tree</code>
</li>
</ul>
</details>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
