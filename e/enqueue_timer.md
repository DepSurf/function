# Function: <code>enqueue_timer</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8189e138)
Location: kernel/time/timer.c:514
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:__internal_add_timer
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
In kernel/time/timer.c (ffffffff818d2fee)
Location: kernel/time/timer.c:514
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:__internal_add_timer
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
In kernel/time/timer.c (ffffffff810fe2e0)
Location: kernel/time/timer.c:517
Inline: True
Inline callers:
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:__internal_add_timer
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
In kernel/time/timer.c (ffffffff81108b70)
Location: kernel/time/timer.c:517
Inline: True
Inline callers:
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:__internal_add_timer
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
In kernel/time/timer.c (ffffffff811145bf)
Location: kernel/time/timer.c:534
Inline: True
Inline callers:
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:__internal_add_timer
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
In kernel/time/timer.c (ffffffff8111fe3f)
Location: kernel/time/timer.c:533
Inline: True
Inline callers:
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:__internal_add_timer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void enqueue_timer(struct timer_base *base, struct timer_list *timer, unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81128210)
Location: kernel/time/timer.c:533
Inline: False
Direct callers:
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:__internal_add_timer
```
**Symbols:**

```
ffffffff81128210-ffffffff811282b7: enqueue_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void enqueue_timer(struct timer_base *base, struct timer_list *timer, unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811341b0)
Location: kernel/time/timer.c:537
Inline: False
Direct callers:
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:__internal_add_timer
```
**Symbols:**

```
ffffffff811341b0-ffffffff81134257: enqueue_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void enqueue_timer(struct timer_base *base, struct timer_list *timer, unsigned int idx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81145d19)
Location: kernel/time/timer.c:537
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
Direct callers:
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:__mod_timer
```
**Symbols:**

```
ffffffff811440b0-ffffffff81144158: enqueue_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void enqueue_timer(struct timer_base *base, struct timer_list *timer, unsigned int idx, long unsigned int bucket_expiry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811409f0)
Location: kernel/time/timer.c:577
Inline: False
Direct callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:__mod_timer
```
**Symbols:**

```
ffffffff811409f0-ffffffff81140ab8: enqueue_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void enqueue_timer(struct timer_base *base, struct timer_list *timer, unsigned int idx, long unsigned int bucket_expiry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81141ac0)
Location: kernel/time/timer.c:578
Inline: False
Direct callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:__mod_timer
```
**Symbols:**

```
ffffffff81141ac0-ffffffff81141b8e: enqueue_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void enqueue_timer(struct timer_base *base, struct timer_list *timer, unsigned int idx, long unsigned int bucket_expiry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timer.c (0)
Location: kernel/time/timer.c:578
Inline: False
Direct callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:__mod_timer
```
**Symbols:**

```
ffffffff811650b0-ffffffff81165184: enqueue_timer (STB_LOCAL)
ffffffff81cb08ad-ffffffff81cb08c1: enqueue_timer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void enqueue_timer(struct timer_base *base, struct timer_list *timer, unsigned int idx, long unsigned int bucket_expiry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timer.c (0)
Location: kernel/time/timer.c:601
Inline: False
Direct callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:__mod_timer
```
**Symbols:**

```
ffffffff81198cf0-ffffffff81198dfb: enqueue_timer (STB_LOCAL)
ffffffff81e61e22-ffffffff81e61e36: enqueue_timer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void enqueue_timer(struct timer_base *base, struct timer_list *timer, unsigned int idx, long unsigned int bucket_expiry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timer.c (0)
Location: kernel/time/timer.c:601
Inline: False
Direct callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:__mod_timer
```
**Symbols:**

```
ffffffff811d7230-ffffffff811d733b: enqueue_timer (STB_LOCAL)
ffffffff8205acf5-ffffffff8205ad09: enqueue_timer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void enqueue_timer(struct timer_base *base, struct timer_list *timer, unsigned int idx, long unsigned int bucket_expiry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timer.c (0)
Location: kernel/time/timer.c:601
Inline: False
Direct callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:__mod_timer
```
**Symbols:**

```
ffffffff811ebb90-ffffffff811ebc9b: enqueue_timer (STB_LOCAL)
ffffffff820d95e1-ffffffff820d95f5: enqueue_timer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void enqueue_timer(struct timer_base *base, struct timer_list *timer, unsigned int idx, long unsigned int bucket_expiry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timer.c (0)
Location: kernel/time/timer.c:598
Inline: False
Direct callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:__mod_timer
```
**Symbols:**

```
ffffffff812016e0-ffffffff812017e6: enqueue_timer (STB_LOCAL)
ffffffff821b4e46-ffffffff821b4e5a: enqueue_timer.cold (STB_LOCAL)
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
void enqueue_timer(struct timer_base *base, struct timer_list *timer, unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffff80001019e288)
Location: kernel/time/timer.c:537
Inline: False
Direct callers:
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:__internal_add_timer
```
**Symbols:**

```
ffff80001019e288-ffff80001019e3ac: enqueue_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void enqueue_timer(struct timer_base *base, struct timer_list *timer, unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c03e7614)
Location: kernel/time/timer.c:537
Inline: False
Direct callers:
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:__internal_add_timer
```
**Symbols:**

```
c03e7614-c03e7718: enqueue_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void enqueue_timer(struct timer_base *base, struct timer_list *timer, unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c0000000001fc270)
Location: kernel/time/timer.c:537
Inline: False
Direct callers:
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:__internal_add_timer
```
**Symbols:**

```
c0000000001fc270-c0000000001fc3ac: enqueue_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void enqueue_timer(struct timer_base *base, struct timer_list *timer, unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffe00012be6a)
Location: kernel/time/timer.c:537
Inline: False
Direct callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
```
**Symbols:**

```
ffffffe00012be6a-ffffffe00012bf5e: enqueue_timer (STB_LOCAL)
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
void enqueue_timer(struct timer_base *base, struct timer_list *timer, unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8112c960)
Location: kernel/time/timer.c:537
Inline: False
Direct callers:
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:__internal_add_timer
```
**Symbols:**

```
ffffffff8112c960-ffffffff8112ca07: enqueue_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void enqueue_timer(struct timer_base *base, struct timer_list *timer, unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8111f1d0)
Location: kernel/time/timer.c:537
Inline: False
Direct callers:
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:__internal_add_timer
```
**Symbols:**

```
ffffffff8111f1d0-ffffffff8111f277: enqueue_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void enqueue_timer(struct timer_base *base, struct timer_list *timer, unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8112a680)
Location: kernel/time/timer.c:537
Inline: False
Direct callers:
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:__internal_add_timer
```
**Symbols:**

```
ffffffff8112a680-ffffffff8112a727: enqueue_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void enqueue_timer(struct timer_base *base, struct timer_list *timer, unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81137c60)
Location: kernel/time/timer.c:537
Inline: False
Direct callers:
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:__internal_add_timer
```
**Symbols:**

```
ffffffff81137c60-ffffffff81137d15: enqueue_timer (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int bucket_expiry</code>
</li>
</ul>
</details>
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
