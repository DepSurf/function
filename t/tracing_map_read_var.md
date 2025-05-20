# Function: <code>tracing_map_read_var</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 tracing_map_read_var(struct tracing_map_elt *elt, unsigned int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff811898f0)
Location: kernel/trace/tracing_map.c:111
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_trigger_entry_print
  - kernel/trace/trace_events_hist.c:hist_trigger_entry_print
  - kernel/trace/trace_events_hist.c:onmax_save
  - kernel/trace/trace_events_hist.c:resolve_var_refs
```
**Symbols:**

```
ffffffff811898f0-ffffffff811898fe: tracing_map_read_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 tracing_map_read_var(struct tracing_map_elt *elt, unsigned int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff811971a0)
Location: kernel/trace/tracing_map.c:102
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_trigger_entry_print
  - kernel/trace/trace_events_hist.c:hist_trigger_entry_print
  - kernel/trace/trace_events_hist.c:onmax_save
  - kernel/trace/trace_events_hist.c:resolve_var_refs
```
**Symbols:**

```
ffffffff811971a0-ffffffff811971ae: tracing_map_read_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 tracing_map_read_var(struct tracing_map_elt *elt, unsigned int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff811a53f0)
Location: kernel/trace/tracing_map.c:102
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_events_hist.c:ontrack_action
  - kernel/trace/trace_events_hist.c:cond_snapshot_update
  - kernel/trace/trace_events_hist.c:resolve_var_refs
```
**Symbols:**

```
ffffffff811a53f0-ffffffff811a53fe: tracing_map_read_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 tracing_map_read_var(struct tracing_map_elt *elt, unsigned int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff811b0c20)
Location: kernel/trace/tracing_map.c:102
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_events_hist.c:ontrack_action
  - kernel/trace/trace_events_hist.c:cond_snapshot_update
  - kernel/trace/trace_events_hist.c:resolve_var_refs
```
**Symbols:**

```
ffffffff811b0c20-ffffffff811b0c2e: tracing_map_read_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 tracing_map_read_var(struct tracing_map_elt *elt, unsigned int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff811c93e0)
Location: kernel/trace/tracing_map.c:102
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:ontrack_action
  - kernel/trace/trace_events_hist.c:track_data_print
  - kernel/trace/trace_events_hist.c:track_data_print
  - kernel/trace/trace_events_hist.c:cond_snapshot_update
  - kernel/trace/trace_events_hist.c:resolve_var_refs
```
**Symbols:**

```
ffffffff811c93e0-ffffffff811c93ee: tracing_map_read_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 tracing_map_read_var(struct tracing_map_elt *elt, unsigned int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff811c6aa0)
Location: kernel/trace/tracing_map.c:102
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:ontrack_action
  - kernel/trace/trace_events_hist.c:track_data_print
  - kernel/trace/trace_events_hist.c:track_data_print
  - kernel/trace/trace_events_hist.c:cond_snapshot_update
  - kernel/trace/trace_events_hist.c:resolve_var_refs
```
**Symbols:**

```
ffffffff811c6aa0-ffffffff811c6aae: tracing_map_read_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 tracing_map_read_var(struct tracing_map_elt *elt, unsigned int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff811c7a90)
Location: kernel/trace/tracing_map.c:102
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:print_entries
  - kernel/trace/trace_events_hist.c:print_entries
  - kernel/trace/trace_events_hist.c:ontrack_action
  - kernel/trace/trace_events_hist.c:cond_snapshot_update
  - kernel/trace/trace_events_hist.c:resolve_var_refs
```
**Symbols:**

```
ffffffff811c7a90-ffffffff811c7a9e: tracing_map_read_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 tracing_map_read_var(struct tracing_map_elt *elt, unsigned int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff811f3300)
Location: kernel/trace/tracing_map.c:103
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:print_entries
  - kernel/trace/trace_events_hist.c:print_entries
  - kernel/trace/trace_events_hist.c:ontrack_action
  - kernel/trace/trace_events_hist.c:cond_snapshot_update
  - kernel/trace/trace_events_hist.c:resolve_var_refs
```
**Symbols:**

```
ffffffff811f3300-ffffffff811f330e: tracing_map_read_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 tracing_map_read_var(struct tracing_map_elt *elt, unsigned int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff8122c940)
Location: kernel/trace/tracing_map.c:103
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:print_entries
  - kernel/trace/trace_events_hist.c:print_entries
  - kernel/trace/trace_events_hist.c:ontrack_action
  - kernel/trace/trace_events_hist.c:cond_snapshot_update
  - kernel/trace/trace_events_hist.c:resolve_var_refs
