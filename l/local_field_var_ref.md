# Function: <code>local_field_var_ref</code>

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
In kernel/trace/trace_events_hist.c (ffffffff811a064d)
Location: kernel/trace/trace_events_hist.c:2391
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_atom
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
In kernel/trace/trace_events_hist.c (ffffffff811addad)
Location: kernel/trace/trace_events_hist.c:2508
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_atom
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
In kernel/trace/trace_events_hist.c (ffffffff811bbcea)
Location: kernel/trace/trace_events_hist.c:2662
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_atom
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
In kernel/trace/trace_events_hist.c (ffffffff811c753a)
Location: kernel/trace/trace_events_hist.c:2773
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_atom
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
char *local_field_var_ref(struct hist_trigger_data *hist_data, char *system, char *event_name, char *var_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e38e0)
Location: kernel/trace/trace_events_hist.c:1868
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:parse_atom
```
**Symbols:**

```
ffffffff811e38e0-ffffffff811e39fe: local_field_var_ref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
char *local_field_var_ref(struct hist_trigger_data *hist_data, char *system, char *event_name, char *var_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e1200)
Location: kernel/trace/trace_events_hist.c:1878
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:parse_atom
```
**Symbols:**

```
ffffffff811e1200-ffffffff811e131e: local_field_var_ref (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffffffff811e431f)
Location: kernel/trace/trace_events_hist.c:1904
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_atom
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
In kernel/trace/trace_events_hist.c (ffffffff81214893)
Location: kernel/trace/trace_events_hist.c:1938
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_atom
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
In kernel/trace/trace_events_hist.c (ffffffff812514c1)
Location: kernel/trace/trace_events_hist.c:2196
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_atom
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
In kernel/trace/trace_events_hist.c (ffffffff812a07b1)
Location: kernel/trace/trace_events_hist.c:2236
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_atom
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
In kernel/trace/trace_events_hist.c (ffffffff812be5a1)
Location: kernel/trace/trace_events_hist.c:2250
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_atom
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
In kernel/trace/trace_events_hist.c (ffffffff812dac01)
Location: kernel/trace/trace_events_hist.c:2243
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_atom
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
In kernel/trace/trace_events_hist.c (ffff800010247864)
Location: kernel/trace/trace_events_hist.c:2773
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_atom
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
In kernel/trace/trace_events_hist.c (c0000000002e0080)
Location: kernel/trace/trace_events_hist.c:2773
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_atom
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
In kernel/trace/trace_events_hist.c (ffffffff811bfb5a)
Location: kernel/trace/trace_events_hist.c:2773
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_atom
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
In kernel/trace/trace_events_hist.c (ffffffff811b293a)
Location: kernel/trace/trace_events_hist.c:2773
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_atom
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
In kernel/trace/trace_events_hist.c (ffffffff811bd92a)
Location: kernel/trace/trace_events_hist.c:2773
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_atom
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
In kernel/trace/trace_events_hist.c (ffffffff811cb9ca)
Location: kernel/trace/trace_events_hist.c:2773
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_atom
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
