# Function: <code>memcg_alloc_cache_id</code>

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
In mm/memcontrol.c (ffffffff811f9d22)
Location: mm/memcontrol.c:2242
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_activate_kmem
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81894c0e)
Location: mm/memcontrol.c:2127
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff818c9333)
Location: mm/memcontrol.c:2098
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff819008ac)
Location: mm/memcontrol.c:2109
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8198a8b9)
Location: mm/memcontrol.c:2136
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff819e71b5)
Location: mm/memcontrol.c:2123
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81a22628)
Location: mm/memcontrol.c:2419
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
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
In mm/memcontrol.c (ffffffff81a92674)
Location: mm/memcontrol.c:2620
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
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
In mm/memcontrol.c (ffffffff81ac9e24)
Location: mm/memcontrol.c:2819
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int memcg_alloc_cache_id();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812f5730)
Location: mm/memcontrol.c:2699
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
**Symbols:**

```
ffffffff812f5730-ffffffff812f57f8: memcg_alloc_cache_id (STB_LOCAL)
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
In mm/memcontrol.c (ffffffff8130131c)
Location: mm/memcontrol.c:3025
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_online_kmem
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
In mm/memcontrol.c (ffffffff8130794c)
Location: mm/memcontrol.c:2857
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_online_kmem
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
In mm/memcontrol.c (ffffffff813513ab)
Location: mm/memcontrol.c:2925
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_online_kmem
```
</details>
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
In mm/memcontrol.c (ffff800010d9d6f8)
Location: mm/memcontrol.c:2819
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
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
In mm/memcontrol.c (c0e98e8c)
Location: mm/memcontrol.c:2819
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
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
In mm/memcontrol.c (c00000000045bd80)
Location: mm/memcontrol.c:2819
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
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
In mm/memcontrol.c (ffffffe0008c496c)
Location: mm/memcontrol.c:2819
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
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
In mm/memcontrol.c (ffffffff81a68c94)
Location: mm/memcontrol.c:2819
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
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
In mm/memcontrol.c (ffffffff81a25754)
Location: mm/memcontrol.c:2819
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
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
In mm/memcontrol.c (ffffffff81ad50a4)
Location: mm/memcontrol.c:2819
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
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
In mm/memcontrol.c (ffffffff81ae1574)
Location: mm/memcontrol.c:2819
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
