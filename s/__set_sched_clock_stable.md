# Function: <code>__set_sched_clock_stable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __set_sched_clock_stable();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810b11b0)
Location: kernel/sched/clock.c:88
Inline: False
Direct callers:
  - kernel/sched/clock.c:set_sched_clock_stable
  - kernel/sched/clock.c:sched_clock_init
```
**Symbols:**

```
ffffffff810b11b0-ffffffff810b11c8: __set_sched_clock_stable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __set_sched_clock_stable();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810b3c60)
Location: kernel/sched/clock.c:89
Inline: False
Direct callers:
  - kernel/sched/clock.c:sched_clock_init
  - kernel/sched/clock.c:set_sched_clock_stable
```
**Symbols:**

```
ffffffff810b3c60-ffffffff810b3c78: __set_sched_clock_stable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __set_sched_clock_stable();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810ba2a0)
Location: kernel/sched/clock.c:89
Inline: False
Direct callers:
  - kernel/sched/clock.c:sched_clock_init
  - kernel/sched/clock.c:set_sched_clock_stable
```
**Symbols:**

```
ffffffff810ba2a0-ffffffff810ba2b8: __set_sched_clock_stable (STB_LOCAL)
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
In kernel/sched/clock.c (ffffffff820c3880)
Location: kernel/sched/clock.c:134
Inline: True
Inline callers:
  - kernel/sched/clock.c:sched_clock_init_late
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
In kernel/sched/clock.c (ffffffff826cb8b0)
Location: kernel/sched/clock.c:134
Inline: True
Inline callers:
  - kernel/sched/clock.c:sched_clock_init_late
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
In kernel/sched/clock.c (ffffffff826f59ff)
Location: kernel/sched/clock.c:122
Inline: True
Inline callers:
  - kernel/sched/clock.c:sched_clock_init_late
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
In kernel/sched/clock.c (ffffffff828ac828)
Location: kernel/sched/clock.c:118
Inline: True
Inline callers:
  - kernel/sched/clock.c:sched_clock_init_late
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff828c5164)
Location: kernel/sched/clock.c:119
Inline: True
Inline callers:
  - kernel/sched/clock.c:sched_clock_init_late
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff828cd7cd)
Location: kernel/sched/clock.c:119
Inline: True
Inline callers:
  - kernel/sched/clock.c:sched_clock_init_late
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
In kernel/sched/clock.c (ffffffff82ceeb0c)
Location: kernel/sched/clock.c:119
Inline: True
Inline callers:
  - kernel/sched/clock.c:sched_clock_init_late
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
In kernel/sched/clock.c (ffffffff82fdb223)
Location: kernel/sched/clock.c:119
Inline: True
Inline callers:
  - kernel/sched/clock.c:sched_clock_init_late
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
In kernel/sched/clock.c (ffffffff831e5ddc)
Location: kernel/sched/clock.c:119
Inline: True
Inline callers:
  - kernel/sched/clock.c:sched_clock_init_late
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
In kernel/sched/clock.c (ffffffff832c9e79)
Location: kernel/sched/clock.c:119
Inline: True
Inline callers:
  - kernel/sched/clock.c:sched_clock_init_late
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __set_sched_clock_stable();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81e5696b)
Location: kernel/sched/clock.c:117
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sched_clock_init_late
```
**Symbols:**

```
ffffffff81e5696b-ffffffff81e569df: __set_sched_clock_stable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __set_sched_clock_stable();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811671a0)
Location: kernel/sched/clock.c:117
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sched_clock_init_late
```
**Symbols:**

```
ffffffff811671a0-ffffffff81167214: __set_sched_clock_stable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __set_sched_clock_stable();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811775e0)
Location: kernel/sched/clock.c:117
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sched_clock_init_late
```
**Symbols:**

```
ffffffff811775e0-ffffffff81177654: __set_sched_clock_stable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __set_sched_clock_stable();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/clock.c:117
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sched_clock_init_late
```
**Symbols:**

```
ffffffff8118c0c0-ffffffff8118c171: __set_sched_clock_stable (STB_LOCAL)
ffffffff821b1724-ffffffff821b1738: __set_sched_clock_stable.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff828b655d)
Location: kernel/sched/clock.c:119
Inline: True
Inline callers:
  - kernel/sched/clock.c:sched_clock_init_late
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
In kernel/sched/clock.c (ffffffff828ae74a)
Location: kernel/sched/clock.c:119
Inline: True
Inline callers:
  - kernel/sched/clock.c:sched_clock_init_late
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff828c9401)
Location: kernel/sched/clock.c:119
Inline: True
Inline callers:
  - kernel/sched/clock.c:sched_clock_init_late
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
In kernel/sched/clock.c (ffffffff828ce7b3)
Location: kernel/sched/clock.c:119
Inline: True
Inline callers:
  - kernel/sched/clock.c:sched_clock_init_late
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
