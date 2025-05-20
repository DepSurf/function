# Function: <code>perf_clear_branch_entry_bitfields</code>

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
In arch/x86/events/amd/brs.c (ffffffff8100b839)
Location: include/linux/perf_event.h:1071
Inline: True
Inline callers:
  - arch/x86/events/amd/brs.c:amd_brs_drain
```
```
In arch/x86/events/intel/lbr.c (ffffffff81018712)
Location: include/linux/perf_event.h:1071
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_store_lbr
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_32
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
In arch/x86/events/amd/lbr.c (ffffffff8100d5aa)
Location: include/linux/perf_event.h:1169
Inline: True
Inline callers:
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_read
```
```
In arch/x86/events/amd/brs.c (ffffffff8100e183)
Location: include/linux/perf_event.h:1169
Inline: True
Inline callers:
  - arch/x86/events/amd/brs.c:amd_brs_drain
```
```
In arch/x86/events/intel/lbr.c (ffffffff8101c549)
Location: include/linux/perf_event.h:1169
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_store_lbr
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_32
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
In arch/x86/events/amd/lbr.c (ffffffff8100cd7a)
Location: include/linux/perf_event.h:1280
Inline: True
Inline callers:
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_read
```
```
In arch/x86/events/amd/brs.c (ffffffff8100d7ed)
Location: include/linux/perf_event.h:1280
Inline: True
Inline callers:
  - arch/x86/events/amd/brs.c:amd_brs_drain
```
```
In arch/x86/events/intel/lbr.c (ffffffff8101c209)
Location: include/linux/perf_event.h:1280
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_store_lbr
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_32
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
In arch/x86/events/amd/lbr.c (ffffffff810125ba)
Location: include/linux/perf_event.h:1306
Inline: True
Inline callers:
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_read
```
```
In arch/x86/events/amd/brs.c (ffffffff8101302d)
Location: include/linux/perf_event.h:1306
Inline: True
Inline callers:
  - arch/x86/events/amd/brs.c:amd_brs_drain
```
```
In arch/x86/events/intel/lbr.c (ffffffff81022189)
Location: include/linux/perf_event.h:1306
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_store_lbr
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_32
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
