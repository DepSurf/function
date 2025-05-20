# Function: <code>__traceiter_powernv_throttle</code>

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
int __traceiter_powernv_throttle(void *__data, int chip_id, const char *reason, int pmax);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/power-traces.c (ffffffff811eca80)
Location: include/trace/events/power.h:43
Inline: False
```
**Symbols:**

```
ffffffff811eca80-ffffffff811ecacc: __traceiter_powernv_throttle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_powernv_throttle(void *__data, int chip_id, const char *reason, int pmax);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/power-traces.c (ffffffff811eda30)
Location: include/trace/events/power.h:43
Inline: False
```
**Symbols:**

```
ffffffff811eda30-ffffffff811eda7a: __traceiter_powernv_throttle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_powernv_throttle(void *__data, int chip_id, const char *reason, int pmax);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/power-traces.c (ffffffff8121eaa0)
Location: include/trace/events/power.h:43
Inline: False
```
**Symbols:**

```
ffffffff8121eaa0-ffffffff8121eaea: __traceiter_powernv_throttle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_powernv_throttle(void *__data, int chip_id, const char *reason, int pmax);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/power-traces.c (ffffffff8125e170)
Location: include/trace/events/power.h:43
Inline: False
```
**Symbols:**

```
ffffffff8125e170-ffffffff8125e1c6: __traceiter_powernv_throttle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_powernv_throttle(void *__data, int chip_id, const char *reason, int pmax);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/power-traces.c (ffffffff812aed10)
Location: include/trace/events/power.h:65
Inline: False
```
**Symbols:**

```
ffffffff812aed10-ffffffff812aed66: __traceiter_powernv_throttle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_powernv_throttle(void *__data, int chip_id, const char *reason, int pmax);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/power-traces.c (ffffffff812d1290)
Location: include/trace/events/power.h:65
Inline: False
```
**Symbols:**

```
ffffffff812d1290-ffffffff812d12e6: __traceiter_powernv_throttle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_powernv_throttle(void *__data, int chip_id, const char *reason, int pmax);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/power-traces.c (ffffffff812eed90)
Location: include/trace/events/power.h:65
Inline: False
```
**Symbols:**

```
ffffffff812eed90-ffffffff812eede6: __traceiter_powernv_throttle (STB_GLOBAL)
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
