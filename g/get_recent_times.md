# Function: <code>get_recent_times</code>

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
In kernel/sched/psi.c (ffffffff810ef008)
Location: kernel/sched/psi.c:213
Inline: True
Inline callers:
  - kernel/sched/psi.c:update_stats
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
In kernel/sched/psi.c (ffffffff810f6306)
Location: kernel/sched/psi.c:236
Inline: True
Inline callers:
  - kernel/sched/psi.c:collect_percpu_times
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
In kernel/sched/psi.c (ffffffff811020a6)
Location: kernel/sched/psi.c:237
Inline: True
Inline callers:
  - kernel/sched/psi.c:collect_percpu_times
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
In kernel/sched/psi.c (ffffffff8110cd10)
Location: kernel/sched/psi.c:237
Inline: True
Direct callers:
  - kernel/sched/psi.c:collect_percpu_times
```
**Symbols:**

```
ffffffff8110cd10-ffffffff8110cdf1: get_recent_times.isra.0 (STB_LOCAL)
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
In kernel/sched/psi.c (ffffffff81109ec0)
Location: kernel/sched/psi.c:236
Inline: True
Direct callers:
  - kernel/sched/psi.c:collect_percpu_times
```
**Symbols:**

```
ffffffff81109ec0-ffffffff81109f9f: get_recent_times.isra.0 (STB_LOCAL)
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
In kernel/sched/psi.c (ffffffff8110bc19)
Location: kernel/sched/psi.c:245
Inline: True
Inline callers:
  - kernel/sched/psi.c:collect_percpu_times
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
In kernel/sched/psi.c (ffffffff8112a6cb)
Location: kernel/sched/psi.c:256
Inline: True
Inline callers:
  - kernel/sched/psi.c:collect_percpu_times
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
In kernel/sched/build_utility.c (ffffffff81143780)
Location: kernel/sched/psi.c:242
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:collect_percpu_times
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void get_recent_times(struct psi_group *group, int cpu, enum psi_aggregators aggregator, u32 *times, u32 *pchanged_states);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8116ee30)
Location: kernel/sched/psi.c:241
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:collect_percpu_times
```
**Symbols:**

```
ffffffff8116ee30-ffffffff8116f0e3: get_recent_times (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void get_recent_times(struct psi_group *group, int cpu, enum psi_aggregators aggregator, u32 *times, u32 *pchanged_states);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811805a0)
Location: kernel/sched/psi.c:245
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:collect_percpu_times
```
**Symbols:**

```
ffffffff811805a0-ffffffff8118090e: get_recent_times (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void get_recent_times(struct psi_group *group, int cpu, enum psi_aggregators aggregator, u32 *times, u32 *pchanged_states);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8118e2f0)
Location: kernel/sched/psi.c:245
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:collect_percpu_times
```
**Symbols:**

```
ffffffff8118e2f0-ffffffff8118e65e: get_recent_times (STB_LOCAL)
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
In kernel/sched/psi.c (ffff800010166d38)
Location: kernel/sched/psi.c:237
Inline: True
Inline callers:
  - kernel/sched/psi.c:collect_percpu_times
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
In kernel/sched/psi.c (c03b2b8c)
Location: kernel/sched/psi.c:237
Inline: True
Inline callers:
  - kernel/sched/psi.c:collect_percpu_times
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
In kernel/sched/psi.c (c0000000001bded0)
Location: kernel/sched/psi.c:237
Inline: True
Inline callers:
  - kernel/sched/psi.c:collect_percpu_times
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
In kernel/sched/psi.c (ffffffe000108ac0)
Location: kernel/sched/psi.c:237
Inline: True
Inline callers:
  - kernel/sched/psi.c:collect_percpu_times
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
In kernel/sched/psi.c (ffffffff810fb3b6)
Location: kernel/sched/psi.c:237
Inline: True
Inline callers:
  - kernel/sched/psi.c:collect_percpu_times
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
In kernel/sched/psi.c (ffffffff810eb5d6)
Location: kernel/sched/psi.c:237
Inline: True
Inline callers:
  - kernel/sched/psi.c:collect_percpu_times
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
In kernel/sched/psi.c (ffffffff810f8576)
Location: kernel/sched/psi.c:237
Inline: True
Inline callers:
  - kernel/sched/psi.c:collect_percpu_times
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
In kernel/sched/psi.c (ffffffff811036b6)
Location: kernel/sched/psi.c:237
Inline: True
Inline callers:
  - kernel/sched/psi.c:collect_percpu_times
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
