# Function: <code>irq_is_percpu_devid</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/perf/arm_pmu.c (ffff800010b944cc)
Location: include/linux/irqdesc.h:251
Inline: True
Inline callers:
  - drivers/perf/arm_pmu.c:arm_perf_starting_cpu
  - drivers/perf/arm_pmu.c:armpmu_request_irq
  - drivers/perf/arm_pmu.c:armpmu_free_irq
```
```
In drivers/perf/arm_pmu_platform.c (ffff800010b95918)
Location: include/linux/irqdesc.h:251
Inline: True
Inline callers:
  - drivers/perf/arm_pmu_platform.c:pmu_parse_irqs
  - drivers/perf/arm_pmu_platform.c:pmu_parse_irqs
```
```
In drivers/perf/arm_pmu_acpi.c (ffff800010b95da0)
Location: include/linux/irqdesc.h:251
Inline: True
Inline callers:
  - drivers/perf/arm_pmu_acpi.c:arm_pmu_acpi_cpu_starting
  - drivers/perf/arm_pmu_acpi.c:arm_pmu_acpi_cpu_starting
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/perf/arm_pmu.c (c0c7dc28)
Location: include/linux/irqdesc.h:251
Inline: True
Inline callers:
  - drivers/perf/arm_pmu.c:arm_perf_starting_cpu
  - drivers/perf/arm_pmu.c:armpmu_request_irq
  - drivers/perf/arm_pmu.c:armpmu_free_irq
```
```
In drivers/perf/arm_pmu_platform.c (c0c7ede0)
Location: include/linux/irqdesc.h:251
Inline: True
Inline callers:
  - drivers/perf/arm_pmu_platform.c:arm_pmu_device_probe
  - drivers/perf/arm_pmu_platform.c:arm_pmu_device_probe
```
</details>
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
