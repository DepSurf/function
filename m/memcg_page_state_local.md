# Function: <code>memcg_page_state_local</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812afb6d)
Location: include/linux/memcontrol.h:572
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:mem_cgroup_nr_lru_pages
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
In mm/memcontrol.c (ffffffff812c15dd)
Location: include/linux/memcontrol.h:608
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:mem_cgroup_nr_lru_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812f8319)
Location: include/linux/memcontrol.h:585
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81303dc9)
Location: include/linux/memcontrol.h:903
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
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
In mm/memcontrol.c (ffffffff81309f65)
Location: mm/memcontrol.c:661
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
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
In mm/memcontrol.c (ffffffff81354310)
Location: mm/memcontrol.c:707
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
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
In mm/memcontrol.c (ffffffff813cbff0)
Location: mm/memcontrol.c:681
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int memcg_page_state_local(struct mem_cgroup *memcg, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8144f920)
Location: mm/memcontrol.c:751
Inline: False
Direct callers:
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
```
**Symbols:**

```
ffffffff8144f920-ffffffff8144fa05: memcg_page_state_local (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int memcg_page_state_local(struct mem_cgroup *memcg, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81484f30)
Location: mm/memcontrol.c:776
Inline: False
Direct callers:
  - mm/memcontrol.c:memcg_numa_stat_show
```
**Symbols:**

```
ffffffff81484f30-ffffffff81485015: memcg_page_state_local (STB_LOCAL)
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
In mm/memcontrol.c (ffffffff814b5b35)
Location: mm/memcontrol.c:827
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_numa_stat_show
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
In mm/memcontrol.c (ffff8000103630d4)
Location: include/linux/memcontrol.h:608
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:mem_cgroup_nr_lru_pages
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
In mm/memcontrol.c (c05556d0)
Location: include/linux/memcontrol.h:608
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
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
In mm/memcontrol.c (c00000000044fde4)
Location: include/linux/memcontrol.h:608
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:mem_cgroup_nr_lru_pages
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
In mm/memcontrol.c (ffffffe0002427e4)
Location: include/linux/memcontrol.h:608
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
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
In mm/memcontrol.c (ffffffff812b9bbd)
Location: include/linux/memcontrol.h:608
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:mem_cgroup_nr_lru_pages
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
In mm/memcontrol.c (ffffffff812aae4d)
Location: include/linux/memcontrol.h:608
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:mem_cgroup_nr_lru_pages
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
In mm/memcontrol.c (ffffffff812b79cd)
Location: include/linux/memcontrol.h:608
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:mem_cgroup_nr_lru_pages
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
In mm/memcontrol.c (ffffffff812c82bd)
Location: include/linux/memcontrol.h:608
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:mem_cgroup_nr_lru_pages
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
</ul>
