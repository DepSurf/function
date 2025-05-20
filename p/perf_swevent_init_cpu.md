# Function: <code>perf_swevent_init_cpu</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void perf_swevent_init_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811adfd0)
Location: kernel/events/core.c:11013
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init_cpu
```
**Symbols:**

```
ffffffff811adfd0-ffffffff811ae05e: perf_swevent_init_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void perf_swevent_init_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811c1b30)
Location: kernel/events/core.c:11045
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init_cpu
```
**Symbols:**

```
ffffffff811c1b30-ffffffff811c1bbe: perf_swevent_init_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void perf_swevent_init_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e1ec0)
Location: kernel/events/core.c:11597
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init_cpu
```
**Symbols:**

```
ffffffff811e1ec0-ffffffff811e1f4e: perf_swevent_init_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void perf_swevent_init_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f2330)
Location: kernel/events/core.c:11640
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init_cpu
```
**Symbols:**

```
ffffffff811f2330-ffffffff811f23b1: perf_swevent_init_cpu (STB_GLOBAL)
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
In kernel/events/core.c (ffffffff81209f80)
Location: kernel/events/core.c:12005
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
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
In kernel/events/core.c (ffffffff812172f0)
Location: kernel/events/core.c:12122
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void perf_swevent_init_cpu(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81231930)
Location: kernel/events/core.c:12725
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init_cpu
```
**Symbols:**

```
ffffffff81231930-ffffffff812319be: perf_swevent_init_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void perf_swevent_init_cpu(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123b5a0)
Location: kernel/events/core.c:13008
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init_cpu
```
**Symbols:**

```
ffffffff8123b5a0-ffffffff8123b62e: perf_swevent_init_cpu (STB_LOCAL)
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
In kernel/events/core.c (ffffffff81251d50)
Location: kernel/events/core.c:13201
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
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
In kernel/events/core.c (ffffffff8128d570)
Location: kernel/events/core.c:13322
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
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
In kernel/events/core.c (ffffffff812e22d5)
Location: kernel/events/core.c:13292
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
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
In kernel/events/core.c (ffffffff8134a875)
Location: kernel/events/core.c:13524
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
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
In kernel/events/core.c (ffffffff8137b8b5)
Location: kernel/events/core.c:13566
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
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
In kernel/events/core.c (ffffffff813a4ab5)
Location: kernel/events/core.c:13664
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
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
In kernel/events/core.c (ffff8000102a1568)
Location: kernel/events/core.c:12122
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
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
In kernel/events/core.c (c04d171c)
Location: kernel/events/core.c:12122
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
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
In kernel/events/core.c (c000000000353970)
Location: kernel/events/core.c:12122
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
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
In kernel/events/core.c (ffffffe0001d0864)
Location: kernel/events/core.c:12122
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
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
In kernel/events/core.c (ffffffff8120f940)
Location: kernel/events/core.c:12122
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
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
In kernel/events/core.c (ffffffff812026d0)
Location: kernel/events/core.c:12122
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
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
In kernel/events/core.c (ffffffff8120d6e0)
Location: kernel/events/core.c:12122
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
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
In kernel/events/core.c (ffffffff8121c580)
Location: kernel/events/core.c:12122
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
