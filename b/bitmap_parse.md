# Function: <code>bitmap_parse</code>

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
In kernel/workqueue.c (ffffffff8109c63a)
Location: include/linux/bitmap.h:323
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_unbound_cpumask_store
```
```
In kernel/padata.c (ffffffff8118a656)
Location: include/linux/bitmap.h:323
Inline: True
Inline callers:
  - kernel/padata.c:store_cpumask
```
```
In net/core/net-sysfs.c (ffffffff81736331)
Location: include/linux/bitmap.h:323
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_xps_map
  - net/core/net-sysfs.c:store_rps_map
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
In kernel/workqueue.c (ffffffff810a0a5b)
Location: include/linux/bitmap.h:336
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
```
```
In kernel/padata.c (ffffffff8119cd26)
Location: include/linux/bitmap.h:336
Inline: True
Inline callers:
  - kernel/padata.c:store_cpumask
```
```
In net/core/net-sysfs.c (ffffffff817a24e1)
Location: include/linux/bitmap.h:336
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_xps_map
  - net/core/net-sysfs.c:store_rps_map
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
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81044422)
Location: include/linux/bitmap.h:336
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
```
```
In kernel/workqueue.c (ffffffff810a5b1a)
Location: include/linux/bitmap.h:336
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
```
```
In kernel/padata.c (ffffffff811ac72a)
Location: include/linux/bitmap.h:336
Inline: True
Inline callers:
  - kernel/padata.c:store_cpumask
```
```
In net/core/net-sysfs.c (ffffffff817d0e1b)
Location: include/linux/bitmap.h:336
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_xps_map
  - net/core/net-sysfs.c:store_rps_map
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
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff810433ce)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
```
```
In kernel/workqueue.c (ffffffff810a2b83)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
```
```
In kernel/padata.c (ffffffff811b3d51)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - kernel/padata.c:store_cpumask
```
```
In net/core/net-sysfs.c (ffffffff817effeb)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_xps_map
  - net/core/net-sysfs.c:store_rps_map
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
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81046a22)
Location: include/linux/bitmap.h:379
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
```
```
In kernel/workqueue.c (ffffffff810a94b3)
Location: include/linux/bitmap.h:379
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
```
```
In kernel/padata.c (ffffffff811c79e1)
Location: include/linux/bitmap.h:379
Inline: True
Inline callers:
  - kernel/padata.c:store_cpumask
```
```
In net/core/net-sysfs.c (ffffffff8186b60b)
Location: include/linux/bitmap.h:379
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:store_rps_map
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
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81048fdd)
Location: include/linux/bitmap.h:410
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
```
```
In kernel/workqueue.c (ffffffff810afbe3)
Location: include/linux/bitmap.h:410
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
```
```
In kernel/padata.c (ffffffff811e7c21)
Location: include/linux/bitmap.h:410
Inline: True
Inline callers:
  - kernel/padata.c:store_cpumask
```
```
In net/core/net-sysfs.c (ffffffff818bbd7b)
Location: include/linux/bitmap.h:410
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:store_rps_map
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81058fbf)
Location: include/linux/bitmap.h:411
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In kernel/workqueue.c (ffffffff810b8d53)
Location: include/linux/bitmap.h:411
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
```
```
In kernel/padata.c (ffffffff811f8b71)
Location: include/linux/bitmap.h:411
Inline: True
Inline callers:
  - kernel/padata.c:store_cpumask
```
```
In net/core/net-sysfs.c (ffffffff818e454a)
Location: include/linux/bitmap.h:411
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:store_rps_map
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105c568)
Location: include/linux/bitmap.h:411
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In kernel/workqueue.c (ffffffff810be85c)
Location: include/linux/bitmap.h:411
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
```
```
In kernel/padata.c (ffffffff81210631)
Location: include/linux/bitmap.h:411
Inline: True
Inline callers:
  - kernel/padata.c:store_cpumask
