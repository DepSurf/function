# Function: <code>__traceiter_clock_set_rate</code>

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
int __traceiter_clock_set_rate(void *__data, const char *name, unsigned int state, unsigned int cpu_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/power-traces.c (ffffffff811ece10)
Location: include/trace/events/power.h:322
Inline: False
```
**Symbols:**

```
ffffffff811ece10-ffffffff811ece5c: __traceiter_clock_set_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_clock_set_rate(void *__data, const char *name, unsigned int state, unsigned int cpu_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/power-traces.c (ffffffff811edd80)
Location: include/trace/events/power.h:322
Inline: False
```
**Symbols:**

```
ffffffff811edd80-ffffffff811eddca: __traceiter_clock_set_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_clock_set_rate(void *__data, const char *name, unsigned int state, unsigned int cpu_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/power-traces.c (ffffffff8121edf0)
Location: include/trace/events/power.h:322
Inline: False
```
**Symbols:**

```
ffffffff8121edf0-ffffffff8121ee3a: __traceiter_clock_set_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_clock_set_rate(void *__data, const char *name, unsigned int state, unsigned int cpu_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/power-traces.c (ffffffff8125e570)
Location: include/trace/events/power.h:322
Inline: False
```
**Symbols:**

```
ffffffff8125e570-ffffffff8125e5c6: __traceiter_clock_set_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_clock_set_rate(void *__data, const char *name, unsigned int state, unsigned int cpu_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/power-traces.c (ffffffff812af1c0)
Location: include/trace/events/power.h:344
Inline: False
```
**Symbols:**

```
ffffffff812af1c0-ffffffff812af216: __traceiter_clock_set_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_clock_set_rate(void *__data, const char *name, unsigned int state, unsigned int cpu_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/power-traces.c (ffffffff812d1840)
Location: include/trace/events/power.h:344
Inline: False
```
**Symbols:**

```
ffffffff812d1840-ffffffff812d1896: __traceiter_clock_set_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_clock_set_rate(void *__data, const char *name, unsigned int state, unsigned int cpu_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/power-traces.c (ffffffff812ef340)
Location: include/trace/events/power.h:344
Inline: False
```
**Symbols:**

```
ffffffff812ef340-ffffffff812ef396: __traceiter_clock_set_rate (STB_GLOBAL)
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
