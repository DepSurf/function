# Function: <code>find_var</code>

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
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811a1a9e)
Location: kernel/trace/trace_events_hist.c:1478
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:create_var
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:create_var
```
**Symbols:**

```
ffffffff8119f570-ffffffff8119f5c7: find_var.part.36 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811b0377)
Location: kernel/trace/trace_events_hist.c:1562
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_var
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_var
```
**Symbols:**

```
ffffffff811acbc0-ffffffff811acc17: find_var.part.26 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811bca8e)
Location: kernel/trace/trace_events_hist.c:1716
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_var
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_var
```
**Symbols:**

```
ffffffff811bae90-ffffffff811baee7: find_var.part.0 (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffffffff811c91c0)
Location: kernel/trace/trace_events_hist.c:1790
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_var
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_var
```
**Symbols:**

```
ffffffff811c6470-ffffffff811c64c7: find_var.part.0 (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffffffff811e618e)
Location: kernel/trace/trace_events_hist.c:881
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_var_fields
  - kernel/trace/trace_events_hist.c:create_var_fields
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:create_var
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e3b15)
Location: kernel/trace/trace_events_hist.c:884
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_var_field
  - kernel/trace/trace_events_hist.c:create_var_field
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:create_var
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
In kernel/trace/trace_events_hist.c (ffffffff811e50e9)
Location: kernel/trace/trace_events_hist.c:900
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_var_fields
  - kernel/trace/trace_events_hist.c:create_var_fields
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:create_var
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
In kernel/trace/trace_events_hist.c (ffffffff812151b0)
Location: kernel/trace/trace_events_hist.c:924
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_var_field
  - kernel/trace/trace_events_hist.c:create_var_field
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:create_var
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
In kernel/trace/trace_events_hist.c (ffffffff81252488)
Location: kernel/trace/trace_events_hist.c:1098
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_var_fields
  - kernel/trace/trace_events_hist.c:create_var_fields
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:create_var
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
In kernel/trace/trace_events_hist.c (ffffffff812a19e8)
Location: kernel/trace/trace_events_hist.c:1131
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_var_fields
  - kernel/trace/trace_events_hist.c:create_var_fields
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:create_var
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
In kernel/trace/trace_events_hist.c (ffffffff812bf64a)
Location: kernel/trace/trace_events_hist.c:1128
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_var_fields
  - kernel/trace/trace_events_hist.c:create_var_fields
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:create_var
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
In kernel/trace/trace_events_hist.c (ffffffff812dbc6a)
Location: kernel/trace/trace_events_hist.c:1121
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_var_fields
  - kernel/trace/trace_events_hist.c:create_var_fields
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:create_var
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
In kernel/trace/trace_events_hist.c (ffff8000102484c0)
Location: kernel/trace/trace_events_hist.c:1790
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_var
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_var
```
**Symbols:**

```
ffff8000102468b0-ffff800010246938: find_var.part.0 (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (c0000000002e263c)
Location: kernel/trace/trace_events_hist.c:1790
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_var
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_var
```
**Symbols:**

```
c0000000002da340-c0000000002da3f0: find_var.part.0 (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffffffff811c17e0)
Location: kernel/trace/trace_events_hist.c:1790
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_var
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_var
```
**Symbols:**

```
ffffffff811bea90-ffffffff811beae7: find_var.part.0 (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffffffff811b45c0)
Location: kernel/trace/trace_events_hist.c:1790
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_var
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_var
```
**Symbols:**

```
ffffffff811b1870-ffffffff811b18c7: find_var.part.0 (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffffffff811bf5b0)
Location: kernel/trace/trace_events_hist.c:1790
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_var
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_var
```
**Symbols:**

```
ffffffff811bc860-ffffffff811bc8b7: find_var.part.0 (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffffffff811cd650)
Location: kernel/trace/trace_events_hist.c:1790
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_var
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_var
```
**Symbols:**

```
ffffffff811ca900-ffffffff811ca957: find_var.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
