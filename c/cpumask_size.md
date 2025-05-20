# Function: <code>cpumask_size</code>

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
In kernel/sched/core.c (0)
Location: include/linux/cpumask.h:609
Inline: True
```
```
In kernel/compat.c (0)
Location: include/linux/cpumask.h:609
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
In kernel/sched/core.c (0)
Location: include/linux/cpumask.h:611
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/cpumask.h:611
Inline: True
```
```
In kernel/compat.c (0)
Location: include/linux/cpumask.h:611
Inline: True
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
In kernel/sched/core.c (ffffffff81fe2b54)
Location: include/linux/cpumask.h:611
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:SyS_sched_getaffinity
  - kernel/sched/core.c:SyS_sched_setaffinity
```
```
In kernel/compat.c (ffffffff81120a30)
Location: include/linux/cpumask.h:611
Inline: True
Inline callers:
  - kernel/compat.c:compat_SyS_sched_getaffinity
  - kernel/compat.c:compat_SyS_sched_setaffinity
```
```
In lib/cpumask.c (ffffffff82003fbf)
Location: include/linux/cpumask.h:611
Inline: True
Inline callers:
  - lib/cpumask.c:free_bootmem_cpumask_var
  - lib/cpumask.c:alloc_bootmem_cpumask_var
  - lib/cpumask.c:alloc_cpumask_var_node
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
In kernel/sched/core.c (ffffffff820c33f4)
Location: include/linux/cpumask.h:639
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:SyS_sched_getaffinity
  - kernel/sched/core.c:SyS_sched_setaffinity
```
```
In kernel/sched/topology.c (ffffffff810cc63b)
Location: include/linux/cpumask.h:639
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_init_numa
```
```
In kernel/compat.c (ffffffff81121325)
Location: include/linux/cpumask.h:639
Inline: True
Inline callers:
  - kernel/compat.c:compat_SyS_sched_getaffinity
  - kernel/compat.c:compat_SyS_sched_setaffinity
```
```
In lib/cpumask.c (ffffffff8210f161)
Location: include/linux/cpumask.h:639
Inline: True
Inline callers:
  - lib/cpumask.c:free_bootmem_cpumask_var
  - lib/cpumask.c:alloc_bootmem_cpumask_var
  - lib/cpumask.c:alloc_cpumask_var_node
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
In kernel/sched/core.c (ffffffff826cb473)
Location: include/linux/cpumask.h:643
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:SyS_sched_getaffinity
  - kernel/sched/core.c:SyS_sched_setaffinity
```
```
In kernel/sched/topology.c (ffffffff810d3327)
Location: include/linux/cpumask.h:643
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_init_numa
```
```
In kernel/compat.c (ffffffff8112c995)
Location: include/linux/cpumask.h:643
Inline: True
Inline callers:
  - kernel/compat.c:compat_SyS_sched_getaffinity
  - kernel/compat.c:compat_SyS_sched_setaffinity
```
```
In lib/cpumask.c (ffffffff82719552)
Location: include/linux/cpumask.h:643
Inline: True
Inline callers:
  - lib/cpumask.c:free_bootmem_cpumask_var
  - lib/cpumask.c:alloc_bootmem_cpumask_var
  - lib/cpumask.c:alloc_cpumask_var_node
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
In kernel/sched/core.c (ffffffff826f55d4)
Location: include/linux/cpumask.h:645
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/sched/core.c:get_user_cpu_mask
```
```
In kernel/sched/topology.c (ffffffff810dafff)
Location: include/linux/cpumask.h:645
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_init_numa
```
```
In kernel/compat.c (ffffffff8113b155)
Location: include/linux/cpumask.h:645
Inline: True
Inline callers:
  - kernel/compat.c:__x32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
  - kernel/compat.c:compat_get_user_cpu_mask
