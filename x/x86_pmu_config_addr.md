# Function: <code>x86_pmu_config_addr</code>

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
In arch/x86/events/core.c (ffffffff81005d31)
Location: arch/x86/events/perf_event.h:703
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_disable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
  - arch/x86/events/core.c:x86_pmu_enable
  - arch/x86/events/core.c:perf_event_print_debug
```
```
In arch/x86/events/intel/core.c (ffffffff8100abe6)
Location: arch/x86/events/perf_event.h:703
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:core_guest_get_msrs
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
```
In arch/x86/events/intel/p4.c (ffffffff81f5f7c7)
Location: arch/x86/events/perf_event.h:703
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_init
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
In arch/x86/events/core.c (ffffffff810072aa)
Location: arch/x86/events/perf_event.h:712
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:x86_pmu_enable
  - arch/x86/events/core.c:x86_pmu_disable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
```
```
In arch/x86/events/intel/core.c (ffffffff8100ad75)
Location: arch/x86/events/perf_event.h:712
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:core_guest_get_msrs
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
```
In arch/x86/events/intel/p4.c (ffffffff81f8774d)
Location: arch/x86/events/perf_event.h:712
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_init
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
In arch/x86/events/core.c (ffffffff810072aa)
Location: arch/x86/events/perf_event.h:715
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:x86_pmu_enable
  - arch/x86/events/core.c:x86_pmu_disable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
```
```
In arch/x86/events/intel/core.c (ffffffff8100adb5)
Location: arch/x86/events/perf_event.h:715
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:core_guest_get_msrs
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
```
In arch/x86/events/intel/p4.c (ffffffff81fc2bc5)
Location: arch/x86/events/perf_event.h:715
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_init
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
In arch/x86/events/core.c (ffffffff81006fbb)
Location: arch/x86/events/perf_event.h:720
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:x86_pmu_enable
  - arch/x86/events/core.c:x86_pmu_disable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
```
```
In arch/x86/events/intel/core.c (ffffffff8100ab98)
Location: arch/x86/events/perf_event.h:720
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:core_guest_get_msrs
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
```
In arch/x86/events/intel/p4.c (ffffffff820a2e3e)
Location: arch/x86/events/perf_event.h:720
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_init
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
In arch/x86/events/core.c (ffffffff810073e2)
Location: arch/x86/events/perf_event.h:728
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:x86_pmu_enable
  - arch/x86/events/core.c:x86_pmu_disable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
```
```
In arch/x86/events/intel/core.c (ffffffff8100b088)
Location: arch/x86/events/perf_event.h:728
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:core_guest_get_msrs
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
```
In arch/x86/events/intel/p4.c (ffffffff826a9132)
Location: arch/x86/events/perf_event.h:728
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_init
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
In arch/x86/events/core.c (ffffffff826cf80c)
Location: arch/x86/events/perf_event.h:731
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:x86_pmu_enable
  - arch/x86/events/core.c:x86_pmu_disable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
```
```
In arch/x86/events/intel/core.c (ffffffff8100b531)
Location: arch/x86/events/perf_event.h:731
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:core_guest_get_msrs
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
```
In arch/x86/events/intel/p4.c (ffffffff826d22b4)
Location: arch/x86/events/perf_event.h:731
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_init
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
In arch/x86/events/core.c (ffffffff82885866)
Location: arch/x86/events/perf_event.h:749
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:x86_pmu_enable
  - arch/x86/events/core.c:x86_pmu_disable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
```
```
In arch/x86/events/intel/core.c (ffffffff8100b4e1)
Location: arch/x86/events/perf_event.h:749
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:core_guest_get_msrs
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/p4.c (ffffffff828885c4)
Location: arch/x86/events/perf_event.h:749
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_init
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
In arch/x86/events/core.c (ffffffff8289c85e)
Location: arch/x86/events/perf_event.h:786
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:x86_pmu_enable
  - arch/x86/events/core.c:x86_pmu_disable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
```
```
In arch/x86/events/intel/core.c (ffffffff8100baf1)
Location: arch/x86/events/perf_event.h:786
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:core_guest_get_msrs
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/p4.c (ffffffff8289f735)
Location: arch/x86/events/perf_event.h:786
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_init
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
In arch/x86/events/core.c (ffffffff8289f84e)
Location: arch/x86/events/perf_event.h:802
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_pmu_enable
  - arch/x86/events/core.c:x86_pmu_enable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
```
```
In arch/x86/events/amd/core.c (ffffffff81008fa2)
Location: arch/x86/events/perf_event.h:802
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
```
```
In arch/x86/events/intel/core.c (ffffffff8100d86c)
Location: arch/x86/events/perf_event.h:802
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:core_guest_get_msrs
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
```
```
In arch/x86/events/intel/p4.c (ffffffff828a2807)
Location: arch/x86/events/perf_event.h:802
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int x86_pmu_config_addr(int index);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81008d97)
Location: arch/x86/events/perf_event.h:811
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_pmu_enable
  - arch/x86/events/core.c:x86_pmu_enable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
  - arch/x86/events/core.c:reserve_pmc_hardware
  - arch/x86/events/core.c:reserve_pmc_hardware
