# Function: <code>track_data_print</code>

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
In kernel/trace/trace_events_hist.c (ffffffff811bd3c0)
Location: kernel/trace/trace_events_hist.c:3693
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
In kernel/trace/trace_events_hist.c (ffffffff811c8760)
Location: kernel/trace/trace_events_hist.c:3810
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
void track_data_print(struct seq_file *m, struct hist_trigger_data *hist_data, struct tracing_map_elt *elt, struct action_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e0570)
Location: kernel/trace/trace_events_hist.c:2906
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_trigger_entry_print
```
**Symbols:**

```
ffffffff811e0570-ffffffff811e066e: track_data_print (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void track_data_print(struct seq_file *m, struct hist_trigger_data *hist_data, struct tracing_map_elt *elt, struct action_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811ddf30)
Location: kernel/trace/trace_events_hist.c:2916
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_trigger_entry_print
```
**Symbols:**

```
ffffffff811ddf30-ffffffff811de02e: track_data_print (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffffffff811e16ad)
Location: kernel/trace/trace_events_hist.c:2980
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:print_entries
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
In kernel/trace/trace_events_hist.c (ffffffff8121177e)
Location: kernel/trace/trace_events_hist.c:3036
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:print_entries
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
In kernel/trace/trace_events_hist.c (ffffffff8124dc9a)
Location: kernel/trace/trace_events_hist.c:3413
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:print_entries
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
In kernel/trace/trace_events_hist.c (ffffffff8129cb8f)
Location: kernel/trace/trace_events_hist.c:3464
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:print_entries
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
In kernel/trace/trace_events_hist.c (ffffffff812ba4bc)
Location: kernel/trace/trace_events_hist.c:3502
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:print_entries
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
In kernel/trace/trace_events_hist.c (ffffffff812d6b0c)
Location: kernel/trace/trace_events_hist.c:3495
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:print_entries
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
In kernel/trace/trace_events_hist.c (ffff800010248ea8)
Location: kernel/trace/trace_events_hist.c:3810
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
In kernel/trace/trace_events_hist.c (c0000000002dd6a0)
Location: kernel/trace/trace_events_hist.c:3810
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
In kernel/trace/trace_events_hist.c (ffffffff811c0d80)
Location: kernel/trace/trace_events_hist.c:3810
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
In kernel/trace/trace_events_hist.c (ffffffff811b3b60)
Location: kernel/trace/trace_events_hist.c:3810
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
In kernel/trace/trace_events_hist.c (ffffffff811beb50)
Location: kernel/trace/trace_events_hist.c:3810
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
In kernel/trace/trace_events_hist.c (ffffffff811ccbf0)
Location: kernel/trace/trace_events_hist.c:3810
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