```
**Symbols:**

```
ffffffff8122c940-ffffffff8122c956: tracing_map_read_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 tracing_map_read_var(struct tracing_map_elt *elt, unsigned int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff812784f0)
Location: kernel/trace/tracing_map.c:103
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:print_entries
  - kernel/trace/trace_events_hist.c:print_entries
  - kernel/trace/trace_events_hist.c:ontrack_action
  - kernel/trace/trace_events_hist.c:cond_snapshot_update
  - kernel/trace/trace_events_hist.c:resolve_var_refs
```
**Symbols:**

```
ffffffff812784f0-ffffffff81278506: tracing_map_read_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 tracing_map_read_var(struct tracing_map_elt *elt, unsigned int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff8128ff30)
Location: kernel/trace/tracing_map.c:103
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:print_entries
  - kernel/trace/trace_events_hist.c:print_entries
  - kernel/trace/trace_events_hist.c:ontrack_action
  - kernel/trace/trace_events_hist.c:cond_snapshot_update
  - kernel/trace/trace_events_hist.c:resolve_var_refs
```
**Symbols:**

```
ffffffff8128ff30-ffffffff8128ff46: tracing_map_read_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 tracing_map_read_var(struct tracing_map_elt *elt, unsigned int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff812ab4f0)
Location: kernel/trace/tracing_map.c:103
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:print_entries
  - kernel/trace/trace_events_hist.c:print_entries
  - kernel/trace/trace_events_hist.c:ontrack_action
  - kernel/trace/trace_events_hist.c:cond_snapshot_update
  - kernel/trace/trace_events_hist.c:resolve_var_refs
```
**Symbols:**

```
ffffffff812ab4f0-ffffffff812ab506: tracing_map_read_var (STB_GLOBAL)
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
u64 tracing_map_read_var(struct tracing_map_elt *elt, unsigned int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffff80001022e4c8)
Location: kernel/trace/tracing_map.c:102
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_events_hist.c:ontrack_action
  - kernel/trace/trace_events_hist.c:cond_snapshot_update
  - kernel/trace/trace_events_hist.c:resolve_var_refs
```
**Symbols:**

```
ffff80001022e4c8-ffff80001022e4d8: tracing_map_read_var (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 tracing_map_read_var(struct tracing_map_elt *elt, unsigned int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (c0000000002b7830)
Location: kernel/trace/tracing_map.c:102
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_events_hist.c:ontrack_action
  - kernel/trace/trace_events_hist.c:cond_snapshot_update
  - kernel/trace/trace_events_hist.c:resolve_var_refs
```
**Symbols:**

```
c0000000002b7830-c0000000002b7840: tracing_map_read_var (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
u64 tracing_map_read_var(struct tracing_map_elt *elt, unsigned int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff811a9240)
Location: kernel/trace/tracing_map.c:102
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_events_hist.c:ontrack_action
  - kernel/trace/trace_events_hist.c:cond_snapshot_update
  - kernel/trace/trace_events_hist.c:resolve_var_refs
```
**Symbols:**

```
ffffffff811a9240-ffffffff811a924e: tracing_map_read_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 tracing_map_read_var(struct tracing_map_elt *elt, unsigned int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff8119c1c0)
Location: kernel/trace/tracing_map.c:102
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_events_hist.c:ontrack_action
  - kernel/trace/trace_events_hist.c:cond_snapshot_update
  - kernel/trace/trace_events_hist.c:resolve_var_refs
```
**Symbols:**

```
ffffffff8119c1c0-ffffffff8119c1ce: tracing_map_read_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 tracing_map_read_var(struct tracing_map_elt *elt, unsigned int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff811a7010)
Location: kernel/trace/tracing_map.c:102
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_events_hist.c:ontrack_action
  - kernel/trace/trace_events_hist.c:cond_snapshot_update
  - kernel/trace/trace_events_hist.c:resolve_var_refs
```
**Symbols:**

```
ffffffff811a7010-ffffffff811a701e: tracing_map_read_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 tracing_map_read_var(struct tracing_map_elt *elt, unsigned int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff811b4db0)
Location: kernel/trace/tracing_map.c:102
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_events_hist.c:ontrack_action
  - kernel/trace/trace_events_hist.c:cond_snapshot_update
  - kernel/trace/trace_events_hist.c:resolve_var_refs
```
**Symbols:**

```
ffffffff811b4db0-ffffffff811b4dbe: tracing_map_read_var (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
