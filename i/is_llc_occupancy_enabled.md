# Function: <code>is_llc_occupancy_enabled</code>

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
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff810416a3)
Location: arch/x86/kernel/cpu/intel_rdt.h:265
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu
```
```
In arch/x86/kernel/cpu/intel_rdt_monitor.c (ffffffff81044863)
Location: arch/x86/kernel/cpu/intel_rdt.h:265
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:rdt_get_mon_l3_config
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
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff81044b0a)
Location: arch/x86/kernel/cpu/intel_rdt.h:269
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu
```
```
In arch/x86/kernel/cpu/intel_rdt_monitor.c (ffffffff81048034)
Location: arch/x86/kernel/cpu/intel_rdt.h:269
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:rdt_get_mon_l3_config
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
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff810468fe)
Location: arch/x86/kernel/cpu/intel_rdt.h:287
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu
```
```
In arch/x86/kernel/cpu/intel_rdt_monitor.c (ffffffff8104a8ce)
Location: arch/x86/kernel/cpu/intel_rdt.h:287
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:free_rmid
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105588f)
Location: arch/x86/kernel/cpu/resctrl/internal.h:366
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105ac4e)
Location: arch/x86/kernel/cpu/resctrl/internal.h:366
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81058ae2)
Location: arch/x86/kernel/cpu/resctrl/internal.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105df62)
Location: arch/x86/kernel/cpu/resctrl/internal.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810593b2)
Location: arch/x86/kernel/cpu/resctrl/internal.h:383
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105e81e)
Location: arch/x86/kernel/cpu/resctrl/internal.h:383
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105e604)
Location: arch/x86/kernel/cpu/resctrl/internal.h:391
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_setup_mon_state
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff810642c9)
Location: arch/x86/kernel/cpu/resctrl/internal.h:391
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105cb31)
Location: arch/x86/kernel/cpu/resctrl/internal.h:412
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_setup_mon_state
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff810626c9)
Location: arch/x86/kernel/cpu/resctrl/internal.h:412
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105d490)
Location: arch/x86/kernel/cpu/resctrl/internal.h:412
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81062e29)
Location: arch/x86/kernel/cpu/resctrl/internal.h:412
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81066b9c)
Location: arch/x86/kernel/cpu/resctrl/internal.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8106ccad)
Location: arch/x86/kernel/cpu/resctrl/internal.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810738dd)
Location: arch/x86/kernel/cpu/resctrl/internal.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8107a189)
Location: arch/x86/kernel/cpu/resctrl/internal.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81083caa)
Location: arch/x86/kernel/cpu/resctrl/internal.h:330
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81089ff5)
Location: arch/x86/kernel/cpu/resctrl/internal.h:330
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_offline_domain
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8108b2b6)
Location: arch/x86/kernel/cpu/resctrl/internal.h:330
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8108624a)
Location: arch/x86/kernel/cpu/resctrl/internal.h:355
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108d081)
Location: arch/x86/kernel/cpu/resctrl/internal.h:355
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_offline_domain
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff836a74ff)
Location: arch/x86/kernel/cpu/resctrl/internal.h:355
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8108d12a)
Location: arch/x86/kernel/cpu/resctrl/internal.h:355
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81094411)
Location: arch/x86/kernel/cpu/resctrl/internal.h:355
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_offline_domain
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff838d7a3f)
Location: arch/x86/kernel/cpu/resctrl/internal.h:355
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81058f32)
Location: arch/x86/kernel/cpu/resctrl/internal.h:383
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105e39e)
Location: arch/x86/kernel/cpu/resctrl/internal.h:383
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81049132)
Location: arch/x86/kernel/cpu/resctrl/internal.h:383
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8104e6ce)
Location: arch/x86/kernel/cpu/resctrl/internal.h:383
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81059362)
Location: arch/x86/kernel/cpu/resctrl/internal.h:383
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105e7ce)
Location: arch/x86/kernel/cpu/resctrl/internal.h:383
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105a802)
Location: arch/x86/kernel/cpu/resctrl/internal.h:383
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105fd0e)
Location: arch/x86/kernel/cpu/resctrl/internal.h:383
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
```
</details>
</li>
</ul>

## Differences
