# Function: <code>__remove_hrtimer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __remove_hrtimer(struct hrtimer *timer, struct hrtimer_clock_base *base, u8 newstate, int reprogram);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810eeeb0)
Location: kernel/time/hrtimer.c:898
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff810eeeb0-ffffffff810eef3c: __remove_hrtimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __remove_hrtimer(struct hrtimer *timer, struct hrtimer_clock_base *base, u8 newstate, int reprogram);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810f5f70)
Location: kernel/time/hrtimer.c:888
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff810f5f70-ffffffff810f5ffc: __remove_hrtimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __remove_hrtimer(struct hrtimer *timer, struct hrtimer_clock_base *base, u8 newstate, int reprogram);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810fcd90)
Location: kernel/time/hrtimer.c:888
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff810fcd90-ffffffff810fcdfc: __remove_hrtimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __remove_hrtimer(struct hrtimer *timer, struct hrtimer_clock_base *base, u8 newstate, int reprogram);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810ff190)
Location: kernel/time/hrtimer.c:861
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff810ff190-ffffffff810ff1fa: __remove_hrtimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __remove_hrtimer(struct hrtimer *timer, struct hrtimer_clock_base *base, u8 newstate, int reprogram);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81109f70)
Location: kernel/time/hrtimer.c:861
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff81109f70-ffffffff81109fda: __remove_hrtimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __remove_hrtimer(struct hrtimer *timer, struct hrtimer_clock_base *base, u8 newstate, int reprogram);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811156c0)
Location: kernel/time/hrtimer.c:973
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff811156c0-ffffffff8111572a: __remove_hrtimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __remove_hrtimer(struct hrtimer *timer, struct hrtimer_clock_base *base, u8 newstate, int reprogram);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81120d00)
Location: kernel/time/hrtimer.c:964
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff81120d00-ffffffff81120d6a: __remove_hrtimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __remove_hrtimer(struct hrtimer *timer, struct hrtimer_clock_base *base, u8 newstate, int reprogram);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112b510)
Location: kernel/time/hrtimer.c:963
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff8112b510-ffffffff8112b57a: __remove_hrtimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __remove_hrtimer(struct hrtimer *timer, struct hrtimer_clock_base *base, u8 newstate, int reprogram);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811375f0)
Location: kernel/time/hrtimer.c:985
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff811375f0-ffffffff8113765a: __remove_hrtimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __remove_hrtimer(struct hrtimer *timer, struct hrtimer_clock_base *base, u8 newstate, int reprogram);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81147b44)
Location: kernel/time/hrtimer.c:985
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:__run_hrtimer
Direct callers:
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff811469f0-ffffffff81146a5a: __remove_hrtimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __remove_hrtimer(struct hrtimer *timer, struct hrtimer_clock_base *base, u8 newstate, int reprogram);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81143fd0)
Location: kernel/time/hrtimer.c:1002
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:__run_hrtimer
Direct callers:
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff81142930-ffffffff811429b9: __remove_hrtimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __remove_hrtimer(struct hrtimer *timer, struct hrtimer_clock_base *base, u8 newstate, int reprogram);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81145160)
Location: kernel/time/hrtimer.c:1002
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:__hrtimer_run_queues
Direct callers:
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff81143fc0-ffffffff81144049: __remove_hrtimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __remove_hrtimer(struct hrtimer *timer, struct hrtimer_clock_base *base, u8 newstate, int reprogram);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (0)
Location: kernel/time/hrtimer.c:1104
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff811671e0-ffffffff8116727a: __remove_hrtimer (STB_LOCAL)
ffffffff81cb0960-ffffffff81cb097e: __remove_hrtimer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __remove_hrtimer(struct hrtimer *timer, struct hrtimer_clock_base *base, u8 newstate, int reprogram);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (0)
Location: kernel/time/hrtimer.c:1104
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_try_to_cancel
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff8119aa20-ffffffff8119aacb: __remove_hrtimer (STB_LOCAL)
ffffffff81e61eeb-ffffffff81e61f09: __remove_hrtimer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __remove_hrtimer(struct hrtimer *timer, struct hrtimer_clock_base *base, u8 newstate, int reprogram);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (0)
Location: kernel/time/hrtimer.c:1104
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_try_to_cancel
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff811d9200-ffffffff811d92ab: __remove_hrtimer (STB_LOCAL)
ffffffff8205adbd-ffffffff8205addb: __remove_hrtimer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __remove_hrtimer(struct hrtimer *timer, struct hrtimer_clock_base *base, u8 newstate, int reprogram);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (0)
Location: kernel/time/hrtimer.c:1107
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff811ed660-ffffffff811ed70b: __remove_hrtimer (STB_LOCAL)
ffffffff820d966c-ffffffff820d968a: __remove_hrtimer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __remove_hrtimer(struct hrtimer *timer, struct hrtimer_clock_base *base, u8 newstate, int reprogram);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (0)
Location: kernel/time/hrtimer.c:1108
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_cpu_dying
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff812039c0-ffffffff81203a6b: __remove_hrtimer (STB_LOCAL)
ffffffff821b4f6b-ffffffff821b4f89: __remove_hrtimer.cold (STB_LOCAL)
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
void __remove_hrtimer(struct hrtimer *timer, struct hrtimer_clock_base *base, u8 newstate, int reprogram);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffff8000101a0a40)
Location: kernel/time/hrtimer.c:985
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
ffff8000101a0a40-ffff8000101a0adc: __remove_hrtimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __remove_hrtimer(struct hrtimer *timer, struct hrtimer_clock_base *base, u8 newstate, int reprogram);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c03ea80c)
Location: kernel/time/hrtimer.c:985
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
c03ea80c-c03ea888: __remove_hrtimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __remove_hrtimer(struct hrtimer *timer, struct hrtimer_clock_base *base, u8 newstate, int reprogram);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c000000000201c60)
Location: kernel/time/hrtimer.c:985
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
c000000000201c60-c000000000201d58: __remove_hrtimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __remove_hrtimer(struct hrtimer *timer, struct hrtimer_clock_base *base, u8 newstate, int reprogram);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffe00012e2b6)
Location: kernel/time/hrtimer.c:985
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
ffffffe00012e2b6-ffffffe00012e33e: __remove_hrtimer (STB_LOCAL)
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
void __remove_hrtimer(struct hrtimer *timer, struct hrtimer_clock_base *base, u8 newstate, int reprogram);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112fda0)
Location: kernel/time/hrtimer.c:985
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff8112fda0-ffffffff8112fe0a: __remove_hrtimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __remove_hrtimer(struct hrtimer *timer, struct hrtimer_clock_base *base, u8 newstate, int reprogram);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81122810)
Location: kernel/time/hrtimer.c:985
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff81122810-ffffffff8112287a: __remove_hrtimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __remove_hrtimer(struct hrtimer *timer, struct hrtimer_clock_base *base, u8 newstate, int reprogram);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112dac0)
Location: kernel/time/hrtimer.c:985
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff8112dac0-ffffffff8112db2a: __remove_hrtimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __remove_hrtimer(struct hrtimer *timer, struct hrtimer_clock_base *base, u8 newstate, int reprogram);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8113a3f0)
Location: kernel/time/hrtimer.c:985
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff8113a3f0-ffffffff8113a45a: __remove_hrtimer (STB_LOCAL)
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
