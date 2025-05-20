# Function: <code>__traceiter_hrtimer_expire_entry</code>

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
int __traceiter_hrtimer_expire_entry(void *__data, struct hrtimer *hrtimer, ktime_t *now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8113f190)
Location: include/trace/events/timer.h:232
Inline: False
```
**Symbols:**

```
ffffffff8113f190-ffffffff8113f1d7: __traceiter_hrtimer_expire_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_hrtimer_expire_entry(void *__data, struct hrtimer *hrtimer, ktime_t *now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811403a0)
Location: include/trace/events/timer.h:232
Inline: False
```
**Symbols:**

```
ffffffff811403a0-ffffffff811403e5: __traceiter_hrtimer_expire_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_hrtimer_expire_entry(void *__data, struct hrtimer *hrtimer, ktime_t *now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81163830)
Location: include/trace/events/timer.h:232
Inline: False
```
**Symbols:**

```
ffffffff81163830-ffffffff81163875: __traceiter_hrtimer_expire_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_hrtimer_expire_entry(void *__data, struct hrtimer *hrtimer, ktime_t *now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81196900)
Location: include/trace/events/timer.h:235
Inline: False
```
**Symbols:**

```
ffffffff81196900-ffffffff8119694f: __traceiter_hrtimer_expire_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_hrtimer_expire_entry(void *__data, struct hrtimer *hrtimer, ktime_t *now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811d49b0)
Location: include/trace/events/timer.h:235
Inline: False
```
**Symbols:**

```
ffffffff811d49b0-ffffffff811d49ff: __traceiter_hrtimer_expire_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_hrtimer_expire_entry(void *__data, struct hrtimer *hrtimer, ktime_t *now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811e8d40)
Location: include/trace/events/timer.h:239
Inline: False
```
**Symbols:**

```
ffffffff811e8d40-ffffffff811e8d8f: __traceiter_hrtimer_expire_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_hrtimer_expire_entry(void *__data, struct hrtimer *hrtimer, ktime_t *now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811feac0)
Location: include/trace/events/timer.h:259
Inline: False
```
**Symbols:**

```
ffffffff811feac0-ffffffff811feb0f: __traceiter_hrtimer_expire_entry (STB_GLOBAL)
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
