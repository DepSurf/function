# Function: <code>perf_event_stop</code>

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
int perf_event_stop(struct perf_event *event, int restart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81188f60)
Location: kernel/events/core.c:2504
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:__perf_addr_filters_adjust
  - kernel/events/core.c:perf_event_addr_filters_exec
  - kernel/events/core.c:ring_buffer_attach
```
**Symbols:**

```
ffffffff81188f60-ffffffff81188ff9: perf_event_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int perf_event_stop(struct perf_event *event, int restart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81198330)
Location: kernel/events/core.c:2568
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:__perf_addr_filters_adjust
  - kernel/events/core.c:perf_event_addr_filters_exec
  - kernel/events/core.c:ring_buffer_attach
```
**Symbols:**

```
ffffffff81198330-ffffffff811983c9: perf_event_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int perf_event_stop(struct perf_event *event, int restart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a0030)
Location: kernel/events/core.c:2651
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:__perf_addr_filters_adjust
  - kernel/events/core.c:perf_event_addr_filters_exec
  - kernel/events/core.c:ring_buffer_attach
```
**Symbols:**

```
ffffffff811a0030-ffffffff811a00c9: perf_event_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int perf_event_stop(struct perf_event *event, int restart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811b3960)
Location: kernel/events/core.c:2563
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:__perf_addr_filters_adjust
  - kernel/events/core.c:perf_event_addr_filters_exec
  - kernel/events/core.c:ring_buffer_attach
```
**Symbols:**

```
ffffffff811b3960-ffffffff811b39f9: perf_event_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int perf_event_stop(struct perf_event *event, int restart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811d2e60)
Location: kernel/events/core.c:2772
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:__perf_addr_filters_adjust
  - kernel/events/core.c:perf_event_addr_filters_exec
  - kernel/events/core.c:ring_buffer_attach
```
**Symbols:**

```
ffffffff811d2e60-ffffffff811d2ef9: perf_event_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int perf_event_stop(struct perf_event *event, int restart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e3150)
Location: kernel/events/core.c:2772
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:__perf_addr_filters_adjust
  - kernel/events/core.c:perf_event_addr_filters_exec
  - kernel/events/core.c:ring_buffer_attach
```
**Symbols:**

```
ffffffff811e3150-ffffffff811e31e9: perf_event_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int perf_event_stop(struct perf_event *event, int restart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fa320)
Location: kernel/events/core.c:2790
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:__perf_addr_filters_adjust
  - kernel/events/core.c:perf_event_addr_filters_exec
  - kernel/events/core.c:ring_buffer_attach
```
**Symbols:**

```
ffffffff811fa320-ffffffff811fa3b2: perf_event_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int perf_event_stop(struct perf_event *event, int restart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812073f0)
Location: kernel/events/core.c:2875
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:__perf_addr_filters_adjust
  - kernel/events/core.c:perf_event_addr_filters_exec
  - kernel/events/core.c:ring_buffer_attach
```
**Symbols:**

```
ffffffff812073f0-ffffffff81207482: perf_event_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff812322a0)
Location: kernel/events/core.c:3044
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:__perf_addr_filters_adjust
  - kernel/events/core.c:perf_event_addr_filters_exec
  - kernel/events/core.c:ring_buffer_attach
```
**Symbols:**

```
ffffffff812322a0-ffffffff8123232e: perf_event_stop.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff8123bdb0)
Location: kernel/events/core.c:3088
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:__perf_addr_filters_adjust
  - kernel/events/core.c:perf_event_addr_filters_exec
  - kernel/events/core.c:ring_buffer_attach
```
**Symbols:**

```
ffffffff8123bdb0-ffffffff8123be3e: perf_event_stop.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff81240410)
Location: kernel/events/core.c:3090
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:__perf_addr_filters_adjust
  - kernel/events/core.c:perf_event_addr_filters_exec
  - kernel/events/core.c:ring_buffer_attach
