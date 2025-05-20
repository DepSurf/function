# Function: <code>update_wall_time</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void update_wall_time();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810f61c0)
Location: kernel/time/timekeeping.c:2034
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:xtime_update
  - kernel/time/tick-common.c:tick_periodic
  - kernel/time/tick-sched.c:tick_do_update_jiffies64
```
**Symbols:**

```
ffffffff810f61c0-ffffffff810f6959: update_wall_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void update_wall_time();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810fd3e0)
Location: kernel/time/timekeeping.c:2039
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:xtime_update
  - kernel/time/tick-common.c:tick_periodic
  - kernel/time/tick-sched.c:tick_do_update_jiffies64
```
**Symbols:**

```
ffffffff810fd3e0-ffffffff810fdb59: update_wall_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void update_wall_time();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811001d0)
Location: kernel/time/timekeeping.c:2051
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:xtime_update
  - kernel/time/tick-common.c:tick_periodic
```
**Symbols:**

```
ffffffff811001d0-ffffffff81100949: update_wall_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void update_wall_time();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811023a0)
Location: kernel/time/timekeeping.c:2040
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:xtime_update
  - kernel/time/tick-common.c:tick_periodic
```
**Symbols:**

```
ffffffff811023a0-ffffffff81102a88: update_wall_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void update_wall_time();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8110d340)
Location: kernel/time/timekeeping.c:2075
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:xtime_update
  - kernel/time/tick-common.c:tick_periodic
```
**Symbols:**

```
ffffffff8110d340-ffffffff8110da2b: update_wall_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void update_wall_time();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:2028
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:xtime_update
  - kernel/time/tick-common.c:tick_periodic
```
**Symbols:**

```
ffffffff8111985d-ffffffff81119880: update_wall_time.cold.23 (STB_LOCAL)
ffffffff81118ec0-ffffffff81119448: update_wall_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void update_wall_time();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81124d44)
Location: kernel/time/timekeeping.c:2125
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
Direct callers:
  - kernel/time/tick-common.c:tick_periodic
```
**Symbols:**

```
ffffffff81124920-ffffffff81124932: update_wall_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void update_wall_time();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8112f725)
Location: kernel/time/timekeeping.c:2135
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
Direct callers:
  - kernel/time/tick-common.c:tick_periodic
```
**Symbols:**

```
ffffffff8112f260-ffffffff8112f272: update_wall_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void update_wall_time();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8113b6e5)
Location: kernel/time/timekeeping.c:2135
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
Direct callers:
  - kernel/time/tick-common.c:tick_periodic
```
**Symbols:**

```
ffffffff8113b220-ffffffff8113b232: update_wall_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void update_wall_time();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8114a735)
Location: kernel/time/timekeeping.c:2134
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
Direct callers:
  - kernel/time/tick-common.c:tick_periodic
```
**Symbols:**

```
ffffffff8114a270-ffffffff8114a282: update_wall_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void update_wall_time();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811467c0)
Location: kernel/time/timekeeping.c:2197
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_periodic
```
**Symbols:**

```
ffffffff811467c0-ffffffff811467d2: update_wall_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void update_wall_time();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81147930)
Location: kernel/time/timekeeping.c:2208
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_periodic
```
**Symbols:**

```
ffffffff81147930-ffffffff81147942: update_wall_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void update_wall_time();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8116b450)
Location: kernel/time/timekeeping.c:2208
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_periodic
```
**Symbols:**

```
ffffffff8116b450-ffffffff8116b46d: update_wall_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void update_wall_time();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8119f350)
Location: kernel/time/timekeeping.c:2229
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_periodic
```
**Symbols:**

```
ffffffff8119f350-ffffffff8119f37d: update_wall_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void update_wall_time();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811de020)
Location: kernel/time/timekeeping.c:2229
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_periodic
```
**Symbols:**

```
ffffffff811de020-ffffffff811de04d: update_wall_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void update_wall_time();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811f24f0)
Location: kernel/time/timekeeping.c:2229
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_periodic
```
**Symbols:**

```
ffffffff811f24f0-ffffffff811f251d: update_wall_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void update_wall_time();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81208630)
Location: kernel/time/timekeeping.c:2229
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_periodic
```
**Symbols:**

```
ffffffff81208630-ffffffff8120865d: update_wall_time (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void update_wall_time();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffff8000101a59ac)
Location: kernel/time/timekeeping.c:2135
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
Direct callers:
  - kernel/time/tick-common.c:tick_periodic
```
**Symbols:**

```
ffff8000101a5420-ffff8000101a5440: update_wall_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void update_wall_time();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (c03f09bc)
Location: kernel/time/timekeeping.c:2135
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
Direct callers:
  - kernel/time/tick-common.c:tick_periodic
```
**Symbols:**

```
c03f03d0-c03f03f0: update_wall_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void update_wall_time();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (c0000000002078ac)
Location: kernel/time/timekeeping.c:2135
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
Direct callers:
  - kernel/time/tick-common.c:tick_periodic
```
**Symbols:**

```
c0000000002071f0-c000000000207208: update_wall_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void update_wall_time();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffe000131d24)
Location: kernel/time/timekeeping.c:2135
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
Direct callers:
  - kernel/time/tick-common.c:tick_periodic
```
**Symbols:**

```
ffffffe00013188c-ffffffe0001318b0: update_wall_time (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void update_wall_time();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81133e95)
Location: kernel/time/timekeeping.c:2135
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
Direct callers:
  - kernel/time/tick-common.c:tick_periodic
```
**Symbols:**

```
ffffffff811339d0-ffffffff811339e2: update_wall_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void update_wall_time();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811268f5)
Location: kernel/time/timekeeping.c:2135
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
Direct callers:
  - kernel/time/tick-common.c:tick_periodic
```
**Symbols:**

```
ffffffff81126430-ffffffff81126442: update_wall_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void update_wall_time();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81131bb5)
Location: kernel/time/timekeeping.c:2135
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
Direct callers:
  - kernel/time/tick-common.c:tick_periodic
```
**Symbols:**

```
ffffffff811316f0-ffffffff81131702: update_wall_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void update_wall_time();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8113e5d3)
Location: kernel/time/timekeeping.c:2135
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
Direct callers:
  - kernel/time/tick-common.c:tick_periodic
```
**Symbols:**

```
ffffffff8113e110-ffffffff8113e122: update_wall_time (STB_GLOBAL)
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
