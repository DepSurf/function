# Function: <code>register_synth_event</code>

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
In kernel/trace/trace_events_hist.c (ffffffff811a419f)
Location: kernel/trace/trace_events_hist.c:872
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
In kernel/trace/trace_events_hist.c (ffffffff811af895)
Location: kernel/trace/trace_events_hist.c:962
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
In kernel/trace/trace_events_hist.c (ffffffff811c09ff)
Location: kernel/trace/trace_events_hist.c:1116
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
In kernel/trace/trace_events_hist.c (ffffffff811cc2af)
Location: kernel/trace/trace_events_hist.c:1186
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int register_synth_event(struct synth_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_synth.c (0)
Location: kernel/trace/trace_events_synth.c:590
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:__create_synth_event
```
**Symbols:**

```
ffffffff811defa0-ffffffff811df128: register_synth_event (STB_LOCAL)
ffffffff811dffe4-ffffffff811e000d: register_synth_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int register_synth_event(struct synth_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_synth.c (0)
Location: kernel/trace/trace_events_synth.c:752
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:__create_synth_event
```
**Symbols:**

```
ffffffff811dc960-ffffffff811dcae8: register_synth_event (STB_LOCAL)
ffffffff81be6323-ffffffff81be634c: register_synth_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int register_synth_event(struct synth_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_synth.c (0)
Location: kernel/trace/trace_events_synth.c:770
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:__create_synth_event
```
**Symbols:**

```
ffffffff811ddaf0-ffffffff811ddcbc: register_synth_event (STB_LOCAL)
ffffffff81bd7fde-ffffffff81bd8007: register_synth_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int register_synth_event(struct synth_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_synth.c (0)
Location: kernel/trace/trace_events_synth.c:770
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:__create_synth_event
```
**Symbols:**

```
ffffffff8120d320-ffffffff8120d4ec: register_synth_event (STB_LOCAL)
ffffffff81cb6d8c-ffffffff81cb6db5: register_synth_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int register_synth_event(struct synth_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_synth.c (0)
Location: kernel/trace/trace_events_synth.c:778
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:__create_synth_event
```
**Symbols:**

```
ffffffff812496a0-ffffffff8124987a: register_synth_event (STB_LOCAL)
ffffffff81e67dd0-ffffffff81e67e01: register_synth_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int register_synth_event(struct synth_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff81297890)
Location: kernel/trace/trace_events_synth.c:789
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:__create_synth_event
```
**Symbols:**

```
ffffffff81297890-ffffffff81297a8a: register_synth_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int register_synth_event(struct synth_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff812b4a00)
Location: kernel/trace/trace_events_synth.c:861
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:__create_synth_event
```
**Symbols:**

```
ffffffff812b4a00-ffffffff812b4bfa: register_synth_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int register_synth_event(struct synth_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff812d10e0)
Location: kernel/trace/trace_events_synth.c:862
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:__create_synth_event
```
**Symbols:**

```
ffffffff812d10e0-ffffffff812d1308: register_synth_event (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffff80001024bfcc)
Location: kernel/trace/trace_events_hist.c:1186
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
In kernel/trace/trace_events_hist.c (c0000000002e72a8)
Location: kernel/trace/trace_events_hist.c:1186
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
In kernel/trace/trace_events_hist.c (ffffffff811c48cf)
Location: kernel/trace/trace_events_hist.c:1186
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
In kernel/trace/trace_events_hist.c (ffffffff811b76af)
Location: kernel/trace/trace_events_hist.c:1186
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
In kernel/trace/trace_events_hist.c (ffffffff811c269f)
Location: kernel/trace/trace_events_hist.c:1186
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
In kernel/trace/trace_events_hist.c (ffffffff811d073f)
Location: kernel/trace/trace_events_hist.c:1186
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
