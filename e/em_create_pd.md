# Function: <code>em_create_pd</code>

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
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct em_perf_domain *em_create_pd(cpumask_t *span, int nr_states, struct em_data_callback *cb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/energy_model.c (0)
Location: kernel/power/energy_model.c:81
Inline: False
```
**Symbols:**

```
ffffffff8111c9d0-ffffffff8111cbd5: em_create_pd (STB_LOCAL)
ffffffff8111cd25-ffffffff8111cd99: em_create_pd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int em_create_pd(struct device *dev, int nr_states, struct em_data_callback *cb, cpumask_t *cpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/energy_model.c (ffffffff81117670)
Location: kernel/power/energy_model.c:187
Inline: False
Direct callers:
  - kernel/power/energy_model.c:em_dev_register_perf_domain
```
**Symbols:**

```
ffffffff81117670-ffffffff81117793: em_create_pd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int em_create_pd(struct device *dev, int nr_states, struct em_data_callback *cb, cpumask_t *cpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/energy_model.c (ffffffff81117c30)
Location: kernel/power/energy_model.c:187
Inline: False
Direct callers:
  - kernel/power/energy_model.c:em_dev_register_perf_domain
```
**Symbols:**

```
ffffffff81117c30-ffffffff81117d53: em_create_pd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int em_create_pd(struct device *dev, int nr_states, struct em_data_callback *cb, cpumask_t *cpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/energy_model.c (ffffffff81137f90)
Location: kernel/power/energy_model.c:182
Inline: False
Direct callers:
  - kernel/power/energy_model.c:em_dev_register_perf_domain
```
**Symbols:**

```
ffffffff81137f90-ffffffff811380b3: em_create_pd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int em_create_pd(struct device *dev, int nr_states, struct em_data_callback *cb, cpumask_t *cpus, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/energy_model.c (0)
Location: kernel/power/energy_model.c:198
Inline: False
Direct callers:
  - kernel/power/energy_model.c:em_dev_register_perf_domain
```
**Symbols:**

```
ffffffff8115a6c0-ffffffff8115a814: em_create_pd (STB_LOCAL)
ffffffff81e5c427-ffffffff81e5c441: em_create_pd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int em_create_pd(struct device *dev, int nr_states, struct em_data_callback *cb, cpumask_t *cpus, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/energy_model.c (ffffffff8118cae0)
Location: kernel/power/energy_model.c:195
Inline: False
Direct callers:
  - kernel/power/energy_model.c:em_dev_register_perf_domain
```
**Symbols:**

```
ffffffff8118cae0-ffffffff8118cc57: em_create_pd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int em_create_pd(struct device *dev, int nr_states, struct em_data_callback *cb, cpumask_t *cpus, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/energy_model.c (0)
Location: kernel/power/energy_model.c:195
Inline: False
Direct callers:
  - kernel/power/energy_model.c:em_dev_register_perf_domain
```
**Symbols:**

```
ffffffff8119e210-ffffffff8119e3f5: em_create_pd (STB_LOCAL)
ffffffff820d70a1-ffffffff820d70cc: em_create_pd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int em_create_pd(struct device *dev, int nr_states, struct em_data_callback *cb, cpumask_t *cpus, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/energy_model.c (0)
Location: kernel/power/energy_model.c:195
Inline: False
Direct callers:
  - kernel/power/energy_model.c:em_dev_register_perf_domain
```
**Symbols:**

```
ffffffff811ad380-ffffffff811ad5b3: em_create_pd (STB_LOCAL)
ffffffff821b2338-ffffffff821b2363: em_create_pd.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct device *dev</code>
</li>
<li>
<b>Param added. </b>
<code>cpumask_t *cpus</code>
</li>
<li>
<b>Param removed. </b>
<code>cpumask_t *span</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct em_perf_domain *</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
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
