# Function: <code>__run_timers</code>

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
In kernel/time/timer.c (ffffffff810ecb05)
Location: kernel/time/timer.c:1205
Inline: True
Inline callers:
  - kernel/time/timer.c:run_timer_softirq
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
In kernel/time/timer.c (ffffffff810f3fb4)
Location: kernel/time/timer.c:1611
Inline: True
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
In kernel/time/timer.c (ffffffff810fb154)
Location: kernel/time/timer.c:1626
Inline: True
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
In kernel/time/timer.c (ffffffff810fd4b4)
Location: kernel/time/timer.c:1604
Inline: True
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
In kernel/time/timer.c (ffffffff81107bf4)
Location: kernel/time/timer.c:1642
Inline: True
Inline callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
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
In kernel/time/timer.c (ffffffff811149a4)
Location: kernel/time/timer.c:1650
Inline: True
Inline callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
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
In kernel/time/timer.c (ffffffff8111f144)
Location: kernel/time/timer.c:1649
Inline: True
Inline callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
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
In kernel/time/timer.c (ffffffff811298b8)
Location: kernel/time/timer.c:1653
Inline: True
Inline callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
Direct callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
```
**Symbols:**

```
ffffffff81129620-ffffffff81129897: __run_timers.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/timer.c (ffffffff81135858)
Location: kernel/time/timer.c:1740
Inline: True
Inline callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
Direct callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
```
**Symbols:**

```
ffffffff811355c0-ffffffff81135835: __run_timers.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/timer.c (ffffffff81145738)
Location: kernel/time/timer.c:1759
Inline: True
Inline callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
Direct callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
```
**Symbols:**

```
ffffffff811454a0-ffffffff81145712: __run_timers.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/timer.c (ffffffff81141808)
Location: kernel/time/timer.c:1707
Inline: True
Inline callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
Direct callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
```
**Symbols:**

```
ffffffff811415a0-ffffffff811417e8: __run_timers.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/timer.c (ffffffff81143018)
Location: kernel/time/timer.c:1724
Inline: True
Inline callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
Direct callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
```
**Symbols:**

```
ffffffff81142db0-ffffffff81142ff6: __run_timers.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/timer.c (ffffffff811665a8)
Location: kernel/time/timer.c:1710
Inline: True
Inline callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
Direct callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
```
**Symbols:**

```
ffffffff81166340-ffffffff81166589: __run_timers.part.0 (STB_LOCAL)
ffffffff81cb08d6-ffffffff81cb08ea: __run_timers.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __run_timers(struct timer_base *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timer.c (0)
Location: kernel/time/timer.c:1763
Inline: False
Direct callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
```
**Symbols:**

```
ffffffff81198f60-ffffffff8119924b: __run_timers (STB_LOCAL)
ffffffff81e61e4b-ffffffff81e61e75: __run_timers.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __run_timers(struct timer_base *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timer.c (0)
Location: kernel/time/timer.c:1995
Inline: False
Direct callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
```
**Symbols:**

```
ffffffff811d74c0-ffffffff811d77c7: __run_timers (STB_LOCAL)
ffffffff8205ad1e-ffffffff8205ad46: __run_timers.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __run_timers(struct timer_base *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timer.c (0)
Location: kernel/time/timer.c:1995
Inline: False
Direct callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
```
**Symbols:**

```
ffffffff811eb820-ffffffff811ebb27: __run_timers (STB_LOCAL)
ffffffff820d95b9-ffffffff820d95e1: __run_timers.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __run_timers(struct timer_base *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timer.c (0)
Location: kernel/time/timer.c:2007
Inline: False
Direct callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
```
**Symbols:**

```
ffffffff81201970-ffffffff81201c62: __run_timers (STB_LOCAL)
ffffffff821b4e6e-ffffffff821b4e96: __run_timers.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/timer.c (ffff80001019ea64)
Location: kernel/time/timer.c:1740
Inline: True
Inline callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
Direct callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
```
**Symbols:**

```
ffff80001019e6f0-ffff80001019ea38: __run_timers.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c03e8340)
Location: kernel/time/timer.c:1740
Inline: True
Inline callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c0000000001fe7f8)
Location: kernel/time/timer.c:1740
Inline: True
Inline callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
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
In kernel/time/timer.c (ffffffe00012c4ec)
Location: kernel/time/timer.c:1740
Inline: True
Inline callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/timer.c (ffffffff8112e008)
Location: kernel/time/timer.c:1740
Inline: True
Inline callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
Direct callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
```
**Symbols:**

```
ffffffff8112dd70-ffffffff8112dfe5: __run_timers.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81120634)
Location: kernel/time/timer.c:1740
Inline: True
Inline callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/timer.c (ffffffff8112bd28)
Location: kernel/time/timer.c:1740
Inline: True
Inline callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
Direct callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
```
**Symbols:**

```
ffffffff8112ba90-ffffffff8112bd05: __run_timers.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81138194)
Location: kernel/time/timer.c:1740
Inline: True
Inline callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
