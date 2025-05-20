# Function: <code>__traceiter_alarmtimer_fired</code>

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
int __traceiter_alarmtimer_fired(void *__data, struct alarm *alarm, ktime_t now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff81149e90)
Location: include/trace/events/alarmtimer.h:73
Inline: False
```
**Symbols:**

```
ffffffff81149e90-ffffffff81149ed7: __traceiter_alarmtimer_fired (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_alarmtimer_fired(void *__data, struct alarm *alarm, ktime_t now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8114b350)
Location: include/trace/events/alarmtimer.h:73
Inline: False
```
**Symbols:**

```
ffffffff8114b350-ffffffff8114b395: __traceiter_alarmtimer_fired (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_alarmtimer_fired(void *__data, struct alarm *alarm, ktime_t now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8116f020)
Location: include/trace/events/alarmtimer.h:73
Inline: False
```
**Symbols:**

```
ffffffff8116f020-ffffffff8116f065: __traceiter_alarmtimer_fired (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_alarmtimer_fired(void *__data, struct alarm *alarm, ktime_t now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff811a33b0)
Location: include/trace/events/alarmtimer.h:73
Inline: False
```
**Symbols:**

```
ffffffff811a33b0-ffffffff811a33ff: __traceiter_alarmtimer_fired (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_alarmtimer_fired(void *__data, struct alarm *alarm, ktime_t now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff811e29c0)
Location: include/trace/events/alarmtimer.h:73
Inline: False
```
**Symbols:**

```
ffffffff811e29c0-ffffffff811e2a0f: __traceiter_alarmtimer_fired (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_alarmtimer_fired(void *__data, struct alarm *alarm, ktime_t now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff811f6fd0)
Location: include/trace/events/alarmtimer.h:73
Inline: False
```
**Symbols:**

```
ffffffff811f6fd0-ffffffff811f701f: __traceiter_alarmtimer_fired (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_alarmtimer_fired(void *__data, struct alarm *alarm, ktime_t now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8120d170)
Location: include/trace/events/alarmtimer.h:73
Inline: False
```
**Symbols:**

```
ffffffff8120d170-ffffffff8120d1bf: __traceiter_alarmtimer_fired (STB_GLOBAL)
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
