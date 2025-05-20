# Function: <code>pt_config_stop</code>

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
void pt_config_stop(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff81012c20)
Location: arch/x86/events/intel/pt.c:414
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff81012c20-ffffffff81012c69: pt_config_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pt_config_stop(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff81012d10)
Location: arch/x86/events/intel/pt.c:435
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff81012d10-ffffffff81012d59: pt_config_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pt_config_stop(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff810112a0)
Location: arch/x86/events/intel/pt.c:509
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff810112a0-ffffffff81011303: pt_config_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pt_config_stop(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff810132b0)
Location: arch/x86/events/intel/pt.c:510
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff810132b0-ffffffff81013313: pt_config_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pt_config_stop(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff810136c0)
Location: arch/x86/events/intel/pt.c:510
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff810136c0-ffffffff81013723: pt_config_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pt_config_stop(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff810140a0)
Location: arch/x86/events/intel/pt.c:518
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff810140a0-ffffffff81014103: pt_config_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pt_config_stop(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff81015590)
Location: arch/x86/events/intel/pt.c:510
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff81015590-ffffffff810155f4: pt_config_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pt_config_stop(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff81015e60)
Location: arch/x86/events/intel/pt.c:510
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff81015e60-ffffffff81015ec4: pt_config_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff81016671)
Location: arch/x86/events/intel/pt.c:522
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_snapshot_aux
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff81016b11)
Location: arch/x86/events/intel/pt.c:522
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_snapshot_aux
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
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
In arch/x86/events/intel/pt.c (ffffffff81017dee)
Location: arch/x86/events/intel/pt.c:522
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_snapshot_aux
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
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
In arch/x86/events/intel/pt.c (ffffffff8101ab78)
Location: arch/x86/events/intel/pt.c:522
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_snapshot_aux
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
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
In arch/x86/events/intel/pt.c (ffffffff8101d3e1)
Location: arch/x86/events/intel/pt.c:540
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_snapshot_aux
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
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
In arch/x86/events/intel/pt.c (ffffffff810217f1)
Location: arch/x86/events/intel/pt.c:540
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_snapshot_aux
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
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
In arch/x86/events/intel/pt.c (ffffffff81021541)
Location: arch/x86/events/intel/pt.c:540
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_snapshot_aux
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
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
In arch/x86/events/intel/pt.c (ffffffff81027ec7)
Location: arch/x86/events/intel/pt.c:540
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_snapshot_aux
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void pt_config_stop(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff81015e60)
Location: arch/x86/events/intel/pt.c:510
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff81015e60-ffffffff81015ec4: pt_config_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pt_config_stop(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff810154a0)
Location: arch/x86/events/intel/pt.c:510
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff810154a0-ffffffff81015519: pt_config_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pt_config_stop(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff81015e20)
Location: arch/x86/events/intel/pt.c:510
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff81015e20-ffffffff81015e84: pt_config_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pt_config_stop(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff81016060)
Location: arch/x86/events/intel/pt.c:510
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff81016060-ffffffff810160c4: pt_config_stop (STB_LOCAL)
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
