# Function: <code>sh_tmu_clock_event_set_state</code>

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
int sh_tmu_clock_event_set_state(struct clock_event_device *ced, int periodic);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/sh_tmu.c (ffff800010b66198)
Location: drivers/clocksource/sh_tmu.c:354
Inline: False
Direct callers:
  - drivers/clocksource/sh_tmu.c:sh_tmu_clock_event_set_periodic
  - drivers/clocksource/sh_tmu.c:sh_tmu_clock_event_set_oneshot
```
**Symbols:**

```
ffff800010b66198-ffff800010b6627c: sh_tmu_clock_event_set_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sh_tmu_clock_event_set_state(struct clock_event_device *ced, int periodic);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/sh_tmu.c (c0c463d8)
Location: drivers/clocksource/sh_tmu.c:354
Inline: False
Direct callers:
  - drivers/clocksource/sh_tmu.c:sh_tmu_clock_event_set_periodic
  - drivers/clocksource/sh_tmu.c:sh_tmu_clock_event_set_oneshot
```
**Symbols:**

```
c0c463d8-c0c464c0: sh_tmu_clock_event_set_state (STB_LOCAL)
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
