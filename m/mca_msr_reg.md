# Function: <code>mca_msr_reg</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81068763)
Location: arch/x86/kernel/cpu/mce/internal.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:vendor_disable_error_reporting
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:msr_to_offset
  - arch/x86/kernel/cpu/mce/core.c:msr_to_offset
  - arch/x86/kernel/cpu/mce/core.c:msr_to_offset
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8106c092)
Location: arch/x86/kernel/cpu/mce/internal.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff81077e99)
Location: arch/x86/kernel/cpu/mce/internal.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_reenable_cpu
  - arch/x86/kernel/cpu/mce/core.c:vendor_disable_error_reporting
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:msr_to_offset
  - arch/x86/kernel/cpu/mce/core.c:msr_to_offset
  - arch/x86/kernel/cpu/mce/core.c:msr_to_offset
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8107c0ac)
Location: arch/x86/kernel/cpu/mce/internal.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - arch/x86/kernel/cpu/mce/amd.c:_log_error_deferred
  - arch/x86/kernel/cpu/mce/amd.c:_log_error_deferred
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff8107a149)
Location: arch/x86/kernel/cpu/mce/internal.h:259
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_reenable_cpu
  - arch/x86/kernel/cpu/mce/core.c:vendor_disable_error_reporting
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:msr_to_offset
  - arch/x86/kernel/cpu/mce/core.c:msr_to_offset
  - arch/x86/kernel/cpu/mce/core.c:msr_to_offset
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8107e389)
Location: arch/x86/kernel/cpu/mce/internal.h:259
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - arch/x86/kernel/cpu/mce/amd.c:_log_error_deferred
  - arch/x86/kernel/cpu/mce/amd.c:_log_error_deferred
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff810819c9)
Location: arch/x86/kernel/cpu/mce/internal.h:315
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_reenable_cpu
  - arch/x86/kernel/cpu/mce/core.c:vendor_disable_error_reporting
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:msr_to_offset
  - arch/x86/kernel/cpu/mce/core.c:msr_to_offset
  - arch/x86/kernel/cpu/mce/core.c:msr_to_offset
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81085898)
Location: arch/x86/kernel/cpu/mce/internal.h:315
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - arch/x86/kernel/cpu/mce/amd.c:_log_error_deferred
  - arch/x86/kernel/cpu/mce/amd.c:_log_error_deferred
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
