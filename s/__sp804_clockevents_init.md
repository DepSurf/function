# Function: <code>__sp804_clockevents_init</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int __sp804_clockevents_init(void *base, unsigned int irq, struct clk *clk, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/timer-sp804.c (ffff8000114a9ce8)
Location: drivers/clocksource/timer-sp804.c:178
Inline: False
Direct callers:
  - drivers/clocksource/timer-sp804.c:integrator_cp_of_init
  - drivers/clocksource/timer-sp804.c:sp804_of_init
  - drivers/clocksource/timer-sp804.c:sp804_of_init
```
**Symbols:**

```
ffff8000114a9ce8-ffff8000114a9df8: __sp804_clockevents_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __sp804_clockevents_init(void *base, unsigned int irq, struct clk *clk, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/timer-sp804.c (c15adcb8)
Location: drivers/clocksource/timer-sp804.c:178
Inline: False
Direct callers:
  - drivers/clocksource/timer-sp804.c:integrator_cp_of_init
  - drivers/clocksource/timer-sp804.c:sp804_of_init
  - drivers/clocksource/timer-sp804.c:sp804_of_init
```
**Symbols:**

```
c15adcb8-c15adda8: __sp804_clockevents_init (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
