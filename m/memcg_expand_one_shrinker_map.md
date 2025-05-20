# Function: <code>memcg_expand_one_shrinker_map</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8129835a)
Location: mm/memcontrol.c:326
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_expand_shrinker_maps
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
In mm/memcontrol.c (ffffffff812b364a)
Location: mm/memcontrol.c:325
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_expand_shrinker_maps
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
In mm/memcontrol.c (ffffffff812c639a)
Location: mm/memcontrol.c:331
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_expand_shrinker_maps
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int memcg_expand_one_shrinker_map(struct mem_cgroup *memcg, int size, int old_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812f5800)
Location: mm/memcontrol.c:322
Inline: False
Direct callers:
  - mm/memcontrol.c:memcg_expand_shrinker_maps
```
**Symbols:**

```
ffffffff812f5800-ffffffff812f593c: memcg_expand_one_shrinker_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int memcg_expand_one_shrinker_map(struct mem_cgroup *memcg, int size, int old_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81300db0)
Location: mm/memcontrol.c:408
Inline: False
Direct callers:
  - mm/memcontrol.c:memcg_expand_shrinker_maps
```
**Symbols:**

```
ffffffff81300db0-ffffffff81300eec: memcg_expand_one_shrinker_map (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In mm/memcontrol.c (ffff8000103690cc)
Location: mm/memcontrol.c:331
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_expand_shrinker_maps
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
In mm/memcontrol.c (c055a650)
Location: mm/memcontrol.c:331
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_expand_shrinker_maps
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
In mm/memcontrol.c (c00000000045763c)
Location: mm/memcontrol.c:331
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_expand_shrinker_maps
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
In mm/memcontrol.c (ffffffe000246c9e)
Location: mm/memcontrol.c:331
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_expand_shrinker_maps
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
In mm/memcontrol.c (ffffffff812be97a)
Location: mm/memcontrol.c:331
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_expand_shrinker_maps
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
In mm/memcontrol.c (ffffffff812afa6a)
Location: mm/memcontrol.c:331
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_expand_shrinker_maps
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
In mm/memcontrol.c (ffffffff812bc78a)
Location: mm/memcontrol.c:331
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_expand_shrinker_maps
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
In mm/memcontrol.c (ffffffff812ccf6a)
Location: mm/memcontrol.c:331
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_expand_shrinker_maps
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
</ul>
