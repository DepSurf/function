# Function: <code>calc_stack</code>

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
In kernel/trace/trace_events_filter.c (ffffffff81199460)
Location: kernel/trace/trace_events_filter.c:1391
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:process_preds
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
In kernel/trace/trace_events_filter.c (ffffffff811a75d0)
Location: kernel/trace/trace_events_filter.c:1384
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:process_preds
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
In kernel/trace/trace_events_filter.c (ffffffff811b5940)
Location: kernel/trace/trace_events_filter.c:1406
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:process_preds
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
In kernel/trace/trace_events_filter.c (ffffffff811c0fc0)
Location: kernel/trace/trace_events_filter.c:1408
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:process_preds
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int calc_stack(const char *str, int *parens, int *preds, int *err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811d9630)
Location: kernel/trace/trace_events_filter.c:1408
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:process_preds
```
**Symbols:**

```
ffffffff811d9630-ffffffff811d9867: calc_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int calc_stack(const char *str, int *parens, int *preds, int *err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811d6740)
Location: kernel/trace/trace_events_filter.c:1408
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:process_preds
```
**Symbols:**

```
ffffffff811d6740-ffffffff811d698a: calc_stack (STB_LOCAL)
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
In kernel/trace/trace_events_filter.c (ffffffff811d91a8)
Location: kernel/trace/trace_events_filter.c:1408
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:process_preds
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
In kernel/trace/trace_events_filter.c (ffffffff812064b8)
Location: kernel/trace/trace_events_filter.c:1501
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:process_preds
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
In kernel/trace/trace_events_filter.c (ffffffff81241d68)
Location: kernel/trace/trace_events_filter.c:1529
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:process_preds
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
In kernel/trace/trace_events_filter.c (ffffffff8128f708)
Location: kernel/trace/trace_events_filter.c:1626
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:process_preds
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
In kernel/trace/trace_events_filter.c (ffffffff812ac8b8)
Location: kernel/trace/trace_events_filter.c:1717
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:process_preds
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
In kernel/trace/trace_events_filter.c (ffffffff812c8d48)
Location: kernel/trace/trace_events_filter.c:1978
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:process_preds
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
In kernel/trace/trace_events_filter.c (ffff800010240688)
Location: kernel/trace/trace_events_filter.c:1408
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:process_preds
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (c047c064)
Location: kernel/trace/trace_events_filter.c:1408
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:process_preds
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (c0000000002d11d0)
Location: kernel/trace/trace_events_filter.c:1408
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:process_preds
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffe00019590a)
Location: kernel/trace/trace_events_filter.c:1408
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:process_preds
```
</details>
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
In kernel/trace/trace_events_filter.c (ffffffff811b95e0)
Location: kernel/trace/trace_events_filter.c:1408
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:process_preds
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
In kernel/trace/trace_events_filter.c (ffffffff811ac3c0)
Location: kernel/trace/trace_events_filter.c:1408
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:process_preds
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
In kernel/trace/trace_events_filter.c (ffffffff811b73b0)
Location: kernel/trace/trace_events_filter.c:1408
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:process_preds
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
In kernel/trace/trace_events_filter.c (ffffffff811c5450)
Location: kernel/trace/trace_events_filter.c:1408
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:process_preds
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
