# Function: <code>__traceiter_wakeup_source_deactivate</code>

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
int __traceiter_wakeup_source_deactivate(void *__data, const char *name, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/power-traces.c (ffffffff811ecd20)
Location: include/trace/events/power.h:275
Inline: False
```
**Symbols:**

```
ffffffff811ecd20-ffffffff811ecd62: __traceiter_wakeup_source_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_wakeup_source_deactivate(void *__data, const char *name, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/power-traces.c (ffffffff811edca0)
Location: include/trace/events/power.h:275
Inline: False
```
**Symbols:**

```
ffffffff811edca0-ffffffff811edce0: __traceiter_wakeup_source_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_wakeup_source_deactivate(void *__data, const char *name, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/power-traces.c (ffffffff8121ed10)
Location: include/trace/events/power.h:275
Inline: False
```
**Symbols:**

```
ffffffff8121ed10-ffffffff8121ed50: __traceiter_wakeup_source_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_wakeup_source_deactivate(void *__data, const char *name, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/power-traces.c (ffffffff8125e460)
Location: include/trace/events/power.h:275
Inline: False
```
**Symbols:**

```
ffffffff8125e460-ffffffff8125e4aa: __traceiter_wakeup_source_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_wakeup_source_deactivate(void *__data, const char *name, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/power-traces.c (ffffffff812af080)
Location: include/trace/events/power.h:297
Inline: False
```
**Symbols:**

```
ffffffff812af080-ffffffff812af0ca: __traceiter_wakeup_source_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_wakeup_source_deactivate(void *__data, const char *name, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/power-traces.c (ffffffff812d16e0)
Location: include/trace/events/power.h:297
Inline: False
```
**Symbols:**

```
ffffffff812d16e0-ffffffff812d172a: __traceiter_wakeup_source_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_wakeup_source_deactivate(void *__data, const char *name, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/power-traces.c (ffffffff812ef1e0)
Location: include/trace/events/power.h:297
Inline: False
```
**Symbols:**

```
ffffffff812ef1e0-ffffffff812ef22a: __traceiter_wakeup_source_deactivate (STB_GLOBAL)
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
