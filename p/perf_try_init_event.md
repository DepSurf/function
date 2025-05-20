# Function: <code>perf_try_init_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int perf_try_init_event(struct pmu *pmu, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8117b3b0)
Location: kernel/events/core.c:7748
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff8117b3b0-ffffffff8117b433: perf_try_init_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int perf_try_init_event(struct pmu *pmu, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8118cc80)
Location: kernel/events/core.c:8781
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff8118cc80-ffffffff8118cd01: perf_try_init_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int perf_try_init_event(struct pmu *pmu, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8119c2c0)
Location: kernel/events/core.c:8975
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff8119c2c0-ffffffff8119c341: perf_try_init_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int perf_try_init_event(struct pmu *pmu, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a3bd0)
Location: kernel/events/core.c:9185
Inline: True
```
**Symbols:**

```
ffffffff811a3bd0-ffffffff811a3c59: perf_try_init_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int perf_try_init_event(struct pmu *pmu, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811b7df0)
Location: kernel/events/core.c:9201
Inline: True
```
**Symbols:**

```
ffffffff811b7df0-ffffffff811b7ea2: perf_try_init_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int perf_try_init_event(struct pmu *pmu, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811d7830)
Location: kernel/events/core.c:9723
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff811d7830-ffffffff811d78f5: perf_try_init_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int perf_try_init_event(struct pmu *pmu, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e8110)
Location: kernel/events/core.c:9766
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff811e8110-ffffffff811e81d5: perf_try_init_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int perf_try_init_event(struct pmu *pmu, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81202190)
Location: kernel/events/core.c:10081
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff81202190-ffffffff812022b7: perf_try_init_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int perf_try_init_event(struct pmu *pmu, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120f040)
Location: kernel/events/core.c:10197
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff8120f040-ffffffff8120f167: perf_try_init_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int perf_try_init_event(struct pmu *pmu, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81234620)
Location: kernel/events/core.c:10762
Inline: False
Direct callers:
  - kernel/events/core.c:perf_init_event
  - kernel/events/core.c:perf_init_event
  - kernel/events/core.c:perf_init_event
```
**Symbols:**

```
ffffffff81234620-ffffffff8123474a: perf_try_init_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int perf_try_init_event(struct pmu *pmu, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123ef70)
Location: kernel/events/core.c:11044
Inline: False
Direct callers:
  - kernel/events/core.c:perf_init_event
  - kernel/events/core.c:perf_init_event
  - kernel/events/core.c:perf_init_event
```
**Symbols:**

```
ffffffff8123ef70-ffffffff8123f09a: perf_try_init_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int perf_try_init_event(struct pmu *pmu, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812430e0)
Location: kernel/events/core.c:11174
Inline: False
Direct callers:
  - kernel/events/core.c:perf_init_event
  - kernel/events/core.c:perf_init_event
  - kernel/events/core.c:perf_init_event
```
**Symbols:**

```
ffffffff812430e0-ffffffff8124320a: perf_try_init_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int perf_try_init_event(struct pmu *pmu, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8127d930)
Location: kernel/events/core.c:11286
Inline: False
Direct callers:
  - kernel/events/core.c:perf_init_event
  - kernel/events/core.c:perf_init_event
  - kernel/events/core.c:perf_init_event
```
**Symbols:**

```
ffffffff8127d930-ffffffff8127da5a: perf_try_init_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int perf_try_init_event(struct pmu *pmu, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812d1f80)
Location: kernel/events/core.c:11222
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff812d1f80-ffffffff812d20fc: perf_try_init_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int perf_try_init_event(struct pmu *pmu, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8133ada0)
Location: kernel/events/core.c:11534
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff8133ada0-ffffffff8133af1c: perf_try_init_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int perf_try_init_event(struct pmu *pmu, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8136bc80)
Location: kernel/events/core.c:11568
Inline: False
Direct callers:
  - kernel/events/core.c:perf_init_event
  - kernel/events/core.c:perf_init_event
  - kernel/events/core.c:perf_init_event
```
**Symbols:**

```
ffffffff8136bc80-ffffffff8136bdfc: perf_try_init_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int perf_try_init_event(struct pmu *pmu, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81394e40)
Location: kernel/events/core.c:11652
Inline: False
Direct callers:
  - kernel/events/core.c:perf_init_event
  - kernel/events/core.c:perf_init_event
  - kernel/events/core.c:perf_init_event
```
**Symbols:**

```
ffffffff81394e40-ffffffff81394fb9: perf_try_init_event (STB_LOCAL)
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
int perf_try_init_event(struct pmu *pmu, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff800010293e88)
Location: kernel/events/core.c:10197
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffff800010293e88-ffff800010293f88: perf_try_init_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int perf_try_init_event(struct pmu *pmu, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c4e08)
Location: kernel/events/core.c:10197
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
c04c4e08-c04c4ef4: perf_try_init_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int perf_try_init_event(struct pmu *pmu, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c000000000343b00)
Location: kernel/events/core.c:10197
Inline: False
```
**Symbols:**

```
c000000000343b00-c000000000343c88: perf_try_init_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int perf_try_init_event(struct pmu *pmu, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001c4fea)
Location: kernel/events/core.c:10197
Inline: False
```
**Symbols:**

```
ffffffe0001c4fea-ffffffe0001c50aa: perf_try_init_event (STB_LOCAL)
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
int perf_try_init_event(struct pmu *pmu, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81207660)
Location: kernel/events/core.c:10197
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff81207660-ffffffff81207787: perf_try_init_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int perf_try_init_event(struct pmu *pmu, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fa500)
Location: kernel/events/core.c:10197
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff811fa500-ffffffff811fa627: perf_try_init_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int perf_try_init_event(struct pmu *pmu, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81205430)
Location: kernel/events/core.c:10197
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff81205430-ffffffff81205557: perf_try_init_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int perf_try_init_event(struct pmu *pmu, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812142a0)
Location: kernel/events/core.c:10197
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff812142a0-ffffffff812143c7: perf_try_init_event (STB_LOCAL)
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
