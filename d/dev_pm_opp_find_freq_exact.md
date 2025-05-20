# Function: <code>dev_pm_opp_find_freq_exact</code>

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
struct dev_pm_opp *dev_pm_opp_find_freq_exact(struct device *dev, long unsigned int freq, bool available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff817d4540)
Location: drivers/opp/core.c:363
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_set_cur_state
```
**Symbols:**

```
ffffffff817d4540-ffffffff817d45f4: dev_pm_opp_find_freq_exact (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dev_pm_opp *dev_pm_opp_find_freq_exact(struct device *dev, long unsigned int freq, bool available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8181d300)
Location: drivers/opp/core.c:370
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_set_cur_state
```
**Symbols:**

```
ffffffff8181d300-ffffffff8181d3b4: dev_pm_opp_find_freq_exact (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dev_pm_opp *dev_pm_opp_find_freq_exact(struct device *dev, long unsigned int freq, bool available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818490f0)
Location: drivers/opp/core.c:354
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_set_cur_state
```
**Symbols:**

```
ffffffff818490f0-ffffffff818491a4: dev_pm_opp_find_freq_exact (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct dev_pm_opp *dev_pm_opp_find_freq_exact(struct device *dev, long unsigned int freq, bool available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:369
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_set_cur_state
```
**Symbols:**

```
ffffffff8188d61d-ffffffff8188d63d: dev_pm_opp_find_freq_exact.cold (STB_LOCAL)
ffffffff8188bfd0-ffffffff8188c063: dev_pm_opp_find_freq_exact (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct dev_pm_opp *dev_pm_opp_find_freq_exact(struct device *dev, long unsigned int freq, bool available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:369
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_set_cur_state
```
**Symbols:**

```
ffffffff818bf80b-ffffffff818bf82b: dev_pm_opp_find_freq_exact.cold (STB_LOCAL)
ffffffff818be0b0-ffffffff818be143: dev_pm_opp_find_freq_exact (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct dev_pm_opp *dev_pm_opp_find_freq_exact(struct device *dev, long unsigned int freq, bool available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:369
Inline: False
```
**Symbols:**

```
ffffffff819914bc-ffffffff819914f7: dev_pm_opp_find_freq_exact.cold (STB_LOCAL)
ffffffff8198eb80-ffffffff8198ec8c: dev_pm_opp_find_freq_exact (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct dev_pm_opp *dev_pm_opp_find_freq_exact(struct device *dev, long unsigned int freq, bool available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:369
Inline: False
```
**Symbols:**

```
ffffffff81c29236-ffffffff81c29271: dev_pm_opp_find_freq_exact.cold (STB_LOCAL)
ffffffff81992a30-ffffffff81992b3c: dev_pm_opp_find_freq_exact (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct dev_pm_opp *dev_pm_opp_find_freq_exact(struct device *dev, long unsigned int freq, bool available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:399
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
**Symbols:**

```
ffffffff81c1b32d-ffffffff81c1b368: dev_pm_opp_find_freq_exact.cold (STB_LOCAL)
ffffffff819770a0-ffffffff819771ac: dev_pm_opp_find_freq_exact (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct dev_pm_opp *dev_pm_opp_find_freq_exact(struct device *dev, long unsigned int freq, bool available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:399
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
**Symbols:**

```
ffffffff81d2b44f-ffffffff81d2b4ae: dev_pm_opp_find_freq_exact.cold (STB_LOCAL)
ffffffff81a1ffd0-ffffffff81a2011a: dev_pm_opp_find_freq_exact (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct dev_pm_opp *dev_pm_opp_find_freq_exact(struct device *dev, long unsigned int freq, bool available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:424
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
**Symbols:**

```
ffffffff81ef75ff-ffffffff81ef765e: dev_pm_opp_find_freq_exact.cold (STB_LOCAL)
ffffffff81b88b80-ffffffff81b88cd1: dev_pm_opp_find_freq_exact (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dev_pm_opp *dev_pm_opp_find_freq_exact(struct device *dev, long unsigned int freq, bool available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81d28140)
Location: drivers/opp/core.c:616
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
**Symbols:**

```
ffffffff81d28140-ffffffff81d281a9: dev_pm_opp_find_freq_exact (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dev_pm_opp *dev_pm_opp_find_freq_exact(struct device *dev, long unsigned int freq, bool available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81d912e0)
Location: drivers/opp/core.c:619
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
**Symbols:**

```
ffffffff81d912e0-ffffffff81d91349: dev_pm_opp_find_freq_exact (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dev_pm_opp *dev_pm_opp_find_freq_exact(struct device *dev, long unsigned int freq, bool available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81e489b0)
Location: drivers/opp/core.c:618
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
**Symbols:**

```
ffffffff81e489b0-ffffffff81e48a19: dev_pm_opp_find_freq_exact (STB_GLOBAL)
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
struct dev_pm_opp *dev_pm_opp_find_freq_exact(struct device *dev, long unsigned int freq, bool available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffff800010b18f08)
Location: drivers/opp/core.c:369
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_set_cur_state
```
**Symbols:**

```
ffff800010b18f08-ffff800010b18fe8: dev_pm_opp_find_freq_exact (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dev_pm_opp *dev_pm_opp_find_freq_exact(struct device *dev, long unsigned int freq, bool available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c0bf3d28)
Location: drivers/opp/core.c:369
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:get_voltage
  - drivers/thermal/devfreq_cooling.c:get_voltage
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_set_cur_state
```
**Symbols:**

```
c0bf3d28-c0bf3de8: dev_pm_opp_find_freq_exact (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dev_pm_opp *dev_pm_opp_find_freq_exact(struct device *dev, long unsigned int freq, bool available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c000000000c0a930)
Location: drivers/opp/core.c:369
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:get_voltage
  - drivers/thermal/devfreq_cooling.c:get_voltage
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_set_cur_state
```
**Symbols:**

```
c000000000c0a930-c000000000c0aa50: dev_pm_opp_find_freq_exact (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dev_pm_opp *dev_pm_opp_find_freq_exact(struct device *dev, long unsigned int freq, bool available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffe0007019d6)
Location: drivers/opp/core.c:369
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:get_voltage
  - drivers/thermal/devfreq_cooling.c:get_voltage
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_set_cur_state
```
**Symbols:**

```
ffffffe0007019d6-ffffffe000701a94: dev_pm_opp_find_freq_exact (STB_GLOBAL)
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
struct dev_pm_opp *dev_pm_opp_find_freq_exact(struct device *dev, long unsigned int freq, bool available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:369
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_set_cur_state
```
**Symbols:**

```
ffffffff81863f2b-ffffffff81863f4b: dev_pm_opp_find_freq_exact.cold (STB_LOCAL)
ffffffff818627d0-ffffffff81862863: dev_pm_opp_find_freq_exact (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct dev_pm_opp *dev_pm_opp_find_freq_exact(struct device *dev, long unsigned int freq, bool available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:369
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_set_cur_state
```
**Symbols:**

```
ffffffff8182cbdb-ffffffff8182cbfb: dev_pm_opp_find_freq_exact.cold (STB_LOCAL)
ffffffff8182b480-ffffffff8182b513: dev_pm_opp_find_freq_exact (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct dev_pm_opp *dev_pm_opp_find_freq_exact(struct device *dev, long unsigned int freq, bool available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:369
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_set_cur_state
```
**Symbols:**

```
ffffffff818b4cbb-ffffffff818b4cdb: dev_pm_opp_find_freq_exact.cold (STB_LOCAL)
ffffffff818b3560-ffffffff818b35f3: dev_pm_opp_find_freq_exact (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct dev_pm_opp *dev_pm_opp_find_freq_exact(struct device *dev, long unsigned int freq, bool available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:369
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_set_cur_state
```
**Symbols:**

```
ffffffff818d0f6b-ffffffff818d0f8b: dev_pm_opp_find_freq_exact.cold (STB_LOCAL)
ffffffff818cf810-ffffffff818cf8a3: dev_pm_opp_find_freq_exact (STB_GLOBAL)
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
