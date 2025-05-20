# Function: <code>memcg_free_shrinker_maps</code>

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
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff81293c7e)
Location: mm/memcontrol.c:356
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_online
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_online
```
**Symbols:**

```
ffffffff81293a30-ffffffff81293ac7: memcg_free_shrinker_maps.part.48 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff812af9c7)
Location: mm/memcontrol.c:355
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_online
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_online
```
**Symbols:**

```
ffffffff812af770-ffffffff812af807: memcg_free_shrinker_maps.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff812c143a)
Location: mm/memcontrol.c:361
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_online
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_online
```
**Symbols:**

```
ffffffff812c11d0-ffffffff812c1267: memcg_free_shrinker_maps.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff812f60e4)
Location: mm/memcontrol.c:352
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:memcg_alloc_shrinker_maps
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:memcg_alloc_shrinker_maps
```
**Symbols:**

```
ffffffff812f59a0-ffffffff812f5a37: memcg_free_shrinker_maps.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff813038e4)
Location: mm/memcontrol.c:438
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:memcg_alloc_shrinker_maps
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:memcg_alloc_shrinker_maps
```
**Symbols:**

```
ffffffff81300f80-ffffffff81301017: memcg_free_shrinker_maps.part.0 (STB_LOCAL)
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
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffff800010364458)
Location: mm/memcontrol.c:361
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_online
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_online
```
**Symbols:**

```
ffff800010362438-ffff8000103624d8: memcg_free_shrinker_maps.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void memcg_free_shrinker_maps(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c05547b4)
Location: mm/memcontrol.c:361
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_online
```
**Symbols:**

```
c05547b4-c05547fc: memcg_free_shrinker_maps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (c00000000044faf0)
Location: mm/memcontrol.c:361
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_online
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_online
```
**Symbols:**

```
c00000000044f760-c00000000044f860: memcg_free_shrinker_maps.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void memcg_free_shrinker_maps(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffe0002416d0)
Location: mm/memcontrol.c:361
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_online
```
**Symbols:**

```
ffffffe0002416d0-ffffffe000241716: memcg_free_shrinker_maps (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff812b9a1a)
Location: mm/memcontrol.c:361
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_online
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_online
```
**Symbols:**

```
ffffffff812b97b0-ffffffff812b9847: memcg_free_shrinker_maps.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff812aacaa)
Location: mm/memcontrol.c:361
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_online
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_online
```
**Symbols:**

```
ffffffff812aaa40-ffffffff812aaad7: memcg_free_shrinker_maps.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff812b782a)
Location: mm/memcontrol.c:361
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_online
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_online
```
**Symbols:**

```
ffffffff812b75c0-ffffffff812b7657: memcg_free_shrinker_maps.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff812c811a)
Location: mm/memcontrol.c:361
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_online
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_online
```
**Symbols:**

```
ffffffff812c7ea0-ffffffff812c7f37: memcg_free_shrinker_maps.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
