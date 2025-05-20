# Function: <code>enqueue_hrtimer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int enqueue_hrtimer(struct hrtimer *timer, struct hrtimer_clock_base *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810eea70)
Location: kernel/time/hrtimer.c:876
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff810eea70-ffffffff810eeaf7: enqueue_hrtimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int enqueue_hrtimer(struct hrtimer *timer, struct hrtimer_clock_base *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810f5cd0)
Location: kernel/time/hrtimer.c:866
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff810f5cd0-ffffffff810f5d50: enqueue_hrtimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int enqueue_hrtimer(struct hrtimer *timer, struct hrtimer_clock_base *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810fce00)
Location: kernel/time/hrtimer.c:866
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff810fce00-ffffffff810fce80: enqueue_hrtimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int enqueue_hrtimer(struct hrtimer *timer, struct hrtimer_clock_base *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810ff200)
Location: kernel/time/hrtimer.c:839
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff810ff200-ffffffff810ff281: enqueue_hrtimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int enqueue_hrtimer(struct hrtimer *timer, struct hrtimer_clock_base *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81109fe0)
Location: kernel/time/hrtimer.c:839
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff81109fe0-ffffffff8110a064: enqueue_hrtimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int enqueue_hrtimer(struct hrtimer *timer, struct hrtimer_clock_base *base, enum hrtimer_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81115770)
Location: kernel/time/hrtimer.c:950
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff81115770-ffffffff811157fd: enqueue_hrtimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int enqueue_hrtimer(struct hrtimer *timer, struct hrtimer_clock_base *base, enum hrtimer_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81120e40)
Location: kernel/time/hrtimer.c:941
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff81120e40-ffffffff81120ecd: enqueue_hrtimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int enqueue_hrtimer(struct hrtimer *timer, struct hrtimer_clock_base *base, enum hrtimer_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112b5c0)
Location: kernel/time/hrtimer.c:940
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff8112b5c0-ffffffff8112b64d: enqueue_hrtimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int enqueue_hrtimer(struct hrtimer *timer, struct hrtimer_clock_base *base, enum hrtimer_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81137740)
Location: kernel/time/hrtimer.c:961
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff81137740-ffffffff811377cd: enqueue_hrtimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int enqueue_hrtimer(struct hrtimer *timer, struct hrtimer_clock_base *base, enum hrtimer_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81146360)
Location: kernel/time/hrtimer.c:961
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:__run_hrtimer
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff81146360-ffffffff811463ee: enqueue_hrtimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int enqueue_hrtimer(struct hrtimer *timer, struct hrtimer_clock_base *base, enum hrtimer_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81142ab0)
Location: kernel/time/hrtimer.c:978
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:__run_hrtimer
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff81142ab0-ffffffff81142b1e: enqueue_hrtimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int enqueue_hrtimer(struct hrtimer *timer, struct hrtimer_clock_base *base, enum hrtimer_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81143ad0)
Location: kernel/time/hrtimer.c:978
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff81143ad0-ffffffff81143b3e: enqueue_hrtimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int enqueue_hrtimer(struct hrtimer *timer, struct hrtimer_clock_base *base, enum hrtimer_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (0)
Location: kernel/time/hrtimer.c:1080
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff81166ef0-ffffffff81166f6c: enqueue_hrtimer (STB_LOCAL)
ffffffff81cb091c-ffffffff81cb093a: enqueue_hrtimer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int enqueue_hrtimer(struct hrtimer *timer, struct hrtimer_clock_base *base, enum hrtimer_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (0)
Location: kernel/time/hrtimer.c:1080
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff8119a740-ffffffff8119a7e0: enqueue_hrtimer (STB_LOCAL)
ffffffff81e61ea7-ffffffff81e61ec5: enqueue_hrtimer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int enqueue_hrtimer(struct hrtimer *timer, struct hrtimer_clock_base *base, enum hrtimer_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (0)
Location: kernel/time/hrtimer.c:1080
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff811d8ee0-ffffffff811d8f80: enqueue_hrtimer (STB_LOCAL)
ffffffff8205ad78-ffffffff8205ad96: enqueue_hrtimer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int enqueue_hrtimer(struct hrtimer *timer, struct hrtimer_clock_base *base, enum hrtimer_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (0)
Location: kernel/time/hrtimer.c:1083
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff811ed320-ffffffff811ed3c0: enqueue_hrtimer (STB_LOCAL)
ffffffff820d9627-ffffffff820d9645: enqueue_hrtimer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int enqueue_hrtimer(struct hrtimer *timer, struct hrtimer_clock_base *base, enum hrtimer_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (0)
Location: kernel/time/hrtimer.c:1083
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_cpu_dying
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff81203160-ffffffff81203215: enqueue_hrtimer (STB_LOCAL)
ffffffff821b4f23-ffffffff821b4f44: enqueue_hrtimer.cold (STB_LOCAL)
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
int enqueue_hrtimer(struct hrtimer *timer, struct hrtimer_clock_base *base, enum hrtimer_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffff8000101a0fc8)
Location: kernel/time/hrtimer.c:961
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
ffff8000101a0fc8-ffff8000101a109c: enqueue_hrtimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int enqueue_hrtimer(struct hrtimer *timer, struct hrtimer_clock_base *base, enum hrtimer_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c03ea4c0)
Location: kernel/time/hrtimer.c:961
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
c03ea4c0-c03ea58c: enqueue_hrtimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int enqueue_hrtimer(struct hrtimer *timer, struct hrtimer_clock_base *base, enum hrtimer_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c000000000201820)
Location: kernel/time/hrtimer.c:961
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
c000000000201820-c000000000201914: enqueue_hrtimer (STB_LOCAL)
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
In kernel/time/hrtimer.c (ffffffe00012e8a4)
Location: kernel/time/hrtimer.c:961
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
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
int enqueue_hrtimer(struct hrtimer *timer, struct hrtimer_clock_base *base, enum hrtimer_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112fef0)
Location: kernel/time/hrtimer.c:961
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff8112fef0-ffffffff8112ff7d: enqueue_hrtimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int enqueue_hrtimer(struct hrtimer *timer, struct hrtimer_clock_base *base, enum hrtimer_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81122960)
Location: kernel/time/hrtimer.c:961
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff81122960-ffffffff811229ed: enqueue_hrtimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int enqueue_hrtimer(struct hrtimer *timer, struct hrtimer_clock_base *base, enum hrtimer_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112dc10)
Location: kernel/time/hrtimer.c:961
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff8112dc10-ffffffff8112dc9d: enqueue_hrtimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int enqueue_hrtimer(struct hrtimer *timer, struct hrtimer_clock_base *base, enum hrtimer_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8113a540)
Location: kernel/time/hrtimer.c:961
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff8113a540-ffffffff8113a5e5: enqueue_hrtimer (STB_LOCAL)
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
<code>enum hrtimer_mode mode</code>
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
