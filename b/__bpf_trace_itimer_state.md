# Function: <code>__bpf_trace_itimer_state</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __bpf_trace_itimer_state(void *__data, int which, const const struct itimerval * value, long long unsigned int expires);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81112d30)
Location: include/trace/events/timer.h:299
Inline: False
```
**Symbols:**

```
ffffffff81112d30-ffffffff81112d3d: __bpf_trace_itimer_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __bpf_trace_itimer_state(void *__data, int which, const const struct itimerval * value, long long unsigned int expires);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8111e510)
Location: include/trace/events/timer.h:299
Inline: False
```
**Symbols:**

```
ffffffff8111e510-ffffffff8111e51d: __bpf_trace_itimer_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_itimer_state(void *__data, int which, const const struct itimerval * value, long long unsigned int expires);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81129190)
Location: include/trace/events/timer.h:304
Inline: False
```
**Symbols:**

```
ffffffff81129190-ffffffff8112919d: __bpf_trace_itimer_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_itimer_state(void *__data, int which, const const struct itimerval * value, long long unsigned int expires);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81135130)
Location: include/trace/events/timer.h:304
Inline: False
```
**Symbols:**

```
ffffffff81135130-ffffffff8113513d: __bpf_trace_itimer_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_itimer_state(void *__data, int which, const const struct itimerspec64 * value, long long unsigned int expires);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81143e20)
Location: include/trace/events/timer.h:304
Inline: True
```
**Symbols:**

```
ffffffff81143e20-ffffffff81143e2d: __bpf_trace_itimer_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_itimer_state(void *__data, int which, const const struct itimerspec64 * value, long long unsigned int expires);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81140490)
Location: include/trace/events/timer.h:304
Inline: True
```
**Symbols:**

```
ffffffff81140490-ffffffff8114049d: __bpf_trace_itimer_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_itimer_state(void *__data, int which, const const struct itimerspec64 * value, long long unsigned int expires);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81141670)
Location: include/trace/events/timer.h:304
Inline: True
```
**Symbols:**

```
ffffffff81141670-ffffffff8114167d: __bpf_trace_itimer_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_itimer_state(void *__data, int which, const const struct itimerspec64 * value, long long unsigned int expires);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81164b30)
Location: include/trace/events/timer.h:304
Inline: True
```
**Symbols:**

```
ffffffff81164b30-ffffffff81164b3d: __bpf_trace_itimer_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_itimer_state(void *__data, int which, const const struct itimerspec64 * value, long long unsigned int expires);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811985a0)
Location: include/trace/events/timer.h:307
Inline: True
```
**Symbols:**

```
ffffffff811985a0-ffffffff811985b9: __bpf_trace_itimer_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_itimer_state(void *__data, int which, const const struct itimerspec64 * value, long long unsigned int expires);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811d68a0)
Location: include/trace/events/timer.h:307
Inline: True
```
**Symbols:**

```
ffffffff811d68a0-ffffffff811d68b9: __bpf_trace_itimer_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_itimer_state(void *__data, int which, const const struct itimerspec64 * value, long long unsigned int expires);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811eac90)
Location: include/trace/events/timer.h:311
Inline: True
```
**Symbols:**

```
ffffffff811eac90-ffffffff811eaca9: __bpf_trace_itimer_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_itimer_state(void *__data, int which, const const struct itimerspec64 * value, long long unsigned int expires);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81200ca0)
Location: include/trace/events/timer.h:331
Inline: True
```
**Symbols:**

```
ffffffff81200ca0-ffffffff81200cb9: __bpf_trace_itimer_state (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void __bpf_trace_itimer_state(void *__data, int which, const const struct itimerval * value, long long unsigned int expires);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffff80001019cbc8)
Location: include/trace/events/timer.h:304
Inline: False
```
**Symbols:**

```
ffff80001019cbc8-ffff80001019cbe0: __bpf_trace_itimer_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_itimer_state(void *__data, int which, const const struct itimerval * value, long long unsigned int expires);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c03e7354)
Location: include/trace/events/timer.h:304
Inline: False
```
**Symbols:**

```
c03e7354-c03e738c: __bpf_trace_itimer_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_itimer_state(void *__data, int which, const const struct itimerval * value, long long unsigned int expires);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c0000000001fdf30)
Location: include/trace/events/timer.h:304
Inline: False
```
**Symbols:**

```
c0000000001fdf30-c0000000001fdf60: __bpf_trace_itimer_state (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void __bpf_trace_itimer_state(void *__data, int which, const const struct itimerval * value, long long unsigned int expires);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8112d8e0)
Location: include/trace/events/timer.h:304
Inline: False
```
**Symbols:**

```
ffffffff8112d8e0-ffffffff8112d8ed: __bpf_trace_itimer_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_itimer_state(void *__data, int which, const const struct itimerval * value, long long unsigned int expires);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81120150)
Location: include/trace/events/timer.h:304
Inline: False
```
**Symbols:**

```
ffffffff81120150-ffffffff8112015d: __bpf_trace_itimer_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_itimer_state(void *__data, int which, const const struct itimerval * value, long long unsigned int expires);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8112b600)
Location: include/trace/events/timer.h:304
Inline: False
```
**Symbols:**

```
ffffffff8112b600-ffffffff8112b60d: __bpf_trace_itimer_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_itimer_state(void *__data, int which, const const struct itimerval * value, long long unsigned int expires);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81137a10)
Location: include/trace/events/timer.h:304
Inline: False
```
**Symbols:**

```
ffffffff81137a10-ffffffff81137a1d: __bpf_trace_itimer_state (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const const struct itimerval * value</code> ➡️ <code>const const struct itimerspec64 * value</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
