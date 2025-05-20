# Function: <code>hrtimer_interrupt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void hrtimer_interrupt(struct clock_event_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810ef930)
Location: kernel/time/hrtimer.c:1323
Inline: False
```
**Symbols:**

```
ffffffff810ef930-ffffffff810efac3: hrtimer_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void hrtimer_interrupt(struct clock_event_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810f69b0)
Location: kernel/time/hrtimer.c:1313
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
**Symbols:**

```
ffffffff810f69b0-ffffffff810f6b2e: hrtimer_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void hrtimer_interrupt(struct clock_event_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810fda00)
Location: kernel/time/hrtimer.c:1313
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
**Symbols:**

```
ffffffff810fda00-ffffffff810fdbd4: hrtimer_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void hrtimer_interrupt(struct clock_event_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810ffc80)
Location: kernel/time/hrtimer.c:1288
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
**Symbols:**

```
ffffffff810ffc80-ffffffff810ffe48: hrtimer_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void hrtimer_interrupt(struct clock_event_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8110aa70)
Location: kernel/time/hrtimer.c:1293
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
**Symbols:**

```
ffffffff8110aa70-ffffffff8110ac38: hrtimer_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void hrtimer_interrupt(struct clock_event_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (0)
Location: kernel/time/hrtimer.c:1488
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
**Symbols:**

```
ffffffff81116e13-ffffffff81116e2e: hrtimer_interrupt.cold.26 (STB_LOCAL)
ffffffff811163c0-ffffffff811165d3: hrtimer_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void hrtimer_interrupt(struct clock_event_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (0)
Location: kernel/time/hrtimer.c:1479
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
**Symbols:**

```
ffffffff81122453-ffffffff8112246e: hrtimer_interrupt.cold.28 (STB_LOCAL)
ffffffff81121a00-ffffffff81121c13: hrtimer_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void hrtimer_interrupt(struct clock_event_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (0)
Location: kernel/time/hrtimer.c:1479
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
**Symbols:**

```
ffffffff8112cd8a-ffffffff8112cda5: hrtimer_interrupt.cold (STB_LOCAL)
ffffffff8112c330-ffffffff8112c54b: hrtimer_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void hrtimer_interrupt(struct clock_event_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (0)
Location: kernel/time/hrtimer.c:1611
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
**Symbols:**

```
ffffffff81138d57-ffffffff81138d72: hrtimer_interrupt.cold (STB_LOCAL)
ffffffff81138350-ffffffff8113856b: hrtimer_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void hrtimer_interrupt(struct clock_event_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (0)
Location: kernel/time/hrtimer.c:1616
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
**Symbols:**

```
ffffffff81147cb7-ffffffff81147cd2: hrtimer_interrupt.cold (STB_LOCAL)
ffffffff81147160-ffffffff81147373: hrtimer_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void hrtimer_interrupt(struct clock_event_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (0)
Location: kernel/time/hrtimer.c:1633
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
**Symbols:**

```
ffffffff81be3837-ffffffff81be3852: hrtimer_interrupt.cold (STB_LOCAL)
ffffffff81143600-ffffffff8114388b: hrtimer_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void hrtimer_interrupt(struct clock_event_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (0)
Location: kernel/time/hrtimer.c:1633
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
**Symbols:**

```
ffffffff81bd56b9-ffffffff81bd56d4: hrtimer_interrupt.cold (STB_LOCAL)
ffffffff811447b0-ffffffff81144a3c: hrtimer_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void hrtimer_interrupt(struct clock_event_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (0)
Location: kernel/time/hrtimer.c:1781
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
**Symbols:**

```
ffffffff81cb09c6-ffffffff81cb09f5: hrtimer_interrupt.cold (STB_LOCAL)
ffffffff81168070-ffffffff81168288: hrtimer_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void hrtimer_interrupt(struct clock_event_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (0)
Location: kernel/time/hrtimer.c:1781
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
**Symbols:**

```
ffffffff81e61f5c-ffffffff81e61f8c: hrtimer_interrupt.cold (STB_LOCAL)
ffffffff8119ba60-ffffffff8119bc8d: hrtimer_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void hrtimer_interrupt(struct clock_event_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (0)
Location: kernel/time/hrtimer.c:1781
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
**Symbols:**

```
ffffffff8205ae28-ffffffff8205ae3d: hrtimer_interrupt.cold (STB_LOCAL)
ffffffff811da370-ffffffff811da5b1: hrtimer_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void hrtimer_interrupt(struct clock_event_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (0)
Location: kernel/time/hrtimer.c:1784
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
**Symbols:**

```
ffffffff820d96dc-ffffffff820d96f1: hrtimer_interrupt.cold (STB_LOCAL)
ffffffff811ee8a0-ffffffff811eeae1: hrtimer_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void hrtimer_interrupt(struct clock_event_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (0)
Location: kernel/time/hrtimer.c:1785
Inline: False
```
**Symbols:**

```
ffffffff821b4fdb-ffffffff821b4ff0: hrtimer_interrupt.cold (STB_LOCAL)
ffffffff81204a20-ffffffff81204c61: hrtimer_interrupt (STB_GLOBAL)
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
void hrtimer_interrupt(struct clock_event_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffff8000101a1e98)
Location: kernel/time/hrtimer.c:1611
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
**Symbols:**

```
ffff8000101a1e98-ffff8000101a218c: hrtimer_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void hrtimer_interrupt(struct clock_event_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c03ebc20)
Location: kernel/time/hrtimer.c:1611
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
**Symbols:**

```
c03ebc20-c03ebef0: hrtimer_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void hrtimer_interrupt(struct clock_event_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c000000000203330)
Location: kernel/time/hrtimer.c:1611
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
**Symbols:**

```
c000000000203330-c000000000203628: hrtimer_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void hrtimer_interrupt(struct clock_event_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffe00012f13e)
Location: kernel/time/hrtimer.c:1611
Inline: False
```
**Symbols:**

```
ffffffe00012f13e-ffffffe00012f33e: hrtimer_interrupt (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void hrtimer_interrupt(struct clock_event_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (0)
Location: kernel/time/hrtimer.c:1611
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
**Symbols:**

```
ffffffff81131507-ffffffff81131522: hrtimer_interrupt.cold (STB_LOCAL)
ffffffff81130b00-ffffffff81130d1b: hrtimer_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void hrtimer_interrupt(struct clock_event_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (0)
Location: kernel/time/hrtimer.c:1611
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
**Symbols:**

```
ffffffff81123f6b-ffffffff81123f86: hrtimer_interrupt.cold (STB_LOCAL)
ffffffff81123570-ffffffff8112378b: hrtimer_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void hrtimer_interrupt(struct clock_event_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (0)
Location: kernel/time/hrtimer.c:1611
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
**Symbols:**

```
ffffffff8112f227-ffffffff8112f242: hrtimer_interrupt.cold (STB_LOCAL)
ffffffff8112e820-ffffffff8112ea3b: hrtimer_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void hrtimer_interrupt(struct clock_event_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (0)
Location: kernel/time/hrtimer.c:1611
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
**Symbols:**

```
ffffffff8113bc42-ffffffff8113bc5d: hrtimer_interrupt.cold (STB_LOCAL)
ffffffff8113b220-ffffffff8113b43b: hrtimer_interrupt (STB_GLOBAL)
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
