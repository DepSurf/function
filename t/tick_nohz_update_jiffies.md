# Function: <code>tick_nohz_update_jiffies</code>

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
In kernel/time/tick-sched.c (ffffffff810fecbf)
Location: kernel/time/tick-sched.c:423
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_irq_enter
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
In kernel/time/tick-sched.c (ffffffff8110605f)
Location: kernel/time/tick-sched.c:515
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_irq_enter
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
In kernel/time/tick-sched.c (ffffffff8110d7bf)
Location: kernel/time/tick-sched.c:513
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_irq_enter
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
In kernel/time/tick-sched.c (ffffffff8110f6af)
Location: kernel/time/tick-sched.c:523
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_irq_enter
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
In kernel/time/tick-sched.c (ffffffff8111a98f)
Location: kernel/time/tick-sched.c:499
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_irq_enter
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
In kernel/time/tick-sched.c (ffffffff8112770f)
Location: kernel/time/tick-sched.c:492
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_irq_enter
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
In kernel/time/tick-sched.c (ffffffff81132dff)
Location: kernel/time/tick-sched.c:489
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_irq_enter
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
In kernel/time/tick-sched.c (ffffffff8113d99f)
Location: kernel/time/tick-sched.c:498
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_irq_enter
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
In kernel/time/tick-sched.c (ffffffff8114953f)
Location: kernel/time/tick-sched.c:502
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_irq_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tick_nohz_update_jiffies(ktime_t now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81158d60)
Location: kernel/time/tick-sched.c:527
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_irq_enter
```
**Symbols:**

```
ffffffff81158d60-ffffffff81158db3: tick_nohz_update_jiffies (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tick_nohz_update_jiffies(ktime_t now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81154d60)
Location: kernel/time/tick-sched.c:575
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_irq_enter
```
**Symbols:**

```
ffffffff81154d60-ffffffff81154d9d: tick_nohz_update_jiffies (STB_LOCAL)
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
In kernel/time/tick-sched.c (ffffffff811568b3)
Location: kernel/time/tick-sched.c:576
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_irq_enter
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
In kernel/time/tick-sched.c (ffffffff8117b5d3)
Location: kernel/time/tick-sched.c:611
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_irq_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tick_nohz_update_jiffies(ktime_t now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff811afe10)
Location: kernel/time/tick-sched.c:627
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_irq_enter
```
**Symbols:**

```
ffffffff811afe10-ffffffff811afe54: tick_nohz_update_jiffies (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tick_nohz_update_jiffies(ktime_t now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff811f0860)
Location: kernel/time/tick-sched.c:627
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_irq_enter
```
**Symbols:**

```
ffffffff811f0860-ffffffff811f08b3: tick_nohz_update_jiffies (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tick_nohz_update_jiffies(ktime_t now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81205280)
Location: kernel/time/tick-sched.c:648
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_irq_enter
```
**Symbols:**

```
ffffffff81205280-ffffffff812052d3: tick_nohz_update_jiffies (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tick_nohz_update_jiffies(ktime_t now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8121b950)
Location: kernel/time/tick-sched.c:649
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_irq_enter
```
**Symbols:**

```
ffffffff8121b950-ffffffff8121b9a3: tick_nohz_update_jiffies (STB_LOCAL)
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
In kernel/time/tick-sched.c (ffff8000101b5ae8)
Location: kernel/time/tick-sched.c:502
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_irq_enter
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
In kernel/time/tick-sched.c (c03ffaa4)
Location: kernel/time/tick-sched.c:502
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_irq_enter
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
In kernel/time/tick-sched.c (c00000000021b45c)
Location: kernel/time/tick-sched.c:502
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_irq_enter
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
In kernel/time/tick-sched.c (ffffffe00013bcd2)
Location: kernel/time/tick-sched.c:502
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_irq_enter
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
In kernel/time/tick-sched.c (ffffffff81141b5f)
Location: kernel/time/tick-sched.c:502
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_irq_enter
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
In kernel/time/tick-sched.c (ffffffff81134ecf)
Location: kernel/time/tick-sched.c:502
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_irq_enter
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
In kernel/time/tick-sched.c (ffffffff8113fa0f)
Location: kernel/time/tick-sched.c:502
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_irq_enter
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
In kernel/time/tick-sched.c (ffffffff8114c53f)
Location: kernel/time/tick-sched.c:502
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_irq_enter
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
