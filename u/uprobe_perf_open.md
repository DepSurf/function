# Function: <code>uprobe_perf_open</code>

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
In kernel/trace/trace_uprobe.c (ffffffff811701eb)
Location: kernel/trace/trace_uprobe.c:1059
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
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
In kernel/trace/trace_uprobe.c (ffffffff8117d8ff)
Location: kernel/trace/trace_uprobe.c:1059
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
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
In kernel/trace/trace_uprobe.c (ffffffff8118950f)
Location: kernel/trace/trace_uprobe.c:1059
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
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
In kernel/trace/trace_uprobe.c (ffffffff8118c080)
Location: kernel/trace/trace_uprobe.c:1062
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
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
In kernel/trace/trace_uprobe.c (ffffffff81199b46)
Location: kernel/trace/trace_uprobe.c:1062
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
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
In kernel/trace/trace_uprobe.c (ffffffff811af36a)
Location: kernel/trace/trace_uprobe.c:1045
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
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
In kernel/trace/trace_uprobe.c (ffffffff811bda5f)
Location: kernel/trace/trace_uprobe.c:1047
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
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
In kernel/trace/trace_uprobe.c (ffffffff811cc881)
Location: kernel/trace/trace_uprobe.c:1069
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
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
In kernel/trace/trace_uprobe.c (ffffffff811d8cfb)
Location: kernel/trace/trace_uprobe.c:1282
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int uprobe_perf_open(struct trace_event_call *call, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811f51e0)
Location: kernel/trace/trace_uprobe.c:1282
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
**Symbols:**

```
ffffffff811f51e0-ffffffff811f536c: uprobe_perf_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int uprobe_perf_open(struct trace_event_call *call, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811f3b70)
Location: kernel/trace/trace_uprobe.c:1295
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
**Symbols:**

```
ffffffff811f3b70-ffffffff811f3cfc: uprobe_perf_open (STB_LOCAL)
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
In kernel/trace/trace_uprobe.c (ffffffff811f4fab)
Location: kernel/trace/trace_uprobe.c:1300
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
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
In kernel/trace/trace_uprobe.c (ffffffff81227f8d)
Location: kernel/trace/trace_uprobe.c:1300
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
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
In kernel/trace/trace_uprobe.c (ffffffff81267fff)
Location: kernel/trace/trace_uprobe.c:1291
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
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
In kernel/trace/trace_uprobe.c (ffffffff812ba1af)
Location: kernel/trace/trace_uprobe.c:1297
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
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
In kernel/trace/trace_uprobe.c (ffffffff812dcfcb)
Location: kernel/trace/trace_uprobe.c:1297
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
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
In kernel/trace/trace_uprobe.c (ffffffff812fb0ab)
Location: kernel/trace/trace_uprobe.c:1293
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
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
In kernel/trace/trace_uprobe.c (ffff800010259dd8)
Location: kernel/trace/trace_uprobe.c:1282
Inline: True
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
In kernel/trace/trace_uprobe.c (c048bdf4)
Location: kernel/trace/trace_uprobe.c:1282
Inline: True
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
In kernel/trace/trace_uprobe.c (c0000000002fd654)
Location: kernel/trace/trace_uprobe.c:1282
Inline: True
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
In kernel/trace/trace_uprobe.c (ffffffff811d131b)
Location: kernel/trace/trace_uprobe.c:1282
Inline: True
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
In kernel/trace/trace_uprobe.c (ffffffff811c40eb)
Location: kernel/trace/trace_uprobe.c:1282
Inline: True
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
In kernel/trace/trace_uprobe.c (ffffffff811cf0eb)
Location: kernel/trace/trace_uprobe.c:1282
Inline: True
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
In kernel/trace/trace_uprobe.c (ffffffff811dd37b)
Location: kernel/trace/trace_uprobe.c:1282
Inline: True
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
</ul>
