# Function: <code>read_hv_clock_msr</code>

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
u64 read_hv_clock_msr(struct clocksource *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8102bb30)
Location: arch/x86/hyperv/hv_init.c:88
Inline: False
```
**Symbols:**

```
ffffffff8102bb30-ffffffff8102bb47: read_hv_clock_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 read_hv_clock_msr(struct clocksource *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff81029d70)
Location: arch/x86/hyperv/hv_init.c:66
Inline: False
```
**Symbols:**

```
ffffffff81029d70-ffffffff81029d87: read_hv_clock_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 read_hv_clock_msr(struct clocksource *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff81029fa0)
Location: arch/x86/hyperv/hv_init.c:68
Inline: False
```
**Symbols:**

```
ffffffff81029fa0-ffffffff81029fb7: read_hv_clock_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 read_hv_clock_msr(struct clocksource *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8102aa80)
Location: arch/x86/hyperv/hv_init.c:71
Inline: False
```
**Symbols:**

```
ffffffff8102aa80-ffffffff8102aa97: read_hv_clock_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 read_hv_clock_msr(struct clocksource *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8102b110)
Location: arch/x86/hyperv/hv_init.c:72
Inline: False
```
**Symbols:**

```
ffffffff8102b110-ffffffff8102b127: read_hv_clock_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 read_hv_clock_msr(struct clocksource *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff818bc7c0)
Location: drivers/clocksource/hyperv_timer.c:261
Inline: False
```
**Symbols:**

```
ffffffff818bc7c0-ffffffff818bc7d7: read_hv_clock_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
u64 read_hv_clock_msr(struct clocksource *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff818ef2b5)
Location: drivers/clocksource/hyperv_timer.c:248
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_msr
```
**Symbols:**

```
ffffffff818ef290-ffffffff818ef2a2: read_hv_clock_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
u64 read_hv_clock_msr();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff819c3105)
Location: drivers/clocksource/hyperv_timer.c:390
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_msr
  - drivers/clocksource/hyperv_timer.c:read_hv_clock_msr_cs
```
**Symbols:**

```
ffffffff819c30c0-ffffffff819c30d2: read_hv_clock_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
u64 read_hv_clock_msr();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff819c34f0)
Location: drivers/clocksource/hyperv_timer.c:390
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_msr
  - drivers/clocksource/hyperv_timer.c:read_hv_clock_msr_cs
```
**Symbols:**

```
ffffffff819c34d0-ffffffff819c34e2: read_hv_clock_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
u64 read_hv_clock_msr();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff819a7820)
Location: drivers/clocksource/hyperv_timer.c:446
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_msr
  - drivers/clocksource/hyperv_timer.c:read_hv_clock_msr_cs
```
**Symbols:**

```
ffffffff819a7800-ffffffff819a7812: read_hv_clock_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
u64 read_hv_clock_msr();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81a54d90)
Location: drivers/clocksource/hyperv_timer.c:443
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_msr
  - drivers/clocksource/hyperv_timer.c:read_hv_clock_msr_cs
```
**Symbols:**

```
ffffffff81a54d50-ffffffff81a54d62: read_hv_clock_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
u64 read_hv_clock_msr();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81bc4450)
Location: drivers/clocksource/hyperv_timer.c:443
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_msr
  - drivers/clocksource/hyperv_timer.c:read_hv_clock_msr_cs
```
**Symbols:**

```
ffffffff81bc43f0-ffffffff81bc4419: read_hv_clock_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
u64 read_hv_clock_msr();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81d69c30)
Location: drivers/clocksource/hyperv_timer.c:452
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_msr
  - drivers/clocksource/hyperv_timer.c:read_hv_clock_msr_cs
```
**Symbols:**

```
ffffffff81d69bf0-ffffffff81d69c19: read_hv_clock_msr (STB_LOCAL)
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
In drivers/clocksource/hyperv_timer.c (ffffffff81dd4f50)
Location: drivers/clocksource/hyperv_timer.c:368
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:read_hv_clock_msr_cs
  - drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_tsc
  - drivers/clocksource/hyperv_timer.c:read_hv_clock_tsc_cs
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
In drivers/clocksource/hyperv_timer.c (ffffffff81e8d0a0)
Location: drivers/clocksource/hyperv_timer.c:368
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:read_hv_clock_msr_cs
  - drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_tsc
  - drivers/clocksource/hyperv_timer.c:read_hv_clock_tsc_cs
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
u64 read_hv_clock_msr(struct clocksource *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81890685)
Location: drivers/clocksource/hyperv_timer.c:248
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_msr
```
**Symbols:**

```
ffffffff81890660-ffffffff81890672: read_hv_clock_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
u64 read_hv_clock_msr(struct clocksource *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81849b15)
Location: drivers/clocksource/hyperv_timer.c:248
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_msr
```
**Symbols:**

```
ffffffff81849ad0-ffffffff81849b09: read_hv_clock_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
u64 read_hv_clock_msr(struct clocksource *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff818e40e5)
Location: drivers/clocksource/hyperv_timer.c:248
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_msr
```
**Symbols:**

```
ffffffff818e40c0-ffffffff818e40d2: read_hv_clock_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
u64 read_hv_clock_msr(struct clocksource *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81900d45)
Location: drivers/clocksource/hyperv_timer.c:248
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_msr
```
**Symbols:**

```
ffffffff81900d20-ffffffff81900d32: read_hv_clock_msr (STB_LOCAL)
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
