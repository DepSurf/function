# Function: <code>read_hv_clock_tsc</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u64 read_hv_clock_tsc(struct clocksource *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8102bad0)
Location: arch/x86/hyperv/hv_init.c:41
Inline: False
```
**Symbols:**

```
ffffffff8102bad0-ffffffff8102bb22: read_hv_clock_tsc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
u64 read_hv_clock_tsc(struct clocksource *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff81029e90)
Location: arch/x86/hyperv/hv_init.c:47
Inline: True
```
**Symbols:**

```
ffffffff81029e90-ffffffff81029f21: read_hv_clock_tsc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
u64 read_hv_clock_tsc(struct clocksource *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8102a020)
Location: arch/x86/hyperv/hv_init.c:49
Inline: True
```
**Symbols:**

```
ffffffff8102a020-ffffffff8102a0b1: read_hv_clock_tsc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
u64 read_hv_clock_tsc(struct clocksource *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8102aad0)
Location: arch/x86/hyperv/hv_init.c:52
Inline: True
```
**Symbols:**

```
ffffffff8102aad0-ffffffff8102ab50: read_hv_clock_tsc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
u64 read_hv_clock_tsc(struct clocksource *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8102b160)
Location: arch/x86/hyperv/hv_init.c:53
Inline: True
```
**Symbols:**

```
ffffffff8102b160-ffffffff8102b1e0: read_hv_clock_tsc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 read_hv_clock_tsc(struct clocksource *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff818bc960)
Location: drivers/clocksource/hyperv_timer.c:235
Inline: False
```
**Symbols:**

```
ffffffff818bc960-ffffffff818bc9e1: read_hv_clock_tsc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
u64 read_hv_clock_tsc(struct clocksource *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff818ef500)
Location: drivers/clocksource/hyperv_timer.c:224
Inline: True
Direct callers:
  - drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_tsc
```
**Symbols:**

```
ffffffff818ef500-ffffffff818ef580: read_hv_clock_tsc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
u64 read_hv_clock_tsc();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff819c3360)
Location: drivers/clocksource/hyperv_timer.c:329
Inline: True
Direct callers:
  - drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_tsc
  - drivers/clocksource/hyperv_timer.c:read_hv_clock_tsc_cs
```
**Symbols:**

```
ffffffff819c3360-ffffffff819c33b0: read_hv_clock_tsc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
u64 read_hv_clock_tsc();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff819c3750)
Location: drivers/clocksource/hyperv_timer.c:329
Inline: True
Direct callers:
  - drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_tsc
  - drivers/clocksource/hyperv_timer.c:read_hv_clock_tsc_cs
```
**Symbols:**

```
ffffffff819c3750-ffffffff819c37a0: read_hv_clock_tsc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
u64 read_hv_clock_tsc();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff819a7a60)
Location: drivers/clocksource/hyperv_timer.c:378
Inline: True
Direct callers:
  - drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_tsc
  - drivers/clocksource/hyperv_timer.c:read_hv_clock_tsc_cs
```
**Symbols:**

```
ffffffff819a7a60-ffffffff819a7ab0: read_hv_clock_tsc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
u64 read_hv_clock_tsc();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81a55010)
Location: drivers/clocksource/hyperv_timer.c:375
Inline: True
Direct callers:
  - drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_tsc
  - drivers/clocksource/hyperv_timer.c:read_hv_clock_tsc_cs
```
**Symbols:**

```
ffffffff81a55010-ffffffff81a55060: read_hv_clock_tsc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
u64 read_hv_clock_tsc();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81bc4330)
Location: drivers/clocksource/hyperv_timer.c:375
Inline: True
Direct callers:
  - drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_tsc
  - drivers/clocksource/hyperv_timer.c:read_hv_clock_tsc_cs
```
**Symbols:**

```
ffffffff81bc4330-ffffffff81bc43b0: read_hv_clock_tsc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
u64 read_hv_clock_tsc();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81d69ac0)
Location: drivers/clocksource/hyperv_timer.c:385
Inline: True
Direct callers:
  - drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_tsc
  - drivers/clocksource/hyperv_timer.c:read_hv_clock_tsc_cs
```
**Symbols:**

```
ffffffff81d69ac0-ffffffff81d69b3b: read_hv_clock_tsc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
u64 read_hv_clock_tsc();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff82142a00)
Location: drivers/clocksource/hyperv_timer.c:410
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_tsc
  - drivers/clocksource/hyperv_timer.c:read_hv_clock_tsc_cs
```
**Symbols:**

```
ffffffff81dd4e20-ffffffff81dd4e87: read_hv_clock_tsc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
u64 read_hv_clock_tsc();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff822250f0)
Location: drivers/clocksource/hyperv_timer.c:410
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_tsc
  - drivers/clocksource/hyperv_timer.c:read_hv_clock_tsc_cs
```
**Symbols:**

```
ffffffff81e8cf70-ffffffff81e8cfd7: read_hv_clock_tsc (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
u64 read_hv_clock_tsc(struct clocksource *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff818908d0)
Location: drivers/clocksource/hyperv_timer.c:224
Inline: True
Direct callers:
  - drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_tsc
```
**Symbols:**

```
ffffffff818908d0-ffffffff81890950: read_hv_clock_tsc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
u64 read_hv_clock_tsc(struct clocksource *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81849ca0)
Location: drivers/clocksource/hyperv_timer.c:224
Inline: True
Direct callers:
  - drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_tsc
```
**Symbols:**

```
ffffffff81849ca0-ffffffff81849d40: read_hv_clock_tsc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
u64 read_hv_clock_tsc(struct clocksource *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff818e4330)
Location: drivers/clocksource/hyperv_timer.c:224
Inline: True
Direct callers:
  - drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_tsc
```
**Symbols:**

```
ffffffff818e4330-ffffffff818e43b0: read_hv_clock_tsc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
u64 read_hv_clock_tsc(struct clocksource *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81900f90)
Location: drivers/clocksource/hyperv_timer.c:224
Inline: True
Direct callers:
  - drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_tsc
```
**Symbols:**

```
ffffffff81900f90-ffffffff81901010: read_hv_clock_tsc (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct clocksource *arg</code>
</li>
</ul>
</details>
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
