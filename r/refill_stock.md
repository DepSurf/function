# Function: <code>refill_stock</code>

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
In mm/memcontrol.c (ffffffff811fbfdf)
Location: mm/memcontrol.c:1935
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
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
In mm/memcontrol.c (ffffffff8121ffb0)
Location: mm/memcontrol.c:1797
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
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
In mm/memcontrol.c (ffffffff8123264c)
Location: mm/memcontrol.c:1768
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
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
In mm/memcontrol.c (ffffffff8123d721)
Location: mm/memcontrol.c:1779
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void refill_stock(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8125ccc0)
Location: mm/memcontrol.c:1797
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:try_charge
```
**Symbols:**

```
ffffffff8125ccc0-ffffffff8125cd37: refill_stock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void refill_stock(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81280d30)
Location: mm/memcontrol.c:1749
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:try_charge
```
**Symbols:**

```
ffffffff81280d30-ffffffff81280da9: refill_stock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void refill_stock(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812959b0)
Location: mm/memcontrol.c:2027
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:try_charge
```
**Symbols:**

```
ffffffff812959b0-ffffffff81295a29: refill_stock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void refill_stock(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b19e0)
Location: mm/memcontrol.c:2228
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:try_charge
```
**Symbols:**

```
ffffffff812b19e0-ffffffff812b1a5d: refill_stock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void refill_stock(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c33d0)
Location: mm/memcontrol.c:2244
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:try_charge
```
**Symbols:**

```
ffffffff812c33d0-ffffffff812c344d: refill_stock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void refill_stock(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812f9070)
Location: mm/memcontrol.c:2121
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:try_charge
```
**Symbols:**

```
ffffffff812f9070-ffffffff812f90e3: refill_stock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void refill_stock(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81304220)
Location: mm/memcontrol.c:2343
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:__memcg_kmem_uncharge_page
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:obj_cgroup_release
```
**Symbols:**

```
ffffffff81304220-ffffffff813042b8: refill_stock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void refill_stock(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8130b2f0)
Location: mm/memcontrol.c:2152
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:obj_cgroup_uncharge_pages
  - mm/memcontrol.c:try_charge
```
**Symbols:**

```
ffffffff8130b2f0-ffffffff8130b397: refill_stock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void refill_stock(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81355dd0)
Location: mm/memcontrol.c:2251
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:obj_cgroup_uncharge_pages
  - mm/memcontrol.c:try_charge_memcg
```
**Symbols:**

```
ffffffff81355dd0-ffffffff81355e77: refill_stock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void refill_stock(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813cd990)
Location: mm/memcontrol.c:2253
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:obj_cgroup_uncharge_pages
  - mm/memcontrol.c:try_charge_memcg
```
**Symbols:**

```
ffffffff813cd990-ffffffff813cd9c9: refill_stock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void refill_stock(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81452550)
Location: mm/memcontrol.c:2313
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:obj_cgroup_uncharge_pages
  - mm/memcontrol.c:try_charge_memcg
```
**Symbols:**

```
ffffffff81452550-ffffffff8145259f: refill_stock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void refill_stock(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81488060)
Location: mm/memcontrol.c:2323
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:obj_cgroup_uncharge_pages
  - mm/memcontrol.c:try_charge_memcg
```
**Symbols:**

```
ffffffff81488060-ffffffff814880af: refill_stock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void refill_stock(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814b7cd0)
Location: mm/memcontrol.c:2395
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:obj_cgroup_uncharge_pages
  - mm/memcontrol.c:try_charge_memcg
```
**Symbols:**

```
ffffffff814b7cd0-ffffffff814b7d1f: refill_stock (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void refill_stock(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff800010365ba8)
Location: mm/memcontrol.c:2244
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:try_charge
```
**Symbols:**

```
ffff800010365ba8-ffff800010365c50: refill_stock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void refill_stock(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c0557940)
Location: mm/memcontrol.c:2244
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:try_charge
```
**Symbols:**

```
c0557940-c05579b8: refill_stock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void refill_stock(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c000000000452c60)
Location: mm/memcontrol.c:2244
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:try_charge
```
**Symbols:**

```
c000000000452c60-c000000000452d5c: refill_stock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void refill_stock(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffe000244526)
Location: mm/memcontrol.c:2244
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:try_charge
```
**Symbols:**

```
ffffffe000244526-ffffffe0002445b6: refill_stock (STB_LOCAL)
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
void refill_stock(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bb9b0)
Location: mm/memcontrol.c:2244
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:try_charge
```
**Symbols:**

```
ffffffff812bb9b0-ffffffff812bba2d: refill_stock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void refill_stock(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812acb20)
Location: mm/memcontrol.c:2244
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:try_charge
```
**Symbols:**

```
ffffffff812acb20-ffffffff812acb89: refill_stock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void refill_stock(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b97c0)
Location: mm/memcontrol.c:2244
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:try_charge
```
**Symbols:**

```
ffffffff812b97c0-ffffffff812b983d: refill_stock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void refill_stock(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c9e30)
Location: mm/memcontrol.c:2244
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:try_charge
```
**Symbols:**

```
ffffffff812c9e30-ffffffff812c9ead: refill_stock (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
