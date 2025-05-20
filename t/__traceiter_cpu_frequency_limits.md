# Function: <code>__traceiter_cpu_frequency_limits</code>

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
<summary>In <code>5.11</code>: ✅</summary>

```c
int __traceiter_cpu_frequency_limits(void *__data, struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/power-traces.c (ffffffff811ecba0)
Location: include/trace/events/power.h:152
Inline: False
```
**Symbols:**

```
ffffffff811ecba0-ffffffff811ecbd8: __traceiter_cpu_frequency_limits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_cpu_frequency_limits(void *__data, struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/power-traces.c (ffffffff811edb40)
Location: include/trace/events/power.h:152
Inline: False
```
**Symbols:**

```
ffffffff811edb40-ffffffff811edb76: __traceiter_cpu_frequency_limits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_cpu_frequency_limits(void *__data, struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/power-traces.c (ffffffff8121ebb0)
Location: include/trace/events/power.h:152
Inline: False
```
**Symbols:**

```
ffffffff8121ebb0-ffffffff8121ebe6: __traceiter_cpu_frequency_limits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_cpu_frequency_limits(void *__data, struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/power-traces.c (ffffffff8125e2c0)
Location: include/trace/events/power.h:152
Inline: False
```
**Symbols:**

```
ffffffff8125e2c0-ffffffff8125e2fe: __traceiter_cpu_frequency_limits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_cpu_frequency_limits(void *__data, struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/power-traces.c (ffffffff812aee90)
Location: include/trace/events/power.h:174
Inline: False
```
**Symbols:**

```
ffffffff812aee90-ffffffff812aeece: __traceiter_cpu_frequency_limits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_cpu_frequency_limits(void *__data, struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/power-traces.c (ffffffff812d1450)
Location: include/trace/events/power.h:174
Inline: False
```
**Symbols:**

```
ffffffff812d1450-ffffffff812d148e: __traceiter_cpu_frequency_limits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_cpu_frequency_limits(void *__data, struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/power-traces.c (ffffffff812eef50)
Location: include/trace/events/power.h:174
Inline: False
```
**Symbols:**

```
ffffffff812eef50-ffffffff812eef8e: __traceiter_cpu_frequency_limits (STB_GLOBAL)
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