```
**Symbols:**

```
ffffffff81240410-ffffffff8124049e: perf_event_stop.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff8127ade0)
Location: kernel/events/core.c:3132
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:__perf_addr_filters_adjust
  - kernel/events/core.c:perf_event_addr_filters_exec
  - kernel/events/core.c:ring_buffer_attach
```
**Symbols:**

```
ffffffff8127ade0-ffffffff8127ae6e: perf_event_stop.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff812cecb0)
Location: kernel/events/core.c:3043
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:__perf_addr_filters_adjust
  - kernel/events/core.c:perf_event_addr_filters_exec
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:ring_buffer_attach
```
**Symbols:**

```
ffffffff812cecb0-ffffffff812ced5a: perf_event_stop.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff81337000)
Location: kernel/events/core.c:3044
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:__perf_addr_filters_adjust
  - kernel/events/core.c:perf_event_addr_filters_exec
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:ring_buffer_attach
```
**Symbols:**

```
ffffffff81337000-ffffffff813370aa: perf_event_stop.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff81367ee0)
Location: kernel/events/core.c:3044
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:__perf_addr_filters_adjust
  - kernel/events/core.c:perf_event_addr_filters_exec
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:ring_buffer_attach
```
**Symbols:**

```
ffffffff81367ee0-ffffffff81367f8a: perf_event_stop.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff81390e00)
Location: kernel/events/core.c:3082
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:__perf_addr_filters_adjust
  - kernel/events/core.c:perf_event_addr_filters_exec
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:ring_buffer_attach
```
**Symbols:**

```
ffffffff81390e00-ffffffff81390eaa: perf_event_stop.isra.0 (STB_LOCAL)
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
int perf_event_stop(struct perf_event *event, int restart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff800010290eb0)
Location: kernel/events/core.c:2875
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:ring_buffer_attach
```
**Symbols:**

```
ffff800010290eb0-ffff800010290f60: perf_event_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int perf_event_stop(struct perf_event *event, int restart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c0c34)
Location: kernel/events/core.c:2875
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:ring_buffer_attach
```
**Symbols:**

```
c04c0c34-c04c0ce8: perf_event_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int perf_event_stop(struct perf_event *event, int restart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c00000000033e9d0)
Location: kernel/events/core.c:2875
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:ring_buffer_attach
```
**Symbols:**

```
c00000000033e9d0-c00000000033ead0: perf_event_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int perf_event_stop(struct perf_event *event, int restart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001c3aee)
Location: kernel/events/core.c:2875
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:ring_buffer_attach
```
**Symbols:**

```
ffffffe0001c3aee-ffffffe0001c3b7e: perf_event_stop (STB_LOCAL)
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
int perf_event_stop(struct perf_event *event, int restart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811ffa10)
Location: kernel/events/core.c:2875
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:__perf_addr_filters_adjust
  - kernel/events/core.c:perf_event_addr_filters_exec
  - kernel/events/core.c:ring_buffer_attach
```
**Symbols:**

```
ffffffff811ffa10-ffffffff811ffaa2: perf_event_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int perf_event_stop(struct perf_event *event, int restart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f2760)
Location: kernel/events/core.c:2875
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:__perf_addr_filters_adjust
  - kernel/events/core.c:perf_event_addr_filters_exec
  - kernel/events/core.c:ring_buffer_attach
```
**Symbols:**

```
ffffffff811f2760-ffffffff811f27f2: perf_event_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int perf_event_stop(struct perf_event *event, int restart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fd7e0)
Location: kernel/events/core.c:2875
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:__perf_addr_filters_adjust
  - kernel/events/core.c:perf_event_addr_filters_exec
  - kernel/events/core.c:ring_buffer_attach
```
**Symbols:**

```
ffffffff811fd7e0-ffffffff811fd872: perf_event_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int perf_event_stop(struct perf_event *event, int restart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120c620)
Location: kernel/events/core.c:2875
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:__perf_addr_filters_adjust
  - kernel/events/core.c:perf_event_addr_filters_exec
  - kernel/events/core.c:ring_buffer_attach
```
**Symbols:**

```
ffffffff8120c620-ffffffff8120c6b2: perf_event_stop (STB_LOCAL)
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
