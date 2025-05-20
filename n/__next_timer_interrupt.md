# Function: <code>__next_timer_interrupt</code>

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
In kernel/time/timer.c (ffffffff810ee6dc)
Location: kernel/time/timer.c:1269
Inline: True
Inline callers:
  - kernel/time/timer.c:get_next_timer_interrupt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int __next_timer_interrupt(struct timer_base *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810f3820)
Location: kernel/time/timer.c:1393
Inline: False
Direct callers:
  - kernel/time/timer.c:get_next_timer_interrupt
```
**Symbols:**

```
ffffffff810f3820-ffffffff810f38f4: __next_timer_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int __next_timer_interrupt(struct timer_base *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810fab70)
Location: kernel/time/timer.c:1403
Inline: False
Direct callers:
  - kernel/time/timer.c:get_next_timer_interrupt
```
**Symbols:**

```
ffffffff810fab70-ffffffff810fac44: __next_timer_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int __next_timer_interrupt(struct timer_base *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810fcf50)
Location: kernel/time/timer.c:1375
Inline: False
Direct callers:
  - kernel/time/timer.c:get_next_timer_interrupt
```
**Symbols:**

```
ffffffff810fcf50-ffffffff810fd023: __next_timer_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int __next_timer_interrupt(struct timer_base *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81107850)
Location: kernel/time/timer.c:1410
Inline: False
Direct callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:get_next_timer_interrupt
```
**Symbols:**

```
ffffffff81107850-ffffffff81107923: __next_timer_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int __next_timer_interrupt(struct timer_base *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81112e00)
Location: kernel/time/timer.c:1418
Inline: False
Direct callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:get_next_timer_interrupt
```
**Symbols:**

```
ffffffff81112e00-ffffffff81112eca: __next_timer_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int __next_timer_interrupt(struct timer_base *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8111e5e0)
Location: kernel/time/timer.c:1417
Inline: False
Direct callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:get_next_timer_interrupt
```
**Symbols:**

```
ffffffff8111e5e0-ffffffff8111e6aa: __next_timer_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int __next_timer_interrupt(struct timer_base *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811292b0)
Location: kernel/time/timer.c:1421
Inline: False
Direct callers:
  - kernel/time/timer.c:get_next_timer_interrupt
```
**Symbols:**

```
ffffffff811292b0-ffffffff81129385: __next_timer_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int __next_timer_interrupt(struct timer_base *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81135250)
Location: kernel/time/timer.c:1506
Inline: False
Direct callers:
  - kernel/time/timer.c:get_next_timer_interrupt
```
**Symbols:**

```
ffffffff81135250-ffffffff81135325: __next_timer_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int __next_timer_interrupt(struct timer_base *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81143e70)
Location: kernel/time/timer.c:1518
Inline: False
Direct callers:
  - kernel/time/timer.c:get_next_timer_interrupt
```
**Symbols:**

```
ffffffff81143e70-ffffffff81143f45: __next_timer_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int __next_timer_interrupt(struct timer_base *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811404e0)
Location: kernel/time/timer.c:1518
Inline: False
Direct callers:
  - kernel/time/timer.c:get_next_timer_interrupt
```
**Symbols:**

```
ffffffff811404e0-ffffffff811405e9: __next_timer_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int __next_timer_interrupt(struct timer_base *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81141700)
Location: kernel/time/timer.c:1536
Inline: False
Direct callers:
  - kernel/time/timer.c:get_next_timer_interrupt
```
**Symbols:**

```
ffffffff81141700-ffffffff8114182c: __next_timer_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int __next_timer_interrupt(struct timer_base *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81164bc0)
Location: kernel/time/timer.c:1522
Inline: False
Direct callers:
  - kernel/time/timer.c:get_next_timer_interrupt
```
**Symbols:**

```
ffffffff81164bc0-ffffffff81164cec: __next_timer_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int __next_timer_interrupt(struct timer_base *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81198740)
Location: kernel/time/timer.c:1575
Inline: False
Direct callers:
  - kernel/time/timer.c:__run_timers
  - kernel/time/timer.c:__run_timers
  - kernel/time/timer.c:get_next_timer_interrupt
```
**Symbols:**

```
ffffffff81198740-ffffffff81198871: __next_timer_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int __next_timer_interrupt(struct timer_base *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811d6bf0)
Location: kernel/time/timer.c:1807
Inline: False
Direct callers:
  - kernel/time/timer.c:__run_timers
  - kernel/time/timer.c:__run_timers
  - kernel/time/timer.c:get_next_timer_interrupt
```
**Symbols:**

```
ffffffff811d6bf0-ffffffff811d6d0e: __next_timer_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int __next_timer_interrupt(struct timer_base *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811eb010)
Location: kernel/time/timer.c:1807
Inline: False
Direct callers:
  - kernel/time/timer.c:__run_timers
  - kernel/time/timer.c:__run_timers
  - kernel/time/timer.c:get_next_timer_interrupt
```
**Symbols:**

```
ffffffff811eb010-ffffffff811eb12e: __next_timer_interrupt (STB_LOCAL)
```
</details>
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
long unsigned int __next_timer_interrupt(struct timer_base *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffff80001019cd00)
Location: kernel/time/timer.c:1506
Inline: False
Direct callers:
  - kernel/time/timer.c:get_next_timer_interrupt
```
**Symbols:**

```
ffff80001019cd00-ffff80001019cdec: __next_timer_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int __next_timer_interrupt(struct timer_base *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c03e7984)
Location: kernel/time/timer.c:1506
Inline: False
Direct callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:get_next_timer_interrupt
```
**Symbols:**

```
c03e7984-c03e7a30: __next_timer_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int __next_timer_interrupt(struct timer_base *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c0000000001fe1e0)
Location: kernel/time/timer.c:1506
Inline: False
Direct callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:get_next_timer_interrupt
```
**Symbols:**

```
c0000000001fe1e0-c0000000001fe320: __next_timer_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int __next_timer_interrupt(struct timer_base *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffe00012c0dc)
Location: kernel/time/timer.c:1506
Inline: False
Direct callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:get_next_timer_interrupt
```
**Symbols:**

```
ffffffe00012c0dc-ffffffe00012c1c0: __next_timer_interrupt (STB_LOCAL)
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
long unsigned int __next_timer_interrupt(struct timer_base *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8112da00)
Location: kernel/time/timer.c:1506
Inline: False
Direct callers:
  - kernel/time/timer.c:get_next_timer_interrupt
```
**Symbols:**

```
ffffffff8112da00-ffffffff8112dad5: __next_timer_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int __next_timer_interrupt(struct timer_base *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81120270)
Location: kernel/time/timer.c:1506
Inline: False
Direct callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:get_next_timer_interrupt
```
**Symbols:**

```
ffffffff81120270-ffffffff81120345: __next_timer_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int __next_timer_interrupt(struct timer_base *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8112b720)
Location: kernel/time/timer.c:1506
Inline: False
Direct callers:
  - kernel/time/timer.c:get_next_timer_interrupt
```
**Symbols:**

```
ffffffff8112b720-ffffffff8112b7f5: __next_timer_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int __next_timer_interrupt(struct timer_base *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81137da0)
Location: kernel/time/timer.c:1506
Inline: False
Direct callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:get_next_timer_interrupt
```
**Symbols:**

```
ffffffff81137da0-ffffffff81137e75: __next_timer_interrupt (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
