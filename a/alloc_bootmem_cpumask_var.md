# Function: <code>alloc_bootmem_cpumask_var</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: include/linux/cpumask.h:693
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: include/linux/cpumask.h:693
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/cpumask.h:693
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: include/linux/cpumask.h:695
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: include/linux/cpumask.h:695
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/cpumask.h:695
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void alloc_bootmem_cpumask_var(cpumask_var_t *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff82003f8f)
Location: lib/cpumask.c:114
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/mm/numa.c:setup_node_to_cpumask_map
```
**Symbols:**

```
ffffffff82003f8f-ffffffff82003fbf: alloc_bootmem_cpumask_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void alloc_bootmem_cpumask_var(cpumask_var_t *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff8210f132)
Location: lib/cpumask.c:146
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/mm/numa.c:setup_node_to_cpumask_map
```
**Symbols:**

```
ffffffff8210f132-ffffffff8210f161: alloc_bootmem_cpumask_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void alloc_bootmem_cpumask_var(cpumask_var_t *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff82719523)
Location: lib/cpumask.c:163
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/mm/numa.c:setup_node_to_cpumask_map
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
**Symbols:**

```
ffffffff82719523-ffffffff82719552: alloc_bootmem_cpumask_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void alloc_bootmem_cpumask_var(cpumask_var_t *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff82743ce1)
Location: lib/cpumask.c:164
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/mm/numa.c:setup_node_to_cpumask_map
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
**Symbols:**

```
ffffffff82743ce1-ffffffff82743d10: alloc_bootmem_cpumask_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void alloc_bootmem_cpumask_var(cpumask_var_t *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff828fdfff)
Location: lib/cpumask.c:164
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/mm/numa.c:setup_node_to_cpumask_map
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
**Symbols:**

```
ffffffff828fdfff-ffffffff828fe031: alloc_bootmem_cpumask_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void alloc_bootmem_cpumask_var(cpumask_var_t *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff8291ac36)
Location: lib/cpumask.c:165
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/mm/numa.c:setup_node_to_cpumask_map
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
**Symbols:**

```
ffffffff8291ac36-ffffffff8291ac91: alloc_bootmem_cpumask_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void alloc_bootmem_cpumask_var(cpumask_var_t *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff82924aa5)
Location: lib/cpumask.c:165
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/mm/numa.c:setup_node_to_cpumask_map
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
**Symbols:**

```
ffffffff82924aa5-ffffffff82924b00: alloc_bootmem_cpumask_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void alloc_bootmem_cpumask_var(cpumask_var_t *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff82d0a8b5)
Location: lib/cpumask.c:165
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/mm/numa.c:setup_node_to_cpumask_map
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
**Symbols:**

```
ffffffff82d0a8b5-ffffffff82d0a910: alloc_bootmem_cpumask_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void alloc_bootmem_cpumask_var(cpumask_var_t *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff82ff7ea9)
Location: lib/cpumask.c:165
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/mm/numa.c:setup_node_to_cpumask_map
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
**Symbols:**

```
ffffffff82ff7ea9-ffffffff82ff7f04: alloc_bootmem_cpumask_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void alloc_bootmem_cpumask_var(cpumask_var_t *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff83202b20)
Location: lib/cpumask.c:165
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/mm/numa.c:setup_node_to_cpumask_map
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
**Symbols:**

```
ffffffff83202b20-ffffffff83202b7b: alloc_bootmem_cpumask_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void alloc_bootmem_cpumask_var(cpumask_var_t *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff832ea31c)
Location: lib/cpumask.c:165
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/mm/numa.c:setup_node_to_cpumask_map
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
**Symbols:**

```
ffffffff832ea31c-ffffffff832ea377: alloc_bootmem_cpumask_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void alloc_bootmem_cpumask_var(cpumask_var_t *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff834a1c76)
Location: lib/cpumask.c:165
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/mm/numa.c:setup_node_to_cpumask_map
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:housekeeping_setup_type
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
**Symbols:**

```
ffffffff834a1c76-ffffffff834a1ce6: alloc_bootmem_cpumask_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void alloc_bootmem_cpumask_var(cpumask_var_t *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff83f17bf0)
Location: lib/cpumask.c:82
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/mm/numa.c:setup_node_to_cpumask_map
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
**Symbols:**

```
ffffffff83f17bf0-ffffffff83f17c65: alloc_bootmem_cpumask_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void alloc_bootmem_cpumask_var(cpumask_var_t *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff8373e3b0)
Location: lib/cpumask.c:83
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:setup_cpu_local_masks
  - arch/x86/mm/numa.c:setup_node_to_cpumask_map
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
**Symbols:**

```
ffffffff8373e3b0-ffffffff8373e425: alloc_bootmem_cpumask_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void alloc_bootmem_cpumask_var(cpumask_var_t *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff83972dd0)
Location: lib/cpumask.c:84
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:setup_cpu_local_masks
  - arch/x86/mm/numa.c:setup_node_to_cpumask_map
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/irq/irqdesc.c:irq_affinity_setup
  - kernel/rcu/tree.c:rcu_nocb_setup
  - kernel/time/tick-sched.c:tick_nohz_full_setup
```
**Symbols:**

```
ffffffff83972dd0-ffffffff83972e45: alloc_bootmem_cpumask_var (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/numa.c (0)
Location: include/linux/cpumask.h:780
Inline: True
```
```
In kernel/sched/isolation.c (0)
Location: include/linux/cpumask.h:780
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/cpumask.h:780
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (0)
Location: include/linux/cpumask.h:780
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/cpumask.h:780
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/numa.c (0)
Location: include/linux/cpumask.h:780
Inline: True
```
```
In arch/powerpc/platforms/pseries/smp.c (0)
Location: include/linux/cpumask.h:780
Inline: True
```
```
In kernel/sched/isolation.c (0)
Location: include/linux/cpumask.h:780
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/cpumask.h:780
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (0)
Location: include/linux/cpumask.h:780
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/cpumask.h:780
Inline: True
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
void alloc_bootmem_cpumask_var(cpumask_var_t *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff829097a9)
Location: lib/cpumask.c:165
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/mm/numa.c:setup_node_to_cpumask_map
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
**Symbols:**

```
ffffffff829097a9-ffffffff82909804: alloc_bootmem_cpumask_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void alloc_bootmem_cpumask_var(cpumask_var_t *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff82901af7)
Location: lib/cpumask.c:165
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/mm/numa.c:setup_node_to_cpumask_map
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/irq/irqdesc.c:irq_affinity_setup
  - kernel/rcu/tree.c:rcu_nocb_setup
  - kernel/time/tick-sched.c:tick_nohz_full_setup
```
**Symbols:**

```
ffffffff82901af7-ffffffff82901b52: alloc_bootmem_cpumask_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void alloc_bootmem_cpumask_var(cpumask_var_t *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff8291f0f3)
Location: lib/cpumask.c:165
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/mm/numa.c:setup_node_to_cpumask_map
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
**Symbols:**

```
ffffffff8291f0f3-ffffffff8291f14e: alloc_bootmem_cpumask_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void alloc_bootmem_cpumask_var(cpumask_var_t *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff82925b17)
Location: lib/cpumask.c:165
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/kernel/cpu/common.c:setup_cpu_local_masks
  - arch/x86/mm/numa.c:setup_node_to_cpumask_map
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
**Symbols:**

```
ffffffff82925b17-ffffffff82925b72: alloc_bootmem_cpumask_var (STB_GLOBAL)
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
