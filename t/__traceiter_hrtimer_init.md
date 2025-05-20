# Function: <code>__traceiter_hrtimer_init</code>

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
int __traceiter_hrtimer_init(void *__data, struct hrtimer *hrtimer, clockid_t clockid, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8113f0e0)
Location: include/trace/events/timer.h:167
Inline: False
```
**Symbols:**

```
ffffffff8113f0e0-ffffffff8113f131: __traceiter_hrtimer_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_hrtimer_init(void *__data, struct hrtimer *hrtimer, clockid_t clockid, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81140300)
Location: include/trace/events/timer.h:167
Inline: False
```
**Symbols:**

```
ffffffff81140300-ffffffff8114034f: __traceiter_hrtimer_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_hrtimer_init(void *__data, struct hrtimer *hrtimer, clockid_t clockid, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81163790)
Location: include/trace/events/timer.h:167
Inline: False
```
**Symbols:**

```
ffffffff81163790-ffffffff811637df: __traceiter_hrtimer_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_hrtimer_init(void *__data, struct hrtimer *hrtimer, clockid_t clockid, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81196850)
Location: include/trace/events/timer.h:169
Inline: False
```
**Symbols:**

```
ffffffff81196850-ffffffff811968ab: __traceiter_hrtimer_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_hrtimer_init(void *__data, struct hrtimer *hrtimer, clockid_t clockid, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811d48e0)
Location: include/trace/events/timer.h:169
Inline: False
```
**Symbols:**

```
ffffffff811d48e0-ffffffff811d493b: __traceiter_hrtimer_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_hrtimer_init(void *__data, struct hrtimer *hrtimer, clockid_t clockid, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811e8c30)
Location: include/trace/events/timer.h:173
Inline: False
```
**Symbols:**

```
ffffffff811e8c30-ffffffff811e8c8b: __traceiter_hrtimer_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_hrtimer_init(void *__data, struct hrtimer *hrtimer, clockid_t clockid, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811fe9b0)
Location: include/trace/events/timer.h:193
Inline: False
```
**Symbols:**

```
ffffffff811fe9b0-ffffffff811fea0b: __traceiter_hrtimer_init (STB_GLOBAL)
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
