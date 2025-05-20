# Function: <code>__traceiter_itimer_expire</code>

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
int __traceiter_itimer_expire(void *__data, int which, struct pid *pid, long long unsigned int now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8113f2c0)
Location: include/trace/events/timer.h:341
Inline: False
```
**Symbols:**

```
ffffffff8113f2c0-ffffffff8113f311: __traceiter_itimer_expire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_itimer_expire(void *__data, int which, struct pid *pid, long long unsigned int now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811404c0)
Location: include/trace/events/timer.h:341
Inline: False
```
**Symbols:**

```
ffffffff811404c0-ffffffff8114050f: __traceiter_itimer_expire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_itimer_expire(void *__data, int which, struct pid *pid, long long unsigned int now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81163950)
Location: include/trace/events/timer.h:341
Inline: False
```
**Symbols:**

```
ffffffff81163950-ffffffff8116399f: __traceiter_itimer_expire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_itimer_expire(void *__data, int which, struct pid *pid, long long unsigned int now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81196a50)
Location: include/trace/events/timer.h:344
Inline: False
```
**Symbols:**

```
ffffffff81196a50-ffffffff81196aab: __traceiter_itimer_expire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_itimer_expire(void *__data, int which, struct pid *pid, long long unsigned int now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811d4b40)
Location: include/trace/events/timer.h:344
Inline: False
```
**Symbols:**

```
ffffffff811d4b40-ffffffff811d4b9b: __traceiter_itimer_expire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_itimer_expire(void *__data, int which, struct pid *pid, long long unsigned int now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811e8f10)
Location: include/trace/events/timer.h:348
Inline: False
```
**Symbols:**

```
ffffffff811e8f10-ffffffff811e8f6b: __traceiter_itimer_expire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_itimer_expire(void *__data, int which, struct pid *pid, long long unsigned int now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811fec90)
Location: include/trace/events/timer.h:368
Inline: False
```
**Symbols:**

```
ffffffff811fec90-ffffffff811feceb: __traceiter_itimer_expire (STB_GLOBAL)
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
