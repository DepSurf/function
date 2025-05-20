# Function: <code>__perf_event_header_size</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff811798f0)
Location: kernel/events/core.c:1280
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event__header_size
  - kernel/events/core.c:SYSC_perf_event_open
```
**Symbols:**

```
ffffffff811798f0-ffffffff8117993c: __perf_event_header_size.isra.29 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff8118a2f0)
Location: kernel/events/core.c:1533
Inline: True
Direct callers:
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_event__header_size
```
**Symbols:**

```
ffffffff8118a2f0-ffffffff8118a339: __perf_event_header_size.isra.38 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff811996e0)
Location: kernel/events/core.c:1539
Inline: True
Direct callers:
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_event__header_size
```
**Symbols:**

```
ffffffff811996e0-ffffffff81199729: __perf_event_header_size.isra.40 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff811a15d0)
Location: kernel/events/core.c:1552
Inline: True
Direct callers:
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_event__header_size
```
**Symbols:**

```
ffffffff811a15d0-ffffffff811a1619: __perf_event_header_size.isra.32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff811b5140)
Location: kernel/events/core.c:1548
Inline: True
Direct callers:
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_event__header_size
```
**Symbols:**

```
ffffffff811b5140-ffffffff811b5195: __perf_event_header_size.isra.35 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff811d3f70)
Location: kernel/events/core.c:1730
Inline: True
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event__header_size
```
**Symbols:**

```
ffffffff811d3f70-ffffffff811d3fc0: __perf_event_header_size.isra.44 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff811e4610)
Location: kernel/events/core.c:1730
Inline: True
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event__header_size
```
**Symbols:**

```
ffffffff811e4610-ffffffff811e4660: __perf_event_header_size.isra.50 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff811fb920)
Location: kernel/events/core.c:1732
Inline: True
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event__header_size
```
**Symbols:**

```
ffffffff811fb920-ffffffff811fb970: __perf_event_header_size.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff81208ba0)
Location: kernel/events/core.c:1732
Inline: True
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event__header_size
```
**Symbols:**

```
ffffffff81208ba0-ffffffff81208bf0: __perf_event_header_size.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __perf_event_header_size(struct perf_event *event, u64 sample_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812302d0)
Location: kernel/events/core.c:1856
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event__header_size
```
**Symbols:**

```
ffffffff812302d0-ffffffff8123033f: __perf_event_header_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __perf_event_header_size(struct perf_event *event, u64 sample_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81239f10)
Location: kernel/events/core.c:1874
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event__header_size
```
**Symbols:**

```
ffffffff81239f10-ffffffff81239f97: __perf_event_header_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __perf_event_header_size(struct perf_event *event, u64 sample_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123e740)
Location: kernel/events/core.c:1857
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event__header_size
```
**Symbols:**

```
ffffffff8123e740-ffffffff8123e7ca: __perf_event_header_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __perf_event_header_size(struct perf_event *event, u64 sample_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81279220)
Location: kernel/events/core.c:1925
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event__header_size
```
**Symbols:**

```
ffffffff81279220-ffffffff812792aa: __perf_event_header_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __perf_event_header_size(struct perf_event *event, u64 sample_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812cc120)
Location: kernel/events/core.c:1836
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event__header_size
```
**Symbols:**

```
ffffffff812cc120-ffffffff812cc1c2: __perf_event_header_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __perf_event_header_size(struct perf_event *event, u64 sample_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81333bd0)
Location: kernel/events/core.c:1838
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_attach
  - kernel/events/core.c:perf_group_attach
```
**Symbols:**

```
ffffffff81333bd0-ffffffff81333c72: __perf_event_header_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __perf_event_header_size(struct perf_event *event, u64 sample_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81364940)
Location: kernel/events/core.c:1838
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_attach
  - kernel/events/core.c:perf_group_attach
```
**Symbols:**

```
ffffffff81364940-ffffffff813649e2: __perf_event_header_size (STB_LOCAL)
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
In kernel/events/core.c (ffffffff8138d894)
Location: kernel/events/core.c:1852
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event__header_size
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffff8000102923a8)
Location: kernel/events/core.c:1732
Inline: True
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event__header_size
```
**Symbols:**

```
ffff8000102923a8-ffff80001029241c: __perf_event_header_size.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __perf_event_header_size(struct perf_event *event, u64 sample_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04bfdbc)
Location: kernel/events/core.c:1732
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event__header_size
```
**Symbols:**

```
c04bfdbc-c04bfe78: __perf_event_header_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __perf_event_header_size(struct perf_event *event, u64 sample_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c00000000033d730)
Location: kernel/events/core.c:1732
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event__header_size
```
**Symbols:**

```
c00000000033d730-c00000000033d7b0: __perf_event_header_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __perf_event_header_size(struct perf_event *event, u64 sample_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001c31e0)
Location: kernel/events/core.c:1732
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event__header_size
```
**Symbols:**

```
ffffffe0001c31e0-ffffffe0001c3256: __perf_event_header_size (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff812011c0)
Location: kernel/events/core.c:1732
Inline: True
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event__header_size
```
**Symbols:**

```
ffffffff812011c0-ffffffff81201210: __perf_event_header_size.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff811f3f10)
Location: kernel/events/core.c:1732
Inline: True
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event__header_size
```
**Symbols:**

```
ffffffff811f3f10-ffffffff811f3f60: __perf_event_header_size.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff811fef90)
Location: kernel/events/core.c:1732
Inline: True
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event__header_size
```
**Symbols:**

```
ffffffff811fef90-ffffffff811fefe0: __perf_event_header_size.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff8120e020)
Location: kernel/events/core.c:1732
Inline: True
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event__header_size
```
**Symbols:**

```
ffffffff8120e020-ffffffff8120e070: __perf_event_header_size.isra.0 (STB_LOCAL)
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
