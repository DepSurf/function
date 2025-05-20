# Function: <code>register_power_pmu</code>

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
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int register_power_pmu(struct power_pmu *pmu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/perf/core-book3s.c (c000000000129c80)
Location: arch/powerpc/perf/core-book3s.c:2275
Inline: False
Direct callers:
  - arch/powerpc/perf/ppc970-pmu.c:init_ppc970_pmu
  - arch/powerpc/perf/power5-pmu.c:init_power5_pmu
  - arch/powerpc/perf/power5+-pmu.c:init_power5p_pmu
  - arch/powerpc/perf/power6-pmu.c:init_power6_pmu
  - arch/powerpc/perf/power7-pmu.c:init_power7_pmu
  - arch/powerpc/perf/power8-pmu.c:init_power8_pmu
  - arch/powerpc/perf/power9-pmu.c:init_power9_pmu
  - arch/powerpc/perf/generic-compat-pmu.c:init_generic_compat_pmu
```
**Symbols:**

```
c000000000129c80-c000000000129d60: register_power_pmu (STB_GLOBAL)
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
