# Function: <code>bitmap_parselist</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int bitmap_parselist(const char *bp, long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff813f9b50)
Location: lib/bitmap.c:583
Inline: False
Direct callers:
  - kernel/sched/core.c:isolated_cpu_setup
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/taskstats.c:parse
  - mm/mempolicy.c:mpol_parse_str
  - drivers/input/keyboard/atkbd.c:atkbd_set_force_release
```
**Symbols:**

```
ffffffff813f9b50-ffffffff813f9b89: bitmap_parselist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int bitmap_parselist(const char *bp, long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81440ba0)
Location: lib/bitmap.c:585
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:irq_affinity_setup
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/taskstats.c:parse
  - mm/mempolicy.c:mpol_parse_str
  - drivers/input/keyboard/atkbd.c:atkbd_set_force_release
```
**Symbols:**

```
ffffffff81440ba0-ffffffff81440bd9: bitmap_parselist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int bitmap_parselist(const char *bp, long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8145ddc0)
Location: lib/bitmap.c:627
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:irq_affinity_setup
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/taskstats.c:parse
  - mm/mempolicy.c:mpol_parse_str
  - drivers/input/keyboard/atkbd.c:atkbd_set_force_release
```
**Symbols:**

```
ffffffff8145ddc0-ffffffff8145ddf9: bitmap_parselist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int bitmap_parselist(const char *bp, long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81462d20)
Location: lib/bitmap.c:627
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - kernel/irq/irqdesc.c:irq_affinity_setup
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/taskstats.c:parse
  - mm/mempolicy.c:mpol_parse_str
  - drivers/input/keyboard/atkbd.c:atkbd_set_force_release
```
**Symbols:**

```
ffffffff81462d20-ffffffff81462d59: bitmap_parselist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int bitmap_parselist(const char *bp, long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8148ec30)
Location: lib/bitmap.c:623
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/irq/irqdesc.c:irq_affinity_setup
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/taskstats.c:parse
  - mm/mempolicy.c:mpol_parse_str
  - drivers/input/keyboard/atkbd.c:atkbd_set_force_release
```
**Symbols:**

```
ffffffff8148ec30-ffffffff8148ec69: bitmap_parselist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bitmap_parselist(const char *bp, long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff814c3a00)
Location: lib/bitmap.c:620
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/irq/irqdesc.c:irq_affinity_setup
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/taskstats.c:parse
  - mm/mempolicy.c:mpol_parse_str
  - drivers/input/keyboard/atkbd.c:atkbd_set_force_release
```
**Symbols:**

```
ffffffff814c3a00-ffffffff814c3a39: bitmap_parselist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bitmap_parselist(const char *bp, long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff814d7ed0)
Location: lib/bitmap.c:615
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/irq/irqdesc.c:irq_affinity_setup
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/taskstats.c:parse
  - mm/mempolicy.c:mpol_parse_str
  - drivers/input/keyboard/atkbd.c:atkbd_set_force_release
```
**Symbols:**

```
ffffffff814d7ed0-ffffffff814d7f09: bitmap_parselist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bitmap_parselist(const char *buf, long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81503b30)
Location: lib/bitmap.c:622
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/irq/irqdesc.c:irq_affinity_setup
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/taskstats.c:parse
  - mm/mempolicy.c:mpol_parse_str
  - lib/bitmap.c:bitmap_parselist_user
  - drivers/input/keyboard/atkbd.c:atkbd_set_force_release
```
**Symbols:**

```
ffffffff81503b30-ffffffff81503d6f: bitmap_parselist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bitmap_parselist(const char *buf, long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81521ad0)
Location: lib/bitmap.c:642
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/irq/irqdesc.c:irq_affinity_setup
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/taskstats.c:parse
  - mm/mempolicy.c:mpol_parse_str
  - lib/bitmap.c:bitmap_parselist_user
  - drivers/input/keyboard/atkbd.c:atkbd_set_force_release
```
**Symbols:**

```
ffffffff81521ad0-ffffffff81521d0f: bitmap_parselist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bitmap_parselist(const char *buf, long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81585130)
Location: lib/bitmap.c:638
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/irq/irqdesc.c:irq_affinity_setup
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/taskstats.c:parse
  - mm/mempolicy.c:mpol_parse_str
  - lib/bitmap.c:bitmap_parselist_user
  - drivers/input/keyboard/atkbd.c:atkbd_set_force_release
