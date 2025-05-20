# Function: <code>__traceiter_itimer_state</code>

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
int __traceiter_itimer_state(void *__data, int which, const const struct itimerspec64 * value, long long unsigned int expires);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8113f260)
Location: include/trace/events/timer.h:304
Inline: False
```
**Symbols:**

```
ffffffff8113f260-ffffffff8113f2b1: __traceiter_itimer_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_itimer_state(void *__data, int which, const const struct itimerspec64 * value, long long unsigned int expires);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81140470)
Location: include/trace/events/timer.h:304
Inline: False
```
**Symbols:**

```
ffffffff81140470-ffffffff811404bf: __traceiter_itimer_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_itimer_state(void *__data, int which, const const struct itimerspec64 * value, long long unsigned int expires);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81163900)
Location: include/trace/events/timer.h:304
Inline: False
```
**Symbols:**

```
ffffffff81163900-ffffffff8116394f: __traceiter_itimer_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_itimer_state(void *__data, int which, const const struct itimerspec64 * value, long long unsigned int expires);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811969f0)
Location: include/trace/events/timer.h:307
Inline: False
```
**Symbols:**

```
ffffffff811969f0-ffffffff81196a4b: __traceiter_itimer_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_itimer_state(void *__data, int which, const const struct itimerspec64 * value, long long unsigned int expires);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811d4ad0)
Location: include/trace/events/timer.h:307
Inline: False
```
**Symbols:**

```
ffffffff811d4ad0-ffffffff811d4b2b: __traceiter_itimer_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_itimer_state(void *__data, int which, const const struct itimerspec64 * value, long long unsigned int expires);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811e8e80)
Location: include/trace/events/timer.h:311
Inline: False
```
**Symbols:**

```
ffffffff811e8e80-ffffffff811e8edb: __traceiter_itimer_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_itimer_state(void *__data, int which, const const struct itimerspec64 * value, long long unsigned int expires);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811fec00)
Location: include/trace/events/timer.h:331
Inline: False
```
**Symbols:**

```
ffffffff811fec00-ffffffff811fec5b: __traceiter_itimer_state (STB_GLOBAL)
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
