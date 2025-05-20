# Function: <code>em_pd_get</code>

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
struct em_perf_domain *em_pd_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/energy_model.c (ffffffff8111789b)
Location: kernel/power/energy_model.c:230
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_dev_register_perf_domain
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
**Symbols:**

```
ffffffff81117160-ffffffff81117184: em_pd_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct em_perf_domain *em_pd_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/energy_model.c (ffffffff81117f63)
Location: kernel/power/energy_model.c:230
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_dev_register_perf_domain
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
**Symbols:**

```
ffffffff81117890-ffffffff811178b4: em_pd_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct em_perf_domain *em_pd_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/energy_model.c (ffffffff811382c3)
Location: kernel/power/energy_model.c:225
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_dev_register_perf_domain
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
**Symbols:**

```
ffffffff81137bf0-ffffffff81137c14: em_pd_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct em_perf_domain *em_pd_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/energy_model.c (ffffffff8115a947)
Location: kernel/power/energy_model.c:289
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_dev_register_perf_domain
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
**Symbols:**

```
ffffffff8115a250-ffffffff8115a280: em_pd_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct em_perf_domain *em_pd_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/energy_model.c (ffffffff8118cfb2)
Location: kernel/power/energy_model.c:286
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_dev_register_perf_domain
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
**Symbols:**

```
ffffffff8118c560-ffffffff8118c590: em_pd_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct em_perf_domain *em_pd_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/energy_model.c (ffffffff8119e751)
Location: kernel/power/energy_model.c:286
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_dev_register_perf_domain
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
**Symbols:**

```
ffffffff8119dc80-ffffffff8119dcb0: em_pd_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct em_perf_domain *em_pd_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/energy_model.c (ffffffff811ad911)
Location: kernel/power/energy_model.c:286
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_dev_register_perf_domain
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
**Symbols:**

```
ffffffff811acdf0-ffffffff811ace20: em_pd_get (STB_GLOBAL)
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
