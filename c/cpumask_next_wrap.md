# Function: <code>cpumask_next_wrap</code>

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
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bd5e9)
Location: kernel/sched/fair.c:5593
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cpumask_next_wrap(int n, const struct cpumask *mask, int start, bool wrap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff818ebc00)
Location: lib/cpumask.c:58
Inline: False
Direct callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffffffff818ebc00-ffffffff818ebc76: cpumask_next_wrap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cpumask_next_wrap(int n, const struct cpumask *mask, int start, bool wrap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81971be0)
Location: lib/cpumask.c:75
Inline: False
Direct callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffffffff81971be0-ffffffff81971c56: cpumask_next_wrap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cpumask_next_wrap(int n, const struct cpumask *mask, int start, bool wrap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff819cdf70)
Location: lib/cpumask.c:76
Inline: False
Direct callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffffffff819cdf70-ffffffff819cdfe6: cpumask_next_wrap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cpumask_next_wrap(int n, const struct cpumask *mask, int start, bool wrap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81a07430)
Location: lib/cpumask.c:76
Inline: False
Direct callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffffffff81a07430-ffffffff81a074a6: cpumask_next_wrap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cpumask_next_wrap(int n, const struct cpumask *mask, int start, bool wrap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81a76d90)
Location: lib/cpumask.c:77
Inline: False
Direct callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
```
**Symbols:**

```
ffffffff81a76d90-ffffffff81a76e01: cpumask_next_wrap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cpumask_next_wrap(int n, const struct cpumask *mask, int start, bool wrap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81aae1a0)
Location: lib/cpumask.c:77
Inline: False
Direct callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/padata.c:padata_find_next
```
**Symbols:**

```
ffffffff81aae1a0-ffffffff81aae211: cpumask_next_wrap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cpumask_next_wrap(int n, const struct cpumask *mask, int start, bool wrap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff815e7e60)
Location: lib/cpumask.c:77
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/fair.c:task_numa_assign
  - kernel/sched/fair.c:task_numa_assign
  - kernel/sched/topology.c:build_sched_groups
  - kernel/sched/topology.c:build_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/padata.c:padata_find_next
```
**Symbols:**

```
ffffffff815e7e60-ffffffff815e7ed1: cpumask_next_wrap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cpumask_next_wrap(int n, const struct cpumask *mask, int start, bool wrap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff8160cfc0)
Location: lib/cpumask.c:77
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/fair.c:task_numa_assign
  - kernel/sched/fair.c:task_numa_assign
  - kernel/sched/topology.c:build_sched_groups
  - kernel/sched/topology.c:build_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/padata.c:padata_find_next
```
**Symbols:**

```
ffffffff8160cfc0-ffffffff8160d031: cpumask_next_wrap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cpumask_next_wrap(int n, const struct cpumask *mask, int start, bool wrap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff815f0750)
Location: lib/cpumask.c:77
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:task_numa_assign
  - kernel/sched/fair.c:task_numa_assign
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/padata.c:padata_find_next
```
**Symbols:**

```
ffffffff815f0750-ffffffff815f07c9: cpumask_next_wrap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cpumask_next_wrap(int n, const struct cpumask *mask, int start, bool wrap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff8165d830)
Location: lib/cpumask.c:77
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:task_numa_assign
  - kernel/sched/fair.c:task_numa_assign
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/padata.c:padata_find_next
```
**Symbols:**

```
ffffffff8165d830-ffffffff8165d8a9: cpumask_next_wrap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cpumask_next_wrap(int n, const struct cpumask *mask, int start, bool wrap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81776e40)
Location: lib/cpumask.c:77
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:task_numa_assign
  - kernel/sched/fair.c:task_numa_assign
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/padata.c:padata_find_next
```
**Symbols:**

```
ffffffff81776e40-ffffffff81776ed9: cpumask_next_wrap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int cpumask_next_wrap(int n, const struct cpumask *mask, int start, bool wrap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff8201f900)
Location: lib/cpumask.c:22
Inline: False
Direct callers:
  - kernel/padata.c:padata_find_next
