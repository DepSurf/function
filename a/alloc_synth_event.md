# Function: <code>alloc_synth_event</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811a40d3)
Location: kernel/trace/trace_events_hist.c:953
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_synth_event
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
In kernel/trace/trace_events_hist.c (ffffffff811af7ce)
Location: kernel/trace/trace_events_hist.c:1043
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
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
In kernel/trace/trace_events_hist.c (ffffffff811c0942)
Location: kernel/trace/trace_events_hist.c:1197
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
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
In kernel/trace/trace_events_hist.c (ffffffff811cc1f2)
Location: kernel/trace/trace_events_hist.c:1267
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct synth_event *alloc_synth_event(const char *name, int n_fields, struct synth_field **fields);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff811df6d0)
Location: kernel/trace/trace_events_synth.c:671
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:__create_synth_event
```
**Symbols:**

```
ffffffff811df6d0-ffffffff811df7c9: alloc_synth_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct synth_event *alloc_synth_event(const char *name, int n_fields, struct synth_field **fields);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff811dce90)
Location: kernel/trace/trace_events_synth.c:834
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:__create_synth_event
```
**Symbols:**

```
ffffffff811dce90-ffffffff811dd02a: alloc_synth_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct synth_event *alloc_synth_event(const char *name, int n_fields, struct synth_field **fields);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff811de0f0)
Location: kernel/trace/trace_events_synth.c:852
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:__create_synth_event
```
**Symbols:**

```
ffffffff811de0f0-ffffffff811de284: alloc_synth_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct synth_event *alloc_synth_event(const char *name, int n_fields, struct synth_field **fields);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_synth.c (0)
Location: kernel/trace/trace_events_synth.c:852
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:__create_synth_event
```
**Symbols:**

```
ffffffff8120d950-ffffffff8120dafb: alloc_synth_event (STB_LOCAL)
ffffffff81cb6e01-ffffffff81cb6e41: alloc_synth_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct synth_event *alloc_synth_event(const char *name, int n_fields, struct synth_field **fields);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_synth.c (0)
Location: kernel/trace/trace_events_synth.c:860
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:__create_synth_event
```
**Symbols:**

```
ffffffff81249960-ffffffff81249b0e: alloc_synth_event (STB_LOCAL)
ffffffff81e67e01-ffffffff81e67e41: alloc_synth_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct synth_event *alloc_synth_event(const char *name, int n_fields, struct synth_field **fields);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_synth.c (0)
Location: kernel/trace/trace_events_synth.c:870
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:__create_synth_event
```
**Symbols:**

```
ffffffff81297c90-ffffffff81297e3e: alloc_synth_event (STB_LOCAL)
ffffffff8205e6d6-ffffffff8205e716: alloc_synth_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct synth_event *alloc_synth_event(const char *name, int n_fields, struct synth_field **fields);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_synth.c (0)
Location: kernel/trace/trace_events_synth.c:942
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:__create_synth_event
```
**Symbols:**

```
ffffffff812b4d00-ffffffff812b4eae: alloc_synth_event (STB_LOCAL)
ffffffff820dd1c5-ffffffff820dd205: alloc_synth_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct synth_event *alloc_synth_event(const char *name, int n_fields, struct synth_field **fields);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_synth.c (0)
Location: kernel/trace/trace_events_synth.c:943
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:__create_synth_event
```
**Symbols:**

```
ffffffff812d1320-ffffffff812d14fd: alloc_synth_event (STB_LOCAL)
ffffffff821b8fc9-ffffffff821b9009: alloc_synth_event.cold (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffff80001024bf24)
Location: kernel/trace/trace_events_hist.c:1267
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (c0000000002e71d8)
Location: kernel/trace/trace_events_hist.c:1267
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In kernel/trace/trace_events_hist.c (ffffffff811c4812)
Location: kernel/trace/trace_events_hist.c:1267
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
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
In kernel/trace/trace_events_hist.c (ffffffff811b75f2)
Location: kernel/trace/trace_events_hist.c:1267
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
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
In kernel/trace/trace_events_hist.c (ffffffff811c25e2)
Location: kernel/trace/trace_events_hist.c:1267
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
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
In kernel/trace/trace_events_hist.c (ffffffff811d0682)
Location: kernel/trace/trace_events_hist.c:1267
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
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
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
