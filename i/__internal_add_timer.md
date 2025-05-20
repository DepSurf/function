# Function: <code>__internal_add_timer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __internal_add_timer(struct tvec_base *base, struct timer_list *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810eb900)
Location: kernel/time/timer.c:374
Inline: False
Direct callers:
  - kernel/time/timer.c:cascade
```
**Symbols:**

```
ffffffff810eb900-ffffffff810eb9cc: __internal_add_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __internal_add_timer(struct timer_base *base, struct timer_list *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810f2770)
Location: kernel/time/timer.c:523
Inline: False
Direct callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:mod_timer_pending
```
**Symbols:**

```
ffffffff810f2770-ffffffff810f27c8: __internal_add_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __internal_add_timer(struct timer_base *base, struct timer_list *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810f98f0)
Location: kernel/time/timer.c:523
Inline: False
Direct callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:mod_timer_pending
```
**Symbols:**

```
ffffffff810f98f0-ffffffff810f9948: __internal_add_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __internal_add_timer(struct timer_base *base, struct timer_list *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810fbe20)
Location: kernel/time/timer.c:526
Inline: False
Direct callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:mod_timer_pending
```
**Symbols:**

```
ffffffff810fbe20-ffffffff810fbe78: __internal_add_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __internal_add_timer(struct timer_base *base, struct timer_list *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81106710)
Location: kernel/time/timer.c:526
Inline: False
Direct callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
```
**Symbols:**

```
ffffffff81106710-ffffffff81106768: __internal_add_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __internal_add_timer(struct timer_base *base, struct timer_list *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81111d60)
Location: kernel/time/timer.c:543
Inline: False
Direct callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
```
**Symbols:**

```
ffffffff81111d60-ffffffff81111db8: __internal_add_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __internal_add_timer(struct timer_base *base, struct timer_list *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8111d3a0)
Location: kernel/time/timer.c:542
Inline: False
Direct callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
```
**Symbols:**

```
ffffffff8111d3a0-ffffffff8111d3f8: __internal_add_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __internal_add_timer(struct timer_base *base, struct timer_list *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811282c0)
Location: kernel/time/timer.c:544
Inline: False
Direct callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
```
**Symbols:**

```
ffffffff811282c0-ffffffff811282f3: __internal_add_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __internal_add_timer(struct timer_base *base, struct timer_list *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81134260)
Location: kernel/time/timer.c:548
Inline: False
Direct callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
```
**Symbols:**

```
ffffffff81134260-ffffffff81134293: __internal_add_timer (STB_LOCAL)
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
Location: kernel/time/timer.c:548
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:__mod_timer
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void __internal_add_timer(struct timer_base *base, struct timer_list *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffff80001019e3b0)
Location: kernel/time/timer.c:548
Inline: False
Direct callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
```
**Symbols:**

```
ffff80001019e3b0-ffff80001019e3f4: __internal_add_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __internal_add_timer(struct timer_base *base, struct timer_list *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c03e7718)
Location: kernel/time/timer.c:548
Inline: False
Direct callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
```
**Symbols:**

```
c03e7718-c03e7754: __internal_add_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __internal_add_timer(struct timer_base *base, struct timer_list *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c0000000001fc3b0)
Location: kernel/time/timer.c:548
Inline: False
Direct callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:add_timer
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
```
**Symbols:**

```
c0000000001fc3b0-c0000000001fc410: __internal_add_timer (STB_LOCAL)
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
Location: kernel/time/timer.c:548
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
<summary>In <code>aws</code>: ✅</summary>

```c
void __internal_add_timer(struct timer_base *base, struct timer_list *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8112ca10)
Location: kernel/time/timer.c:548
Inline: False
Direct callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
```
**Symbols:**

```
ffffffff8112ca10-ffffffff8112ca43: __internal_add_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __internal_add_timer(struct timer_base *base, struct timer_list *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8111f280)
Location: kernel/time/timer.c:548
Inline: False
Direct callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
```
**Symbols:**

```
ffffffff8111f280-ffffffff8111f2b3: __internal_add_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __internal_add_timer(struct timer_base *base, struct timer_list *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8112a730)
Location: kernel/time/timer.c:548
Inline: False
Direct callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
```
**Symbols:**

```
ffffffff8112a730-ffffffff8112a763: __internal_add_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __internal_add_timer(struct timer_base *base, struct timer_list *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81137d20)
Location: kernel/time/timer.c:548
Inline: False
Direct callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
```
**Symbols:**

```
ffffffff81137d20-ffffffff81137d53: __internal_add_timer (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct tvec_base *base</code> ➡️ <code>struct timer_base *base</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
