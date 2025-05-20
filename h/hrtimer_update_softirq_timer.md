# Function: <code>hrtimer_update_softirq_timer</code>

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
void hrtimer_update_softirq_timer(struct hrtimer_cpu_base *cpu_base, bool reprogram);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81115730)
Location: kernel/time/hrtimer.c:1046
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_run_softirq
```
**Symbols:**

```
ffffffff81115730-ffffffff8111576c: hrtimer_update_softirq_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void hrtimer_update_softirq_timer(struct hrtimer_cpu_base *cpu_base, bool reprogram);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81120e00)
Location: kernel/time/hrtimer.c:1037
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_run_softirq
```
**Symbols:**

```
ffffffff81120e00-ffffffff81120e3c: hrtimer_update_softirq_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void hrtimer_update_softirq_timer(struct hrtimer_cpu_base *cpu_base, bool reprogram);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112b580)
Location: kernel/time/hrtimer.c:1036
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_run_softirq
```
**Symbols:**

```
ffffffff8112b580-ffffffff8112b5bf: hrtimer_update_softirq_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void hrtimer_update_softirq_timer(struct hrtimer_cpu_base *cpu_base, bool reprogram);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81137700)
Location: kernel/time/hrtimer.c:1060
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_run_softirq
```
**Symbols:**

```
ffffffff81137700-ffffffff8113773f: hrtimer_update_softirq_timer (STB_LOCAL)
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
In kernel/time/hrtimer.c (ffffffff81147bef)
Location: kernel/time/hrtimer.c:1060
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_run_softirq
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
In kernel/time/hrtimer.c (ffffffff81144072)
Location: kernel/time/hrtimer.c:1077
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_run_softirq
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
In kernel/time/hrtimer.c (ffffffff81145202)
Location: kernel/time/hrtimer.c:1077
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_run_softirq
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
In kernel/time/hrtimer.c (ffffffff81168a5b)
Location: kernel/time/hrtimer.c:1188
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_run_softirq
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
In kernel/time/hrtimer.c (ffffffff8119c5bd)
Location: kernel/time/hrtimer.c:1188
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_run_softirq
  - kernel/time/hrtimer.c:hrtimer_run_softirq
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
In kernel/time/hrtimer.c (ffffffff811daf8d)
Location: kernel/time/hrtimer.c:1188
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_run_softirq
  - kernel/time/hrtimer.c:hrtimer_run_softirq
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
In kernel/time/hrtimer.c (ffffffff811ef4bd)
Location: kernel/time/hrtimer.c:1191
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_run_softirq
  - kernel/time/hrtimer.c:hrtimer_run_softirq
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
In kernel/time/hrtimer.c (ffffffff81203dc1)
Location: kernel/time/hrtimer.c:1192
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_run_softirq
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
void hrtimer_update_softirq_timer(struct hrtimer_cpu_base *cpu_base, bool reprogram);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffff8000101a1560)
Location: kernel/time/hrtimer.c:1060
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_run_softirq
```
**Symbols:**

```
ffff8000101a1560-ffff8000101a15ac: hrtimer_update_softirq_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void hrtimer_update_softirq_timer(struct hrtimer_cpu_base *cpu_base, bool reprogram);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c03ea888)
Location: kernel/time/hrtimer.c:1060
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_run_softirq
```
**Symbols:**

```
c03ea888-c03ea8d0: hrtimer_update_softirq_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void hrtimer_update_softirq_timer(struct hrtimer_cpu_base *cpu_base, bool reprogram);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c000000000201e60)
Location: kernel/time/hrtimer.c:1060
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_run_softirq
```
**Symbols:**

```
c000000000201e60-c000000000201ee8: hrtimer_update_softirq_timer (STB_LOCAL)
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
In kernel/time/hrtimer.c (ffffffe00012eb36)
Location: kernel/time/hrtimer.c:1060
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_run_softirq
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
void hrtimer_update_softirq_timer(struct hrtimer_cpu_base *cpu_base, bool reprogram);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112feb0)
Location: kernel/time/hrtimer.c:1060
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_run_softirq
```
**Symbols:**

```
ffffffff8112feb0-ffffffff8112feef: hrtimer_update_softirq_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void hrtimer_update_softirq_timer(struct hrtimer_cpu_base *cpu_base, bool reprogram);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81122920)
Location: kernel/time/hrtimer.c:1060
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_run_softirq
```
**Symbols:**

```
ffffffff81122920-ffffffff8112295f: hrtimer_update_softirq_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void hrtimer_update_softirq_timer(struct hrtimer_cpu_base *cpu_base, bool reprogram);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112dbd0)
Location: kernel/time/hrtimer.c:1060
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_run_softirq
```
**Symbols:**

```
ffffffff8112dbd0-ffffffff8112dc0f: hrtimer_update_softirq_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void hrtimer_update_softirq_timer(struct hrtimer_cpu_base *cpu_base, bool reprogram);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8113a500)
Location: kernel/time/hrtimer.c:1060
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_run_softirq
```
**Symbols:**

```
ffffffff8113a500-ffffffff8113a53f: hrtimer_update_softirq_timer (STB_LOCAL)
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
