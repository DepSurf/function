# Function: <code>cpu_clock_event_stop</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void cpu_clock_event_stop(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8117a780)
Location: kernel/events/core.c:7267
Inline: False
Direct callers:
  - kernel/events/core.c:cpu_clock_event_del
```
**Symbols:**

```
ffffffff8117a780-ffffffff8117a7b3: cpu_clock_event_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cpu_clock_event_stop(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8118b580)
Location: kernel/events/core.c:8259
Inline: False
Direct callers:
  - kernel/events/core.c:cpu_clock_event_del
```
**Symbols:**

```
ffffffff8118b580-ffffffff8118b5ba: cpu_clock_event_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cpu_clock_event_stop(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8119a2d0)
Location: kernel/events/core.c:8448
Inline: False
Direct callers:
  - kernel/events/core.c:cpu_clock_event_del
```
**Symbols:**

```
ffffffff8119a2d0-ffffffff8119a30a: cpu_clock_event_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cpu_clock_event_stop(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a20f0)
Location: kernel/events/core.c:8686
Inline: False
Direct callers:
  - kernel/events/core.c:cpu_clock_event_del
```
**Symbols:**

```
ffffffff811a20f0-ffffffff811a212a: cpu_clock_event_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cpu_clock_event_stop(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811b5d80)
Location: kernel/events/core.c:8694
Inline: False
Direct callers:
  - kernel/events/core.c:cpu_clock_event_del
```
**Symbols:**

```
ffffffff811b5d80-ffffffff811b5dba: cpu_clock_event_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void cpu_clock_event_stop(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811d5470)
Location: kernel/events/core.c:9216
Inline: False
Direct callers:
  - kernel/events/core.c:cpu_clock_event_del
```
**Symbols:**

```
ffffffff811d5470-ffffffff811d54ac: cpu_clock_event_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cpu_clock_event_stop(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e5af0)
Location: kernel/events/core.c:9256
Inline: False
Direct callers:
  - kernel/events/core.c:cpu_clock_event_del
```
**Symbols:**

```
ffffffff811e5af0-ffffffff811e5b4b: cpu_clock_event_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void cpu_clock_event_stop(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fd2e0)
Location: kernel/events/core.c:9559
Inline: False
Direct callers:
  - kernel/events/core.c:cpu_clock_event_del
```
**Symbols:**

```
ffffffff811fd2e0-ffffffff811fd31c: cpu_clock_event_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cpu_clock_event_stop(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120a590)
Location: kernel/events/core.c:9675
Inline: False
Direct callers:
  - kernel/events/core.c:cpu_clock_event_del
```
**Symbols:**

```
ffffffff8120a590-ffffffff8120a5cc: cpu_clock_event_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void cpu_clock_event_stop(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81232800)
Location: kernel/events/core.c:10223
Inline: True
Inline callers:
  - kernel/events/core.c:cpu_clock_event_del
```
**Symbols:**

```
ffffffff81232210-ffffffff8123226b: cpu_clock_event_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void cpu_clock_event_stop(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123c120)
Location: kernel/events/core.c:10505
Inline: True
Inline callers:
  - kernel/events/core.c:cpu_clock_event_del
```
**Symbols:**

```
ffffffff8123bce0-ffffffff8123bd3b: cpu_clock_event_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void cpu_clock_event_stop(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81240780)
Location: kernel/events/core.c:10635
Inline: True
Inline callers:
  - kernel/events/core.c:cpu_clock_event_del
```
**Symbols:**

```
ffffffff812402c0-ffffffff8124031b: cpu_clock_event_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void cpu_clock_event_stop(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8127b180)
Location: kernel/events/core.c:10747
Inline: True
Inline callers:
  - kernel/events/core.c:cpu_clock_event_del
```
**Symbols:**

```
ffffffff8127ac90-ffffffff8127aceb: cpu_clock_event_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void cpu_clock_event_stop(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812cebb5)
Location: kernel/events/core.c:10683
Inline: True
Inline callers:
  - kernel/events/core.c:cpu_clock_event_del
```
**Symbols:**

```
ffffffff812ce690-ffffffff812ce6fc: cpu_clock_event_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void cpu_clock_event_stop(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81336ee5)
Location: kernel/events/core.c:11049
Inline: True
Inline callers:
  - kernel/events/core.c:cpu_clock_event_del
```
**Symbols:**

```
ffffffff81336ae0-ffffffff81336b4c: cpu_clock_event_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void cpu_clock_event_stop(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81367c55)
Location: kernel/events/core.c:11089
Inline: True
Inline callers:
  - kernel/events/core.c:cpu_clock_event_del
```
**Symbols:**

```
ffffffff81366510-ffffffff81366575: cpu_clock_event_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void cpu_clock_event_stop(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81390b75)
Location: kernel/events/core.c:11159
Inline: True
Inline callers:
  - kernel/events/core.c:cpu_clock_event_del
```
**Symbols:**

```
ffffffff813907c0-ffffffff81390825: cpu_clock_event_stop (STB_LOCAL)
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
void cpu_clock_event_stop(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff8000102940e8)
Location: kernel/events/core.c:9675
Inline: True
```
**Symbols:**

```
ffff8000102940e8-ffff800010294148: cpu_clock_event_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void cpu_clock_event_stop(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c3c10)
Location: kernel/events/core.c:9675
Inline: True
```
**Symbols:**

```
c04c3c10-c04c3c40: cpu_clock_event_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void cpu_clock_event_stop(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c000000000341d20)
Location: kernel/events/core.c:9675
Inline: True
Inline callers:
  - kernel/events/core.c:cpu_clock_event_del
```
**Symbols:**

```
c000000000341cb0-c000000000341d04: cpu_clock_event_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void cpu_clock_event_stop(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001c5f26)
Location: kernel/events/core.c:9675
Inline: False
Direct callers:
  - kernel/events/core.c:cpu_clock_event_del
```
**Symbols:**

```
ffffffe0001c5f26-ffffffe0001c5f7e: cpu_clock_event_stop (STB_LOCAL)
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
void cpu_clock_event_stop(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81202bb0)
Location: kernel/events/core.c:9675
Inline: False
Direct callers:
  - kernel/events/core.c:cpu_clock_event_del
```
**Symbols:**

```
ffffffff81202bb0-ffffffff81202bec: cpu_clock_event_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cpu_clock_event_stop(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f5900)
Location: kernel/events/core.c:9675
Inline: False
Direct callers:
  - kernel/events/core.c:cpu_clock_event_del
```
**Symbols:**

```
ffffffff811f5900-ffffffff811f593c: cpu_clock_event_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cpu_clock_event_stop(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81200980)
Location: kernel/events/core.c:9675
Inline: False
Direct callers:
  - kernel/events/core.c:cpu_clock_event_del
```
**Symbols:**

```
ffffffff81200980-ffffffff812009bc: cpu_clock_event_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cpu_clock_event_stop(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120fa10)
Location: kernel/events/core.c:9675
Inline: False
Direct callers:
  - kernel/events/core.c:cpu_clock_event_del
```
**Symbols:**

```
ffffffff8120fa10-ffffffff8120fa4c: cpu_clock_event_stop (STB_LOCAL)
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
