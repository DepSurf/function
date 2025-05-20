# Function: <code>read_hv_clock_tsc_cs</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 read_hv_clock_tsc_cs(struct clocksource *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff819c33b0)
Location: drivers/clocksource/hyperv_timer.c:339
Inline: False
```
**Symbols:**

```
ffffffff819c33b0-ffffffff819c33bb: read_hv_clock_tsc_cs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 read_hv_clock_tsc_cs(struct clocksource *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff819c37a0)
Location: drivers/clocksource/hyperv_timer.c:339
Inline: False
```
**Symbols:**

```
ffffffff819c37a0-ffffffff819c37ab: read_hv_clock_tsc_cs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 read_hv_clock_tsc_cs(struct clocksource *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff819a7ab0)
Location: drivers/clocksource/hyperv_timer.c:388
Inline: False
```
**Symbols:**

```
ffffffff819a7ab0-ffffffff819a7abb: read_hv_clock_tsc_cs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 read_hv_clock_tsc_cs(struct clocksource *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81a55080)
Location: drivers/clocksource/hyperv_timer.c:385
Inline: False
```
**Symbols:**

```
ffffffff81a55080-ffffffff81a5508b: read_hv_clock_tsc_cs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 read_hv_clock_tsc_cs(struct clocksource *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81bc43e0)
Location: drivers/clocksource/hyperv_timer.c:385
Inline: False
```
**Symbols:**

```
ffffffff81bc43e0-ffffffff81bc43ef: read_hv_clock_tsc_cs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 read_hv_clock_tsc_cs(struct clocksource *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81d69b90)
Location: drivers/clocksource/hyperv_timer.c:395
Inline: False
```
**Symbols:**

```
ffffffff81d69b90-ffffffff81d69b9f: read_hv_clock_tsc_cs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 read_hv_clock_tsc_cs(struct clocksource *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81dd4ea0)
Location: drivers/clocksource/hyperv_timer.c:426
Inline: False
```
**Symbols:**

```
ffffffff81dd4ea0-ffffffff81dd4f07: read_hv_clock_tsc_cs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 read_hv_clock_tsc_cs(struct clocksource *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81e8cff0)
Location: drivers/clocksource/hyperv_timer.c:426
Inline: False
```
**Symbols:**

```
ffffffff81e8cff0-ffffffff81e8d057: read_hv_clock_tsc_cs (STB_LOCAL)
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
<b>Regular</b>
<ul>
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
