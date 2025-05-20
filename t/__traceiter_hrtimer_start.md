# Function: <code>__traceiter_hrtimer_start</code>

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
int __traceiter_hrtimer_start(void *__data, struct hrtimer *hrtimer, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8113f140)
Location: include/trace/events/timer.h:195
Inline: False
```
**Symbols:**

```
ffffffff8113f140-ffffffff8113f187: __traceiter_hrtimer_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_hrtimer_start(void *__data, struct hrtimer *hrtimer, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81140350)
Location: include/trace/events/timer.h:195
Inline: False
```
**Symbols:**

```
ffffffff81140350-ffffffff81140395: __traceiter_hrtimer_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_hrtimer_start(void *__data, struct hrtimer *hrtimer, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811637e0)
Location: include/trace/events/timer.h:195
Inline: False
```
**Symbols:**

```
ffffffff811637e0-ffffffff81163825: __traceiter_hrtimer_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_hrtimer_start(void *__data, struct hrtimer *hrtimer, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811968b0)
Location: include/trace/events/timer.h:198
Inline: False
```
**Symbols:**

```
ffffffff811968b0-ffffffff811968ff: __traceiter_hrtimer_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_hrtimer_start(void *__data, struct hrtimer *hrtimer, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811d4950)
Location: include/trace/events/timer.h:198
Inline: False
```
**Symbols:**

```
ffffffff811d4950-ffffffff811d499f: __traceiter_hrtimer_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_hrtimer_start(void *__data, struct hrtimer *hrtimer, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811e8cc0)
Location: include/trace/events/timer.h:202
Inline: False
```
**Symbols:**

```
ffffffff811e8cc0-ffffffff811e8d0f: __traceiter_hrtimer_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_hrtimer_start(void *__data, struct hrtimer *hrtimer, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811fea40)
Location: include/trace/events/timer.h:222
Inline: False
```
**Symbols:**

```
ffffffff811fea40-ffffffff811fea8f: __traceiter_hrtimer_start (STB_GLOBAL)
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
