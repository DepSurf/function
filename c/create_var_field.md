# Function: <code>create_var_field</code>

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
In kernel/trace/trace_events_hist.c (ffffffff811a19eb)
Location: kernel/trace/trace_events_hist.c:3868
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
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
In kernel/trace/trace_events_hist.c (ffffffff811b02da)
Location: kernel/trace/trace_events_hist.c:3953
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
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
In kernel/trace/trace_events_hist.c (ffffffff811bc9c9)
Location: kernel/trace/trace_events_hist.c:4423
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
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
In kernel/trace/trace_events_hist.c (ffffffff811c9109)
Location: kernel/trace/trace_events_hist.c:4545
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
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
In kernel/trace/trace_events_hist.c (ffffffff811e6106)
Location: kernel/trace/trace_events_hist.c:3647
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_var_fields
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int create_var_field(struct hist_trigger_data *hist_data, unsigned int val_idx, struct trace_event_file *file, char *var_name, char *expr_str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e3af0)
Location: kernel/trace/trace_events_hist.c:3666
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
```
**Symbols:**

```
ffffffff811e3af0-ffffffff811e3cab: create_var_field (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffffffff811e5056)
Location: kernel/trace/trace_events_hist.c:3734
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_var_fields
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int create_var_field(struct hist_trigger_data *hist_data, unsigned int val_idx, struct trace_event_file *file, char *var_name, char *expr_str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:3826
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
```
**Symbols:**

```
ffffffff81215130-ffffffff81215486: create_var_field (STB_LOCAL)
ffffffff81cb70e1-ffffffff81cb70f5: create_var_field.cold (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffffffff812523e1)
Location: kernel/trace/trace_events_hist.c:4203
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_var_fields
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
In kernel/trace/trace_events_hist.c (ffffffff812a1941)
Location: kernel/trace/trace_events_hist.c:4327
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_var_fields
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
In kernel/trace/trace_events_hist.c (ffffffff812bf59f)
Location: kernel/trace/trace_events_hist.c:4403
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_var_fields
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
In kernel/trace/trace_events_hist.c (ffffffff812dbbbf)
Location: kernel/trace/trace_events_hist.c:4396
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_var_fields
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
In kernel/trace/trace_events_hist.c (ffff80001024843c)
Location: kernel/trace/trace_events_hist.c:4545
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
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
In kernel/trace/trace_events_hist.c (c0000000002e262c)
Location: kernel/trace/trace_events_hist.c:4545
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
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
In kernel/trace/trace_events_hist.c (ffffffff811c1729)
Location: kernel/trace/trace_events_hist.c:4545
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
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
In kernel/trace/trace_events_hist.c (ffffffff811b4509)
Location: kernel/trace/trace_events_hist.c:4545
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
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
In kernel/trace/trace_events_hist.c (ffffffff811bf4f9)
Location: kernel/trace/trace_events_hist.c:4545
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
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
In kernel/trace/trace_events_hist.c (ffffffff811cd599)
Location: kernel/trace/trace_events_hist.c:4545
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
