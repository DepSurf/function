# Function: <code>call_timer_fn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void call_timer_fn(struct timer_list *timer, void (*fn)(long unsigned int), long unsigned int data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810ec310)
Location: kernel/time/timer.c:1153
Inline: False
Direct callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
```
**Symbols:**

```
ffffffff810ec310-ffffffff810ec42f: call_timer_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void call_timer_fn(struct timer_list *timer, void (*fn)(long unsigned int), long unsigned int data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810f39b0)
Location: kernel/time/timer.c:1273
Inline: False
```
**Symbols:**

```
ffffffff810f39b0-ffffffff810f3ac1: call_timer_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void call_timer_fn(struct timer_list *timer, void (*fn)(long unsigned int), long unsigned int data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810fad50)
Location: kernel/time/timer.c:1283
Inline: False
```
**Symbols:**

```
ffffffff810fad50-ffffffff810fae83: call_timer_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void call_timer_fn(struct timer_list *timer, void (*fn)(long unsigned int), long unsigned int data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810fd070)
Location: kernel/time/timer.c:1256
Inline: False
```
**Symbols:**

```
ffffffff810fd070-ffffffff810fd191: call_timer_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void call_timer_fn(struct timer_list *timer, void (*fn)(struct timer_list *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81107950)
Location: kernel/time/timer.c:1294
Inline: False
Direct callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
```
**Symbols:**

```
ffffffff81107950-ffffffff81107a72: call_timer_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void call_timer_fn(struct timer_list *timer, void (*fn)(struct timer_list *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81112ef0)
Location: kernel/time/timer.c:1302
Inline: False
Direct callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
```
**Symbols:**

```
ffffffff81112ef0-ffffffff81113012: call_timer_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void call_timer_fn(struct timer_list *timer, void (*fn)(struct timer_list *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8111e6d0)
Location: kernel/time/timer.c:1301
Inline: False
Direct callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
```
**Symbols:**

```
ffffffff8111e6d0-ffffffff8111e7fe: call_timer_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void call_timer_fn(struct timer_list *timer, void (*fn)(struct timer_list *), long unsigned int baseclk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811293b0)
Location: kernel/time/timer.c:1296
Inline: False
```
**Symbols:**

```
ffffffff811293b0-ffffffff811294dc: call_timer_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void call_timer_fn(struct timer_list *timer, void (*fn)(struct timer_list *), long unsigned int baseclk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81135350)
Location: kernel/time/timer.c:1378
Inline: False
```
**Symbols:**

```
ffffffff81135350-ffffffff8113547c: call_timer_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void call_timer_fn(struct timer_list *timer, void (*fn)(struct timer_list *), long unsigned int baseclk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81144460)
Location: kernel/time/timer.c:1390
Inline: False
```
**Symbols:**

```
ffffffff81144460-ffffffff8114458c: call_timer_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void call_timer_fn(struct timer_list *timer, void (*fn)(struct timer_list *), long unsigned int baseclk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81140ac0)
Location: kernel/time/timer.c:1391
Inline: False
```
**Symbols:**

```
ffffffff81140ac0-ffffffff81140bb7: call_timer_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void call_timer_fn(struct timer_list *timer, void (*fn)(struct timer_list *), long unsigned int baseclk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81141c40)
Location: kernel/time/timer.c:1409
Inline: False
```
**Symbols:**

```
ffffffff81141c40-ffffffff81141d37: call_timer_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void call_timer_fn(struct timer_list *timer, void (*fn)(struct timer_list *), long unsigned int baseclk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timer.c (0)
Location: kernel/time/timer.c:1395
Inline: False
```
**Symbols:**

```
ffffffff81165190-ffffffff811652a2: call_timer_fn (STB_LOCAL)
ffffffff81cb08c1-ffffffff81cb08d6: call_timer_fn.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void call_timer_fn(struct timer_list *timer, void (*fn)(struct timer_list *), long unsigned int baseclk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timer.c (0)
Location: kernel/time/timer.c:1448
Inline: False
Direct callers:
  - kernel/time/timer.c:__run_timers
  - kernel/time/timer.c:__run_timers
```
**Symbols:**

```
ffffffff81198e00-ffffffff81198f57: call_timer_fn (STB_LOCAL)
ffffffff81e61e36-ffffffff81e61e4b: call_timer_fn.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void call_timer_fn(struct timer_list *timer, void (*fn)(struct timer_list *), long unsigned int baseclk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timer.c (0)
Location: kernel/time/timer.c:1674
Inline: False
Direct callers:
  - kernel/time/timer.c:__run_timers
  - kernel/time/timer.c:__run_timers
```
**Symbols:**

```
ffffffff811d7350-ffffffff811d74a7: call_timer_fn (STB_LOCAL)
ffffffff8205ad09-ffffffff8205ad1e: call_timer_fn.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void call_timer_fn(struct timer_list *timer, void (*fn)(struct timer_list *), long unsigned int baseclk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timer.c (0)
Location: kernel/time/timer.c:1674
Inline: False
Direct callers:
  - kernel/time/timer.c:__run_timers
  - kernel/time/timer.c:__run_timers
```
**Symbols:**

```
ffffffff811eb6b0-ffffffff811eb807: call_timer_fn (STB_LOCAL)
ffffffff820d95a4-ffffffff820d95b9: call_timer_fn.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void call_timer_fn(struct timer_list *timer, void (*fn)(struct timer_list *), long unsigned int baseclk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timer.c (0)
Location: kernel/time/timer.c:1674
Inline: False
Direct callers:
  - kernel/time/timer.c:__run_timers
  - kernel/time/timer.c:__run_timers
```
**Symbols:**

```
ffffffff81201800-ffffffff81201951: call_timer_fn (STB_LOCAL)
ffffffff821b4e5a-ffffffff821b4e6e: call_timer_fn.cold (STB_LOCAL)
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
void call_timer_fn(struct timer_list *timer, void (*fn)(struct timer_list *), long unsigned int baseclk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffff80001019e578)
Location: kernel/time/timer.c:1378
Inline: False
```
**Symbols:**

```
ffff80001019e578-ffff80001019e6ec: call_timer_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void call_timer_fn(struct timer_list *timer, void (*fn)(struct timer_list *), long unsigned int baseclk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c03e77e4)
Location: kernel/time/timer.c:1378
Inline: False
Direct callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
```
**Symbols:**

```
c03e77e4-c03e7984: call_timer_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void call_timer_fn(struct timer_list *timer, void (*fn)(struct timer_list *), long unsigned int baseclk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c0000000001fe360)
Location: kernel/time/timer.c:1378
Inline: False
Direct callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
```
**Symbols:**

```
c0000000001fe360-c0000000001fe524: call_timer_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void call_timer_fn(struct timer_list *timer, void (*fn)(struct timer_list *), long unsigned int baseclk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffe00012bfac)
Location: kernel/time/timer.c:1378
Inline: False
Direct callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
```
**Symbols:**

```
ffffffe00012bfac-ffffffe00012c0dc: call_timer_fn (STB_LOCAL)
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
void call_timer_fn(struct timer_list *timer, void (*fn)(struct timer_list *), long unsigned int baseclk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8112db00)
Location: kernel/time/timer.c:1378
Inline: False
```
**Symbols:**

```
ffffffff8112db00-ffffffff8112dc2c: call_timer_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void call_timer_fn(struct timer_list *timer, void (*fn)(struct timer_list *), long unsigned int baseclk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81120370)
Location: kernel/time/timer.c:1378
Inline: False
Direct callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
```
**Symbols:**

```
ffffffff81120370-ffffffff8112049c: call_timer_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void call_timer_fn(struct timer_list *timer, void (*fn)(struct timer_list *), long unsigned int baseclk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8112b820)
Location: kernel/time/timer.c:1378
Inline: False
```
**Symbols:**

```
ffffffff8112b820-ffffffff8112b94c: call_timer_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void call_timer_fn(struct timer_list *timer, void (*fn)(struct timer_list *), long unsigned int baseclk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81137ea0)
Location: kernel/time/timer.c:1378
Inline: False
Direct callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
```
**Symbols:**

```
ffffffff81137ea0-ffffffff81137ffe: call_timer_fn (STB_LOCAL)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long unsigned int data</code>
</li>
<li>
<b>Param type changed. </b>
<code>void (*fn)(long unsigned int)</code> ➡️ <code>void (*fn)(struct timer_list *)</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int baseclk</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