```
**Symbols:**

```
ffffffff8201f900-ffffffff8201f984: cpumask_next_wrap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int cpumask_next_wrap(int n, const struct cpumask *mask, int start, bool wrap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff8209f960)
Location: lib/cpumask.c:22
Inline: False
Direct callers:
  - kernel/padata.c:padata_find_next
  - drivers/net/virtio_net.c:virtnet_set_affinity
```
**Symbols:**

```
ffffffff8209f960-ffffffff8209f9e4: cpumask_next_wrap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int cpumask_next_wrap(int n, const struct cpumask *mask, int start, bool wrap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff82177930)
Location: lib/cpumask.c:22
Inline: False
Direct callers:
  - kernel/padata.c:padata_find_next
  - drivers/net/virtio_net.c:virtnet_set_affinity
  - lib/objpool.c:objpool_pop
```
**Symbols:**

```
ffffffff82177930-ffffffff821779b4: cpumask_next_wrap (STB_GLOBAL)
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
int cpumask_next_wrap(int n, const struct cpumask *mask, int start, bool wrap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffff800010d84508)
Location: lib/cpumask.c:77
Inline: False
Direct callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/padata.c:padata_find_next
```
**Symbols:**

```
ffff800010d84508-ffff800010d8458c: cpumask_next_wrap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cpumask_next_wrap(int n, const struct cpumask *mask, int start, bool wrap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (c0e7fa28)
Location: lib/cpumask.c:77
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/padata.c:padata_find_next
```
**Symbols:**

```
c0e7fa28-c0e7fa88: cpumask_next_wrap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cpumask_next_wrap(int n, const struct cpumask *mask, int start, bool wrap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (c000000000ec3710)
Location: lib/cpumask.c:77
Inline: False
Direct callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/padata.c:padata_find_next
```
**Symbols:**

```
c000000000ec3710-c000000000ec37e4: cpumask_next_wrap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cpumask_next_wrap(int n, const struct cpumask *mask, int start, bool wrap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffe0008aea38)
Location: lib/cpumask.c:77
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/padata.c:padata_find_next
```
**Symbols:**

```
ffffffe0008aea38-ffffffe0008aea90: cpumask_next_wrap (STB_GLOBAL)
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
int cpumask_next_wrap(int n, const struct cpumask *mask, int start, bool wrap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81a4cff0)
Location: lib/cpumask.c:77
Inline: False
Direct callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/padata.c:padata_find_next
```
**Symbols:**

```
ffffffff81a4cff0-ffffffff81a4d061: cpumask_next_wrap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cpumask_next_wrap(int n, const struct cpumask *mask, int start, bool wrap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81a0a120)
Location: lib/cpumask.c:77
Inline: False
Direct callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/padata.c:padata_find_next
  - drivers/scsi/storvsc_drv.c:storvsc_queuecommand
  - drivers/scsi/storvsc_drv.c:storvsc_queuecommand
```
**Symbols:**

```
ffffffff81a0a120-ffffffff81a0a191: cpumask_next_wrap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cpumask_next_wrap(int n, const struct cpumask *mask, int start, bool wrap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81ab93e0)
Location: lib/cpumask.c:77
Inline: False
Direct callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/padata.c:padata_find_next
```
**Symbols:**

```
ffffffff81ab93e0-ffffffff81ab9451: cpumask_next_wrap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cpumask_next_wrap(int n, const struct cpumask *mask, int start, bool wrap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81ac5830)
Location: lib/cpumask.c:77
Inline: False
Direct callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/padata.c:padata_find_next
```
**Symbols:**

```
ffffffff81ac5830-ffffffff81ac58a1: cpumask_next_wrap (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>unsigned int</code>
</li>
</ul>
</details>
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
