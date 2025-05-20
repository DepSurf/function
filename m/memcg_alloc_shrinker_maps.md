# Function: <code>memcg_alloc_shrinker_maps</code>

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
In mm/memcontrol.c (ffffffff81294005)
Location: mm/memcontrol.c:374
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
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
In mm/memcontrol.c (ffffffff812b0235)
Location: mm/memcontrol.c:373
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
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
In mm/memcontrol.c (ffffffff812c1d25)
Location: mm/memcontrol.c:379
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int memcg_alloc_shrinker_maps(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812f5a40)
Location: mm/memcontrol.c:370
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_online
```
**Symbols:**

```
ffffffff812f5a40-ffffffff812f5b2a: memcg_alloc_shrinker_maps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int memcg_alloc_shrinker_maps(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81301020)
Location: mm/memcontrol.c:456
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_online
```
**Symbols:**

```
ffffffff81301020-ffffffff8130110a: memcg_alloc_shrinker_maps (STB_LOCAL)
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
In mm/memcontrol.c (ffff800010366210)
Location: mm/memcontrol.c:379
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
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
In mm/memcontrol.c (c0556918)
Location: mm/memcontrol.c:379
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
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
In mm/memcontrol.c (c00000000045098c)
Location: mm/memcontrol.c:379
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
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
In mm/memcontrol.c (ffffffe000243074)
Location: mm/memcontrol.c:379
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
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
In mm/memcontrol.c (ffffffff812ba305)
Location: mm/memcontrol.c:379
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
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
In mm/memcontrol.c (ffffffff812ab4c5)
Location: mm/memcontrol.c:379
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
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
In mm/memcontrol.c (ffffffff812b8115)
Location: mm/memcontrol.c:379
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
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
In mm/memcontrol.c (ffffffff812c8a45)
Location: mm/memcontrol.c:379
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
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