```
```
In lib/cpumask.c (ffffffff82743d10)
Location: include/linux/cpumask.h:645
Inline: True
Inline callers:
  - lib/cpumask.c:free_bootmem_cpumask_var
  - lib/cpumask.c:alloc_bootmem_cpumask_var
  - lib/cpumask.c:alloc_cpumask_var_node
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
In kernel/fork.c (ffffffff828a9b3b)
Location: include/linux/cpumask.h:657
Inline: True
Inline callers:
  - kernel/fork.c:proc_caches_init
```
```
In kernel/sched/core.c (ffffffff828ac419)
Location: include/linux/cpumask.h:657
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/sched/core.c:get_user_cpu_mask
```
```
In kernel/sched/topology.c (ffffffff810e4baf)
Location: include/linux/cpumask.h:657
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_init_numa
```
```
In kernel/compat.c (ffffffff811469c5)
Location: include/linux/cpumask.h:657
Inline: True
Inline callers:
  - kernel/compat.c:__x32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
  - kernel/compat.c:compat_get_user_cpu_mask
```
```
In drivers/powercap/idle_inject.c (ffffffff81883ee5)
Location: include/linux/cpumask.h:657
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_register
```
```
In lib/cpumask.c (ffffffff828fe031)
Location: include/linux/cpumask.h:657
Inline: True
Inline callers:
  - lib/cpumask.c:free_bootmem_cpumask_var
  - lib/cpumask.c:alloc_bootmem_cpumask_var
  - lib/cpumask.c:alloc_cpumask_var_node
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
In kernel/fork.c (ffffffff828c2204)
Location: include/linux/cpumask.h:656
Inline: True
Inline callers:
  - kernel/fork.c:proc_caches_init
```
```
In kernel/sched/core.c (ffffffff828c4cec)
Location: include/linux/cpumask.h:656
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/sched/core.c:get_user_cpu_mask
```
```
In kernel/sched/topology.c (ffffffff810ebb4f)
Location: include/linux/cpumask.h:656
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/compat.c (ffffffff81151b18)
Location: include/linux/cpumask.h:656
Inline: True
Inline callers:
  - kernel/compat.c:__x32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
  - kernel/compat.c:compat_get_user_cpu_mask
```
```
In drivers/powercap/idle_inject.c (ffffffff818ce5f5)
Location: include/linux/cpumask.h:656
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_register
```
```
In lib/cpumask.c (ffffffff8291ac91)
Location: include/linux/cpumask.h:656
Inline: True
Inline callers:
  - lib/cpumask.c:free_bootmem_cpumask_var
  - lib/cpumask.c:alloc_bootmem_cpumask_var
  - lib/cpumask.c:alloc_bootmem_cpumask_var
  - lib/cpumask.c:alloc_cpumask_var_node
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
In kernel/fork.c (ffffffff828ca7ff)
Location: include/linux/cpumask.h:686
Inline: True
Inline callers:
  - kernel/fork.c:proc_caches_init
```
```
In kernel/sched/core.c (ffffffff828cd2da)
Location: include/linux/cpumask.h:686
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/sched/core.c:get_user_cpu_mask
```
```
In kernel/sched/topology.c (ffffffff810f7516)
Location: include/linux/cpumask.h:686
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/compat.c (ffffffff8115d768)
Location: include/linux/cpumask.h:686
Inline: True
Inline callers:
  - kernel/compat.c:__x32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
  - kernel/compat.c:compat_get_user_cpu_mask
```
```
In drivers/powercap/idle_inject.c (ffffffff819009e5)
Location: include/linux/cpumask.h:686
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_register
```
```
In lib/cpumask.c (ffffffff82924b00)
Location: include/linux/cpumask.h:686
Inline: True
Inline callers:
  - lib/cpumask.c:free_bootmem_cpumask_var
  - lib/cpumask.c:alloc_bootmem_cpumask_var
  - lib/cpumask.c:alloc_bootmem_cpumask_var
  - lib/cpumask.c:alloc_cpumask_var_node
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff82cecd9a)
Location: include/linux/cpumask.h:691
Inline: True
Inline callers:
  - kernel/fork.c:proc_caches_init
