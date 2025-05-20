# Function: <code>sync_entity_load_avg</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void sync_entity_load_avg(struct sched_entity *se);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c4820)
Location: kernel/sched/fair.c:3385
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:remove_entity_load_avg
```
**Symbols:**

```
ffffffff810c4820-ffffffff810c4988: sync_entity_load_avg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void sync_entity_load_avg(struct sched_entity *se);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810b7c26)
Location: kernel/sched/fair.c:3490
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:remove_entity_load_avg
```
**Symbols:**

```
ffffffff810bef10-ffffffff810bef2e: sync_entity_load_avg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void sync_entity_load_avg(struct sched_entity *se);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bf0bf)
Location: kernel/sched/fair.c:3826
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:remove_entity_load_avg
```
**Symbols:**

```
ffffffff810c66f0-ffffffff810c670e: sync_entity_load_avg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void sync_entity_load_avg(struct sched_entity *se);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c7842)
Location: kernel/sched/fair.c:3884
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:remove_entity_load_avg
```
**Symbols:**

```
ffffffff810ce5c0-ffffffff810ce5e1: sync_entity_load_avg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void sync_entity_load_avg(struct sched_entity *se);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810cff7e)
Location: kernel/sched/fair.c:3558
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:remove_entity_load_avg
```
**Symbols:**

```
ffffffff810d7ac0-ffffffff810d7aee: sync_entity_load_avg (STB_GLOBAL)
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
In kernel/sched/fair.c (ffffffff810d7efc)
Location: kernel/sched/fair.c:3648
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:remove_entity_load_avg
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
In kernel/sched/fair.c (ffffffff810e2678)
Location: kernel/sched/fair.c:3649
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:remove_entity_load_avg
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
In kernel/sched/fair.c (ffffffff810eaa07)
Location: kernel/sched/fair.c:3836
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:remove_entity_load_avg
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
In kernel/sched/fair.c (ffffffff810e85b7)
Location: kernel/sched/fair.c:3853
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:remove_entity_load_avg
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
In kernel/sched/fair.c (ffffffff810e9b67)
Location: kernel/sched/fair.c:3901
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:remove_entity_load_avg
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
In kernel/sched/fair.c (ffffffff81104f2a)
Location: kernel/sched/fair.c:3913
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:remove_entity_load_avg
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
In kernel/sched/fair.c (ffffffff81122412)
Location: kernel/sched/fair.c:3962
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:remove_entity_load_avg
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
In kernel/sched/fair.c (ffffffff8114e1d2)
Location: kernel/sched/fair.c:4231
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:remove_entity_load_avg
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
In kernel/sched/fair.c (ffffffff8115c13f)
Location: kernel/sched/fair.c:4288
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:remove_entity_load_avg
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81167a52)
Location: kernel/sched/fair.c:4775
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:remove_entity_load_avg
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
In kernel/sched/fair.c (ffff80001014361c)
Location: kernel/sched/fair.c:3649
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:remove_entity_load_avg
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sync_entity_load_avg(struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c03906a8)
Location: kernel/sched/fair.c:3649
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:remove_entity_load_avg
```
**Symbols:**

```
c03906a8-c03906e8: sync_entity_load_avg (STB_LOCAL)
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
In kernel/sched/fair.c (c000000000191a50)
Location: kernel/sched/fair.c:3649
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:remove_entity_load_avg
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
In kernel/sched/fair.c (ffffffe0000ef6a6)
Location: kernel/sched/fair.c:3649
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:remove_entity_load_avg
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
In kernel/sched/fair.c (ffffffff810dc828)
Location: kernel/sched/fair.c:3649
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:remove_entity_load_avg
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
In kernel/sched/fair.c (ffffffff810cb838)
Location: kernel/sched/fair.c:3649
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:remove_entity_load_avg
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
In kernel/sched/fair.c (ffffffff810d8ba8)
Location: kernel/sched/fair.c:3649
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:remove_entity_load_avg
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
In kernel/sched/fair.c (ffffffff810e46b5)
Location: kernel/sched/fair.c:3649
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:remove_entity_load_avg
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
</ul>
