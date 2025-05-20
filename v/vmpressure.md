# Function: <code>vmpressure</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void vmpressure(gfp_t gfp, struct mem_cgroup *memcg, long unsigned int scanned, long unsigned int reclaimed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmpressure.c (ffffffff812007d0)
Location: mm/vmpressure.c:211
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_zone
  - mm/vmpressure.c:vmpressure_prio
```
**Symbols:**

```
ffffffff812007d0-ffffffff8120084f: vmpressure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void vmpressure(gfp_t gfp, struct mem_cgroup *memcg, bool tree, long unsigned int scanned, long unsigned int reclaimed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmpressure.c (ffffffff81224ea0)
Location: mm/vmpressure.c:219
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmpressure.c:vmpressure_prio
```
**Symbols:**

```
ffffffff81224ea0-ffffffff81224fbc: vmpressure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void vmpressure(gfp_t gfp, struct mem_cgroup *memcg, bool tree, long unsigned int scanned, long unsigned int reclaimed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmpressure.c (ffffffff81237490)
Location: mm/vmpressure.c:227
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmpressure.c:vmpressure_prio
```
**Symbols:**

```
ffffffff81237490-ffffffff812375ac: vmpressure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void vmpressure(gfp_t gfp, struct mem_cgroup *memcg, bool tree, long unsigned int scanned, long unsigned int reclaimed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmpressure.c (ffffffff81242f40)
Location: mm/vmpressure.c:243
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmpressure.c:vmpressure_prio
```
**Symbols:**

```
ffffffff81242f40-ffffffff81243067: vmpressure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void vmpressure(gfp_t gfp, struct mem_cgroup *memcg, bool tree, long unsigned int scanned, long unsigned int reclaimed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmpressure.c (ffffffff81262d90)
Location: mm/vmpressure.c:243
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmpressure.c:vmpressure_prio
```
**Symbols:**

```
ffffffff81262d90-ffffffff81262eb7: vmpressure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void vmpressure(gfp_t gfp, struct mem_cgroup *memcg, bool tree, long unsigned int scanned, long unsigned int reclaimed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmpressure.c (ffffffff81287130)
Location: mm/vmpressure.c:243
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmpressure.c:vmpressure_prio
```
**Symbols:**

```
ffffffff81287130-ffffffff8128725b: vmpressure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void vmpressure(gfp_t gfp, struct mem_cgroup *memcg, bool tree, long unsigned int scanned, long unsigned int reclaimed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmpressure.c (ffffffff8129c080)
Location: mm/vmpressure.c:243
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmpressure.c:vmpressure_prio
```
**Symbols:**

```
ffffffff8129c080-ffffffff8129c1ab: vmpressure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void vmpressure(gfp_t gfp, struct mem_cgroup *memcg, bool tree, long unsigned int scanned, long unsigned int reclaimed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmpressure.c (ffffffff812b7210)
Location: mm/vmpressure.c:240
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmpressure.c:vmpressure_prio
```
**Symbols:**

```
ffffffff812b7210-ffffffff812b733d: vmpressure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void vmpressure(gfp_t gfp, struct mem_cgroup *memcg, bool tree, long unsigned int scanned, long unsigned int reclaimed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmpressure.c (ffffffff812c90e0)
Location: mm/vmpressure.c:240
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmpressure.c:vmpressure_prio
```
**Symbols:**

```
ffffffff812c90e0-ffffffff812c920d: vmpressure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void vmpressure(gfp_t gfp, struct mem_cgroup *memcg, bool tree, long unsigned int scanned, long unsigned int reclaimed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmpressure.c (ffffffff812fe740)
Location: mm/vmpressure.c:240
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmpressure.c:vmpressure_prio
```
**Symbols:**

```
ffffffff812fe740-ffffffff812fe86d: vmpressure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void vmpressure(gfp_t gfp, struct mem_cgroup *memcg, bool tree, long unsigned int scanned, long unsigned int reclaimed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmpressure.c (ffffffff8130aa80)
Location: mm/vmpressure.c:240
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmpressure.c:vmpressure_prio
```
**Symbols:**

```
ffffffff8130aa80-ffffffff8130abad: vmpressure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void vmpressure(gfp_t gfp, struct mem_cgroup *memcg, bool tree, long unsigned int scanned, long unsigned int reclaimed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmpressure.c (ffffffff813110e0)
Location: mm/vmpressure.c:240
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmpressure.c:vmpressure_prio
```
**Symbols:**

```
ffffffff813110e0-ffffffff8131120d: vmpressure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void vmpressure(gfp_t gfp, struct mem_cgroup *memcg, bool tree, long unsigned int scanned, long unsigned int reclaimed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmpressure.c (ffffffff8135c3d0)
Location: mm/vmpressure.c:239
Inline: True
Direct callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmpressure.c:vmpressure_prio
```
**Symbols:**

```
ffffffff8135c3d0-ffffffff8135c501: vmpressure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void vmpressure(gfp_t gfp, struct mem_cgroup *memcg, bool tree, long unsigned int scanned, long unsigned int reclaimed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmpressure.c (ffffffff813d5ff0)
Location: mm/vmpressure.c:239
Inline: True
Direct callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmpressure.c:vmpressure_prio
```
**Symbols:**

```
ffffffff813d5ff0-ffffffff813d6144: vmpressure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void vmpressure(gfp_t gfp, struct mem_cgroup *memcg, bool tree, long unsigned int scanned, long unsigned int reclaimed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmpressure.c (ffffffff8145ba20)
Location: mm/vmpressure.c:239
Inline: True
Direct callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmpressure.c:vmpressure_prio
```
**Symbols:**

```
ffffffff8145ba20-ffffffff8145bb74: vmpressure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void vmpressure(gfp_t gfp, struct mem_cgroup *memcg, bool tree, long unsigned int scanned, long unsigned int reclaimed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmpressure.c (ffffffff814916a0)
Location: mm/vmpressure.c:239
Inline: True
Direct callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_one
  - mm/vmpressure.c:vmpressure_prio
```
**Symbols:**

```
ffffffff814916a0-ffffffff81491816: vmpressure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void vmpressure(gfp_t gfp, struct mem_cgroup *memcg, bool tree, long unsigned int scanned, long unsigned int reclaimed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmpressure.c (ffffffff814c1080)
Location: mm/vmpressure.c:239
Inline: True
Direct callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_one
  - mm/vmpressure.c:vmpressure_prio
```
**Symbols:**

```
ffffffff814c1080-ffffffff814c11f6: vmpressure (STB_GLOBAL)
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
void vmpressure(gfp_t gfp, struct mem_cgroup *memcg, bool tree, long unsigned int scanned, long unsigned int reclaimed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmpressure.c (ffff80001036c580)
Location: mm/vmpressure.c:240
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmpressure.c:vmpressure_prio
```
**Symbols:**

```
ffff80001036c580-ffff80001036c720: vmpressure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void vmpressure(gfp_t gfp, struct mem_cgroup *memcg, bool tree, long unsigned int scanned, long unsigned int reclaimed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmpressure.c (c055d664)
Location: mm/vmpressure.c:240
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmpressure.c:vmpressure_prio
```
**Symbols:**

```
c055d664-c055d7b8: vmpressure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void vmpressure(gfp_t gfp, struct mem_cgroup *memcg, bool tree, long unsigned int scanned, long unsigned int reclaimed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmpressure.c (c00000000045c390)
Location: mm/vmpressure.c:240
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmpressure.c:vmpressure_prio
```
**Symbols:**

```
c00000000045c390-c00000000045c598: vmpressure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void vmpressure(gfp_t gfp, struct mem_cgroup *memcg, bool tree, long unsigned int scanned, long unsigned int reclaimed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmpressure.c (ffffffe00024956e)
Location: mm/vmpressure.c:240
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmpressure.c:vmpressure_prio
```
**Symbols:**

```
ffffffe00024956e-ffffffe000249728: vmpressure (STB_GLOBAL)
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
void vmpressure(gfp_t gfp, struct mem_cgroup *memcg, bool tree, long unsigned int scanned, long unsigned int reclaimed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmpressure.c (ffffffff812c16c0)
Location: mm/vmpressure.c:240
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmpressure.c:vmpressure_prio
```
**Symbols:**

```
ffffffff812c16c0-ffffffff812c17ed: vmpressure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void vmpressure(gfp_t gfp, struct mem_cgroup *memcg, bool tree, long unsigned int scanned, long unsigned int reclaimed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmpressure.c (ffffffff812b2710)
Location: mm/vmpressure.c:240
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmpressure.c:vmpressure_prio
```
**Symbols:**

```
ffffffff812b2710-ffffffff812b283d: vmpressure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void vmpressure(gfp_t gfp, struct mem_cgroup *memcg, bool tree, long unsigned int scanned, long unsigned int reclaimed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmpressure.c (ffffffff812bf4d0)
Location: mm/vmpressure.c:240
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmpressure.c:vmpressure_prio
```
**Symbols:**

```
ffffffff812bf4d0-ffffffff812bf5fd: vmpressure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void vmpressure(gfp_t gfp, struct mem_cgroup *memcg, bool tree, long unsigned int scanned, long unsigned int reclaimed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmpressure.c (ffffffff812cff30)
Location: mm/vmpressure.c:240
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmpressure.c:vmpressure_prio
```
**Symbols:**

```
ffffffff812cff30-ffffffff812d005d: vmpressure (STB_GLOBAL)
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
<b>Param added. </b>
<code>bool tree</code>
</li>
<li>
<b>Param reordered. </b>
<code>gfp, memcg, scanned, reclaimed</code> ➡️ <code>gfp, memcg, tree, scanned, reclaimed</code>
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
