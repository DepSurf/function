# Function: <code>__traceiter_device_pm_callback_start</code>

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
int __traceiter_device_pm_callback_start(void *__data, struct device *dev, const char *pm_ops, int event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/power-traces.c (ffffffff811ecbe0)
Location: include/trace/events/power.h:176
Inline: False
```
**Symbols:**

```
ffffffff811ecbe0-ffffffff811ecc2c: __traceiter_device_pm_callback_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_device_pm_callback_start(void *__data, struct device *dev, const char *pm_ops, int event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/power-traces.c (ffffffff811edb80)
Location: include/trace/events/power.h:176
Inline: False
```
**Symbols:**

```
ffffffff811edb80-ffffffff811edbca: __traceiter_device_pm_callback_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_device_pm_callback_start(void *__data, struct device *dev, const char *pm_ops, int event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/power-traces.c (ffffffff8121ebf0)
Location: include/trace/events/power.h:176
Inline: False
```
**Symbols:**

```
ffffffff8121ebf0-ffffffff8121ec3a: __traceiter_device_pm_callback_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_device_pm_callback_start(void *__data, struct device *dev, const char *pm_ops, int event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/power-traces.c (ffffffff8125e300)
Location: include/trace/events/power.h:176
Inline: False
```
**Symbols:**

```
ffffffff8125e300-ffffffff8125e356: __traceiter_device_pm_callback_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_device_pm_callback_start(void *__data, struct device *dev, const char *pm_ops, int event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/power-traces.c (ffffffff812aeee0)
Location: include/trace/events/power.h:198
Inline: False
```
**Symbols:**

```
ffffffff812aeee0-ffffffff812aef36: __traceiter_device_pm_callback_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_device_pm_callback_start(void *__data, struct device *dev, const char *pm_ops, int event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/power-traces.c (ffffffff812d14c0)
Location: include/trace/events/power.h:198
Inline: False
```
**Symbols:**

```
ffffffff812d14c0-ffffffff812d1516: __traceiter_device_pm_callback_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_device_pm_callback_start(void *__data, struct device *dev, const char *pm_ops, int event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/power-traces.c (ffffffff812eefc0)
Location: include/trace/events/power.h:198
Inline: False
```
**Symbols:**

```
ffffffff812eefc0-ffffffff812ef016: __traceiter_device_pm_callback_start (STB_GLOBAL)
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
