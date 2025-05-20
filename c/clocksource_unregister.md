# Function: <code>clocksource_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int clocksource_unregister(struct clocksource *cs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff810f8240)
Location: kernel/time/clocksource.c:792
Inline: False
```
**Symbols:**

```
ffffffff810f8240-ffffffff810f8287: clocksource_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int clocksource_unregister(struct clocksource *cs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff810ff4b0)
Location: kernel/time/clocksource.c:826
Inline: False
```
**Symbols:**

```
ffffffff810ff4b0-ffffffff810ff4fa: clocksource_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int clocksource_unregister(struct clocksource *cs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff81102320)
Location: kernel/time/clocksource.c:836
Inline: False
```
**Symbols:**

```
ffffffff81102320-ffffffff8110236a: clocksource_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int clocksource_unregister(struct clocksource *cs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff811044a0)
Location: kernel/time/clocksource.c:843
Inline: False
```
**Symbols:**

```
ffffffff811044a0-ffffffff811044ea: clocksource_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int clocksource_unregister(struct clocksource *cs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff8110f520)
Location: kernel/time/clocksource.c:842
Inline: False
```
**Symbols:**

```
ffffffff8110f520-ffffffff8110f56a: clocksource_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int clocksource_unregister(struct clocksource *cs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff8111af00)
Location: kernel/time/clocksource.c:880
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:init_tsc_clocksource
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
```
**Symbols:**

```
ffffffff8111af00-ffffffff8111af4a: clocksource_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int clocksource_unregister(struct clocksource *cs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff81126400)
Location: kernel/time/clocksource.c:1013
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:init_tsc_clocksource
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
```
**Symbols:**

```
ffffffff81126400-ffffffff8112644a: clocksource_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int clocksource_unregister(struct clocksource *cs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff81130e20)
Location: kernel/time/clocksource.c:1013
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:init_tsc_clocksource
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
```
**Symbols:**

```
ffffffff81130e20-ffffffff81130e6e: clocksource_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int clocksource_unregister(struct clocksource *cs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff8113cd60)
Location: kernel/time/clocksource.c:1020
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:init_tsc_clocksource
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock
```
**Symbols:**

```
ffffffff8113cd60-ffffffff8113cdae: clocksource_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int clocksource_unregister(struct clocksource *cs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff8114bb90)
Location: kernel/time/clocksource.c:1027
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:init_tsc_clocksource
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock
```
**Symbols:**

```
ffffffff8114bb90-ffffffff8114bbde: clocksource_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int clocksource_unregister(struct clocksource *cs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff81147ff0)
Location: kernel/time/clocksource.c:1019
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:init_tsc_clocksource
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock
```
**Symbols:**

```
ffffffff81147ff0-ffffffff8114803e: clocksource_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int clocksource_unregister(struct clocksource *cs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff811495a0)
Location: kernel/time/clocksource.c:1122
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:init_tsc_clocksource
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock
```
**Symbols:**

```
ffffffff811495a0-ffffffff811495ee: clocksource_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int clocksource_unregister(struct clocksource *cs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff8116cf60)
Location: kernel/time/clocksource.c:1254
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:init_tsc_clocksource
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock
```
**Symbols:**

```
ffffffff8116cf60-ffffffff8116cfae: clocksource_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int clocksource_unregister(struct clocksource *cs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff811a13f0)
Location: kernel/time/clocksource.c:1260
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:init_tsc_clocksource
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock
```
**Symbols:**

```
ffffffff811a13f0-ffffffff811a1442: clocksource_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int clocksource_unregister(struct clocksource *cs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff811e0340)
Location: kernel/time/clocksource.c:1279
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:init_tsc_clocksource
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock
```
**Symbols:**

```
ffffffff811e0340-ffffffff811e0392: clocksource_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int clocksource_unregister(struct clocksource *cs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff811f4840)
Location: kernel/time/clocksource.c:1290
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:init_tsc_clocksource
  - arch/x86/kernel/tsc.c:init_tsc_clocksource
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock
```
**Symbols:**

```
ffffffff811f4840-ffffffff811f4892: clocksource_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int clocksource_unregister(struct clocksource *cs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff8120a980)
Location: kernel/time/clocksource.c:1313
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:init_tsc_clocksource
  - arch/x86/kernel/tsc.c:init_tsc_clocksource
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock
```
**Symbols:**

```
ffffffff8120a980-ffffffff8120a9d2: clocksource_unregister (STB_GLOBAL)
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
int clocksource_unregister(struct clocksource *cs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffff8000101a6e30)
Location: kernel/time/clocksource.c:1020
Inline: False
```
**Symbols:**

```
ffff8000101a6e30-ffff8000101a6ea8: clocksource_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int clocksource_unregister(struct clocksource *cs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (c03f1e5c)
Location: kernel/time/clocksource.c:1020
Inline: False
```
**Symbols:**

```
c03f1e5c-c03f1eb0: clocksource_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int clocksource_unregister(struct clocksource *cs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (c000000000209710)
Location: kernel/time/clocksource.c:1020
Inline: False
```
**Symbols:**

```
c000000000209710-c0000000002097bc: clocksource_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int clocksource_unregister(struct clocksource *cs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffe000132ef0)
Location: kernel/time/clocksource.c:1020
Inline: False
```
**Symbols:**

```
ffffffe000132ef0-ffffffe000132f4c: clocksource_unregister (STB_GLOBAL)
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
int clocksource_unregister(struct clocksource *cs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff81135510)
Location: kernel/time/clocksource.c:1020
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:init_tsc_clocksource
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
```
**Symbols:**

```
ffffffff81135510-ffffffff8113555e: clocksource_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int clocksource_unregister(struct clocksource *cs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff81127f70)
Location: kernel/time/clocksource.c:1020
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:init_tsc_clocksource
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
```
**Symbols:**

```
ffffffff81127f70-ffffffff81127fbe: clocksource_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int clocksource_unregister(struct clocksource *cs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff81133230)
Location: kernel/time/clocksource.c:1020
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:init_tsc_clocksource
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
```
**Symbols:**

```
ffffffff81133230-ffffffff8113327e: clocksource_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int clocksource_unregister(struct clocksource *cs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff8113fc50)
Location: kernel/time/clocksource.c:1020
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:init_tsc_clocksource
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock
```
**Symbols:**

```
ffffffff8113fc50-ffffffff8113fc9e: clocksource_unregister (STB_GLOBAL)
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
