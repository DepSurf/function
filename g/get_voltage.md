# Function: <code>get_voltage</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff817a5cb0)
Location: drivers/thermal/devfreq_cooling.c:177
Inline: True
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
**Symbols:**

```
ffffffff817a5cb0-ffffffff817a5db3: get_voltage.isra.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff817ed740)
Location: drivers/thermal/devfreq_cooling.c:177
Inline: True
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
**Symbols:**

```
ffffffff817ed740-ffffffff817ed83c: get_voltage.isra.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff81819610)
Location: drivers/thermal/devfreq_cooling.c:177
Inline: True
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
**Symbols:**

```
ffffffff81819610-ffffffff8181970c: get_voltage.isra.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (0)
Location: drivers/thermal/devfreq_cooling.c:177
Inline: True
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
**Symbols:**

```
ffffffff8185b770-ffffffff8185b862: get_voltage.isra.0 (STB_LOCAL)
ffffffff8185c0d7-ffffffff8185c10b: get_voltage.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (0)
Location: drivers/thermal/devfreq_cooling.c:177
Inline: True
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
**Symbols:**

```
ffffffff8188d280-ffffffff8188d372: get_voltage.isra.0 (STB_LOCAL)
ffffffff8188dbe7-ffffffff8188dc1b: get_voltage.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (0)
Location: drivers/thermal/devfreq_cooling.c:143
Inline: True
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_gen_tables
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_power2state
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_state2power
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
**Symbols:**

```
ffffffff8195bdb0-ffffffff8195bea2: get_voltage.isra.0 (STB_LOCAL)
ffffffff8195c795-ffffffff8195c7c9: get_voltage.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (0)
Location: drivers/thermal/devfreq_cooling.c:139
Inline: True
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
**Symbols:**

```
ffffffff81962e30-ffffffff81962f22: get_voltage.isra.0 (STB_LOCAL)
ffffffff81c25da0-ffffffff81c25dd4: get_voltage.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff819464b4)
Location: drivers/thermal/devfreq_cooling.c:134
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff819eaeb4)
Location: drivers/thermal/devfreq_cooling.c:134
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff81b50d14)
Location: drivers/thermal/devfreq_cooling.c:134
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff81ce8cf4)
Location: drivers/thermal/devfreq_cooling.c:136
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff81d514b4)
Location: drivers/thermal/devfreq_cooling.c:136
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff81e08234)
Location: drivers/thermal/devfreq_cooling.c:136
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
</details>
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
In drivers/thermal/devfreq_cooling.c (ffff800010adca90)
Location: drivers/thermal/devfreq_cooling.c:177
Inline: True
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
**Symbols:**

```
ffff800010adca90-ffff800010adcbb0: get_voltage.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int get_voltage(struct devfreq *df, long unsigned int freq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (c0bbcef4)
Location: drivers/thermal/devfreq_cooling.c:177
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
  - drivers/thermal/devfreq_cooling.c:get_static_power
```
**Symbols:**

```
c0bbcef4-c0bbcff4: get_voltage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int get_voltage(struct devfreq *df, long unsigned int freq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (c000000000bc4eb0)
Location: drivers/thermal/devfreq_cooling.c:177
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
**Symbols:**

```
c000000000bc4eb0-c000000000bc5034: get_voltage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int get_voltage(struct devfreq *df, long unsigned int freq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffe0006d5d4e)
Location: drivers/thermal/devfreq_cooling.c:177
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
**Symbols:**

```
ffffffe0006d5d4e-ffffffe0006d5e44: get_voltage (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (0)
Location: drivers/thermal/devfreq_cooling.c:177
Inline: True
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
**Symbols:**

```
ffffffff81833100-ffffffff818331f2: get_voltage.isra.0 (STB_LOCAL)
ffffffff81833a67-ffffffff81833a9b: get_voltage.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (0)
Location: drivers/thermal/devfreq_cooling.c:177
Inline: True
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
**Symbols:**

```
ffffffff817fa790-ffffffff817fa882: get_voltage.isra.0 (STB_LOCAL)
ffffffff817fb0f7-ffffffff817fb12b: get_voltage.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (0)
Location: drivers/thermal/devfreq_cooling.c:177
Inline: True
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
**Symbols:**

```
ffffffff81882730-ffffffff81882822: get_voltage.isra.0 (STB_LOCAL)
ffffffff81883097-ffffffff818830cb: get_voltage.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (0)
Location: drivers/thermal/devfreq_cooling.c:177
Inline: True
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
**Symbols:**

```
ffffffff8189e1d0-ffffffff8189e2c2: get_voltage.isra.0 (STB_LOCAL)
ffffffff8189eb57-ffffffff8189eb8b: get_voltage.isra.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
