# Function: <code>read_hv_sched_clock_msr</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff818bc7c5)
Location: drivers/clocksource/hyperv_timer.c:249
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:read_hv_clock_msr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 read_hv_sched_clock_msr();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff818ef2b0)
Location: drivers/clocksource/hyperv_timer.c:260
Inline: False
```
**Symbols:**

```
ffffffff818ef2b0-ffffffff818ef2da: read_hv_sched_clock_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 read_hv_sched_clock_msr();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff819c3100)
Location: drivers/clocksource/hyperv_timer.c:407
Inline: False
```
**Symbols:**

```
ffffffff819c3100-ffffffff819c312a: read_hv_sched_clock_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 read_hv_sched_clock_msr();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff819c34f0)
Location: drivers/clocksource/hyperv_timer.c:407
Inline: False
```
**Symbols:**

```
ffffffff819c34f0-ffffffff819c3515: read_hv_sched_clock_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 read_hv_sched_clock_msr();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff819a7820)
Location: drivers/clocksource/hyperv_timer.c:461
Inline: False
```
**Symbols:**

```
ffffffff819a7820-ffffffff819a7845: read_hv_sched_clock_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 read_hv_sched_clock_msr();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81a54d90)
Location: drivers/clocksource/hyperv_timer.c:458
Inline: False
```
**Symbols:**

```
ffffffff81a54d90-ffffffff81a54db5: read_hv_sched_clock_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 read_hv_sched_clock_msr();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81bc4450)
Location: drivers/clocksource/hyperv_timer.c:458
Inline: False
```
**Symbols:**

```
ffffffff81bc4450-ffffffff81bc448c: read_hv_sched_clock_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 read_hv_sched_clock_msr();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81d69c30)
Location: drivers/clocksource/hyperv_timer.c:467
Inline: False
```
**Symbols:**

```
ffffffff81d69c30-ffffffff81d69c6c: read_hv_sched_clock_msr (STB_LOCAL)
```
</details>
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
<summary>In <code>aws</code>: ✅</summary>

```c
u64 read_hv_sched_clock_msr();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81890680)
Location: drivers/clocksource/hyperv_timer.c:260
Inline: False
```
**Symbols:**

```
ffffffff81890680-ffffffff818906aa: read_hv_sched_clock_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 read_hv_sched_clock_msr();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81849b10)
Location: drivers/clocksource/hyperv_timer.c:260
Inline: False
```
**Symbols:**

```
ffffffff81849b10-ffffffff81849b5a: read_hv_sched_clock_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 read_hv_sched_clock_msr();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff818e40e0)
Location: drivers/clocksource/hyperv_timer.c:260
Inline: False
```
**Symbols:**

```
ffffffff818e40e0-ffffffff818e410a: read_hv_sched_clock_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 read_hv_sched_clock_msr();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81900d40)
Location: drivers/clocksource/hyperv_timer.c:260
Inline: False
```
**Symbols:**

```
ffffffff81900d40-ffffffff81900d6a: read_hv_sched_clock_msr (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