```
**Symbols:**

```
ffffffff81585130-ffffffff8158524d: bitmap_parselist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bitmap_parselist(const char *buf, long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815a2230)
Location: lib/bitmap.c:638
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/irq/irqdesc.c:irq_affinity_setup
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/taskstats.c:parse
  - mm/mempolicy.c:mpol_parse_str
  - lib/bitmap.c:bitmap_parselist_user
  - drivers/input/keyboard/atkbd.c:atkbd_set_force_release
```
**Symbols:**

```
ffffffff815a2230-ffffffff815a234d: bitmap_parselist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bitmap_parselist(const char *buf, long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815a8f50)
Location: lib/bitmap.c:650
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/irq/irqdesc.c:irq_affinity_setup
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/taskstats.c:parse
  - mm/mempolicy.c:mpol_parse_str
  - lib/bitmap.c:bitmap_parselist_user
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_force_release
```
**Symbols:**

```
ffffffff815a8f50-ffffffff815a92bc: bitmap_parselist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bitmap_parselist(const char *buf, long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81612300)
Location: lib/bitmap.c:780
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/irq/irqdesc.c:irq_affinity_setup
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/taskstats.c:parse
  - mm/mempolicy.c:mpol_parse_str
  - lib/bitmap.c:bitmap_parselist_user
  - drivers/acpi/sysfs.c:acpi_gpe_set_masked_gpes
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_force_release
```
**Symbols:**

```
ffffffff81612300-ffffffff81612419: bitmap_parselist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bitmap_parselist(const char *buf, long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff816de410)
Location: lib/bitmap.c:796
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/irq/irqdesc.c:irq_affinity_setup
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/taskstats.c:parse
  - mm/mempolicy.c:mpol_parse_str
  - lib/bitmap.c:bitmap_parselist_user
  - drivers/acpi/sysfs.c:acpi_gpe_set_masked_gpes
  - drivers/input/keyboard/atkbd.c:atkbd_set_force_release
```
**Symbols:**

```
ffffffff816de410-ffffffff816de7c8: bitmap_parselist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bitmap_parselist(const char *buf, long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff817ce710)
Location: lib/bitmap.c:807
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/irq/irqdesc.c:irq_affinity_setup
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/taskstats.c:parse
  - mm/mempolicy.c:mpol_parse_str
  - lib/bitmap.c:bitmap_parselist_user
  - drivers/acpi/sysfs.c:acpi_gpe_set_masked_gpes
  - drivers/input/keyboard/atkbd.c:atkbd_set_force_release
```
**Symbols:**

```
ffffffff817ce710-ffffffff817cead6: bitmap_parselist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bitmap_parselist(const char *buf, long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8180cbc0)
Location: lib/bitmap.c:807
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/irq/irqdesc.c:irq_affinity_setup
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/taskstats.c:parse
  - kernel/trace/trace_osnoise.c:osnoise_cpus_write
  - mm/mempolicy.c:mpol_parse_str
  - lib/bitmap.c:bitmap_parselist_user
  - drivers/acpi/sysfs.c:acpi_gpe_set_masked_gpes
  - drivers/input/keyboard/atkbd.c:atkbd_set_force_release
