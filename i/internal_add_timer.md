# Function: <code>internal_add_timer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void internal_add_timer(struct tvec_base *base, struct timer_list *timer);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810ec610)
Location: kernel/time/timer.c:415
Inline: True
Direct callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:migrate_timer_list
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer
```
**Symbols:**

```
ffffffff810ec610-ffffffff810ec68e: internal_add_timer (STB_LOCAL)
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
In kernel/time/timer.c (ffffffff810f593d)
Location: kernel/time/timer.c:568
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:mod_timer_pending
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
In kernel/time/timer.c (ffffffff810fc97d)
Location: kernel/time/timer.c:568
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:mod_timer_pending
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
In kernel/time/timer.c (ffffffff810fedce)
Location: kernel/time/timer.c:571
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:mod_timer_pending
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
In kernel/time/timer.c (ffffffff81109b4d)
Location: kernel/time/timer.c:571
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
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
In kernel/time/timer.c (ffffffff81115183)
Location: kernel/time/timer.c:588
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
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
In kernel/time/timer.c (ffffffff811207c3)
Location: kernel/time/timer.c:587
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
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
In kernel/time/timer.c (ffffffff8112b0aa)
Location: kernel/time/timer.c:589
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
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
In kernel/time/timer.c (ffffffff8113704a)
Location: kernel/time/timer.c:593
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81145d0f)
Location: kernel/time/timer.c:601
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:__mod_timer
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
In kernel/time/timer.c (ffffffff81142303)
Location: kernel/time/timer.c:603
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:__mod_timer
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
In kernel/time/timer.c (ffffffff811434f3)
Location: kernel/time/timer.c:605
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:__mod_timer
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
In kernel/time/timer.c (ffffffff81166ab6)
Location: kernel/time/timer.c:605
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:__mod_timer
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
In kernel/time/timer.c (ffffffff8119a1e2)
Location: kernel/time/timer.c:628
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:__mod_timer
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
In kernel/time/timer.c (ffffffff811d88ec)
Location: kernel/time/timer.c:628
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:__mod_timer
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
In kernel/time/timer.c (ffffffff811ecd14)
Location: kernel/time/timer.c:628
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:__mod_timer
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
In kernel/time/timer.c (ffffffff81202e6e)
Location: kernel/time/timer.c:625
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:__mod_timer
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
In kernel/time/timer.c (ffff8000101a036c)
Location: kernel/time/timer.c:593
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
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
In kernel/time/timer.c (c03e9ff8)
Location: kernel/time/timer.c:593
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
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
In kernel/time/timer.c (c00000000020132c)
Location: kernel/time/timer.c:593
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:add_timer
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
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
In kernel/time/timer.c (ffffffe0008c87b2)
Location: kernel/time/timer.c:593
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
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
In kernel/time/timer.c (ffffffff8112f7fa)
Location: kernel/time/timer.c:593
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
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
In kernel/time/timer.c (ffffffff8112227a)
Location: kernel/time/timer.c:593
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
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
In kernel/time/timer.c (ffffffff8112d51a)
Location: kernel/time/timer.c:593
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
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
In kernel/time/timer.c (ffffffff81139e31)
Location: kernel/time/timer.c:593
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
