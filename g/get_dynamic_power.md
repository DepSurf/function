# Function: <code>get_dynamic_power</code>

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
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff817a632b)
Location: drivers/thermal/devfreq_cooling.c:245
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff817edd97)
Location: drivers/thermal/devfreq_cooling.c:245
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
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
In drivers/thermal/devfreq_cooling.c (ffffffff81819c6c)
Location: drivers/thermal/devfreq_cooling.c:245
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff8185bdf6)
Location: drivers/thermal/devfreq_cooling.c:245
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff8188d906)
Location: drivers/thermal/devfreq_cooling.c:245
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
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
In drivers/thermal/devfreq_cooling.c (ffffffff8195c253)
Location: drivers/thermal/devfreq_cooling.c:211
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_gen_tables
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_gen_tables
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
<summary>In <code>arm64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/cpu_cooling.c (ffff800010adc11c)
Location: drivers/thermal/cpu_cooling.c:259
Inline: True
Inline callers:
  - drivers/thermal/cpu_cooling.c:cpufreq_get_requested_power
```
```
In drivers/thermal/devfreq_cooling.c (ffff800010add264)
Location: drivers/thermal/devfreq_cooling.c:245
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Selective Inline ⚠️</summary>

```c
u32 get_dynamic_power(struct cpufreq_cooling_device *cpufreq_cdev, long unsigned int freq);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/cpu_cooling.c (c0bbc51c)
Location: drivers/thermal/cpu_cooling.c:259
Inline: True
Inline callers:
  - drivers/thermal/cpu_cooling.c:cpufreq_get_requested_power
```
```
In drivers/thermal/devfreq_cooling.c (c0bbd57c)
Location: drivers/thermal/devfreq_cooling.c:245
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
**Symbols:**

```
c0bbd57c-c0bbd630: get_dynamic_power (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/cpu_cooling.c (c000000000bc4340)
Location: drivers/thermal/cpu_cooling.c:259
Inline: True
Inline callers:
  - drivers/thermal/cpu_cooling.c:cpufreq_get_requested_power
```
```
In drivers/thermal/devfreq_cooling.c (c000000000bc5c30)
Location: drivers/thermal/devfreq_cooling.c:245
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffe0006d647c)
Location: drivers/thermal/devfreq_cooling.c:245
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff81833786)
Location: drivers/thermal/devfreq_cooling.c:245
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff817fae16)
Location: drivers/thermal/devfreq_cooling.c:245
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff81882db6)
Location: drivers/thermal/devfreq_cooling.c:245
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff8189e876)
Location: drivers/thermal/devfreq_cooling.c:245
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
