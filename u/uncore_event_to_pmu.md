# Function: <code>uncore_event_to_pmu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct intel_uncore_pmu *uncore_event_to_pmu(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81016620)
Location: arch/x86/events/intel/uncore.c:85
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_to_box
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init
```
**Symbols:**

```
ffffffff81016620-ffffffff8101662f: uncore_event_to_pmu (STB_GLOBAL)
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
In arch/x86/events/intel/uncore.c (0)
Location: arch/x86/events/intel/uncore.h:329
Inline: True
```
```
In arch/x86/events/intel/uncore_snb.c (0)
Location: arch/x86/events/intel/uncore.h:329
Inline: True
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
In arch/x86/events/intel/uncore.c (0)
Location: arch/x86/events/intel/uncore.h:334
Inline: True
```
```
In arch/x86/events/intel/uncore_snb.c (0)
Location: arch/x86/events/intel/uncore.h:334
Inline: True
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
In arch/x86/events/intel/uncore.c (0)
Location: arch/x86/events/intel/uncore.h:334
Inline: True
```
```
In arch/x86/events/intel/uncore_snb.c (0)
Location: arch/x86/events/intel/uncore.h:334
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
In arch/x86/events/intel/uncore.c (0)
Location: arch/x86/events/intel/uncore.h:335
Inline: True
```
```
In arch/x86/events/intel/uncore_snb.c (0)
Location: arch/x86/events/intel/uncore.h:335
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
In arch/x86/events/intel/uncore.c (ffffffff810146dc)
Location: arch/x86/events/intel/uncore.h:456
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_init
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff81017bfc)
Location: arch/x86/events/intel/uncore.h:456
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init
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
In arch/x86/events/intel/uncore.c (ffffffff81014ddc)
Location: arch/x86/events/intel/uncore.h:473
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_init
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff810183ec)
Location: arch/x86/events/intel/uncore.h:473
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init
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
In arch/x86/events/intel/uncore.c (ffffffff8101642a)
Location: arch/x86/events/intel/uncore.h:495
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_init
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff810199cc)
Location: arch/x86/events/intel/uncore.h:495
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init
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
In arch/x86/events/intel/uncore.c (ffffffff81016dda)
Location: arch/x86/events/intel/uncore.h:483
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_init
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff8101a34c)
Location: arch/x86/events/intel/uncore.h:483
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init
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
In arch/x86/events/intel/uncore.c (ffffffff81018b9a)
Location: arch/x86/events/intel/uncore.h:486
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_init
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff8101bc2c)
Location: arch/x86/events/intel/uncore.h:486
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init
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
In arch/x86/events/intel/uncore.c (ffffffff8101931a)
Location: arch/x86/events/intel/uncore.h:523
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_init
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff8101c12c)
Location: arch/x86/events/intel/uncore.h:523
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init
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
In arch/x86/events/intel/uncore.c (ffffffff8101a63a)
Location: arch/x86/events/intel/uncore.h:536
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_init
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff8101d50c)
Location: arch/x86/events/intel/uncore.h:536
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init
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
In arch/x86/events/intel/uncore.c (ffffffff8101cfca)
Location: arch/x86/events/intel/uncore.h:537
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_init
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff8102060c)
Location: arch/x86/events/intel/uncore.h:537
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init
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
In arch/x86/events/intel/uncore.c (0)
Location: arch/x86/events/intel/uncore.h:537
Inline: True
```
```
In arch/x86/events/intel/uncore_snb.c (0)
Location: arch/x86/events/intel/uncore.h:537
Inline: True
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
In arch/x86/events/intel/uncore.c (0)
Location: arch/x86/events/intel/uncore.h:553
Inline: True
```
```
In arch/x86/events/intel/uncore_snb.c (0)
Location: arch/x86/events/intel/uncore.h:553
Inline: True
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
In arch/x86/events/intel/uncore.c (0)
Location: arch/x86/events/intel/uncore.h:556
Inline: True
```
```
In arch/x86/events/intel/uncore_snb.c (0)
Location: arch/x86/events/intel/uncore.h:556
Inline: True
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
In arch/x86/events/intel/uncore.c (0)
Location: arch/x86/events/intel/uncore.h:556
Inline: True
```
```
In arch/x86/events/intel/uncore_snb.c (0)
Location: arch/x86/events/intel/uncore.h:556
Inline: True
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
In arch/x86/events/intel/uncore.c (ffffffff81016dda)
Location: arch/x86/events/intel/uncore.h:483
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_init
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff8101a34c)
Location: arch/x86/events/intel/uncore.h:483
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init
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
In arch/x86/events/intel/uncore.c (ffffffff8101620a)
Location: arch/x86/events/intel/uncore.h:483
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_init
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff8101990c)
Location: arch/x86/events/intel/uncore.h:483
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init
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
In arch/x86/events/intel/uncore.c (ffffffff81016d9a)
Location: arch/x86/events/intel/uncore.h:483
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_init
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff8101a30c)
Location: arch/x86/events/intel/uncore.h:483
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init
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
In arch/x86/events/intel/uncore.c (ffffffff81016fda)
Location: arch/x86/events/intel/uncore.h:483
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_init
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff8101a54c)
Location: arch/x86/events/intel/uncore.h:483
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
