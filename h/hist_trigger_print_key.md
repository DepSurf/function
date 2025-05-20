# Function: <code>hist_trigger_print_key</code>

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
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811bcec0)
Location: kernel/trace/trace_events_hist.c:5307
Inline: True
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_events_hist.c:hist_show
```
**Symbols:**

```
ffffffff811bcec0-ffffffff811bd18f: hist_trigger_print_key.isra.0 (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffffffff811c8260)
Location: kernel/trace/trace_events_hist.c:5417
Inline: True
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_events_hist.c:hist_show
```
**Symbols:**

```
ffffffff811c8260-ffffffff811c852f: hist_trigger_print_key.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void hist_trigger_print_key(struct seq_file *m, struct hist_trigger_data *hist_data, void *key, struct tracing_map_elt *elt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e2550)
Location: kernel/trace/trace_events_hist.c:4525
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_trigger_entry_print
  - kernel/trace/trace_events_hist.c:track_data_snapshot_print
```
**Symbols:**

```
ffffffff811e2550-ffffffff811e2820: hist_trigger_print_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void hist_trigger_print_key(struct seq_file *m, struct hist_trigger_data *hist_data, void *key, struct tracing_map_elt *elt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e0170)
Location: kernel/trace/trace_events_hist.c:4566
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_trigger_entry_print
  - kernel/trace/trace_events_hist.c:track_data_snapshot_print
```
**Symbols:**

```
ffffffff811e0170-ffffffff811e0440: hist_trigger_print_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void hist_trigger_print_key(struct seq_file *m, struct hist_trigger_data *hist_data, void *key, struct tracing_map_elt *elt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e1270)
Location: kernel/trace/trace_events_hist.c:4635
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_events_hist.c:print_entries
```
**Symbols:**

```
ffffffff811e1270-ffffffff811e1540: hist_trigger_print_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void hist_trigger_print_key(struct seq_file *m, struct hist_trigger_data *hist_data, void *key, struct tracing_map_elt *elt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812112a0)
Location: kernel/trace/trace_events_hist.c:4733
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_events_hist.c:print_entries
```
**Symbols:**

```
ffffffff812112a0-ffffffff812115de: hist_trigger_print_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void hist_trigger_print_key(struct seq_file *m, struct hist_trigger_data *hist_data, void *key, struct tracing_map_elt *elt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8124d7d0)
Location: kernel/trace/trace_events_hist.c:5111
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_events_hist.c:print_entries
```
**Symbols:**

```
ffffffff8124d7d0-ffffffff8124daf0: hist_trigger_print_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void hist_trigger_print_key(struct seq_file *m, struct hist_trigger_data *hist_data, void *key, struct tracing_map_elt *elt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8129b960)
Location: kernel/trace/trace_events_hist.c:5245
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_events_hist.c:print_entries
```
**Symbols:**

```
ffffffff8129b960-ffffffff8129bc80: hist_trigger_print_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void hist_trigger_print_key(struct seq_file *m, struct hist_trigger_data *hist_data, void *key, struct tracing_map_elt *elt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812b90d0)
Location: kernel/trace/trace_events_hist.c:5343
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_events_hist.c:print_entries
```
**Symbols:**

```
ffffffff812b90d0-ffffffff812b93f0: hist_trigger_print_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void hist_trigger_print_key(struct seq_file *m, struct hist_trigger_data *hist_data, void *key, struct tracing_map_elt *elt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812d5720)
Location: kernel/trace/trace_events_hist.c:5335
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_events_hist.c:print_entries
```
**Symbols:**

```
ffffffff812d5720-ffffffff812d5a40: hist_trigger_print_key (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffff800010248958)
Location: kernel/trace/trace_events_hist.c:5417
Inline: True
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_events_hist.c:hist_show
```
**Symbols:**

```
ffff800010248958-ffff800010248c2c: hist_trigger_print_key.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (c0000000002dcee0)
Location: kernel/trace/trace_events_hist.c:5417
Inline: True
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_events_hist.c:hist_show
```
**Symbols:**

```
c0000000002dcee0-c0000000002dd378: hist_trigger_print_key.isra.0 (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811c0880)
Location: kernel/trace/trace_events_hist.c:5417
Inline: True
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_events_hist.c:hist_show
```
**Symbols:**

```
ffffffff811c0880-ffffffff811c0b4f: hist_trigger_print_key.isra.0 (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffffffff811b3660)
Location: kernel/trace/trace_events_hist.c:5417
Inline: True
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_events_hist.c:hist_show
```
**Symbols:**

```
ffffffff811b3660-ffffffff811b392f: hist_trigger_print_key.isra.0 (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffffffff811be650)
Location: kernel/trace/trace_events_hist.c:5417
Inline: True
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_events_hist.c:hist_show
```
**Symbols:**

```
ffffffff811be650-ffffffff811be91f: hist_trigger_print_key.isra.0 (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffffffff811cc6f0)
Location: kernel/trace/trace_events_hist.c:5417
Inline: True
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_events_hist.c:hist_show
```
**Symbols:**

```
ffffffff811cc6f0-ffffffff811cc9bf: hist_trigger_print_key.isra.0 (STB_LOCAL)
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
