# Function: <code>drain_all_stock</code>

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
In mm/memcontrol.c (ffffffff811fbb66)
Location: mm/memcontrol.c:1951
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff81222b24)
Location: mm/memcontrol.c:1818
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge
```
**Symbols:**

```
ffffffff8121f170-ffffffff8121f279: drain_all_stock.part.31 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff812318e0)
Location: mm/memcontrol.c:1789
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge
```
**Symbols:**

```
ffffffff81231680-ffffffff8123179a: drain_all_stock.part.32 (STB_LOCAL)
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
In mm/memcontrol.c (ffffffff8123d107)
Location: mm/memcontrol.c:1800
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge
```
**Symbols:**

```
ffffffff8123ceb0-ffffffff8123cfc5: drain_all_stock.part.35 (STB_LOCAL)
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
In mm/memcontrol.c (ffffffff8125cc89)
Location: mm/memcontrol.c:1821
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge
```
**Symbols:**

```
ffffffff8125c9d0-ffffffff8125cb50: drain_all_stock.part.36 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void drain_all_stock(struct mem_cgroup *root_memcg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81280660)
Location: mm/memcontrol.c:1773
Inline: True
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge
```
**Symbols:**

```
ffffffff81280660-ffffffff812807fc: drain_all_stock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void drain_all_stock(struct mem_cgroup *root_memcg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81295210)
Location: mm/memcontrol.c:2051
Inline: True
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge
```
**Symbols:**

```
ffffffff81295210-ffffffff8129539c: drain_all_stock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void drain_all_stock(struct mem_cgroup *root_memcg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b11d0)
Location: mm/memcontrol.c:2252
Inline: True
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge
```
**Symbols:**

```
ffffffff812b11d0-ffffffff812b134c: drain_all_stock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void drain_all_stock(struct mem_cgroup *root_memcg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c2c30)
Location: mm/memcontrol.c:2268
Inline: True
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge
```
**Symbols:**

```
ffffffff812c2c30-ffffffff812c2d2f: drain_all_stock (STB_LOCAL)
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
In mm/memcontrol.c (ffffffff812f9043)
Location: mm/memcontrol.c:2145
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge
```
**Symbols:**

```
ffffffff812f8780-ffffffff812f887b: drain_all_stock.part.0 (STB_LOCAL)
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
In mm/memcontrol.c (ffffffff81304f54)
Location: mm/memcontrol.c:2368
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge
```
**Symbols:**

```
ffffffff81304580-ffffffff8130470a: drain_all_stock.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff8130bf54)
Location: mm/memcontrol.c:2177
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge
```
**Symbols:**

```
ffffffff8130b580-ffffffff8130b70a: drain_all_stock.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff81357241)
Location: mm/memcontrol.c:2276
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge_memcg
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge_memcg
```
**Symbols:**

```
ffffffff813567c0-ffffffff813569bb: drain_all_stock.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff813d002c)
Location: mm/memcontrol.c:2266
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge_memcg
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge_memcg
```
**Symbols:**

```
ffffffff813cf6f0-ffffffff813cf895: drain_all_stock.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff814554ac)
Location: mm/memcontrol.c:2326
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge_memcg
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge_memcg
```
**Symbols:**

```
ffffffff814549f0-ffffffff81454ba1: drain_all_stock.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff8148b2cc)
Location: mm/memcontrol.c:2336
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge_memcg
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge_memcg
```
**Symbols:**

```
ffffffff8148a7e0-ffffffff8148a9c0: drain_all_stock.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff814babcc)
Location: mm/memcontrol.c:2408
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge_memcg
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge_memcg
```
**Symbols:**

```
ffffffff814ba090-ffffffff814ba283: drain_all_stock.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void drain_all_stock(struct mem_cgroup *root_memcg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff800010365570)
Location: mm/memcontrol.c:2268
Inline: True
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge
```
**Symbols:**

```
ffff800010365570-ffff800010365730: drain_all_stock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void drain_all_stock(struct mem_cgroup *root_memcg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c0557044)
Location: mm/memcontrol.c:2268
Inline: True
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge
```
**Symbols:**

```
c0557044-c055719c: drain_all_stock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void drain_all_stock(struct mem_cgroup *root_memcg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c000000000452040)
Location: mm/memcontrol.c:2268
Inline: True
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge
```
**Symbols:**

```
c000000000452040-c00000000045222c: drain_all_stock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void drain_all_stock(struct mem_cgroup *root_memcg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffe000243d46)
Location: mm/memcontrol.c:2268
Inline: True
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge
```
**Symbols:**

```
ffffffe000243d46-ffffffe000243e86: drain_all_stock (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void drain_all_stock(struct mem_cgroup *root_memcg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bb210)
Location: mm/memcontrol.c:2268
Inline: True
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge
```
**Symbols:**

```
ffffffff812bb210-ffffffff812bb30f: drain_all_stock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void drain_all_stock(struct mem_cgroup *root_memcg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812ac380)
Location: mm/memcontrol.c:2268
Inline: True
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge
```
**Symbols:**

```
ffffffff812ac380-ffffffff812ac47f: drain_all_stock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void drain_all_stock(struct mem_cgroup *root_memcg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b9020)
Location: mm/memcontrol.c:2268
Inline: True
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge
```
**Symbols:**

```
ffffffff812b9020-ffffffff812b911f: drain_all_stock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void drain_all_stock(struct mem_cgroup *root_memcg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c9660)
Location: mm/memcontrol.c:2268
Inline: True
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge
```
**Symbols:**

```
ffffffff812c9660-ffffffff812c9793: drain_all_stock (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
