# Function: <code>mem_cgroup_throttle_swaprate</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
void mem_cgroup_throttle_swaprate(struct mem_cgroup *memcg, int node, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81262a50)
Location: mm/swapfile.c:3727
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_delay
```
**Symbols:**

```
ffffffff81262a50-ffffffff81262b68: mem_cgroup_throttle_swaprate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void mem_cgroup_throttle_swaprate(struct mem_cgroup *memcg, int node, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8127d940)
Location: mm/swapfile.c:3732
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_delay
```
**Symbols:**

```
ffffffff8127d940-ffffffff8127da6b: mem_cgroup_throttle_swaprate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void mem_cgroup_throttle_swaprate(struct mem_cgroup *memcg, int node, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8128d3e0)
Location: mm/swapfile.c:3740
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_delay
```
**Symbols:**

```
ffffffff8128d3e0-ffffffff8128d50b: mem_cgroup_throttle_swaprate (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
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
<summary>In <code>arm64</code>: ✅</summary>

```c
void mem_cgroup_throttle_swaprate(struct mem_cgroup *memcg, int node, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffff800010328c48)
Location: mm/swapfile.c:3740
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_delay
```
**Symbols:**

```
ffff800010328c48-ffff800010328dcc: mem_cgroup_throttle_swaprate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mem_cgroup_throttle_swaprate(struct mem_cgroup *memcg, int node, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (c053ffec)
Location: mm/swapfile.c:3740
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_delay
```
**Symbols:**

```
c053ffec-c0540134: mem_cgroup_throttle_swaprate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mem_cgroup_throttle_swaprate(struct mem_cgroup *memcg, int node, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (c000000000400020)
Location: mm/swapfile.c:3740
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_delay
```
**Symbols:**

```
c000000000400020-c0000000004001cc: mem_cgroup_throttle_swaprate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void mem_cgroup_throttle_swaprate(struct mem_cgroup *memcg, int node, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffe0002289fc)
Location: mm/swapfile.c:3740
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_delay
```
**Symbols:**

```
ffffffe0002289fc-ffffffe000228b30: mem_cgroup_throttle_swaprate (STB_GLOBAL)
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
void mem_cgroup_throttle_swaprate(struct mem_cgroup *memcg, int node, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812859c0)
Location: mm/swapfile.c:3740
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_delay
```
**Symbols:**

```
ffffffff812859c0-ffffffff81285aeb: mem_cgroup_throttle_swaprate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void mem_cgroup_throttle_swaprate(struct mem_cgroup *memcg, int node, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81277830)
Location: mm/swapfile.c:3740
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_delay
```
**Symbols:**

```
ffffffff81277830-ffffffff8127795b: mem_cgroup_throttle_swaprate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void mem_cgroup_throttle_swaprate(struct mem_cgroup *memcg, int node, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812837d0)
Location: mm/swapfile.c:3740
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_delay
```
**Symbols:**

```
ffffffff812837d0-ffffffff812838fb: mem_cgroup_throttle_swaprate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void mem_cgroup_throttle_swaprate(struct mem_cgroup *memcg, int node, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812934d0)
Location: mm/swapfile.c:3740
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_delay
```
**Symbols:**

```
ffffffff812934d0-ffffffff812935eb: mem_cgroup_throttle_swaprate (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