```
```
In kernel/sched/core.c (ffffffff82cee74f)
Location: include/linux/cpumask.h:691
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/sched/core.c:get_user_cpu_mask
```
```
In kernel/sched/topology.c (ffffffff811011d8)
Location: include/linux/cpumask.h:691
Inline: True
Inline callers:
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:build_group_from_child_sched_domain
```
```
In kernel/power/energy_model.c (ffffffff8111ca18)
Location: include/linux/cpumask.h:691
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_create_pd
```
```
In kernel/compat.c (ffffffff8116e1a8)
Location: include/linux/cpumask.h:691
Inline: True
Inline callers:
  - kernel/compat.c:__x32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
  - kernel/compat.c:compat_get_user_cpu_mask
```
```
In lib/cpumask.c (ffffffff82d0a910)
Location: include/linux/cpumask.h:691
Inline: True
Inline callers:
  - lib/cpumask.c:free_bootmem_cpumask_var
  - lib/cpumask.c:alloc_bootmem_cpumask_var
  - lib/cpumask.c:alloc_bootmem_cpumask_var
  - lib/cpumask.c:alloc_cpumask_var_node
```
```
In drivers/powercap/idle_inject.c (ffffffff819d79e5)
Location: include/linux/cpumask.h:691
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff82fd93f4)
Location: include/linux/cpumask.h:697
Inline: True
Inline callers:
  - kernel/fork.c:proc_caches_init
```
```
In kernel/sched/core.c (ffffffff82fdae4d)
Location: include/linux/cpumask.h:697
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/sched/core.c:get_user_cpu_mask
```
```
In kernel/sched/topology.c (ffffffff810ffd38)
Location: include/linux/cpumask.h:697
Inline: True
Inline callers:
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:build_group_from_child_sched_domain
```
```
In kernel/power/energy_model.c (ffffffff811176f5)
Location: include/linux/cpumask.h:697
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_create_pd
```
```
In kernel/compat.c (ffffffff8116a7b8)
Location: include/linux/cpumask.h:697
Inline: True
Inline callers:
  - kernel/compat.c:__x32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
  - kernel/compat.c:compat_get_user_cpu_mask
```
```
In lib/cpumask.c (ffffffff82ff7f04)
Location: include/linux/cpumask.h:697
Inline: True
Inline callers:
  - lib/cpumask.c:free_bootmem_cpumask_var
  - lib/cpumask.c:alloc_bootmem_cpumask_var
  - lib/cpumask.c:alloc_bootmem_cpumask_var
  - lib/cpumask.c:alloc_cpumask_var_node
```
```
In drivers/powercap/idle_inject.c (ffffffff819d6b25)
Location: include/linux/cpumask.h:697
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff831e3d48)
Location: include/linux/cpumask.h:668
Inline: True
Inline callers:
  - kernel/fork.c:proc_caches_init
```
```
In kernel/sched/core.c (ffffffff831e594b)
Location: include/linux/cpumask.h:668
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/sched/core.c:get_user_cpu_mask
```
```
In kernel/sched/topology.c (ffffffff81101938)
Location: include/linux/cpumask.h:668
Inline: True
Inline callers:
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/power/energy_model.c (ffffffff81117cb5)
Location: include/linux/cpumask.h:668
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_create_pd
```
```
In kernel/compat.c (ffffffff8116b418)
Location: include/linux/cpumask.h:668
Inline: True
Inline callers:
  - kernel/compat.c:__x32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
  - kernel/compat.c:compat_get_user_cpu_mask