Direct callers:
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:check_hw_exists
```
```
In arch/x86/events/amd/core.c (ffffffff8100a6b0)
Location: arch/x86/events/perf_event.h:811
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
```
```
In arch/x86/events/intel/core.c (ffffffff8100e4c8)
Location: arch/x86/events/perf_event.h:811
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:core_guest_get_msrs
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_workaround
```
```
In arch/x86/events/intel/p4.c (ffffffff82cc8879)
Location: arch/x86/events/perf_event.h:811
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_init
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff8101fa2c)
Location: arch/x86/events/perf_event.h:811
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event
```
**Symbols:**

```
ffffffff81006550-ffffffff8100657c: x86_pmu_config_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int x86_pmu_config_addr(int index);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81007e4d)
Location: arch/x86/events/perf_event.h:942
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_pmu_enable
  - arch/x86/events/core.c:x86_pmu_enable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
  - arch/x86/events/core.c:reserve_pmc_hardware
  - arch/x86/events/core.c:reserve_pmc_hardware
Direct callers:
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:check_hw_exists
```
```
In arch/x86/events/amd/core.c (ffffffff81009536)
Location: arch/x86/events/perf_event.h:942
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
```
```
In arch/x86/events/intel/core.c (ffffffff8100d690)
Location: arch/x86/events/perf_event.h:942
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:core_guest_get_msrs
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_workaround
```
```
In arch/x86/events/intel/p4.c (ffffffff82fb4690)
Location: arch/x86/events/perf_event.h:942
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_init
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff810204d2)
Location: arch/x86/events/perf_event.h:942
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event
```
**Symbols:**

```
ffffffff810056c0-ffffffff810056ec: x86_pmu_config_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int x86_pmu_config_addr(int index);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff8100861d)
Location: arch/x86/events/perf_event.h:1062
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_pmu_enable
  - arch/x86/events/core.c:x86_pmu_enable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
  - arch/x86/events/core.c:check_hw_exists
Direct callers:
  - arch/x86/events/core.c:perf_event_print_debug
```
```
In arch/x86/events/amd/core.c (ffffffff81009f01)
Location: arch/x86/events/perf_event.h:1062
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
```
```
In arch/x86/events/intel/core.c (ffffffff8100e422)
Location: arch/x86/events/perf_event.h:1062
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:core_guest_get_msrs
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
```
```
In arch/x86/events/intel/p4.c (ffffffff831bec04)
Location: arch/x86/events/perf_event.h:1062
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_init
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff81022862)
Location: arch/x86/events/perf_event.h:1062
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event
```
**Symbols:**

```
ffffffff81bc3be1-ffffffff81bc3c09: x86_pmu_config_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int x86_pmu_config_addr(int index);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff8100940d)
Location: arch/x86/events/perf_event.h:1062
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_pmu_enable
  - arch/x86/events/core.c:x86_pmu_enable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
  - arch/x86/events/core.c:check_hw_exists
Direct callers:
  - arch/x86/events/core.c:perf_event_print_debug
```
```
In arch/x86/events/amd/core.c (ffffffff8100b011)
Location: arch/x86/events/perf_event.h:1062
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
```
```
In arch/x86/events/intel/core.c (ffffffff8100ebe6)
Location: arch/x86/events/perf_event.h:1062
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:core_guest_get_msrs
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
```
```
In arch/x86/events/intel/p4.c (ffffffff8329f070)
Location: arch/x86/events/perf_event.h:1062
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_init
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff810266e5)
Location: arch/x86/events/perf_event.h:1062
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event
```
**Symbols:**

```
ffffffff81c94c32-ffffffff81c94c5a: x86_pmu_config_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int x86_pmu_config_addr(int index);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81008a9f)
Location: arch/x86/events/perf_event.h:1083
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_pmu_enable
  - arch/x86/events/core.c:x86_pmu_enable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
  - arch/x86/events/core.c:check_hw_exists
Direct callers:
  - arch/x86/events/core.c:perf_event_print_debug
```
```
In arch/x86/events/amd/core.c (ffffffff8100b3b9)
Location: arch/x86/events/perf_event.h:1083
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_v2_enable_event
```
```
In arch/x86/events/intel/core.c (ffffffff8100ffa4)
Location: arch/x86/events/perf_event.h:1083
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:core_guest_get_msrs
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
```
```
In arch/x86/events/intel/p4.c (ffffffff8344de30)
Location: arch/x86/events/perf_event.h:1083
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_init
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff8102a7fd)
Location: arch/x86/events/perf_event.h:1083
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event
```
**Symbols:**

```
ffffffff81e43ee8-ffffffff81e43f1a: x86_pmu_config_addr (STB_LOCAL)
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
In arch/x86/events/core.c (ffffffff81009d6d)
Location: arch/x86/events/perf_event.h:1091
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_pmu_enable
  - arch/x86/events/core.c:x86_pmu_enable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
  - arch/x86/events/core.c:check_hw_exists
