# Function: <code>mem_cgroup_get_nr_swap_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int mem_cgroup_get_nr_swap_pages(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81224bd0)
Location: mm/memcontrol.c:5965
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node_memcg
```
**Symbols:**

```
ffffffff81224bd0-ffffffff81224c2f: mem_cgroup_get_nr_swap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int mem_cgroup_get_nr_swap_pages(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812371c0)
Location: mm/memcontrol.c:5965
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node_memcg
```
**Symbols:**

```
ffffffff812371c0-ffffffff8123721f: mem_cgroup_get_nr_swap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int mem_cgroup_get_nr_swap_pages(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81242c80)
Location: mm/memcontrol.c:6030
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node_memcg
```
**Symbols:**

```
ffffffff81242c80-ffffffff81242cdf: mem_cgroup_get_nr_swap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int mem_cgroup_get_nr_swap_pages(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81262ac0)
Location: mm/memcontrol.c:6136
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node_memcg
```
**Symbols:**

```
ffffffff81262ac0-ffffffff81262b21: mem_cgroup_get_nr_swap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int mem_cgroup_get_nr_swap_pages(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81286c80)
Location: mm/memcontrol.c:6211
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node_memcg
```
**Symbols:**

```
ffffffff81286c80-ffffffff81286ce0: mem_cgroup_get_nr_swap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int mem_cgroup_get_nr_swap_pages(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8129bb90)
Location: mm/memcontrol.c:6542
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node_memcg
```
**Symbols:**

```
ffffffff8129bb90-ffffffff8129bbed: mem_cgroup_get_nr_swap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int mem_cgroup_get_nr_swap_pages(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b6d60)
Location: mm/memcontrol.c:6834
Inline: False
Direct callers:
  - mm/vmscan.c:get_scan_count
```
**Symbols:**

```
ffffffff812b6d60-ffffffff812b6dc2: mem_cgroup_get_nr_swap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int mem_cgroup_get_nr_swap_pages(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c8c30)
Location: mm/memcontrol.c:7164
Inline: False
Direct callers:
  - mm/vmscan.c:get_scan_count
```
**Symbols:**

```
ffffffff812c8c30-ffffffff812c8c92: mem_cgroup_get_nr_swap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int mem_cgroup_get_nr_swap_pages(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812fe260)
Location: mm/memcontrol.c:7018
Inline: False
Direct callers:
  - mm/vmscan.c:get_scan_count
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
```
**Symbols:**

```
ffffffff812fe260-ffffffff812fe2c1: mem_cgroup_get_nr_swap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int mem_cgroup_get_nr_swap_pages(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8130a790)
Location: mm/memcontrol.c:7272
Inline: False
Direct callers:
  - mm/vmscan.c:get_scan_count
  - mm/workingset.c:workingset_refault
```
**Symbols:**

```
ffffffff8130a790-ffffffff8130a7f1: mem_cgroup_get_nr_swap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int mem_cgroup_get_nr_swap_pages(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81310de0)
Location: mm/memcontrol.c:7141
Inline: False
Direct callers:
  - mm/vmscan.c:get_scan_count
  - mm/workingset.c:workingset_refault
