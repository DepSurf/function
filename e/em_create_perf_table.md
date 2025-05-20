# Function: <code>em_create_perf_table</code>

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
int em_create_perf_table(struct device *dev, struct em_perf_domain *pd, int nr_states, struct em_data_callback *cb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/energy_model.c (0)
Location: kernel/power/energy_model.c:107
Inline: False
Direct callers:
  - kernel/power/energy_model.c:em_create_pd
```
**Symbols:**

```
ffffffff811174a0-ffffffff81117666: em_create_perf_table (STB_LOCAL)
ffffffff81be1075-ffffffff81be10c1: em_create_perf_table.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int em_create_perf_table(struct device *dev, struct em_perf_domain *pd, int nr_states, struct em_data_callback *cb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/energy_model.c (0)
Location: kernel/power/energy_model.c:107
Inline: False
Direct callers:
  - kernel/power/energy_model.c:em_create_pd
```
**Symbols:**

```
ffffffff81117a60-ffffffff81117c26: em_create_perf_table (STB_LOCAL)
ffffffff81bd30e2-ffffffff81bd312e: em_create_perf_table.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int em_create_perf_table(struct device *dev, struct em_perf_domain *pd, int nr_states, struct em_data_callback *cb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/energy_model.c (0)
Location: kernel/power/energy_model.c:107
Inline: False
Direct callers:
  - kernel/power/energy_model.c:em_create_pd
```
**Symbols:**

```
ffffffff81137dc0-ffffffff81137f8e: em_create_perf_table (STB_LOCAL)
ffffffff81cabf32-ffffffff81cabf7a: em_create_perf_table.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int em_create_perf_table(struct device *dev, struct em_perf_domain *pd, int nr_states, struct em_data_callback *cb, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/energy_model.c (0)
Location: kernel/power/energy_model.c:109
Inline: False
Direct callers:
  - kernel/power/energy_model.c:em_create_pd
```
**Symbols:**

```
ffffffff8115a450-ffffffff8115a6b3: em_create_perf_table (STB_LOCAL)
ffffffff81e5c396-ffffffff81e5c427: em_create_perf_table.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int em_create_perf_table(struct device *dev, struct em_perf_domain *pd, int nr_states, struct em_data_callback *cb, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/energy_model.c (ffffffff8118c7e0)
Location: kernel/power/energy_model.c:106
Inline: False
Direct callers:
  - kernel/power/energy_model.c:em_create_pd
```
**Symbols:**

```
ffffffff8118c7e0-ffffffff8118cad0: em_create_perf_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int em_create_perf_table(struct device *dev, struct em_perf_domain *pd, int nr_states, struct em_data_callback *cb, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/energy_model.c (ffffffff8119df00)
Location: kernel/power/energy_model.c:106
Inline: False
Direct callers:
  - kernel/power/energy_model.c:em_create_pd
```
**Symbols:**

```
ffffffff8119df00-ffffffff8119e1f8: em_create_perf_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int em_create_perf_table(struct device *dev, struct em_perf_domain *pd, int nr_states, struct em_data_callback *cb, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/energy_model.c (ffffffff811ad070)
Location: kernel/power/energy_model.c:106
Inline: False
Direct callers:
  - kernel/power/energy_model.c:em_create_pd
```
**Symbols:**

```
ffffffff811ad070-ffffffff811ad368: em_create_perf_table (STB_LOCAL)
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
<code>long unsigned int flags</code>
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
