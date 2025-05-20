# Function: <code>run_local_timers</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void run_local_timers();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810ee8c2)
Location: kernel/time/timer.c:1443
Inline: True
Inline callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff810ee900-ffffffff810ee91a: run_local_timers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void run_local_timers();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810f57b0)
Location: kernel/time/timer.c:1648
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff810f57b0-ffffffff810f5800: run_local_timers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void run_local_timers();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810fc810)
Location: kernel/time/timer.c:1663
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff810fc810-ffffffff810fc860: run_local_timers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void run_local_timers();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810fec60)
Location: kernel/time/timer.c:1654
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff810fec60-ffffffff810fecae: run_local_timers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void run_local_timers();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81109950)
Location: kernel/time/timer.c:1692
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff81109950-ffffffff81109998: run_local_timers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void run_local_timers();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81114f70)
Location: kernel/time/timer.c:1703
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff81114f70-ffffffff81114fb8: run_local_timers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void run_local_timers();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811205b0)
Location: kernel/time/timer.c:1702
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff811205b0-ffffffff811205f8: run_local_timers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void run_local_timers();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8112aea0)
Location: kernel/time/timer.c:1706
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff8112aea0-ffffffff8112aee8: run_local_timers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void run_local_timers();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81136e40)
Location: kernel/time/timer.c:1794
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff81136e40-ffffffff81136e88: run_local_timers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void run_local_timers();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81145ad5)
Location: kernel/time/timer.c:1813
Inline: True
Inline callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff81145b50-ffffffff81145b9b: run_local_timers (STB_GLOBAL)
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
In kernel/time/timer.c (ffffffff81142108)
Location: kernel/time/timer.c:1752
Inline: True
Inline callers:
  - kernel/time/timer.c:update_process_times
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
In kernel/time/timer.c (ffffffff811432f8)
Location: kernel/time/timer.c:1769
Inline: True
Inline callers:
  - kernel/time/timer.c:update_process_times
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
In kernel/time/timer.c (ffffffff81166878)
Location: kernel/time/timer.c:1755
Inline: True
Inline callers:
  - kernel/time/timer.c:update_process_times
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81199f49)
Location: kernel/time/timer.c:1811
Inline: True
Inline callers:
  - kernel/time/timer.c:update_process_times
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811d8639)
Location: kernel/time/timer.c:2043
Inline: True
Inline callers:
  - kernel/time/timer.c:update_process_times
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
In kernel/time/timer.c (ffffffff811eca69)
Location: kernel/time/timer.c:2043
Inline: True
Inline callers:
  - kernel/time/timer.c:update_process_times
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
In kernel/time/timer.c (ffffffff81202bc9)
Location: kernel/time/timer.c:2059
Inline: True
Inline callers:
  - kernel/time/timer.c:update_process_times
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
void run_local_timers();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffff8000101a00a8)
Location: kernel/time/timer.c:1794
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffff8000101a00a8-ffff8000101a0108: run_local_timers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void run_local_timers();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c03e9d48)
Location: kernel/time/timer.c:1794
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
c03e9d48-c03e9dac: run_local_timers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void run_local_timers();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c000000000201000)
Location: kernel/time/timer.c:1794
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
c000000000201000-c000000000201080: run_local_timers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void run_local_timers();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffe00012dd9c)
Location: kernel/time/timer.c:1794
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffe00012dd9c-ffffffe00012de0e: run_local_timers (STB_GLOBAL)
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
void run_local_timers();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8112f5f0)
Location: kernel/time/timer.c:1794
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff8112f5f0-ffffffff8112f638: run_local_timers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void run_local_timers();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81122070)
Location: kernel/time/timer.c:1794
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff81122070-ffffffff811220b8: run_local_timers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void run_local_timers();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8112d310)
Location: kernel/time/timer.c:1794
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff8112d310-ffffffff8112d358: run_local_timers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void run_local_timers();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81139c20)
Location: kernel/time/timer.c:1794
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff81139c20-ffffffff81139c68: run_local_timers (STB_GLOBAL)
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
