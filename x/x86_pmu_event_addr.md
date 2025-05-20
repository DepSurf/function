# Function: <code>x86_pmu_event_addr</code>

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
In arch/x86/events/core.c (ffffffff81005cbb)
Location: arch/x86/events/perf_event.h:709
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_enable
  - arch/x86/events/core.c:perf_event_print_debug
```
```
In arch/x86/events/intel/core.c (ffffffff8100c621)
Location: arch/x86/events/perf_event.h:709
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
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
In arch/x86/events/core.c (ffffffff810072d9)
Location: arch/x86/events/perf_event.h:718
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:x86_pmu_enable
```
```
In arch/x86/events/intel/core.c (ffffffff8100c897)
Location: arch/x86/events/perf_event.h:718
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
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
In arch/x86/events/core.c (ffffffff810072d9)
Location: arch/x86/events/perf_event.h:721
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:x86_pmu_enable
```
```
In arch/x86/events/intel/core.c (ffffffff8100c95f)
Location: arch/x86/events/perf_event.h:721
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
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
In arch/x86/events/core.c (ffffffff81006fea)
Location: arch/x86/events/perf_event.h:726
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:x86_pmu_enable
```
```
In arch/x86/events/intel/core.c (ffffffff8100c6a9)
Location: arch/x86/events/perf_event.h:726
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
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
In arch/x86/events/core.c (ffffffff81007414)
Location: arch/x86/events/perf_event.h:734
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:x86_pmu_enable
```
```
In arch/x86/events/intel/core.c (ffffffff8100cc5c)
Location: arch/x86/events/perf_event.h:734
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
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
In arch/x86/events/core.c (ffffffff826cf8e9)
Location: arch/x86/events/perf_event.h:737
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:x86_pmu_enable
```
```
In arch/x86/events/intel/core.c (ffffffff8100d366)
Location: arch/x86/events/perf_event.h:737
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
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
In arch/x86/events/core.c (ffffffff82885943)
Location: arch/x86/events/perf_event.h:755
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:x86_pmu_enable
```
```
In arch/x86/events/intel/core.c (ffffffff8100b616)
Location: arch/x86/events/perf_event.h:755
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
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
In arch/x86/events/core.c (ffffffff8289c936)
Location: arch/x86/events/perf_event.h:792
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:x86_pmu_enable
```
```
In arch/x86/events/amd/core.c (ffffffff81008c08)
Location: arch/x86/events/perf_event.h:792
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_wait_on_overflow
```
```
In arch/x86/events/intel/core.c (ffffffff8100bc26)
Location: arch/x86/events/perf_event.h:792
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
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
In arch/x86/events/core.c (ffffffff8289f926)
Location: arch/x86/events/perf_event.h:808
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_pmu_enable
```
```
In arch/x86/events/amd/core.c (ffffffff81008f28)
Location: arch/x86/events/perf_event.h:808
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_wait_on_overflow
```
```
In arch/x86/events/intel/core.c (ffffffff8100c036)
Location: arch/x86/events/perf_event.h:808
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int x86_pmu_event_addr(int index);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81008909)
Location: arch/x86/events/perf_event.h:817
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_pmu_enable
  - arch/x86/events/core.c:reserve_pmc_hardware
  - arch/x86/events/core.c:reserve_pmc_hardware
Direct callers:
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:check_hw_exists
```
```
In arch/x86/events/amd/core.c (ffffffff8100a068)
Location: arch/x86/events/perf_event.h:817
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_wait_on_overflow
```
```
In arch/x86/events/intel/core.c (ffffffff8100eff6)
Location: arch/x86/events/perf_event.h:817
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
**Symbols:**

```
ffffffff81006580-ffffffff810065a9: x86_pmu_event_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int x86_pmu_event_addr(int index);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff8100798b)
Location: arch/x86/events/perf_event.h:948
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_pmu_enable
  - arch/x86/events/core.c:reserve_pmc_hardware
  - arch/x86/events/core.c:reserve_pmc_hardware
Direct callers:
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:check_hw_exists
```
```
In arch/x86/events/amd/core.c (ffffffff81008ee8)
Location: arch/x86/events/perf_event.h:948
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_wait_on_overflow
```
```
In arch/x86/events/intel/core.c (ffffffff8100e366)
Location: arch/x86/events/perf_event.h:948
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
**Symbols:**

```
ffffffff810056f0-ffffffff81005719: x86_pmu_event_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int x86_pmu_event_addr(int index);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81008c9e)
Location: arch/x86/events/perf_event.h:1068
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_clear_dirty_counters
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_pmu_enable
  - arch/x86/events/core.c:check_hw_exists
Direct callers:
  - arch/x86/events/core.c:perf_event_print_debug
```
```
In arch/x86/events/amd/core.c (ffffffff81009888)
Location: arch/x86/events/perf_event.h:1068
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_wait_on_overflow
```
```
In arch/x86/events/intel/core.c (ffffffff8100f375)
Location: arch/x86/events/perf_event.h:1068
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
**Symbols:**

