# Function: <code>mem_cgroup_from_obj</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct mem_cgroup *mem_cgroup_from_obj(void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c6ed0)
Location: mm/memcontrol.c:2798
Inline: False
Direct callers:
  - mm/memcontrol.c:mod_memcg_obj_state
```
**Symbols:**

```
ffffffff812c6ed0-ffffffff812c6f5f: mem_cgroup_from_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct mem_cgroup *mem_cgroup_from_obj(void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812fc7f0)
Location: mm/memcontrol.c:2678
Inline: False
Direct callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
  - mm/memcontrol.c:mod_memcg_obj_state
  - mm/memcontrol.c:__mod_lruvec_slab_state
```
**Symbols:**

```
ffffffff812fc7f0-ffffffff812fc87f: mem_cgroup_from_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct mem_cgroup *mem_cgroup_from_obj(void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81308ad0)
Location: mm/memcontrol.c:2964
Inline: False
Direct callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
  - mm/memcontrol.c:__mod_lruvec_kmem_state
```
**Symbols:**

```
ffffffff81308ad0-ffffffff81308bae: mem_cgroup_from_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct mem_cgroup *mem_cgroup_from_obj(void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8130f210)
Location: mm/memcontrol.c:2796
Inline: False
Direct callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
  - mm/memcontrol.c:__mod_lruvec_kmem_state
```
**Symbols:**

```
ffffffff8130f210-ffffffff8130f2ef: mem_cgroup_from_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_from_obj(void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:2864
Inline: False
Direct callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
  - mm/memcontrol.c:__mod_lruvec_kmem_state
```
**Symbols:**

```
ffffffff81cc2b0e-ffffffff81cc2b51: mem_cgroup_from_obj.cold (STB_LOCAL)
ffffffff8135a080-ffffffff8135a1d4: mem_cgroup_from_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_from_obj(void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:2857
Inline: False
Direct callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
  - mm/memcontrol.c:__mod_lruvec_kmem_state
```
**Symbols:**

```
ffffffff81e75093-ffffffff81e750cd: mem_cgroup_from_obj.cold (STB_LOCAL)
ffffffff813d3440-ffffffff813d360c: mem_cgroup_from_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_from_obj(void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:2965
Inline: False
```
**Symbols:**

```
ffffffff820681dc-ffffffff8206821b: mem_cgroup_from_obj.cold (STB_LOCAL)
ffffffff81458c10-ffffffff81458e08: mem_cgroup_from_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_from_obj(void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:2975
Inline: False
```
**Symbols:**

```
ffffffff820e7ac6-ffffffff820e7b00: mem_cgroup_from_obj.cold (STB_LOCAL)
ffffffff8148e890-ffffffff8148ea91: mem_cgroup_from_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_from_obj(void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:3090
Inline: False
```
**Symbols:**

```
ffffffff821c47ef-ffffffff821c4829: mem_cgroup_from_obj.cold (STB_LOCAL)
ffffffff814be250-ffffffff814be44b: mem_cgroup_from_obj (STB_GLOBAL)
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
struct mem_cgroup *mem_cgroup_from_obj(void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff800010369c80)
Location: mm/memcontrol.c:2798
Inline: False
Direct callers:
  - mm/memcontrol.c:mod_memcg_obj_state
```
**Symbols:**

```
ffff800010369c80-ffff800010369d20: mem_cgroup_from_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct mem_cgroup *mem_cgroup_from_obj(void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c055afe0)
Location: mm/memcontrol.c:2798
Inline: False
Direct callers:
  - mm/memcontrol.c:mod_memcg_obj_state
```
**Symbols:**

```
c055afe0-c055b078: mem_cgroup_from_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct mem_cgroup *mem_cgroup_from_obj(void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c000000000458810)
Location: mm/memcontrol.c:2798
Inline: False
Direct callers:
  - mm/memcontrol.c:mod_memcg_obj_state
```
**Symbols:**

```
c000000000458810-c0000000004588b8: mem_cgroup_from_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct mem_cgroup *mem_cgroup_from_obj(void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffe000247514)
Location: mm/memcontrol.c:2798
Inline: False
Direct callers:
  - mm/memcontrol.c:mod_memcg_obj_state
```
**Symbols:**

```
ffffffe000247514-ffffffe0002475a0: mem_cgroup_from_obj (STB_GLOBAL)
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
struct mem_cgroup *mem_cgroup_from_obj(void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bf4b0)
Location: mm/memcontrol.c:2798
Inline: False
Direct callers:
  - mm/memcontrol.c:mod_memcg_obj_state
```
**Symbols:**

```
ffffffff812bf4b0-ffffffff812bf53f: mem_cgroup_from_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct mem_cgroup *mem_cgroup_from_obj(void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b05a0)
Location: mm/memcontrol.c:2798
Inline: False
Direct callers:
  - mm/memcontrol.c:mod_memcg_obj_state
```
**Symbols:**

```
ffffffff812b05a0-ffffffff812b062f: mem_cgroup_from_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct mem_cgroup *mem_cgroup_from_obj(void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bd2c0)
Location: mm/memcontrol.c:2798
Inline: False
Direct callers:
  - mm/memcontrol.c:mod_memcg_obj_state
```
**Symbols:**

```
ffffffff812bd2c0-ffffffff812bd34f: mem_cgroup_from_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct mem_cgroup *mem_cgroup_from_obj(void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812cdb20)
Location: mm/memcontrol.c:2798
Inline: False
Direct callers:
  - mm/memcontrol.c:mod_memcg_obj_state
```
**Symbols:**

```
ffffffff812cdb20-ffffffff812cdbaf: mem_cgroup_from_obj (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
