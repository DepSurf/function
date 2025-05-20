# Function: <code>pt_config_start</code>

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
In arch/x86/events/intel/pt.c (ffffffff81014100)
Location: arch/x86/events/intel/pt.c:274
Inline: True
Direct callers:
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff81014100-ffffffff81014165: pt_config_start.constprop.10 (STB_LOCAL)
```
</details>
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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void pt_config_start(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff81016a38)
Location: arch/x86/events/intel/pt.c:398
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_config
Direct callers:
  - arch/x86/events/intel/pt.c:pt_event_snapshot_aux
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff81016550-ffffffff810165be: pt_config_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void pt_config_start(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff81016ed8)
Location: arch/x86/events/intel/pt.c:398
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_config
Direct callers:
  - arch/x86/events/intel/pt.c:pt_event_snapshot_aux
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff810169f0-ffffffff81016a5e: pt_config_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pt_config_start(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff81017cd0)
Location: arch/x86/events/intel/pt.c:398
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_event_snapshot_aux
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff81017cd0-ffffffff81017d3e: pt_config_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pt_config_start(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff8101aa50)
Location: arch/x86/events/intel/pt.c:398
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_event_snapshot_aux
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff8101aa50-ffffffff8101aabe: pt_config_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pt_config_start(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff8101d260)
Location: arch/x86/events/intel/pt.c:416
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_event_snapshot_aux
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff8101d260-ffffffff8101d301: pt_config_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pt_config_start(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff81021660)
Location: arch/x86/events/intel/pt.c:416
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_event_snapshot_aux
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff81021660-ffffffff81021701: pt_config_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pt_config_start(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff810213b0)
Location: arch/x86/events/intel/pt.c:416
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_event_snapshot_aux
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff810213b0-ffffffff81021451: pt_config_start (STB_LOCAL)
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
In arch/x86/events/intel/pt.c (ffffffff81027f0b)
Location: arch/x86/events/intel/pt.c:416
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_snapshot_aux
  - arch/x86/events/intel/pt.c:pt_event_start
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
