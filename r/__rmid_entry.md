# Function: <code>__rmid_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/cqm.c (ffffffff8100e548)
Location: arch/x86/events/intel/cqm.c:210
Inline: True
Inline callers:
  - arch/x86/events/intel/cqm.c:__put_rmid
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/cqm.c (ffffffff8100e248)
Location: arch/x86/events/intel/cqm.c:210
Inline: True
Inline callers:
  - arch/x86/events/intel/cqm.c:__put_rmid
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/cqm.c (ffffffff8100e308)
Location: arch/x86/events/intel/cqm.c:191
Inline: True
Inline callers:
  - arch/x86/events/intel/cqm.c:__put_rmid
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_monitor.c (ffffffff81044840)
Location: arch/x86/kernel/cpu/intel_rdt_monitor.c:78
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:free_rmid
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:__check_limbo
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_monitor.c (ffffffff81048011)
Location: arch/x86/kernel/cpu/intel_rdt_monitor.c:78
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:free_rmid
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:__check_limbo
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_monitor.c (ffffffff8104a87e)
Location: arch/x86/kernel/cpu/intel_rdt_monitor.c:78
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:free_rmid
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:__check_limbo
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105abfe)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:75
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105df12)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:67
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
```
**Symbols:**

```
ffffffff8105e01f-ffffffff8105e033: __rmid_entry.part.0 (STB_LOCAL)
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
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105e7ce)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:67
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81063f0a)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:67
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8106233a)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:130
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
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
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81062bfa)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:130
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
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
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8106ca89)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:130
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
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
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81079f19)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:130
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8108aff9)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:139
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8108e099)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:139
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81095429)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:139
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105e34e)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:67
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
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
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8104e67e)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:67
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
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
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105e77e)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:67
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
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
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105fcbe)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:67
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
```
</details>
</li>
</ul>

## Differences
