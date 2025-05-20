# Function: <code>early_cpu_to_node</code>

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
In arch/x86/kernel/cpu/common.c (ffffffff810410f5)
Location: arch/x86/include/asm/topology.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/smpboot.c (ffffffff81051bbf)
Location: arch/x86/include/asm/topology.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff81f6fc23)
Location: arch/x86/include/asm/topology.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance
  - arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
```
```
In arch/x86/mm/numa.c (ffffffff81f78c9e)
Location: arch/x86/include/asm/topology.h:65
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_add_cpu
  - arch/x86/mm/numa.c:numa_remove_cpu
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
In arch/x86/kernel/cpu/common.c (ffffffff81041016)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/smpboot.c (ffffffff81051d51)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff81f9867a)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance
  - arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
```
```
In arch/x86/mm/numa.c (ffffffff81076245)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_remove_cpu
  - arch/x86/mm/numa.c:numa_add_cpu
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81040a67)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/smpboot.c (ffffffff8105464e)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff81fd3b43)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance
  - arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
```
```
In arch/x86/mm/numa.c (ffffffff81079e35)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_remove_cpu
  - arch/x86/mm/numa.c:numa_add_cpu
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8103e9ea)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/smpboot.c (ffffffff81053fa1)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff820b4834)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance
  - arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
```
```
In arch/x86/mm/numa.c (ffffffff810786e5)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_remove_cpu
  - arch/x86/mm/numa.c:numa_add_cpu
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff810416b4)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/smpboot.c (ffffffff81057d50)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff826baf39)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance
  - arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
```
```
In arch/x86/mm/numa.c (ffffffff8107ea45)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_remove_cpu
  - arch/x86/mm/numa.c:numa_add_cpu
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81042f84)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/smpboot.c (ffffffff8105aa72)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff826e4d04)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance
  - arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
```
```
In arch/x86/mm/numa.c (ffffffff81081b85)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_remove_cpu
  - arch/x86/mm/numa.c:numa_add_cpu
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8104456b)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/smpboot.c (ffffffff810606f2)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff8289b7dc)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance
  - arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
```
```
In arch/x86/mm/numa.c (ffffffff81088795)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_remove_cpu
  - arch/x86/mm/numa.c:numa_add_cpu
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81046b1e)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/smpboot.c (ffffffff81063eac)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff828b35a7)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance
  - arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
```
```
In arch/x86/mm/numa.c (ffffffff8108c3c5)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_remove_cpu
  - arch/x86/mm/numa.c:numa_add_cpu
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8104729e)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/smpboot.c (ffffffff81064551)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff828b69fe)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance
  - arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
```
```
In arch/x86/mm/numa.c (ffffffff8108d025)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_remove_cpu
  - arch/x86/mm/numa.c:numa_add_cpu
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int early_cpu_to_node(int cpu);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8104b097)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/smpboot.c (ffffffff810698c5)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:announce_cpu
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff8106c331)
Location: arch/x86/include/asm/topology.h:56
Inline: False
Direct callers:
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance
  - arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance
  - arch/x86/kernel/setup_percpu.c:pcpu_alloc_bootmem
```
```
In arch/x86/mm/numa.c (ffffffff81094665)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_remove_cpu
  - arch/x86/mm/numa.c:numa_add_cpu
Direct callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
**Symbols:**

```
ffffffff8106c331-ffffffff8106c358: early_cpu_to_node (STB_LOCAL)
ffffffff810943b0-ffffffff810943db: early_cpu_to_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int early_cpu_to_node(int cpu);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8104a767)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106b595)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:announce_cpu
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff81bd6c78)
Location: arch/x86/include/asm/topology.h:56
Inline: False
Direct callers:
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance
  - arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance
  - arch/x86/kernel/setup_percpu.c:pcpu_alloc_bootmem
```
```
In arch/x86/mm/numa.c (ffffffff81093a65)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_remove_cpu
  - arch/x86/mm/numa.c:numa_add_cpu
Direct callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
**Symbols:**

```
ffffffff81bd6c78-ffffffff81bd6c9f: early_cpu_to_node (STB_LOCAL)
ffffffff810937b0-ffffffff810937db: early_cpu_to_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int early_cpu_to_node(int cpu);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8104c024)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106bf75)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:announce_cpu
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff81bc8e53)
Location: arch/x86/include/asm/topology.h:56
Inline: False
Direct callers:
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance
  - arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance
  - arch/x86/kernel/setup_percpu.c:pcpu_alloc_bootmem
```
```
In arch/x86/mm/numa.c (ffffffff81094425)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_remove_cpu
  - arch/x86/mm/numa.c:numa_add_cpu
Direct callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
**Symbols:**

