# Function: <code>clocksource_stop_suspend_timing</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 clocksource_stop_suspend_timing(struct clocksource *cs, u64 cycle_now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff81126b80)
Location: kernel/time/clocksource.c:556
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_resume
```
**Symbols:**

```
ffffffff81126b80-ffffffff81126c46: clocksource_stop_suspend_timing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 clocksource_stop_suspend_timing(struct clocksource *cs, u64 cycle_now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff81131530)
Location: kernel/time/clocksource.c:556
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_resume
```
**Symbols:**

```
ffffffff81131530-ffffffff811315f9: clocksource_stop_suspend_timing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 clocksource_stop_suspend_timing(struct clocksource *cs, u64 cycle_now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff8113d480)
Location: kernel/time/clocksource.c:563
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_resume
```
**Symbols:**

```
ffffffff8113d480-ffffffff8113d549: clocksource_stop_suspend_timing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 clocksource_stop_suspend_timing(struct clocksource *cs, u64 cycle_now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff8114c610)
Location: kernel/time/clocksource.c:563
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_resume
```
**Symbols:**

```
ffffffff8114c610-ffffffff8114c6ce: clocksource_stop_suspend_timing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 clocksource_stop_suspend_timing(struct clocksource *cs, u64 cycle_now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff81148a70)
Location: kernel/time/clocksource.c:563
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_resume
```
**Symbols:**

```
ffffffff81148a70-ffffffff81148b2e: clocksource_stop_suspend_timing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 clocksource_stop_suspend_timing(struct clocksource *cs, u64 cycle_now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff81149f70)
Location: kernel/time/clocksource.c:664
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_resume
```
**Symbols:**

```
ffffffff81149f70-ffffffff8114a02e: clocksource_stop_suspend_timing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u64 clocksource_stop_suspend_timing(struct clocksource *cs, u64 cycle_now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clocksource.c (0)
Location: kernel/time/clocksource.c:776
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_resume
```
**Symbols:**

```
ffffffff81cb1a9a-ffffffff81cb1ac4: clocksource_stop_suspend_timing.cold (STB_LOCAL)
ffffffff8116dc90-ffffffff8116dd92: clocksource_stop_suspend_timing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u64 clocksource_stop_suspend_timing(struct clocksource *cs, u64 cycle_now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clocksource.c (0)
Location: kernel/time/clocksource.c:782
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_resume
```
**Symbols:**

```
ffffffff81e63045-ffffffff81e6306f: clocksource_stop_suspend_timing.cold (STB_LOCAL)
ffffffff811a1e70-ffffffff811a1f82: clocksource_stop_suspend_timing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
u64 clocksource_stop_suspend_timing(struct clocksource *cs, u64 cycle_now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clocksource.c (0)
Location: kernel/time/clocksource.c:801
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_resume
```
**Symbols:**

```
ffffffff8205b9de-ffffffff8205ba08: clocksource_stop_suspend_timing.cold (STB_LOCAL)
ffffffff811e1300-ffffffff811e1412: clocksource_stop_suspend_timing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u64 clocksource_stop_suspend_timing(struct clocksource *cs, u64 cycle_now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clocksource.c (0)
Location: kernel/time/clocksource.c:812
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_resume
```
**Symbols:**

```
ffffffff820da1e0-ffffffff820da20a: clocksource_stop_suspend_timing.cold (STB_LOCAL)
ffffffff811f5860-ffffffff811f5972: clocksource_stop_suspend_timing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u64 clocksource_stop_suspend_timing(struct clocksource *cs, u64 cycle_now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clocksource.c (0)
Location: kernel/time/clocksource.c:835
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_resume
```
**Symbols:**

```
ffffffff821b5adf-ffffffff821b5b09: clocksource_stop_suspend_timing.cold (STB_LOCAL)
ffffffff8120ba00-ffffffff8120bb12: clocksource_stop_suspend_timing (STB_GLOBAL)
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
u64 clocksource_stop_suspend_timing(struct clocksource *cs, u64 cycle_now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffff8000101a7050)
Location: kernel/time/clocksource.c:563
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_resume
```
**Symbols:**

```
ffff8000101a7050-ffff8000101a713c: clocksource_stop_suspend_timing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 clocksource_stop_suspend_timing(struct clocksource *cs, u64 cycle_now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (c03f20fc)
Location: kernel/time/clocksource.c:563
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_resume
```
**Symbols:**

```
c03f20fc-c03f21fc: clocksource_stop_suspend_timing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 clocksource_stop_suspend_timing(struct clocksource *cs, u64 cycle_now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (c0000000002099f0)
Location: kernel/time/clocksource.c:563
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_resume
```
**Symbols:**

```
c0000000002099f0-c000000000209b24: clocksource_stop_suspend_timing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 clocksource_stop_suspend_timing(struct clocksource *cs, u64 cycle_now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffe0001330c8)
Location: kernel/time/clocksource.c:563
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_resume
```
**Symbols:**

```
ffffffe0001330c8-ffffffe000133184: clocksource_stop_suspend_timing (STB_GLOBAL)
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
u64 clocksource_stop_suspend_timing(struct clocksource *cs, u64 cycle_now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff81135c30)
Location: kernel/time/clocksource.c:563
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_resume
```
**Symbols:**

```
ffffffff81135c30-ffffffff81135cf9: clocksource_stop_suspend_timing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 clocksource_stop_suspend_timing(struct clocksource *cs, u64 cycle_now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff81128680)
Location: kernel/time/clocksource.c:563
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_resume
```
**Symbols:**

```
ffffffff81128680-ffffffff81128749: clocksource_stop_suspend_timing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 clocksource_stop_suspend_timing(struct clocksource *cs, u64 cycle_now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff81133950)
Location: kernel/time/clocksource.c:563
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_resume
```
**Symbols:**

```
ffffffff81133950-ffffffff81133a19: clocksource_stop_suspend_timing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 clocksource_stop_suspend_timing(struct clocksource *cs, u64 cycle_now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff81140370)
Location: kernel/time/clocksource.c:563
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_resume
```
**Symbols:**

```
ffffffff81140370-ffffffff81140439: clocksource_stop_suspend_timing (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
