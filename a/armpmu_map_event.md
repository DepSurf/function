# Function: <code>armpmu_map_event</code>

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
<summary>In <code>arm64</code>: ✅</summary>

```c
int armpmu_map_event(struct perf_event *event, const unsigned int[10] *event_map, const unsigned int[42] *cache_map, u32 raw_event_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/perf/arm_pmu.c (ffff800010b94c60)
Location: drivers/perf/arm_pmu.c:94
Inline: False
```
**Symbols:**

```
ffff800010b94c60-ffff800010b94d84: armpmu_map_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int armpmu_map_event(struct perf_event *event, const unsigned int[10] *event_map, const unsigned int[42] *cache_map, u32 raw_event_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/perf/arm_pmu.c (c0c7e28c)
Location: drivers/perf/arm_pmu.c:94
Inline: False
Direct callers:
  - arch/arm/kernel/perf_event_v7.c:scorpion_map_event
  - arch/arm/kernel/perf_event_v7.c:krait_map_event_no_branch
  - arch/arm/kernel/perf_event_v7.c:krait_map_event
  - arch/arm/kernel/perf_event_v7.c:armv7_a12_map_event
  - arch/arm/kernel/perf_event_v7.c:armv7_a7_map_event
  - arch/arm/kernel/perf_event_v7.c:armv7_a15_map_event
  - arch/arm/kernel/perf_event_v7.c:armv7_a5_map_event
  - arch/arm/kernel/perf_event_v7.c:armv7_a9_map_event
  - arch/arm/kernel/perf_event_v7.c:armv7_a8_map_event
```
**Symbols:**

```
c0c7e28c-c0c7e364: armpmu_map_event (STB_GLOBAL)
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
<b>Arch</b>
<ul>
</ul>
