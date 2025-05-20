# Function: <code>__hrtimer_run_queues</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __hrtimer_run_queues(struct hrtimer_cpu_base *cpu_base, ktime_t now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810ef110)
Location: kernel/time/hrtimer.c:1278
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_run_queues
```
**Symbols:**

```
ffffffff810ef110-ffffffff810ef391: __hrtimer_run_queues (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __hrtimer_run_queues(struct hrtimer_cpu_base *cpu_base, ktime_t now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810f61c0)
Location: kernel/time/hrtimer.c:1268
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
```
**Symbols:**

```
ffffffff810f61c0-ffffffff810f6423: __hrtimer_run_queues (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __hrtimer_run_queues(struct hrtimer_cpu_base *cpu_base, ktime_t now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810fd1e0)
Location: kernel/time/hrtimer.c:1268
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
```
**Symbols:**

```
ffffffff810fd1e0-ffffffff810fd443: __hrtimer_run_queues (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __hrtimer_run_queues(struct hrtimer_cpu_base *cpu_base, ktime_t now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810ff560)
Location: kernel/time/hrtimer.c:1243
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
```
**Symbols:**

```
ffffffff810ff560-ffffffff810ff780: __hrtimer_run_queues (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __hrtimer_run_queues(struct hrtimer_cpu_base *cpu_base, ktime_t now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8110a360)
Location: kernel/time/hrtimer.c:1248
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
```
**Symbols:**

```
ffffffff8110a360-ffffffff8110a58b: __hrtimer_run_queues (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __hrtimer_run_queues(struct hrtimer_cpu_base *cpu_base, ktime_t now, long unsigned int flags, unsigned int active_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81115df0)
Location: kernel/time/hrtimer.c:1428
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_run_softirq
```
**Symbols:**

```
ffffffff81115df0-ffffffff81116060: __hrtimer_run_queues (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __hrtimer_run_queues(struct hrtimer_cpu_base *cpu_base, ktime_t now, long unsigned int flags, unsigned int active_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81121220)
Location: kernel/time/hrtimer.c:1419
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_run_softirq
```
**Symbols:**

```
ffffffff81121220-ffffffff81121490: __hrtimer_run_queues (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __hrtimer_run_queues(struct hrtimer_cpu_base *cpu_base, ktime_t now, long unsigned int flags, unsigned int active_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112ba40)
Location: kernel/time/hrtimer.c:1419
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_run_softirq
```
**Symbols:**

```
ffffffff8112ba40-ffffffff8112bcb0: __hrtimer_run_queues (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __hrtimer_run_queues(struct hrtimer_cpu_base *cpu_base, ktime_t now, long unsigned int flags, unsigned int active_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81137ae0)
Location: kernel/time/hrtimer.c:1547
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_run_softirq
```
**Symbols:**

```
ffffffff81137ae0-ffffffff81137d50: __hrtimer_run_queues (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __hrtimer_run_queues(struct hrtimer_cpu_base *cpu_base, ktime_t now, long unsigned int flags, unsigned int active_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81146750)
Location: kernel/time/hrtimer.c:1552
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_run_softirq
```
**Symbols:**

```
ffffffff81146750-ffffffff81146830: __hrtimer_run_queues (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __hrtimer_run_queues(struct hrtimer_cpu_base *cpu_base, ktime_t now, long unsigned int flags, unsigned int active_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81143140)
Location: kernel/time/hrtimer.c:1569
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_run_softirq
```
**Symbols:**

```
ffffffff81143140-ffffffff81143220: __hrtimer_run_queues (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __hrtimer_run_queues(struct hrtimer_cpu_base *cpu_base, ktime_t now, long unsigned int flags, unsigned int active_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81143bb0)
Location: kernel/time/hrtimer.c:1569
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_run_softirq
```
**Symbols:**

```
ffffffff81143bb0-ffffffff81143e1f: __hrtimer_run_queues (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __hrtimer_run_queues(struct hrtimer_cpu_base *cpu_base, ktime_t now, long unsigned int flags, unsigned int active_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (0)
Location: kernel/time/hrtimer.c:1717
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_run_softirq
```
**Symbols:**

```
ffffffff81167280-ffffffff81167487: __hrtimer_run_queues (STB_LOCAL)
ffffffff81cb097e-ffffffff81cb099f: __hrtimer_run_queues.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __hrtimer_run_queues(struct hrtimer_cpu_base *cpu_base, ktime_t now, long unsigned int flags, unsigned int active_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (0)
Location: kernel/time/hrtimer.c:1717
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_run_softirq
```
**Symbols:**

```
ffffffff8119ac20-ffffffff8119ae9d: __hrtimer_run_queues (STB_LOCAL)
ffffffff81e61f09-ffffffff81e61f2a: __hrtimer_run_queues.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __hrtimer_run_queues(struct hrtimer_cpu_base *cpu_base, ktime_t now, long unsigned int flags, unsigned int active_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (0)
Location: kernel/time/hrtimer.c:1717
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_run_softirq
```
**Symbols:**

```
ffffffff811d92c0-ffffffff811d953d: __hrtimer_run_queues (STB_LOCAL)
ffffffff8205addb-ffffffff8205adfc: __hrtimer_run_queues.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __hrtimer_run_queues(struct hrtimer_cpu_base *cpu_base, ktime_t now, long unsigned int flags, unsigned int active_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (0)
Location: kernel/time/hrtimer.c:1720
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_run_softirq
```
**Symbols:**

```
ffffffff811ed720-ffffffff811ed9bb: __hrtimer_run_queues (STB_LOCAL)
ffffffff820d968a-ffffffff820d96ab: __hrtimer_run_queues.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __hrtimer_run_queues(struct hrtimer_cpu_base *cpu_base, ktime_t now, long unsigned int flags, unsigned int active_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (0)
Location: kernel/time/hrtimer.c:1721
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_run_softirq
```
**Symbols:**

```
ffffffff81203a80-ffffffff81203d1b: __hrtimer_run_queues (STB_LOCAL)
ffffffff821b4f89-ffffffff821b4faa: __hrtimer_run_queues.cold (STB_LOCAL)
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
void __hrtimer_run_queues(struct hrtimer_cpu_base *cpu_base, ktime_t now, long unsigned int flags, unsigned int active_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffff8000101a10a0)
Location: kernel/time/hrtimer.c:1547
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_run_softirq
```
**Symbols:**

```
ffff8000101a10a0-ffff8000101a13fc: __hrtimer_run_queues (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __hrtimer_run_queues(struct hrtimer_cpu_base *cpu_base, ktime_t now, long unsigned int flags, unsigned int active_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c03eacd8)
Location: kernel/time/hrtimer.c:1547
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_run_softirq
```
**Symbols:**

```
c03eacd8-c03eb094: __hrtimer_run_queues (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __hrtimer_run_queues(struct hrtimer_cpu_base *cpu_base, ktime_t now, long unsigned int flags, unsigned int active_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c0000000002025d0)
Location: kernel/time/hrtimer.c:1547
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_run_softirq
```
**Symbols:**

```
c0000000002025d0-c0000000002029e8: __hrtimer_run_queues (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __hrtimer_run_queues(struct hrtimer_cpu_base *cpu_base, ktime_t now, long unsigned int flags, unsigned int active_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffe00012e826)
Location: kernel/time/hrtimer.c:1547
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_run_softirq
```
**Symbols:**

```
ffffffe00012e826-ffffffe00012eab2: __hrtimer_run_queues (STB_LOCAL)
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
void __hrtimer_run_queues(struct hrtimer_cpu_base *cpu_base, ktime_t now, long unsigned int flags, unsigned int active_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81130290)
Location: kernel/time/hrtimer.c:1547
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_run_softirq
```
**Symbols:**

```
ffffffff81130290-ffffffff81130500: __hrtimer_run_queues (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __hrtimer_run_queues(struct hrtimer_cpu_base *cpu_base, ktime_t now, long unsigned int flags, unsigned int active_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81122d00)
Location: kernel/time/hrtimer.c:1547
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_run_softirq
```
**Symbols:**

```
ffffffff81122d00-ffffffff81122f70: __hrtimer_run_queues (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __hrtimer_run_queues(struct hrtimer_cpu_base *cpu_base, ktime_t now, long unsigned int flags, unsigned int active_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112dfb0)
Location: kernel/time/hrtimer.c:1547
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_run_softirq
```
**Symbols:**

```
ffffffff8112dfb0-ffffffff8112e220: __hrtimer_run_queues (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __hrtimer_run_queues(struct hrtimer_cpu_base *cpu_base, ktime_t now, long unsigned int flags, unsigned int active_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8113a930)
Location: kernel/time/hrtimer.c:1547
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_run_softirq
```
**Symbols:**

```
ffffffff8113a930-ffffffff8113abeb: __hrtimer_run_queues (STB_LOCAL)
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
<code>long unsigned int flags</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int active_mask</code>
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
