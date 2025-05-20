# Function: <code>__x86_pmu_enable_event</code>

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
In arch/x86/events/core.c (ffffffff81006615)
Location: arch/x86/events/perf_event.h:736
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_enable_all
  - arch/x86/events/core.c:x86_pmu_enable_event
```
```
In arch/x86/events/intel/core.c (ffffffff8100becc)
Location: arch/x86/events/perf_event.h:736
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
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
In arch/x86/events/core.c (ffffffff8100709b)
Location: arch/x86/events/perf_event.h:745
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_pmu_enable_all
```
```
In arch/x86/events/intel/core.c (ffffffff8100c2d7)
Location: arch/x86/events/perf_event.h:745
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
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
In arch/x86/events/core.c (ffffffff8100709b)
Location: arch/x86/events/perf_event.h:748
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_pmu_enable_all
```
```
In arch/x86/events/intel/core.c (ffffffff8100c397)
Location: arch/x86/events/perf_event.h:748
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
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
In arch/x86/events/core.c (ffffffff81006dac)
Location: arch/x86/events/perf_event.h:753
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_pmu_enable_all
```
```
In arch/x86/events/intel/core.c (ffffffff8100c0ee)
Location: arch/x86/events/perf_event.h:753
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
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
In arch/x86/events/core.c (ffffffff810071cf)
Location: arch/x86/events/perf_event.h:763
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_pmu_enable_all
```
```
In arch/x86/events/intel/core.c (ffffffff8100c3be)
Location: arch/x86/events/perf_event.h:763
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
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
In arch/x86/events/core.c (ffffffff8100792f)
Location: arch/x86/events/perf_event.h:766
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_pmu_enable_all
```
```
In arch/x86/events/intel/core.c (ffffffff8100cb46)
Location: arch/x86/events/perf_event.h:766
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
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
In arch/x86/events/core.c (ffffffff8100780f)
Location: arch/x86/events/perf_event.h:784
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_pmu_enable_all
```
```
In arch/x86/events/intel/core.c (ffffffff8100cb06)
Location: arch/x86/events/perf_event.h:784
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
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
In arch/x86/events/core.c (ffffffff81007afb)
Location: arch/x86/events/perf_event.h:821
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_pmu_enable_all
```
```
In arch/x86/events/intel/core.c (ffffffff8100d346)
Location: arch/x86/events/perf_event.h:821
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
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
In arch/x86/events/core.c (ffffffff81007cbf)
Location: arch/x86/events/perf_event.h:842
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_pmu_enable_all
```
```
In arch/x86/events/intel/core.c (ffffffff8100d908)
Location: arch/x86/events/perf_event.h:842
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
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
In arch/x86/events/core.c (ffffffff81008d2f)
Location: arch/x86/events/perf_event.h:851
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_pmu_enable_all
```
```
In arch/x86/events/intel/core.c (ffffffff8100e490)
Location: arch/x86/events/perf_event.h:851
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_workaround
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff8101f9c4)
Location: arch/x86/events/perf_event.h:851
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
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
In arch/x86/events/core.c (ffffffff81007ddf)
Location: arch/x86/events/perf_event.h:982
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_pmu_enable_all
```
```
In arch/x86/events/intel/core.c (ffffffff8100d650)
Location: arch/x86/events/perf_event.h:982
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_workaround
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff81020464)
Location: arch/x86/events/perf_event.h:982
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
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
In arch/x86/events/core.c (ffffffff810085af)
Location: arch/x86/events/perf_event.h:1105
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_pmu_enable_all
```
```
In arch/x86/events/intel/core.c (ffffffff8100e3e0)
Location: arch/x86/events/perf_event.h:1105
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff810227f4)
Location: arch/x86/events/perf_event.h:1105
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
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
In arch/x86/events/core.c (ffffffff8100939f)
Location: arch/x86/events/perf_event.h:1105
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_pmu_enable_all
```
```
In arch/x86/events/intel/core.c (ffffffff8100eba6)
Location: arch/x86/events/perf_event.h:1105
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff81026677)
Location: arch/x86/events/perf_event.h:1105
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
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
In arch/x86/events/core.c (ffffffff81008a19)
Location: arch/x86/events/perf_event.h:1131
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_pmu_enable_all
```
```
In arch/x86/events/amd/core.c (ffffffff8100b325)
Location: arch/x86/events/perf_event.h:1131
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_v2_enable_event
```
```
In arch/x86/events/intel/core.c (ffffffff8100ff65)
Location: arch/x86/events/perf_event.h:1131
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff8102a777)
Location: arch/x86/events/perf_event.h:1131
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
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
In arch/x86/events/core.c (ffffffff81009bc9)
Location: arch/x86/events/perf_event.h:1139
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_pmu_enable_all
```
```
In arch/x86/events/amd/core.c (ffffffff8100ccf5)
Location: arch/x86/events/perf_event.h:1139
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_v2_enable_event
```
```
In arch/x86/events/intel/core.c (ffffffff81013c05)
Location: arch/x86/events/perf_event.h:1139
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff81031347)
Location: arch/x86/events/perf_event.h:1139
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
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
In arch/x86/events/core.c (ffffffff810093e9)
Location: arch/x86/events/perf_event.h:1144
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_pmu_enable_all
```
```
In arch/x86/events/amd/core.c (ffffffff8100c4b5)
Location: arch/x86/events/perf_event.h:1144
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_v2_enable_event
```
```
In arch/x86/events/intel/core.c (ffffffff81013463)
Location: arch/x86/events/perf_event.h:1144
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff81031357)
Location: arch/x86/events/perf_event.h:1144
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
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
In arch/x86/events/core.c (ffffffff8100eb09)
Location: arch/x86/events/perf_event.h:1159
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_pmu_enable_all
```
```
In arch/x86/events/amd/core.c (ffffffff81011c95)
Location: arch/x86/events/perf_event.h:1159
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_v2_enable_event
```
```
In arch/x86/events/intel/core.c (ffffffff81018af3)
Location: arch/x86/events/perf_event.h:1159
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff81037647)
Location: arch/x86/events/perf_event.h:1159
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
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
In arch/x86/events/core.c (ffffffff81007cbf)
Location: arch/x86/events/perf_event.h:842
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_pmu_enable_all
```
```
In arch/x86/events/intel/core.c (ffffffff8100d908)
Location: arch/x86/events/perf_event.h:842
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
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
In arch/x86/events/core.c (ffffffff81006495)
Location: arch/x86/events/perf_event.h:842
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_pmu_enable_all
```
```
In arch/x86/events/intel/core.c (ffffffff8100c08c)
Location: arch/x86/events/perf_event.h:842
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
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
In arch/x86/events/core.c (ffffffff81007c7f)
Location: arch/x86/events/perf_event.h:842
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_pmu_enable_all
```
```
In arch/x86/events/intel/core.c (ffffffff8100d8c8)
Location: arch/x86/events/perf_event.h:842
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
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
In arch/x86/events/core.c (ffffffff81007ddf)
Location: arch/x86/events/perf_event.h:842
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_pmu_enable_all
```
```
In arch/x86/events/intel/core.c (ffffffff8100da98)
Location: arch/x86/events/perf_event.h:842
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
```
</details>
</li>
</ul>

## Differences
