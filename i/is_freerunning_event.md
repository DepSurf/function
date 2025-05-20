# Function: <code>is_freerunning_event</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff810147ab)
Location: arch/x86/events/intel/uncore.h:397
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_init
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
In arch/x86/events/intel/uncore.c (ffffffff81014eab)
Location: arch/x86/events/intel/uncore.h:414
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_init
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
In arch/x86/events/intel/uncore.c (ffffffff810164fa)
Location: arch/x86/events/intel/uncore.h:426
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_init
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81019f57)
Location: arch/x86/events/intel/uncore.h:426
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:uncore_freerunning_hw_config
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
In arch/x86/events/intel/uncore.c (ffffffff81016eaa)
Location: arch/x86/events/intel/uncore.h:426
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_init
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101a8d7)
Location: arch/x86/events/intel/uncore.h:426
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:uncore_freerunning_hw_config
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
In arch/x86/events/intel/uncore.c (ffffffff81018c6a)
Location: arch/x86/events/intel/uncore.h:429
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_init
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff8101ba10)
Location: arch/x86/events/intel/uncore.h:429
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:uncore_freerunning_hw_config
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101c480)
Location: arch/x86/events/intel/uncore.h:429
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:uncore_freerunning_hw_config
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
In arch/x86/events/intel/uncore.c (ffffffff810193ea)
Location: arch/x86/events/intel/uncore.h:466
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_init
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff8101bf10)
Location: arch/x86/events/intel/uncore.h:466
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:uncore_freerunning_hw_config
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101c9f0)
Location: arch/x86/events/intel/uncore.h:466
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:uncore_freerunning_hw_config
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
In arch/x86/events/intel/uncore.c (ffffffff8101a70a)
Location: arch/x86/events/intel/uncore.h:479
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_init
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff8101d2c0)
Location: arch/x86/events/intel/uncore.h:479
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:uncore_freerunning_hw_config
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101dea0)
Location: arch/x86/events/intel/uncore.h:479
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:uncore_freerunning_hw_config
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
In arch/x86/events/intel/uncore.c (ffffffff8101d0a7)
Location: arch/x86/events/intel/uncore.h:480
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_init
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff810203c0)
Location: arch/x86/events/intel/uncore.h:480
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:uncore_freerunning_hw_config
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81020fa0)
Location: arch/x86/events/intel/uncore.h:480
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:uncore_freerunning_hw_config
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
In arch/x86/events/intel/uncore.c (ffffffff8101f8ff)
Location: arch/x86/events/intel/uncore.h:480
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_init
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff81023340)
Location: arch/x86/events/intel/uncore.h:480
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:uncore_freerunning_hw_config
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81024550)
Location: arch/x86/events/intel/uncore.h:480
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:uncore_freerunning_hw_config
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
In arch/x86/events/intel/uncore.c (ffffffff8102413f)
Location: arch/x86/events/intel/uncore.h:496
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_init
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff81028080)
Location: arch/x86/events/intel/uncore.h:496
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:uncore_freerunning_hw_config
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81029700)
Location: arch/x86/events/intel/uncore.h:496
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:uncore_freerunning_hw_config
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
In arch/x86/events/intel/uncore.c (ffffffff81023e5f)
Location: arch/x86/events/intel/uncore.h:499
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_init
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff810280b0)
Location: arch/x86/events/intel/uncore.h:499
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:uncore_freerunning_hw_config
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81029730)
Location: arch/x86/events/intel/uncore.h:499
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:uncore_freerunning_hw_config
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
In arch/x86/events/intel/uncore.c (ffffffff81029f8b)
Location: arch/x86/events/intel/uncore.h:499
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_init
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff8102e210)
Location: arch/x86/events/intel/uncore.h:499
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:uncore_freerunning_hw_config
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102f890)
Location: arch/x86/events/intel/uncore.h:499
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:uncore_freerunning_hw_config
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
In arch/x86/events/intel/uncore.c (ffffffff81016eaa)
Location: arch/x86/events/intel/uncore.h:426
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_init
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101a8d7)
Location: arch/x86/events/intel/uncore.h:426
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:uncore_freerunning_hw_config
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
In arch/x86/events/intel/uncore.c (ffffffff810162da)
Location: arch/x86/events/intel/uncore.h:426
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_init
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101a037)
Location: arch/x86/events/intel/uncore.h:426
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:uncore_freerunning_hw_config
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
In arch/x86/events/intel/uncore.c (ffffffff81016e6a)
Location: arch/x86/events/intel/uncore.h:426
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_init
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101a897)
Location: arch/x86/events/intel/uncore.h:426
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:uncore_freerunning_hw_config
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
In arch/x86/events/intel/uncore.c (ffffffff810170aa)
Location: arch/x86/events/intel/uncore.h:426
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_init
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101aad7)
Location: arch/x86/events/intel/uncore.h:426
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:uncore_freerunning_hw_config
```
</details>
</li>
</ul>

## Differences