```
ffffffff81bc3c09-ffffffff81bc3c2e: x86_pmu_event_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int x86_pmu_event_addr(int index);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81009b1a)
Location: arch/x86/events/perf_event.h:1068
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_clear_dirty_counters
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_pmu_enable
  - arch/x86/events/core.c:check_hw_exists
Direct callers:
  - arch/x86/events/core.c:perf_event_print_debug
```
```
In arch/x86/events/amd/core.c (ffffffff8100a85c)
Location: arch/x86/events/perf_event.h:1068
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_wait_on_overflow
```
```
In arch/x86/events/intel/core.c (ffffffff8101013f)
Location: arch/x86/events/perf_event.h:1068
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
**Symbols:**

```
ffffffff81c94c5a-ffffffff81c94c7f: x86_pmu_event_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int x86_pmu_event_addr(int index);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81009247)
Location: arch/x86/events/perf_event.h:1089
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_clear_dirty_counters
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_pmu_enable
  - arch/x86/events/core.c:check_hw_exists
Direct callers:
  - arch/x86/events/core.c:perf_event_print_debug
```
```
In arch/x86/events/amd/core.c (ffffffff8100aa35)
Location: arch/x86/events/perf_event.h:1089
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_test_overflow_topbit
```
```
In arch/x86/events/intel/core.c (ffffffff81011756)
Location: arch/x86/events/perf_event.h:1089
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
**Symbols:**

```
ffffffff81e43f1a-ffffffff81e43f49: x86_pmu_event_addr (STB_LOCAL)
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
In arch/x86/events/core.c (ffffffff8100a699)
Location: arch/x86/events/perf_event.h:1097
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_clear_dirty_counters
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_pmu_enable
  - arch/x86/events/core.c:check_hw_exists
```
```
In arch/x86/events/amd/core.c (ffffffff8100c645)
Location: arch/x86/events/perf_event.h:1097
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_test_overflow_topbit
```
```
In arch/x86/events/intel/core.c (ffffffff8101516e)
Location: arch/x86/events/perf_event.h:1097
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
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
In arch/x86/events/core.c (ffffffff81009ee9)
Location: arch/x86/events/perf_event.h:1102
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_clear_dirty_counters
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_pmu_enable
  - arch/x86/events/core.c:check_hw_exists
```
```
In arch/x86/events/amd/core.c (ffffffff8100be05)
Location: arch/x86/events/perf_event.h:1102
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_test_overflow_topbit
```
```
In arch/x86/events/intel/core.c (ffffffff810149d1)
Location: arch/x86/events/perf_event.h:1102
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
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
In arch/x86/events/core.c (ffffffff8100f609)
Location: arch/x86/events/perf_event.h:1117
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_clear_dirty_counters
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_pmu_enable
  - arch/x86/events/core.c:check_hw_exists
```
```
In arch/x86/events/amd/core.c (ffffffff810115e5)
Location: arch/x86/events/perf_event.h:1117
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_test_overflow_topbit
```
```
In arch/x86/events/intel/core.c (ffffffff810199c1)
Location: arch/x86/events/perf_event.h:1117
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
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
In arch/x86/events/core.c (ffffffff8288d926)
Location: arch/x86/events/perf_event.h:808
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_pmu_enable
```
```
In arch/x86/events/amd/core.c (ffffffff81008f28)
Location: arch/x86/events/perf_event.h:808
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_wait_on_overflow
```
```
In arch/x86/events/intel/core.c (ffffffff8100c036)
Location: arch/x86/events/perf_event.h:808
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
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
In arch/x86/events/core.c (ffffffff8288b849)
Location: arch/x86/events/perf_event.h:808
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_pmu_enable
```
```
In arch/x86/events/amd/core.c (ffffffff81007739)
Location: arch/x86/events/perf_event.h:808
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_wait_on_overflow
```
```
In arch/x86/events/intel/core.c (ffffffff8100cd8c)
Location: arch/x86/events/perf_event.h:808
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
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
In arch/x86/events/core.c (ffffffff828a0926)
Location: arch/x86/events/perf_event.h:808
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_pmu_enable
```
```
In arch/x86/events/amd/core.c (ffffffff81008ee8)
Location: arch/x86/events/perf_event.h:808
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_wait_on_overflow
```
```
In arch/x86/events/intel/core.c (ffffffff8100bff6)
Location: arch/x86/events/perf_event.h:808
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
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
In arch/x86/events/core.c (ffffffff828a092b)
Location: arch/x86/events/perf_event.h:808
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_pmu_enable
```
```
In arch/x86/events/amd/core.c (ffffffff81009048)
Location: arch/x86/events/perf_event.h:808
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_wait_on_overflow
```
```
In arch/x86/events/intel/core.c (ffffffff8100c226)
Location: arch/x86/events/perf_event.h:808
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
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
