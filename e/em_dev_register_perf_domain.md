# Function: <code>em_dev_register_perf_domain</code>

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
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int em_dev_register_perf_domain(struct device *dev, unsigned int nr_states, struct em_data_callback *cb, cpumask_t *cpus, bool milliwatts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/energy_model.c (0)
Location: kernel/power/energy_model.c:281
Inline: False
```
**Symbols:**

```
ffffffff81be10c1-ffffffff81be10f5: em_dev_register_perf_domain.cold (STB_LOCAL)
ffffffff811177a0-ffffffff811178bc: em_dev_register_perf_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int em_dev_register_perf_domain(struct device *dev, unsigned int nr_states, struct em_data_callback *cb, cpumask_t *cpus, bool milliwatts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/energy_model.c (0)
Location: kernel/power/energy_model.c:281
Inline: False
```
**Symbols:**

```
ffffffff81bd312e-ffffffff81bd3176: em_dev_register_perf_domain.cold (STB_LOCAL)
ffffffff81117d60-ffffffff81117fb6: em_dev_register_perf_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int em_dev_register_perf_domain(struct device *dev, unsigned int nr_states, struct em_data_callback *cb, cpumask_t *cpus, bool milliwatts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/energy_model.c (0)
Location: kernel/power/energy_model.c:276
Inline: False
```
**Symbols:**

```
ffffffff81cabf7a-ffffffff81cabfc2: em_dev_register_perf_domain.cold (STB_LOCAL)
ffffffff811380c0-ffffffff81138316: em_dev_register_perf_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int em_dev_register_perf_domain(struct device *dev, unsigned int nr_states, struct em_data_callback *cb, cpumask_t *cpus, bool microwatts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/energy_model.c (0)
Location: kernel/power/energy_model.c:340
Inline: False
```
**Symbols:**

```
ffffffff81e5c441-ffffffff81e5c4a0: em_dev_register_perf_domain.cold (STB_LOCAL)
ffffffff8115a820-ffffffff8115ab85: em_dev_register_perf_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int em_dev_register_perf_domain(struct device *dev, unsigned int nr_states, struct em_data_callback *cb, cpumask_t *cpus, bool microwatts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/energy_model.c (ffffffff8118cc70)
Location: kernel/power/energy_model.c:337
Inline: False
```
**Symbols:**

```
ffffffff8118cc70-ffffffff8118d063: em_dev_register_perf_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int em_dev_register_perf_domain(struct device *dev, unsigned int nr_states, struct em_data_callback *cb, cpumask_t *cpus, bool microwatts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/energy_model.c (ffffffff8119e410)
Location: kernel/power/energy_model.c:337
Inline: False
```
**Symbols:**

```
ffffffff8119e410-ffffffff8119e802: em_dev_register_perf_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int em_dev_register_perf_domain(struct device *dev, unsigned int nr_states, struct em_data_callback *cb, cpumask_t *cpus, bool microwatts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/energy_model.c (ffffffff811ad5d0)
Location: kernel/power/energy_model.c:337
Inline: False
```
**Symbols:**

```
ffffffff811ad5d0-ffffffff811ad9c2: em_dev_register_perf_domain (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool microwatts</code>
</li>
<li>
<b>Param removed. </b>
<code>bool milliwatts</code>
</li>
</ul>
</details>
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
