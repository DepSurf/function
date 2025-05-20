# Function: <code>cancel_charge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void cancel_charge(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff811fb480)
Location: mm/memcontrol.c:2164
Inline: False
Direct callers:
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_cancel_charge
```
**Symbols:**

```
ffffffff811fb480-ffffffff811fb4ff: cancel_charge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cancel_charge(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8121f000)
Location: mm/memcontrol.c:2049
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:memcg_kmem_charge_memcg
```
**Symbols:**

```
ffffffff8121f000-ffffffff8121f07b: cancel_charge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cancel_charge(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81231510)
Location: mm/memcontrol.c:2020
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:memcg_kmem_charge_memcg
```
**Symbols:**

```
ffffffff81231510-ffffffff8123158b: cancel_charge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff81242062)
Location: mm/memcontrol.c:2031
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:memcg_kmem_charge_memcg
Direct callers:
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:memcg_kmem_charge_memcg
```
**Symbols:**

```
ffffffff8123cd40-ffffffff8123cdbd: cancel_charge.part.34 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff81261da6)
Location: mm/memcontrol.c:2058
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:memcg_kmem_charge_memcg
Direct callers:
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:memcg_kmem_charge_memcg
```
**Symbols:**

```
ffffffff8125c210-ffffffff8125c292: cancel_charge.part.37 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff81285db6)
Location: mm/memcontrol.c:2045
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:memcg_kmem_charge_memcg
Direct callers:
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:memcg_kmem_charge_memcg
```
**Symbols:**

```
ffffffff812804d0-ffffffff81280552: cancel_charge.part.38 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff8129ad16)
Location: mm/memcontrol.c:2341
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:memcg_kmem_charge_memcg
Direct callers:
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:memcg_kmem_charge_memcg
```
**Symbols:**

```
ffffffff81295080-ffffffff81295102: cancel_charge.part.40 (STB_LOCAL)
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
In mm/memcontrol.c (ffffffff812b5f9e)
Location: mm/memcontrol.c:2542
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__memcg_kmem_charge_memcg
Direct callers:
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__memcg_kmem_charge_memcg
```
**Symbols:**

```
ffffffff812b0fd0-ffffffff812b104a: cancel_charge.part.0 (STB_LOCAL)
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
In mm/memcontrol.c (ffffffff812c7e8e)
Location: mm/memcontrol.c:2714
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__memcg_kmem_charge_memcg
Direct callers:
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__memcg_kmem_charge_memcg
```
**Symbols:**

```
ffffffff812c2a30-ffffffff812c2aaa: cancel_charge.part.0 (STB_LOCAL)
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
In mm/memcontrol.c (ffffffff812f9c9a)
Location: mm/memcontrol.c:2644
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
```
**Symbols:**

```
ffffffff812f7fb0-ffffffff812f8029: cancel_charge.part.0 (STB_LOCAL)
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
In mm/memcontrol.c (ffffffff8130520a)
Location: mm/memcontrol.c:2907
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
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
In mm/memcontrol.c (ffffffff8130aaea)
Location: mm/memcontrol.c:2702
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:obj_cgroup_charge_pages
  - mm/memcontrol.c:obj_cgroup_charge_pages
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
In mm/memcontrol.c (ffffffff8135321a)
Location: mm/memcontrol.c:2770
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:obj_cgroup_charge_pages
  - mm/memcontrol.c:obj_cgroup_charge_pages
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
In mm/memcontrol.c (ffffffff813cdd3a)
Location: mm/memcontrol.c:2760
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81452e1a)
Location: mm/memcontrol.c:2830
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81488a6a)
Location: mm/memcontrol.c:2840
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
```
</details>
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
In mm/memcontrol.c (ffff80001036adac)
Location: mm/memcontrol.c:2714
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__memcg_kmem_charge_memcg
Direct callers:
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__memcg_kmem_charge_memcg
```
**Symbols:**

```
ffff800010365200-ffff800010365278: cancel_charge.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (c055c3f0)
Location: mm/memcontrol.c:2714
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__memcg_kmem_charge_memcg
Direct callers:
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__memcg_kmem_charge_memcg
```
**Symbols:**

```
c0556d70-c0556e3c: cancel_charge.part.0 (STB_LOCAL)
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
In mm/memcontrol.c (c00000000045a35c)
Location: mm/memcontrol.c:2714
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__memcg_kmem_charge_memcg
Direct callers:
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__memcg_kmem_charge_memcg
```
**Symbols:**

```
c000000000451aa0-c000000000451bbc: cancel_charge.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffe000248546)
Location: mm/memcontrol.c:2714
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__memcg_kmem_charge_memcg
Direct callers:
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__memcg_kmem_charge_memcg
```
**Symbols:**

```
ffffffe000243a74-ffffffe000243b30: cancel_charge.part.0 (STB_LOCAL)
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
In mm/memcontrol.c (ffffffff812c046e)
Location: mm/memcontrol.c:2714
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__memcg_kmem_charge_memcg
Direct callers:
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__memcg_kmem_charge_memcg
```
**Symbols:**

```
ffffffff812bb010-ffffffff812bb08a: cancel_charge.part.0 (STB_LOCAL)
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
In mm/memcontrol.c (ffffffff812b153e)
Location: mm/memcontrol.c:2714
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__memcg_kmem_charge_memcg
Direct callers:
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__memcg_kmem_charge_memcg
```
**Symbols:**

```
ffffffff812ac190-ffffffff812ac20a: cancel_charge.part.0 (STB_LOCAL)
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
In mm/memcontrol.c (ffffffff812be27e)
Location: mm/memcontrol.c:2714
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__memcg_kmem_charge_memcg
Direct callers:
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__memcg_kmem_charge_memcg
```
**Symbols:**

```
ffffffff812b8e20-ffffffff812b8e9a: cancel_charge.part.0 (STB_LOCAL)
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
In mm/memcontrol.c (ffffffff812cec6e)
Location: mm/memcontrol.c:2714
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__memcg_kmem_charge_memcg
Direct callers:
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__memcg_kmem_charge_memcg
```
**Symbols:**

```
ffffffff812c9430-ffffffff812c94bc: cancel_charge.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
