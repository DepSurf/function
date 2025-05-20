# Function: <code>__perf_event_output_stop</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __perf_event_output_stop(struct perf_event *event, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81188ad0)
Location: kernel/events/core.c:6168
Inline: False
```
**Symbols:**

```
ffffffff81188ad0-ffffffff81188b4a: __perf_event_output_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __perf_event_output_stop(struct perf_event *event, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81197eb0)
Location: kernel/events/core.c:6266
Inline: False
```
**Symbols:**

```
ffffffff81197eb0-ffffffff81197f2a: __perf_event_output_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __perf_event_output_stop(struct perf_event *event, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8119f9c0)
Location: kernel/events/core.c:6362
Inline: False
```
**Symbols:**

```
ffffffff8119f9c0-ffffffff8119fa3a: __perf_event_output_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __perf_event_output_stop(struct perf_event *event, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811b3330)
Location: kernel/events/core.c:6350
Inline: False
```
**Symbols:**

```
ffffffff811b3330-ffffffff811b33aa: __perf_event_output_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __perf_event_output_stop(struct perf_event *event, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811d2a90)
Location: kernel/events/core.c:6724
Inline: False
```
**Symbols:**

```
ffffffff811d2a90-ffffffff811d2b0d: __perf_event_output_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __perf_event_output_stop(struct perf_event *event, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e2d90)
Location: kernel/events/core.c:6733
Inline: False
```
**Symbols:**

```
ffffffff811e2d90-ffffffff811e2e0d: __perf_event_output_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __perf_event_output_stop(struct perf_event *event, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f9f40)
Location: kernel/events/core.c:6815
Inline: False
```
**Symbols:**

```
ffffffff811f9f40-ffffffff811f9fbd: __perf_event_output_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __perf_event_output_stop(struct perf_event *event, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81207010)
Location: kernel/events/core.c:6931
Inline: False
```
**Symbols:**

```
ffffffff81207010-ffffffff8120708d: __perf_event_output_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __perf_event_output_stop(struct perf_event *event, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123314f)
Location: kernel/events/core.c:7376
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_pmu_output_stop
```
**Symbols:**

```
ffffffff81230520-ffffffff8123059b: __perf_event_output_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __perf_event_output_stop(struct perf_event *event, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123cf1f)
Location: kernel/events/core.c:7558
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_pmu_output_stop
```
**Symbols:**

```
ffffffff8123a180-ffffffff8123a1fb: __perf_event_output_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __perf_event_output_stop(struct perf_event *event, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8124199f)
Location: kernel/events/core.c:7669
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_pmu_output_stop
```
**Symbols:**

```
ffffffff8123e9b0-ffffffff8123ea2b: __perf_event_output_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __perf_event_output_stop(struct perf_event *event, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8127c38f)
Location: kernel/events/core.c:7793
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_pmu_output_stop
```
**Symbols:**

```
ffffffff81279470-ffffffff812794eb: __perf_event_output_stop (STB_LOCAL)
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
In kernel/events/core.c (ffffffff812d2456)
Location: kernel/events/core.c:7698
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:__perf_pmu_output_stop
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __perf_event_output_stop(struct perf_event *event, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81334160)
Location: kernel/events/core.c:7981
Inline: False
```
**Symbols:**

```
ffffffff81334160-ffffffff813341ee: __perf_event_output_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __perf_event_output_stop(struct perf_event *event, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81364ed0)
Location: kernel/events/core.c:8009
Inline: False
```
**Symbols:**

```
ffffffff81364ed0-ffffffff81364f5e: __perf_event_output_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __perf_event_output_stop(struct perf_event *event, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8138dea0)
Location: kernel/events/core.c:8090
Inline: False
```
**Symbols:**

```
ffffffff8138dea0-ffffffff8138df2e: __perf_event_output_stop (STB_LOCAL)
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
void __perf_event_output_stop(struct perf_event *event, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff800010297b98)
Location: kernel/events/core.c:6931
Inline: False
```
**Symbols:**

```
ffff800010297b98-ffff800010297c18: __perf_event_output_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __perf_event_output_stop(struct perf_event *event, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c01f8)
Location: kernel/events/core.c:6931
Inline: False
```
**Symbols:**

```
c04c01f8-c04c028c: __perf_event_output_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __perf_event_output_stop(struct perf_event *event, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c00000000033dab0)
Location: kernel/events/core.c:6931
Inline: False
```
**Symbols:**

```
c00000000033dab0-c00000000033db68: __perf_event_output_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __perf_event_output_stop(struct perf_event *event, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001c361a)
Location: kernel/events/core.c:6931
Inline: False
```
**Symbols:**

```
ffffffe0001c361a-ffffffe0001c3670: __perf_event_output_stop (STB_LOCAL)
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
void __perf_event_output_stop(struct perf_event *event, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811ff630)
Location: kernel/events/core.c:6931
Inline: False
```
**Symbols:**

```
ffffffff811ff630-ffffffff811ff6ad: __perf_event_output_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __perf_event_output_stop(struct perf_event *event, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f2380)
Location: kernel/events/core.c:6931
Inline: False
```
**Symbols:**

```
ffffffff811f2380-ffffffff811f23fd: __perf_event_output_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __perf_event_output_stop(struct perf_event *event, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fd400)
Location: kernel/events/core.c:6931
Inline: False
```
**Symbols:**

```
ffffffff811fd400-ffffffff811fd47d: __perf_event_output_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __perf_event_output_stop(struct perf_event *event, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120c160)
Location: kernel/events/core.c:6931
Inline: False
```
**Symbols:**

```
ffffffff8120c160-ffffffff8120c1dd: __perf_event_output_stop (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