```
**Symbols:**

```
ffffffff81310de0-ffffffff81310e41: mem_cgroup_get_nr_swap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long int mem_cgroup_get_nr_swap_pages(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:7317
Inline: False
Direct callers:
  - mm/vmscan.c:get_scan_count
  - mm/workingset.c:workingset_refault
```
**Symbols:**

```
ffffffff81cc2bef-ffffffff81cc2c04: mem_cgroup_get_nr_swap_pages.cold (STB_LOCAL)
ffffffff8135c0c0-ffffffff8135c13a: mem_cgroup_get_nr_swap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long int mem_cgroup_get_nr_swap_pages(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:7298
Inline: False
Direct callers:
  - mm/vmscan.c:get_scan_count
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
```
**Symbols:**

```
ffffffff81e75158-ffffffff81e7516d: mem_cgroup_get_nr_swap_pages.cold (STB_LOCAL)
ffffffff813d5a00-ffffffff813d5a78: mem_cgroup_get_nr_swap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int mem_cgroup_get_nr_swap_pages(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8145b460)
Location: mm/memcontrol.c:7490
Inline: False
Direct callers:
  - mm/vmscan.c:get_swappiness
  - mm/vmscan.c:get_scan_count
  - mm/workingset.c:workingset_refault
```
**Symbols:**

```
ffffffff8145b460-ffffffff8145b4b5: mem_cgroup_get_nr_swap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int mem_cgroup_get_nr_swap_pages(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814910d0)
Location: mm/memcontrol.c:7559
Inline: False
Direct callers:
  - mm/vmscan.c:get_swappiness
  - mm/vmscan.c:get_scan_count
  - mm/workingset.c:workingset_test_recent
  - mm/workingset.c:workingset_test_recent
```
**Symbols:**

```
ffffffff814910d0-ffffffff81491125: mem_cgroup_get_nr_swap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int mem_cgroup_get_nr_swap_pages(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814c0a40)
Location: mm/memcontrol.c:7933
Inline: False
Direct callers:
  - mm/vmscan.c:get_swappiness
  - mm/vmscan.c:get_scan_count
  - mm/workingset.c:workingset_test_recent
  - mm/workingset.c:workingset_test_recent
```
**Symbols:**

```
ffffffff814c0a40-ffffffff814c0a95: mem_cgroup_get_nr_swap_pages (STB_GLOBAL)
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
long int mem_cgroup_get_nr_swap_pages(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff80001036bae8)
Location: mm/memcontrol.c:7164
Inline: False
Direct callers:
  - mm/vmscan.c:get_scan_count
```
**Symbols:**

```
ffff80001036bae8-ffff80001036bb60: mem_cgroup_get_nr_swap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int mem_cgroup_get_nr_swap_pages(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c055d15c)
Location: mm/memcontrol.c:7164
Inline: False
Direct callers:
  - mm/vmscan.c:get_scan_count
```
**Symbols:**

```
c055d15c-c055d1e4: mem_cgroup_get_nr_swap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int mem_cgroup_get_nr_swap_pages(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c00000000045b780)
Location: mm/memcontrol.c:7164
Inline: False
Direct callers:
  - mm/vmscan.c:get_scan_count
```
**Symbols:**

```
c00000000045b780-c00000000045b814: mem_cgroup_get_nr_swap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int mem_cgroup_get_nr_swap_pages(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffe0002490e0)
Location: mm/memcontrol.c:7164
Inline: False
Direct callers:
  - mm/vmscan.c:get_scan_count
```
**Symbols:**

```
ffffffe0002490e0-ffffffe000249148: mem_cgroup_get_nr_swap_pages (STB_GLOBAL)
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
long int mem_cgroup_get_nr_swap_pages(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c1210)
Location: mm/memcontrol.c:7164
Inline: False
Direct callers:
  - mm/vmscan.c:get_scan_count
```
**Symbols:**

```
ffffffff812c1210-ffffffff812c1272: mem_cgroup_get_nr_swap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int mem_cgroup_get_nr_swap_pages(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b2260)
Location: mm/memcontrol.c:7164
Inline: False
Direct callers:
  - mm/vmscan.c:get_scan_count
```
**Symbols:**

```
ffffffff812b2260-ffffffff812b22c2: mem_cgroup_get_nr_swap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int mem_cgroup_get_nr_swap_pages(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bf020)
Location: mm/memcontrol.c:7164
Inline: False
Direct callers:
  - mm/vmscan.c:get_scan_count
```
**Symbols:**

```
ffffffff812bf020-ffffffff812bf082: mem_cgroup_get_nr_swap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int mem_cgroup_get_nr_swap_pages(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812cfa90)
Location: mm/memcontrol.c:7164
Inline: False
Direct callers:
  - mm/vmscan.c:get_scan_count
```
**Symbols:**

```
ffffffff812cfa90-ffffffff812cfaf2: mem_cgroup_get_nr_swap_pages (STB_GLOBAL)
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
