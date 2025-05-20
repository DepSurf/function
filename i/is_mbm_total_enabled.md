# Function: <code>is_mbm_total_enabled</code>

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
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff810412ff)
Location: arch/x86/kernel/cpu/intel_rdt.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (0)
Location: arch/x86/kernel/cpu/intel_rdt.h:270
Inline: True
```
```
In arch/x86/kernel/cpu/intel_rdt_monitor.c (ffffffff810441f7)
Location: arch/x86/kernel/cpu/intel_rdt.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_update
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
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff810446bf)
Location: arch/x86/kernel/cpu/intel_rdt.h:274
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (0)
Location: arch/x86/kernel/cpu/intel_rdt.h:274
Inline: True
```
```
In arch/x86/kernel/cpu/intel_rdt_monitor.c (ffffffff810479c7)
Location: arch/x86/kernel/cpu/intel_rdt.h:274
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_update
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
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff810468e7)
Location: arch/x86/kernel/cpu/intel_rdt.h:292
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff8104884a)
Location: arch/x86/kernel/cpu/intel_rdt.h:292
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:set_mba_sc
```
```
In arch/x86/kernel/cpu/intel_rdt_monitor.c (ffffffff8104a8d3)
Location: arch/x86/kernel/cpu/intel_rdt.h:292
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_update
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81055878)
Location: arch/x86/kernel/cpu/resctrl/internal.h:371
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810577c1)
Location: arch/x86/kernel/cpu/resctrl/internal.h:371
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105ac53)
Location: arch/x86/kernel/cpu/resctrl/internal.h:371
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81058aca)
Location: arch/x86/kernel/cpu/resctrl/internal.h:387
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105aa7b)
Location: arch/x86/kernel/cpu/resctrl/internal.h:387
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105df67)
Location: arch/x86/kernel/cpu/resctrl/internal.h:387
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105939a)
Location: arch/x86/kernel/cpu/resctrl/internal.h:388
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b152)
Location: arch/x86/kernel/cpu/resctrl/internal.h:388
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105e823)
Location: arch/x86/kernel/cpu/resctrl/internal.h:388
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105e5ee)
Location: arch/x86/kernel/cpu/resctrl/internal.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_setup_mon_state
  - arch/x86/kernel/cpu/resctrl/core.c:domain_setup_mon_state
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810612f4)
Location: arch/x86/kernel/cpu/resctrl/internal.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff810642f2)
Location: arch/x86/kernel/cpu/resctrl/internal.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105cb1b)
Location: arch/x86/kernel/cpu/resctrl/internal.h:417
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_setup_mon_state
  - arch/x86/kernel/cpu/resctrl/core.c:domain_setup_mon_state
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105f6c1)
Location: arch/x86/kernel/cpu/resctrl/internal.h:417
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff810626f2)
Location: arch/x86/kernel/cpu/resctrl/internal.h:417
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105d47a)
Location: arch/x86/kernel/cpu/resctrl/internal.h:417
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ffd1)
Location: arch/x86/kernel/cpu/resctrl/internal.h:417
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81062e52)
Location: arch/x86/kernel/cpu/resctrl/internal.h:417
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81066b86)
Location: arch/x86/kernel/cpu/resctrl/internal.h:344
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8106a498)
Location: arch/x86/kernel/cpu/resctrl/internal.h:344
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8106ccd0)
Location: arch/x86/kernel/cpu/resctrl/internal.h:344
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810738c7)
Location: arch/x86/kernel/cpu/resctrl/internal.h:344
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810776d4)
Location: arch/x86/kernel/cpu/resctrl/internal.h:344
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8107a1ac)
Location: arch/x86/kernel/cpu/resctrl/internal.h:344
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81083c92)
Location: arch/x86/kernel/cpu/resctrl/internal.h:335
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108a003)
Location: arch/x86/kernel/cpu/resctrl/internal.h:335
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_offline_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8108b2d9)
Location: arch/x86/kernel/cpu/resctrl/internal.h:335
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81086232)
Location: arch/x86/kernel/cpu/resctrl/internal.h:360
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108d08f)
Location: arch/x86/kernel/cpu/resctrl/internal.h:360
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_offline_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff836a7522)
Location: arch/x86/kernel/cpu/resctrl/internal.h:360
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/resctrl/monitor.c:resctrl_arch_reset_rmid_all
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8108d112)
Location: arch/x86/kernel/cpu/resctrl/internal.h:360
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8109441f)
Location: arch/x86/kernel/cpu/resctrl/internal.h:360
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_offline_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff838d7a62)
Location: arch/x86/kernel/cpu/resctrl/internal.h:360
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/resctrl/monitor.c:resctrl_arch_reset_rmid_all
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81058f1a)
Location: arch/x86/kernel/cpu/resctrl/internal.h:388
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105acd2)
Location: arch/x86/kernel/cpu/resctrl/internal.h:388
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105e3a3)
Location: arch/x86/kernel/cpu/resctrl/internal.h:388
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8104911a)
Location: arch/x86/kernel/cpu/resctrl/internal.h:388
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104ad52)
Location: arch/x86/kernel/cpu/resctrl/internal.h:388
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8104e6d3)
Location: arch/x86/kernel/cpu/resctrl/internal.h:388
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105934a)
Location: arch/x86/kernel/cpu/resctrl/internal.h:388
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b102)
Location: arch/x86/kernel/cpu/resctrl/internal.h:388
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105e7d3)
Location: arch/x86/kernel/cpu/resctrl/internal.h:388
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105a7ea)
Location: arch/x86/kernel/cpu/resctrl/internal.h:388
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105c5c2)
Location: arch/x86/kernel/cpu/resctrl/internal.h:388
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105fd13)
Location: arch/x86/kernel/cpu/resctrl/internal.h:388
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update
```
</details>
</li>
</ul>

## Differences
