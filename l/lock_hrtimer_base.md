# Function: <code>lock_hrtimer_base</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810eedf0)
Location: kernel/time/hrtimer.c:139
Inline: True
Direct callers:
  - kernel/time/hrtimer.c:__hrtimer_get_remaining
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff810eedf0-ffffffff810eee3c: lock_hrtimer_base.isra.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810f5eb0)
Location: kernel/time/hrtimer.c:139
Inline: True
Direct callers:
  - kernel/time/hrtimer.c:__hrtimer_get_remaining
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff810f5eb0-ffffffff810f5efc: lock_hrtimer_base.isra.21 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810fcfe0)
Location: kernel/time/hrtimer.c:139
Inline: True
Direct callers:
  - kernel/time/hrtimer.c:__hrtimer_get_remaining
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff810fcfe0-ffffffff810fd02c: lock_hrtimer_base.isra.23 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810ff370)
Location: kernel/time/hrtimer.c:140
Inline: True
Direct callers:
  - kernel/time/hrtimer.c:__hrtimer_get_remaining
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff810ff370-ffffffff810ff3bc: lock_hrtimer_base.isra.20 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8110a160)
Location: kernel/time/hrtimer.c:140
Inline: True
Direct callers:
  - kernel/time/hrtimer.c:__hrtimer_get_remaining
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff8110a160-ffffffff8110a1ac: lock_hrtimer_base.isra.20 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81115950)
Location: kernel/time/hrtimer.c:166
Inline: True
Direct callers:
  - kernel/time/hrtimer.c:__hrtimer_get_remaining
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff81115950-ffffffff8111599c: lock_hrtimer_base.isra.22 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81121020)
Location: kernel/time/hrtimer.c:157
Inline: True
Direct callers:
  - kernel/time/hrtimer.c:__hrtimer_get_remaining
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff81121020-ffffffff8112106c: lock_hrtimer_base.isra.24 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112b840)
Location: kernel/time/hrtimer.c:156
Inline: True
Direct callers:
  - kernel/time/hrtimer.c:__hrtimer_get_remaining
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff8112b840-ffffffff8112b88c: lock_hrtimer_base.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct hrtimer_clock_base *lock_hrtimer_base(const struct hrtimer *timer, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81137260)
Location: kernel/time/hrtimer.c:161
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__hrtimer_get_remaining
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff81137260-ffffffff811372ae: lock_hrtimer_base (STB_LOCAL)
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
In kernel/time/hrtimer.c (ffffffff81146513)
Location: kernel/time/hrtimer.c:161
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_get_remaining
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
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
In kernel/time/hrtimer.c (ffffffff81142b33)
Location: kernel/time/hrtimer.c:165
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_get_remaining
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
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
In kernel/time/hrtimer.c (ffffffff81144063)
Location: kernel/time/hrtimer.c:165
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_get_remaining
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
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
In kernel/time/hrtimer.c (ffffffff81167613)
Location: kernel/time/hrtimer.c:165
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_get_remaining
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
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
In kernel/time/hrtimer.c (ffffffff8119b1c3)
Location: kernel/time/hrtimer.c:165
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_get_remaining
  - kernel/time/hrtimer.c:hrtimer_try_to_cancel
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
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
In kernel/time/hrtimer.c (ffffffff811d9a23)
Location: kernel/time/hrtimer.c:165
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_get_remaining
  - kernel/time/hrtimer.c:hrtimer_try_to_cancel
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
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
In kernel/time/hrtimer.c (ffffffff811ee1d3)
Location: kernel/time/hrtimer.c:165
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_get_remaining
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
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
In kernel/time/hrtimer.c (ffffffff81203873)
Location: kernel/time/hrtimer.c:165
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_get_remaining
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
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
struct hrtimer_clock_base *lock_hrtimer_base(const struct hrtimer *timer, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffff8000101a0b90)
Location: kernel/time/hrtimer.c:161
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__hrtimer_get_remaining
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
ffff8000101a0b90-ffff8000101a0c90: lock_hrtimer_base (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct hrtimer_clock_base *lock_hrtimer_base(const struct hrtimer *timer, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c03ea1b8)
Location: kernel/time/hrtimer.c:161
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__hrtimer_get_remaining
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
c03ea1b8-c03ea23c: lock_hrtimer_base (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct hrtimer_clock_base *lock_hrtimer_base(const struct hrtimer *timer, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c000000000201520)
Location: kernel/time/hrtimer.c:161
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__hrtimer_get_remaining
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
c000000000201520-c0000000002015c8: lock_hrtimer_base (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct hrtimer_clock_base *lock_hrtimer_base(const struct hrtimer *timer, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffe00012dfe8)
Location: kernel/time/hrtimer.c:161
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__hrtimer_get_remaining
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
ffffffe00012dfe8-ffffffe00012e050: lock_hrtimer_base (STB_LOCAL)
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
struct hrtimer_clock_base *lock_hrtimer_base(const struct hrtimer *timer, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112fa10)
Location: kernel/time/hrtimer.c:161
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__hrtimer_get_remaining
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff8112fa10-ffffffff8112fa5e: lock_hrtimer_base (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct hrtimer_clock_base *lock_hrtimer_base(const struct hrtimer *timer, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81122480)
Location: kernel/time/hrtimer.c:161
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__hrtimer_get_remaining
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff81122480-ffffffff811224ce: lock_hrtimer_base (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct hrtimer_clock_base *lock_hrtimer_base(const struct hrtimer *timer, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112d730)
Location: kernel/time/hrtimer.c:161
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__hrtimer_get_remaining
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff8112d730-ffffffff8112d77e: lock_hrtimer_base (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct hrtimer_clock_base *lock_hrtimer_base(const struct hrtimer *timer, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8113a060)
Location: kernel/time/hrtimer.c:161
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__hrtimer_get_remaining
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
**Symbols:**

```
ffffffff8113a060-ffffffff8113a0ae: lock_hrtimer_base (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