```
```
In lib/cpumask.c (ffffffff83202b7b)
Location: include/linux/cpumask.h:668
Inline: True
Inline callers:
  - lib/cpumask.c:free_bootmem_cpumask_var
  - lib/cpumask.c:alloc_bootmem_cpumask_var
  - lib/cpumask.c:alloc_bootmem_cpumask_var
  - lib/cpumask.c:alloc_cpumask_var_node
```
```
In drivers/powercap/idle_inject.c (ffffffff819bcca5)
Location: include/linux/cpumask.h:668
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff832c7920)
Location: include/linux/cpumask.h:668
Inline: True
Inline callers:
  - kernel/fork.c:proc_caches_init
```
```
In kernel/sched/core.c (ffffffff832c98ff)
Location: include/linux/cpumask.h:668
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/sched/core.c:get_user_cpu_mask
  - kernel/sched/core.c:dup_user_cpus_ptr
```
```
In kernel/sched/topology.c (ffffffff8111dc37)
Location: include/linux/cpumask.h:668
Inline: True
Inline callers:
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:asym_cpu_capacity_scan
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/power/energy_model.c (ffffffff81138015)
Location: include/linux/cpumask.h:668
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_create_pd
```
```
In kernel/compat.c (ffffffff81191018)
Location: include/linux/cpumask.h:668
Inline: True
Inline callers:
  - kernel/compat.c:__x64_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
  - kernel/compat.c:compat_get_user_cpu_mask
```
```
In fs/io_uring.c (ffffffff813ded11)
Location: include/linux/cpumask.h:668
Inline: True
```
```
In lib/cpumask.c (ffffffff832ea377)
Location: include/linux/cpumask.h:668
Inline: True
Inline callers:
  - lib/cpumask.c:free_bootmem_cpumask_var
  - lib/cpumask.c:alloc_bootmem_cpumask_var
  - lib/cpumask.c:alloc_bootmem_cpumask_var
  - lib/cpumask.c:alloc_cpumask_var_node
```
```
In drivers/powercap/idle_inject.c (ffffffff81a6c1d5)
Location: include/linux/cpumask.h:668
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8347a7e8)
Location: include/linux/cpumask.h:694
Inline: True
Inline callers:
  - kernel/fork.c:proc_caches_init
```
```
In kernel/sched/core.c (ffffffff8347cb8f)
Location: include/linux/cpumask.h:694
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/sched/core.c:get_user_cpu_mask
  - kernel/sched/core.c:dup_user_cpus_ptr
```
```
In kernel/sched/build_utility.c (ffffffff8113fde8)
Location: include/linux/cpumask.h:694
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:asym_cpu_capacity_scan
  - kernel/sched/build_utility.c:build_overlap_sched_groups
```
```
In kernel/power/energy_model.c (ffffffff8115a77b)
Location: include/linux/cpumask.h:694
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_create_pd
```
```
In kernel/compat.c (ffffffff811c071a)
Location: include/linux/cpumask.h:694
Inline: True
Inline callers:
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_setaffinity
```
```
In io_uring/io_uring.c (ffffffff81e8f66c)
Location: include/linux/cpumask.h:694
Inline: True
```
```
In lib/cpumask.c (ffffffff834a1ce6)
Location: include/linux/cpumask.h:694
Inline: True
Inline callers:
  - lib/cpumask.c:free_bootmem_cpumask_var
  - lib/cpumask.c:alloc_bootmem_cpumask_var
  - lib/cpumask.c:alloc_bootmem_cpumask_var
  - lib/cpumask.c:alloc_cpumask_var_node
```
```
In drivers/powercap/idle_inject.c (ffffffff81bdcce5)
Location: include/linux/cpumask.h:694
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_register
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
In kernel/fork.c (ffffffff83ea4ff5)
Location: include/linux/cpumask.h:770
Inline: True
Inline callers:
  - kernel/fork.c:mm_cache_init
```
```
In kernel/sched/core.c (ffffffff8114074f)
Location: include/linux/cpumask.h:770
Inline: True
Inline callers:
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/sched/core.c:get_user_cpu_mask
  - kernel/sched/core.c:alloc_user_cpus_ptr
