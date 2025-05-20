# Function: <code>track_data_snapshot_print</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811bd4a7)
Location: kernel/trace/trace_events_hist.c:3652
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
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
In kernel/trace/trace_events_hist.c (ffffffff811c8847)
Location: kernel/trace/trace_events_hist.c:3769
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void track_data_snapshot_print(struct seq_file *m, struct hist_trigger_data *hist_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e2950)
Location: kernel/trace/trace_events_hist.c:2865
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_show
```
**Symbols:**

```
ffffffff811e2950-ffffffff811e2a34: track_data_snapshot_print (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void track_data_snapshot_print(struct seq_file *m, struct hist_trigger_data *hist_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e0570)
Location: kernel/trace/trace_events_hist.c:2875
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_show
```
**Symbols:**

```
ffffffff811e0570-ffffffff811e0654: track_data_snapshot_print (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffffffff811e18ba)
Location: kernel/trace/trace_events_hist.c:2938
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
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
In kernel/trace/trace_events_hist.c (ffffffff81211a3a)
Location: kernel/trace/trace_events_hist.c:2994
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
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
In kernel/trace/trace_events_hist.c (ffffffff8124df48)
Location: kernel/trace/trace_events_hist.c:3371
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
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
In kernel/trace/trace_events_hist.c (ffffffff8129d058)
Location: kernel/trace/trace_events_hist.c:3422
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
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
In kernel/trace/trace_events_hist.c (ffffffff812ba9eb)
Location: kernel/trace/trace_events_hist.c:3460
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
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
In kernel/trace/trace_events_hist.c (ffffffff812d703b)
Location: kernel/trace/trace_events_hist.c:3453
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
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
In kernel/trace/trace_events_hist.c (ffff800010248fa4)
Location: kernel/trace/trace_events_hist.c:3769
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
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
In kernel/trace/trace_events_hist.c (c0000000002dd7c0)
Location: kernel/trace/trace_events_hist.c:3769
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
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
In kernel/trace/trace_events_hist.c (ffffffff811c0e67)
Location: kernel/trace/trace_events_hist.c:3769
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
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
In kernel/trace/trace_events_hist.c (ffffffff811b3c47)
Location: kernel/trace/trace_events_hist.c:3769
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
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
In kernel/trace/trace_events_hist.c (ffffffff811bec37)
Location: kernel/trace/trace_events_hist.c:3769
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
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
In kernel/trace/trace_events_hist.c (ffffffff811cccd7)
Location: kernel/trace/trace_events_hist.c:3769
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
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
