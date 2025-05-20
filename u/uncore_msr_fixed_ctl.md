# Function: <code>uncore_msr_fixed_ctl</code>

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
In arch/x86/events/intel/uncore.c (ffffffff81017043)
Location: arch/x86/events/intel/uncore.h:191
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff810171b5)
Location: arch/x86/events/intel/uncore.h:191
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
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
In arch/x86/events/intel/uncore.c (ffffffff81016284)
Location: arch/x86/events/intel/uncore.h:199
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81016508)
Location: arch/x86/events/intel/uncore.h:199
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
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
In arch/x86/events/intel/uncore.c (ffffffff81016490)
Location: arch/x86/events/intel/uncore.h:204
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81016718)
Location: arch/x86/events/intel/uncore.h:204
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
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
In arch/x86/events/intel/uncore.c (ffffffff810148fa)
Location: arch/x86/events/intel/uncore.h:204
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81014c91)
Location: arch/x86/events/intel/uncore.h:204
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
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
In arch/x86/events/intel/uncore.c (ffffffff8101515a)
Location: arch/x86/events/intel/uncore.h:205
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff810169a1)
Location: arch/x86/events/intel/uncore.h:205
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
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
In arch/x86/events/intel/uncore.c (ffffffff81015c60)
Location: arch/x86/events/intel/uncore.h:231
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff810175cb)
Location: arch/x86/events/intel/uncore.h:231
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
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
In arch/x86/events/intel/uncore.c (ffffffff810163a9)
Location: arch/x86/events/intel/uncore.h:238
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81017d4b)
Location: arch/x86/events/intel/uncore.h:238
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
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
In arch/x86/events/intel/uncore.c (ffffffff810179c2)
Location: arch/x86/events/intel/uncore.h:250
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8101933b)
Location: arch/x86/events/intel/uncore.h:250
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
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
In arch/x86/events/intel/uncore.c (ffffffff81018352)
Location: arch/x86/events/intel/uncore.h:250
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81019cbb)
Location: arch/x86/events/intel/uncore.h:250
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
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
In arch/x86/events/intel/uncore.c (ffffffff81019012)
Location: arch/x86/events/intel/uncore.h:251
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_assign_hw_event
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8101b4fb)
Location: arch/x86/events/intel/uncore.h:251
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
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
In arch/x86/events/intel/uncore.c (ffffffff8101976b)
Location: arch/x86/events/intel/uncore.h:288
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_assign_hw_event
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8101b9fb)
Location: arch/x86/events/intel/uncore.h:288
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
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
In arch/x86/events/intel/uncore.c (ffffffff8101aa91)
Location: arch/x86/events/intel/uncore.h:301
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_assign_hw_event
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8101cdab)
Location: arch/x86/events/intel/uncore.h:301
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
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
In arch/x86/events/intel/uncore.c (ffffffff8101d474)
Location: arch/x86/events/intel/uncore.h:302
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_assign_hw_event
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8101fe8c)
Location: arch/x86/events/intel/uncore.h:302
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
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
In arch/x86/events/intel/uncore.c (ffffffff8101fde4)
Location: arch/x86/events/intel/uncore.h:302
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_assign_hw_event
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81022d5f)
Location: arch/x86/events/intel/uncore.h:302
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
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
In arch/x86/events/intel/uncore.c (ffffffff81024644)
Location: arch/x86/events/intel/uncore.h:318
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_assign_hw_event
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81027a3f)
Location: arch/x86/events/intel/uncore.h:318
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
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
In arch/x86/events/intel/uncore.c (ffffffff810243a4)
Location: arch/x86/events/intel/uncore.h:321
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_assign_hw_event
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81027a5f)
Location: arch/x86/events/intel/uncore.h:321
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
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
In arch/x86/events/intel/uncore.c (ffffffff8102a4d4)
Location: arch/x86/events/intel/uncore.h:321
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_assign_hw_event
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8102dcaf)
Location: arch/x86/events/intel/uncore.h:321
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
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
In arch/x86/events/intel/uncore.c (ffffffff81018352)
Location: arch/x86/events/intel/uncore.h:250
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81019cbb)
Location: arch/x86/events/intel/uncore.h:250
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
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
In arch/x86/events/intel/uncore.c (ffffffff81017782)
Location: arch/x86/events/intel/uncore.h:250
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff810191e7)
Location: arch/x86/events/intel/uncore.h:250
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
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
In arch/x86/events/intel/uncore.c (ffffffff81018312)
Location: arch/x86/events/intel/uncore.h:250
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81019c7b)
Location: arch/x86/events/intel/uncore.h:250
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
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
In arch/x86/events/intel/uncore.c (ffffffff81018552)
Location: arch/x86/events/intel/uncore.h:250
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81019ebb)
Location: arch/x86/events/intel/uncore.h:250
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
</details>
</li>
</ul>

## Differences
