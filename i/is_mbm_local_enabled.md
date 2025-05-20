# Function: <code>is_mbm_local_enabled</code>

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
In arch/x86/kernel/cpu/intel_rdt.c (0)
Location: arch/x86/kernel/cpu/intel_rdt.h:275
Inline: True
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (0)
Location: arch/x86/kernel/cpu/intel_rdt.h:275
Inline: True
```
```
In arch/x86/kernel/cpu/intel_rdt_monitor.c (0)
Location: arch/x86/kernel/cpu/intel_rdt.h:275
Inline: True
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
In arch/x86/kernel/cpu/intel_rdt.c (0)
Location: arch/x86/kernel/cpu/intel_rdt.h:279
Inline: True
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (0)
Location: arch/x86/kernel/cpu/intel_rdt.h:279
Inline: True
```
```
In arch/x86/kernel/cpu/intel_rdt_monitor.c (0)
Location: arch/x86/kernel/cpu/intel_rdt.h:279
Inline: True
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
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff81046e30)
Location: arch/x86/kernel/cpu/intel_rdt.h:297
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (0)
Location: arch/x86/kernel/cpu/intel_rdt.h:297
Inline: True
```
```
In arch/x86/kernel/cpu/intel_rdt_monitor.c (ffffffff8104a904)
Location: arch/x86/kernel/cpu/intel_rdt.h:297
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81055e49)
Location: arch/x86/kernel/cpu/resctrl/internal.h:376
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/internal.h:376
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105ac84)
Location: arch/x86/kernel/cpu/resctrl/internal.h:376
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81059078)
Location: arch/x86/kernel/cpu/resctrl/internal.h:392
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/internal.h:392
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105df99)
Location: arch/x86/kernel/cpu/resctrl/internal.h:392
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81059948)
Location: arch/x86/kernel/cpu/resctrl/internal.h:393
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/internal.h:393
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105e855)
Location: arch/x86/kernel/cpu/resctrl/internal.h:393
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105e9c4)
Location: arch/x86/kernel/cpu/resctrl/internal.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_setup_mon_state
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/internal.h:401
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81064324)
Location: arch/x86/kernel/cpu/resctrl/internal.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/resctrl/monitor.c:update_mba_bw
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105cee4)
Location: arch/x86/kernel/cpu/resctrl/internal.h:422
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_setup_mon_state
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/internal.h:422
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81062724)
Location: arch/x86/kernel/cpu/resctrl/internal.h:422
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/resctrl/monitor.c:update_mba_bw
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105d9aa)
Location: arch/x86/kernel/cpu/resctrl/internal.h:422
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/internal.h:422
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81062e84)
Location: arch/x86/kernel/cpu/resctrl/internal.h:422
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/resctrl/monitor.c:update_mba_bw
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810670ac)
Location: arch/x86/kernel/cpu/resctrl/internal.h:349
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/internal.h:349
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8106ccfc)
Location: arch/x86/kernel/cpu/resctrl/internal.h:349
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/resctrl/monitor.c:update_mba_bw
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81073dd3)
Location: arch/x86/kernel/cpu/resctrl/internal.h:349
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/internal.h:349
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8107a1d2)
Location: arch/x86/kernel/cpu/resctrl/internal.h:349
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/resctrl/monitor.c:update_mba_bw
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8108409b)
Location: arch/x86/kernel/cpu/resctrl/internal.h:340
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81089f95)
Location: arch/x86/kernel/cpu/resctrl/internal.h:340
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_offline_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_parse_param
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8108b2ff)
Location: arch/x86/kernel/cpu/resctrl/internal.h:340
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/resctrl/monitor.c:update_mba_bw
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8108663b)
Location: arch/x86/kernel/cpu/resctrl/internal.h:365
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108d025)
Location: arch/x86/kernel/cpu/resctrl/internal.h:365
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_offline_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_parse_param
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff836a7548)
Location: arch/x86/kernel/cpu/resctrl/internal.h:365
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/resctrl/monitor.c:update_mba_bw
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8108d550)
Location: arch/x86/kernel/cpu/resctrl/internal.h:365
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810943b5)
Location: arch/x86/kernel/cpu/resctrl/internal.h:365
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_offline_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_parse_param
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff838d7a88)
Location: arch/x86/kernel/cpu/resctrl/internal.h:365
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/resctrl/monitor.c:update_mba_bw
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810594c8)
Location: arch/x86/kernel/cpu/resctrl/internal.h:393
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/internal.h:393
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105e3d5)
Location: arch/x86/kernel/cpu/resctrl/internal.h:393
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810496e8)
Location: arch/x86/kernel/cpu/resctrl/internal.h:393
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/internal.h:393
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8104e705)
Location: arch/x86/kernel/cpu/resctrl/internal.h:393
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810598f8)
Location: arch/x86/kernel/cpu/resctrl/internal.h:393
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/internal.h:393
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105e805)
Location: arch/x86/kernel/cpu/resctrl/internal.h:393
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105ad98)
Location: arch/x86/kernel/cpu/resctrl/internal.h:393
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/internal.h:393
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105fd45)
Location: arch/x86/kernel/cpu/resctrl/internal.h:393
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update
```
</details>
</li>
</ul>

## Differences
