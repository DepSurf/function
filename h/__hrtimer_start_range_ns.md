# Function: <code>__hrtimer_start_range_ns</code>

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
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81115b16)
Location: kernel/time/hrtimer.c:1070
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81121626)
Location: kernel/time/hrtimer.c:1061
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112bee6)
Location: kernel/time/hrtimer.c:1060
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81137ee5)
Location: kernel/time/hrtimer.c:1084
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __hrtimer_start_range_ns(struct hrtimer *timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode, struct hrtimer_clock_base *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81146a60)
Location: kernel/time/hrtimer.c:1084
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff81146a60-ffffffff81146cc3: __hrtimer_start_range_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __hrtimer_start_range_ns(struct hrtimer *timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode, struct hrtimer_clock_base *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81142b90)
Location: kernel/time/hrtimer.c:1101
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff81142b90-ffffffff81142ddb: __hrtimer_start_range_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __hrtimer_start_range_ns(struct hrtimer *timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode, struct hrtimer_clock_base *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811440c0)
Location: kernel/time/hrtimer.c:1101
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff811440c0-ffffffff81144301: __hrtimer_start_range_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __hrtimer_start_range_ns(struct hrtimer *timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode, struct hrtimer_clock_base *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81167890)
Location: kernel/time/hrtimer.c:1212
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff81167890-ffffffff81167bb1: __hrtimer_start_range_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __hrtimer_start_range_ns(struct hrtimer *timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode, struct hrtimer_clock_base *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8119b230)
Location: kernel/time/hrtimer.c:1212
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff8119b230-ffffffff8119b56d: __hrtimer_start_range_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __hrtimer_start_range_ns(struct hrtimer *timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode, struct hrtimer_clock_base *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811d9aa0)
Location: kernel/time/hrtimer.c:1212
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff811d9aa0-ffffffff811d9ddd: __hrtimer_start_range_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __hrtimer_start_range_ns(struct hrtimer *timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode, struct hrtimer_clock_base *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811edbd0)
Location: kernel/time/hrtimer.c:1215
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff811edbd0-ffffffff811edf33: __hrtimer_start_range_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __hrtimer_start_range_ns(struct hrtimer *timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode, struct hrtimer_clock_base *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81203f30)
Location: kernel/time/hrtimer.c:1216
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff81203f30-ffffffff81204293: __hrtimer_start_range_ns (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffff8000101a1720)
Location: kernel/time/hrtimer.c:1084
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c03eb304)
Location: kernel/time/hrtimer.c:1084
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c000000000202c74)
Location: kernel/time/hrtimer.c:1084
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffe00012ec60)
Location: kernel/time/hrtimer.c:1084
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81130695)
Location: kernel/time/hrtimer.c:1084
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81123105)
Location: kernel/time/hrtimer.c:1084
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112e3b5)
Location: kernel/time/hrtimer.c:1084
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8113ad95)
Location: kernel/time/hrtimer.c:1084
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
