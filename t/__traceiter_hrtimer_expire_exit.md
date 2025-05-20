# Function: <code>__traceiter_hrtimer_expire_exit</code>

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
int __traceiter_hrtimer_expire_exit(void *__data, struct hrtimer *hrtimer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8113f1e0)
Location: include/trace/events/timer.h:279
Inline: False
```
**Symbols:**

```
ffffffff8113f1e0-ffffffff8113f21d: __traceiter_hrtimer_expire_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_hrtimer_expire_exit(void *__data, struct hrtimer *hrtimer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811403f0)
Location: include/trace/events/timer.h:279
Inline: False
```
**Symbols:**

```
ffffffff811403f0-ffffffff8114042b: __traceiter_hrtimer_expire_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_hrtimer_expire_exit(void *__data, struct hrtimer *hrtimer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81163880)
Location: include/trace/events/timer.h:279
Inline: False
```
**Symbols:**

```
ffffffff81163880-ffffffff811638bb: __traceiter_hrtimer_expire_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_hrtimer_expire_exit(void *__data, struct hrtimer *hrtimer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81196950)
Location: include/trace/events/timer.h:282
Inline: False
```
**Symbols:**

```
ffffffff81196950-ffffffff81196993: __traceiter_hrtimer_expire_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_hrtimer_expire_exit(void *__data, struct hrtimer *hrtimer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811d4a10)
Location: include/trace/events/timer.h:282
Inline: False
```
**Symbols:**

```
ffffffff811d4a10-ffffffff811d4a53: __traceiter_hrtimer_expire_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_hrtimer_expire_exit(void *__data, struct hrtimer *hrtimer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811e8dc0)
Location: include/trace/events/timer.h:286
Inline: False
```
**Symbols:**

```
ffffffff811e8dc0-ffffffff811e8e03: __traceiter_hrtimer_expire_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_hrtimer_expire_exit(void *__data, struct hrtimer *hrtimer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811feb40)
Location: include/trace/events/timer.h:306
Inline: False
```
**Symbols:**

```
ffffffff811feb40-ffffffff811feb83: __traceiter_hrtimer_expire_exit (STB_GLOBAL)
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
