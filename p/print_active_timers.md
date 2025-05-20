# Function: <code>print_active_timers</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void print_active_timers(struct seq_file *m, struct hrtimer_clock_base *base, u64 now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffffffff810f8d40)
Location: kernel/time/timer_list.c:89
Inline: False
Direct callers:
  - kernel/time/timer_list.c:print_cpu
```
**Symbols:**

```
ffffffff810f8d40-ffffffff810f8fa4: print_active_timers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void print_active_timers(struct seq_file *m, struct hrtimer_clock_base *base, u64 now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffffffff810fffc0)
Location: kernel/time/timer_list.c:89
Inline: False
Direct callers:
  - kernel/time/timer_list.c:print_cpu
```
**Symbols:**

```
ffffffff810fffc0-ffffffff81100224: print_active_timers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void print_active_timers(struct seq_file *m, struct hrtimer_clock_base *base, u64 now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffffffff81102dc0)
Location: kernel/time/timer_list.c:89
Inline: False
Direct callers:
  - kernel/time/timer_list.c:print_cpu
```
**Symbols:**

```
ffffffff81102dc0-ffffffff81102fc1: print_active_timers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffffffff8110500f)
Location: kernel/time/timer_list.c:80
Inline: True
Inline callers:
  - kernel/time/timer_list.c:print_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffffffff8111016f)
Location: kernel/time/timer_list.c:80
Inline: True
Inline callers:
  - kernel/time/timer_list.c:print_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffffffff8111bc15)
Location: kernel/time/timer_list.c:78
Inline: True
Inline callers:
  - kernel/time/timer_list.c:print_cpu
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
In kernel/time/timer_list.c (ffffffff811273c5)
Location: kernel/time/timer_list.c:73
Inline: True
Inline callers:
  - kernel/time/timer_list.c:print_cpu
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
In kernel/time/timer_list.c (ffffffff81131e07)
Location: kernel/time/timer_list.c:73
Inline: True
Inline callers:
  - kernel/time/timer_list.c:print_cpu
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
In kernel/time/timer_list.c (ffffffff8113dd57)
Location: kernel/time/timer_list.c:73
Inline: True
Inline callers:
  - kernel/time/timer_list.c:print_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void print_active_timers(struct seq_file *m, struct hrtimer_clock_base *base, u64 now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffffffff8114cdd0)
Location: kernel/time/timer_list.c:73
Inline: False
Direct callers:
  - kernel/time/timer_list.c:print_base
```
**Symbols:**

```
ffffffff8114cdd0-ffffffff8114cf43: print_active_timers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void print_active_timers(struct seq_file *m, struct hrtimer_clock_base *base, u64 now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffffffff81149010)
Location: kernel/time/timer_list.c:60
Inline: False
Direct callers:
  - kernel/time/timer_list.c:print_cpu
```
**Symbols:**

```
ffffffff81149010-ffffffff81149164: print_active_timers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffffffff8114a607)
Location: kernel/time/timer_list.c:60
Inline: True
Inline callers:
  - kernel/time/timer_list.c:print_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffffffff8116e315)
Location: kernel/time/timer_list.c:60
Inline: True
Inline callers:
  - kernel/time/timer_list.c:print_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffffffff811a25c9)
Location: kernel/time/timer_list.c:60
Inline: True
Inline callers:
  - kernel/time/timer_list.c:print_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffffffff811e1b19)
Location: kernel/time/timer_list.c:60
Inline: True
Inline callers:
  - kernel/time/timer_list.c:print_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffffffff811f6079)
Location: kernel/time/timer_list.c:60
Inline: True
Inline callers:
  - kernel/time/timer_list.c:print_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffffffff8120c219)
Location: kernel/time/timer_list.c:60
Inline: True
Inline callers:
  - kernel/time/timer_list.c:print_cpu
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
void print_active_timers(struct seq_file *m, struct hrtimer_clock_base *base, u64 now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffff8000101a7b50)
Location: kernel/time/timer_list.c:73
Inline: False
Direct callers:
  - kernel/time/timer_list.c:print_cpu
```
**Symbols:**

```
ffff8000101a7b50-ffff8000101a7d0c: print_active_timers (STB_LOCAL)
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
In kernel/time/timer_list.c (c03f2ce4)
Location: kernel/time/timer_list.c:73
Inline: True
Inline callers:
  - kernel/time/timer_list.c:print_cpu
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
In kernel/time/timer_list.c (c00000000020a724)
Location: kernel/time/timer_list.c:73
Inline: True
Inline callers:
  - kernel/time/timer_list.c:print_cpu
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
In kernel/time/timer_list.c (ffffffe000133798)
Location: kernel/time/timer_list.c:73
Inline: True
Inline callers:
  - kernel/time/timer_list.c:print_cpu
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
In kernel/time/timer_list.c (ffffffff81136507)
Location: kernel/time/timer_list.c:73
Inline: True
Inline callers:
  - kernel/time/timer_list.c:print_cpu
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
In kernel/time/timer_list.c (ffffffff81128f57)
Location: kernel/time/timer_list.c:73
Inline: True
Inline callers:
  - kernel/time/timer_list.c:print_cpu
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
In kernel/time/timer_list.c (ffffffff81134227)
Location: kernel/time/timer_list.c:73
Inline: True
Inline callers:
  - kernel/time/timer_list.c:print_cpu
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
In kernel/time/timer_list.c (ffffffff81140c47)
Location: kernel/time/timer_list.c:73
Inline: True
Inline callers:
  - kernel/time/timer_list.c:print_cpu
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
