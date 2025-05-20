# Function: <code>walk_pred_tree</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int walk_pred_tree(struct filter_pred *preds, struct filter_pred *root, filter_pred_walkcb_t cb, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff81163070)
Location: kernel/trace/trace_events_filter.c:457
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:filter_match_preds
  - kernel/trace/trace_events_filter.c:replace_preds
  - kernel/trace/trace_events_filter.c:replace_preds
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
```
**Symbols:**

```
ffffffff81163070-ffffffff81163161: walk_pred_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int walk_pred_tree(struct filter_pred *preds, struct filter_pred *root, filter_pred_walkcb_t cb, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff8116d830)
Location: kernel/trace/trace_events_filter.c:457
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:replace_preds
  - kernel/trace/trace_events_filter.c:replace_preds
  - kernel/trace/trace_events_filter.c:filter_match_preds
```
**Symbols:**

```
ffffffff8116d830-ffffffff8116d91f: walk_pred_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int walk_pred_tree(struct filter_pred *preds, struct filter_pred *root, filter_pred_walkcb_t cb, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff81178f00)
Location: kernel/trace/trace_events_filter.c:488
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:replace_preds
  - kernel/trace/trace_events_filter.c:replace_preds
  - kernel/trace/trace_events_filter.c:filter_match_preds
```
**Symbols:**

```
ffffffff81178f00-ffffffff81178fef: walk_pred_tree (STB_LOCAL)
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
In kernel/trace/trace_events_filter.c (ffffffff8117e305)
Location: kernel/trace/trace_events_filter.c:488
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:replace_preds
  - kernel/trace/trace_events_filter.c:replace_preds
  - kernel/trace/trace_events_filter.c:filter_match_preds
Direct callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:replace_preds
  - kernel/trace/trace_events_filter.c:replace_preds
  - kernel/trace/trace_events_filter.c:filter_match_preds
```
**Symbols:**

```
ffffffff8117c100-ffffffff8117c207: walk_pred_tree.part.5 (STB_LOCAL)
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
In kernel/trace/trace_events_filter.c (ffffffff8118bb95)
Location: kernel/trace/trace_events_filter.c:487
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:replace_preds
  - kernel/trace/trace_events_filter.c:replace_preds
  - kernel/trace/trace_events_filter.c:filter_match_preds
Direct callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:replace_preds
  - kernel/trace/trace_events_filter.c:replace_preds
  - kernel/trace/trace_events_filter.c:filter_match_preds
```
**Symbols:**

```
ffffffff81189990-ffffffff81189a9f: walk_pred_tree.part.5 (STB_LOCAL)
```
</details>
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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
