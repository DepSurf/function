# Function: <code>mem_cgroup_out_of_memory</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void mem_cgroup_out_of_memory(struct mem_cgroup *memcg, gfp_t gfp_mask, int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff811fe870)
Location: mm/memcontrol.c:1335
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff811fe870-ffffffff811feb58: mem_cgroup_out_of_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool mem_cgroup_out_of_memory(struct mem_cgroup *memcg, gfp_t gfp_mask, int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812226d0)
Location: mm/memcontrol.c:1198
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff812226d0-ffffffff812229e0: mem_cgroup_out_of_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool mem_cgroup_out_of_memory(struct mem_cgroup *memcg, gfp_t gfp_mask, int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8122fe60)
Location: mm/memcontrol.c:1236
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff8122fe60-ffffffff8122fed6: mem_cgroup_out_of_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool mem_cgroup_out_of_memory(struct mem_cgroup *memcg, gfp_t gfp_mask, int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8123b770)
Location: mm/memcontrol.c:1228
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff8123b770-ffffffff8123b7e6: mem_cgroup_out_of_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool mem_cgroup_out_of_memory(struct mem_cgroup *memcg, gfp_t gfp_mask, int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8125aff0)
Location: mm/memcontrol.c:1242
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff8125aff0-ffffffff8125b066: mem_cgroup_out_of_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool mem_cgroup_out_of_memory(struct mem_cgroup *memcg, gfp_t gfp_mask, int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8127ebc0)
Location: mm/memcontrol.c:1199
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff8127ebc0-ffffffff8127ec36: mem_cgroup_out_of_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool mem_cgroup_out_of_memory(struct mem_cgroup *memcg, gfp_t gfp_mask, int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812933f0)
Location: mm/memcontrol.c:1380
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff812933f0-ffffffff81293466: mem_cgroup_out_of_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool mem_cgroup_out_of_memory(struct mem_cgroup *memcg, gfp_t gfp_mask, int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812affb0)
Location: mm/memcontrol.c:1572
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff812affb0-ffffffff812b0082: mem_cgroup_out_of_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool mem_cgroup_out_of_memory(struct mem_cgroup *memcg, gfp_t gfp_mask, int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c1a20)
Location: mm/memcontrol.c:1588
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff812c1a20-ffffffff812c1af2: mem_cgroup_out_of_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool mem_cgroup_out_of_memory(struct mem_cgroup *memcg, gfp_t gfp_mask, int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812f6430)
Location: mm/memcontrol.c:1553
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff812f6430-ffffffff812f6502: mem_cgroup_out_of_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool mem_cgroup_out_of_memory(struct mem_cgroup *memcg, gfp_t gfp_mask, int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81303c40)
Location: mm/memcontrol.c:1736
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff81303c40-ffffffff81303d8e: mem_cgroup_out_of_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool mem_cgroup_out_of_memory(struct mem_cgroup *memcg, gfp_t gfp_mask, int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81309dc0)
Location: mm/memcontrol.c:1559
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff81309dc0-ffffffff81309f13: mem_cgroup_out_of_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool mem_cgroup_out_of_memory(struct mem_cgroup *memcg, gfp_t gfp_mask, int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:1611
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff81352250-ffffffff813523a3: mem_cgroup_out_of_memory (STB_LOCAL)
ffffffff81cc2796-ffffffff81cc27af: mem_cgroup_out_of_memory.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool mem_cgroup_out_of_memory(struct mem_cgroup *memcg, gfp_t gfp_mask, int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:1628
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff813cb3f0-ffffffff813cb54d: mem_cgroup_out_of_memory (STB_LOCAL)
ffffffff81e74d70-ffffffff81e74d89: mem_cgroup_out_of_memory.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool mem_cgroup_out_of_memory(struct mem_cgroup *memcg, gfp_t gfp_mask, int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:1688
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff81452030-ffffffff8145219b: mem_cgroup_out_of_memory (STB_LOCAL)
ffffffff82068122-ffffffff8206813b: mem_cgroup_out_of_memory.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool mem_cgroup_out_of_memory(struct mem_cgroup *memcg, gfp_t gfp_mask, int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:1722
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
```
**Symbols:**

```
ffffffff81487980-ffffffff81487aeb: mem_cgroup_out_of_memory (STB_LOCAL)
ffffffff820e7a0c-ffffffff820e7a25: mem_cgroup_out_of_memory.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool mem_cgroup_out_of_memory(struct mem_cgroup *memcg, gfp_t gfp_mask, int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:1794
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
```
**Symbols:**

```
ffffffff814b76c0-ffffffff814b782b: mem_cgroup_out_of_memory (STB_LOCAL)
ffffffff821c4720-ffffffff821c4739: mem_cgroup_out_of_memory.cold (STB_LOCAL)
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
bool mem_cgroup_out_of_memory(struct mem_cgroup *memcg, gfp_t gfp_mask, int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff8000103635a8)
Location: mm/memcontrol.c:1588
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffff8000103635a8-ffff80001036368c: mem_cgroup_out_of_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool mem_cgroup_out_of_memory(struct mem_cgroup *memcg, gfp_t gfp_mask, int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c0555f60)
Location: mm/memcontrol.c:1588
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
c0555f60-c0556064: mem_cgroup_out_of_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool mem_cgroup_out_of_memory(struct mem_cgroup *memcg, gfp_t gfp_mask, int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c000000000450420)
Location: mm/memcontrol.c:1588
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
c000000000450420-c000000000450568: mem_cgroup_out_of_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool mem_cgroup_out_of_memory(struct mem_cgroup *memcg, gfp_t gfp_mask, int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffe000242c8c)
Location: mm/memcontrol.c:1588
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffe000242c8c-ffffffe000242d50: mem_cgroup_out_of_memory (STB_LOCAL)
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
bool mem_cgroup_out_of_memory(struct mem_cgroup *memcg, gfp_t gfp_mask, int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812ba000)
Location: mm/memcontrol.c:1588
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff812ba000-ffffffff812ba0d2: mem_cgroup_out_of_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool mem_cgroup_out_of_memory(struct mem_cgroup *memcg, gfp_t gfp_mask, int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812ab290)
Location: mm/memcontrol.c:1588
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff812ab290-ffffffff812ab362: mem_cgroup_out_of_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool mem_cgroup_out_of_memory(struct mem_cgroup *memcg, gfp_t gfp_mask, int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b7e10)
Location: mm/memcontrol.c:1588
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff812b7e10-ffffffff812b7ee2: mem_cgroup_out_of_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool mem_cgroup_out_of_memory(struct mem_cgroup *memcg, gfp_t gfp_mask, int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c8700)
Location: mm/memcontrol.c:1588
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff812c8700-ffffffff812c87d2: mem_cgroup_out_of_memory (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
</li>
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
