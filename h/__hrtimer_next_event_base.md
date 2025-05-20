# Function: <code>__hrtimer_next_event_base</code>

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
ktime_t __hrtimer_next_event_base(struct hrtimer_cpu_base *cpu_base, const struct hrtimer *exclude, unsigned int active, ktime_t expires_next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811154e0)
Location: kernel/time/hrtimer.c:492
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_next_event_without
  - kernel/time/hrtimer.c:hrtimer_next_event_without
  - kernel/time/hrtimer.c:__hrtimer_get_next_event
  - kernel/time/hrtimer.c:__hrtimer_get_next_event
```
**Symbols:**

```
ffffffff811154e0-ffffffff811155b6: __hrtimer_next_event_base (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ktime_t __hrtimer_next_event_base(struct hrtimer_cpu_base *cpu_base, const struct hrtimer *exclude, unsigned int active, ktime_t expires_next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81120b20)
Location: kernel/time/hrtimer.c:483
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_next_event_without
  - kernel/time/hrtimer.c:hrtimer_next_event_without
  - kernel/time/hrtimer.c:__hrtimer_get_next_event
  - kernel/time/hrtimer.c:__hrtimer_get_next_event
```
**Symbols:**

```
ffffffff81120b20-ffffffff81120bf6: __hrtimer_next_event_base (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ktime_t __hrtimer_next_event_base(struct hrtimer_cpu_base *cpu_base, const struct hrtimer *exclude, unsigned int active, ktime_t expires_next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112b330)
Location: kernel/time/hrtimer.c:482
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_next_event_without
  - kernel/time/hrtimer.c:hrtimer_next_event_without
  - kernel/time/hrtimer.c:__hrtimer_get_next_event
  - kernel/time/hrtimer.c:__hrtimer_get_next_event
```
**Symbols:**

```
ffffffff8112b330-ffffffff8112b402: __hrtimer_next_event_base (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ktime_t __hrtimer_next_event_base(struct hrtimer_cpu_base *cpu_base, const struct hrtimer *exclude, unsigned int active, ktime_t expires_next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81137410)
Location: kernel/time/hrtimer.c:503
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_next_event_without
  - kernel/time/hrtimer.c:hrtimer_next_event_without
  - kernel/time/hrtimer.c:__hrtimer_get_next_event
  - kernel/time/hrtimer.c:__hrtimer_get_next_event
```
**Symbols:**

```
ffffffff81137410-ffffffff811374e2: __hrtimer_next_event_base (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ktime_t __hrtimer_next_event_base(struct hrtimer_cpu_base *cpu_base, const struct hrtimer *exclude, unsigned int active, ktime_t expires_next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811460a0)
Location: kernel/time/hrtimer.c:503
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_run_softirq
  - kernel/time/hrtimer.c:hrtimer_next_event_without
  - kernel/time/hrtimer.c:hrtimer_next_event_without
  - kernel/time/hrtimer.c:hrtimer_force_reprogram
  - kernel/time/hrtimer.c:hrtimer_force_reprogram
  - kernel/time/hrtimer.c:hrtimer_force_reprogram
```
**Symbols:**

```
ffffffff811460a0-ffffffff81146175: __hrtimer_next_event_base (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ktime_t __hrtimer_next_event_base(struct hrtimer_cpu_base *cpu_base, const struct hrtimer *exclude, unsigned int active, ktime_t expires_next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811425c0)
Location: kernel/time/hrtimer.c:502
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_run_softirq
  - kernel/time/hrtimer.c:hrtimer_next_event_without
  - kernel/time/hrtimer.c:hrtimer_next_event_without
```
**Symbols:**

```
ffffffff811425c0-ffffffff81142695: __hrtimer_next_event_base (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ktime_t __hrtimer_next_event_base(struct hrtimer_cpu_base *cpu_base, const struct hrtimer *exclude, unsigned int active, ktime_t expires_next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811437a0)
Location: kernel/time/hrtimer.c:502
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_run_softirq
  - kernel/time/hrtimer.c:hrtimer_next_event_without
  - kernel/time/hrtimer.c:hrtimer_next_event_without
```
**Symbols:**

```
ffffffff811437a0-ffffffff8114386f: __hrtimer_next_event_base (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ktime_t __hrtimer_next_event_base(struct hrtimer_cpu_base *cpu_base, const struct hrtimer *exclude, unsigned int active, ktime_t expires_next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (0)
Location: kernel/time/hrtimer.c:502
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_run_softirq
  - kernel/time/hrtimer.c:hrtimer_next_event_without
  - kernel/time/hrtimer.c:hrtimer_next_event_without
  - kernel/time/hrtimer.c:hrtimer_update_next_event
  - kernel/time/hrtimer.c:hrtimer_update_next_event
  - kernel/time/hrtimer.c:hrtimer_update_next_event
```
**Symbols:**

```
ffffffff81166f70-ffffffff8116703a: __hrtimer_next_event_base (STB_LOCAL)
ffffffff81cb093a-ffffffff81cb0960: __hrtimer_next_event_base.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ktime_t __hrtimer_next_event_base(struct hrtimer_cpu_base *cpu_base, const struct hrtimer *exclude, unsigned int active, ktime_t expires_next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (0)
Location: kernel/time/hrtimer.c:502
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_run_softirq
  - kernel/time/hrtimer.c:hrtimer_next_event_without
  - kernel/time/hrtimer.c:hrtimer_next_event_without
  - kernel/time/hrtimer.c:hrtimer_update_next_event
  - kernel/time/hrtimer.c:hrtimer_update_next_event
  - kernel/time/hrtimer.c:hrtimer_update_next_event
```
**Symbols:**

```
ffffffff8119a7e0-ffffffff8119a8b7: __hrtimer_next_event_base (STB_LOCAL)
ffffffff81e61ec5-ffffffff81e61eeb: __hrtimer_next_event_base.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
ktime_t __hrtimer_next_event_base(struct hrtimer_cpu_base *cpu_base, const struct hrtimer *exclude, unsigned int active, ktime_t expires_next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (0)
Location: kernel/time/hrtimer.c:502
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_run_softirq
  - kernel/time/hrtimer.c:hrtimer_next_event_without
  - kernel/time/hrtimer.c:hrtimer_next_event_without
  - kernel/time/hrtimer.c:hrtimer_update_next_event
  - kernel/time/hrtimer.c:hrtimer_update_next_event
  - kernel/time/hrtimer.c:hrtimer_update_next_event
```
**Symbols:**

```
ffffffff811d8f90-ffffffff811d9068: __hrtimer_next_event_base (STB_LOCAL)
ffffffff8205ad96-ffffffff8205adbd: __hrtimer_next_event_base.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
ktime_t __hrtimer_next_event_base(struct hrtimer_cpu_base *cpu_base, const struct hrtimer *exclude, unsigned int active, ktime_t expires_next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (0)
Location: kernel/time/hrtimer.c:504
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_run_softirq
  - kernel/time/hrtimer.c:hrtimer_next_event_without
  - kernel/time/hrtimer.c:hrtimer_next_event_without
  - kernel/time/hrtimer.c:hrtimer_update_next_event
  - kernel/time/hrtimer.c:hrtimer_update_next_event
  - kernel/time/hrtimer.c:hrtimer_update_next_event
```
**Symbols:**

```
ffffffff811ed3d0-ffffffff811ed4cc: __hrtimer_next_event_base (STB_LOCAL)
ffffffff820d9645-ffffffff820d966c: __hrtimer_next_event_base.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
ktime_t __hrtimer_next_event_base(struct hrtimer_cpu_base *cpu_base, const struct hrtimer *exclude, unsigned int active, ktime_t expires_next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (0)
Location: kernel/time/hrtimer.c:504
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_cpu_dying
  - kernel/time/hrtimer.c:hrtimer_run_softirq
  - kernel/time/hrtimer.c:hrtimer_next_event_without
  - kernel/time/hrtimer.c:hrtimer_next_event_without
  - kernel/time/hrtimer.c:hrtimer_update_next_event
  - kernel/time/hrtimer.c:hrtimer_update_next_event
  - kernel/time/hrtimer.c:hrtimer_update_next_event
```
**Symbols:**

```
ffffffff81203550-ffffffff8120364c: __hrtimer_next_event_base (STB_LOCAL)
ffffffff821b4f44-ffffffff821b4f6b: __hrtimer_next_event_base.cold (STB_LOCAL)
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
ktime_t __hrtimer_next_event_base(struct hrtimer_cpu_base *cpu_base, const struct hrtimer *exclude, unsigned int active, ktime_t expires_next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffff8000101a0810)
Location: kernel/time/hrtimer.c:503
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_next_event_without
  - kernel/time/hrtimer.c:hrtimer_next_event_without
  - kernel/time/hrtimer.c:__hrtimer_get_next_event
  - kernel/time/hrtimer.c:__hrtimer_get_next_event
```
**Symbols:**

```
ffff8000101a0810-ffff8000101a0908: __hrtimer_next_event_base (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ktime_t __hrtimer_next_event_base(struct hrtimer_cpu_base *cpu_base, const struct hrtimer *exclude, unsigned int active, ktime_t expires_next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c03ea58c)
Location: kernel/time/hrtimer.c:503
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_next_event_without
  - kernel/time/hrtimer.c:hrtimer_next_event_without
  - kernel/time/hrtimer.c:__hrtimer_get_next_event
  - kernel/time/hrtimer.c:__hrtimer_get_next_event
```
**Symbols:**

```
c03ea58c-c03ea68c: __hrtimer_next_event_base (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ktime_t __hrtimer_next_event_base(struct hrtimer_cpu_base *cpu_base, const struct hrtimer *exclude, unsigned int active, ktime_t expires_next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c000000000201920)
Location: kernel/time/hrtimer.c:503
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_next_event_without
  - kernel/time/hrtimer.c:hrtimer_next_event_without
  - kernel/time/hrtimer.c:__hrtimer_get_next_event
  - kernel/time/hrtimer.c:__hrtimer_get_next_event
```
**Symbols:**

```
c000000000201920-c000000000201a98: __hrtimer_next_event_base (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ktime_t __hrtimer_next_event_base(struct hrtimer_cpu_base *cpu_base, const struct hrtimer *exclude, unsigned int active, ktime_t expires_next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffe00012e116)
Location: kernel/time/hrtimer.c:503
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_next_event_without
  - kernel/time/hrtimer.c:hrtimer_next_event_without
  - kernel/time/hrtimer.c:__hrtimer_get_next_event
  - kernel/time/hrtimer.c:__hrtimer_get_next_event
```
**Symbols:**

```
ffffffe00012e116-ffffffe00012e1ac: __hrtimer_next_event_base (STB_LOCAL)
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
ktime_t __hrtimer_next_event_base(struct hrtimer_cpu_base *cpu_base, const struct hrtimer *exclude, unsigned int active, ktime_t expires_next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112fbc0)
Location: kernel/time/hrtimer.c:503
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_next_event_without
  - kernel/time/hrtimer.c:hrtimer_next_event_without
  - kernel/time/hrtimer.c:__hrtimer_get_next_event
  - kernel/time/hrtimer.c:__hrtimer_get_next_event
```
**Symbols:**

```
ffffffff8112fbc0-ffffffff8112fc92: __hrtimer_next_event_base (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ktime_t __hrtimer_next_event_base(struct hrtimer_cpu_base *cpu_base, const struct hrtimer *exclude, unsigned int active, ktime_t expires_next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81122630)
Location: kernel/time/hrtimer.c:503
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_next_event_without
  - kernel/time/hrtimer.c:hrtimer_next_event_without
  - kernel/time/hrtimer.c:__hrtimer_get_next_event
  - kernel/time/hrtimer.c:__hrtimer_get_next_event
```
**Symbols:**

```
ffffffff81122630-ffffffff81122702: __hrtimer_next_event_base (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ktime_t __hrtimer_next_event_base(struct hrtimer_cpu_base *cpu_base, const struct hrtimer *exclude, unsigned int active, ktime_t expires_next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112d8e0)
Location: kernel/time/hrtimer.c:503
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_next_event_without
  - kernel/time/hrtimer.c:hrtimer_next_event_without
  - kernel/time/hrtimer.c:__hrtimer_get_next_event
  - kernel/time/hrtimer.c:__hrtimer_get_next_event
```
**Symbols:**

```
ffffffff8112d8e0-ffffffff8112d9b2: __hrtimer_next_event_base (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ktime_t __hrtimer_next_event_base(struct hrtimer_cpu_base *cpu_base, const struct hrtimer *exclude, unsigned int active, ktime_t expires_next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8113a210)
Location: kernel/time/hrtimer.c:503
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_next_event_without
  - kernel/time/hrtimer.c:hrtimer_next_event_without
  - kernel/time/hrtimer.c:__hrtimer_get_next_event
  - kernel/time/hrtimer.c:__hrtimer_get_next_event
```
**Symbols:**

```
ffffffff8113a210-ffffffff8113a2e2: __hrtimer_next_event_base (STB_LOCAL)
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
