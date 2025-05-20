# Function: <code>read_hv_sched_clock_tsc</code>

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
In drivers/clocksource/hyperv_timer.c (ffffffff818bc988)
Location: drivers/clocksource/hyperv_timer.c:225
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:read_hv_clock_tsc
  - drivers/clocksource/hyperv_timer.c:read_hv_clock_tsc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 read_hv_sched_clock_tsc();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff818ef580)
Location: drivers/clocksource/hyperv_timer.c:234
Inline: False
```
**Symbols:**

```
ffffffff818ef580-ffffffff818ef5a5: read_hv_sched_clock_tsc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 read_hv_sched_clock_tsc();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff819c33c0)
Location: drivers/clocksource/hyperv_timer.c:344
Inline: False
```
**Symbols:**

```
ffffffff819c33c0-ffffffff819c33e3: read_hv_sched_clock_tsc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 read_hv_sched_clock_tsc();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff819c37b0)
Location: drivers/clocksource/hyperv_timer.c:344
Inline: False
```
**Symbols:**

```
ffffffff819c37b0-ffffffff819c37ce: read_hv_sched_clock_tsc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 read_hv_sched_clock_tsc();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff819a7ac0)
Location: drivers/clocksource/hyperv_timer.c:393
Inline: False
```
**Symbols:**

```
ffffffff819a7ac0-ffffffff819a7ade: read_hv_sched_clock_tsc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 read_hv_sched_clock_tsc();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81a55060)
Location: drivers/clocksource/hyperv_timer.c:390
Inline: False
```
**Symbols:**

```
ffffffff81a55060-ffffffff81a5507e: read_hv_sched_clock_tsc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 read_hv_sched_clock_tsc();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81bc43b0)
Location: drivers/clocksource/hyperv_timer.c:390
Inline: False
```
**Symbols:**

```
ffffffff81bc43b0-ffffffff81bc43d2: read_hv_sched_clock_tsc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 read_hv_sched_clock_tsc();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81d69b50)
Location: drivers/clocksource/hyperv_timer.c:400
Inline: False
```
**Symbols:**

```
ffffffff81d69b50-ffffffff81d69b72: read_hv_sched_clock_tsc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 read_hv_sched_clock_tsc();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff82142a00)
Location: drivers/clocksource/hyperv_timer.c:431
Inline: False
```
**Symbols:**

```
ffffffff82142a00-ffffffff82142a6b: read_hv_sched_clock_tsc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 read_hv_sched_clock_tsc();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff822250f0)
Location: drivers/clocksource/hyperv_timer.c:431
Inline: False
```
**Symbols:**

```
ffffffff822250f0-ffffffff8222515b: read_hv_sched_clock_tsc (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
u64 read_hv_sched_clock_tsc();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81890950)
Location: drivers/clocksource/hyperv_timer.c:234
Inline: False
```
**Symbols:**

```
ffffffff81890950-ffffffff81890975: read_hv_sched_clock_tsc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 read_hv_sched_clock_tsc();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81849d40)
Location: drivers/clocksource/hyperv_timer.c:234
Inline: False
```
**Symbols:**

```
ffffffff81849d40-ffffffff81849d65: read_hv_sched_clock_tsc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 read_hv_sched_clock_tsc();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff818e43b0)
Location: drivers/clocksource/hyperv_timer.c:234
Inline: False
```
**Symbols:**

```
ffffffff818e43b0-ffffffff818e43d5: read_hv_sched_clock_tsc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 read_hv_sched_clock_tsc();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81901010)
Location: drivers/clocksource/hyperv_timer.c:234
Inline: False
```
**Symbols:**

```
ffffffff81901010-ffffffff81901035: read_hv_sched_clock_tsc (STB_LOCAL)
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
