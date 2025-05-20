# Function: <code>__cpufreq_offline</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __cpufreq_offline(unsigned int cpu, struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:1583
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
```
**Symbols:**

```
ffffffff81b90740-ffffffff81b908c8: __cpufreq_offline (STB_LOCAL)
ffffffff81ef8385-ffffffff81ef839d: __cpufreq_offline.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __cpufreq_offline(unsigned int cpu, struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81d30950)
Location: drivers/cpufreq/cpufreq.c:1580
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
```
**Symbols:**

```
ffffffff81d30950-ffffffff81d30aef: __cpufreq_offline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __cpufreq_offline(unsigned int cpu, struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81d99bd0)
Location: drivers/cpufreq/cpufreq.c:1587
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
```
**Symbols:**

```
ffffffff81d99bd0-ffffffff81d99d6f: __cpufreq_offline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __cpufreq_offline(unsigned int cpu, struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81e51840)
Location: drivers/cpufreq/cpufreq.c:1628
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
```
**Symbols:**

```
ffffffff81e51840-ffffffff81e51a14: __cpufreq_offline (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
