# Function: <code>print_base</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffffffff810f9008)
Location: kernel/time/timer_list.c:125
Inline: True
Inline callers:
  - kernel/time/timer_list.c:print_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffffffff81100288)
Location: kernel/time/timer_list.c:125
Inline: True
Inline callers:
  - kernel/time/timer_list.c:print_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffffffff81103028)
Location: kernel/time/timer_list.c:125
Inline: True
Inline callers:
  - kernel/time/timer_list.c:print_cpu
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
Location: kernel/time/timer_list.c:119
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
Location: kernel/time/timer_list.c:119
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
In kernel/time/timer_list.c (ffffffff8111bb83)
Location: kernel/time/timer_list.c:117
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
In kernel/time/timer_list.c (ffffffff81127333)
Location: kernel/time/timer_list.c:112
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
In kernel/time/timer_list.c (ffffffff81131d73)
Location: kernel/time/timer_list.c:112
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
In kernel/time/timer_list.c (ffffffff8113dcc3)
Location: kernel/time/timer_list.c:112
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
void print_base(struct seq_file *m, struct hrtimer_clock_base *base, u64 now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffffffff8114cf50)
Location: kernel/time/timer_list.c:112
Inline: False
Direct callers:
  - kernel/time/timer_list.c:print_cpu
```
**Symbols:**

```
ffffffff8114cf50-ffffffff8114d003: print_base (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffffffff811491cd)
Location: kernel/time/timer_list.c:99
Inline: True
Inline callers:
  - kernel/time/timer_list.c:print_cpu
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
In kernel/time/timer_list.c (ffffffff8114a58c)
Location: kernel/time/timer_list.c:99
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
In kernel/time/timer_list.c (ffffffff8116e29a)
Location: kernel/time/timer_list.c:99
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
In kernel/time/timer_list.c (ffffffff811a2552)
Location: kernel/time/timer_list.c:99
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
In kernel/time/timer_list.c (ffffffff811e1aa2)
Location: kernel/time/timer_list.c:99
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
In kernel/time/timer_list.c (ffffffff811f6002)
Location: kernel/time/timer_list.c:99
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
In kernel/time/timer_list.c (ffffffff8120c1a2)
Location: kernel/time/timer_list.c:99
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffff8000101a7de0)
Location: kernel/time/timer_list.c:112
Inline: True
Inline callers:
  - kernel/time/timer_list.c:print_cpu
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
In kernel/time/timer_list.c (c03f2c18)
Location: kernel/time/timer_list.c:112
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
In kernel/time/timer_list.c (c00000000020a6a4)
Location: kernel/time/timer_list.c:112
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
In kernel/time/timer_list.c (ffffffe000133790)
Location: kernel/time/timer_list.c:112
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
In kernel/time/timer_list.c (ffffffff81136473)
Location: kernel/time/timer_list.c:112
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
In kernel/time/timer_list.c (ffffffff81128ec3)
Location: kernel/time/timer_list.c:112
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
In kernel/time/timer_list.c (ffffffff81134193)
Location: kernel/time/timer_list.c:112
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
In kernel/time/timer_list.c (ffffffff81140bb3)
Location: kernel/time/timer_list.c:112
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
</ul>
