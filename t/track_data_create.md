# Function: <code>track_data_create</code>

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
In kernel/trace/trace_events_hist.c (ffffffff811bf97f)
Location: kernel/trace/trace_events_hist.c:3783
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
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
In kernel/trace/trace_events_hist.c (ffffffff811cb1cf)
Location: kernel/trace/trace_events_hist.c:3900
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int track_data_create(struct hist_trigger_data *hist_data, struct action_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e7eb0)
Location: kernel/trace/trace_events_hist.c:2996
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
**Symbols:**

```
ffffffff811e7eb0-ffffffff811e8084: track_data_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int track_data_create(struct hist_trigger_data *hist_data, struct action_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e58a0)
Location: kernel/trace/trace_events_hist.c:3006
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
**Symbols:**

```
ffffffff811e58a0-ffffffff811e5a74: track_data_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int track_data_create(struct hist_trigger_data *hist_data, struct action_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e6fb0)
Location: kernel/trace/trace_events_hist.c:3072
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
**Symbols:**

```
ffffffff811e6fb0-ffffffff811e7184: track_data_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int track_data_create(struct hist_trigger_data *hist_data, struct action_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812164d0)
Location: kernel/trace/trace_events_hist.c:3128
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
**Symbols:**

```
ffffffff812164d0-ffffffff812166ca: track_data_create (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffffffff8125497d)
Location: kernel/trace/trace_events_hist.c:3505
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_actions
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
In kernel/trace/trace_events_hist.c (ffffffff812a3dfd)
Location: kernel/trace/trace_events_hist.c:3556
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_actions
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
In kernel/trace/trace_events_hist.c (ffffffff812c1cad)
Location: kernel/trace/trace_events_hist.c:3594
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_actions
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
In kernel/trace/trace_events_hist.c (ffffffff812de0ed)
Location: kernel/trace/trace_events_hist.c:3587
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_actions
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
In kernel/trace/trace_events_hist.c (ffff80001024a4f0)
Location: kernel/trace/trace_events_hist.c:3900
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
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
In kernel/trace/trace_events_hist.c (c0000000002e557c)
Location: kernel/trace/trace_events_hist.c:3900
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
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
In kernel/trace/trace_events_hist.c (ffffffff811c37ef)
Location: kernel/trace/trace_events_hist.c:3900
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
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
In kernel/trace/trace_events_hist.c (ffffffff811b65cf)
Location: kernel/trace/trace_events_hist.c:3900
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
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
In kernel/trace/trace_events_hist.c (ffffffff811c15bf)
Location: kernel/trace/trace_events_hist.c:3900
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
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
In kernel/trace/trace_events_hist.c (ffffffff811cf65f)
Location: kernel/trace/trace_events_hist.c:3900
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
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
</ul>
