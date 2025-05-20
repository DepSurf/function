# Function: <code>mem_cgroup_id_put_many</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void mem_cgroup_id_put_many(struct mem_cgroup *memcg, unsigned int n);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8121eee0)
Location: mm/memcontrol.c:4098
Inline: True
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_css_offline
```
**Symbols:**

```
ffffffff8121eee0-ffffffff8121ef3e: mem_cgroup_id_put_many (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void mem_cgroup_id_put_many(struct mem_cgroup *memcg, unsigned int n);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812313f0)
Location: mm/memcontrol.c:4072
Inline: True
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_css_offline
```
**Symbols:**

```
ffffffff812313f0-ffffffff8123144e: mem_cgroup_id_put_many (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void mem_cgroup_id_put_many(struct mem_cgroup *memcg, unsigned int n);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8123cc20)
Location: mm/memcontrol.c:4092
Inline: True
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_css_offline
```
**Symbols:**

```
ffffffff8123cc20-ffffffff8123cc80: mem_cgroup_id_put_many (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void mem_cgroup_id_put_many(struct mem_cgroup *memcg, unsigned int n);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8125c0d0)
Location: mm/memcontrol.c:4119
Inline: True
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_css_offline
```
**Symbols:**

```
ffffffff8125c0d0-ffffffff8125c134: mem_cgroup_id_put_many (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mem_cgroup_id_put_many(struct mem_cgroup *memcg, unsigned int n);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff8127f8e0)
Location: mm/memcontrol.c:4054
Inline: True
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_css_offline
```
**Symbols:**

```
ffffffff8127f8e0-ffffffff8127f918: mem_cgroup_id_put_many.part.46 (STB_LOCAL)
ffffffff8127f920-ffffffff8127f96c: mem_cgroup_id_put_many (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mem_cgroup_id_put_many(struct mem_cgroup *memcg, unsigned int n);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff81294480)
Location: mm/memcontrol.c:4328
Inline: True
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_css_offline
```
**Symbols:**

```
ffffffff81294480-ffffffff812944b8: mem_cgroup_id_put_many.part.47 (STB_LOCAL)
ffffffff812944c0-ffffffff81294512: mem_cgroup_id_put_many (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void mem_cgroup_id_put_many(struct mem_cgroup *memcg, unsigned int n);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b1050)
Location: mm/memcontrol.c:4668
Inline: True
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_css_offline
```
**Symbols:**

```
ffffffff812b1050-ffffffff812b10c3: mem_cgroup_id_put_many (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void mem_cgroup_id_put_many(struct mem_cgroup *memcg, unsigned int n);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c2ab0)
Location: mm/memcontrol.c:4993
Inline: True
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_css_offline
```
**Symbols:**

```
ffffffff812c2ab0-ffffffff812c2b23: mem_cgroup_id_put_many (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void mem_cgroup_id_put_many(struct mem_cgroup *memcg, unsigned int n);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812f7570)
Location: mm/memcontrol.c:4875
Inline: True
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_css_offline
```
**Symbols:**

```
ffffffff812f7570-ffffffff812f760a: mem_cgroup_id_put_many (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void mem_cgroup_id_put_many(struct mem_cgroup *memcg, unsigned int n);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813033e0)
Location: mm/memcontrol.c:5137
Inline: True
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_css_offline
```
**Symbols:**

```
ffffffff813033e0-ffffffff81303486: mem_cgroup_id_put_many (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void mem_cgroup_id_put_many(struct mem_cgroup *memcg, unsigned int n);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81309900)
Location: mm/memcontrol.c:4905
Inline: True
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_css_offline
```
**Symbols:**

```
ffffffff81309900-ffffffff813099a6: mem_cgroup_id_put_many (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void mem_cgroup_id_put_many(struct mem_cgroup *memcg, unsigned int n);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81353140)
Location: mm/memcontrol.c:5072
Inline: True
Direct callers:
  - mm/memcontrol.c:__mem_cgroup_uncharge_swap
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_css_offline
```
**Symbols:**

```
ffffffff81353140-ffffffff813531e6: mem_cgroup_id_put_many (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void mem_cgroup_id_put_many(struct mem_cgroup *memcg, unsigned int n);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813cdc40)
Location: mm/memcontrol.c:5036
Inline: True
Direct callers:
  - mm/memcontrol.c:__mem_cgroup_uncharge_swap
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_css_offline
```
**Symbols:**

```
ffffffff813cdc40-ffffffff813cdd0f: mem_cgroup_id_put_many (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void mem_cgroup_id_put_many(struct mem_cgroup *memcg, unsigned int n);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81452300)
Location: mm/memcontrol.c:5157
Inline: True
Direct callers:
  - mm/memcontrol.c:__mem_cgroup_uncharge_swap
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_css_offline
```
**Symbols:**

```
ffffffff81452300-ffffffff814523cf: mem_cgroup_id_put_many (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void mem_cgroup_id_put_many(struct mem_cgroup *memcg, unsigned int n);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81487e10)
Location: mm/memcontrol.c:5184
Inline: True
Direct callers:
  - mm/memcontrol.c:__mem_cgroup_uncharge_swap
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_css_offline
```
**Symbols:**

```
ffffffff81487e10-ffffffff81487edf: mem_cgroup_id_put_many (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void mem_cgroup_id_put_many(struct mem_cgroup *memcg, unsigned int n);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814b7fe0)
Location: mm/memcontrol.c:5381
Inline: True
Direct callers:
  - mm/memcontrol.c:__mem_cgroup_uncharge_swap
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_css_offline
```
**Symbols:**

```
ffffffff814b7fe0-ffffffff814b80af: mem_cgroup_id_put_many (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mem_cgroup_id_put_many(struct mem_cgroup *memcg, unsigned int n);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffff800010365278)
Location: mm/memcontrol.c:4993
Inline: True
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_css_offline
```
**Symbols:**

```
ffff800010365278-ffff8000103652bc: mem_cgroup_id_put_many.part.0 (STB_LOCAL)
ffff8000103652c0-ffff800010365334: mem_cgroup_id_put_many (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mem_cgroup_id_put_many(struct mem_cgroup *memcg, unsigned int n);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (c0556be8)
Location: mm/memcontrol.c:4993
Inline: True
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_css_offline
```
**Symbols:**

```
c0556be8-c0556c70: mem_cgroup_id_put_many.part.0 (STB_LOCAL)
c0556c70-c0556ccc: mem_cgroup_id_put_many (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void mem_cgroup_id_put_many(struct mem_cgroup *memcg, unsigned int n);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c000000000451d00)
Location: mm/memcontrol.c:4993
Inline: True
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_css_offline
```
**Symbols:**

```
c000000000451d00-c000000000451e44: mem_cgroup_id_put_many (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mem_cgroup_id_put_many(struct mem_cgroup *memcg, unsigned int n);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffe000243850)
Location: mm/memcontrol.c:4993
Inline: True
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_css_offline
```
**Symbols:**

```
ffffffe000243850-ffffffe0002438c4: mem_cgroup_id_put_many.part.0 (STB_LOCAL)
ffffffe0002438c4-ffffffe00024393e: mem_cgroup_id_put_many (STB_LOCAL)
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
void mem_cgroup_id_put_many(struct mem_cgroup *memcg, unsigned int n);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bb090)
Location: mm/memcontrol.c:4993
Inline: True
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_css_offline
```
**Symbols:**

```
ffffffff812bb090-ffffffff812bb103: mem_cgroup_id_put_many (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void mem_cgroup_id_put_many(struct mem_cgroup *memcg, unsigned int n);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812ac210)
Location: mm/memcontrol.c:4993
Inline: True
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_css_offline
```
**Symbols:**

```
ffffffff812ac210-ffffffff812ac283: mem_cgroup_id_put_many (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void mem_cgroup_id_put_many(struct mem_cgroup *memcg, unsigned int n);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b8ea0)
Location: mm/memcontrol.c:4993
Inline: True
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_css_offline
```
**Symbols:**

```
ffffffff812b8ea0-ffffffff812b8f13: mem_cgroup_id_put_many (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void mem_cgroup_id_put_many(struct mem_cgroup *memcg, unsigned int n);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c94c0)
Location: mm/memcontrol.c:4993
Inline: True
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_css_offline
```
**Symbols:**

```
ffffffff812c94c0-ffffffff812c9547: mem_cgroup_id_put_many (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
