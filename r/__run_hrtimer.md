# Function: <code>__run_hrtimer</code>

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
In kernel/time/hrtimer.c (ffffffff810ef147)
Location: kernel/time/hrtimer.c:1208
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_run_queues
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
In kernel/time/hrtimer.c (ffffffff810f622c)
Location: kernel/time/hrtimer.c:1198
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_run_queues
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
In kernel/time/hrtimer.c (ffffffff810fd24c)
Location: kernel/time/hrtimer.c:1198
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_run_queues
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
In kernel/time/hrtimer.c (ffffffff810ff5cd)
Location: kernel/time/hrtimer.c:1174
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_run_queues
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
In kernel/time/hrtimer.c (ffffffff8110a3cd)
Location: kernel/time/hrtimer.c:1179
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_run_queues
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
In kernel/time/hrtimer.c (ffffffff81115eb5)
Location: kernel/time/hrtimer.c:1358
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_run_queues
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
In kernel/time/hrtimer.c (ffffffff811212e5)
Location: kernel/time/hrtimer.c:1349
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_run_queues
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
In kernel/time/hrtimer.c (ffffffff8112baf2)
Location: kernel/time/hrtimer.c:1349
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_run_queues
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
In kernel/time/hrtimer.c (ffffffff81137b92)
Location: kernel/time/hrtimer.c:1477
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_run_queues
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __run_hrtimer(struct hrtimer_cpu_base *cpu_base, struct hrtimer_clock_base *base, struct hrtimer *timer, ktime_t *now, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81146570)
Location: kernel/time/hrtimer.c:1477
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__hrtimer_run_queues
```
**Symbols:**

```
ffffffff81146570-ffffffff81146747: __run_hrtimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __run_hrtimer(struct hrtimer_cpu_base *cpu_base, struct hrtimer_clock_base *base, struct hrtimer *timer, ktime_t *now, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81142f90)
Location: kernel/time/hrtimer.c:1494
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__hrtimer_run_queues
```
**Symbols:**

```
ffffffff81142f90-ffffffff81143136: __run_hrtimer (STB_LOCAL)
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
In kernel/time/hrtimer.c (ffffffff81143c78)
Location: kernel/time/hrtimer.c:1494
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_run_queues
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
In kernel/time/hrtimer.c (ffffffff8116734c)
Location: kernel/time/hrtimer.c:1642
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_run_queues
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
In kernel/time/hrtimer.c (ffffffff8119ace8)
Location: kernel/time/hrtimer.c:1642
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_run_queues
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
In kernel/time/hrtimer.c (ffffffff811d9388)
Location: kernel/time/hrtimer.c:1642
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_run_queues
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
In kernel/time/hrtimer.c (ffffffff811ed7f2)
Location: kernel/time/hrtimer.c:1645
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_run_queues
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
In kernel/time/hrtimer.c (ffffffff81203b52)
Location: kernel/time/hrtimer.c:1646
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_run_queues
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
In kernel/time/hrtimer.c (ffff8000101a1158)
Location: kernel/time/hrtimer.c:1477
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_run_queues
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
In kernel/time/hrtimer.c (c03eae2c)
Location: kernel/time/hrtimer.c:1477
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_run_queues
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
In kernel/time/hrtimer.c (c0000000002026ec)
Location: kernel/time/hrtimer.c:1477
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_run_queues
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
In kernel/time/hrtimer.c (ffffffe00012e85c)
Location: kernel/time/hrtimer.c:1477
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_run_queues
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
In kernel/time/hrtimer.c (ffffffff81130342)
Location: kernel/time/hrtimer.c:1477
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_run_queues
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
In kernel/time/hrtimer.c (ffffffff81122db2)
Location: kernel/time/hrtimer.c:1477
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_run_queues
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
In kernel/time/hrtimer.c (ffffffff8112e062)
Location: kernel/time/hrtimer.c:1477
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_run_queues
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
In kernel/time/hrtimer.c (ffffffff8113a9e2)
Location: kernel/time/hrtimer.c:1477
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_run_queues
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
</ul>
