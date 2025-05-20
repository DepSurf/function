# Function: <code>set_linear_ip</code>

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
In arch/x86/events/amd/ibs.c (ffffffff8100948c)
Location: arch/x86/events/perf_event.h:790
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/ds.c (ffffffff8100f731)
Location: arch/x86/events/perf_event.h:790
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:setup_pebs_sample_data
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
In arch/x86/events/amd/ibs.c (ffffffff81009a21)
Location: arch/x86/events/perf_event.h:799
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/ds.c (ffffffff8100f30e)
Location: arch/x86/events/perf_event.h:799
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_sample_data
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
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
In arch/x86/events/amd/ibs.c (ffffffff81009a61)
Location: arch/x86/events/perf_event.h:802
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/ds.c (ffffffff8100f3ce)
Location: arch/x86/events/perf_event.h:802
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_sample_data
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
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
In arch/x86/events/amd/ibs.c (ffffffff8100976c)
Location: arch/x86/events/perf_event.h:807
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/ds.c (ffffffff8100dae3)
Location: arch/x86/events/perf_event.h:807
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_sample_data
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
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
In arch/x86/events/amd/ibs.c (ffffffff81009dde)
Location: arch/x86/events/perf_event.h:817
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/ds.c (ffffffff8100e253)
Location: arch/x86/events/perf_event.h:817
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_sample_data
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
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
In arch/x86/events/amd/ibs.c (ffffffff8100a2c6)
Location: arch/x86/events/perf_event.h:820
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/ds.c (ffffffff8100ebb8)
Location: arch/x86/events/perf_event.h:820
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_sample_data
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
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
In arch/x86/events/amd/ibs.c (ffffffff8100a1f6)
Location: arch/x86/events/perf_event.h:838
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/ds.c (ffffffff8100f088)
Location: arch/x86/events/perf_event.h:838
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_sample_data
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
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
In arch/x86/events/amd/ibs.c (ffffffff8100a6e3)
Location: arch/x86/events/perf_event.h:875
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/ds.c (ffffffff8100f991)
Location: arch/x86/events/perf_event.h:875
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
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
In arch/x86/events/amd/ibs.c (ffffffff8100aca1)
Location: arch/x86/events/perf_event.h:907
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/ds.c (ffffffff81010071)
Location: arch/x86/events/perf_event.h:907
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
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
In arch/x86/events/amd/ibs.c (ffffffff8100beeb)
Location: arch/x86/events/perf_event.h:916
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/ds.c (ffffffff81011512)
Location: arch/x86/events/perf_event.h:916
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
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
In arch/x86/events/amd/ibs.c (ffffffff8100ae89)
Location: arch/x86/events/perf_event.h:1047
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/ds.c (ffffffff81010b42)
Location: arch/x86/events/perf_event.h:1047
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
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
In arch/x86/events/amd/ibs.c (ffffffff8100b824)
Location: arch/x86/events/perf_event.h:1176
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/ds.c (ffffffff81011b02)
Location: arch/x86/events/perf_event.h:1176
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
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
In arch/x86/events/amd/ibs.c (ffffffff8100bd2b)
Location: arch/x86/events/perf_event.h:1176
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/ds.c (ffffffff810129d2)
Location: arch/x86/events/perf_event.h:1176
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
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
In arch/x86/events/amd/ibs.c (ffffffff8100cada)
Location: arch/x86/events/perf_event.h:1202
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/ds.c (ffffffff810146c2)
Location: arch/x86/events/perf_event.h:1202
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
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
In arch/x86/events/amd/ibs.c (ffffffff8100fb26)
Location: arch/x86/events/perf_event.h:1208
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/ds.c (ffffffff8101889a)
Location: arch/x86/events/perf_event.h:1208
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
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
In arch/x86/events/amd/ibs.c (ffffffff8100f0b9)
Location: arch/x86/events/perf_event.h:1213
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/ds.c (ffffffff8101817b)
Location: arch/x86/events/perf_event.h:1213
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
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
In arch/x86/events/amd/ibs.c (ffffffff810147f9)
Location: arch/x86/events/perf_event.h:1228
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/ds.c (ffffffff8101dcfb)
Location: arch/x86/events/perf_event.h:1228
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
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
In arch/x86/events/amd/ibs.c (ffffffff8100aca1)
Location: arch/x86/events/perf_event.h:907
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/ds.c (ffffffff81010071)
Location: arch/x86/events/perf_event.h:907
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
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
In arch/x86/events/amd/ibs.c (ffffffff810095d9)
Location: arch/x86/events/perf_event.h:907
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/ds.c (ffffffff8100ee11)
Location: arch/x86/events/perf_event.h:907
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
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
In arch/x86/events/amd/ibs.c (ffffffff8100ac61)
Location: arch/x86/events/perf_event.h:907
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/ds.c (ffffffff81010031)
Location: arch/x86/events/perf_event.h:907
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
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
In arch/x86/events/amd/ibs.c (ffffffff8100abf1)
Location: arch/x86/events/perf_event.h:907
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/ds.c (ffffffff81010241)
Location: arch/x86/events/perf_event.h:907
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
```
</details>
</li>
</ul>

## Differences
