# Function: <code>get_mem_cgroup_from_current</code>

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
In mm/memcontrol.c (ffffffff8129a340)
Location: mm/memcontrol.c:879
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_get_cache
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
In mm/memcontrol.c (ffffffff812b55dd)
Location: mm/memcontrol.c:996
Inline: True
Inline callers:
  - mm/memcontrol.c:__memcg_kmem_charge
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
In mm/memcontrol.c (ffffffff812c728d)
Location: mm/memcontrol.c:1007
Inline: True
Inline callers:
  - mm/memcontrol.c:__memcg_kmem_charge
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
In mm/memcontrol.c (ffffffff812fcd5c)
Location: mm/memcontrol.c:969
Inline: True
Inline callers:
  - mm/memcontrol.c:__memcg_kmem_charge_page
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
In mm/memcontrol.c (ffffffff81308f35)
Location: mm/memcontrol.c:1107
Inline: True
Inline callers:
  - mm/memcontrol.c:__memcg_kmem_charge_page
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
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct mem_cgroup *get_mem_cgroup_from_current();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814bb3c0)
Location: mm/memcontrol.c:1120
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_hugetlb_folio
```
**Symbols:**

```
ffffffff814bb3c0-ffffffff814bb463: get_mem_cgroup_from_current (STB_GLOBAL)
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
In mm/memcontrol.c (ffff80001036a0b4)
Location: mm/memcontrol.c:1007
Inline: True
Inline callers:
  - mm/memcontrol.c:__memcg_kmem_charge
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
In mm/memcontrol.c (c055b4c0)
Location: mm/memcontrol.c:1007
Inline: True
Inline callers:
  - mm/memcontrol.c:__memcg_kmem_charge
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
In mm/memcontrol.c (c000000000458e24)
Location: mm/memcontrol.c:1007
Inline: True
Inline callers:
  - mm/memcontrol.c:__memcg_kmem_charge
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
In mm/memcontrol.c (ffffffe0002478f2)
Location: mm/memcontrol.c:1007
Inline: True
Inline callers:
  - mm/memcontrol.c:__memcg_kmem_charge
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
In mm/memcontrol.c (ffffffff812bf86d)
Location: mm/memcontrol.c:1007
Inline: True
Inline callers:
  - mm/memcontrol.c:__memcg_kmem_charge
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
In mm/memcontrol.c (ffffffff812b094d)
Location: mm/memcontrol.c:1007
Inline: True
Inline callers:
  - mm/memcontrol.c:__memcg_kmem_charge
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
In mm/memcontrol.c (ffffffff812bd67d)
Location: mm/memcontrol.c:1007
Inline: True
Inline callers:
  - mm/memcontrol.c:__memcg_kmem_charge
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
In mm/memcontrol.c (ffffffff812cdf65)
Location: mm/memcontrol.c:1007
Inline: True
Inline callers:
  - mm/memcontrol.c:__memcg_kmem_charge
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
