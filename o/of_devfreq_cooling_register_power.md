# Function: <code>of_devfreq_cooling_register_power</code>

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
<summary>In <code>4.15</code>: ✅</summary>

```c
struct thermal_cooling_device *of_devfreq_cooling_register_power(struct device_node *np, struct devfreq *df, struct devfreq_cooling_power *dfc_power);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff817a61e0)
Location: drivers/thermal/devfreq_cooling.c:505
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_register
```
**Symbols:**

```
ffffffff817a61e0-ffffffff817a6619: of_devfreq_cooling_register_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct thermal_cooling_device *of_devfreq_cooling_register_power(struct device_node *np, struct devfreq *df, struct devfreq_cooling_power *dfc_power);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff817edc60)
Location: drivers/thermal/devfreq_cooling.c:505
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_register
```
**Symbols:**

```
ffffffff817edc60-ffffffff817ee085: of_devfreq_cooling_register_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct thermal_cooling_device *of_devfreq_cooling_register_power(struct device_node *np, struct devfreq *df, struct devfreq_cooling_power *dfc_power);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff81819b30)
Location: drivers/thermal/devfreq_cooling.c:505
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_register
```
**Symbols:**

```
ffffffff81819b30-ffffffff81819f57: of_devfreq_cooling_register_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct thermal_cooling_device *of_devfreq_cooling_register_power(struct device_node *np, struct devfreq *df, struct devfreq_cooling_power *dfc_power);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (0)
Location: drivers/thermal/devfreq_cooling.c:505
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_register
```
**Symbols:**

```
ffffffff8185c10b-ffffffff8185c13a: of_devfreq_cooling_register_power.cold (STB_LOCAL)
ffffffff8185bce0-ffffffff8185c09e: of_devfreq_cooling_register_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct thermal_cooling_device *of_devfreq_cooling_register_power(struct device_node *np, struct devfreq *df, struct devfreq_cooling_power *dfc_power);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (0)
Location: drivers/thermal/devfreq_cooling.c:505
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_register
```
**Symbols:**

```
ffffffff8188dc1b-ffffffff8188dc4a: of_devfreq_cooling_register_power.cold (STB_LOCAL)
ffffffff8188d7f0-ffffffff8188dbae: of_devfreq_cooling_register_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct thermal_cooling_device *of_devfreq_cooling_register_power(struct device_node *np, struct devfreq *df, struct devfreq_cooling_power *dfc_power);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (0)
Location: drivers/thermal/devfreq_cooling.c:471
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_register
```
**Symbols:**

```
ffffffff8195c7c9-ffffffff8195c7f3: of_devfreq_cooling_register_power.cold (STB_LOCAL)
ffffffff8195c3e0-ffffffff8195c554: of_devfreq_cooling_register_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct thermal_cooling_device *of_devfreq_cooling_register_power(struct device_node *np, struct devfreq *df, struct devfreq_cooling_power *dfc_power);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (0)
Location: drivers/thermal/devfreq_cooling.c:360
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_register
```
**Symbols:**

```
ffffffff81c25d78-ffffffff81c25da0: of_devfreq_cooling_register_power.cold (STB_LOCAL)
ffffffff81962b00-ffffffff81962ccd: of_devfreq_cooling_register_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct thermal_cooling_device *of_devfreq_cooling_register_power(struct device_node *np, struct devfreq *df, struct devfreq_cooling_power *dfc_power);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (0)
Location: drivers/thermal/devfreq_cooling.c:355
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_register
```
**Symbols:**

```
ffffffff81c17e76-ffffffff81c17e8d: of_devfreq_cooling_register_power.cold (STB_LOCAL)
ffffffff81946100-ffffffff819462b1: of_devfreq_cooling_register_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct thermal_cooling_device *of_devfreq_cooling_register_power(struct device_node *np, struct devfreq *df, struct devfreq_cooling_power *dfc_power);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (0)
Location: drivers/thermal/devfreq_cooling.c:355
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_register
```
**Symbols:**

```
ffffffff81d270a4-ffffffff81d270bb: of_devfreq_cooling_register_power.cold (STB_LOCAL)
ffffffff819eab10-ffffffff819eacbe: of_devfreq_cooling_register_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct thermal_cooling_device *of_devfreq_cooling_register_power(struct device_node *np, struct devfreq *df, struct devfreq_cooling_power *dfc_power);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (0)
Location: drivers/thermal/devfreq_cooling.c:366
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_em_register
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_register
```
**Symbols:**

