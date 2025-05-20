# Function: <code>find_any_var_ref</code>

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
In kernel/trace/trace_events_hist.c (ffffffff8119d483)
Location: kernel/trace/trace_events_hist.c:1325
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:check_var_refs
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
In kernel/trace/trace_events_hist.c (ffffffff811aa2fe)
Location: kernel/trace/trace_events_hist.c:1396
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:check_var_refs
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
In kernel/trace/trace_events_hist.c (ffffffff811b8409)
Location: kernel/trace/trace_events_hist.c:1550
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:check_var_refs
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
In kernel/trace/trace_events_hist.c (ffffffff811c394a)
Location: kernel/trace/trace_events_hist.c:1624
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:check_var_refs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct hist_field *find_any_var_ref(struct hist_trigger_data *hist_data, unsigned int var_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e0240)
Location: kernel/trace/trace_events_hist.c:715
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:check_var_refs
```
**Symbols:**

```
ffffffff811e0240-ffffffff811e02ba: find_any_var_ref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct hist_field *find_any_var_ref(struct hist_trigger_data *hist_data, unsigned int var_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811ddc00)
Location: kernel/trace/trace_events_hist.c:718
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:check_var_refs
```
**Symbols:**

```
ffffffff811ddc00-ffffffff811ddc7a: find_any_var_ref (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffffffff811df2e9)
Location: kernel/trace/trace_events_hist.c:734
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:check_var_refs
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
In kernel/trace/trace_events_hist.c (ffffffff8120ebb4)
Location: kernel/trace/trace_events_hist.c:758
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:check_var_refs
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
In kernel/trace/trace_events_hist.c (ffffffff8124b484)
Location: kernel/trace/trace_events_hist.c:932
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:check_var_refs
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
In kernel/trace/trace_events_hist.c (ffffffff81299cd4)
Location: kernel/trace/trace_events_hist.c:965
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:check_var_refs
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
In kernel/trace/trace_events_hist.c (ffffffff812b7184)
Location: kernel/trace/trace_events_hist.c:962
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:check_var_refs
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
In kernel/trace/trace_events_hist.c (ffffffff812d37d4)
Location: kernel/trace/trace_events_hist.c:955
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:check_var_refs
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
In kernel/trace/trace_events_hist.c (ffff8000102434a0)
Location: kernel/trace/trace_events_hist.c:1624
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:check_var_refs
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
In kernel/trace/trace_events_hist.c (c0000000002d62c8)
Location: kernel/trace/trace_events_hist.c:1624
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:check_var_refs
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
In kernel/trace/trace_events_hist.c (ffffffff811bbf6a)
Location: kernel/trace/trace_events_hist.c:1624
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:check_var_refs
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
In kernel/trace/trace_events_hist.c (ffffffff811aed4a)
Location: kernel/trace/trace_events_hist.c:1624
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:check_var_refs
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
In kernel/trace/trace_events_hist.c (ffffffff811b9d3a)
Location: kernel/trace/trace_events_hist.c:1624
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:check_var_refs
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
In kernel/trace/trace_events_hist.c (ffffffff811c7dda)
Location: kernel/trace/trace_events_hist.c:1624
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:check_var_refs
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