```
**Symbols:**

```
ffffffff8180cbc0-ffffffff8180cf83: bitmap_parselist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bitmap_parselist(const char *buf, long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap-str.c (ffffffff81861810)
Location: lib/bitmap-str.c:374
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - kernel/workqueue.c:workqueue_unbound_cpus_setup
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/irq/irqdesc.c:irq_affinity_setup
  - kernel/rcu/tree.c:rcu_nocb_setup
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_exclusive_cpumask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/taskstats.c:parse
  - kernel/trace/trace_osnoise.c:osnoise_cpus_write
  - kernel/trace/trace_events_filter.c:parse_pred
  - mm/mempolicy.c:mpol_parse_str
  - lib/bitmap-str.c:bitmap_parselist_user
  - drivers/acpi/sysfs.c:acpi_gpe_set_masked_gpes
  - drivers/input/keyboard/atkbd.c:atkbd_set_force_release
```
**Symbols:**

```
ffffffff81861810-ffffffff81861bd3: bitmap_parselist (STB_GLOBAL)
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
int bitmap_parselist(const char *buf, long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffff80001062b300)
Location: lib/bitmap.c:642
Inline: False
Direct callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/irq/irqdesc.c:irq_affinity_setup
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/taskstats.c:parse
  - mm/mempolicy.c:mpol_parse_str
  - lib/bitmap.c:bitmap_parselist_user
  - drivers/input/keyboard/atkbd.c:atkbd_set_force_release
```
**Symbols:**

```
ffff80001062b300-ffff80001062b58c: bitmap_parselist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bitmap_parselist(const char *buf, long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (c07d25a8)
Location: lib/bitmap.c:642
Inline: False
Direct callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/irq/irqdesc.c:irq_affinity_setup
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/taskstats.c:parse
  - lib/bitmap.c:bitmap_parselist_user
  - drivers/input/keyboard/atkbd.c:atkbd_set_force_release
```
**Symbols:**

```
c07d25a8-c07d2808: bitmap_parselist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bitmap_parselist(const char *buf, long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (c0000000007cd870)
Location: lib/bitmap.c:642
Inline: False
Direct callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/irq/irqdesc.c:irq_affinity_setup
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/taskstats.c:parse
  - mm/mempolicy.c:mpol_parse_str
  - lib/bitmap.c:bitmap_parselist_user
  - drivers/input/keyboard/atkbd.c:atkbd_set_force_release
```
**Symbols:**

```
c0000000007cd870-c0000000007cdb90: bitmap_parselist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bitmap_parselist(const char *buf, long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffe00045bd2a)
Location: lib/bitmap.c:642
Inline: False
Direct callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/irq/irqdesc.c:irq_affinity_setup
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/taskstats.c:parse
  - lib/bitmap.c:bitmap_parselist_user
  - drivers/input/keyboard/atkbd.c:atkbd_set_force_release
```
**Symbols:**

```
ffffffe00045bd2a-ffffffe00045bf1a: bitmap_parselist (STB_GLOBAL)
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
int bitmap_parselist(const char *buf, long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8151a0b0)
Location: lib/bitmap.c:642
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/irq/irqdesc.c:irq_affinity_setup
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/taskstats.c:parse
  - mm/mempolicy.c:mpol_parse_str
  - lib/bitmap.c:bitmap_parselist_user
  - drivers/input/keyboard/atkbd.c:atkbd_set_force_release
```
**Symbols:**

```
ffffffff8151a0b0-ffffffff8151a2ef: bitmap_parselist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bitmap_parselist(const char *buf, long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8150a3a0)
Location: lib/bitmap.c:642
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/irq/irqdesc.c:irq_affinity_setup
  - kernel/rcu/tree.c:rcu_nocb_setup
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/taskstats.c:parse
  - mm/mempolicy.c:mpol_parse_str
  - lib/bitmap.c:bitmap_parselist_user
  - drivers/input/keyboard/atkbd.c:atkbd_set_force_release
```
**Symbols:**

```
ffffffff8150a3a0-ffffffff8150a5df: bitmap_parselist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bitmap_parselist(const char *buf, long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81516140)
Location: lib/bitmap.c:642
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/irq/irqdesc.c:irq_affinity_setup
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/taskstats.c:parse
  - mm/mempolicy.c:mpol_parse_str
  - lib/bitmap.c:bitmap_parselist_user
  - drivers/input/keyboard/atkbd.c:atkbd_set_force_release
```
**Symbols:**

```
ffffffff81516140-ffffffff8151637f: bitmap_parselist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bitmap_parselist(const char *buf, long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8152f8d0)
Location: lib/bitmap.c:642
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/irq/irqdesc.c:irq_affinity_setup
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/taskstats.c:parse
  - mm/mempolicy.c:mpol_parse_str
  - lib/bitmap.c:bitmap_parselist_user
  - drivers/input/keyboard/atkbd.c:atkbd_set_force_release
```
**Symbols:**

```
ffffffff8152f8d0-ffffffff8152fb0f: bitmap_parselist (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const char *buf</code>
</li>
<li>
<b>Param removed. </b>
<code>const char *bp</code>
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
