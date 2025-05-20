# Function: <code>__update_load_avg_blocked_se</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff810b6030)
Location: kernel/sched/fair.c:2994
Inline: True
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:remove_entity_load_avg
```
**Symbols:**

```
ffffffff810b6030-ffffffff810b6119: __update_load_avg_blocked_se.isra.36 (STB_LOCAL)
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
In kernel/sched/fair.c (ffffffff810bd170)
Location: kernel/sched/fair.c:3280
Inline: True
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:remove_entity_load_avg
```
**Symbols:**

```
ffffffff810bd170-ffffffff810bd2b2: __update_load_avg_blocked_se.isra.37 (STB_LOCAL)
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
In kernel/sched/fair.c (ffffffff810c4db0)
Location: kernel/sched/fair.c:3330
Inline: True
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:remove_entity_load_avg
```
**Symbols:**

```
ffffffff810c4db0-ffffffff810c4eff: __update_load_avg_blocked_se.isra.44 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __update_load_avg_blocked_se(u64 now, int cpu, struct sched_entity *se);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/pelt.c (ffffffff810e6f60)
Location: kernel/sched/pelt.c:270
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:remove_entity_load_avg
```
**Symbols:**

```
ffffffff810e6f60-ffffffff810e70fb: __update_load_avg_blocked_se (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __update_load_avg_blocked_se(u64 now, struct sched_entity *se);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/pelt.c (ffffffff810edbf0)
Location: kernel/sched/pelt.c:266
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:remove_entity_load_avg
```
**Symbols:**

```
ffffffff810edbf0-ffffffff810ede15: __update_load_avg_blocked_se (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __update_load_avg_blocked_se(u64 now, struct sched_entity *se);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/pelt.c (ffffffff810f97d0)
Location: kernel/sched/pelt.c:266
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:remove_entity_load_avg
```
**Symbols:**

```
ffffffff810f97d0-ffffffff810f99f5: __update_load_avg_blocked_se (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __update_load_avg_blocked_se(u64 now, struct sched_entity *se);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/pelt.c (ffffffff81103850)
Location: kernel/sched/pelt.c:303
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:remove_entity_load_avg
```
**Symbols:**

```
ffffffff81103850-ffffffff81103a5a: __update_load_avg_blocked_se (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __update_load_avg_blocked_se(u64 now, struct sched_entity *se);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/pelt.c (ffffffff81101f80)
Location: kernel/sched/pelt.c:299
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:remove_entity_load_avg
```
**Symbols:**

```
ffffffff81101f80-ffffffff8110215b: __update_load_avg_blocked_se (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __update_load_avg_blocked_se(u64 now, struct sched_entity *se);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/pelt.c (ffffffff811042f0)
Location: kernel/sched/pelt.c:299
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:remove_entity_load_avg
```
**Symbols:**

```
ffffffff811042f0-ffffffff811044ca: __update_load_avg_blocked_se (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __update_load_avg_blocked_se(u64 now, struct sched_entity *se);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/pelt.c (ffffffff81121410)
Location: kernel/sched/pelt.c:299
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:remove_entity_load_avg
```
**Symbols:**

```
ffffffff81121410-ffffffff811216e8: __update_load_avg_blocked_se (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __update_load_avg_blocked_se(u64 now, struct sched_entity *se);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81136880)
Location: kernel/sched/pelt.c:295
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:remove_entity_load_avg
```
**Symbols:**

```
ffffffff81136880-ffffffff81136b72: __update_load_avg_blocked_se (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __update_load_avg_blocked_se(u64 now, struct sched_entity *se);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81160ef0)
Location: kernel/sched/pelt.c:295
Inline: False
Direct callers:
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:remove_entity_load_avg
```
**Symbols:**

```
ffffffff81160ef0-ffffffff811611e2: __update_load_avg_blocked_se (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __update_load_avg_blocked_se(u64 now, struct sched_entity *se);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81171640)
Location: kernel/sched/pelt.c:295
Inline: False
Direct callers:
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:remove_entity_load_avg
```
**Symbols:**

```
ffffffff81171640-ffffffff81171931: __update_load_avg_blocked_se (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __update_load_avg_blocked_se(u64 now, struct sched_entity *se);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8117ef50)
Location: kernel/sched/pelt.c:295
Inline: False
Direct callers:
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:remove_entity_load_avg
```
**Symbols:**

```
ffffffff8117ef50-ffffffff8117f241: __update_load_avg_blocked_se (STB_GLOBAL)
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
int __update_load_avg_blocked_se(u64 now, struct sched_entity *se);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/pelt.c (ffff80001015e1e0)
Location: kernel/sched/pelt.c:266
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:remove_entity_load_avg
```
**Symbols:**

```
ffff80001015e1e0-ffff80001015e3f4: __update_load_avg_blocked_se (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __update_load_avg_blocked_se(u64 now, struct sched_entity *se);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/pelt.c (c03aa0bc)
Location: kernel/sched/pelt.c:266
Inline: False
Direct callers:
  - kernel/sched/fair.c:sync_entity_load_avg
```
**Symbols:**

```
c03aa0bc-c03aa480: __update_load_avg_blocked_se (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __update_load_avg_blocked_se(u64 now, struct sched_entity *se);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/pelt.c (c0000000001b2e50)
Location: kernel/sched/pelt.c:266
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:remove_entity_load_avg
```
**Symbols:**

```
c0000000001b2e50-c0000000001b3194: __update_load_avg_blocked_se (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __update_load_avg_blocked_se(u64 now, struct sched_entity *se);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/pelt.c (ffffffe0001026a2)
Location: kernel/sched/pelt.c:266
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:remove_entity_load_avg
```
**Symbols:**

```
ffffffe0001026a2-ffffffe0001028a2: __update_load_avg_blocked_se (STB_GLOBAL)
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
int __update_load_avg_blocked_se(u64 now, struct sched_entity *se);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/pelt.c (ffffffff810f2bd0)
Location: kernel/sched/pelt.c:266
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:remove_entity_load_avg
```
**Symbols:**

```
ffffffff810f2bd0-ffffffff810f2df5: __update_load_avg_blocked_se (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __update_load_avg_blocked_se(u64 now, struct sched_entity *se);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/pelt.c (ffffffff810e2ce0)
Location: kernel/sched/pelt.c:266
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:remove_entity_load_avg
```
**Symbols:**

```
ffffffff810e2ce0-ffffffff810e2f05: __update_load_avg_blocked_se (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __update_load_avg_blocked_se(u64 now, struct sched_entity *se);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/pelt.c (ffffffff810efd00)
Location: kernel/sched/pelt.c:266
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:remove_entity_load_avg
```
**Symbols:**

```
ffffffff810efd00-ffffffff810eff25: __update_load_avg_blocked_se (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __update_load_avg_blocked_se(u64 now, struct sched_entity *se);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/pelt.c (ffffffff810fad60)
Location: kernel/sched/pelt.c:266
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:remove_entity_load_avg
```
**Symbols:**

```
ffffffff810fad60-ffffffff810faf91: __update_load_avg_blocked_se (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int cpu</code>
</li>
<li>
<b>Param reordered. </b>
<code>now, cpu, se</code> ➡️ <code>now, se</code>
</li>
</ul>
</details>
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
