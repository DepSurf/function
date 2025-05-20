# Function: <code>em_debug_create_pd</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
void em_debug_create_pd(struct em_perf_domain *pd, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/energy_model.c (ffffffff8111c8a0)
Location: kernel/power/energy_model.c:52
Inline: False
Direct callers:
  - kernel/power/energy_model.c:em_create_pd
```
**Symbols:**

```
ffffffff8111c8a0-ffffffff8111c9cd: em_debug_create_pd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void em_debug_create_pd(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/energy_model.c (ffffffff81117290)
Location: kernel/power/energy_model.c:66
Inline: False
Direct callers:
  - kernel/power/energy_model.c:em_dev_register_perf_domain
```
**Symbols:**

```
ffffffff81117290-ffffffff811173f8: em_debug_create_pd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/energy_model.c (ffffffff81117e39)
Location: kernel/power/energy_model.c:66
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_dev_register_perf_domain
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/energy_model.c (ffffffff81138199)
Location: kernel/power/energy_model.c:66
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_dev_register_perf_domain
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/energy_model.c (ffffffff8115aa21)
Location: kernel/power/energy_model.c:67
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_dev_register_perf_domain
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/energy_model.c (ffffffff8118ce1b)
Location: kernel/power/energy_model.c:67
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_dev_register_perf_domain
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/energy_model.c (ffffffff8119e5bb)
Location: kernel/power/energy_model.c:67
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_dev_register_perf_domain
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/energy_model.c (ffffffff811ad77b)
Location: kernel/power/energy_model.c:67
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_dev_register_perf_domain
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
<b>Param removed. </b>
<code>struct em_perf_domain *pd</code>
</li>
<li>
<b>Param removed. </b>
<code>int cpu</code>
</li>
</ul>
</details>
</li>
</ul>