```
```
In net/core/net-sysfs.c (ffffffff819327bc)
Location: include/linux/bitmap.h:411
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:store_rps_map
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ce62)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In kernel/workqueue.c (ffffffff810c4e0c)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
```
```
In kernel/padata.c (ffffffff8121dd81)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - kernel/padata.c:store_cpumask
```
```
In net/core/net-sysfs.c (ffffffff819652fc)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:store_rps_map
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bitmap_parse(const char *start, unsigned int buflen, long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81584b60)
Location: lib/bitmap.c:737
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/padata.c:store_cpumask
  - lib/bitmap.c:bitmap_parse_user
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff81584b60-ffffffff81584ce6: bitmap_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bitmap_parse(const char *start, unsigned int buflen, long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815a1c60)
Location: lib/bitmap.c:737
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/padata.c:store_cpumask
  - lib/bitmap.c:bitmap_parse_user
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff815a1c60-ffffffff815a1de6: bitmap_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bitmap_parse(const char *start, unsigned int buflen, long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815a8a70)
Location: lib/bitmap.c:748
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/padata.c:store_cpumask
  - lib/bitmap.c:bitmap_parse_user
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff815a8a70-ffffffff815a8bff: bitmap_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bitmap_parse(const char *start, unsigned int buflen, long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81611d10)
Location: lib/bitmap.c:878
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/padata.c:store_cpumask
  - lib/bitmap.c:bitmap_parse_user
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff81611d10-ffffffff81611e9f: bitmap_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bitmap_parse(const char *start, unsigned int buflen, long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff816ddfb0)
Location: lib/bitmap.c:895
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/padata.c:store_cpumask
  - lib/bitmap.c:bitmap_parse_user
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff816ddfb0-ffffffff816de16e: bitmap_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bitmap_parse(const char *start, unsigned int buflen, long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff817cdf90)
Location: lib/bitmap.c:906
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/padata.c:store_cpumask
  - lib/bitmap.c:bitmap_parse_user
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff817cdf90-ffffffff817ce130: bitmap_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bitmap_parse(const char *start, unsigned int buflen, long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8180c440)
Location: lib/bitmap.c:906
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/padata.c:store_cpumask
  - lib/bitmap.c:bitmap_parse_user
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:rps_default_mask_sysctl
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff8180c440-ffffffff8180c5db: bitmap_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bitmap_parse(const char *start, unsigned int buflen, long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap-str.c (ffffffff818615e0)
Location: lib/bitmap-str.c:473
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/padata.c:store_cpumask
  - lib/bitmap-str.c:bitmap_parse_user
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:rps_default_mask_sysctl
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff818615e0-ffffffff8186177b: bitmap_parse (STB_GLOBAL)
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
In kernel/workqueue.c (ffff8000101232e4)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
```
```
In kernel/padata.c (ffff8000102a95cc)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - kernel/padata.c:store_cpumask
```
```
In net/core/net-sysfs.c (ffff800010c09c48)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:store_rps_map
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
In kernel/workqueue.c (c0376bec)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
```
```
In kernel/padata.c (c04d8880)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - kernel/padata.c:store_cpumask
```
```
In net/core/net-sysfs.c (c0d22bb0)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:store_rps_map
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
In kernel/workqueue.c (c00000000016d1ec)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
```
```
In kernel/padata.c (c00000000035daa8)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - kernel/padata.c:store_cpumask
```
```
In net/core/net-sysfs.c (c000000000cf4e68)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:store_rps_map
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
In kernel/workqueue.c (ffffffe0000dbad2)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
```
```
In kernel/padata.c (ffffffe0001d2aee)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - kernel/padata.c:store_cpumask
```
```
In net/core/net-sysfs.c (ffffffe000788276)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:store_rps_map
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105c9e2)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In kernel/workqueue.c (ffffffff810bf17c)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
```
```
In kernel/padata.c (ffffffff812163d1)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - kernel/padata.c:store_cpumask
```
```
In net/core/net-sysfs.c (ffffffff819052cc)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:store_rps_map
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104cbb2)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In kernel/workqueue.c (ffffffff810ad99c)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
```
```
In kernel/padata.c (ffffffff81209131)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - kernel/padata.c:store_cpumask
```
```
In net/core/net-sysfs.c (ffffffff818bf0fc)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:store_rps_map
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ce12)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In kernel/workqueue.c (ffffffff810be6dc)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
```
```
In kernel/padata.c (ffffffff81214171)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - kernel/padata.c:store_cpumask
```
```
In net/core/net-sysfs.c (ffffffff819562fc)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:store_rps_map
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105e332)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In kernel/workqueue.c (ffffffff810c6a4c)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
```
```
In kernel/padata.c (ffffffff812233b1)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - kernel/padata.c:store_cpumask
```
```
In net/core/net-sysfs.c (ffffffff819784fc)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:store_rps_map
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