```
```
In kernel/sched/build_utility.c (ffffffff8116bdf5)
Location: include/linux/cpumask.h:770
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:asym_cpu_capacity_scan
  - kernel/sched/build_utility.c:build_overlap_sched_groups
```
```
In kernel/power/energy_model.c (ffffffff8118cb9b)
Location: include/linux/cpumask.h:770
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_create_pd
```
```
In kernel/compat.c (ffffffff81202b1f)
Location: include/linux/cpumask.h:770
Inline: True
Inline callers:
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_setaffinity
```
```
In io_uring/io_uring.c (ffffffff81788ef0)
Location: include/linux/cpumask.h:770
Inline: True
```
```
In drivers/powercap/idle_inject.c (ffffffff81d87e55)
Location: include/linux/cpumask.h:770
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_register
```
```
In lib/cpumask.c (ffffffff83f17c80)
Location: include/linux/cpumask.h:770
Inline: True
Inline callers:
  - lib/cpumask.c:free_bootmem_cpumask_var
  - lib/cpumask.c:alloc_bootmem_cpumask_var
  - lib/cpumask.c:alloc_bootmem_cpumask_var
  - lib/cpumask.c:alloc_cpumask_var_node
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
In kernel/fork.c (ffffffff836c9375)
Location: include/linux/cpumask.h:822
Inline: True
Inline callers:
  - kernel/fork.c:mm_cache_init
  - kernel/fork.c:mm_init
```
```
In kernel/sched/core.c (ffffffff81152356)
Location: include/linux/cpumask.h:822
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_mm_cid_before_execve
  - kernel/sched/core.c:task_mm_cid_work
  - kernel/sched/core.c:sched_mm_cid_remote_clear
  - kernel/sched/core.c:sched_mm_cid_migrate_to
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/sched/core.c:get_user_cpu_mask
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:alloc_user_cpus_ptr
  - kernel/sched/core.c:mm_cid_get
  - kernel/sched/core.c:mm_cid_get
  - kernel/sched/core.c:mm_cid_get
  - kernel/sched/core.c:mm_cid_get
```
```
In kernel/sched/build_utility.c (ffffffff8117c355)
Location: include/linux/cpumask.h:822
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:asym_cpu_capacity_scan
  - kernel/sched/build_utility.c:build_overlap_sched_groups
```
```
In kernel/power/energy_model.c (ffffffff8119e2cb)
Location: include/linux/cpumask.h:822
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_create_pd
```
```
In kernel/compat.c (ffffffff81217edf)
Location: include/linux/cpumask.h:822
Inline: True
Inline callers:
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_setaffinity
```
```
In fs/exec.c (ffffffff814b888a)
Location: include/linux/cpumask.h:822
Inline: True
Inline callers:
  - fs/exec.c:mm_init_cid
```
```
In io_uring/io_uring.c (ffffffff817cadbf)
Location: include/linux/cpumask.h:822
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_register_iowq_aff
```
```
In drivers/powercap/idle_inject.c (ffffffff81df63b5)
Location: include/linux/cpumask.h:822
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_register_full
```
```
In net/core/sysctl_net_core.c (ffffffff81e2a8c4)
Location: include/linux/cpumask.h:822
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:rps_default_mask_sysctl
```
```
In lib/cpumask.c (ffffffff8373e440)
Location: include/linux/cpumask.h:822
Inline: True
Inline callers:
  - lib/cpumask.c:free_bootmem_cpumask_var
  - lib/cpumask.c:alloc_bootmem_cpumask_var
  - lib/cpumask.c:alloc_bootmem_cpumask_var
  - lib/cpumask.c:alloc_cpumask_var_node
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
In kernel/fork.c (ffffffff838f9fc5)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - kernel/fork.c:mm_cache_init
  - kernel/fork.c:mm_init
