# Function: <code>perf_init_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8117ec4a)
Location: kernel/events/core.c:7778
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81190726)
Location: kernel/events/core.c:8811
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8119f5f3)
Location: kernel/events/core.c:9005
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a6068)
Location: kernel/events/core.c:9215
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811b9c5e)
Location: kernel/events/core.c:9237
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811d8fcf)
Location: kernel/events/core.c:9759
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e9452)
Location: kernel/events/core.c:9802
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812027e4)
Location: kernel/events/core.c:10130
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120f5e9)
Location: kernel/events/core.c:10246
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct pmu *perf_init_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81234750)
Location: kernel/events/core.c:10811
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff81234750-ffffffff8123485b: perf_init_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct pmu *perf_init_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123f0a0)
Location: kernel/events/core.c:11093
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff8123f0a0-ffffffff8123f1b0: perf_init_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct pmu *perf_init_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81243210)
Location: kernel/events/core.c:11223
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff81243210-ffffffff81243379: perf_init_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct pmu *perf_init_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8127da60)
Location: kernel/events/core.c:11335
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff8127da60-ffffffff8127dbc9: perf_init_event (STB_LOCAL)
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
In kernel/events/core.c (ffffffff812d6968)
Location: kernel/events/core.c:11271
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
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
In kernel/events/core.c (ffffffff8133f735)
Location: kernel/events/core.c:11583
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct pmu *perf_init_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8136be10)
Location: kernel/events/core.c:11617
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff8136be10-ffffffff8136bf97: perf_init_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct pmu *perf_init_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81394fd0)
Location: kernel/events/core.c:11701
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff81394fd0-ffffffff81395157: perf_init_event (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff800010297570)
Location: kernel/events/core.c:10246
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c77c8)
Location: kernel/events/core.c:10246
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c000000000346e40)
Location: kernel/events/core.c:10246
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001ca03e)
Location: kernel/events/core.c:10246
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81207c09)
Location: kernel/events/core.c:10246
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fad39)
Location: kernel/events/core.c:10246
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812059d9)
Location: kernel/events/core.c:10246
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81214846)
Location: kernel/events/core.c:10246
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
</details>
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
