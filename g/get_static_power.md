# Function: <code>get_static_power</code>

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
In drivers/thermal/devfreq_cooling.c (ffffffff817a5dc0)
Location: drivers/thermal/devfreq_cooling.c:216
Inline: True
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_power2state
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_state2power
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
**Symbols:**

```
ffffffff817a5dc0-ffffffff817a5e0c: get_static_power.isra.3 (STB_LOCAL)
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
In drivers/thermal/devfreq_cooling.c (ffffffff817ed840)
Location: drivers/thermal/devfreq_cooling.c:216
Inline: True
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_power2state
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_state2power
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
**Symbols:**

```
ffffffff817ed840-ffffffff817ed88c: get_static_power.isra.3 (STB_LOCAL)
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
In drivers/thermal/devfreq_cooling.c (ffffffff81819710)
Location: drivers/thermal/devfreq_cooling.c:216
Inline: True
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_power2state
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_state2power
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
**Symbols:**

```
ffffffff81819710-ffffffff8181975c: get_static_power.isra.4 (STB_LOCAL)
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
In drivers/thermal/devfreq_cooling.c (ffffffff8185b870)
Location: drivers/thermal/devfreq_cooling.c:216
Inline: True
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_power2state
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_state2power
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
**Symbols:**

```
ffffffff8185b870-ffffffff8185b8b9: get_static_power.isra.0 (STB_LOCAL)
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
In drivers/thermal/devfreq_cooling.c (ffffffff8188d380)
Location: drivers/thermal/devfreq_cooling.c:216
Inline: True
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_power2state
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_state2power
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
**Symbols:**

```
ffffffff8188d380-ffffffff8188d3c9: get_static_power.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff8195c205)
Location: drivers/thermal/devfreq_cooling.c:182
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_gen_tables
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_power2state
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_state2power
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
</details>
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
In drivers/thermal/devfreq_cooling.c (ffff800010adcbb0)
Location: drivers/thermal/devfreq_cooling.c:216
Inline: True
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_power2state
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_state2power
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
**Symbols:**

```
ffff800010adcbb0-ffff800010adcc28: get_static_power.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int get_static_power(struct devfreq_cooling_device *dfc, long unsigned int freq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (c0bbcff4)
Location: drivers/thermal/devfreq_cooling.c:216
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_power2state
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_state2power
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
**Symbols:**

```
c0bbcff4-c0bbd04c: get_static_power (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (c000000000bc5240)
Location: drivers/thermal/devfreq_cooling.c:216
Inline: True
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_power2state
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_state2power
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
**Symbols:**

```
c000000000bc5240-c000000000bc52dc: get_static_power.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffe0006d5f3e)
Location: drivers/thermal/devfreq_cooling.c:216
Inline: True
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_power2state
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_state2power
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
**Symbols:**

```
ffffffe0006d5f3e-ffffffe0006d5f98: get_static_power.isra.0 (STB_LOCAL)
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
In drivers/thermal/devfreq_cooling.c (ffffffff81833200)
Location: drivers/thermal/devfreq_cooling.c:216
Inline: True
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_power2state
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_state2power
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
**Symbols:**

```
ffffffff81833200-ffffffff81833249: get_static_power.isra.0 (STB_LOCAL)
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
In drivers/thermal/devfreq_cooling.c (ffffffff817fa890)
Location: drivers/thermal/devfreq_cooling.c:216
Inline: True
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_power2state
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_state2power
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
**Symbols:**

```
ffffffff817fa890-ffffffff817fa8d9: get_static_power.isra.0 (STB_LOCAL)
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
In drivers/thermal/devfreq_cooling.c (ffffffff81882830)
Location: drivers/thermal/devfreq_cooling.c:216
Inline: True
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_power2state
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_state2power
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
**Symbols:**

```
ffffffff81882830-ffffffff81882879: get_static_power.isra.0 (STB_LOCAL)
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
In drivers/thermal/devfreq_cooling.c (ffffffff8189e2d0)
Location: drivers/thermal/devfreq_cooling.c:216
Inline: True
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_power2state
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_state2power
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
**Symbols:**

```
ffffffff8189e2d0-ffffffff8189e319: get_static_power.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
