# Function: <code>perf_event_itrace_started</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void perf_event_itrace_started(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811c0f80)
Location: kernel/events/core.c:7275
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_event_start
  - arch/x86/events/intel/pt.c:pt_config
```
**Symbols:**

```
ffffffff811c0f80-ffffffff811c0f8d: perf_event_itrace_started (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void perf_event_itrace_started(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e1320)
Location: kernel/events/core.c:7657
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_event_start
  - arch/x86/events/intel/pt.c:pt_config
```
**Symbols:**

```
ffffffff811e1320-ffffffff811e1328: perf_event_itrace_started (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void perf_event_itrace_started(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f1780)
Location: kernel/events/core.c:7666
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_event_start
  - arch/x86/events/intel/pt.c:pt_config
```
**Symbols:**

```
ffffffff811f1780-ffffffff811f1788: perf_event_itrace_started (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void perf_event_itrace_started(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81209340)
Location: kernel/events/core.c:7970
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_event_start
  - arch/x86/events/intel/pt.c:pt_config
```
**Symbols:**

```
ffffffff81209340-ffffffff81209348: perf_event_itrace_started (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void perf_event_itrace_started(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812166b0)
Location: kernel/events/core.c:8086
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_event_start
  - arch/x86/events/intel/pt.c:pt_config
```
**Symbols:**

```
ffffffff812166b0-ffffffff812166b8: perf_event_itrace_started (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void perf_event_itrace_started(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81242500)
Location: kernel/events/core.c:8636
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_event_start
  - arch/x86/events/intel/pt.c:pt_config
```
**Symbols:**

```
ffffffff81242500-ffffffff81242508: perf_event_itrace_started (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void perf_event_itrace_started(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8124ccf0)
Location: kernel/events/core.c:8902
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_event_start
  - arch/x86/events/intel/pt.c:pt_config
```
**Symbols:**

```
ffffffff8124ccf0-ffffffff8124ccf8: perf_event_itrace_started (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void perf_event_itrace_started(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81251350)
Location: kernel/events/core.c:9031
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_event_start
  - arch/x86/events/intel/pt.c:pt_event_start
```
**Symbols:**

```
ffffffff81251350-ffffffff81251358: perf_event_itrace_started (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void perf_event_itrace_started(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8128c150)
Location: kernel/events/core.c:9150
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_event_start
  - arch/x86/events/intel/pt.c:pt_event_start
```
**Symbols:**

```
ffffffff8128c150-ffffffff8128c158: perf_event_itrace_started (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void perf_event_itrace_started(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812e0b40)
Location: kernel/events/core.c:9055
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_event_start
  - arch/x86/events/intel/pt.c:pt_event_start
```
**Symbols:**

```
ffffffff812e0b40-ffffffff812e0b58: perf_event_itrace_started (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void perf_event_itrace_started(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81348fd0)
Location: kernel/events/core.c:9332
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_event_start
  - arch/x86/events/intel/pt.c:pt_event_start
```
**Symbols:**

```
ffffffff81348fd0-ffffffff81348fe8: perf_event_itrace_started (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void perf_event_itrace_started(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8137a110)
Location: kernel/events/core.c:9360
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_event_start
  - arch/x86/events/intel/pt.c:pt_event_start
```
**Symbols:**

```
ffffffff8137a110-ffffffff8137a128: perf_event_itrace_started (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void perf_event_itrace_started(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff813a33d0)
Location: kernel/events/core.c:9430
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_event_start
  - arch/x86/events/intel/pt.c:pt_event_start
```
**Symbols:**

```
ffffffff813a33d0-ffffffff813a33e8: perf_event_itrace_started (STB_GLOBAL)
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
void perf_event_itrace_started(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff8000102a0728)
Location: kernel/events/core.c:8086
Inline: False
```
**Symbols:**

```
ffff8000102a0728-ffff8000102a0738: perf_event_itrace_started (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void perf_event_itrace_started(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04d0658)
Location: kernel/events/core.c:8086
Inline: False
```
**Symbols:**

```
c04d0658-c04d0674: perf_event_itrace_started (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void perf_event_itrace_started(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c0000000003520c0)
Location: kernel/events/core.c:8086
Inline: False
```
**Symbols:**

```
c0000000003520c0-c0000000003520d0: perf_event_itrace_started (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void perf_event_itrace_started(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001cfc32)
Location: kernel/events/core.c:8086
Inline: False
```
**Symbols:**

```
ffffffe0001cfc32-ffffffe0001cfc4a: perf_event_itrace_started (STB_GLOBAL)
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
void perf_event_itrace_started(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120ed00)
Location: kernel/events/core.c:8086
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_event_start
  - arch/x86/events/intel/pt.c:pt_config
```
**Symbols:**

```
ffffffff8120ed00-ffffffff8120ed08: perf_event_itrace_started (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void perf_event_itrace_started(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81201ab0)
Location: kernel/events/core.c:8086
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_event_start
  - arch/x86/events/intel/pt.c:pt_config
```
**Symbols:**

```
ffffffff81201ab0-ffffffff81201ab8: perf_event_itrace_started (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void perf_event_itrace_started(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120caa0)
Location: kernel/events/core.c:8086
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_event_start
  - arch/x86/events/intel/pt.c:pt_config
```
**Symbols:**

```
ffffffff8120caa0-ffffffff8120caa8: perf_event_itrace_started (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void perf_event_itrace_started(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8121b920)
Location: kernel/events/core.c:8086
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_event_start
  - arch/x86/events/intel/pt.c:pt_config
```
**Symbols:**

```
ffffffff8121b920-ffffffff8121b928: perf_event_itrace_started (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