```
```
In kernel/sched/core.c (ffffffff8115e208)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_mm_cid_before_execve
  - kernel/sched/core.c:task_mm_cid_work
  - kernel/sched/core.c:sched_mm_cid_remote_clear
  - kernel/sched/core.c:sched_mm_cid_migrate_to
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/sched/core.c:get_user_cpu_mask
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:alloc_user_cpus_ptr
  - kernel/sched/core.c:mm_cid_get
  - kernel/sched/core.c:mm_cid_get
  - kernel/sched/core.c:mm_cid_get
  - kernel/sched/core.c:mm_cid_get
```
```
In kernel/sched/build_utility.c (ffffffff8118a035)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:asym_cpu_capacity_scan
  - kernel/sched/build_utility.c:build_overlap_sched_groups
```
```
In kernel/power/energy_model.c (ffffffff811ad46e)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_create_pd
```
```
In kernel/compat.c (ffffffff8122fa9f)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_setaffinity
```
```
In kernel/trace/trace_events_filter.c (ffffffff812c8230)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:parse_pred
```
```
In fs/exec.c (ffffffff814ead9a)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - fs/exec.c:mm_init_cid
```
```
In io_uring/register.c (ffffffff8182b38f)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - io_uring/register.c:io_register_iowq_aff
```
```
In drivers/powercap/idle_inject.c (ffffffff81eacaa5)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_register_full
```
```
In net/core/sysctl_net_core.c (ffffffff81ee8944)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:rps_default_mask_sysctl
```
```
In lib/cpumask.c (ffffffff83972e60)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - lib/cpumask.c:free_bootmem_cpumask_var
  - lib/cpumask.c:alloc_bootmem_cpumask_var
  - lib/cpumask.c:alloc_bootmem_cpumask_var
  - lib/cpumask.c:alloc_cpumask_var_node
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
In kernel/fork.c (0)
Location: include/linux/cpumask.h:686
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/cpumask.h:686
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/cpumask.h:686
Inline: True
```
```
In kernel/compat.c (0)
Location: include/linux/cpumask.h:686
Inline: True
```
```
In drivers/powercap/idle_inject.c (0)
Location: include/linux/cpumask.h:686
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
In kernel/fork.c (0)
Location: include/linux/cpumask.h:686
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/cpumask.h:686
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/cpumask.h:686
Inline: True
```
```
In drivers/cpuidle/cpuidle-big_little.c (0)
Location: include/linux/cpumask.h:686
Inline: True
```
```
In drivers/powercap/idle_inject.c (0)
Location: include/linux/cpumask.h:686
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
In kernel/fork.c (0)
Location: include/linux/cpumask.h:686
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/cpumask.h:686
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/cpumask.h:686
Inline: True
```
```
In kernel/compat.c (0)
Location: include/linux/cpumask.h:686
Inline: True
```
```
In drivers/powercap/idle_inject.c (0)
Location: include/linux/cpumask.h:686
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
In kernel/fork.c (0)
Location: include/linux/cpumask.h:686
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/cpumask.h:686
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/cpumask.h:686
Inline: True
```
</details>
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
In kernel/fork.c (ffffffff828b35f2)
Location: include/linux/cpumask.h:686
Inline: True
Inline callers:
  - kernel/fork.c:proc_caches_init
```
```
In kernel/sched/core.c (ffffffff828b60b6)
Location: include/linux/cpumask.h:686
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/sched/core.c:get_user_cpu_mask
```
```
In kernel/sched/topology.c (ffffffff810f0916)
Location: include/linux/cpumask.h:686
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/compat.c (ffffffff81155d88)
Location: include/linux/cpumask.h:686
Inline: True
Inline callers:
  - kernel/compat.c:__x32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
  - kernel/compat.c:compat_get_user_cpu_mask
```
```
In lib/cpumask.c (ffffffff82909804)
Location: include/linux/cpumask.h:686
Inline: True
Inline callers:
  - lib/cpumask.c:free_bootmem_cpumask_var
  - lib/cpumask.c:alloc_bootmem_cpumask_var
  - lib/cpumask.c:alloc_bootmem_cpumask_var
  - lib/cpumask.c:alloc_cpumask_var_node
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
In kernel/fork.c (ffffffff828ab773)
Location: include/linux/cpumask.h:686
Inline: True
Inline callers:
  - kernel/fork.c:proc_caches_init
```
```
In kernel/sched/core.c (ffffffff828ae258)
Location: include/linux/cpumask.h:686
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/sched/core.c:get_user_cpu_mask
```
```
In kernel/sched/topology.c (ffffffff810e0986)
Location: include/linux/cpumask.h:686
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/compat.c (ffffffff811490a8)
Location: include/linux/cpumask.h:686
Inline: True
Inline callers:
  - kernel/compat.c:__x32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
  - kernel/compat.c:compat_get_user_cpu_mask
```
```
In lib/cpumask.c (ffffffff82901b52)
Location: include/linux/cpumask.h:686
Inline: True
Inline callers:
  - lib/cpumask.c:free_bootmem_cpumask_var
  - lib/cpumask.c:alloc_bootmem_cpumask_var
  - lib/cpumask.c:alloc_bootmem_cpumask_var
  - lib/cpumask.c:alloc_cpumask_var_node
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
In kernel/fork.c (ffffffff828c64f1)
Location: include/linux/cpumask.h:686
Inline: True
Inline callers:
  - kernel/fork.c:proc_caches_init
```
```
In kernel/sched/core.c (ffffffff828c8fcc)
Location: include/linux/cpumask.h:686
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/sched/core.c:get_user_cpu_mask
```
```
In kernel/sched/topology.c (ffffffff810eda46)
Location: include/linux/cpumask.h:686
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/compat.c (ffffffff81153b58)
Location: include/linux/cpumask.h:686
Inline: True
Inline callers:
  - kernel/compat.c:__x32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
  - kernel/compat.c:compat_get_user_cpu_mask
```
```
In drivers/powercap/idle_inject.c (ffffffff818f1405)
Location: include/linux/cpumask.h:686
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_register
```
```
In lib/cpumask.c (ffffffff8291f14e)
Location: include/linux/cpumask.h:686
Inline: True
Inline callers:
  - lib/cpumask.c:free_bootmem_cpumask_var
  - lib/cpumask.c:alloc_bootmem_cpumask_var
  - lib/cpumask.c:alloc_bootmem_cpumask_var
  - lib/cpumask.c:alloc_cpumask_var_node
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
In kernel/fork.c (ffffffff828cb83c)
Location: include/linux/cpumask.h:686
Inline: True
Inline callers:
  - kernel/fork.c:proc_caches_init
```
```
In kernel/sched/core.c (ffffffff828ce30c)
Location: include/linux/cpumask.h:686
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/sched/core.c:get_user_cpu_mask
```
```
In kernel/sched/topology.c (ffffffff810f8a86)
Location: include/linux/cpumask.h:686
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/compat.c (ffffffff81160a58)
Location: include/linux/cpumask.h:686
Inline: True
Inline callers:
  - kernel/compat.c:__x32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
  - kernel/compat.c:compat_get_user_cpu_mask
```
```
In drivers/powercap/idle_inject.c (ffffffff81912485)
Location: include/linux/cpumask.h:686
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_register
```
```
In lib/cpumask.c (ffffffff82925b72)
Location: include/linux/cpumask.h:686
Inline: True
Inline callers:
  - lib/cpumask.c:free_bootmem_cpumask_var
  - lib/cpumask.c:alloc_bootmem_cpumask_var
  - lib/cpumask.c:alloc_bootmem_cpumask_var
  - lib/cpumask.c:alloc_cpumask_var_node
```
</details>
</li>
</ul>

## Differences