```
```
In arch/x86/events/amd/core.c (ffffffff8100cd89)
Location: arch/x86/events/perf_event.h:1091
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_v2_enable_event
```
```
In arch/x86/events/intel/core.c (ffffffff81013c44)
Location: arch/x86/events/perf_event.h:1091
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:core_guest_get_msrs
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
```
```
In arch/x86/events/intel/p4.c (ffffffff83e692e2)
Location: arch/x86/events/perf_event.h:1091
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_init
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff810313cd)
Location: arch/x86/events/perf_event.h:1091
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event
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
In arch/x86/events/core.c (ffffffff8100958b)
Location: arch/x86/events/perf_event.h:1096
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_pmu_enable
  - arch/x86/events/core.c:x86_pmu_enable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
  - arch/x86/events/core.c:check_hw_exists
```
```
In arch/x86/events/amd/core.c (ffffffff8100c549)
Location: arch/x86/events/perf_event.h:1096
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_v2_enable_event
```
```
In arch/x86/events/intel/core.c (ffffffff810134a2)
Location: arch/x86/events/perf_event.h:1096
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:core_guest_get_msrs
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
```
```
In arch/x86/events/intel/p4.c (ffffffff83689c72)
Location: arch/x86/events/perf_event.h:1096
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_init
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff810313dd)
Location: arch/x86/events/perf_event.h:1096
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event
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
In arch/x86/events/core.c (ffffffff8100ecab)
Location: arch/x86/events/perf_event.h:1111
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_pmu_enable
  - arch/x86/events/core.c:x86_pmu_enable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
  - arch/x86/events/core.c:check_hw_exists
```
```
In arch/x86/events/amd/core.c (ffffffff81011d29)
Location: arch/x86/events/perf_event.h:1111
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_v2_enable_event
```
```
In arch/x86/events/intel/core.c (ffffffff81018b32)
Location: arch/x86/events/perf_event.h:1111
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:core_guest_get_msrs
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
```
```
In arch/x86/events/intel/p4.c (ffffffff838b97d2)
Location: arch/x86/events/perf_event.h:1111
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_init
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff810376cd)
Location: arch/x86/events/perf_event.h:1111
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event
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
In arch/x86/events/core.c (ffffffff8288d84e)
Location: arch/x86/events/perf_event.h:802
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_pmu_enable
  - arch/x86/events/core.c:x86_pmu_enable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
```
```
In arch/x86/events/amd/core.c (ffffffff81008fa2)
Location: arch/x86/events/perf_event.h:802
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
```
```
In arch/x86/events/intel/core.c (ffffffff8100d86c)
Location: arch/x86/events/perf_event.h:802
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:core_guest_get_msrs
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
```
```
In arch/x86/events/intel/p4.c (ffffffff82890807)
Location: arch/x86/events/perf_event.h:802
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_init
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
In arch/x86/events/core.c (ffffffff8288b775)
Location: arch/x86/events/perf_event.h:802
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_pmu_enable
  - arch/x86/events/core.c:x86_pmu_enable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
```
```
In arch/x86/events/amd/core.c (ffffffff81007d14)
Location: arch/x86/events/perf_event.h:802
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
```
```
In arch/x86/events/intel/core.c (ffffffff8100bfec)
Location: arch/x86/events/perf_event.h:802
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:core_guest_get_msrs
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
```
```
In arch/x86/events/intel/p4.c (ffffffff8288e71f)
Location: arch/x86/events/perf_event.h:802
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_init
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
In arch/x86/events/core.c (ffffffff828a084e)
Location: arch/x86/events/perf_event.h:802
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_pmu_enable
  - arch/x86/events/core.c:x86_pmu_enable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
```
```
In arch/x86/events/amd/core.c (ffffffff81008f62)
Location: arch/x86/events/perf_event.h:802
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
```
```
In arch/x86/events/intel/core.c (ffffffff8100d82c)
Location: arch/x86/events/perf_event.h:802
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:core_guest_get_msrs
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
```
```
In arch/x86/events/intel/p4.c (ffffffff828a3807)
Location: arch/x86/events/perf_event.h:802
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_init
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
In arch/x86/events/core.c (ffffffff828a0853)
Location: arch/x86/events/perf_event.h:802
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_pmu_enable
  - arch/x86/events/core.c:x86_pmu_enable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
```
```
In arch/x86/events/amd/core.c (ffffffff810090c2)
Location: arch/x86/events/perf_event.h:802
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
```
```
In arch/x86/events/intel/core.c (ffffffff8100d9fc)
Location: arch/x86/events/perf_event.h:802
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:core_guest_get_msrs
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
```
```
In arch/x86/events/intel/p4.c (ffffffff828a381b)
Location: arch/x86/events/perf_event.h:802
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_init
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
