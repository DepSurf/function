# Function: <code>hrtimer_next_event_without</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 hrtimer_next_event_without(const struct hrtimer *exclude);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81116330)
Location: kernel/time/hrtimer.c:1229
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
```
**Symbols:**

```
ffffffff81116330-ffffffff811163ba: hrtimer_next_event_without (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 hrtimer_next_event_without(const struct hrtimer *exclude);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81121970)
Location: kernel/time/hrtimer.c:1220
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
```
**Symbols:**

```
ffffffff81121970-ffffffff811219fa: hrtimer_next_event_without (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 hrtimer_next_event_without(const struct hrtimer *exclude);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112c290)
Location: kernel/time/hrtimer.c:1220
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
```
**Symbols:**

```
ffffffff8112c290-ffffffff8112c322: hrtimer_next_event_without (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 hrtimer_next_event_without(const struct hrtimer *exclude);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811382b0)
Location: kernel/time/hrtimer.c:1337
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
```
**Symbols:**

```
ffffffff811382b0-ffffffff81138342: hrtimer_next_event_without (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 hrtimer_next_event_without(const struct hrtimer *exclude);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811470c0)
Location: kernel/time/hrtimer.c:1337
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
```
**Symbols:**

```
ffffffff811470c0-ffffffff81147152: hrtimer_next_event_without (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 hrtimer_next_event_without(const struct hrtimer *exclude);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81143560)
Location: kernel/time/hrtimer.c:1354
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
```
**Symbols:**

```
ffffffff81143560-ffffffff811435f2: hrtimer_next_event_without (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 hrtimer_next_event_without(const struct hrtimer *exclude);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81144710)
Location: kernel/time/hrtimer.c:1354
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
```
**Symbols:**

```
ffffffff81144710-ffffffff811447a2: hrtimer_next_event_without (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 hrtimer_next_event_without(const struct hrtimer *exclude);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81167fd0)
Location: kernel/time/hrtimer.c:1502
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
```
**Symbols:**

```
ffffffff81167fd0-ffffffff81168062: hrtimer_next_event_without (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 hrtimer_next_event_without(const struct hrtimer *exclude);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8119b9c0)
Location: kernel/time/hrtimer.c:1502
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
```
**Symbols:**

```
ffffffff8119b9c0-ffffffff8119ba56: hrtimer_next_event_without (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 hrtimer_next_event_without(const struct hrtimer *exclude);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811da2c0)
Location: kernel/time/hrtimer.c:1502
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
```
**Symbols:**

```
ffffffff811da2c0-ffffffff811da356: hrtimer_next_event_without (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 hrtimer_next_event_without(const struct hrtimer *exclude);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811ee7f0)
Location: kernel/time/hrtimer.c:1505
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
```
**Symbols:**

```
ffffffff811ee7f0-ffffffff811ee886: hrtimer_next_event_without (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 hrtimer_next_event_without(const struct hrtimer *exclude);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81204970)
Location: kernel/time/hrtimer.c:1506
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
```
**Symbols:**

```
ffffffff81204970-ffffffff81204a06: hrtimer_next_event_without (STB_GLOBAL)
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
u64 hrtimer_next_event_without(const struct hrtimer *exclude);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffff8000101a1da8)
Location: kernel/time/hrtimer.c:1337
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
```
**Symbols:**

```
ffff8000101a1da8-ffff8000101a1e94: hrtimer_next_event_without (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 hrtimer_next_event_without(const struct hrtimer *exclude);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c03ebb5c)
Location: kernel/time/hrtimer.c:1337
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
```
**Symbols:**

```
c03ebb5c-c03ebc20: hrtimer_next_event_without (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 hrtimer_next_event_without(const struct hrtimer *exclude);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c000000000203210)
Location: kernel/time/hrtimer.c:1337
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
```
**Symbols:**

```
c000000000203210-c000000000203328: hrtimer_next_event_without (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 hrtimer_next_event_without(const struct hrtimer *exclude);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffe00012f09c)
Location: kernel/time/hrtimer.c:1337
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
```
**Symbols:**

```
ffffffe00012f09c-ffffffe00012f13e: hrtimer_next_event_without (STB_GLOBAL)
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
u64 hrtimer_next_event_without(const struct hrtimer *exclude);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81130a60)
Location: kernel/time/hrtimer.c:1337
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
```
**Symbols:**

```
ffffffff81130a60-ffffffff81130af2: hrtimer_next_event_without (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 hrtimer_next_event_without(const struct hrtimer *exclude);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811234d0)
Location: kernel/time/hrtimer.c:1337
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
```
**Symbols:**

```
ffffffff811234d0-ffffffff81123562: hrtimer_next_event_without (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 hrtimer_next_event_without(const struct hrtimer *exclude);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112e780)
Location: kernel/time/hrtimer.c:1337
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
```
**Symbols:**

```
ffffffff8112e780-ffffffff8112e812: hrtimer_next_event_without (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 hrtimer_next_event_without(const struct hrtimer *exclude);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8113b180)
Location: kernel/time/hrtimer.c:1337
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
```
**Symbols:**

```
ffffffff8113b180-ffffffff8113b212: hrtimer_next_event_without (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
