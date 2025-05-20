# Function: <code>expand_one_shrinker_info</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int expand_one_shrinker_info(struct mem_cgroup *memcg, int map_size, int defer_size, int old_map_size, int old_defer_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81273190)
Location: mm/vmscan.c:211
Inline: False
Direct callers:
  - mm/vmscan.c:prealloc_shrinker
```
**Symbols:**

```
ffffffff81273190-ffffffff81273311: expand_one_shrinker_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int expand_one_shrinker_info(struct mem_cgroup *memcg, int map_size, int defer_size, int old_map_size, int old_defer_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812b0520)
Location: mm/vmscan.c:215
Inline: False
Direct callers:
  - mm/vmscan.c:prealloc_shrinker
```
**Symbols:**

```
ffffffff812b0520-ffffffff812b06a1: expand_one_shrinker_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int expand_one_shrinker_info(struct mem_cgroup *memcg, int map_size, int defer_size, int old_map_size, int old_defer_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8130be00)
Location: mm/vmscan.c:217
Inline: False
Direct callers:
  - mm/vmscan.c:prealloc_shrinker
```
**Symbols:**

```
ffffffff8130be00-ffffffff8130bf7f: expand_one_shrinker_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int expand_one_shrinker_info(struct mem_cgroup *memcg, int map_size, int defer_size, int old_map_size, int old_defer_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813772f0)
Location: mm/vmscan.c:231
Inline: False
Direct callers:
  - mm/vmscan.c:__prealloc_shrinker
```
**Symbols:**

```
ffffffff813772f0-ffffffff81377464: expand_one_shrinker_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int expand_one_shrinker_info(struct mem_cgroup *memcg, int map_size, int defer_size, int old_map_size, int old_defer_size, int new_nr_max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813a9570)
Location: mm/vmscan.c:215
Inline: False
Direct callers:
  - mm/vmscan.c:__prealloc_shrinker
```
**Symbols:**

```
ffffffff813a9570-ffffffff813a976e: expand_one_shrinker_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int expand_one_shrinker_info(struct mem_cgroup *memcg, int new_size, int old_size, int new_nr_max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shrinker.c (ffffffff813e3b10)
Location: mm/shrinker.c:111
Inline: False
Direct callers:
  - mm/shrinker.c:shrinker_alloc
```
**Symbols:**

```
ffffffff813e3b10-ffffffff813e3d95: expand_one_shrinker_info (STB_LOCAL)
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int new_nr_max</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int new_size</code>
</li>
<li>
<b>Param added. </b>
<code>int old_size</code>
</li>
<li>
<b>Param removed. </b>
<code>int map_size</code>
</li>
<li>
<b>Param removed. </b>
<code>int defer_size</code>
</li>
<li>
<b>Param removed. </b>
<code>int old_map_size</code>
</li>
<li>
<b>Param removed. </b>
<code>int old_defer_size</code>
</li>
<li>
<b>Param reordered. </b>
<code>memcg, map_size, defer_size, old_map_size, old_defer_size, new_nr_max</code> ➡️ <code>memcg, new_size, old_size, new_nr_max</code>
</li>
</ul>
</details>
</li>
</ul>
