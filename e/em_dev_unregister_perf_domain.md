# Function: <code>em_dev_unregister_perf_domain</code>

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
void em_dev_unregister_perf_domain(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/energy_model.c (ffffffff81117400)
Location: kernel/power/energy_model.c:353
Inline: True
```
**Symbols:**

```
ffffffff81117400-ffffffff81117498: em_dev_unregister_perf_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void em_dev_unregister_perf_domain(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/energy_model.c (ffffffff811179c0)
Location: kernel/power/energy_model.c:353
Inline: True
```
**Symbols:**

```
ffffffff811179c0-ffffffff81117a58: em_dev_unregister_perf_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void em_dev_unregister_perf_domain(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/energy_model.c (ffffffff81137d20)
Location: kernel/power/energy_model.c:348
Inline: True
```
**Symbols:**

```
ffffffff81137d20-ffffffff81137db8: em_dev_unregister_perf_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void em_dev_unregister_perf_domain(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/energy_model.c (ffffffff8115a3a0)
Location: kernel/power/energy_model.c:420
Inline: True
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_unregister
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_em_register
```
**Symbols:**

```
ffffffff8115a3a0-ffffffff8115a44c: em_dev_unregister_perf_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void em_dev_unregister_perf_domain(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/energy_model.c (ffffffff8118c720)
Location: kernel/power/energy_model.c:417
Inline: True
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_unregister
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_em_register
```
**Symbols:**

```
ffffffff8118c720-ffffffff8118c7c4: em_dev_unregister_perf_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void em_dev_unregister_perf_domain(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/energy_model.c (ffffffff8119de40)
Location: kernel/power/energy_model.c:417
Inline: True
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_unregister
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_em_register
```
**Symbols:**

```
ffffffff8119de40-ffffffff8119dee4: em_dev_unregister_perf_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void em_dev_unregister_perf_domain(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/energy_model.c (ffffffff811acfb0)
Location: kernel/power/energy_model.c:417
Inline: True
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_unregister
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_em_register
```
**Symbols:**

```
ffffffff811acfb0-ffffffff811ad054: em_dev_unregister_perf_domain (STB_GLOBAL)
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