```
ffffffff81ef2ee9-ffffffff81ef2eff: of_devfreq_cooling_register_power.cold (STB_LOCAL)
ffffffff81b50940-ffffffff81b50b2e: of_devfreq_cooling_register_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct thermal_cooling_device *of_devfreq_cooling_register_power(struct device_node *np, struct devfreq *df, struct devfreq_cooling_power *dfc_power);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff81ce88f0)
Location: drivers/thermal/devfreq_cooling.c:362
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_em_register
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_register
```
**Symbols:**

```
ffffffff81ce88f0-ffffffff81ce8acd: of_devfreq_cooling_register_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct thermal_cooling_device *of_devfreq_cooling_register_power(struct device_node *np, struct devfreq *df, struct devfreq_cooling_power *dfc_power);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff81d510b0)
Location: drivers/thermal/devfreq_cooling.c:362
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_em_register
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_register
```
**Symbols:**

```
ffffffff81d510b0-ffffffff81d5128d: of_devfreq_cooling_register_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct thermal_cooling_device *of_devfreq_cooling_register_power(struct device_node *np, struct devfreq *df, struct devfreq_cooling_power *dfc_power);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff81e07e00)
Location: drivers/thermal/devfreq_cooling.c:362
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_em_register
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_register
```
**Symbols:**

```
ffffffff81e07e00-ffffffff81e0800d: of_devfreq_cooling_register_power (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct thermal_cooling_device *of_devfreq_cooling_register_power(struct device_node *np, struct devfreq *df, struct devfreq_cooling_power *dfc_power);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffff800010add0d0)
Location: drivers/thermal/devfreq_cooling.c:505
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_register
```
**Symbols:**

```
ffff800010add0d0-ffff800010add4e4: of_devfreq_cooling_register_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct thermal_cooling_device *of_devfreq_cooling_register_power(struct device_node *np, struct devfreq *df, struct devfreq_cooling_power *dfc_power);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (c0bbd630)
Location: drivers/thermal/devfreq_cooling.c:505
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_register
```
**Symbols:**

```
c0bbd630-c0bbd9ac: of_devfreq_cooling_register_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct thermal_cooling_device *of_devfreq_cooling_register_power(struct device_node *np, struct devfreq *df, struct devfreq_cooling_power *dfc_power);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (c000000000bc5900)
Location: drivers/thermal/devfreq_cooling.c:505
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_register
```
**Symbols:**

```
c000000000bc5900-c000000000bc5e74: of_devfreq_cooling_register_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct thermal_cooling_device *of_devfreq_cooling_register_power(struct device_node *np, struct devfreq *df, struct devfreq_cooling_power *dfc_power);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffe0006d638c)
Location: drivers/thermal/devfreq_cooling.c:505
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_register
```
**Symbols:**

```
ffffffe0006d638c-ffffffe0006d6702: of_devfreq_cooling_register_power (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
struct thermal_cooling_device *of_devfreq_cooling_register_power(struct device_node *np, struct devfreq *df, struct devfreq_cooling_power *dfc_power);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (0)
Location: drivers/thermal/devfreq_cooling.c:505
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_register
```
**Symbols:**

```
ffffffff81833a9b-ffffffff81833aca: of_devfreq_cooling_register_power.cold (STB_LOCAL)
ffffffff81833670-ffffffff81833a2e: of_devfreq_cooling_register_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct thermal_cooling_device *of_devfreq_cooling_register_power(struct device_node *np, struct devfreq *df, struct devfreq_cooling_power *dfc_power);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (0)
Location: drivers/thermal/devfreq_cooling.c:505
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_register
```
**Symbols:**

```
ffffffff817fb12b-ffffffff817fb15a: of_devfreq_cooling_register_power.cold (STB_LOCAL)
ffffffff817fad00-ffffffff817fb0be: of_devfreq_cooling_register_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct thermal_cooling_device *of_devfreq_cooling_register_power(struct device_node *np, struct devfreq *df, struct devfreq_cooling_power *dfc_power);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (0)
Location: drivers/thermal/devfreq_cooling.c:505
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_register
```
**Symbols:**

```
ffffffff818830cb-ffffffff818830fa: of_devfreq_cooling_register_power.cold (STB_LOCAL)
ffffffff81882ca0-ffffffff8188305e: of_devfreq_cooling_register_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct thermal_cooling_device *of_devfreq_cooling_register_power(struct device_node *np, struct devfreq *df, struct devfreq_cooling_power *dfc_power);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (0)
Location: drivers/thermal/devfreq_cooling.c:505
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_register
```
**Symbols:**

```
ffffffff8189eb8b-ffffffff8189ebba: of_devfreq_cooling_register_power.cold (STB_LOCAL)
ffffffff8189e760-ffffffff8189eb1e: of_devfreq_cooling_register_power (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
