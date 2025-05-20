# Function: <code>write_mmcr0</code>

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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void write_mmcr0(void *val);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/powerpc/kernel/sysfs.c (c000000000023c90)
Location: arch/powerpc/kernel/sysfs.c:470
Inline: False
```
```
In arch/powerpc/perf/core-book3s.c (c000000000129480)
Location: arch/powerpc/perf/core-book3s.c:1162
Inline: True
Inline callers:
  - arch/powerpc/perf/core-book3s.c:perf_event_interrupt
  - arch/powerpc/perf/core-book3s.c:power_pmu_enable
  - arch/powerpc/perf/core-book3s.c:power_pmu_disable
Direct callers:
  - arch/powerpc/perf/core-book3s.c:perf_event_interrupt
  - arch/powerpc/perf/core-book3s.c:power_pmu_enable
  - arch/powerpc/perf/core-book3s.c:power_pmu_disable
```
**Symbols:**

```
c000000000023c90-c000000000023cd4: write_mmcr0 (STB_LOCAL)
c000000000127f80-c0000000001280d0: write_mmcr0.part.0 (STB_LOCAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
