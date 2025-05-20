# Function: <code>__traceiter_cpu_idle</code>

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
int __traceiter_cpu_idle(void *__data, unsigned int state, unsigned int cpu_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/power-traces.c (ffffffff811eca30)
Location: include/trace/events/power.h:36
Inline: False
```
**Symbols:**

```
ffffffff811eca30-ffffffff811eca72: __traceiter_cpu_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_cpu_idle(void *__data, unsigned int state, unsigned int cpu_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/power-traces.c (ffffffff811ed9f0)
Location: include/trace/events/power.h:36
Inline: False
```
**Symbols:**

```
ffffffff811ed9f0-ffffffff811eda30: __traceiter_cpu_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_cpu_idle(void *__data, unsigned int state, unsigned int cpu_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/power-traces.c (ffffffff8121ea60)
Location: include/trace/events/power.h:36
Inline: False
```
**Symbols:**

```
ffffffff8121ea60-ffffffff8121eaa0: __traceiter_cpu_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_cpu_idle(void *__data, unsigned int state, unsigned int cpu_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/power-traces.c (ffffffff8125e120)
Location: include/trace/events/power.h:36
Inline: False
```
**Symbols:**

```
ffffffff8125e120-ffffffff8125e16a: __traceiter_cpu_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_cpu_idle(void *__data, unsigned int state, unsigned int cpu_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/power-traces.c (ffffffff812aec40)
Location: include/trace/events/power.h:36
Inline: False
```
**Symbols:**

```
ffffffff812aec40-ffffffff812aec8a: __traceiter_cpu_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_cpu_idle(void *__data, unsigned int state, unsigned int cpu_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/power-traces.c (ffffffff812d1180)
Location: include/trace/events/power.h:36
Inline: False
```
**Symbols:**

```
ffffffff812d1180-ffffffff812d11ca: __traceiter_cpu_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_cpu_idle(void *__data, unsigned int state, unsigned int cpu_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/power-traces.c (ffffffff812eec80)
Location: include/trace/events/power.h:36
Inline: False
```
**Symbols:**

```
ffffffff812eec80-ffffffff812eecca: __traceiter_cpu_idle (STB_GLOBAL)
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
