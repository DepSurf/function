# Function: <code>hrtimer_reprogram</code>

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
In kernel/time/hrtimer.c (ffffffff810ef6f3)
Location: kernel/time/hrtimer.c:606
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
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
In kernel/time/hrtimer.c (ffffffff810f676b)
Location: kernel/time/hrtimer.c:596
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
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
In kernel/time/hrtimer.c (ffffffff810fd780)
Location: kernel/time/hrtimer.c:596
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
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
In kernel/time/hrtimer.c (ffffffff810ffa83)
Location: kernel/time/hrtimer.c:597
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
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
In kernel/time/hrtimer.c (ffffffff8110a89b)
Location: kernel/time/hrtimer.c:597
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void hrtimer_reprogram(struct hrtimer *timer, bool reprogram);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81115440)
Location: kernel/time/hrtimer.c:764
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_update_softirq_timer
```
**Symbols:**

```
ffffffff81115440-ffffffff811154e0: hrtimer_reprogram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void hrtimer_reprogram(struct hrtimer *timer, bool reprogram);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81120a80)
Location: kernel/time/hrtimer.c:755
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_update_softirq_timer
```
**Symbols:**

```
ffffffff81120a80-ffffffff81120b20: hrtimer_reprogram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void hrtimer_reprogram(struct hrtimer *timer, bool reprogram);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112b290)
Location: kernel/time/hrtimer.c:754
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_update_softirq_timer
```
**Symbols:**

```
ffffffff8112b290-ffffffff8112b32f: hrtimer_reprogram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void hrtimer_reprogram(struct hrtimer *timer, bool reprogram);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81137370)
Location: kernel/time/hrtimer.c:775
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_update_softirq_timer
```
**Symbols:**

```
ffffffff81137370-ffffffff8113740f: hrtimer_reprogram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void hrtimer_reprogram(struct hrtimer *timer, bool reprogram);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81146000)
Location: kernel/time/hrtimer.c:775
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_run_softirq
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff81146000-ffffffff8114609f: hrtimer_reprogram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void hrtimer_reprogram(struct hrtimer *timer, bool reprogram);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81142520)
Location: kernel/time/hrtimer.c:792
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_run_softirq
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff81142520-ffffffff811425bd: hrtimer_reprogram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void hrtimer_reprogram(struct hrtimer *timer, bool reprogram);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81143700)
Location: kernel/time/hrtimer.c:792
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_run_softirq
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff81143700-ffffffff8114379a: hrtimer_reprogram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void hrtimer_reprogram(struct hrtimer *timer, bool reprogram);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81166e50)
Location: kernel/time/hrtimer.c:808
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_run_softirq
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff81166e50-ffffffff81166eea: hrtimer_reprogram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void hrtimer_reprogram(struct hrtimer *timer, bool reprogram);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8119a660)
Location: kernel/time/hrtimer.c:808
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_run_softirq
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff8119a660-ffffffff8119a734: hrtimer_reprogram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void hrtimer_reprogram(struct hrtimer *timer, bool reprogram);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811d8df0)
Location: kernel/time/hrtimer.c:808
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_run_softirq
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff811d8df0-ffffffff811d8ec4: hrtimer_reprogram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void hrtimer_reprogram(struct hrtimer *timer, bool reprogram);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811ed240)
Location: kernel/time/hrtimer.c:810
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_run_softirq
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff811ed240-ffffffff811ed302: hrtimer_reprogram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void hrtimer_reprogram(struct hrtimer *timer, bool reprogram);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81203470)
Location: kernel/time/hrtimer.c:810
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_run_softirq
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff81203470-ffffffff81203532: hrtimer_reprogram (STB_LOCAL)
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
void hrtimer_reprogram(struct hrtimer *timer, bool reprogram);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffff8000101a1490)
Location: kernel/time/hrtimer.c:775
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_update_softirq_timer
```
**Symbols:**

```
ffff8000101a1490-ffff8000101a155c: hrtimer_reprogram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void hrtimer_reprogram(struct hrtimer *timer, bool reprogram);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c03ea388)
Location: kernel/time/hrtimer.c:775
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_update_softirq_timer
```
**Symbols:**

```
c03ea388-c03ea4c0: hrtimer_reprogram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void hrtimer_reprogram(struct hrtimer *timer, bool reprogram);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c000000000201710)
Location: kernel/time/hrtimer.c:775
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_update_softirq_timer
```
**Symbols:**

```
c000000000201710-c000000000201818: hrtimer_reprogram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (ffffffe00012e77a)
Location: kernel/time/hrtimer.c:775
Inline: True
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_run_softirq
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
ffffffe00012e77a-ffffffe00012e826: hrtimer_reprogram.constprop.0 (STB_LOCAL)
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
void hrtimer_reprogram(struct hrtimer *timer, bool reprogram);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112fb20)
Location: kernel/time/hrtimer.c:775
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_update_softirq_timer
```
**Symbols:**

```
ffffffff8112fb20-ffffffff8112fbbf: hrtimer_reprogram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void hrtimer_reprogram(struct hrtimer *timer, bool reprogram);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81122590)
Location: kernel/time/hrtimer.c:775
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_update_softirq_timer
```
**Symbols:**

```
ffffffff81122590-ffffffff8112262f: hrtimer_reprogram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void hrtimer_reprogram(struct hrtimer *timer, bool reprogram);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112d840)
Location: kernel/time/hrtimer.c:775
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_update_softirq_timer
```
**Symbols:**

```
ffffffff8112d840-ffffffff8112d8df: hrtimer_reprogram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void hrtimer_reprogram(struct hrtimer *timer, bool reprogram);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8113a170)
Location: kernel/time/hrtimer.c:775
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_update_softirq_timer
```
**Symbols:**

```
ffffffff8113a170-ffffffff8113a20f: hrtimer_reprogram (STB_LOCAL)
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
