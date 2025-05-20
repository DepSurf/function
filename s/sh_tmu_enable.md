# Function: <code>sh_tmu_enable</code>

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
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clocksource/sh_tmu.c (ffff800010b661fc)
Location: drivers/clocksource/sh_tmu.c:168
Inline: True
Inline callers:
  - drivers/clocksource/sh_tmu.c:sh_tmu_clock_event_set_state
  - drivers/clocksource/sh_tmu.c:sh_tmu_clocksource_enable
Direct callers:
  - drivers/clocksource/sh_tmu.c:sh_tmu_clock_event_set_state
  - drivers/clocksource/sh_tmu.c:sh_tmu_clock_event_set_state
  - drivers/clocksource/sh_tmu.c:sh_tmu_clocksource_enable
```
**Symbols:**

```
ffff800010b65fc8-ffff800010b6601c: sh_tmu_enable.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clocksource/sh_tmu.c (c0c4643c)
Location: drivers/clocksource/sh_tmu.c:168
Inline: True
Inline callers:
  - drivers/clocksource/sh_tmu.c:sh_tmu_clock_event_set_state
  - drivers/clocksource/sh_tmu.c:sh_tmu_clocksource_enable
Direct callers:
  - drivers/clocksource/sh_tmu.c:sh_tmu_clock_event_set_state
  - drivers/clocksource/sh_tmu.c:sh_tmu_clock_event_set_state
  - drivers/clocksource/sh_tmu.c:sh_tmu_clocksource_enable
```
**Symbols:**

```
c0c46234-c0c46280: sh_tmu_enable.part.0 (STB_LOCAL)
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
