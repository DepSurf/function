# Function: <code>devfreq_cooling_em_register</code>

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
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct thermal_cooling_device *devfreq_cooling_em_register(struct devfreq *df, struct devfreq_cooling_power *dfc_power);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff81962d10)
Location: drivers/thermal/devfreq_cooling.c:485
Inline: True
```
**Symbols:**

```
ffffffff81962d10-ffffffff81962db9: devfreq_cooling_em_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct thermal_cooling_device *devfreq_cooling_em_register(struct devfreq *df, struct devfreq_cooling_power *dfc_power);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff81946300)
Location: drivers/thermal/devfreq_cooling.c:477
Inline: True
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff81946300-ffffffff819463a9: devfreq_cooling_em_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct thermal_cooling_device *devfreq_cooling_em_register(struct devfreq *df, struct devfreq_cooling_power *dfc_power);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff819ead00)
Location: drivers/thermal/devfreq_cooling.c:477
Inline: True
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff819ead00-ffffffff819eada6: devfreq_cooling_em_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct thermal_cooling_device *devfreq_cooling_em_register(struct devfreq *df, struct devfreq_cooling_power *dfc_power);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff81b50b80)
Location: drivers/thermal/devfreq_cooling.c:498
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff81b50b80-ffffffff81b50c4b: devfreq_cooling_em_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct thermal_cooling_device *devfreq_cooling_em_register(struct devfreq *df, struct devfreq_cooling_power *dfc_power);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff81ce8b50)
Location: drivers/thermal/devfreq_cooling.c:492
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff81ce8b50-ffffffff81ce8c1b: devfreq_cooling_em_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct thermal_cooling_device *devfreq_cooling_em_register(struct devfreq *df, struct devfreq_cooling_power *dfc_power);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff81d51310)
Location: drivers/thermal/devfreq_cooling.c:492
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff81d51310-ffffffff81d513db: devfreq_cooling_em_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct thermal_cooling_device *devfreq_cooling_em_register(struct devfreq *df, struct devfreq_cooling_power *dfc_power);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff81e08090)
Location: drivers/thermal/devfreq_cooling.c:492
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff81e08090-ffffffff81e0815b: devfreq_cooling_em_register (STB_GLOBAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
