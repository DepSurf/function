# Function: <code>cpu_clock_event_start</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void cpu_clock_event_start(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8117a490)
Location: kernel/events/core.c:7261
Inline: True
Inline callers:
  - kernel/events/core.c:cpu_clock_event_add
```
**Symbols:**

```
ffffffff8117a490-ffffffff8117a4b9: cpu_clock_event_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cpu_clock_event_start(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8118b180)
Location: kernel/events/core.c:8253
Inline: False
Direct callers:
  - kernel/events/core.c:cpu_clock_event_add
```
**Symbols:**

```
ffffffff8118b180-ffffffff8118b1b0: cpu_clock_event_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cpu_clock_event_start(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8119a0b0)
Location: kernel/events/core.c:8442
Inline: False
Direct callers:
  - kernel/events/core.c:cpu_clock_event_add
```
**Symbols:**

```
ffffffff8119a0b0-ffffffff8119a0e0: cpu_clock_event_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cpu_clock_event_start(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a1e00)
Location: kernel/events/core.c:8680
Inline: False
Direct callers:
  - kernel/events/core.c:cpu_clock_event_add
```
**Symbols:**

```
ffffffff811a1e00-ffffffff811a1e30: cpu_clock_event_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cpu_clock_event_start(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811b5a80)
Location: kernel/events/core.c:8688
Inline: False
Direct callers:
  - kernel/events/core.c:cpu_clock_event_add
```
**Symbols:**

```
ffffffff811b5a80-ffffffff811b5ab0: cpu_clock_event_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void cpu_clock_event_start(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811d50d0)
Location: kernel/events/core.c:9210
Inline: False
Direct callers:
  - kernel/events/core.c:cpu_clock_event_add
```
**Symbols:**

```
ffffffff811d50d0-ffffffff811d5100: cpu_clock_event_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cpu_clock_event_start(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e58f0)
Location: kernel/events/core.c:9250
Inline: False
Direct callers:
  - kernel/events/core.c:cpu_clock_event_add
```
**Symbols:**

```
ffffffff811e58f0-ffffffff811e5920: cpu_clock_event_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void cpu_clock_event_start(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fd000)
Location: kernel/events/core.c:9553
Inline: False
Direct callers:
  - kernel/events/core.c:cpu_clock_event_add
```
**Symbols:**

```
ffffffff811fd000-ffffffff811fd034: cpu_clock_event_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cpu_clock_event_start(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120a180)
Location: kernel/events/core.c:9669
Inline: False
Direct callers:
  - kernel/events/core.c:cpu_clock_event_add
```
**Symbols:**

```
ffffffff8120a180-ffffffff8120a1b4: cpu_clock_event_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void cpu_clock_event_start(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812328e0)
Location: kernel/events/core.c:10217
Inline: False
Direct callers:
  - kernel/events/core.c:cpu_clock_event_add
```
**Symbols:**

```
ffffffff812328e0-ffffffff81232958: cpu_clock_event_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void cpu_clock_event_start(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123c440)
Location: kernel/events/core.c:10499
Inline: False
Direct callers:
  - kernel/events/core.c:cpu_clock_event_add
```
**Symbols:**

```
ffffffff8123c440-ffffffff8123c4b8: cpu_clock_event_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void cpu_clock_event_start(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81240a80)
Location: kernel/events/core.c:10629
Inline: False
Direct callers:
  - kernel/events/core.c:cpu_clock_event_add
```
**Symbols:**

```
ffffffff81240a80-ffffffff81240af3: cpu_clock_event_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void cpu_clock_event_start(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8127b250)
Location: kernel/events/core.c:10741
Inline: False
Direct callers:
  - kernel/events/core.c:cpu_clock_event_add
```
**Symbols:**

```
ffffffff8127b250-ffffffff8127b2c3: cpu_clock_event_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void cpu_clock_event_start(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812cf020)
Location: kernel/events/core.c:10677
Inline: False
Direct callers:
  - kernel/events/core.c:cpu_clock_event_add
```
**Symbols:**

```
ffffffff812cf020-ffffffff812cf0a6: cpu_clock_event_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void cpu_clock_event_start(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81337430)
Location: kernel/events/core.c:11043
Inline: False
Direct callers:
  - kernel/events/core.c:cpu_clock_event_add
```
**Symbols:**

```
ffffffff81337430-ffffffff813374b6: cpu_clock_event_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void cpu_clock_event_start(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8137268e)
Location: kernel/events/core.c:11083
Inline: True
Inline callers:
  - kernel/events/core.c:cpu_clock_event_add
```
**Symbols:**

```
ffffffff81367e50-ffffffff81367ecf: cpu_clock_event_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void cpu_clock_event_start(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8139b9fe)
Location: kernel/events/core.c:11153
Inline: True
Inline callers:
  - kernel/events/core.c:cpu_clock_event_add
```
**Symbols:**

```
ffffffff81390cd0-ffffffff81390d4f: cpu_clock_event_start (STB_LOCAL)
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
void cpu_clock_event_start(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff80001029b8c4)
Location: kernel/events/core.c:9669
Inline: True
Inline callers:
  - kernel/events/core.c:cpu_clock_event_add
```
**Symbols:**

```
ffff800010293368-ffff80001029339c: cpu_clock_event_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cpu_clock_event_start(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c396c)
Location: kernel/events/core.c:9669
Inline: False
Direct callers:
  - kernel/events/core.c:cpu_clock_event_add
```
**Symbols:**

```
c04c396c-c04c39b8: cpu_clock_event_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void cpu_clock_event_start(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c00000000034b900)
Location: kernel/events/core.c:9669
Inline: True
Inline callers:
  - kernel/events/core.c:cpu_clock_event_add
```
**Symbols:**

```
c000000000341850-c0000000003418b4: cpu_clock_event_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void cpu_clock_event_start(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001cdf28)
Location: kernel/events/core.c:9669
Inline: True
Inline callers:
  - kernel/events/core.c:cpu_clock_event_add
```
**Symbols:**

```
ffffffe0001c5b2c-ffffffe0001c5b5c: cpu_clock_event_start (STB_LOCAL)
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
void cpu_clock_event_start(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812027a0)
Location: kernel/events/core.c:9669
Inline: False
Direct callers:
  - kernel/events/core.c:cpu_clock_event_add
```
**Symbols:**

```
ffffffff812027a0-ffffffff812027d4: cpu_clock_event_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cpu_clock_event_start(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f54f0)
Location: kernel/events/core.c:9669
Inline: False
Direct callers:
  - kernel/events/core.c:cpu_clock_event_add
```
**Symbols:**

```
ffffffff811f54f0-ffffffff811f5524: cpu_clock_event_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cpu_clock_event_start(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81200570)
Location: kernel/events/core.c:9669
Inline: False
Direct callers:
  - kernel/events/core.c:cpu_clock_event_add
```
**Symbols:**

```
ffffffff81200570-ffffffff812005a4: cpu_clock_event_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cpu_clock_event_start(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120f600)
Location: kernel/events/core.c:9669
Inline: False
Direct callers:
  - kernel/events/core.c:cpu_clock_event_add
```
**Symbols:**

```
ffffffff8120f600-ffffffff8120f634: cpu_clock_event_start (STB_LOCAL)
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