```
ffffffff81bc8e53-ffffffff81bc8e7a: early_cpu_to_node (STB_LOCAL)
ffffffff81094170-ffffffff8109419b: early_cpu_to_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int early_cpu_to_node(int cpu);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8105358d)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
```
```
In arch/x86/kernel/smpboot.c (ffffffff81076b55)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:announce_cpu
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff81c9d884)
Location: arch/x86/include/asm/topology.h:56
Inline: False
Direct callers:
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance
  - arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance
  - arch/x86/kernel/setup_percpu.c:pcpu_alloc_bootmem
```
```
In arch/x86/mm/numa.c (ffffffff810a4345)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_remove_cpu
  - arch/x86/mm/numa.c:numa_add_cpu
Direct callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
**Symbols:**

```
ffffffff81c9d884-ffffffff81c9d8ce: early_cpu_to_node (STB_LOCAL)
ffffffff810a3f70-ffffffff810a3fcb: early_cpu_to_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int early_cpu_to_node(int cpu);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8105f026)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
```
```
In arch/x86/kernel/smpboot.c (ffffffff810859f5)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:announce_cpu
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff81e4ccdc)
Location: arch/x86/include/asm/topology.h:56
Inline: False
Direct callers:
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/setup_percpu.c:pcpu_cpu_to_node
  - arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance
  - arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance
```
```
In arch/x86/mm/numa.c (ffffffff810b8b15)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_remove_cpu
  - arch/x86/mm/numa.c:numa_add_cpu
Direct callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
**Symbols:**

```
ffffffff81e4ccdc-ffffffff81e4cd2e: early_cpu_to_node (STB_LOCAL)
ffffffff810b8680-ffffffff810b86eb: early_cpu_to_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8106d786)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
```
```
In arch/x86/kernel/smpboot.c (ffffffff81098bd5)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:announce_cpu
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff83e8a4c5)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/setup_percpu.c:pcpu_cpu_to_node
  - arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance
  - arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff83e9c755)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
```
```
In arch/x86/mm/numa.c (ffffffff810d43c5)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_remove_cpu
  - arch/x86/mm/numa.c:numa_add_cpu
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8106f0d9)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
```
```
In arch/x86/kernel/smpboot.c (ffffffff8109bea5)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:announce_cpu
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff836adbb2)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/setup_percpu.c:pcpu_cpu_to_node
  - arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance
  - arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff836c0275)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
```
```
In arch/x86/mm/numa.c (ffffffff810d7905)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_remove_cpu
  - arch/x86/mm/numa.c:numa_add_cpu
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8107648e)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
```
```
In arch/x86/kernel/smpboot.c (ffffffff810a34a5)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:announce_cpu
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff838de168)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/setup_percpu.c:pcpu_cpu_to_node
  - arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance
  - arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff838f0d95)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
```
```
In arch/x86/mm/numa.c (ffffffff810e0185)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_remove_cpu
  - arch/x86/mm/numa.c:numa_add_cpu
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
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
In arch/arm64/mm/numa.c (ffff8000114389a0)
Location: arch/arm64/mm/numa.c:144
Inline: True
Inline callers:
  - arch/arm64/mm/numa.c:pcpu_fc_alloc
  - arch/arm64/mm/numa.c:pcpu_cpu_distance
  - arch/arm64/mm/numa.c:pcpu_cpu_distance
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/setup_64.c (c000000000030f90)
Location: arch/powerpc/include/asm/topology.h:53
Inline: True
Inline callers:
  - arch/powerpc/kernel/setup_64.c:pcpu_cpu_distance
  - arch/powerpc/kernel/setup_64.c:pcpu_cpu_distance
  - arch/powerpc/kernel/setup_64.c:pcpu_fc_alloc
  - arch/powerpc/kernel/setup_64.c:alloc_stack
```
```
In arch/powerpc/kernel/paca.c (c00000000134b94c)
Location: arch/powerpc/include/asm/topology.h:53
Inline: True
Inline callers:
  - arch/powerpc/kernel/paca.c:alloc_paca_data
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8104741e)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/smpboot.c (ffffffff81064041)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff828a4a05)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance
  - arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
```
```
In arch/x86/mm/numa.c (ffffffff8108bfe5)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_remove_cpu
  - arch/x86/mm/numa.c:numa_add_cpu
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff810365a3)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/smpboot.c (ffffffff81054341)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff8289cb47)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance
  - arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
```
```
In arch/x86/mm/numa.c (ffffffff8107ab15)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_remove_cpu
  - arch/x86/mm/numa.c:numa_add_cpu
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8104725e)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/smpboot.c (ffffffff810644f1)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff828b7915)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance
  - arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
```
```
In arch/x86/mm/numa.c (ffffffff8108bf95)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_remove_cpu
  - arch/x86/mm/numa.c:numa_add_cpu
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8104865e)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/smpboot.c (ffffffff81065ab1)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff828b7a16)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance
  - arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
```
```
In arch/x86/mm/numa.c (ffffffff8108e2f5)
Location: arch/x86/include/asm/topology.h:56
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_remove_cpu
  - arch/x86/mm/numa.c:numa_add_cpu
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
