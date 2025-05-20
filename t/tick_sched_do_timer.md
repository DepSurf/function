# Function: <code>tick_sched_do_timer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tick_sched_do_timer(ktime_t now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff810fe460)
Location: kernel/time/tick-sched.c:112
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
```
**Symbols:**

```
ffffffff810fe460-ffffffff810fe48e: tick_sched_do_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tick_sched_do_timer(ktime_t now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff811057f0)
Location: kernel/time/tick-sched.c:112
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
```
**Symbols:**

```
ffffffff811057f0-ffffffff8110581d: tick_sched_do_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void tick_sched_do_timer(ktime_t now);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8110cf90)
Location: kernel/time/tick-sched.c:112
Inline: True
Direct callers:
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
```
**Symbols:**

```
ffffffff8110cf90-ffffffff8110cfd1: tick_sched_do_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void tick_sched_do_timer(ktime_t now);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8110ee50)
Location: kernel/time/tick-sched.c:116
Inline: True
Direct callers:
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
```
**Symbols:**

```
ffffffff8110ee50-ffffffff8110ee91: tick_sched_do_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void tick_sched_do_timer(ktime_t now);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8111a540)
Location: kernel/time/tick-sched.c:117
Inline: True
Direct callers:
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
```
**Symbols:**

```
ffffffff8111a540-ffffffff8111a581: tick_sched_do_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tick_sched_do_timer(struct tick_sched *ts, ktime_t now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81126e80)
Location: kernel/time/tick-sched.c:116
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
```
**Symbols:**

```
ffffffff81126e80-ffffffff81126ed7: tick_sched_do_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tick_sched_do_timer(struct tick_sched *ts, ktime_t now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81132570)
Location: kernel/time/tick-sched.c:113
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
```
**Symbols:**

```
ffffffff81132570-ffffffff811325c7: tick_sched_do_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tick_sched_do_timer(struct tick_sched *ts, ktime_t now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8113d0f0)
Location: kernel/time/tick-sched.c:113
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
```
**Symbols:**

```
ffffffff8113d0f0-ffffffff8113d147: tick_sched_do_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tick_sched_do_timer(struct tick_sched *ts, ktime_t now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81148c80)
Location: kernel/time/tick-sched.c:117
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
```
**Symbols:**

```
ffffffff81148c80-ffffffff81148cda: tick_sched_do_timer (STB_LOCAL)
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
In kernel/time/tick-sched.c (ffffffff81158be2)
Location: kernel/time/tick-sched.c:122
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
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
In kernel/time/tick-sched.c (ffffffff81154cd2)
Location: kernel/time/tick-sched.c:172
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
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
In kernel/time/tick-sched.c (ffffffff811562a2)
Location: kernel/time/tick-sched.c:172
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
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
In kernel/time/tick-sched.c (ffffffff8117af52)
Location: kernel/time/tick-sched.c:172
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tick_sched_do_timer(struct tick_sched *ts, ktime_t now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff811afe60)
Location: kernel/time/tick-sched.c:174
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
```
**Symbols:**

```
ffffffff811afe60-ffffffff811afefd: tick_sched_do_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tick_sched_do_timer(struct tick_sched *ts, ktime_t now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff811f08d0)
Location: kernel/time/tick-sched.c:174
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
```
**Symbols:**

```
ffffffff811f08d0-ffffffff811f096d: tick_sched_do_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tick_sched_do_timer(struct tick_sched *ts, ktime_t now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff812052f0)
Location: kernel/time/tick-sched.c:185
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
```
**Symbols:**

```
ffffffff812052f0-ffffffff8120537c: tick_sched_do_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void tick_sched_do_timer(struct tick_sched *ts, ktime_t now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/tick-sched.c (0)
Location: kernel/time/tick-sched.c:186
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_highres_handler
  - kernel/time/tick-sched.c:tick_nohz_lowres_handler
```
**Symbols:**

```
ffffffff8121b9c0-ffffffff8121ba71: tick_sched_do_timer (STB_LOCAL)
ffffffff821b5f78-ffffffff821b5f8d: tick_sched_do_timer.cold (STB_LOCAL)
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
void tick_sched_do_timer(struct tick_sched *ts, ktime_t now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffff8000101b4ee8)
Location: kernel/time/tick-sched.c:117
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
```
**Symbols:**

```
ffff8000101b4ee8-ffff8000101b4f78: tick_sched_do_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tick_sched_do_timer(struct tick_sched *ts, ktime_t now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (c03feac4)
Location: kernel/time/tick-sched.c:117
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
```
**Symbols:**

```
c03feac4-c03feb5c: tick_sched_do_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tick_sched_do_timer(struct tick_sched *ts, ktime_t now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (c00000000021a620)
Location: kernel/time/tick-sched.c:117
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
```
**Symbols:**

```
c00000000021a620-c00000000021a6c0: tick_sched_do_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tick_sched_do_timer(struct tick_sched *ts, ktime_t now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffe00013b2c2)
Location: kernel/time/tick-sched.c:117
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
```
**Symbols:**

```
ffffffe00013b2c2-ffffffe00013b338: tick_sched_do_timer (STB_LOCAL)
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
void tick_sched_do_timer(struct tick_sched *ts, ktime_t now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff811412a0)
Location: kernel/time/tick-sched.c:117
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
```
**Symbols:**

```
ffffffff811412a0-ffffffff811412fa: tick_sched_do_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tick_sched_do_timer(struct tick_sched *ts, ktime_t now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81134110)
Location: kernel/time/tick-sched.c:117
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
```
**Symbols:**

```
ffffffff81134110-ffffffff81134177: tick_sched_do_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tick_sched_do_timer(struct tick_sched *ts, ktime_t now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8113f150)
Location: kernel/time/tick-sched.c:117
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
```
**Symbols:**

```
ffffffff8113f150-ffffffff8113f1aa: tick_sched_do_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tick_sched_do_timer(struct tick_sched *ts, ktime_t now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8114bbb0)
Location: kernel/time/tick-sched.c:117
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
```
**Symbols:**

```
ffffffff8114bbb0-ffffffff8114bc0a: tick_sched_do_timer (STB_LOCAL)
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
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct tick_sched *ts</code>
</li>
<li>
<b>Param reordered. </b>
<code>now</code> ➡️ <code>ts, now</code>
</li>
</ul>
</details>
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
